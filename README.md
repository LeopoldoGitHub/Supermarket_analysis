# Supermarket_analysis
Este proyecto analiza las ventas de un supermercado, en Brasil, que ofrece ventas online. 
Es un proyecto de estudio en mi formación de DataScience por lo cual está abierto a comentarios para mejorar tanto en limpieza de código cómo mejores prácticas en la resolución de algunas lineas de código.

Cómo está organizado? :
1) La primera etapa importa las librerias y carga el archivo csv. para luego realizar EDA y crear una base de datos limpia llamada: df_ventas_limpio.
2) Seguidamente se indica la sección verificación de limpieza de datos para visualizar que la base de datos esté tratada de manera correcta.
3) Sección de preguntas y respuestas:
   para efectos de entendimiento general, se realizaron las respuestas definiendo una función que englobe los cálculos de todos los resutados que queremos mostrar, para así llamarla cuando la necesitemos.
   Luego , otra sección donde se hacen los mismos cálculos al detalle por línea, llamado Desarrollo, para poder apreciar cómo se llegó a resolver cada cálculo. Esta sección puede ser ejecutada o no. Si se aplica la función o esta
   sección generará los mismos resultados.
   Sección Visualización, es toda la configuración para realizar gráficos asociados a cada pregunta y se ejecuta por separado.

Espero que aprecien este proyecto con la asesoría de @ElProfeAlejo y su gran iniciativa para la enseñanza de la ciencia de datos.

#Una cadena de Supermercados Online que opera en Brasil quiere obtener insights sobre la venta de sus productos. Para hacer esto, usted, como científico de datos, deberá analizar los pedidos de sus clientes y mostrar gráficamente las respuestas de las siguientes preguntas de negocio:

### **Preguntas**

#**Pregunta 1: ¿Cuáles son las ventas totales por año? ¿Y qué año tuvo mejor desempeño?**
![image](https://github.com/LeopoldoGitHub/Supermarket_analysis/assets/122738840/8b61d9a5-0243-4163-83d6-70313ef4109b)

El porcentaje de ganancia ha ido incrementando desde el 2019 hasta el 2022 para un aumento global de 73,4%, teniendo el año 2022 con el mejor rendimiento en cuanto a ganancias.
Se observa un crecimiento interanual de 13,1% en el 2020, 29,0% en el 2021 y 18,9% en el 2022 infiriendo un efecto pospandemia en el uso de las compras online para los consumidores en el año 2021.
Se recomendó al cliente mejorar la oferta en cantidad de productos , ya que la tendencia es al crecimiento sostenido de los pedidos y las ventas en el negocio global.
Para determinar que productos podemos potenciar de acuerdo a sus ventas pasaremos a la siguiente pregunta.

2. ¿Cuáles son los 7 productos que más ganancias mostraron durante todo el período?

![image](https://github.com/LeopoldoGitHub/Supermarket_analysis/assets/122738840/a7da7399-33f2-4d4c-ad7d-95f1aed81e29)

Se pudo determinar que existen 4 productos electrónicos que generan las mayores ganancias en el negocio(Lámparas LED,Laptops, Cámaras digitales y smartphones), seguido de los Jeans, y de productos de limpieza(Bolsas de basura y detergente para ropas).
Estos productos aunque generan la mayor cantidad de ganancia , contrastan  con los productos más pedidos mostrados a continuación: 
![image](https://github.com/LeopoldoGitHub/Supermarket_analysis/assets/122738840/f0496e4c-876d-4a73-9cc0-1678ba069adb)

De los 10 productos con mayor cantidad de pedidos, sólo 5 estan dentro de los que generan mayor ganancias. 
De este análisis hemos recomendado a nuestro cliente que puede potenciar con campaña de marketing, mejora en la calidad de materiales y ampliación en la variedad de los otros 5 productos mas pedidos que no generan el mismo porcentaje de ganancia(limpiador de inodoros, vestidos, papel higiénico, ambientador en spray y toallitas desinfectantes).
Si se realizan las mejoras sugeridas se puede incrementar significativamente el procetaje de ganancias de estos productos debido al volumen de pedidos que se reciben.

Profundizando en los datos , determinaremos en que zonas se realizan las mayores ventas contestando lo siguiente:
3. Si separamos las ventas totales por año y por regiones ¿Qué insight podemos obtener de nuestras ventas?


![image](https://github.com/LeopoldoGitHub/Supermarket_analysis/assets/122738840/27d8ac78-6ee0-4416-bf26-731b7bec5d2b)

4. ¿Cuál es el método de envío más utilizado por los clientes del Supermercado? ¿Es proporcional para B2B y B2C?

5. ¿Cuáles son las ventas totales por trimestre en el estado de São Paulo?

6. ¿Existe otro insight que puedas proporcionar?
