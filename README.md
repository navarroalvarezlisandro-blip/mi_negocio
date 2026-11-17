# Mi Negocio — Cafetería

Proyecto escolar de CETis 94, 5.º semestre, Grupo B, Programación.

Sitio web de una cafetería en naranja y crema, con 5 páginas y cotizador en JavaScript.

## Páginas

- `index.html` — Inicio
- `productos.html` — Productos y cotizador
- `nosotros.html` — Nosotros
- `informacion.html` — Información
- `contacto.html` — Contacto
- `estilos.css` — Estilos (naranja y crema, CSS Grid responsive)
- `script.js` — Cotizador

## Productos

1. Café americano — $35
2. Capuchino — $48
3. Chilaquiles verdes con pollo — $65
4. Sándwich de pollo — $55
5. Croissant de mantequilla — $30
6. Jugo natural de naranja — $40

## Cotizador

En `productos.html` hay dos cotizadores:

1. **Un producto:** elige un producto, cantidad de 1 a 20, y calcula. Hay 10% de descuento desde $500 MXN.
2. **Compra de todos los productos:** pon cantidad en cada producto (0 o más) y pulsa **Calcular compra**. Hay 10% de descuento una sola vez sobre el total, desde $1,000 MXN.

Ejemplo probado: 17, 7, 0, 15, 13 y 0 → importe $2,146.00, descuento $214.60, total $1,931.40.

## Cómo verlo

Con XAMPP, copia esta carpeta a `htdocs` y abre:

```
http://localhost/mi_negocio/index.html
```

O abre `index.html` directamente en el navegador.

## Imágenes

- `imagenes/producto1.jpg`–`producto6.jpg` son las imágenes de los 6 productos.
- La carpeta `img/` con mis fotos propias (portada, americano, capuchino, pan, nosotros, hoja de informe) no está incluida aquí; si quieres que se vean en GitHub, copia tu carpeta `img/` junto a estos archivos.
