## Homicidios por siniestros viales en la Ciudad Autónoma de Buenos Aires, Argentina
# Introducción

![Imagen de accidentes de transito](https://www.prevencionintegral.com/sites/default/files/styles/ancho440px/public/blog/513858/field_foto/bloghbbenero2022.jpg)

# Introducción 
En este proyecto, se simula el rol de un Data Analyst que forma parte del equipo de analistas de datos de una empresa consultora. El Observatorio de Movilidad y Seguridad Vial (OMSV), bajo la órbita de la Secretaría de Transporte del Gobierno de la Ciudad Autónoma de Buenos Aires (CABA), solicitó la elaboración de un proyecto de análisis de datos.

# Objetivo
El objetivo principal es proporcionar información que permita a las autoridades locales tomar medidas para reducir la cantidad de víctimas fatales de los siniestros viales ocurridos en CABA. Se dispone de un dataset sobre homicidios en siniestros viales en la Ciudad de Buenos Aires durante el periodo 2016-2021.

# Contexto
Los siniestros viales son un problema importante en la Ciudad Autónoma de Buenos Aires debido al alto volumen de tráfico y la densidad poblacional. Estos incidentes pueden tener un impacto significativo en la seguridad de los residentes y visitantes de la ciudad, así como en la infraestructura vial y los servicios de emergencia.

Actualmente, la población de CABA es de aproximadamente 3,120,612 habitantes en una superficie de 200 km², lo que implica una densidad de aproximadamente 15,603 habitantes por km². Además, en julio de 2023 se registraron 12,437,735 vehículos transitando por los peajes de las autopistas de acceso a CABA.

# Datos
Se utilizó una Base de `Homicidios` y `Lesiones` en formato Excel y , que contiene dos pestañas de datos: "HECHOS", que contiene información sobre los incidentes, y "VICTIMAS", que contiene información sobre las víctimas de esos incidentes. 

# Tecnologías utilizadas
Para este proyecto se emplearon Python y Pandas para el procesamiento de datos y el análisis exploratorio. También se realizó web scraping utilizando la librería BeautifulSoup para obtener datos complementarios. Para la visualización de datos, se utilizó Power BI.

# ETL y EDA
Se llevó a cabo un proceso de extracción, transformación y carga de los datos (ETL), seguido de un análisis exploratorio exhaustivo (EDA). Esto permitió identificar patrones que ayudarían a tomar medidas para reducir las víctimas de siniestros viales, se hizo la union vertical de las dos base de datos, `Homicidios` y `Lesiones`, de el cual se obtuvo un total de 28316 filas por 18 columnas, el cual se guardo como `siniestros_viales`. 

# Análisis de los Datos
Se analizó la variable temporal, el perfil de las víctimas, la distribución espacial de los incidentes, entre otros aspectos. Se encontró que el 70% de las víctimas fallecieron durante la semana, con un pico en diciembre. Además, el 77% de las víctimas son hombres, y el 42% de las víctimas viajaban en moto al momento del incidente.

KPI
Se plantearon tres objetivos relacionados con la disminución de las víctimas fatales de siniestros viales, junto con sus indicadores clave de rendimiento (KPI):

* Reducir en un 10% la tasa de homicidios en siniestros viales de los últimos seis meses en CABA.
* Reducir en un 7% la cantidad de accidentes mortales de motociclistas en el último año en CABA.
`Propuesta de KPI`
* Para este KPI se vio el analisis de datos, y obtuvimos que un 41.67% son accidentes en autopista, para esto se propuso e siguiente KPI:
    Reducir en un 10% la cantidad de accidentes mortales en la comuna 1 en el último año, en CABA, respecto al año anterior.
![Imagen de KPIS](https://github.com/katiaMOC/PI2_siniestros_viales_kat/blob/main/Imagenes/kpis.png)

 
# Conclusiones y Recomendaciones
Entre 2016 y 2021 se registraron 741 víctimas fatales en accidentes de tránsito en CABA. Se observó un alto porcentaje de víctimas masculinas para ser exactos 67.33% y una concentración de incidentes en la comuna 1, como tambien se pudo observar que la mayoria de accidentes fatales se dan en las autpistas. Se cumplió con el objetivo de reducir la tasa de homicidios en siniestros viales para el segundo semestre de 2021, pero no se lograron los objetivos de reducción de accidentes mortales de motociclistas ni de la tasa de homicidios en las autopistas para 2021.

Se recomienda continuar monitoreando los objetivos propuestos y reforzar las campañas de seguridad vial, especialmente dirigidas a conductores de motos y usuarios de las avenidas, así como intensificar las campañas durante los fines de semana y en el mes de diciembre. Además, se sugiere dirigir las campañas de seguridad hacia los conductores debido a que son los que tienes finales fatales, tambien constituyen un grupo de alto riesgo.