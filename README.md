# black_app_android

Aplicación móvil nativa de comercio electrónico desarrollada con **Android Studio**, **Kotlin** y **Jetpack Compose**.

## Descripción del proyecto

La aplicación está planteada para permitir a los usuarios:

- Explorar un catálogo de productos.
- Consultar información detallada de cada producto.
- Gestionar un carrito de compras.
- Disfrutar una experiencia de interfaz rápida, intuitiva y reactiva.

> **Estado:** repositorio inicializado. El proyecto fuente de Android Studio debe incorporarse desde el equipo de desarrollo.

## Subir el proyecto desde Android Studio

Para evitar conflictos con la rama `main` y el commit inicial, clona primero este repositorio:

```bash
git clone https://github.com/theAnub1s/black_app_android.git
cd black_app_android
```

Copia **el contenido** del proyecto de Android Studio a esta carpeta, conservando las carpetas `app/`, `gradle/` y los archivos `.gradle.kts` si existen. Después ejecuta:

```bash
git add .
git commit -m "first commit: Android Studio project"
git push -u origin main
```

No subas `local.properties`, compilaciones, cachés de Gradle ni claves privadas. El archivo `.gitignore` ya está preparado para excluirlos.
