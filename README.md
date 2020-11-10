# Kavak



Prueba técnica Tableau para el puesto de Data Analyst.

La prueba consiste en :

  - Limpieza y transformación de los datos

  - Crear gráficas con información relevante

  - Explicar la información relevante por medio de un dashboard en Tableau

# Limpieza y transformación de los datos

Librerías usadas:
  * Pandas - Manipulacion y analisis de datos

```sh
$ pip install pandas
```
 Objetivo

> El objetivo de este punto
> es crear columnas con el Stock ID de los autos
> en cada una de las tablas de Excel,
para despues poderlas unir (Joins) en Tableau.

El desarrollo esta hecho en un jupyter notebook, el objetivo se logro usando pandas y se reescribio 
cada una de las hojas de Excel en un Excel nuevo.


### Tableau

 Objetivo

> Crear gráficas con información relevante
Explicar la información relevante por medio de un dashboard en Tableau

* Tableau - es una heramienta BI (Business Intelligence) para hacer visualizaciones y crear dashboards.


### Dashboards



● Con los 3 datasets disponibles cree un dashboards de compra/venta de los autos de Enero 2017 a Mayo 2017

● El dashboard contiene Precio de compra que es la Suma de todas la compras hechas en el periodo (la inversion inicial con IVA)

● Ventas con Iva es la Suma de todas las ventas hechas en el periodo

● Ganancia es la cantidad en millones de pesos mxn que obtuvimos de ganancia en ese periodo

● ROI es nuestro Retorno de Inversion de ese periodo (SUM(ventas)-SUM(compras))/SUM(compras)

● Existen 4 graficos 

![Comparacion](https://github.com/DavidCis/Prueba_Kavak/blob/main/Tableau/grafico1.png)
![Marca](https://github.com/DavidCis/Prueba_Kavak/blob/main/Tableau/grafico2.png)
![Ubicacion](https://github.com/DavidCis/Prueba_Kavak/blob/main/Tableau/grafico3.png)
![Cnatidad](https://github.com/DavidCis/Prueba_Kavak/blob/main/Tableau/grafico4.png)

● Todos los graficos son interctivos entre si y se puede filtrar por cada uno de ellos

![comp](https://github.com/DavidCis/Prueba_Kavak/blob/main/Tableau/completo.png)
![marca](https://github.com/DavidCis/Prueba_Kavak/blob/main/Tableau/marca.png)
![ubi](https://github.com/DavidCis/Prueba_Kavak/blob/main/Tableau/precio.png)
![hist](https://github.com/DavidCis/Prueba_Kavak/blob/main/Tableau/ubicacion.png)

* En periodo de Marzo 2017 tuvimos nuestra ganancia mas alta con mas de 9M de pesos mxn.
* Filtrando por la ubicacion de Florencia tambien tenemos una ganancia de 9M de pesos mxn.
* Notamos una tendencia en la cantidad de autos vendidos por precio, se venden mas autos en un rango de precio entre 100mil pesos mxn a 300mil pesos mxn .
* Se vendieron 791 autos entre esa cantidad de precio de los 1100 autos vendidos en ese periodo. (71.9% del total)
* Top 3 de marcas mas vendidas son BMW, Audi y Mazda.
* Nuestro top 3 de marcas mas vendidas son Mazda, Nissan y Audi en el rango de 100k a 300k pesos mxn.
* Tenemos un total de 33M de pesos mxn de ganancia en el periodo,que se traduce a un 13.38% de ROI.

### Informacion Personal

Dejo mis datos de contacto para cualquier pregunta o aclaracion con la prueba.

| Media | Link |
| ------ | ------ |
| Linkedin | https://www.linkedin.com/in/david-cisneros123/ |
| GitHub | https://github.com/DavidCis |
| Celular | 5543924144 |


**David Alfredo Cisneros Diaz**
