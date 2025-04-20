# ✅ QA Checklist – Product Store

## 🧭 Navegación y Elementos Generales
- [x] El logo es visible y redirige correctamente al hacer clic
- [x] El menú superior contiene todos los enlaces esperados: Home, Contact, About us, Cart, Log in, Sign up
- [x] Todos los enlaces del menú funcionan y redirigen a sus respectivas páginas
- [x] El menú permanece visible y funcional en diferentes tamaños de pantalla (responsive)
- [x] El slider/carousel de imágenes funciona correctamente (puede avanzar/retroceder)

## 🛒 Catálogo de Productos
- [x] Cada producto muestra: nombre, precio, imagen y una descripción o especificación básica
- [x] Las imágenes de los productos se cargan correctamente (sin errores de carga)
- [x] Los precios están visibles y en un formato correcto (ej: `$700`)
- [x] Al hacer clic en un producto, debe redirigir a una página de detalles (si aplica)
- [x] Todos los productos están correctamente clasificados bajo sus categorías

## 📂 Categorías
- [x] El bloque de categorías está visible (Phones, Laptops, Monitors)
- [x] Al hacer clic en una categoría, debe filtrarse el contenido correspondiente
- [x] Las categorías están correctamente nombradas y sin errores ortográficos

## 🧪 Validaciones Técnicas Básicas
- [x] No hay errores en la consola del navegador (F12)
- [x] El tiempo de carga de la página es adecuado (preferentemente <3 segundos)
- [x] La estructura HTML/CSS responde correctamente al cambiar de tamaño de pantalla

## 📱 Responsive Design
- [x] Todos los elementos se adaptan correctamente en pantallas móviles/tablets
- [x] El menú es accesible y funcional en dispositivos móviles
- [x] El slider y las tarjetas de producto no se cortan o superponen en pantallas pequeñas

## 🔐 Seguridad y Flujo de Usuario
- [x] El botón **Log in** abre un formulario de autenticación (si está implementado)
- [x] El botón **Sign up** lleva al formulario de registro
- [x] El botón **Cart** muestra productos seleccionados (si aplica)
- [ ] Las rutas protegidas (como el carrito) requieren autenticación si corresponde

## 📄 Contenido y Estética
- [x] No hay errores ortográficos o gramaticales
- [x] Las fuentes y estilos visuales son consistentes en toda la página
- [x] El color del tema (degradado púrpura) no interfiere con la legibilidad del texto

## ⚙️ Pruebas Funcionales
- [x] El carrito agrega productos correctamente (si hay función activa)
- [ ] El login/login de usuario funciona correctamente y da retroalimentación clara
- [ ] El sistema gestiona errores de usuario (campos vacíos, contraseñas erróneas, etc)
