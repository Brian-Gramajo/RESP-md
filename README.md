>>> # *PROGRAMACIÓN II*
## Alumno: *Brian Gramajo*

---
### *EJERCICIOS:*

---
#### **1.** ¿Qué es git?

Es un sistema de control distribuido para distintas versiones de un programa, es el más popular entre todos, es open source. 

Nos ayuda a tener un listado de los cambios que realizamos en nuestro programa, de esta manera podemos controlar las diferentes versiones del mismo.

---
#### **2.** ¿Por qué queremos utilizar git?

Queremos utilizarlo, porque es un sistema de control distribuido, podemos trabajar con un repositorio de código con múltiples desarrolladores y estos van a poder modificar dicho código, cada uno de estos tienen una copia local del código, es decir, que los cambios siempre van a estar actualizados. 
 
También nos permite ver un registro de todas las líneas de códigos, desde todas las versiones de modificación que se realicen. Esto permite volver a una versión anterior que nos sea mucho más eficiente. Ya que guarda cada una de las distintas versiones que sean ido creando.
 
---
#### **3.** ¿Qué es el bash que instala git?

El bash que instala git, es una consola con mejores funcionalidades, trae todos los conceptos del sistema operativo Linux.

---
#### **4.**  Describa los estados (working directory, staging area, repository).

+ **Working Directory:** es donde nos encontraremos trabajando con todos nuestros archivos.
+ **Staging Area:** es donde iremos agregando todos los archivos que vamos a preparar para el guardado con las distintas versiones que realizamos en working directory.
+ **Repository:** es donde se guardan finalmente todos los cambios.

---
#### **5.** Describa el flujo para crear un nuevo repositorio git.

1. Creamos una carpeta donde guardaremos nuestro proyecto (por ejemplo la creamos en el escritorio con el nombre “proyecto”). Luego arrastramos la carpeta a nuestro editor de código donde comenzara nuestro proyecto.

2. Luego debemos abrir un terminal (dando segundo clic en la carpeta del proyecto a realizar – luego clic en la opción  **Git Bash Here** (para abrir un terminal).
3.  Se abrirá una consola, y deberemos entrar a la carpeta del proyecto desde allí. Para ello escribiremos: **`cd Desktop`+ Enter** (entraremos al escritorio donde se guardó la carpeta del proyecto).
 
4. Para ingresar a la carpeta, escribiremos: **`cd proyecto`** (o el nombre que le hallamos dado a la carpeta de nuestro proyecto) **+ Enter**
 
5. Estamos listos para usar. 

---
#### **6.** Describa el flujo para agregar un archivo simple al repositorio.

*El primer comando de git que nos ayudara a iniciar un proyecto y controlar sus versiones, escribiremos:*

1.  **`git init` + Enter** (Esto creara una nueva carpeta en el proyecto que se encargara de guardar todos los cambios de nuestro código) 

2. Para ver el estado de nuestros archivos, iniciaremos el comando: **`git status` + Enter** (Para ver los archivos que se están trabajando) 
 
3. Ingresamos: **`git add` +** nombre del archvio que queremos agregar **+ Enter** (Para agregar un archivo al stating area). 
 
4. Repetimos este último comando para agregar todos los archivos que queremos seguir, luego podemos verificarlos ingresando: **`git status`** 

---
#### **7.** Describa el flujo para cambiar el archivo agregado y guardar los cambios en el repositorio.

1.  Para crear un primer punto de control de nuestro código, Ingresamos: **`git commit` + Enter** (esto nos pedirá que confirmemos que desarrollador a ejecutado los cambios) 
 
2. Para configurar el email de este usuario, ingresaremos: **`git config –global user.email` +** el email que queramos **+ Enter** (ya configuramos el email del usuario que realiza los cambios) 
 
3. Ahora configuramos el nombre del usuario: **`git config –global user.name`** + el nombre del usuario **+ Enter**
 
4. Para nuestro punto de partida del proyecto o inicio de este, ingresaremos: **`git comit` + Enter**.

5. Abrirá un editor de código en el mismo terminal.
 
6. Para escribir allí deberemos presionar **i** Luego escribiremos el nombre del archivo.
 
7. Presionamos: **ESC** y luego escribimos **`:qw`**  . Esto agregara todos los archivos y serán insertados. De esta manera podemos seguir las versiones del programa.

---
#### **8.** ¿Cómo hago para ignorar un archivo o carpeta?

1. Para ignorar un archivo o carpeta, debo crear la carpeta en el compilador con el nombre: **.gitignore** ahí dentro se guardara los archivos que deben ignorarse.
 
2. Dentro de **.gitignore** escribiré el nombre del archivo o carpeta que deseo ingresar para ser ignorado

3. Luego en la consola de git, escribo: **`git add .gitignore` + Enter**


---
#### **9.** Explique qué es un branch. Dé un pequeño ejemplo de cómo haría uno.

Son distintas versiones alternativas de nuestro proyecto y podemos movernos entre ellas para poder editarlas.

El Branch, por ejemplo, lo puedo utilizar para agregar una nueva funcionalidad a mi programa, pero de la cual no estoy del todo seguro si será aplicado al final de este. Ya que sea solo experimental o intente algo nuevo. Esto puede lograr que el programa no funcione como se quiere. Con esta herramienta si deseamos quitar esta rama lo podemos hacer sin perjudicar al resto del código.

	
---
#### **10.** ¿Qué hago con `git add .`?

Git add se utiliza para poder pasar los archivos del working dirrectory al staging área en nuestro proyecto.

---
#### **11.** ¿Cómo cambiamos de un branch a otro?

*Para cambiar de una rama o branch a otra, debemos:*

1. Ingresamos: **`git Branch` + Enter**

2. Luego ingresamos: **`git checkuot` + “**(el nombre de la rama en la que deseamos ingresar entre comillas)**” + Enter**

3. De esta manera habremos cambiado de rama del Branch.

