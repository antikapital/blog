---
layout: post
title: "Blogeando desde terminal con Jekyll"
description: "Sobre uso de Jekyll"
tags: [blog, diseño web, jekyll]
share: true
---
 
#### La tecnología, como la vida, da muchas vueltas

Recuerdo que mi *de-formación* tecnológica me llevó a conocer primero que nada a [Drupal](http://drupal.org) como herramienta de publicación, y quedé impactado por lo simple, potente y flexible del CMS, yo era un novato y me enganchó.


Después aprendí sobre los lenguajes que realizaban esa magia, una mezcla compleja de html, css, php, mysql, javascript y una lista que cada día crece de manera sorprendente.

Se trata de la **web dinámica**, esta tecnología es soporte del uso social de internet, posibilitó la creación del blog personal, y es la base de las redes sociales actuales; la mayoría de los constructores web optamos por desarrollar de este modo (con [Wordpress](http://wordpress.org), Joomla, Drupal, etc.)


Para explicar rápidamente qué hace la web dinámica diremos que construye las páginas "al vuelo", una especie de procesador en el servidor que *interelaciona* información, formatos, diseño, bases de datos, etc.


Resultó inovadora porque permite actualizar muy rápido, ordenar y automatizar tareas que en websites estáticos es muy tedioso.


Por su parte los sitios estáticos se componen de archivos html simples con información definida; para cambiarla se tiene que editar el documento y sustituirlo en el servidor, un martirio si los cambios son frecuentes.

###Web dinámica vs estática

Parecía que la web estática estaba condenada a desaparecer, o sería simplemente una anécdota nostálgica, pero las cosas estan cambiando.


Recientemente, han aparecido algunos CMS que compilan texto plano, como [Jekill](http://jekyllrb.com), [Sculpin](http://sculpin.io) o [[s]press](http://spress.yosymfony.com) (hay muchos más), que tienen como objetivo generar archivos básicos en html para alojarlos en nuestro servidor, sin ningun requerimiento especial.


La gran ventaja de este método es que la compilación del website no la hace el servidor, sino nuestra maquina local, ahorrando recursos y haciendo veloz nuestro sitio; además de hacerlo más seguro.


Funcionan maravilloso usando un sistema de control de versiones, puedes administrar tu contenido, categorización y personalizar el diseño sin límites.

### No para todos, ni para todo

Esta tendencia de desarrollo es una alternativa real para sitios web básicos, landing pages, o curriculums online; y complementada con un servicio de sincronización (git, o rsync desde ssh) es también muy práctica para mantener un blog, siempre que te guste el trabajo desde la terminal, y prefieras trabajar con un editor simple que con un WYSIWYG, si no es así te vendrá mejor continuar con Wordpress.


Si el website que trabajas requiere manejo conplejo de datos, esta alternativa tampoco será util, yo usaría Drupal.


Yo por ahora estoy trabajando con [Jekill](http://jekyllrb.com), porque me parece sencillo y está generando comunidad de usuarios gracias a su posibilidad de alojarlo en un proyecto de [Github](http://github.com), también he probado [S]press, recomiendo ambos.