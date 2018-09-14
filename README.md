# Ejercicio 1
Capacitación: Git, bash y docker
Integrantes:
- Gerardo Sanchez
- Jairo Rojas



PREGUNTAS : 

1. ¿Qué es y para qué sirve GIT?
	Es un sistema de control de versiones, que sirve para llevar el versionado de un proyecto especifico.
2. ¿Que es Github o bitbucket?
	Son contenedores de un conjunto de archivos que trabajan con git para el control de versiones.
3. ¿Qué es y para qué sirve el SSH?
	Es protocolo de autenticacion, que sirve para poder conectarte con un repositorio remoto, sin necesidad de usar otro tipo de credenciales.
4. ¿Que pasa si cambio de PC? ¿Tendré que generar el SSH nuevamente?¿Por qué?
	Al cambiar de PC se pierden tus configuraciones SSH, por ello se tiene que generar una nueva SSH para conectarte a un repositorio remoto, por que se guardan en carpetas propias de tu usuario.
5. ¿Qué es markdown? ¿Para qué sirve?
	Es un formato de lenguaje de marcado ligero, que sirve para convertir el lenguaje en HTML válido.
6. ¿Cómo inicializo y configuro un proyecto de git?
	Para inicializar un proyecto en git, nos ubicamos en repositorio y agregamos el comando **git init**.
	Para configurar las credenciales en git como el username usamos **git config --global user.name "John Doe"** y para agregar el email **git config --global user.email "johndoe@example.com"
**

Scrum Master: **Pedro Vega** 


PREGUNTAS:
1. ¿Para qué ayuda el `git stash`?
	Sirve para poder guardar cambios en memoria sin necesidad de realizar un commit.
2. ¿Cuál es la diferencia entre `git stash pop` y `git stash apply`?
	**git stash pop: ** Elimina los cambios de memoria y lo aplica en la rama.
	**git stash apply: ** Copia los cambios en la rama, sin eliminarlas en memoria.
3. ¿Qué significa el modo interactivo del `git rebase`?
	Significa que puedes interactuar o editar los commit antes de realizar el rebase.
4. ¿Cual es la diferencia entre la shell y la terminal?
	**Shell :** Es la linea de comando que ejecutamos en la consola.
	**Consola :** Es la UI que nos permite ejecutar la linea de comandos.
5. ¿Que hace estos comandos? `git clone`, `git status`, `git add`, `git commit`, `git push`, `git checkout`, `git stash`, `git rebase`, `git merge`, `git branch`, `git push`,
	**git clone :** Clona un repositorio local y remoto.
	**git status :** Lista todas las modificaciones para realizar un commit.
	**git add :** Añade al stage todos los cambios realizados.
	**git commit :** Agrega un HASH a todos los cambios realizados.
	**git push :** Sube los cambios locales a la rama remota.
	**git checkout :** Permite moverte entre ramas especificadas.
	**git stash :** Guarda en memoria los cambios trackeados.
	**git rebase :** Es el proceso de mover o combinar una secuencia de commits a un nuevo commit.
	**git merge :** Es el proceso de combinar ramas en un nuevo commit.
	**git branch :** lista todas las ramas locales.
