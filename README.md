# Escuela Ricardo Gutiérrez — Sitio Web

Sitio web institucional de la Escuela Ricardo Gutiérrez.

🌐 **Sitio web:** https://escuelaricardogutierrez.com.ar

---

## 📁 Estructura del proyecto

El proyecto está organizado de la siguiente manera:

```text
/
├── fotos/
├── CNAME
├── estilo.css
├── index.html
└── README.md
```

### `index.html`

Es la página principal del sitio web. Contiene la estructura y el contenido de las diferentes secciones de la página, incluyendo información de la institución, contacto, imágenes y otros elementos.

### `estilo.css`

Contiene los estilos visuales utilizados por la página, como colores, tipografías, tamaños, espaciados, diseño de las secciones y adaptación a diferentes tamaños de pantalla.

### `fotos/`

Contiene las fotografías utilizadas en el sitio web.

Para agregar una nueva fotografía:

1. Subir la imagen dentro de la carpeta `fotos/`.
2. Agregar su referencia correspondiente en `index.html`.
3. Guardar los cambios.
4. Esperar a que GitHub Pages publique la nueva versión.

Ejemplo:

```html
<img src="fotos/nueva-foto.jpg" alt="Descripción de la fotografía">
```

### `CNAME`

Este archivo permite que GitHub Pages utilice el dominio personalizado:

**escuelaricardogutierrez.com.ar**

No se debe eliminar ni modificar este archivo salvo que se cambie el dominio del sitio.

### `README.md`

Este archivo contiene la documentación básica del proyecto y las instrucciones para su mantenimiento.

---

## 🚀 Publicación

El sitio web está alojado mediante **GitHub Pages**.

Los cambios realizados en el repositorio se publican automáticamente después de que GitHub procese la actualización.

Después de realizar cambios, puede ser necesario esperar unos minutos para que estos aparezcan en el sitio web.

---

## ✏️ Cómo modificar la página

### Modificar textos

Los textos de la página se encuentran principalmente en:

`index.html`

Para modificar un texto, editar el contenido correspondiente dentro de este archivo y guardar los cambios.

### Modificar el diseño

Los estilos visuales de la página se encuentran en:

`estilo.css`

Desde este archivo se pueden modificar colores, tamaños, posiciones, fuentes y otros aspectos visuales.

### Agregar o cambiar fotografías

Las fotografías utilizadas por el sitio se encuentran en:

`fotos/`

Las imágenes pueden reemplazarse o agregarse a esta carpeta y luego ser utilizadas desde `index.html`.

---

## 🌐 Servicios utilizados

### GitHub Pages

Servicio utilizado para alojar y publicar el sitio web.

### Cloudflare

Servicio utilizado para administrar los registros DNS del dominio.

### NIC Argentina

Servicio utilizado para registrar y administrar el dominio:

**escuelaricardogutierrez.com.ar**

---

## 🔒 HTTPS

El sitio utiliza HTTPS para proporcionar una conexión segura:

**https://escuelaricardogutierrez.com.ar**

La configuración del certificado HTTPS se administra mediante GitHub Pages.

---

## ⚠️ Recomendaciones

- No eliminar `index.html`.
- No eliminar `CNAME`.
- No eliminar la carpeta `fotos/`.
- Mantener las imágenes utilizadas por la página dentro de `fotos/`.
- No modificar los registros DNS de Cloudflare sin conocer su función.
- Realizar una copia de seguridad antes de realizar cambios importantes.
- Comprobar la página después de realizar modificaciones.

---

## 🏫 Administración

El repositorio y los servicios asociados al sitio web pertenecen a la **Escuela Ricardo Gutiérrez**.

La cuenta de GitHub, el dominio y la configuración DNS deben permanecer bajo control de la institución.
