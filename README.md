# NEO PULSE — Smartwatch Conceptual

> Proyecto Innovación en Ingeniería · Universidad Libre · 2025

Interfaz interactiva premium para smartwatch circular AMOLED con 7 pantallas, simulaciones en tiempo real y estética WearOS/Garmin.

## Pantallas incluidas

1. **Dashboard Principal** — Hora, fecha, saludo, Neo Score, BPM, SpO₂, pasos, IA
2. **Salud 360°** — ECG animado en vivo, métricas biométricas, sueño, Salud Score
3. **IA Predictiva** — Recomendaciones dinámicas rotativas basadas en métricas
4. **Energía Inteligente** — Modos ECO/Balance/MAX, Solar interactivo, Cinética, USB-C
5. **Sostenibilidad** — CO₂ evitado, gráficos semanales, impacto ambiental
6. **Modularidad** — Estado de módulos, specs del dispositivo
7. **Conectividad** — Bluetooth, Android/iOS, notificaciones

## Ejecutar localmente

```bash
# Opción 1 — Con Node.js (recomendado)
npm install
npm start
# Abrir http://localhost:3000

# Opción 2 — Sin instalación
# Abrir index.html directamente en cualquier navegador
```

## DEPLOY en Railway

1. Crear cuenta en [railway.app](https://railway.app)
2. Nuevo proyecto → "Deploy from GitHub repo"  
   _o_ usar Railway CLI:
   ```bash
   npm install -g @railway/cli
   railway login
   railway init
   railway up
   ```
3. Railway detecta automáticamente Node.js y ejecuta `npm start`
4. Obtener URL pública desde el dashboard de Railway
5. Generar código QR en [qr-code-generator.com](https://www.qr-code-generator.com) con la URL

## Navegación

| Gesto | Acción |
|-------|--------|
| Swipe ← / → | Cambiar pantalla |
| Swipe ↓ | Panel rápido |
| Clic en puntos | Ir a pantalla |
| Botones inferiores | Navegación directa |

## Stack técnico

- HTML5 + CSS3 + JavaScript vanilla
- Canvas API (ECG, Kinética)
- Google Fonts (Exo 2, Rajdhani, Share Tech Mono)
- Express.js (servidor)
- Sin dependencias frontend externas
