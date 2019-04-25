---
diseño: página
título: sitio simple
lema: Sitios web fáciles con GitHub Pages
descripción: tutorial mínimo sobre cómo crear un sitio web sencillo con GitHub Pages
---

[Github Pages] (https://pages.github.com) proporciona una forma sencilla de hacer un
sitio web utilizando
[Markdown] (https://daringfireball.net/projects/markdown/) y
[git] (https://git-scm.com).

Para mí, los aspectos dolorosos de hacer un sitio web son

- Trabajando con html y css.
- Encontrar un sitio de alojamiento.
- Transferir cosas al sitio de alojamiento.

Con [GitHub Pages] (https://pages.github.com), simplemente escribe las cosas en
[Markdown] (https://daringfireball.net/projects/markdown/),
[GitHub] (https://github.com) aloja el sitio por ti, y solo presionas
material a tu repositorio de GitHub con `git add`,` git commit`, y
`git push`.

Si amas [git] (https://git-scm.com/) y
[GitHub] (https://github.com), te encantará
[Páginas de GitHub] (https://pages.github.com), también.

Los sitios utilizan [Jekyll] (https://jekyllrb.com/), un
[ruby] (https://www.ruby-lang.org/en/) [gem] (https://rubygems.org/), para
convertir archivos de Markdown a html, y esta parte está hecha
automáticamente cuando empujas los materiales a la rama `gh-pages`
de un repositorio GitHub.

El [GitHub] (https://pages.github.com) y
[Jekyll] (https://jekyllrb.com) documentación es genial, pero pensé que
Sería útil tener un tutorial mínimo, para aquellos que solo quieren
Ponte en marcha inmediatamente con un sitio simple. Para algunos lectores, lo que GitHub
Puede que sea más simple y más directo. Pero si solo quieres crear
un sitio como el que estás viendo ahora, sigue leyendo.

Comience leyendo la [Página de descripción general] (pages / overview.html), que
Explica la estructura básica de estos sitios. Entonces lee
[cómo hacer un sitio web independiente] (pages / independent_site.html). Entonces
lee cualquiera de las otras cosas, como
[cómo probar su sitio localmente] (pages / local_test.html).

- [Visión general] (páginas / resumen.html)
- [Haciendo un sitio web independiente] (pages / independent_site.html)
- [Haciendo un sitio personal] (pages / user_site.html)
- [Haciendo un sitio para un proyecto] (pages / project_site.html)
- [Haciendo un sitio sin jekyll] (pages / nojekyll.html)
- [Probando su sitio localmente] (pages / local_test.html)
- [Recursos] (páginas / recursos.html)

Si algo aquí es confuso (o _wrong_!), O si me he perdido
detalles importantes, por favor
[enviar un problema] (https://github.com/kbroman/simple_site/issues), o (incluso
mejor) fork [el repositorio de GitHub para este sitio web] (https://github.com/kbroman/simple_site),
hacer modificaciones, y enviar una solicitud de extracción.

---

La fuente de este tutorial mínimo es [en github] (https://github.com/kbroman/simple_site).

También vea mis [tutoriales] (https://kbroman.org/pages/tutorials) en
[git / github] (https://kbroman.org/github_tutorial),
[GNU make] (https://kbroman.org/minimal_make),
[knitr] (https://kbroman.org/knitr_knutshell),
[Paquetes R] (https://kbroman.org/pkg_primer),
[organización de datos] (https://kbroman.org/dataorg),
y [investigación reproducible] (https://kbroman.org/steps2rr).