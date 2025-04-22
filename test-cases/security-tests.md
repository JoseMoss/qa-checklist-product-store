# 🔐 Seguridad y Flujo de Usuario – Product Store

## TC-SEC-01: Acceso a rutas protegidas sin autenticación
- **Categoría**: Seguridad y Flujo de Usuario  
- **Severidad**: Crítica (P1)  
- **Descripción**: Las rutas que requieren usuario autenticado (ej. `/cart`) no deben ser accesibles si no hay sesión activa.  
- **Pasos**:
  1. Desde un navegador “limpio” (sin cookies de sesión), abrir la URL: https://www.demoblaze.com/cart.html
  2. Observar el comportamiento  
- **Resultado esperado**:  
  - Redirección a la página de **Log in**  
  - O mensaje “Debes iniciar sesión para continuar”  
- **Estado actual**: ❌ NO
