# Ilusionismo con GitHub Pages - Preparación del proyecto

## Cómo se hizo la presentación (versión corta)

Presentación realizada con <a href="https://webslides.tv/">WebSlides</a>, una solución open source creada por <a href="https://twitter.com/jlantunez">@jlantunez</a>, <a href="https://twitter.com/Belelros">@Belelros</a> y <a href="https://twitter.com/luissacristan">@luissacristan</a>.

Se ha habilitado GitHub Pages para que se visualice la presentación a partir de la rama master (se habilita en la pestaña "Settings" del repositorio). La información sobre las distintas formas de configurar GitHub Pages la puedes encontrar en <a href="https://help.github.com/articles/configuring-a-publishing-source-for-github-pages/">Configuring a publishing source for GitHub Pages</a>.

## Cómo se hizo la presentación (versión larga)

Desde el repositorio de GitHub de <a href="https://github.com/webslides/WebSlides"> WebSlides</a> te puedes descargar la última versión (en mi caso la 1.3.0), que es un proyecto web con HTML, CSS y JavaScript que puedes editar para añadir tu contenido.

Como en mi caso quería publicar la presentación con GitHub Pages, lo siguiente que he hecho es crear un repositorio en mi cuenta de GitHub:

- En <a href="https://github.com/"> GitHub</a>, hacer click al botón de “New repository", crear el nuevo repositorio (melies-origen en mi caso), una descripción, hacerlo público e inicializar el repositorio con un README (que es el documento que estás leyendo en este momento).

- Una vez creado, en Settings tienes que habilitar GitHub Pages en master, con lo que tendrás la presentación disponible en la url que te indica en cuanto subas el código a la rama master (en mi caso en la url https://cristinafsanz.github.io/melies-origen/).

- Ir a línea de comandos de tu ordenador y clonar el proyecto en el lugar donde quieres tener el proyecto en local:

    <pre><code>git clone git@github.com/user/repository-name.git</code></pre>

- Nota: Puede que tengas que generar la clave ssh para GitHub si no lo tienes hecho ya: https://help.github.com/articles/generating-a-new-ssh-key-and-adding-it-to-the-ssh-agent/

- Copia el proyecto descargado de WebSlides en la raíz de donde hayas clonado el proyecto, quitando las partes que no necesites, como la mayoría de imágenes, el CHANGELOG.md y el directorio demos.

- Edita index.html con tu presentación (también edita la parte del head del html con tu información), teniendo en cuenta que cada sección es una slide. En mi caso he cogido como referencias dos repositorios que han usado WebSlides para coger ideas de cómo estructurar el contenido en el index.html:

    - Repositorio de <a href="https://twitter.com/xaviju">Xavi Julián</a>: <a href="https://github.com/Xaviju/adalab-OS">adalab-OS</a>

    - Repositorio de <a href="https://twitter.com/eletorro">Elena Torró</a>: <a href="https://github.com/elenatorro/jsday-2017-talk">jsday-2017-talk</a>

- Consulta los tutoriales de WebSlides con los <a href="https://webslides.tv/demos/components">componentes</a> y las <a href="https://webslides.tv/demos/classes">clases CSS</a> para ver qué puedes hacer.  

- Puedes abrir el index.html que has modificado en un navegador y moverte por las slides con los botones que hay en la parte inferior (o con las flechas de teclado) y así ver que el contenido y la presentación son correctos.

- Añade información sobre el proyecto en README.md en lenguaje Markdown: https://github.com/adam-p/markdown-here/wiki/Markdown-Cheatsheet.

- Sube los cambios al repositorio

        git status (para ver los ficheros que tienes que añadir)

        git add (para los ficheros que quieras subir)

        git commit -m "Mensaje para el commit"

        git push origin master

- Y con estos pasos ya tienes la presentación en la url que te habilita GitHub Pages :)

## Guión

### Ilusionismo con GitHub Pages

Bienvenidos a la presentación del proyecto

### ¿Quién soy?

Me presento, soy Cristina Fernández y soy desarrolladora front-end. En la foto estoy en la exposición de un personaje que voy a intentar incorporar al proyecto. Por ahora lo dejo ahí.

### Origen de la ideas

Cada día salen nuevas tecnologías que aprender y para asentar conocimientos lo mejor es practicar, pero ¿dónde alojar las páginas web que vayamos creando? Para el código tenemos GitHub y... para publicar una página web también.

### GitHub Pages

GitHub Pages es un servicio de GitHub para publicar páginas web y mediante este proyecto quiero investigar más sobre las posibilidades que tiene.

### Ilusionimso

¿Por qué usaste en el título de la charla lo de ilusionismo? Porque el servicio GitHub Pages lo veo como una técnica de transformación donde tú alojas el código para tenerlo versionado pero a la vez puedes tener una página web disponible para mostrar.

### Georges Méliès

¿Y el personaje que comentaste al inicio? Se trata de Georges Méliés, un ilusionista que empezó a experimentar con el cinematógrafo para unir las 2 disciplinas, el ilusionismo y el cine.

### GitHub Pages + Front-end + Georges Mélìes

¿Por qué no hacer lo mismo y mezclar todas las ideas para el proyecto? Mezclar GitHub Pages, Front-end y Georges Mélìes.

### Idea inicial

Unir un caso de uso de GitHub Pages con una tecnología que vaya a aprender de Front-end y con temática de Georges Méliès.

### Documentación

Realmente con GitHub Pages y Front-end puedo hacer el proyecto, pero investigaré un poco a ver si puedo combinarlo con el ilusionismo.

### Primer proyecto

Un truco de magia más: El primer proyecto lo he hecho a la vez que esta presentación, ¿cómo es posible? Porque la he publicado con GitHub Pages, he usado WebSlides para crear presentaciones y he introducido a Georges Méliès.

### Gracias

Si tenéis alguna pregunta o sugerencia, me podéis contactar en <a href="https://twitter.com/cristinafsanz">@cristinafsanz</a>.




