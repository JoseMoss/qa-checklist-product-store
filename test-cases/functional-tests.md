# ⚙️ Pruebas Funcionales – Product Store

## TC-FUNC-01: Login con retroalimentación clara
- **Categoría**: Pruebas Funcionales  
- **Descripción**: El login de usuario debe mostrar un mensaje claro cuando las credenciales sean incorrectas.  
- **Pasos**:
  1. Ir a la página de **Log in**  
  2. Ingresar un email o contraseña inválidos  
  3. Pulsar **Log in**  
- **Datos de prueba**:  
  - Email: `user@example.com`  
  - Contraseña: `wrongpass`  
- **Resultado esperado**:  
  - Se muestra “Usuario o contraseña incorrecta”  
  - El usuario permanece en la página de login  
- **Estado actual**: ❌ NO

## TC-FUNC-02: Manejo de errores en campos vacíos o mal formateados
- **Categoría**: Pruebas Funcionales  
- **Descripción**: El sistema debe validar y mostrar errores cuando los campos estén vacíos o con formato inválido.  
- **Pasos**:
  1. Ir al formulario de **Log in** o **Sign up**  
  2. Dejar uno o ambos campos vacíos, o ingresar datos con formato incorrecto (ej. email sin `@`)  
  3. Pulsar **Submit**  
- **Datos de prueba**:  
  - Email: `abc`  
  - Contraseña: (vacía)  
- **Resultado esperado**:  
  - Validaciones “Campo obligatorio” y/o “Formato de email inválido” junto a los inputs correspondientes  
- **Estado actual**: ❌ NO
