# Dashboard Solbus

Dashboard corporativo multisede para transporte urbano con datos demo de Córdoba, Comodoro, San Luis y Villa Mercedes.

## Ejecutar en Windows PowerShell

```powershell
cd "$HOME\Documents\dashboard-transporte"
npm install
npm run dev
```

Abrir `http://localhost:5173`.

## Funcionalidad demo

- Logo Solbus integrado en `public/solbus-logo.svg`.
- Módulos navegables: Resumen, Tráfico, Flota, Taller, RRHH, Combustible y Seguridad.
- Filtro por base y búsqueda global.
- Selector de período.
- KPI clickeables que llevan al módulo relacionado.
- Bases operativas clickeables con drawer de detalle.
- KPI del drawer navegables hacia módulos.
- Registros operativos clickeables con detalle.
- Alertas, notificaciones, exportación simulada y mensajes de feedback.
- Responsive para escritorio, tablet y móvil.

Los datos se encuentran en `src/main.tsx` como dataset de demostración. En la siguiente etapa se pueden reemplazar por endpoints de una API y autenticación por roles.
