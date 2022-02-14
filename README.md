# creamos un nuevo repositorio y lo inicializamos con:
git init josep

# ahora abrimos el repositorio en el directorio con:
cd josep

# creamos el fichero README.md
touch README.md

# editamos el READMY.md
git add README.md

# ahora haremos un commit
git commit -m "add README to initial commit"

# el repositorio creado lo pasaremos a nuestro github
git remote add origin https://github.com/joseplluissastre2002/josep.git

# Y por ultimo hacemos un push
git push --set-upstream origin main
