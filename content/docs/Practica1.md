---
weight: 999
title: "Practica 1"
description: "Despliegue de página web estática"
icon: "article"
date: "2023-10-05T10:41:40+02:00"
lastmod: "2023-10-05T10:41:40+02:00"
draft: true
toc: true
---
# Despliegue de página web estática
Para esta primera práctica usaremos Hugo, un moderno framework para la creación de sitios web de propósito general. Está escrito completamente en Go.

Hemos seleccionado la combinación del framework Hugo + un servidor VPS privado.

Para aplicarle estilo a la web generada por Hugo, he escogido el tema [Lotus Docs](https://lotusdocs.dev/docs/overview/). Para que funcione correctamente este tema con Hugo, hay que tener Hugo en su versión [0.119.0](https://github.com/gohugoio/hugo/releases/download/v0.119.0/hugo_0.119.0_linux-amd64.deb)

### Configuración de Hugo
En el archivo `config.toml` hemos configurado distintos parámetros de Hugo para el correcto funcionamiento de la página, como vemos en la captura:

![Captura del archivo config.toml](../../../public/images/image.png)

En el archivo podemos ver la siguientes configuraciones: 
- `module` estamos importando el tema 
- `params` estamos configurando el tipo de letra deseado para la página
- `params.social` configuramos los iconos de redes sociales de la parte superior de la página
- `params.docs` habilitamos la opción de modo oscuro, y que aparezcan iconos en la barra de navegación.