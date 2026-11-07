# flowpedido-contenido

Piezas finales publicadas en **@flowpedido** (Instagram + Facebook vía Metricool, brand FlowPedido).
Solo FlowPedido: el resto de los proyectos usa sus propias carpetas.

## Estructura

```
flowpedido-contenido/
├── reels/AAAA-MM/      # Reels finales (MP4 1080×1920), nombre = fecha de publicación + tema
├── posts/AAAA-MM/      # Posts (PNG 1080×1350); un carrusel es una carpeta con 01.png, 02.png…
└── calendario/         # Calendario semanal con hora y texto de cada publicación
```

## Cómo se usan

Metricool toma los archivos desde su URL pública:

```
https://raw.githubusercontent.com/nicolascisternasm/AI-Marketing-Studio/main/flowpedido-contenido/<ruta>
```

## Producción

- Reels en motion graphics con pantallas de la app (sin imágenes reales), hechos con HyperFrames.
- Voz ElevenLabs: Claudia (`fXWh1uWJcqhsBnk5RY7Q`, modelo eleven_v4) + música ElevenLabs bajo la voz.
- Datos de las pantallas siempre de ejemplo, nunca clientes reales.
- Proyectos fuente: `FlowPedido/PUBLICIDAD/reel_XX_*` (repo flowpedido-v2).
