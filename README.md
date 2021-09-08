# SalenRF-GitHub

git init // Para iniciar una carpeta que tengo en el equipo

git add README.md // Para agregar este archivo
git add . // Para agregar todos los archivos de esa carpeta
git commit -m "Descripción del commit"
git branch -M main
git push -u origin main
----------
// Forma simple
git add .
git commit -m "Etiqueta"
git push
----------
git log     // muestra lo que se ha hecho
git show    // muestra lo hecho, mas especifico
git branch  // muestra las ramas que tenemos, si hay más de 2, en cual estamos
git branch rama2  // se crea rama llamada 'rama2', contenido de la rama actual
git checkout rama2  // nos cambiamos a 'rama2'

// Cuando se intenta hacer C'push' sobre esta nueva rama, se debe teclear:
    git push --set-upstream origin rama2

git pull origin rama2 // copio lo de la 'rama2' a la principal
