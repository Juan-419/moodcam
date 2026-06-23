# MoodCam & Puzzle Camera Effects

Aplicación web experimental de programación creativa que utiliza la cámara web del usuario para generar efectos visuales interactivos en tiempo real mediante visión por computadora.

## Características

- 📷 Captura de video en tiempo real mediante webcam.
- 😀 Detección facial utilizando Face API.
- ✋ Detección y seguimiento de manos mediante MediaPipe Hands.
- 🎨 Efectos visuales dinámicos sobre el video.
- 🧩 Modo Puzzle que divide y reorganiza la imagen en bloques.
- ⚡ Procesamiento en tiempo real usando JavaScript y Canvas.

## Tecnologías utilizadas

- HTML5
- CSS3
- JavaScript (ES6+)
- Canvas API
- Face API.js
- MediaPipe Hands
- Webcam API (`getUserMedia`)

## Estructura del proyecto

```text
/
├── moodcam.html
├── puzzle.html
├── assets/
│   ├── images/
│   └── models/
├── README.md
```

## Instalación

Clona el repositorio:

```bash
git clone https://github.com/tu-usuario/tu-repositorio.git
cd tu-repositorio
```

## Ejecución local

Debido a que el proyecto utiliza acceso a cámara, es recomendable ejecutarlo desde un servidor local.

Con Python:

```bash
python -m http.server 8000
```

Luego abre:

```text
http://localhost:8000
```

O con VS Code utilizando la extensión Live Server.

## Uso

### MoodCam

Abre:

```text
moodcam.html
```

Permite visualizar la cámara en tiempo real y aplicar efectos basados en detección facial y análisis visual.

### Puzzle Mode

Abre:

```text
puzzle.html
```

Divide la imagen de la cámara en múltiples bloques y genera animaciones tipo rompecabezas mediante transformaciones dinámicas.

## Permisos

La aplicación requiere acceso a:

- Cámara web.
- Procesamiento local de video.

No se almacenan imágenes ni videos en servidores externos.

## Compatibilidad

Navegadores recomendados:

- Google Chrome
- Microsoft Edge
- Brave
- Opera

Se recomienda utilizar las versiones más recientes.

## Despliegue

Puede desplegarse fácilmente como sitio estático en:

- Render (Static Site)
- GitHub Pages
- Netlify
- Vercel

No requiere backend para funcionar.

## Futuras mejoras

- Seguimiento corporal completo.
- Más efectos visuales interactivos.
- Reconocimiento de gestos personalizados.
- Modo multijugador.
- Exportación de imágenes y video.
- Optimización mediante WebGL.

## Licencia

Proyecto educativo y experimental desarrollado con fines de aprendizaje e investigación en visión por computadora y programación creativa.

---

Desarrollado con ❤️ utilizando tecnologías web modernas y visión por computadora en tiempo real.
