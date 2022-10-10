# AISX1_M4UF1_apuntes_CarlaMaldonado
# DOCUMENTACIÓN DE LA UF1 CON MARKDOWN #
En este documento podremos ver lo que hemos ido aprendiendo durante esta UF1, como ahora Markdown, HTML o GITHUB, entre otras.

## ÍNDICE ##
1. GITHUB
2. MARKDOWN
    + Encabezados
    + Estilos de letra
    + Listas
    + Párrafos
    + Código
    + Enlaces
    + Imágenes
    + Tablas
3. HTML

## 1. GITHUB ##
![IMG.1678.png](https://github.com/carlamaldonado04/AISX1_M4UF1_apuntes_CarlaMaldonado/blob/main/IMG-1679.jpg "RepNuevo")



## 2. MARCDOWN ##
### ENCABEZADOS ###
Añadiendo # podemos cambiar el tamaño de nuestros títulos, cuantos más pongamos más pequeño será. 

|        |   ENCABEZADOS   |            |
|:--------:|:---------:|:--------------:|
| #H1#| ##H2##|###H3###| 
| ####H4#### | #####H5#####| ######H6######|

### ESTILOS DE LETRA ###
  Para cambiar el estilo de nuestro texto, 
         podemos hacerlo de tres maneras diferentes,
         dependiendo de nuestro objetivo.

 #### NEGRITA ####
  
     Si lo que queremos es enfatizar una palabra o conjunto de palabras, lo único que debemos de 
     hacer es añadir dos asteriscos (*) al principio y al final. 
     Otra manera de hacerlo es añadiendo dos barras bajas (_), también al inicio y al final de 
     la palabra. 
     Más adelante veremos porque nos interesa saber las dos maneras de poner en negrita nuestro 
     texto.

 #### ITÁLICA ####
    Por otra parte, si lo que queremos es citar alguna palabra extranjera o captar la atención 
    del lector de una manera diferente, podemos usar la letra itálica de una forma muy similar 
    a la que usamos para la letra negrita. 
    Solo tenemos que añadir un asterisco (*) o una barra baja (_), al principio y al final de 
    lo que queramos en cursiva.

#### ANIDAR ESTILOS ####
    Antes hemos comentado dos formas para cambiar el estilo de nuestra letra, pues bien, eso 
    nos será útil cuando queramos ambos modos. 
    Es tan sencillo como emplear ambas técnicas a la vez, podemos empezar con un esterisco seguido 
    de dos barras bajas, insertar la palabra, cerrar las barras baja y luego el esterisco o 
    viceversa.
    
|MARCKDOWN|RESULTADO|
|:---------:|:---------:|
| \**negrita** | **negrita** |
| \__negrita__|__negrita__|
|\*cursiva*|*cursiva*|
|\_cursiva_|_cursiva_|
|\_** cursivanegrita**_ | **_cursivanegrita_**|

### LISTAS ###
Tenemos dos tipos de listas: ordenas y desordenadas.

 #### LISTAS ORDENADAS ####
    Las listas ordenadas son aquellas que están numeradas.
    Para hacerlas solo tenemos que númerar nuestra lista y 
    añadir un punto después del número, es decir,
    1. primer elemento
    2. segundo elemento

 #### LISTAS DESORDENADAS ####
    Si lo que queremos no es una lista numerada, podemos usar las listas desordendas, 
    las cuales se crean de dos maneras: con un *, con un + o bien con un -
    Ambas tres tendrán el mismo efecto, es decir, se convertirán en un punto
\+ primer elemento 
+ primer elemento



### PARRÁFOS ###
Para crear parráfos con Markdown tan solo hay que dejar una línea en blanco.

### CÓDIGO ###
Las palabras en código pueden ser útiles para captar la atención del usuario, para ello 
tan solo deberemos añadir dos acentos abiertos al inicio y dos al final de la palabra 
que queramos resaltar

\``código``

``código``
### ENLACES ###
La creación de enlaces la dividiremos en dos pasos:
1. Añadir el texto del link entre corchetes
2. Añadir el link entre paréntesis, dentro de este, al final añadiremos un título opcional para el link, 
que será el que veremos cuando pasemos el ratón por encima 

\[Link](https://url/ "título del enlace")

[Link](https://url/ "título del enlace")


### IMÁGENES ###
El procedimiento para añadir imágenes es muy similar al que utilizamos para los enlaces, aunque cambia el principio.
1. Subimos la foto, previamente guardada en nuestro PC, a nuestro repositorio GITHUB.
2. Hacemos click con el botón derecho del ratón sobre la foto y copiamos el vínculo.
3. Abrimos nuestro repositorio
4. Para insertar la imagen, ponemos el signo de exclamación al principio
5. Abrimos corchetes y ponemos el nombre de la foto
6. Ahora abrimos paréntesis, copiamos el link de la foto y al final, antes de cerrar los corchetes, podemos añadir
un texto opcional de la imagen entre comillas.

\![alt text]\(https:/pegar.vínculo.foto.png "título")


### TABLAS ###
Para hacer tablas, tan solo, tenemos que seguir 3 pasos:
1. Para poner los encabezados empezaremos poneniendo un barra recta al principio de cada título

|encabezado 1 | encabezado 2 |

2. Entre los encabezados y el resto de contenido, añadiremos una fila con guiones:
    + si lo que queremos es tener el texto alineado a la izquierda: | ---- |

    + si queremos tener el texto centrada: | :----: |
    
    + para poner el texto alineado a la derecha: | ----: |

3. Añadiremos los demás elementos a continuación, de la misma manera que el encabezado

|elemento 1|elemento2|

Si seguimos los tres pasos la tabla nos quedaría así:
|encabezado 1 | encabezado 2 |
| :------: | :-----------: |
|elemento 1|elemento2|







