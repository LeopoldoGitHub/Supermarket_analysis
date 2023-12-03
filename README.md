# Supermarket_analysis
Este proyecto analiza las ventas de un supermercado, en Brasil, que ofrece ventas online. 
Es un proyecto de estudio en mi formación de DataScience por lo cual está abierto a comentarios para mejorar tanto en limpieza de código cómo mejores prácticas en la resolución de algunas lineas de código.

Cómo está organizado? :
1) La primera etapa importa las librerias y carga el archivo csv. para luego realizar EDA y crear una base de datos limpia llamada: df_ventas_limpio.
2) Seguidamente se indica la sección verificación de limpieza de datos para visualizar que la base de datos esté tratada de manera correcta.
3) Sección de preguntas y respuestas:
   para efectos de entendimiento general, se realizaron las respuestas definiendo una función que englobe los cálculos de todos los resultados que queremos mostrar, para así llamarla cuando la necesitemos.
   Luego , otra sección donde se hacen los mismos cálculos al detalle por línea, llamado Desarrollo, para poder apreciar cómo se llegó a resolver cada cálculo. Esta sección puede ser ejecutada o no. Si se aplica la función o esta
   sección generará los mismos resultados.
   Sección Visualización, es toda la configuración para realizar gráficos asociados a cada pregunta y se ejecuta por separado.

Espero que aprecien este proyecto con la asesoría de @ElProfeAlejo y su gran iniciativa para la enseñanza de la ciencia de datos.

#**Una cadena de Supermercados Online que opera en Brasil quiere obtener insights sobre la venta de sus productos. Para hacer esto, usted, como científico de datos, deberá analizar los pedidos de sus clientes y mostrar gráficamente las respuestas de las siguientes preguntas de negocio**:

### **Preguntas**

#**Pregunta 1: ¿Cuáles son las ventas totales por año? ¿Y qué año tuvo mejor desempeño?**
![image](https://github.com/LeopoldoGitHub/Supermarket_analysis/assets/122738840/8b61d9a5-0243-4163-83d6-70313ef4109b)

El porcentaje de ganancia ha ido incrementando desde el 2019 hasta el 2022 para un aumento global de 73,4%, teniendo el año 2022 con el mejor rendimiento en cuanto a ganancias.
Se observa un crecimiento interanual de 13,1% en el 2020, 29,0% en el 2021 y 18,9% en el 2022 infiriendo un efecto postpandemia en el uso de las compras online para los consumidores en el año 2021.
Se recomendó al cliente mejorar la oferta en cantidad de productos , ya que la tendencia es al crecimiento sostenido de los pedidos y las ventas en el negocio global.
Para determinar que productos podemos potenciar de acuerdo a sus ventas pasaremos a la siguiente pregunta.

2. ¿Cuáles son los 7 productos que más ganancias mostraron durante todo el período?

Se pudo determinar que existen 4 productos electrónicos que generan las mayores ganancias en el negocio(Lámparas LED,Laptops, Cámaras digitales y smartphones), seguido de los Jeans, y de productos de limpieza(Bolsas de basura y detergente para ropas).

![image](https://github.com/LeopoldoGitHub/Supermarket_analysis/assets/122738840/db69cb5b-8fbd-416a-9254-2f5515a908f5)
Estos productos aunque generan la mayor cantidad de ganancia , contrastan  con los productos más pedidos mostrados a continuación: 

![image](https://github.com/LeopoldoGitHub/Supermarket_analysis/assets/122738840/ce5af736-7718-43d5-b8dd-bdf347c69c97)


De los 10 productos con mayor cantidad de pedidos, sólo 5 estan dentro de los que generan mayor ganancias. 
De este análisis hemos recomendado a nuestro cliente que puede potenciar con campaña de marketing, mejora en la calidad de materiales y ampliación en la variedad de los otros 5 productos mas pedidos que no generan el mismo porcentaje de ganancia(limpiador de inodoros, vestidos, papel higiénico, ambientador en spray y toallitas desinfectantes).
Si se realizan las mejoras sugeridas se puede incrementar significativamente el porcentaje de ganancias de estos productos debido al volumen de pedidos que se reciben.

Profundizando en los datos , determinaremos en que zonas se realizan las mayores ventas contestando lo siguiente:
3. Si separamos las ventas totales por año y por regiones ¿Qué insight podemos obtener de nuestras ventas?

![image](https://github.com/LeopoldoGitHub/Supermarket_analysis/assets/122738840/27d8ac78-6ee0-4416-bf26-731b7bec5d2b)

Desde el 2019 se puede ver que las regiones Sureste, Noreste y Centro-Oeste, concentran el 88,17% de las ventas. Esto principalmente a que concentran ciudades con mayor número de población lo que impacta directamente en el vólumen de pedidos y ventas. Dado este análisis podemos verificar cuales son los productos más pedidos en el último año de estudio(2022) en la región Sureste:

![image](https://github.com/LeopoldoGitHub/Supermarket_analysis/assets/122738840/502cabec-0494-484b-b3a4-61733f43ca2d)

En la gráfica se puede observar que los 3 productos más pedidos son bolsas de basura, lámparas LED y limpiador de inodoros, lo que refleja el impacto de esta región y su cantidad de pedidos con dos de los productos de mayor ganancia, y un producto que aplicando las recomendaciones , puede incrementar su margen de ganancia e impactando significativamente en un crecimiento de las ventas.

4. ¿Cuál es el método de envío más utilizado por los clientes del Supermercado? ¿Es proporcional para B2B y B2C?

![image](https://github.com/LeopoldoGitHub/Supermarket_analysis/assets/122738840/8c39379f-c8eb-4e58-a436-e2e72aa375fa)

Es importante ver la logística de envío en una tienda que vende  productos online, y en la gráfica se observa que el método de envío para Brasil y las regiones de influencia, la entrega estandar es el método preferido de los consumidores con un 59.1% con respecto a los otros métodos. Aun asi, los segmentos B2B y B2C estan equilibrados para cada método en las zonas estudiadas.


5. ¿Cuáles son las ventas totales por trimestre en el estado de São Paulo?

![image](https://github.com/LeopoldoGitHub/Supermarket_analysis/assets/122738840/1432a594-191d-4ae0-8282-6d0c4815c8c2)

Si vamos un poco mas profundo en el análisis y vemos solamente las ventas del estado  de São Paulo, podemos observar que las ventas aumentan considerablemente desde el 2019 hasta el 2022 , con un aumento diferencial en los últimos trimestres de de cada año influenciado por las fiestas navideñas y el aumento del consumo generalizado para esas fechas.

6. Margen de ganancia por producto

![image](https://github.com/LeopoldoGitHub/Supermarket_analysis/assets/122738840/071d6288-3b1c-470b-92ee-3c02ddcdd73d)

Para saber cuales son los productos que tienen mejor rentabilidad , podemos verificar en la gráfica que Los productos con mayor porcentaje de ganancia son las camisetas, Jeans, papel higiénico y zapatillas.
Esto quiere decir que aunque no generen las mayores ganancias, son productos rentables individualmente y que es productivo mantenerlos en el stock de la empresa para optimizar la estrategia y aumentar el volumen de ventas.
