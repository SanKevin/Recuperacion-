# 🚗 Pruebas Automatizadas - Registro de Usuario Buggy Cars

## 📋 Descripción del Proyecto
Suite de pruebas automatizadas para el proceso de **registro de usuario** en el sitio web **Buggy Cars** utilizando **Playwright**. Este proyecto implementa 5 casos de prueba que validan los criterios de aceptación definidos para el registro de usuarios.

## 🎯 Objetivo
Validar el funcionamiento correcto del formulario de registro según los siguientes criterios:
- Campos obligatorios (login, nombre, apellido, clave)
- Validación de contraseña (mínimo 8 caracteres, mayúsculas, minúsculas, números y caracteres especiales)
- Registro único por usuario


## 🧪 Casos de Prueba Implementados

### 1. ✅ Página de registro carga correctamente
- Verifica que la página de registro se carga sin errores
- Confirma que todos los elementos principales están presentes

### 2. ✅ Se pueden llenar todos los campos del formulario
- Valida que los campos aceptan datos de entrada
- Confirma la interactividad del formulario

### 3. ✅ El botón de registro existe en la página
- Verifica la presencia del botón de registro
- Confirma que es accesible para el usuario

### 4. ✅ La página permite interacción básica
- Valida la capacidad de respuesta del sistema
- Confirma la usabilidad básica

### 5. ✅ Navegación completa del proceso de registro
- Prueba el flujo completo de registro
- Valida el proceso de extremo a extremo

## 🛠️ Tecnologías Utilizadas
- **Playwright** - Framework de automatización de pruebas
- **Node.js** - Entorno de ejecución
- **JavaScript** - Lenguaje de programación
- **Git & GitHub** - Control de versiones

## 📥 Instalación

### Prerrequisitos
- Node.js (versión 16 o superior)
- npm o yarn

### Pasos de instalación
```bash
# Clonar el repositorio
git clone https://github.com/SanKevin/Recuperacion-.git
cd Recuperacion-

# Instalar dependencias
npm install

# Instalar browsers de Playwright
npx playwright install
