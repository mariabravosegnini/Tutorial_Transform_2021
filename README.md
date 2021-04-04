# Tutorial Transform 2021 - ANALISIS Y VISUALIZACION DE DATOS

![SWUNG Logo](/images/SWUNG_logo.png)

**Instructoras:**
[Maria Cecilia Bravo](https://github.com/mariabravosegnini)<sup>1</sup>
[Diana Acero-Allard](https://dianaceroallard.github.io/)<sup>1</sup> 

 <sup>1</sup>Geolatinas

![GL Logo](/images/GL_logo.jpeg)

|         | Info |
|--------:|:-----|
| Cuando | Lunes , Abril 19 • 17:00 - 19:00 GMT |
| Slack (preguntas y respuestas) | [Software Underground](https://softwareunderground.org/) channel `t21-mon-data-analysis` |
| Sesion en vivo | https://www.youtube.com/watch?v=mCOZ51Do9uw&list=PLgLft9vxdduCESA3xAo5Ts_ziO8vZAFG1&index=4 |
| Requisitos  | `Anaconda` |
| Documentacion | [Repositorio en Github](https://github.com/mariabravosegnini/Tutorial_Transform_2021)|


## ANTES DEL TUTORIAL

Asegurate de realizar los siguientes pasos **antes de la sesion tutorial el Lunes**:

1. Unete a [Software Underground Slack](https://softwareunderground.org/slack)
2. Unete al canal `t21-mon-data-analysis`. Aqui es donde todos nos comunicamos **todas las comunicaciones son aqui**.
3. Configura tu computador ([instrucciones abajo](#Configuracion)). Durante la sesion no tendremos tiempo 
   de solucionar problemas tecnicos asi que asegurate de realizar estos pasos antes. Si necesitas ayuda 
   pregunta en el canal `t21-mon-data-analysis` en Slack.
4. Si tienes tus propios datos tenlos listos y asegurate que se puedan cargar con Pandas. Tendras algun tiempo
   al final del tutorial para trabajar en tu propio proyecto.
5. Si algo muy basico no es claro visita [Geolatinas Coding Group - Getting Started](https://geolatinas.github.io/)

## Acerca del Tutorial

Los objetivos de este tutorial son: 
- Inspeccionar un archivo tipo .LAS usando Lasio
- Convertir de archivo Lasio a Pandas
- Importar 2 archivos de datos separado por comas (.csv) usando Pandas
- Realizar calculos de valores usando Pandas
- Graficar variables usando Matplotlib y Seaborn

## Datos 

- Archivo de registros electricos .LAS de un pozo con fines geotermales **58-32_main.las**
- Tablas de datos medidos en laboratorio para los ripios del pozo con fines geotermales **58-32_TC.csv** y **58-32_XRD.csv**
Mas detalles acerca de los datos [UTAH FORGE Well 58-32](https://gdr.openei.org/submissions/1111)

## Pre-requisitos

El nivel de este tutorial es para principiantes con fundamentos de python con uso en la plataforma Anaconda.
- Codificaremos usando Jupyter notebooks en la plataforma Anaconda [Instalar Anaconda en Windows](https://www.youtube.com/watch?v=FdatS_NKVrM) [Instalar Anaconda en Linux](https://www.youtube.com/watch?v=3ncwbHyZeAg)
- Pre-requisitos fundamentos de numpy, pandas y matplotlib


## Configuracion

- Instalar Lasio en el terminal ejecutar **pip install lasio** para mas informacion acerca de Lasio [click aqui](https://pypi.org/project/lasio/)
- Instalar Seaborn en el terminal ejecutar **pip install seaborn** para mas informacion acerca de Seaborn [clikc aqui](https://pypi.org/project/seaborn/)

**Empezar un Jupyter notebook:**

1. **Usuarios de Windows:** Asegurense que su buscador de internet **no sea Internet Explorer**. 
2. Empezar un Jupyter notebook: `jupyter notebook`
3. Jupyter debera abrir en tu buscador de internet configurado. Empezaremos desde aca y crearemos 
   un nuevo notebook juntos. 

###  SI TODO LO ANTERIOR NO FUNCIONA

En caso que no puedas configurar correctamente, tienes la opcion de codificar usando 
Google Colab (necesitaras una cuenta de Google).

Para familiarizarse con la plataforma Google colab este video te ayudara
[Google colab tutorial](https://transform2020.sched.com/event/c7Jn/tutorial-using-python-subsurface-tools-no-install-required)


## Como funcionara el tutorial

Debido al numero de participantes no podremos interactuar directamente. 
En cambio, haremos una breve introduccion, codificaremos en vivo usando unos datos de 
ejemplo y finalmente tu podras trabajar en tus propios datos.

| Time          | Activity |
|:-------------:|:---------|
| 17:00 - 17:20 | Introduccion |
| 17:20 - 18:00 | Carga de datos, inspeccion y calculos |
| 18:00 - 18:10 | Receso |
| 18:10 - 18:50 | Visualizacion y analysis |
| 18:50 - 19:00 | Notas finales, preguntas y respuestas - Slack |

## Licencia

Todos los codigos y textos de este repositorio en libre: Se acepta la distrubucion y modificacion 
bajo los terminos de la licencia Creative Commons Zero v1.0 Universal.

