# Panel de Hallazgos y Auditorías — Plan de Mejora Continua

## Requisitos
- Node.js 18+

## Instalación y ejecución
```bash
npm install
npm run dev
```
Abre la URL que muestre la terminal (por defecto http://localhost:5173).

## Uso
El dashboard carga por defecto los datos del archivo Excel original (hoja "HALLAZGOS VISITAS").
Para actualizar con un nuevo archivo, usa el botón "Cargar nuevo Excel" — debe mantener la misma
estructura de columnas en esa hoja.

## Compilar para producción
```bash
npm run build
```
Genera los archivos estáticos en `dist/`.
