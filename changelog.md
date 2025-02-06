# CHANGELOG
---
## Version 0.1.0
- Esta es la primera versión, enfocada principalmente en la **estructura** y **funcionalidad** de la aplicación.
- Se modifica el contenido generado de la página de inicio.
- Se mantienen los blogs de demostración. Para que no se rompa el estilo.
- Footer modificado.
- Formato de fechas en blog modificado.
- Header modificado.
- Se cambia el idioma de la página de inicio y BlogPost.astro
- Se crea la logica para mostrar los blogs solo cuando esten is Published:true
### Archivos modificados
- ***bun.lock***
- ***package.json***
- ***src/components/BaseHead.astro***
- ***src/components/Footer.astro***
- ***src/components/FormattedDate.astro***
- ***src/components/Header.astro***
- ***src/consts.ts***
- ***src/content.config.ts***
- ***src/content/blog/first-post.md***
- ***src/content/blog/markdown-style-guide.md***
- ***src/content/blog/second-post.md***
- ***src/content/blog/third-post.md***
- ***src/content/blog/using-mdx.mdx***
- ***src/layouts/BlogPost.astro***
- ***src/pages/about.astro***
- ***src/pages/blog/[...slug].astro***
- ***src/pages/blog/index.astro***
- ***src/pages/index.astro***
### Archivos creados
- ***changelog***