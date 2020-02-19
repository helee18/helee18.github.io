docker run -it --rm -v "$PWD:/srv/jekyll" jekyll/jekyll jekyll new blog

docker run -it --rm -p 4000:4000 -v "$PWD:/srv/jekyll" jekyll/jekyll jekyll serve --force_polling

Creamos un repositorio `helee18.guthub.io` y al clonarlo introducimos el contenido de la carpeta `blog`.

Si buscamos en el navegador `https://helee.18.github.io` tiene que salirnos la página.