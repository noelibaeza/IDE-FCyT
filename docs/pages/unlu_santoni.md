

*Laura Santoni1,2, Pamela Zamboni1, Fernando Tentor1 y Walter Sione1,3*

1Universidad Autónoma de Entre Ríos. Facultad de Ciencia y Tecnología. Centro Regional de Geomática

(CeReGeo-FCyT-UADER). Ruta 11 km 10.5 Oro Verde, Entre Ríos, Argentina.

2Universidad Autónoma de Entre Ríos. Facultad de Ciencia y Tecnología. CONICET. Ruta 11 km 10.5 Oro

Verde, Entre Ríos, Argentina.

3PRODITEL. Universidad Nacional de Luján. Cruce rutas 5 y Ex 7 CP 6700 Lujan, Buenos Aires, Argentina

Email: <lauracsantoni@gmail.com>





En el marco de:

**PROYECTO DE DOCTORADO EN CIENCIAS**

**AGRARIAS:**

**Análisis del cambio de uso del suelo en socioecosistemas del**

**Espinal entrerriano en un contexto de cambio climático:**

**perspectivas desde la geomática ambiental**

**Estudiante**: Lic. Laura Santoni

**Directora:** D r. Pamela Zamboni (Universidad Autónoma de Entre Ríos)

**Co-Director:** D r. Miguel Lovino (Universidad Nacional del Litoral)

***LÍNEA DE INVESTIGACIÓN O ÁREA DE ESPECIALIZACIÓN:***

La investigación pertenece al área de las ciencias ambientales y agrarias, con aplicación en problemas

de conservación y sustentabilidad, en especial vinculados a cambios en el uso del suelo y

Ordenamiento Ambiental Territorial, mediante aplicaciones de geomática en sistemas

agroproductivos en el espinal de la Provincia de Entre Ríos.





INTRODUCCIÓN:

El **desarrollo sustentable** de

la región requiere de un

**Ordenamiento Territorial**

que minimice el deterioro de

los recursos naturales y

permita el crecimiento

económico.

El espinal

entrerriano

**Bosques nativos**

**Avance de la frontera agropecuaria**

✓ El estudio de los cambios en el

uso de suelo y el análisis de

series temporales son enfoques

útiles en esta tarea.

✓ Existen muchas herramientas

que podrían utilizarse.

(LANDTREND/Trend Earth)

**OBJETIVO:** Estudiar la aplicabilidad de LandTrendr como herramienta para

ubicar espacio-temporalmente los cambios en la cobertura del suelo

(deforestaciones) en la cuenca Feliciano durante el período 1984-2020.





METODOLOGÍA:

Área de estudio: Cuenca del arroyo Feliciano

Fuente:

<https://www.hidraulica.gob.ar/cuencas.php>

Unidades de vegetación

Oyarzábal *et al.* 2018





Análisis de Serie Temporal

• Conjunto de algoritmos de segmentación espectral y

temporal.

LT-GEE

• Detección de cambios: cuenta la historia del píxel.

• Diseñado para detectar disturbios en bosques boreales.

36 escenas – 1 por año

Datos NDVI

Misión

Landsat

Cohen *et al.* 2010

Kennedy *et al.* 2010; 2012; 2018

Fuente:

[https://emapr.github.io/LT-](https://emapr.github.io/LT-GEE/landtrendr.html)

[GEE/landtrendr.html](https://emapr.github.io/LT-GEE/landtrendr.html)





Análisis de Serie Temporal

índice

índice

**Obtención de imagen mejorada**

Identificación de:

Año de detección – Magnitud – Duración del disturbio

Kennedy *et al.* 2012





Análisis de Serie Temporal

Cuenca Feliciano

2020

1984

Análisis de series temporales con Land Trendr en Google Earth

Engine (LT-GEE)

PASOS:

Parametrización de LT con la app

(ensayo con diferentes rangos de

fechas)

Interpretación de

resultados

Ejecución y obtención

de productos

Integración en

un SIG

Por defecto (menos fecha)





¿cuál es el mejor rango de fechas para detectar deforestaciones

en la cuenca Feliciano?

Se ensayó considerando diferentes criterios:

**A. Enero-Diciembre:** teniendo en cuenta que la variabilidad

interestacional de los bosques es mucho menor que la de los cultivos.

**B. Noviembre-Marzo:** teniendo en cuenta la estación de crecimiento

(Kennedy *et al.* 2012).

**C. Febrero-Junio:** teniendo en cuenta similitudes con el chaco seco (De

Marzo *et al.* 2021)

**D. Junio-Octubre:** teniendo en cuenta principalmente la diferenciación

entre áreas agrícolas y el ciclo del pastizal característico del espinal.





RESULTADOS:

Año de detección del disturbio en la Cuenca Feliciano:

(combinando rangos de fecha A-B-C-D)

▪ El modelo

detectó

cambios en la

mayoría de los

años

considerados.

▪ Espacialmente,

estos cambios

se ubican en la

porción inferior

de la cuenca.





RESULTADOS:

Zoom en el área del arroyo Estacas:

▪ Aunque la

cuantificación de

superficie es

perfectible, se

observa una notable

concordancia con

parcelas

agropecuarias

(antiguas áreas de

bosque).

La cuenca del arroyo Estacas es un sitio piloto del Observatorio Nacional de

Degradación de Tierras y Desertificación.

Fuente: <http://www.desertificacion.gob.ar/sitios-piloto/enlaces/>





RESULTADOS:

El modelo identificó cambios en casi todos los años, pero…

Mayor superficie

afectada durante

2008-2010:

▪ Ley OTBN de Entre Ríos

(sancionada en 2007,

vigencia desde 2009):

reestructuración de los

mecanismos de control.

▪ Se afectaron 5 a 20.400 ha según el año.

▪ Picos en 1987, 2008, 2009 y 2019.

▪ Precios de los

principales commodities





Perspectivas:

• **Validar los resultados**: TimeSync, sumar información de

campo, script desarrollado por CeReGeo, procedimiento de

Hurtado y Lizarazo 2019 (firmas espectrales).

• Centrarse en Cuenca Estacas porque hay más antecedentes.

• Decidir qué modelo permite la máxima identificación de

deforestaciones (separación de bosques respecto de los otros

usos de suelo).

• Análisis cuantitativos (cuantificar qué categorías se vieron más

afectadas: OTBN, ANP, Land Cover ESRI, etc.).





CONCLUSIONES:

Existe una dinámica de cambio en los bosques de la Cuenca Feliciano:

Con la información satelital de las últimas décadas tecnologías disponibles actualmente,

es posible estudiar la dinámica de estos cambios y relacionarlos con procesos sociales de

incidencia territorial, como la creación de leyes o el desarrollo agropecuario. A ESCALA

REGIONAL

LandTrendr resultó una herramienta accesible y potente para detectar cambios

en la cuenca, y factible de ser aplicada a nivel regional:

✓ Permite explorar los cambios (deforestaciones) en una extensa región en poco

tiempo.

✓ Bajos requerimientos de hardware-software (proceso en la nube de Google).

✓ Fácil uso y cambio de parámetros para mejorar el ajuste a la zona de estudio o

para evaluar nuevos objetivos.

✓ Permite identificar áreas donde centrar la atención (aunque la cuantificación de

las superficies es perfectible con técnicas posteriores.

Estas aplicaciones contribuyen a la planificación y a una evolución armoniosa

entre los usos de suelo de una región: **desarrollo sustentable.**





BIBLIOGRAFÍA BÁSICA:

Cohen, WB, Yang, Z. y Kennedy, R. (2010). Detección de tendencias en la perturbación y recuperación de

bosques utilizando series temporales anuales de Landsat: 2. Herramientas TimeSync para calibración y

validación. Detección remota del medio ambiente, 114(12), 2911-2924.

**De Marzo, T, Pflugmacher, D, Baumann, M, Lambin, E F, Gasparri, I. y Kuemmerle, T. (2021)**

**Characterizing forest disturbances across the Argentine Dry Chaco based on Landsat time series.**

**International Journal of Applied Earth Observations and Geoinformation, 98.**

Kennedy, RE, Yang, Z. y Cohen, WB (2010). Detección de tendencias en la perturbación y recuperación de

bosques utilizando series temporales anuales de Landsat: 1. LandTrendr: algoritmos de segmentación

temporal. Detección remota del medio ambiente, 114(12), 2897-2910.

Kennedy, RE, Yang, Z., Cohen, WB, Pfaff, E., Braaten, J. y Nelson, P. (2012). Patrones espaciales y

temporales de perturbación forestal y rebrote dentro del área del Plan Forestal del Noroeste.

Teledetección del Medio Ambiente, 122, 117-133.

Kennedy, R.E., Yang, Z., Gorelick, N., Braaten, J., Cavalcante, L., Cohen, W.B., Healey, S. (2018).

Implementation of the LandTrendr Algorithm on Google Earth Engine. Remote Sensing. 10, 691.

Oyarzabal, M., J. Clavijo, L. Oakley, F. Biganzoli, P. Tognetti, I. Barberis, H. M. Maturo, R. Aragón, P. I.

Campanello, D. Prado, M. Oesterheld, y R. J. León. (2018). Unidades de Vegetación de la Argentina.

Ecología Austral 28: 040-063.





MUCHAS GRACIAS

Email: <lauracsantoni@gmail.com>

