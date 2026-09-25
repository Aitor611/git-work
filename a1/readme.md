<center>

# TÍTULO DE LA PRÁCTICA


</center>

***Nombre:Aitor Martin Martin***
***Curso:*** 2º de Ciclo Superior de Desarrollo de Aplicaciones Web.

### ÍNDICE

+ [Introducción](#id1)
+ [Objetivos](#id2)
+ [Material empleado](#id3)
+ [Desarrollo](#id4)
+ [Conclusiones](#id5)


#### ***Introducción***. <a name="id1"></a>

En esta prática hemos trabajado con Git y Github para aprender a gestionar un proyecto de forma colaborativa entre dos usuarios.

Durante esta actividad nos hemos manejado con las herramientas que ofrece Github, como puede ser hacer forks, copiar ramas, compartir trabajos, issues, pull request, etc...

Esta practica ha sido realizada entre User1= Aitor Martín Martín, el User2= Pablo Alvarez Hernandez.

#### ***Objetivos***. <a name="id2"></a>

- Crear un repositorio y trabajar con el.

- Crear un fork para trabajar en diferentes entornos.

- Creación y resolución de issues.

- Trabajar en diferentes ramas.

- Hacer uso de pull request y solucionar conflictos.

- Hacer uso de un tag.


#### ***Material empleado***. <a name="id3"></a>

- Git.

- Github

- Maquinas virtuales con Git(usamos otra maquina en casa que no es la de clase).

- Un editor de codigo

- Un repositorio git 

#### ***Desarrollo***. <a name="id4"></a>

1. User1: Aitor, User2: Pablo

2. User1, creo el repositorio 'git-work'

3. User1, clonamos el https://github.com/Aitor611/git-work.git, añadimos la carpeta a1 con los arhivos propocionados por el profesor, se añaden al main, se hace un commit y se hace un git push main.

4. User2, crea desde github un fork con https://github.com/Aitor611/git-work.git, con esto https://github.com/Pabliins/git-work.git.

5. User2, clona su fork https://github.com/Pabliins/git-work.git.

6. User1, crea el Issue 'Add cusom text for starup contents'

7. User2, crea la rama custom text con git checkout -b custom-text, en este paso modifica index.html elegimos llamar a la empresa TechCanarias y añadirle unos servicios, con esto se hace un push en su fork.

8. User2, con el cambio a index.html crea un Pull Request.

9. User1, prueba en su maquina local el cambio, crea un remoto que se llama upstream, en este implanto un cambio añadiendo mas información para la pagina.

10. Los dos users, tienen una conversación a traves del pull request y se incluye un cambio mas.

11. User1, después de la conversación User1 aprueba los cambios que se han realizado y puede cerrar el issue se actualiza con un git pull origin main.

12. User2, también incorpora los cambios en upstream usando git remote add upstream https://github.com/Aitor611/git-work.git, este sube los cambios a su fork.

13. User1, crea otra Issue que es Improve UX whit cool colors.

14. User1, cambia el archivo cover.css la linea diez por un color morado.

15. User1, hace un commit en su local pero no hace un push, se hace un git add cover.css y un commit.

16. User2, se hace un git pull origin main y crea una nueva rama llamada cool-colors, abre el cover.css y cambia el color a verde fuerte, git add cover.css hace un commit y hace un push.

17. User2, hace otro pull request para los cambios de colores.

18. User1, prueba el pull request, se ve que tiene un conflicto haciendo git fetch upstream, git log --oneline, git fetch origin y se con un comando se crea una rama git checkout -b cool-color-test upstream/cool-colors y se hace un merge origin/cool-colors.

19. User1, modifica la linea 11 con text-shadow: 2px 2px 8px lightgreen.

20. User1, hace un commit arreglando y añadiendo los cambios de cover.css y hace un git push origin main.

21. User1, crea una etiqueta con git tag 0.1.0 se comprueba el tag tanto en local como en github


#### ***Conclusiones***. <a name="id5"></a>

Como conclusión hemos aprendido a poder trabajar desde dos ordenadores de forma remota, pudiendo hacer cambios y modificaciones, para no pisarnos en ningún momento y poder hacer cambios de manera ordenada haciendo un entorno de trabajo más comodo.
