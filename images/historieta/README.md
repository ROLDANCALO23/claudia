# Estructura de Imágenes para la Historieta

Esta carpeta contiene las imágenes para cada página de la historieta.

## Organización:
- `pagina1.jpg` - Imagen para la página 1 (El Comienzo)
- `pagina2.jpg` - Imagen para la página 2 (Nuestro Primer Encuentro)
- `pagina3.jpg` - Imagen para la página 3 (Momentos Especiales)
- `pagina4.jpg` - Imagen para la página 4 (Creciendo Juntos)
- `pagina5.jpg` - Imagen para la página 5 (Nuestro Futuro)

## Recomendaciones:
- Usar imágenes en formato JPG o PNG
- Tamaño recomendado: 600x400px o similar proporción 3:2
- Optimizar las imágenes para web (no muy pesadas)
- Los nombres deben coincidir exactamente con los usados en el código

## Para agregar más páginas:
1. Agregar nueva imagen con el nombre `paginaX.jpg` (donde X es el número)
2. Crear nueva página `paginaX.astro` en `src/pages/`
3. Actualizar el `totalPaginas` en todos los componentes Paginador