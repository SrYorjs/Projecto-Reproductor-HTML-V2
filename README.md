# 🎧 Interactive Sonic Experience V2: A Community-Driven Music Player

![GitHub repo size](https://img.shields.io/github/repo-size/SrYorjs/Projecto-Reproductor-HTML-V2?color=38bdf8&style=for-the-badge)
![GitHub last commit](https://img.shields.io/github/last-commit/SrYorjs/Projecto-Reproductor-HTML-V2?color=ef4444&style=for-the-badge)
![GitHub stars](https://img.shields.io/github/stars/SrYorjs/Projecto-Reproductor-HTML-V2?style=for-the-badge)

Este repositorio alberga un ecosistema de reproductores web inmersivos diseñados con un enfoque en la **sincronización de audio avanzada** y el **diseño atmosférico**. No se trata simplemente de una interfaz de reproducción, sino de una curaduría digital donde cada track posee una arquitectura visual única, combinando estética retro-pixel con tecnologías web modernas.

---

## 🚀 Visión del Proyecto

El objetivo principal es transformar la escucha pasiva en una experiencia interactiva. Utilizando un motor de sincronización personalizado, el proyecto busca:
* **Narrativa Visual:** Adaptar el entorno (colores, efectos de niebla y partículas) al tono emocional de la lírica.
* **Arquitectura Open-Source:** Un proyecto escalable donde la comunidad propone el siguiente "Stage" visual mediante el análisis de nuevas pistas.
* **Análisis Semántico:** Inclusión de *Meaning Boxes* que ofrecen una interpretación contextual de las composiciones.

---

## ✨ Especificaciones Técnicas y Arquitectura

### 🛠️ Core Engine
* **Time-Coded Lyrics Synchronization:** Algoritmo implementado en Vanilla JavaScript para el parseo de marcas de tiempo en formato `MM:SS.ss`, permitiendo una precisión de milisegundos en el renderizado de letras.
* **Individual Word Wave Animation:** Sistema de inyección de nodos DOM dinámicos que envuelve cada palabra en `<span>` para aplicar transformaciones CSS independientes y secuenciales (Staggered Animations).
* **Dynamic Fog & Flare System:** Motor gráfico ligero basado en gradientes radiales animados y filtros de desenfoque gaussiano (`backdrop-filter: blur()`) para simular profundidad y atmósfera.

### 🎨 Diseño y UI/UX
* **Monocraft Typography:** Implementación de `@font-face` con la fuente `monocraft.ttf` para establecer una identidad visual pixelada coherente.
* **Glassmorphism Effects:** Uso de transparencias `rgba` y bordes sutiles para lograr una jerarquía visual moderna sobre fondos dinámicos.
* **State Management:** Controladores de estado para reproducción (`play`/`pause`), volumen y progreso con feedback visual inmediato en los sliders.

---

## 🛠️ Stack Tecnológico

<p align="left">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" />
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" />
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" />
  <img src="https://img.shields.io/badge/Git-F05032?style=for-the-badge&logo=git&logoColor=white" />
  <img src="https://img.shields.io/badge/GitHub%20Pages-222222?style=for-the-badge&logo=github&logoColor=white" />
</p>

---

## 🎵 Playlist & Stages (Orden Alfabético)

| Composición | Artista | Identidad Visual | Engine |
| :--- | :--- | :--- | :--- |
| **Heavy** | The Marías | Vampire / Dark Red | Apple Style Sync |
| **I Thought I Saw Your Face Today** | She & Him | Golden / Glow | Apple Style Sync |
| **Lejos de Ti** | The Marías | Ocean / Deep Blue | Apple Style Sync |
| **No One Noticed** | The Marías | Deep Water / Flare | Apple Style Sync |
| **Nobody New** | The Marías | Mono / Grayscale | Apple Style Sync |
| **Sienna** | The Marías | Nostalgia / Cyan | Apple Style Sync |

---

## 💬 Colaboración y Contribuciones

Este proyecto es un organismo vivo. Si deseas contribuir con un nuevo diseño o una canción:
1.  **Fork** el repositorio.
2.  Crea un nuevo archivo `playerX.html`.
3.  Desarrolla el esquema de colores basado en el sentimiento de la canción.
4.  Realiza un **Pull Request** para integrar tu Stage a la colección oficial.

---

## 👤 Perfil del Desarrollador

**Jose Juan Navarrete (SrYor)**
* **Académico:** Estudiante de Ingeniería Industrial en Procesos Productivos (UTM).
* **Technical Focus:** Automatización, Robótica (Arduino/PLC), Desarrollo Web (Node.js) y Diseño UI.
* **Contacto:** [GitHub Profile](https://github.com/SrYorjs)

---

## 📄 Notas Legales y Créditos

Este software se distribuye bajo la licencia **MIT**. Todos los derechos de audio y arte visual pertenecen a sus respectivos creadores (The Marías, She & Him, Wisp). El propósito de este repositorio es estrictamente académico y de exploración técnica en diseño de interfaces.