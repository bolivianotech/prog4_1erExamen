# StudySync — Examen en Línea · Parte I

Examen interactivo de opción múltiple para la materia de Desarrollo Web Avanzado.

## Cobertura temática

| Sección | Tema | Puntos |
|---------|------|--------|
| 1 | Arquitectura Web: Frontend, Backend y Endpoints | 20 pts |
| 2 | SSR, SPA y Arquitectura del Proyecto StudySync | 20 pts |
| 3 | Redis, Upstash y Pub/Sub | 20 pts |
| 4 | CORS y Rate Limiting | 20 pts |
| 5 | Setup del Proyecto, Swagger y Buenas Prácticas | 20 pts |

**Total: 25 preguntas · 4 puntos c/u · 100 puntos**

## Flujo del examen

1. El estudiante ingresa su **nombre completo** y el **correo** con el que tiene acceso a la unidad de Google Drive de la materia.
2. Resuelve las 25 preguntas en un máximo de **40 minutos**.
3. Al finalizar recibe:
   - Calificación sobre 100
   - Retroalimentación por cada respuesta incorrecta (explicación del concepto)
4. Descarga el resultado en **PDF** y lo sube a su carpeta en Google Drive.

## Tecnologías

- HTML5 puro — sin frameworks
- CSS con variables (design system iOS-inspired)
- JavaScript vanilla (ES2020)
- [jsPDF](https://github.com/parallax/jsPDF) para generación de PDF en cliente
- Google Fonts — IBM Plex Sans + IBM Plex Mono

## Despliegue en GitHub Pages

1. Sube el repositorio a GitHub
2. Ve a **Settings → Pages**
3. En *Source*, selecciona la rama `main` y la carpeta `/ (root)`
4. Haz clic en **Save**
5. La URL quedará disponible en: `https://<tu-usuario>.github.io/<nombre-repo>/`

> No se requiere servidor ni build step. Todo corre en el navegador.

## Estructura del proyecto

```
studysync-exam/
└── index.html   ← Examen completo (auto-contenido)
└── README.md
└── .gitignore
```

## .gitignore

El proyecto no genera archivos de build, pero se incluye `.gitignore` estándar para evitar subir archivos del sistema.

---

**Desarrollado para:** Desarrollo Web Avanzado — Guía StudySync Parte I
