# 🧩 Matriz de Trazabilidad - QA Checklist Product Store

Este documento relaciona los requerimientos funcionales y de interfaz con los casos de prueba creados, asegurando cobertura completa del sistema.

| Requisito ID | Descripción del Requisito                                     | Caso de Prueba ID       | Estado    | Observaciones                       |
|--------------|---------------------------------------------------------------|--------------------------|-----------|-------------------------------------|
| REQ-001      | El logo debe ser visible y redirigir al inicio                | TC-001                   | ✅ Pasado |                                     |
| REQ-002      | El menú debe contener los enlaces principales                 | TC-002                   | ✅ Pasado |                                     |
| REQ-003      | Cada producto debe mostrar nombre, imagen y precio            | TC-010                   | ✅ Pasado |                                     |
| REQ-004      | El sitio debe ser responsive en distintos tamaños de pantalla | TC-020                   | ✅ Pasado |                                     |
| REQ-005      | El botón de login debe mostrar un formulario                  | TC-030                   | ✅ Pasado |                                     |
| REQ-006      | Rutas protegidas requieren autenticación                      | TC-031                   | ❌ Fallido | No redirige si no hay sesión activa |
| REQ-007      | El carrito debe permitir agregar productos                    | TC-040                   | ✅ Pasado |                                     |
| REQ-008      | Se debe gestionar errores de login/registro                   | TC-041                   | ❌ Fallido | No muestra validaciones             |

---

## 📝 Notas

- Casos fallidos están en seguimiento y serán priorizados en la siguiente iteración.
- La matriz se actualizará conforme se agreguen nuevas funcionalidades o se ajusten requisitos.

