# PulseOps · Dashboard corporativo de transporte

Dashboard ejecutivo multisede para Córdoba, Comodoro, San Luis y Villa Mercedes. La interfaz prioriza una lectura rápida, navegación fluida y drill-down desde los indicadores hasta cada base operativa.

## Stack

- React + TypeScript + Vite
- Framer Motion para transiciones y microinteracciones
- Recharts para visualizaciones
- Lucide React para iconografía
- CSS responsive con estética dark glass / neon minimal

## Ejecutar

```bash
npm install
npm run dev
```

Luego abrir `http://localhost:5173`.

## Interacciones incluidas

- Navegación lateral por módulos.
- Selector de período.
- Búsqueda de bases.
- Cards KPI animadas con hover.
- Gráfico de rendimiento operativo.
- Donut interactivo de disponibilidad de flota.
- Cards de bases con hover y estado.
- Drawer lateral animado al seleccionar una base.
- Drill-down de actividad reciente y botón de acceso al tablero de base.
- Layout responsive para desktop, tablet y móvil.

## Próxima etapa

Reemplazar los datos demo de `src/main.tsx` por una API autenticada y conectar los módulos de tráfico, flota, taller, RRHH, combustible y seguridad con PostgreSQL.
