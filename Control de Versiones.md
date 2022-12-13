1. Ademas de Git, ¿que otros sistemas de control de versiones existen?
	- CVS, Subversion, SourceSafe, ClearCase, Darcs, Bazaar, Plastic SCM, Git, SCCS, Mercurial, Perforce, Fossil SCM, Team Foundation Server.
2. En Git, ¿qué tres áreas existen?
	- Git Directory
	- Working Directory
	- Staging Area
3. Busca en Internet un buen tutorial de GIT y realízalo. ¿De qué tutorial se trata?
	- Curso acelerado de Git y GitHub para principiantes (https://www.youtube.com/watch?v=SWYqp7iY_Tc)
	- En el tutorial se ve todos los comandos basicos y mas importantes de Git y GitHUb
4. Visualiza el siguiente video y responde a las cuestiones que aparecen más abajo.
	- [https://www.youtube.com/watch?v=uR6G2v_WsRA](https://www.youtube.com/watch?v=uR6G2v_WsRA)
5. En Git, ¿para qué sirve el comando `git config`?
	- Para definir valores de configuración de Git a nivel de un proyecto global o local.
6. En Git, ¿para qué sirve el comando `git init`?
	- Crea un nuevo repositorio de Git
7. En Git, ¿para qué sirve el comando `git clone`?
	- Para apuntar a un repositorio existente y clonar o copiar dicho repositorio en un nuevo directorio, en otra ubicación.
8. En Git, ¿para qué sirve el comando `git status`?
	- Muestra el estado del directorio de trabajo y del área del entorno de ensayo
9. En Git, ¿para qué sirve el comando `git add`?
	- Añade un cambio del directorio de trabajo en el entorno de ensayo
10. En Git, ¿para qué sirve el comando `git commit`?
	- Para confirmar una instantánea del directorio del entorno de ensayo en el historial de confirmaciones de los repositorios.
11. En Git, ¿para qué sirve el comando `git log`?
	- Para explorar el historial del repositorio
12. En Git, ¿para qué sirve el comando `git reset HEAD nombrearchivo`?
	- Es un comando potente que sirve para deshacer los cambios locales en el estado de un repositorio de Git
13. En Git, ¿para qué sirve el comando `git checkout -- nombrearchivo`?
	- Sirve para deshacer los ultimos cambios sobre el proyecto o sobre un archivo en concreto desde que se hizo el último cambio.
14. Visualiza el siguiente video y responde a las cuestiones que aparecen más abajo.
	- [https://www.youtube.com/watch?v=FyAAIHHClqI](https://www.youtube.com/watch?v=FyAAIHHClqI)
15. En Git, ¿para qué sirve el comando `git branch`?
	- Te permite crear, enumerar y eliminar ramas, así como cambiar su nombre.
16. En Git, ¿para qué sirve el comando `git checkout`?
	- Te permite desplazarte entre las ramas creadas por git branch
17. En Git, ¿para qué sirve el comando `git merge`?
	- Permite tomar las líneas independientes de desarrollo creadas por git branch e integrarlas en una sola rama.
18. En Git, explica cómo funciona la fusión (merge) de tipo fast-forward.
	- Realizar fusiones de avance rápido en las situaciones donde exista un proceso lineal desde el extremo de la rama actual y que se extienda hasta la rama de destino
19. En Git, explica cómo funciona la fusión (merge) de tipo 3-way.
	- La fusión de _3-way_ se basa en 3 confirmaciones diferentes:
		-   El ancestro común.
		-   La punta de la rama Master.
		-   La punta de la rama de funciones.
	- Git identifica estas tres confirmaciones mediante instantáneas. Git compara el ancestro común con cada una de las confirmaciones de punta.