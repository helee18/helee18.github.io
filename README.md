docker run -it --rm -v "$PWD:/srv/jekyll" jekyll/jekyll jekyll new blog

_Dentro de blog_
docker run -it --rm -p 4000:4000 -v "$PWD:/srv/jekyll" jekyll/jekyll jekyll serve --force_polling

Borramos la carpeta `sites`.

Creamos un repositorio `helee18.guthub.io` y al clonarlo introducimos el contenido de la carpeta `blog`.

Si buscamos en el navegador `https://helee.18.github.io` tiene que salirnos la página.

Los archivos de post se llaman `2020-02-20-nombre.md`.

Dentro del archivo copiamos la cabecera correspondiente.

La sintaxis para añadir una imagen es:
```
![Almeria]({{ site.url }}/images/2020-02-20/grl.jpeg)
```

Y la imagen ha de estar en la carpeta images.