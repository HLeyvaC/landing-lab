# Logo - Lab autónomo IA remoto

## Instrucciones de colocación

Coloca el archivo del logo en esta carpeta con el nombre: **logo.png**

El logo se mostrará en:
- **Header del desktop** (sidebar) - altura: 40px
- **Header móvil** - altura: 35px

## Formatos soportados
- PNG (recomendado)
- JPG
- SVG

## Aspectos técnicos
- La imagen se redimensionará automáticamente manteniendo su proporción
- Se usa `object-fit: contain` para evitar distorsión
- Se recomienda un logo con fondo transparente

## Referencias en el código
El logo está referenciado en [src/app/app.html](../../src/app/app.html) en:
- Línea ~10: Sidebar desktop
- Línea ~47: Navbar móvil
