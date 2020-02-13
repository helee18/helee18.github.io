docker run -it --rm -v "$PWD:/srv/jekyll" jekyll/jekyll jekyll new blog

docker run -it --rm -p 4000:4000 -v "$PWD:/srv/jekyll" jekyll/jekyll jekyll serve --force_polling

Creamos un repositorio `helee18.gutbuh.io` y al clonarlo introducimos el contenido de la carpeta `blog`.