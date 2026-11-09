# Cupcake App

Aplicación Android para realizar un pedido de cupcakes. Permite seleccionar la cantidad, el sabor y la fecha de retiro, consultar el resumen y compartir el pedido con otra aplicación.

## Stack

- Android Studio
- Kotlin
- Jetpack Compose y Material 3
- Navigation Compose
- ViewModel y StateFlow
- JUnit y Compose UI Test

## Ejecutar el proyecto

Abrir esta carpeta en Android Studio, sincronizar Gradle y ejecutar el módulo `app` en un emulador o dispositivo Android con API 24 o superior. El proyecto utiliza JDK 17 y Android SDK 34.

## Pruebas

Incluye las 14 pruebas de navegación e interfaz del codelab, verificadas en Android 15.

```bash
./gradlew :app:connectedDebugAndroidTest -Pandroid.experimental.androidTest.useUnifiedTestPlatform=false
```

En Windows se utiliza `gradlew.bat` en lugar de `./gradlew`.

## Referencia

Proyecto basado en el [codelab oficial de Cupcake](https://developer.android.com/codelabs/basic-android-kotlin-compose-test-cupcake?hl=es-419) y su [código fuente de Google](https://github.com/google-developer-training/basic-android-kotlin-compose-training-cupcake). Se conserva la licencia Apache 2.0.
