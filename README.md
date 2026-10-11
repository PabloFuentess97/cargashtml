# Almacén General — Dashboard de cargas

Aplicación web estática para consultar un Excel de movimientos, con filtros combinados de artículos, lotes y órdenes de fabricación, totales de cargas/devoluciones y hojas de trabajo imprimibles.

## Publicar en Seenode

- Repositorio: `PabloFuentess97/cargashtml`
- Rama: `main`
- Tipo: **sitio estático**
- Directorio raíz/de publicación: `/`
- Archivo de entrada: `index.html`
- Comando de compilación: **ninguno**

## Uso

Al abrir la aplicación, importa manualmente tu archivo Excel con el control de carga. El repositorio **no incluye datos reales del almacén** para evitar publicarlos en internet. La herramienta procesa el Excel localmente en el navegador y no requiere base de datos ni backend. La biblioteca ExcelJS se carga desde un CDN y requiere internet.

No subas archivos Excel corporativos ni exportaciones con datos internos a este repositorio público. La app no se sincroniza con SharePoint ni con BaaN IV.
