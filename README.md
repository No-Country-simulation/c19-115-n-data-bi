# c19-115-n-data-bi

# **DataSalud: Exploración de Reseñas de Medicamentos y Análisis de Sentimientos**

# Introducción

El análisis de reseñas de medicamentos es fundamental para comprender la experiencia de los usuarios y evaluar la efectividad y satisfacción de los tratamientos farmacéuticos. Con el auge de plataformas en línea donde los consumidores comparten sus opiniones sobre medicamentos, se ha generado una gran cantidad de datos valiosos que pueden ser explotados para obtener insights significativos.  

En este proyecto, titulado **"DataSalud: Exploración de Reseñas de Medicamentos y Análisis de Sentimientos"**, nos enfocamos en el dataset **"DrugRev: A comprehensive customers reviews on drugs purchasing and satisfaction"**, un conjunto de datos  que recopila reseñas de usuarios sobre una amplia variedad de medicamentos. Este dataset, proveniente de drugs.com y meticulosamente limpiado, contiene 392,510 reseñas únicas que incluyen información sobre el nombre del medicamento, la calificación otorgada por el usuario, la credibilidad de la reseña (medida en "me gusta"), la longitud de la reseña, la afección tratada y el tiempo de uso del medicamento.  

El objetivo principal de este proyecto es analizar las opiniones de los clientes que compraron productos farmacéuticos y establecer un modelo predictivo de la satisfacción y efectos secundarios basado en el análisis del dataset. A través de técnicas de análisis descriptivo y modelado predictivo, buscamos identificar patrones y tendencias en las reseñas de los usuarios, evaluar la distribución de las calificaciones y la credibilidad de las reseñas, y explorar la relación entre estas variables y otras características del dataset.  

Al proporcionar insights valiosos sobre la experiencia del usuario con diferentes medicamentos y afecciones, este análisis puede ayudar a mejorar la toma de decisiones en la industria farmacéutica y contribuir a un mejor entendimiento de la satisfacción del paciente y los posibles efectos secundarios de los tratamientos.  

En las siguientes secciones, detallaremos los pasos metodológicos para el análisis de datos, incluyendo la exploración inicial del dataset, el análisis descriptivo y el modelado predictivo, así como la visualización de resultados y la interpretación de insights clave. 

# Diccionario de datos
Se tiene un total de 9 columnas:  

El diccionario de los datos es:  
    + `MedicineName:` Nombre del medicamento.  
    + `MedicineFor:` para que tipo de condición es la medicina.  
    + `ReviewDate:` Fecha en la que se hizo la reseña.  
    + `UserName:` Nombre del usuario o usuaria.  
    + `IntakeTime:` Periodo de tiempo en el que se tomó la medicina.  
    + `Reviews:` Reseña del usuario o usuaria.  
    + `ReviewLength:` Longitud de la reseña.  
    + `Rating:` calificación que le da el usuario/a al medicamento.    
    + `NumberOfLikes:` Número de likes que recibió el medicamento. 

