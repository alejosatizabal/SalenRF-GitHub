# SalenRF-GitHub

git init // Para iniciar una carpeta que tengo en el equipo

git add README.md // Para agregar este archivo <br>
git add . // Para agregar todos los archivos de esa carpeta<br>
git commit -m "Descripción del commit"<br>
git branch -M main<br>
git push -u origin main<br>

----------

// Forma simple<br>
git add .<br>
git commit -m "Etiqueta"<br>
git push<br>

----------

git log     // muestra lo que se ha hecho<br>
git show    // muestra lo hecho, mas especifico<br>
git branch  // muestra las ramas que tenemos, si hay más de 2, en cual estamos<br>
git branch rama2  // se crea rama llamada 'rama2', contenido de la rama actual<br>
git checkout rama2  // nos cambiamos a 'rama2'<br>

// Cuando se intenta hacer C'push' sobre esta nueva rama, se debe teclear:<br>
_______git push --set-upstream origin rama2<br>

git pull origin rama2 // copio lo de la 'rama2' a la principal<br>
