# Graficas-de-barras-con-intervalos-de-confianza

La forma más indicada de interpretar gráficas de barras es a través de intervalos de confianza. Por ejemplo, se toma la cantidad de ingresos anuales de 100 personas. Se le 
calcula la media a esas 100 personas y así sabremos cuanto ganan en promedio esas 100 personas al año. Sin embargo, pueden existir pocas personas que tengan ingresos muy grandes 
y así la media de ingresos anuales puede subir de forma exgerada, mintiendonos acerca de los ingresos anuales de esas 100 personas. Esto se le conoce como los "outliers" porque 
son datos que están muy alejados de la media y producen un sesgo en los resultados.

Al momento de graficar con barras ocurre el problema heredado por la interpretación erronea de la media, este problema se puede solucionar si aplicamos los intervalos de 
confianza. En las distribuciones normales tenemos la media y la desviación estándar de una muestra, la desviación estándar nos dice que tanto están variando los datos en la
muestra. A partir de esta desviación estándar junto con la media podemos crear intervalos de confianza donde la mitad del intervalo es la media.

Este mismo concepto lo podemos observar en una gráfica de barras donde en el eje x pondremos los ingresos anuales y en el eje y, la media de ingresos en ese año. Como se graficó
la media de ingresos por año, entonces la altura de la barra será la media y por lo tanto la altura de la barra será la mitad del intervalo de confianza. Entre mayor sea la 
desviación estándar, mayor será el intervalo.

Ahora, para saber si un dato fijo de los 100 de nuestro ejemplo está por fuera o no del intervalo de confianza aplicaremos un color claro si está adentro y de manera opuesta, un 
color oscuro si esta afuera. Si el dato fijo está por encima de la media aplicaremos el color rojo y si está por debajo de la media aplicaremos un color azul. Finalmente si el dato fijo está cercano a la media será de color gris. Usar colores de distintos tonos en nuestras barras facilitará la visualización.

Para comprender de forma correcta lo que acabo de mencionar, puedes observar el código en Python con Jupyter Notebook que subí.
