---
title: 'Los dos tipos de Pre-renderizado'
date: '2022-03-25'
---

Next.js tiene dos maneras de pre-renderizado: La **Generación de Sitios Estáticos** *(SSG: Static Site Generation)* o también conocida como Generación Estática y el **Renderizado del lado del Servidor** *(SSR: Server-side Rendering)*. Donde la diferencia está en cuándo se genera el HTML para una página.

- La **generación estática** (SSG) es el método de pre-renderizado que genera el HTML al **momento de compilar**. Por lo cual, el HTML pre-renderizado se _reutiliza_ en cada solicitud.

- La **renderizado del lado del servidor** (SSR) es el método de pre-renderizado que genera el HTML en **cada solicitud**.

Es importante destacar que Next.js te permite **elegir** la manera de pre-renderizado para cada página. Así que, puedes crear una aplicación Next.js "híbrida" mediante el uso de la Generación Estática (SSG) para la mayoría de las páginas; y el Renderizado del Lado del Servidor (SSR) para otras.