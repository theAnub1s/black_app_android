# Black App Android 🛍️

**Black App Android** es un proyecto de aplicación móvil nativa de comercio electrónico diseñado para desarrollarse en **Android Studio** con **Kotlin** y **Jetpack Compose**.

## Objetivo

Proponer una experiencia de compra intuitiva, rápida y reactiva desde Android, con navegación por productos y gestión de un carrito.

## Funcionalidades previstas

- **Catálogo:** explorar y consultar productos.
- **Detalle de producto:** revisar descripción e información del artículo.
- **Carrito de compras:** agregar, visualizar y administrar productos seleccionados.
- **Interfaz reactiva:** actualizar la información mostrada mediante estados de Jetpack Compose.

## Tecnologías propuestas

| Componente | Tecnología |
| --- | --- |
| Lenguaje | Kotlin |
| Entorno de desarrollo | Android Studio |
| Interfaz | Jetpack Compose |
| Control de versiones | Git y GitHub |

## Estado del repositorio

> **En preparación.** La base del repositorio ya incluye este README y un `.gitignore` de Android Studio; **aún falta incorporar el código fuente de la aplicación**. Las funcionalidades anteriores son objetivos, no implementaciones verificadas.

## Flujo de trabajo con ramas

- `main`: rama principal; permanece sin los cambios de documentación de esta rama hasta que se apruebe una fusión.
- `feature/readme-update`: rama de trabajo creada para actualizar y revisar la documentación.

Para descargar y trabajar en esta rama:

```bash
git clone https://github.com/theAnub1s/black_app_android.git
cd black_app_android
git switch feature/readme-update
```

Cuando se integre el proyecto de Android Studio, coloca los archivos del proyecto en el directorio clonado y conserva los archivos de configuración de Gradle. Para registrar cambios en **esta** rama:

```bash
git add .
git commit -m "Add Android Studio project"
git push -u origin feature/readme-update
```

## Próximos pasos

1. Incorporar la estructura real del proyecto de Android Studio.
2. Construir las pantallas del catálogo, los detalles y el carrito.
3. Verificar la compilación y la navegación.
4. Revisar los cambios antes de fusionarlos con `main`.

**Nota:** No incluyas credenciales, claves privadas ni `local.properties` en los commits. El `.gitignore` excluye archivos locales y generados.
