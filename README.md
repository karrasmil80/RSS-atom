# Proyecto de Feeds RSS y Atom

Este repositorio contiene dos archivos con formatos diferentes para sindicar contenido de noticias:

- `feed.xml` — Feed en formato **RSS 2.0**
- `atom.xml` — Feed en formato **Atom 1.0**

---

## Archivos de feed

### feed.xml (RSS)

Archivo que contiene el feed RSS con las noticias en formato XML clásico para lectores compatibles con RSS.

### atom.xml (Atom)

Archivo que contiene el feed Atom, un estándar más moderno y flexible, con la misma información en formato Atom 1.0.

---

## Cómo acceder a los feeds en la web

Para hacer que estos feeds estén disponibles públicamente en Internet, usamos **GitHub Pages**, un servicio gratuito de hosting estático para sitios web y archivos.

### Pasos para configurar GitHub Pages

1. **Sube los archivos a tu repositorio de GitHub**

   Asegúrate que `feed.xml` y `atom.xml` estén en la raíz del repositorio (o en la carpeta que elijas).

2. **Activa GitHub Pages**

   - Ve a la pestaña **Settings** de tu repositorio.
   - En el menú lateral, selecciona **Pages**.
   - En la sección **Source**, selecciona la rama que quieres usar para publicar (normalmente `main` o `master`).
   - Selecciona la carpeta raíz `/` si tus archivos están en la raíz del repositorio.
   - Haz clic en **Save**.

3. **Accede a tu sitio**

   GitHub te dará una URL pública como: https://tu-usuario.github.io/tu-repositorio/


4. **Accede a los feeds**

- Para el RSS:  
  ```
  https://tu-usuario.github.io/tu-repositorio/feed.xml
  ```
- Para el Atom:  
  ```
  https://tu-usuario.github.io/tu-repositorio/atom.xml
  ```

---

## Uso

Puedes usar estas URLs para suscribirte en lectores de RSS/Atom, agregarlas a tu sitio web, o compartirlas para que otros se mantengan informados con tus noticias.

---

## Nota

- Asegúrate de que el archivo `atom.xml` sea válido y cumpla con el estándar para evitar problemas de lectura en los lectores de feeds.
- Puedes validar tus feeds en servicios como [W3C Feed Validation Service](https://validator.w3.org/feed/).

---

¡Listo! Ahora tienes tus feeds RSS y Atom disponibles en línea vía GitHub Pages.
