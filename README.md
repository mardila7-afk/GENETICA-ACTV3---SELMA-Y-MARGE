# GENETICA-ACTV3---SELMA-Y-MARGE
 A partir de una muestra de raspado bucal de varios miembros de la familia Simpson y otros familiares, se realiza un análisis de exoma completo en busca de las patologías hereditarias que pudieran padecer. El laboratorio envía los archivos .vcf y el genetista debe realizar la anotación de variantes para encontrar las mutaciones.


INTRODUCTION
La interpretación de variantes en individuos relacionados proporciona un contexto crítico para distinguir la herencia patogénica de la variación benigna. Aquí presentamos un análisis comparativo mediante el Predictor de Efecto de Variantes (VEP) de dos mujeres emparentadas, Marge y Selma, identificadas como portadoras de variantes en los genes LEPR y MED12 mediante secuenciación de exoma completo alineada con el genoma de referencia humano (GRCh38).



METHODOLOGY 

Se realizó la secuenciación del exoma completo de dos mujeres emparentadas (Marge y Selma) en la plataforma Illumina, con lecturas alineadas a GRCh38 mediante BWA-MEM. Las variantes se identificaron de forma independiente para cada individuo utilizando BCFtools mpileup con anotación de profundidad alélica. Ambos archivos VCF fueron anotados utilizando Ensembl Variant Effect Predictor (VEP) a través de Galaxy, consultando las bases de datos COSMIC y dbSNP, junto con predicciones in silico de patogenicidad mediante SIFT y PolyPhen-2. La cigosidad se determinó a partir de las proporciones de profundidad alélica y del contexto cromosómico, aplicando una interpretación sensible al sexo para el locus MED12 ligado al cromosoma X. Se realizó un análisis comparativo mediante scripts personalizados de Python para identificar variantes compartidas frente a variantes privadas, evaluar patrones de herencia y caracterizar la heterocigosidad compuesta en LEPR.




DISCUSSION
Las variantes identificadas en Marge como en Selma se consideran patogénicas basándose en sus consecuencias funcionales y en las asociaciones con enfermedades mencionadas. La variante de “frameshift” cambio de nucleótido, en el gen LEPR altera el dominio de señalización intracelular del receptor de leptina, anulando la señalización de saciedad mediada por las vías JAK2/STAT3 y PI3K/AKT, y predisponiendo a obesidad grave de inicio temprano. Ambas personas son heterocigotas para esta variante, lo cual es consistente con la condición de herencia autosómica recesiva. Selma presenta una segunda variante en el sitio aceptor de splice acceptor del gen LEPR en el alelo opuesto, lo que establece una heterocigosidad compuesta y una pérdida de función alélica, suficiente para producir el fenotipo completo de deficiencia de *LEPR*. La variante de cambio de aminoácido, deleción, en el gen MED12, heterocigoto en ambas mujeres en el cromosoma X, alterando la regulación transcripcional en el músculo uterino, causante de los fibromas uterinos. En conjunto, estos hallazgos respaldan una clasificación patogénica para ambos loci; Selma presenta un riesgo clínico significativamente mayor debido a su genotipo de heterocigosidad compuesta en LEPR, las dos requieren vigilancia ginecológica dada su variante compartida en MED12.


CONCLUSIONES
El análisis comparativo del VEP identificó tres variantes patogénicas en dos mujeres emparentadas con implicaciones clínicas distintas. Tanto Marge como Selma son portadoras de alelos heterocigotos con pérdida de función en el gen LEPR y de una variante de cambio de aminoácido heterocigota en el gen MED12 en el cromosoma X, lo que aumenta el riesgo de  fibromas uterinos debido a una alteración en la señalización del complejo Mediator. Estos resultados resaltan el valor diagnóstico de la comparación de variantes a nivel familiar para determinar la cigocidad y aclarar los patrones de herencia y mejorar la interpretación clínica. 
<img width="4934" height="39" alt="image" src="https://github.com/user-attachments/assets/106664da-f8d6-46af-bfdc-e505650dd472" />
