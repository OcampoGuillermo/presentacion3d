# Presentación 3D - CaszaMosqui

Presentación navegable en 3D (no video MP4) que explica las funcionalidades públicas y de administración de [CaszaMosqui](https://caszamosqui.onrender.com/), su problemática y cómo la resuelve.

## Ver presentación online

Habilita **GitHub Pages** en la configuración del repositorio (Settings → Pages → Branch: `main` → Folder: `/ (root)`).

Luego accede a:
👉 **https://ocampoguillermo.github.io/presentacion3d/caszamosqui-3d/presentacion.html**

## Estructura

```
caszamosqui-3d/
├── presentacion.html   # Deck 3D navegable (único archivo, autocontenido)
├── contenido.json      # Fuente editable de las 10 paradas
└── imagenes/           # Capturas reales del sitio y panel admin
```

## Contenido (10 paradas)

| # | Parada | Tema |
|---|--------|------|
| 0 | Portada | Bienvenida, temas y presentación del Cazador |
| 1 | El enemigo | Problema: Aedes aegypti, criaderos, brecha de reporte |
| 2 | La misión | Solución: entrada, inteligencia y acción |
| 3 | Mapa de riesgo | 28 barrios, 24 reportes, semáforo 2/8/18 |
| 4 | Reporte ciudadano | Formulario público, foto y GPS, sin login |
| 5 | Clima | Alerta climática, bonus climático, cada 10 min |
| 6 | Prevención | Guía, quiz de 5, test de síntomas |
| 7 | Comunidad | Comentarios, Mosqui 24/7, límites claros |
| 8 | Panel de caza | KPIs, gestión, respaldo JSON, límites del admin |
| 9 | Impacto | De reaccionar a anticipar, QR del sitio |

## Guía

**El Cazador** — personaje 3D con sombrero de explorador, chaleco teal, mochila-tanque de fumigación, bastón de niebla y red entomológica.

## Controles

- Clic / Espacio / Enter → avanzar una parada
- Flechas ← / → → anterior / siguiente
- Teclas **1–9** → saltar a cada parada
- **A** → modo automático
- **F** → pantalla completa
- **H** → ocultar/mostrar HUD

## Desarrollado con

- [HyperFrames](https://github.com/heygen-com/hyperframes) (skill `presentacion-academica-3d`)
- three.js para la escena 3D
- GSAP para animaciones

## Licencia

MIT