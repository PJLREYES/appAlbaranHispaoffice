# Albaranes → ClasGes · Hispaoffice

Importador de albaranes de proveedor (Liderpapel / Comercial del Sur, Novedades Marlu) a **ClasGes 7** (ClassicGes).

- **Aplicación web:** https://appalbaranhispaoffice.netlify.app/
- **Archivo único:** `index.html` (HTML/JS sin dependencias de instalación; pdf.js y Tesseract se cargan del CDN solo para albaranes escaneados).
- **Lectura con IA (opcional):** con una clave de la API de Claude (Ajustes › Lectura con IA) los escaneos, fotos y proveedores sin lector propio se leen con Claude en lugar del OCR. La clave queda solo en el navegador.
- **Datos:** lee y graba directamente en `C:\Clasges7\datos` mediante el permiso de carpeta del navegador (Chrome o Edge). No sube nada a internet.

## Instalación en un equipo

1. Descarga `instalador/Instalar Albaranes Hispaoffice.cmd` y ejecútalo (doble clic).
2. Crea el acceso directo **Albaranes Hispaoffice** en el Escritorio y en *Inicio › Hispaoffice*, con el logo, que abre la aplicación en su propia ventana de Chrome/Edge.
3. La primera vez, pulsa **Elegir carpeta de ClasGes** y selecciona `C:\Clasges7`.

No instala programas ni necesita permisos de administrador. Para quitarlo: `Desinstalar Albaranes Hispaoffice.cmd`.

## Versiones

| Versión | Cambios |
|---|---|
| PJLR Ver.2026.09 | Lectura con IA (API de Claude): clave en Ajustes, modelo a elegir, modo «solo escaneados» o «siempre»; lee cualquier proveedor, cargos CRC y portes; botón «Leer/Releer con IA». |
| PJLR Ver.2026.08 | Logo de Hispaoffice (cabecera, pantalla de conexión, favicon). Publicada en Netlify y GitHub. Instalador de acceso directo. |
| PJLR Ver.2026.07 | Adaptada a ClasGes 7 (`C:\Clasges7`): campo PAGO5 en albaranes, aviso si se conecta a la carpeta antigua de ClasGes 6. |
| PJLR Ver.2026.06 | Última versión para ClasGes 6. |
