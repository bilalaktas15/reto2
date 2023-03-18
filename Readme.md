1- Necesitamos hacer `git init` en la carpeta dónde queramos iniciar el repositorio de git
2- Una vez hecho esto, podemos añadir archivos con `git add .`
3- Para añadir estos archivos al historial de versiones podemos usar `git commit` seguido de `-m` para hacer un mensaje de commit
Ejemplo: `git commit -m "Added Readme.md`

4- Si quisieramos conectar este proyecto a un repositorio remojo como uno de Github deberíamos obtener la url de este repositorio
`git remote add origin https://github.com/{{cuenta}}/{{repositorio}}.git`
5- Una vez conectado podemos hacer `git push`