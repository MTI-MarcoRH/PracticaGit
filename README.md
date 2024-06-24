# PracticaGit

Esta práctica sirve para conocer los comandos básicos del maquetado bajo el estadar de  MARKDOWN (.md), que nos servirá para crear la documentación de nuestros proyectos de software durante nuestra formación profesional.

## 1. Títulos  (HEADERS)

Si para la documentación deseamos ubicar secciones de algíún tema o contenido podremos utilizar estos elemento para poner textos resaltados como encabezados. Estos son muy similares a las etiquetas  \<H1> ... \<H6> en HTML.

**EJEMPLO:**

# Título Principal (Nivel 1) 
## Subtitulo de Nivel 2
### Subtítulo de Nivel 3
#### Subtítulo de Nivel 4
##### Subtítulo de Nivel 5
###### Subtítulo de Nivel 6
####### El estándar solo te permite hasta 6 posibles títulos, a partir del séptimo omitirá la instrucción de maquetado.

## 2. Separadores (SEPARATORS)
Esta instrucción coloca una línea vertical entre las secciones del documento permitiendo organizar y distribuir mejor el contenido, y  puede ser maquetado utilizanto 3 guines medios (-) continuos despúes del párrafo deseado.

**EJEMPLO:**

Título de Sección
---
Párrafo 2 Párrafo 2 Párrafo 2 Párrafo 2 Párrafo 2 Párrafo 2 Párrafo 2 Párrafo 2 Párrafo 2 Párrafo 2


## 3. Párrafos (PARAGRAPHS)
Son utilizados para presentar texto descriptivo de la documentación de los proyectos, en el cuaál podremos utilizar la propiedad de  *align* de HTML para porder controlar la alineación del texto.

**EJEMPLO:**

Párrafo 1 en caso de no definir la alineación estará por defecto a la izquierda Párrafo 1 en caso de no definir la alineación estará por defecto a la izquierda Párrafo 1 en caso de no definir la alineación estará por defecto a la izquierda Párrafo 1 en caso de no definir la alineación estará por defecto a la izquierda Párrafo 1 en caso de no definir la alineación estará por defecto a la izquierda Párrafo 1 en caso de no definir la alineación estará por defecto a la izquierda

<p align="right"> Párrafo 2 al utilizar la etiqueta p y la propiedad de alineación align con el valor right , este estara alineado a la derecha Párrafo 2 al utilizar la etiqueta p y la propiedad de alineación align con el valor right , este estara alineado a la derecha Párrafo 2 al utilizar la etiqueta p y la propiedad de alineación align con el valor right , este estara alineado a la derecha </p>

<p align="center"> Párrafo 3 es texto estará centrado Párrafo 3 es texto estará centrado Párrafo 3 es texto estará centrado Párrafo 3 es texto estará centrado Párrafo 3 es texto estará centrado Párrafo 3 es texto estará centrado Párrafo 3 es texto estará centrado  Párrafo 3 es texto estará centrado </p>

<p align="justify"> Algunas veces desearemos justificar el texto para presentar el texto de una manera más organizada Párrafo 4 justificado Algunas veces desearemos justificar el texto para presentar el texto de una manera más organizada Párrafo 4 justificado Algunas veces desearemos justificar el texto para presentar el texto de una manera más organizada Párrafo 4 justificado Algunas veces desearemos justificar el texto para presentar el texto de una manera más organizada Párrafo 4 justificado Algunas veces desearemos justificar el texto para presentar el texto de una manera más organizada Párrafo 4 justificado Algunas veces desearemos justificar el texto para presentar el texto de una manera más organizada Párrafo 4 justificado</p>


## 4. Texto Enfatizado (BOLD ,  ITALIC, ITALIC/BOLD  y UNDERLINE) 

También es posible resaltar algunas palabras importantes utilizando la estilización de  **Letras Negritas**, para la que  colocaremos dos * antes y después de la palabra a resaltar, *Letras Cursivas* para que solo ponemos un * antes y despúes de las palabras, ***Letras Cursivas y Negritas*** colocanto 3 *  y por último  <ins>texto subrayado </ins> encerrando la frase o palabras entre la etiqueta \<ins> y la etiqueta de cierre \</ins>


## 5. Cuadores de Código o Reseñas  (BLOCKQUOTES)

Esto elementos son utilizados para resaltar intrucciones específicas para la instalación , configuración y/o inicialización del proyecto, para mostrar secciones de código fuente , y se maqueta utilizando el síbolo de mayor qué  (>) antes del texto.

**EJEMPLO:**

Para listar las carpetas y archivos desde una terminal de comandos en el sistema operativo de Windos debmos usa el comando: 

> C:/dir

Después oprimimos la tecla *Enter*.

También podemos poner texto multilínea

**EJEMPLO:**

Pasos para instalar MySQL
> - Descargar el archivo instalador desde la página oficial  www.mysql.com
> - Instalar el Servidor de Bases de Datos
> - Definir el puerto y contraseña para el usuario **root**
> - Inicializar el serviro de bases de datos
> - Conectarnos a la base datos para verificar que se instaló correctamente.


## 6. Listas Ordenadas y No Ordenadas

Si en nuestra documentación necesitamos incluir información en modo de lista, es decir un elementro , tras otro podremos hacerlo utilizado las listas ya sea usando viñetas o numeración definida.

Para el uso de viñetas  solo es necesario agregar un (-) antes del texto

**EJEMPLO:**
Mi tipo favorito de música es:
- Balada
- Rock
- Electro House
- Pop

Para enlistar elementos en órden numérico solo basta con anteponer un número antes del texto con un (.)

**EJEMPLO:**
Para crear un nuuevo repositorio en **GitHub** debo:

1. Crear una cuenta de GitHub
2. Logearme con mi cuenta de GitHub
6. Ir a la página principal de mi perfil (Home)
7. En el menú lateral buscar el botón que dice **Nuevo Repositorio**
8. Asignarle un nombre
50. Definir si el proyecto es:
    - **Público:** Cualquier persona podra ver y consultar el contenido de mi proyecto
    - **Privado:**  Solo aquella persona que yo autorice podrán visualizar y  modificar el contenido de mi proyecto.
1. Agregar un primer archivo documetal *README:md*
1. Aprobar la creación del repositorio.


## 7. Ligas e Hipervínculos (LINKS)

Estas son utilizadas para redirigir a archivos, secciones dentro o fuera de nuestro repositorio. Se maquetan utilizando corchetes \[ \], inmediatamente de parentesis con la url destino \( \).

**EJEMPLO**

Mi buscador favorito es:  [Google](https://www.google.com)

Esta documentación fué creada por: ***M.T.I. Marco Antonio Ramírez Hernández***

<marco.ramirez@utxicotepec.edu.mx>

### 8. Tablas (TABLES)

Si la documentación lo requiere podemos presentar información en formato de tablas con filas y columnas , para maquetarlas podemos utilizaqr el caractér |  para delifitar las columnas y  -  para delimitar las filas

**EJEMPLO:**

-----------------------------------------
| Encabezado 1 | Encabezado 2 | Encabezado 3 | Encabezado 4 |
|-------------|---------------|---------------|--------------|
|Fila 1 Celda 1 | Fila 1 Celda 2 | Fila 1 Celda 3| Fila 1 Celda 4|
|Fila 2 Celda 1 | Fila 2 Celda 2 | Fila 2 Celda 3| Fila 2 Celda 4|
|Fila 3 Celda 1 | Fila 3 Celda 2 | Fila 3 Celda 3| Fila 3 Celda 4|
