# 1.- En que año se desarrolló Git?
> Git fue desarrollado en el año 2005 por Linus Torvalds, creador del kernel de Linux. En unas
pocas semanas, desde principios de abril de 2005 hasta mediados de julio del mismo año, Git se
convirtió en la herramienta de publicación y administración de versiones del kernel de Linux. En
diciembre del mismo año, se lanzó la versión 1.03.

# 2.- Como se hace la creación de un repositorio en Github? (Adjunte capturas de pantalla y explique si es necesario).
1. Primer paso.- Dar clic en New, posterior a eso se nos abrirá una nueva ventana

2. Segundo paso.- Dar un nombre al repositorio, además de una descripción y seleccionar si el
repositorio será público o privado, así como también añadir una licencia de ser necesario y dar
clic en crear repositorio.

3. Tercer paso.- De haber sido realizado correctamente los dos pasos anteriores deberán aparecer la siguiente ventana

Finalmente, solo queda implementar el repositorio en el proyecto que sea necesario.

# 3.- Nombre 10 comandos de Git, además, explicando para que sirven.
```git init``` :Este comando se utiliza para inicializar un nuevo repositorio Git en el directorio actual.

```git clone <url>``` :Este comando se utiliza para copiar un repositorio Git existente desde una URL.

```git add <archivo>``` :Este comando agrega un archivo al área de preparación para el próximo
commit.

```git commit -m "<mensaje>"``` :Este comando guarda los cambios en el repositorio con un mensaje
descriptivo.

```git status``` :Este comando muestra el estado del repositorio Git actual, como los cambios que
están en el área de preparación, pero aún no se han confirmado.

```git pull``` :Este comando actualiza el repositorio local con los cambios del repositorio remoto.

```git push <remoto> <rama>``` :Este comando envía los cambios confirmados al repositorio remoto.

```git branch <nombre_de_rama>``` :Este comando crea una nueva rama en el repositorio Git.

```git checkout <nombre_de_rama>``` :Este comando cambia a la rama especificada.

```git merge <nombre_de_rama>``` :Este comando fusiona la rama especificada con la rama actual.

# 4.- Una vez completado, la pregunta 3, diríjase al siguiente enlace 
#### https://education.github.com/git-cheat-sheet-education.pdf y comente si ya sabía de su existencia sobre las denominadas (cheatsheet), además diga si algo le llamo la atención.
> Si sabia acerca de los cheatsheets, lo que me llamo la atención es la forma en la que están
interpretados los temas los cuales deben estar en un orden correcto para poder asimilar de que
trata el tema que se esta presentando y así captar la atención del que lo está leyendo.

# 5.- Volviendo al segundo paso, si usted creo correctamente un repo (repositorio) haremos lo siguiente:

#### Cree una carpeta llamada HW01 en su escritorio, e ingrese a esa carpeta desde la terminal de Windows o su línea de comandos favorita, a continuación, ingresamos el siguiente comando:

Una vez abierto el editor de código, creamos el siguiente archivo y código:

Para subir nuestro código en nuestro repositorio creado debemos seguir los siguientes pasos:
1. Primer paso.- Con el comando git init iniciamos el repositorio en este caso en nuestra carpeta HW01

2. Segundo paso.- El comando git status nos permite ver que archivos fueron creados y actualizados

3. Tercer paso.- Con el comando git add . añadimos todos los archivos realizados a nuestro repositorio

4. Cuarto paso.- Con el comando git commit -m “” añadimos un comentario acerca del cambio o tarea
que realizamos, así mismo nos indica cuantos cambios e inserciones tuvimos.

5. Quinto paso.- Con el comando git Branch -M main cambiamos el nombre de la rama actual a main

6. Sexto paso.- Con el comando git remote add origin url añadimos el nuevo repositorio a nuestro
repositorio Git local

7. Septimo paso.- Con el comando git push -u origin main subimos los cambios de la rama de nuestro
repositorio local a nuestro repositorio remoto origin.

8. Octavo paso.- Si los anteriores pasos fueron realizados correctamente nos dirigimos a nuestro
repositorio de GitHub y deberíamos tener los archivos subidos junto al commit realizado.
