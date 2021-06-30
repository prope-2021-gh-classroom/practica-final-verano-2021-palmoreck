Antes de iniciar a trabajar: **sólo una persona de cada equipo debe darle click a la liga de gh-classroom** que está indicada en la publicación del *google classroom*. Una vez que le dé click a la liga de gh-classroom tal persona invitará a sus integrantes de equipo como *Admins*. Para invitar a sus integrantes ir dentro del repo de gh-classroom a *Settings* -> *Manage Access* y enviar la invitación ingresando *users* de github de sus integrantes.


# Objetivo

Aprendizaje y uso de la amplia gama de paquetes que proporcionan *Python* y *R* para análisis de datos y resolución de problemas.

# Descripción

Cada equipo elige datos de su interés relacionados con alguno de los temas vistos en el curso: Cálculo Diferencial e Integral, Álgebra Lineal, Probabilidad o Estadística (como mínimo un tema debe considerarse y pueden mezclarse) para su análisis vía los paquetes de los lenguajes revisados en el curso.

Algunos ejemplos:

* Análisis de las ecuaciones de Lotka-Volterra para describir la interacción de sistemas con depredadores y presas con los paquetes numpy, matplotlib, sympy de *Python*.

* Modelo de regresión logística ajustado a análisis de datos de salarios de personas con los paquetes tidyverse, readr, e1071, kernlab, ROCR, pROC, corrplot de *R*.

* Análisis exploratorio de base de películas con los paquetes pandas, numpy, seaborn, matplotlib de *Python*.

* Análisis descriptivo de datos del videojuego de Pokemon con los paquetes ggplot2 y MASS de *R*.

* Uso del álgebra lineal en criptografía y análisis de difusión de mensajes cifrados con los paquetes numpy, matplotlib y pandas de *Python*.

* Análisis descriptivo de la movilidad social en México con los paquetes haven, markovchain, diagram, shape, ggplot2, MmgraphR, Gmisc, magrittr de *R*.

* Análisis descriptivo de incidencia delictiva en la Ciudad de México con los paquetes numpy, matplotlib, pandas, geopandas y shapely de *Python*.


Se ha asignado el lenguaje por equipo (*Python* o *R*) en la publicación de *google classroom*. Cada equipo decide los datos y paquetes a utilizar.

# Herramientas

Jupyter notebooks, repl, git, github, docker, binder, Python3, Rstudio, Spyder.

# Dinámica

Misma dinámica que en la práctica 1 por equipos donde se utilizó la funcionalidad de github para la creación de proyectos, *issues*, *milestones*, *reviewers*, *pull requests* y la organización y comunicación de su trabajo. Ver ejemplo de lo anterior en el [video](https://youtu.be/z4Xpif7HI04) (mismo video de la práctica 1).

**Para que esta dinámica funcione cada equipo debe tener una persona que vaya creando el proyecto, que cree/cierre los *issues*, *milestones* y debe observar que los pull requests sean revisados y finalmente que se haga el *merge* por la persona reviewer.** Ustedes deciden quiénes tendrán este rol, aka, ***project manager***. 

# ¿Fecha de entrega?

El lunes 5 de julio 14:00 pm suban su trabajo escrito en formato de notebook o pdf a sus repos de gh-classroom con nombre `<practica_final_equipo_x>.ipynb` o `.pdf`. Su presentación **no la suban** a este repo, coloquen una liga hacia donde esté almacenada (por ejemplo un *google drive* o un *dropbox*) y háganla pública, no me inviten a colaborar. Una vez que hayan finalizado su presentación coloquen la liga a la misma en su `README.md` de sus repos.


# ¿Calificación y porcentaje?

Si en todo el prope no entregaron 3 prácticas semanales o bien al sumar sus puntos de las prácticas semanales y por equipos hasta la número 4 (incluyéndola) no tienen al menos 3 puntos acumulados, la calificación de **todas** las prácticas (también la final) será de 10%. En otro caso las prácticas semanales incluyendo las que fueron por equipos acumulan 70% y la práctica final será de 30% de acuerdo a lo presentado el primer día del curso. 

La práctica final será evaluada como sigue:

* 10% trabajo escrito.

* 60% uso de los paquetes del lenguaje asignado.

* 10% uso de la funcionalidad de github por todo el equipo.

* 10% trabajo individual evaluado vía los *commits* realizados en github.

* 10% presentación en clase. Todas y todos tienen que presentar y resolver las preguntas que surjan durante su presentación.


# Y si ya elegimos el tema y paquete ¿qué debemos realizar a continuación?

Crear un nuevo `README.md` en la raíz de su repo colocando el tema, paquete a usar, referencias a sus datos y las que utilizan para su práctica final\*, el lenguaje, integrantes y qué persona\* será la *project manager*. Les sugiero conserven la instrucciones de este `README.md` renombrándolo como `old_README.md`.

\* **Las referencias colóquenlas utilizando *Markdown*, esto es, no coloquen ligas de la forma:**

* https://web.archive.org/web/20061025183237/http://www.idiom.com/~zilla/Work/nvisionInterface/nip.html

**pues es difícil leerlas y acordarse qué referencia era, utilicen *Markdown***:

  * [Fast Normalized Cross-Correlation](https://web.archive.org/web/20061025183237/http://www.idiom.com/~zilla/Work/nvisionInterface/nip.html).
  
\* **Coloquen para cada integrante las asignaciones realizadas en su `README.md`, por ejemplo:**

|User| Trabajo|
|:---:|:---:|
|@ericka| Project manager, búsqueda de datos y paquete. Gráficas.|
|@erick | Propuesta de tema y análisis de datos. |

-> **También coloquen sus referencias en su `<practica_final_equipo_x>.ipynb` o `.pdf`**


# ¿Cuando presenta mi equipo?

Equipos 1 y 2 el lunes 5 de julio. Equipos restantes el martes 6 de julio. Ambos días nos vemos 18:00 por M. Teams.

# Notas

* **Deben usar [repl.it](https://repl.it/), `git` o Github para llevar la historia de cambios en la realización de sus notebooks o cualquier otro archivo y subirlos a sus repos. No se revisarán aquellos archivos que tengan un commit con todas las respuestas. El trabajo es incremental.**

* Aquí el botón de binder: [![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/palmoreck/dockerfiles-for-binder/jupyterlab_prope_r_kernel_tidyerse?urlpath=lab/tree/Propedeutico) (recuerden que también permite uso de R, sólo hay que asegurarse que el kernel es el de *R*)

<img src="https://dl.dropboxusercontent.com/s/o8e6xk5xwhlzzgj/r_kernel_jupyterlab.png?dl=0" heigth="800" width="800">

<img src="https://dl.dropboxusercontent.com/s/82kjtun9r2lv28t/r_kernel_jupyterlab_2.png?dl=0" heigth="300" width="300">

* Incluyan mensajes en sus *commits* que tengan información útil y que hagan referencia en su mensaje al *issue* que se está trabajando, por ejemplo:

```
git commit -m "solving issue #4 regarding download of data" -i <archivo(s) asociado(s) al commit>
```

 * Poner las referencias que utilizan (aún si le preguntan a una compañera o compañero de la clase coloquen esto en su entrega) pues no está permitido copiar y escribir que lo hicieron sin citar sus fuentes.


* Ir guardando su trabajo si usan *binder*.

* Usar [repl.it](https://repl.it/), `git` o github para añadir archivos a sus repos de gh-classroom. Algunos comandos de `git` útiles para añadir un archivo (por ejemplo un notebook) son:


```
git clone <url de mi repo que está en gh-classroom> <aquí colocar nombre de un directorio>

#el comando anterior les pedirá sus credenciales de github tecleen la respuesta y den enter por cada respuesta

cd <nombre del directorio elegido en la línea anterior> #cd es "change directory" y lo usamos para entrar al directorio

```

**La url de un repositorio en github puede obtenerse con el botón `Code`**

<img src="https://dl.dropboxusercontent.com/s/rszq68r63gl1pwu/github_button_to_clone_repo.png?dl=0" heigth="300" width="300">

```
git config --global user.email "<mi correo asociado de github>"
git config --global user.name "<mi nombre>"
git add <nombre de mi notebook>
git commit -m "mensaje de mi commit" -i <nombre de mi notebook>
git push
```

La última línea les pedirá sus credenciales de github.

Después de realizar por primera vez lo anterior si quiero hacer cambios en mi notebook el flujo que sigo es:

```
#clonar repo a un directorio si no lo tengo clonado
#entrar al directorio con cd
#git config --global user.email "<mi correo asociado de github>"
#git config --global user.name "<mi nombre>"
git commit -m "mensaje de mi commit con los cambios" -i <nombre de mi notebook>
git push
```

La última línea les pedirá sus credenciales de github.

Si decideron no usar `git` y prefieren usar github para subir los notebooks (que previamente descargué de binder) pueden usar el botón de `Upload files`:

<img src="https://dl.dropboxusercontent.com/s/dvehbsysah6crr3/upload_files_github.png?dl=0" heigth="500" width="500">

y no olviden escribir un mensaje significativo de los cambios que han hecho (incluso si subieron un archivo)


<img src="https://dl.dropboxusercontent.com/s/hk4yp2ncs97hv70/commit_changes.png?dl=0" heigth="500" width="500">


* **Su trabajo individual y su tiempo es muy valioso e importante, también el trabajo en equipo. Si alguna persona del equipo no realizó su tarea asignada, avísenme y no realicen su tarea asignada. Si tienen algún problema (familiar, salud,...) infórmenme con tiempo para ver qué podemos hacer :)**



