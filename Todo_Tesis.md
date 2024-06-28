

Junta Viernes 16-02-2024

    * Donde puedo Sacar datos por año poblacionales y clima ? [ x ] Hacer interpolación
    * Creo que puedo sacar un resumen diario, haciendo un Bot (https://www.smn.gob.ar/descarga-de-datos)  Descargar DH
    * Matriz de vecindad  [ x ]

   
    * Puedo asumir que VIH es igual a Resultado VIH, y dejar aquel que contenga datos?, igualandolos y eliminando una de las 2 columnas?
    * Puedo asumir que aquellos sin información y tienen prueba VIH, son resultados negativos? (son como 17)
    * Puedo asumir que aquellos con Resultados de VIH, deberían tener prueba de VIH, puedo eliminar finalmente la prueba si considero lo anterior?

    * Puedo asumir NS de embarazo como sin Información
    * Puedo asumir sexos fuera de M y F como sin información.


    (lunes, 5 de febrero de 2024 12:13)

        -  Hacer un clustering de la incidencia por región y/o departamento (ver los principales focos),analizar año a año y patron identificable. <.p>
        -  Estudiar correlación con co-morbilidades (VIH principalmente) aplicar correlación lineales y/o modelo de Spearman. <.p>  [ x ]
        -  Hacer descomposiciones de las series. Analizar las tendencias pre y post-pandemia.  <.p>

    (mié, 31 ene 2024 a las 16:15) (Propuesto)
        x  Profundizar en el análisis de autocorrelación puesto que sigo sin entenderlo mucho (voy a modificar uno de mis ramos de manera de poder tomar este semestre "Time Series" que trata de este tipo de algoritmos) [ x ]
        x  Mejorar la base de datos, haciendo oversampling de "Tratamiento Exitoso"
        -  Rellenar los valores vacíos, ya sea analizando posibles distribuciones o aplicando otra técnica
        -  Obtener datos generales de la población (por ejemplo % de Diabetes por provincia, ) de manera de comparar la probabilidad de contagio de una persona sana vs una enferma  [ ]
        x  Hace un segundo barrido de limpieza de datos
        x  Incluir temperatura, humedad, densidad poblaciones, pobreza y otros datos a cada provincia para observar el impacto ....  <.p>
        -  Limpiar código, crear repositorio. <.p>

    (miércoles, 31 de enero de 2024 14:20)
        -  Crear un repositorio compartido para ir subiendo resultados y que Leonardo pueda revisarlos

    (mié, 20 dic 2023 a las 14:24)
        -  Hacer regresión lineal para comprobar la relación entre clima, densidad poblacional, pobreza, etc contra los casos reportados. <.p>
        -  Hacer  auto-correlación para ver si hay seasonality en las series temporales o no.  <.p>
            -  Obtener Index  <.p> [header link](#morgan-y-lisa)
            -  Obtener Local Indicator of Spatial Association (LISA) <.p> [header link](#morgan-y-lisa)
        -  Revisar Papers Autocorrelación, Refresión, PCA (Papers 1)
        -  Analizar Paper Vecindarios  (Papers 1)
        -  Mirar Repo  (Papers 1)
        -  Armar review con el estado del arte, epidemología de la enfermedad, principales comorbilidades, estado actual de la enfermedad en la región y en el mundo. (Tip 1.-)


    (miércoles, 29 de noviembre de 2023 10:59)
        x  Descargar datos de INDEC que están a escala departamental. (https://portalgeoestadistico.indec.gob.ar/)  <.p>

   (viernes, 17 de noviembre de 2023 19:59)
        -   Revisar papers estado del arte (Papers 2) 


Datos
- Nombre: Leonardo Rafael Lopez
- Correo: leonardorafael.lopez@isglobal.org
- Numero Personal: +34615823007
- Dirección: Campus Mar C/ Doctor Aiguader, 88. 08003. Barcelona. Phone: +34932147300



Tips

1.-  Puedes poner que es un tema de preocupación para la OMS debido al aumento de casos a escala global y justificar que el estudio de la dinámica en argentina ayudaría a entender las tendcencias actuales y futuras debido a la heterogeneidad socio-económica y la variedad de escenarios que se pueden analizar, mas allá de que el país no representa una zona de alta incidencia como por ejemplo, Brasil, por poner un ejemplo regional.


Papers 

1.- 
    Autocorrelación
    http://52.59.210.70/index.php/KnE-Engineering/article/view/5841
    https://link.springer.com/article/10.1186/s12879-020-05249-3
    https://link.springer.com/article/10.1186/s40249-016-0104-2
    Regresión.
    https://bmcpublichealth.biomedcentral.com/articles/10.1186/s12889-019-7026-4
    https://www.sciencedirect.com/science/article/abs/pii/S2452014419301694
    PCA
    https://journals.plos.org/plosone/article?id=10.1371/journal.pone.0047533

    Por otro lado, para un análisis espacial mas detallado, podemos hacer una análisis de vecindarios. . Este término se refiere al proceso de agrupar unidades espaciales en función de su proximidad. Luego, se utiliza un análisis estadístico para comparar las unidades espaciales dentro de cada grupo.
    https://www.sciencedirect.com/science/article/pii/S1047279716303751?casa_token=us_WTvt19fgAAAAA:ntCVAjveMFHd6tO9rSUgO-EAAFUk-VRwROh0bvwL0RE376kwqNFgtAEmmC3cidgyt2C76CLC4g
    Mirate este repo
    https://github.com/oturns/geosnap


2.-

    https://www.sciencedirect.com/science/article/abs/pii/S0013935122007630?via%3Dihub
    https://www.scielo.br/j/rbepid/a/W3wSwjYkJNfWFjyFdYMSLDL/?lang=en
    https://www.sciencedirect.com/science/article/abs/pii/S0306456519302724
    https://www.scielo.br/j/rbepid/a/W3wSwjYkJNfWFjyFdYMSLDL/?format=html&lang=en
    http://www.scielo.org.ar/scielo.php?pid=S0025-76802017000400003&script=sci_arttext
    http://www.scielo.org.co/scielo.php?pid=S0120-41572018000200180&script=sci_arttext
    También podes chequear estos links mas genereales
    https://www.cdc.gov/tb/default.htm
    https://www.who.int/publications/i/item/9789240083851


### Morgan y LISA
The Moran index is a global index used to determine whether there is a spatial relationship in disease spreading. Whereas LISA is
used to evaluate the tendency for spatial grouping locally and to show some forms of spatial relations.






[-] Sobre los datos, está bien. Puedes interporlarlos. No hay problema. De todos modos le voy a escribir a FLACSO para ver que me puedan enviar mas datos. Ve haciendo los análsisi con las interpolaciones como para ir eesscribiendo lo métodos y luego vemos si los resultados se condicen con los datos reales (en caso de que se consigan)

[-] Esos datos son de estaciones climáticas del serviciio meterológico nacional. 
    *   Prueba bajaar datos desde la  página de la CONAE https://catalogos.conae.gov.ar/Catalogo/catalogoGeo.html   (Solo encuentro diarios)
    * Si no se puede, entonces podemos intenar con datos simulados o satelitales de copernicus o CMIP https://cds.climate.copernicus.eu/cdsapp#!/dataset/
    projections-cmip5-daily-single-levels?tab=overview  (Debo famliarizarme mejor con la API)
    * De todas maneras creo que es mejor con mi propuesta

[x] puedes probar een estas páginas (Funcionó)
    https://www.indec.gob.ar/indec/web/Institucional-Indec-Codgeo
    https://www.ign.gob.ar/NuestrasActividades/InformacionGeoespacial/CapasSIG

[-] Lo vemos la semana que viene. Puede ser que haya confusión entre departamento de diagnóstico, de residencia, etc. Además de que hay municipios que se llaman de la misma forma en dos provincias diferentes. Te mando un código que en su momento hice yo. Es bastante rústico

[-] Se lo voy a pedir a la socióloga de FLACSO.




Hacer el cambio de provincia y localidad...
da  

Gancho Genero / Sexo con Incidencia 

2) Hacer año y agregar provincias (Agregar video)

Bayesiano Criteiro de información (para encontrar mejor modelo)


Como lidiamos con la falta información, recuperar información  (Otra parte)

	- Fundación HUESPED (llevan registros VIH) 



Hacer documento drive (de lo que queremos contar)

Generar informes
	Composición de datos (quitando outliers, con cuanto podemos trabajar...)
	Resultados de Autoccorellación (2)



Hacer un clustering de la incidencia por región y/o departamento (ver los principales focos),analizar año a año y patron identificable. <.p>



Kulldorff’s spatial-temporal scan statistical