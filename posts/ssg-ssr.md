---
title: 'Cuándo usar Generación Estática vs. Renderizado del lado del servidor'
date: '2022-03-27'
---

Siempre que sea posible, con o sin datos, utiliza la **Generación Estática** *(SSG: Static Site Generation)*. Ya que tu página se construye una vez y se sirve mediante una **red de distribución de contenido** (CDN). Esto permite obtener una versión en caché del contenido almacenado en el servidor más cercano a tu ubicación geográfica. Lo cual es más rápido que renderizar la página en cada solicitud.

De manera que, podrás usar la Generación de Sitios Estáticos (SSG) para muchos tipos de páginas, como en los casos siguientes:

- Páginas de marketing
- Publicaciones de blog
- Listados de productos de comercio electrónico (E-commerce)
- Ayuda y documentación

Por otra parte, debería preguntarte: ¿Puedo pre-renderizar esta página **antes** de que el usuario la solicite? Si la respuesta es afirmativa, entonces debe elegir la Generación estática (SSG).

No obstante, la Generación Estática (SSG) **no** es una buena idea si no puede renderizar previamente una página antes que el usuario la solicite. Tal vez tu página muestre datos actualizados con frecuencia y el contenido de la página cambie con cada solicitud.

En este caso, lo correcto es usar la **Renderización del lado del servidor** *(SSR: Server-Side Rendering)*. Por supuesto, será más lento, pero la página pre-renderizada siempre estará actualizada. También, puedes omitir la representación previa y usar JavaScript del lado del cliente para completar los datos.