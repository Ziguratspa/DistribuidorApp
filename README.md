# 📦 DistribuidorApp

Aplicación Android desarrollada en **Android Studio** que permite:

- Autenticación de usuarios mediante **Firebase Authentication** (correo/contraseña).
- Registro de la **ubicación del usuario** en **Firebase Realtime Database** tras el inicio de sesión.
- Cálculo de despacho entre una distribuidora y sus clientes.

---

## 🚀 Características

- **Login seguro** con Firebase Authentication.
- **Registro automático de ubicación** usando `FusedLocationProviderClient`.
- **Almacenamiento en tiempo real** en Firebase Realtime Database.
- Código modular y fácil de extender.
- Pensada como base para sistemas de distribución y logística.

---

## 📂 Estructura de Archivos Relevantes

```bash
app/
 └── src/
     └── main/
         ├── java/com/example/distribuidora/
         │   └── LoginActivity.java   # Manejo de login y registro de ubicación
         ├── res/layout/
         │   └── activity_login.xml   # Interfaz de login
         └── AndroidManifest.xml      # Permisos y configuración de la app
