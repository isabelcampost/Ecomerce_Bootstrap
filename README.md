# Ecomerce_Isyel
![Automatizando Reportes con Python](img/portada.jpg)

>Como generar un ecomerce con bootstrap 

[![Facebook](https://img.shields.io/badge/-Facebook-3b5998)](https://www.facebook.com/datahackformation)
[![Youtube](https://img.shields.io/badge/-Youtube-FF0000)](https://www.facebook.com/datahackformation)

aqui veremos paso a paso como hacer un ecomerce

>si puedes imaginarlo lo puedes programar

***
## primer paso
Primero lo que tenemos que hacer es importar los modulos, nombrar los archivos asignarles algun nombre legible
![Primer paso](img/)

## Segundo paso
Primero lo que tenemos que hacer es importar los modulos, nombrar los archivos asignarles algun nombre legible
![Primer paso](img/portada.jpg)

## Quinto paso
#### Graficamos el reporte en 
![quinto paso](img/portada.jpg)

## Sobre nosotros ✏
En [datahack.ai](https://fre/) bridamos formacion de temas de data. Nuestro objetivo es contar con un equipo altamente calificado

## License
>Copyright @ 2020 DataHack - <hola@hotmauil.com>


# Plantilla de README.md

Este gist te ayudará a aprender los fundamentos básicos del lenguaje rápido **Markdown** 

```
(también conocido como MD o .md)
```

## Instrucciones

El objetivo final es que tengas un archivo llamado **README.md** en tu GIST Público.

### Iniciar Sesión 

Antes que nada verifica que tengas una sesión activa en [GitHub](https://github.com)

### Crea un FORK a este archivo

Busca el botón de FORK para crear una copia de este archivo en tu propia cuenta.

```
Todos los archivos que terminan en .md son identificados como un archivo Markdown.
```

### Editar tu archivo y completa la actividad

TEMA : MARKDOWN

Escribe un pequeño reporte de más de 100 palabras que responda lo siguiente:

1. ¿Quién inventó MarkDown y en que año fue?
2. Explica que es GitHub Flavored Markdown (GFM)
3. Explica las diferencias entre un GIST anónimo, público y secreto
4. Describe los pasos necesarios para usar WGET para descargar un archivo RAW en 

Para completar esta actividad deberás incluir los siguientes elementos:

* Breve descripción del archivo.
* 3 Niveles de cabeceras diferentes (H1, H2, H3).
* Una lista con puntos o con números.
* Una tabla con cualquier información.

---

## Ejemplos

Para ver más ejemplos puedes visitar este [LINK - ejemplos.md](https://gist.github.com/recurs1v0/0b396678831df73c9cd4ac9e8566e50f).

---

# Reporte clase 202: TAKEAWAYS

## La herramienta para dar formato a texto en Gist, Github, Reddit, Overflow y otros.

### Al estar interactuando con Gist y Github, rápidamente se encuentra uno con el concepto de Markdown (Md): 

* A Es un lenguaje para dar formato a texto.
* B Fue desarrollado en 2004 por John Gruber con ayuda de Aaron Swartz como una forma súmamente legible de redactar eliminando la necesitdad del uso de etiquetas para dar formato.
* C Complementariamente se desarrolló la especificación Github Flavored Markdown (GFM) que es un dialecto estricto de Md para definir una semántica y sintáxis muy precisas. Si bien Md es compatible para su conversión a HTML, GFM es respaldado por Github.com pues tyras su conversión lo postprocesa y sanitiza asegurando así un desempeño seguro y consistente del sitio que lo hospede.

## Las diferencias entre un Gist anónimo, público y secreto:

|Tipo de cuenta de gist | Especificaciones |
| ------                |          ------: |
|  Anónimo              |  Se hace para no tener vinculado Github con gist, por lo tanto para obtenerlo es necesario salir de                              la cuenta de github o navegar en modo incógnito antes de entrar a gist. |
|  Público              |  Se enlista en la sección principal de gist, está visible para todos, va a estar listado en google y                            demás servidores y lo que compartas puede llegar fácilmente a cualquier usuario de gist. |
|  Secreto              |  No se enlista en la sección principal de gist, está invisible para todos, no va a estar listado en                              google y demás servidores y es más difícil que te identifiquen en gist pero no imposible, cualquiera                            con un link de tu contenido te podrá encontrar mediante ese contenido así que no es tan privado.  |



## Pasos necesarios para usar WGET y descargar un archivo RAW en el IDE

* 1 Con el IDE abierto crea o selecciona la ubicación a dónde descargar el archivo RAW
* 2 Entra a dicha ubicación con el comando "cd"
* 3 Teclea el comando "wget" sin comillas, deja un espacio y a continuación escribe la dirección del repositorio público desde donde obtener el archivo RAW. En este caso es una dirección de gist
* 4 Enter
* 5 Utiliza el comando ls para verificar que se descargó

#### Nota: wget es un comando que sirve para descargar un archivo desde algún repositorio público por medio de mi IDE, debe estar en formato RAW y si está en GIST solo se tiene acceso a la última versión disponible.


---

## Autores

* **EPPR** - *Colaborador Inicial* - [GitHub](https://github.com/EPPR/)
* Sharles256 - *Colaborador Complementario* - [GitHub](https://github.com/Sharles256/)


# Reconocimiento facial con OPENCV
Mediante el uso de un script aprenderemos las caras que nos interesen y con otro script arrancaremos la función de reconocimiento.

OPENCV tiene 3 metodos incorporados para realizar reconocimiento facial, y porque **#Python** podemos usar cualquiera de ellos solo cambiando una linea de codigo. Aqui los 3 metodos y como llamarlos:

1. EigenFaces – cv2.face.EigenFaceRecognizer_create()
2. FisherFaces – cv2.face.FisherFaceRecognizer_create()
3. Local Binary Patterns Histograms (LBPH) – cv2.face.LBPHFaceRecognizer_create()

Cada uno resalta componentes principales diferentes, es cuestion de elegir el adecuado de acuerdo a las necesidades de cada proyecto.

| **EigenFaces** | **FisherFaces** | **LBPH** |
| :-------: | :------: | :-----: |
| <img src="https://docs.opencv.org/2.4/_images/eigenfaces_opencv.png" width="200">|<img src="https://docs.opencv.org/2.4/_images/fisherfaces_opencv.png" width="200">|<img src="https://docs.opencv.org/2.4/_images/lbp_yale.jpg" width="200">|

# Como usar la herramienta
Para empezar deberemos instalar OpenCV junto con todas sus dependencias ⚠ Numpy y contrib son importantes ⚠ 
~~~
pip install opencv-contrib-python
~~~

Posteriormente para guardar las fotos de entrenamiento para el modelo, nos descargaremos una pequeña BD de caras para que tenga mejor precisión y a la que añadiremos nuestra cara o las que nos interesen. Nos bajamos la BD de ejemplo de la Database of Faces de AT&T Laboratories Cambridge, descomprimimos la carpeta, dentro de ella creamos una mas llamada orl_faces y dentro de esa creamos una carpeta con el nombre de las caras que queremos reconocer. La ruta seria algo como esto:
~~~
carpeta_de_proyecto\att_faces\orl_faces\luis_sustaita
carpeta_de_proyecto\att_faces\orl_faces\antonio_smith
carpeta_de_proyecto\att_faces\orl_faces\ricardo_ferro
carpeta_de_proyecto\att_faces\orl_faces\rodolfo_miron
~~~

De los scripts uno será para aprender caras (capture.py) y el otro para reconocerlas (reconocimiento.py).

El primero de ellos es simple: busca una cara, toma una foto de ella y la guarda en la carpeta correspondiente.
~~~
python capture.py nombrePersona
~~~
<img src="https://github.com/futurelabmx/FaceRecognition2/blob/master/entrenamiento.png?raw=true" width="600">

- ⚠Ten en cuenta que el nombre de la persona es el mismo que pusiste en el nombre de su carpeta.

- 👌Por default el script toma 100 fotos del rostro, pero recuerda que entre mayor sea el entrenamiento mejores reultados se obtendran.

- ☝Trata de que solo una parsona aparezca en la escena para no guardar otros rostros con la misma etiqueta o nombre.

Para comenzar a detectar y reconocer caras:
~~~
python reconocimiento.py
~~~
- Puedes cambiar el metodo de reconocimiento por caulquiera de los 3 mencionados al inicio, prueba los 3 y checa cual te da mejores resultados.

<img src="https://github.com/futurelabmx/FaceRecognition2/blob/master/reconocido.png" width="600">

============================================




# Sesión de reconocimiento Facial

Sesión de reconocimiento facial para el Google Developer Student Club Guanajuato & Hackademy. En esta sesión explicamos el proceso completo para la detección de rostros que realiza el algoritmo de [Viola-Jones](https://www.cs.cmu.edu/~efros/courses/LBMV07/Papers/viola-cvpr-01.pdf) (2001):

![Viola-Jones](assets/process.png)


Revisa los slides [aquí](https://docs.google.com/presentation/d/e/2PACX-1vR5wgAoNGyy0fhkLbYGiY2CTzh80j5ACa3hrTLU0U7feA4ZUoFLvumO4yqqLO5vwTygy8wFbcqdAoMX/pub?start=false&loop=false&delayms=3000).

Y un TikTok demostrando el funcionamiento aquí: [https://vm.tiktok.com/ZMdoMfmKM/](https://vm.tiktok.com/ZMdoMfmKM/)


## Setup

Instala OpenCV y NumPy con Anaconda:
```bash
conda install -c conda-forge opencv numpy
```

O utiliza pip:
```bash
pip install opencv-python numpy
```

Ejecuta el archivo `facedet.py`:
```bash
python facedet.py
```

