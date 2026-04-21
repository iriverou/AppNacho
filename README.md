# AppNacho

Plantilla moderna de aplicación Android con Material Design 3 y Jetpack Compose.

## Características

✨ **Material Design 3** - Interfaz moderna y fluida
🎨 **Jetpack Compose** - UI declarativa y reactiva
🏗️ **MVVM Architecture** - Separación de responsabilidades
📦 **Modular** - Estructura escalable
🔄 **Live Data** - Reactividad con datos en tiempo real

## Requisitos

- Android Studio Hedgehog o superior
- JDK 11+
- Android SDK 24+ (API nivel mínimo)

## Instalación

1. Clona el repositorio:
```bash
git clone https://github.com/iriverou/AppNacho.git
cd AppNacho
```

2. Abre en Android Studio:
   - File → Open → Selecciona la carpeta del proyecto

3. Conecta un dispositivo o emulador Android

4. Ejecuta: `Shift + F10` o botón Run

## Estructura del Proyecto

```
AppNacho/
├── app/
│   ├── src/
│   │   ├── main/
│   │   │   ├── java/com/appnacho/
│   │   │   │   ├── MainActivity.kt
│   │   │   │   ├── ui/
│   │   │   │   │   ├── screens/
│   │   │   │   │   ├── components/
│   │   │   │   │   └── theme/
│   │   │   │   └── viewmodel/
│   │   │   └── res/
│   │   └── test/
│   └── build.gradle
├── gradle/
└── settings.gradle
```

## Tecnologías

- **Kotlin** - Lenguaje de programación
- **Jetpack Compose** - Framework UI
- **Material 3** - Diseño moderno
- **Lifecycle** - Gestión del ciclo de vida
- **Navigation** - Navegación entre pantallas
- **Coroutines** - Programación asincrónica

## Próximas Características

- [ ] Ejemplos de navegación
- [ ] Integración con API REST
- [ ] Base de datos local (Room)
- [ ] Almacenamiento seguro de credenciales
- [ ] Ejemplos de animaciones

## Licencia

MIT License - Ver archivo LICENSE

## Autor

Creado por [iriverou](https://github.com/iriverou)
