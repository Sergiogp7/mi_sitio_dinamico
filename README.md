# 🧱 mi_sitio_dinamico

El proyecto **mi_sitio_dinamico** es un ejemplo sencillo y bien estructurado de cómo crear una **página web modular con PHP**, aplicando **buenas prácticas de programación** y usando **Bootstrap** para el diseño.

Su objetivo principal es **evitar la repetición de código HTML**, separando la cabecera, el contenido y el pie de página en archivos independientes que se incluyen dinámicamente desde un **layout principal**.

---

## 📁 Estructura del proyecto

```bash
/mi_sitio_dinamico/
├── index.php               → Punto de entrada del sitio (control principal)
├── layout.php              → Plantilla maestra con el <html> y </html>
└── /elementos/             → Carpeta con componentes reutilizables
    ├── header.php          → Encabezado común con el título y subtítulo
    ├── contenido.php       → Zona principal con el listado de productos
    └── footer.php          → Pie de página dinámico con el año actual

---

## 🔧 Cómo probar localmente

Para ver la nueva barra de navegación (Bootstrap) puedes iniciar un servidor PHP embebido desde la carpeta del proyecto y abrir http://localhost:8000 en tu navegador:

```powershell
php -S localhost:8000
```

Luego abre `index.php` o `layout.php` en el navegador. La barra es responsive y usa el bundle JS de Bootstrap incluido en `layout.php`.
