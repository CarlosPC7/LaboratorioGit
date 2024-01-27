# Paso 1 Crear repositorio en local
Hemos creado carpeta LaboratorioGit y nos hemos introducido en ella con el comando cd
Después, hemos creado la carpeta src con sus archivos index.js e index.html dentro, además del package.json y del readme.me
Realizamos npm install y npm start
Creamos archivo .gitignore
Aplicamos git init y git status y nos damos cuenta que debemos añadirlos al stagging
Para ello, git add. y git commit -m "Hola Laboratorio Git"
# Paso 2 Subir repositorio a Github
Creamos repositorio en Github, público y sin archivo readme.md
Copiamos la url SSH
Realizamos conexión de local y nube con git remote add origin
Para subir de primeras la carpeta local a la nube y github lo entienda, usamos git push --sep-upstream
Visualizamos que lo hemos realizado correctamente y ya está subido en GitHub
# Paso 3 Hacer un commit y un push
Creo los archivos texto fichero 1 y fichero 2
Lo añadimos al staging, comiteamos y los subimos a GitHub
# Paso 4 Crear una rama
Creanos la rama development y nos metemos en ella
Dentro de la rama development, creamos los ficheros 3 y 4, y modificamos el fichero 1 y 2
Hacemos commit y los subimos a GitHub
# Paso 5 Hacer un merge
Volvemos a la rama master
Realizamos un merge de la rama development