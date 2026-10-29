AgroScan - Tesis / Startup 2026

Plataforma web desarrollada como proyecto de tesis que combina Inteligencia Artificial e imágenes satelitales para el monitoreo de cultivos en el sector agroexportador.

## Funcionalidades Principales
- Monitoreo y seguimiento del estado de cultivos agrícolas.
- Estimación de la fecha óptima de cosecha mediante análisis predictivo.
- Emisión de certificados digitales de trazabilidad agrícola.

## Stack Tecnológico
- **Backend:** FastAPI (Python), arquitectura modular (auth, models, routers, schemas, services).
- **Frontend:** React.js, diseño de interfaz web interactiva.
- **Inteligencia Artificial / Datos:** Procesamiento de imágenes satelitales e integración con modelos de visión por computadora (Roboflow).

## Estructura del Proyecto
```text
agroscan/
├── backend/app/        # API principal en FastAPI (Auth, Routers, Modelos)
├── frontend-web/       # Interfaz de usuario en React.js
└── README.md           # Documentación del proyecto
