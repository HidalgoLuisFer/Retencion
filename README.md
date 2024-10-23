Este trabajo se enfoca en la retención de empleados, un tema crucial para cualquier empresa, ya que la salida de personal (Desercion) puede generar altos costos y dificultades para reemplazar talento y experiencia.

Utilizando datos de IBM, primero se realizará la  extracción, transformación y carga cuaderno IBM_ETL.ipynb (ETL).
Se realizará un análisis exploratorio de datos en Python que incluya:

1. Carga e inspeccion del dataset.
2. Visualización de las columnas.
3. Detección y manejo de valores nulos.
4. Detección y manejo de registros duplicados.
5. Resumen estadístico de las Columnas Numéricas.
6. Transformacion de datos.
7. Exportar CSV Limpio IBM_DATOS_LIMPIOS.

En el cuaderno IBM_EDA.ipynb se enfoca en la **retención de empleados**, un aspecto fundamental para cualquier empresa, ya que la rotación de personal (desgaste) puede generar altos costos y desafíos para reemplazar talento y experiencia. Utilizando un conjunto de datos de **IBM**, se llevará a cabo un **análisis exploratorio de datos (EDA)** y un proceso de **preprocesamiento** para preparar los datos para análisis más avanzados.

Durante el EDA, se explorarán las principales características del conjunto de datos:

1.  Se importará  archivo de datos con infooramcion limpia y transformada
2.  Se Visualizaran las relaciones entre Variables
3.  Análisis de Interacciones
4.  Diagramas de Caja para Variables Categóricas

Conclusiones:

El análisis del conjunto de información revela varias conclusiones clave sobre la relación entre diferentes aspectos laborales y la deserción de empleados:

1. **Satisfacción y cargos**: Las personas más jóvenes, a pesar de ocupar cargos más altos, tienden a estar menos satisfechas con su trabajo. Esto sugiere que la edad y el nivel de satisfacción pueden estar inversamente relacionados, aunque no de forma lineal.

2. **Tiempo en la empresa y promociones**: Los empleados que llevan más tiempo en la empresa suelen haber permanecido en el mismo puesto durante largos períodos y haber sido promovidos hace más tiempo, lo que puede influir en su percepción de las oportunidades de crecimiento.

3. **Ingresos y desempeño**: Aquellos empleados que han recibido mejores evaluaciones y aumentos salariales tienden a tener ingresos más altos. Esto indica que el desempeño y la recompensa están estrechamente conectados.

4. **Variabilidad de ingresos**: Existe una gran variabilidad en los ingresos, donde los roles de mayor responsabilidad, como Gerente y Director de Investigación, tienen los salarios más altos, mientras que los roles de Técnico de Laboratorio y Representante de Ventas reciben los salarios más bajos. Los valores atípicos en ciertos roles sugieren que factores como la antigüedad o las bonificaciones especiales pueden generar diferencias salariales significativas.

5. **Deserción**: Aunque la mayoría de los empleados no han desertado, las tasas de deserción son ligeramente más altas entre los grupos de edad más jóvenes y los más mayores. Los primeros podrían estar en búsqueda de nuevas oportunidades, mientras que los segundos podrían estar más cerca de la jubilación. Además, las personas con menos años en la empresa muestran una mayor tendencia a desertar.

6. **Factores relacionados con el crecimiento**: Variables como el nivel de trabajo, el porcentaje de aumento salarial y la evaluación de desempeño parecen estar ligadas a las oportunidades de desarrollo dentro de la empresa. Una baja percepción de estas oportunidades podría incrementar la probabilidad de deserción.

7. **Encuestas y satisfacción laboral**: Los resultados de encuestas sobre participación, balance de vida laboral y satisfacción muestran que las tasas de deserción son más altas cuando los empleados otorgan puntuaciones más bajas a estos aspectos.

8. **Brecha salarial de género**: Existe una brecha salarial de género persistente, donde las mujeres que no desertan ganan significativamente más que los hombres en la misma condición. Este patrón sugiere una desigualdad salarial que prevalece, incluso considerando la deserción.

9. **Impacto de la deserción en los ingresos**: Tanto en hombres como en mujeres, la deserción se asocia con una caída considerable en los ingresos mensuales, lo que evidencia el impacto financiero negativo de dejar la empresa.

En resumen, los factores que influyen en la deserción son diversos, desde la antigüedad y el nivel de satisfacción hasta las oportunidades de crecimiento y las desigualdades salariales. Identificar estos patrones puede ser clave para desarrollar estrategias de retención más efectivas.

   

