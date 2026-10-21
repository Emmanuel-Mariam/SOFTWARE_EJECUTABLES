# ⚡ Odwin Pedraza — Soluciones Informáticas & Soporte Técnico Especializado

> *Tu tecnología en buenas manos*

Sitio web de soporte técnico y centro de descargas de instaladores, publicado con **GitHub Pages**. Los instaladores se guardan en **GitHub Releases** y la página los lista automáticamente para su descarga.

## 📞 Contacto

| | |
|---|---|
| 💬 WhatsApp / Teléfono | [318 489 6105](https://wa.me/573184896105) |
| ✉️ Correo | [helpdesk.col@outlook.com](mailto:helpdesk.col@outlook.com) |
| 📍 Ubicación | Lérida, Tolima - Villavicencio, Meta |

## 🛠️ Servicios

- Diagnóstico de equipos de cómputo (portátil y escritorio)
- Actualización de sistema operativo
- Instalación de software especializado
- Licencias originales de Office y Windows

## 💾 Software disponible

| Categoría | Programas |
|---|---|
| Ofimática y documentos | Office 2021, Office 2024, FlexiPDF, PDF Editor, Adobe Captivate |
| Seguridad y antivirus | ESET NOD32, Malwarebytes, Avast Security, AVG HitmanPro, Trojan Remover, Shield Antivirus, Malware Hunter |
| Imagen y fotografía | Photoshop (Completo / CS5 / Portable), Lightroom Classic, Luminar Neo, PanoramaStudio, Photo Recovery |
| Audio y producción | FL Studio, Adobe Audition, Serato DJ Pro, Virtual DJ, Camtasia, Audiate |
| Diseño, CAD y 3D | Revit 2027, AutoCAD, CorelCAD, SketchUp Pro, 3D Studio Max |

## 📁 Estructura del repositorio

```
.
├── index.html   # Sitio completo (HTML, CSS y JavaScript en un solo archivo)
└── README.md    # Este archivo
```

## 🚀 Puesta en marcha

### 1. Publicar con GitHub Pages
1. Crea un repositorio **público** en GitHub.
2. Sube `index.html` y `README.md`.
3. Ve a **Settings → Pages**, elige **Deploy from a branch**, rama `main` y carpeta `/ (root)`.
4. Tu sitio quedará en `https://TU_USUARIO.github.io/TU_REPOSITORIO/`.

### 2. Configurar el sitio
Abre `index.html` y edita estas líneas al inicio del bloque `<script>`:

```js
const GH_USER = "TU_USUARIO_GITHUB";
const GH_REPO = "TU_REPOSITORIO";
const TAG     = "instaladores";   // nombre de la release donde se guardan los archivos
```

### 3. Activar el formulario de contacto
1. Obtén tu *access key* gratuita en [Web3Forms](https://web3forms.com) usando helpdesk.col@outlook.com.
2. Reemplaza `PEGA_AQUI_TU_ACCESS_KEY_DE_WEB3FORMS` en `index.html`.

## 📤 Cómo subir instaladores

### Opción A — Desde el panel de la página
1. Crea un token en GitHub: **Settings → Developer settings → Personal access tokens → Fine-grained tokens**.
2. Dale acceso **solo a este repositorio** con el permiso **Contents: Read and write**.
3. En la página, pulsa **🔐 Administrador**, pega el token y arrastra los instaladores.
4. Los archivos aparecen de inmediato en la lista de descargas.

> 🔒 El token solo se usa en la ventana abierta y **no se guarda**. Nunca lo escribas dentro del código ni lo subas al repositorio.

### Opción B — Directamente en GitHub
1. Entra a **Releases → Draft a new release**.
2. Usa la etiqueta (`tag`) `instaladores`.
3. Arrastra los archivos y pulsa **Publish release**.

## ⚠️ Límites a tener en cuenta

- Cada archivo en Releases puede pesar hasta **2 GB**.
- El repositorio debe ser **público** para que las descargas funcionen sin iniciar sesión.
- El listado usa la API pública de GitHub, que permite unas 60 consultas por hora por IP.
- Publica únicamente software que tengas derecho a distribuir. Alojar programas con licencia o activadores puede infringir los términos de GitHub y causar la suspensión del repositorio.

## 🎨 Personalización

- **Colores:** variables CSS al inicio de `index.html` (`--blue`, `--cyan`, `--bg`).
- **Logo:** reemplaza el icono ⏻ de la clase `.logo` por una imagen `<img src="logo.png">`.
- **Textos y categorías:** edita directamente las secciones de `index.html`.

---

© Odwin Pedraza · Todos los derechos reservados.
