# peliculasApp

Este proyecto es una aplicación móvil desarrollada con Ionic y Angular, que permite a los usuarios explorar información sobre películas.

## Tecnologías y Dependencias

Esta aplicación está construida utilizando las siguientes tecnologías y librerías clave:

- **Ionic Framework**: Un framework de código abierto para desarrollar aplicaciones móviles híbridas utilizando tecnologías web.
- **Angular**: Un framework de desarrollo para construir interfaces de usuario interactivas.
- **Capacitor**: Una interfaz nativa de la aplicación para acceder a las funcionalidades del sistema operativo y del dispositivo.
- **TypeScript**: Un superset de JavaScript que añade tipado estático.
- **RxJS**: Librería para programación reactiva.
- **Ionic Storage**: Un sistema de almacenamiento clave-valor fácil de usar para Ionic.

Las dependencias principales incluyen:

- `@angular/common`, `@angular/core`, `@angular/forms`, `@angular/platform-browser`, `@angular/router`: Componentes fundamentales de Angular.
- `@capacitor/android`, `@capacitor/app`, `@capacitor/core`, `@capacitor/haptics`, `@capacitor/keyboard`, `@capacitor/status-bar`: Componentes de Capacitor para la integración con Android y funcionalidades del dispositivo.
- `@ionic/angular`, `@ionic/storage`, `@ionic/storage-angular`: Componentes específicos de Ionic.
- `ionicons`: Iconos utilizados en la aplicación.

## Instalación y Ejecución

Sigue estos pasos para configurar y ejecutar la aplicación en tu entorno local:

### Requisitos Previos

Asegúrate de tener instalados los siguientes programas:

- [Node.js](https://nodejs.org/): Entorno de ejecución de JavaScript.
- [npm](https://www.npmjs.com/): Gestor de paquetes de Node.js (viene incluido con Node.js).
- [Ionic CLI](https://ionicframework.com/docs/cli): Interfaz de línea de comandos de Ionic. Puedes instalarlo globalmente con:
  ```bash
  npm install -g @ionic/cli

#### Pasos de Instalación
- 1. Clona el repositorio (en este ejemplo es con SSH)
``` bash
git clone git@github.com:lemisora/movies-app.git
```
- 2. Cambia al directorio
``` bash
cd peliculasApp
```

- 3. Instala las dependencias
``` bash
npm install
```

#### Ejecución
- Para la vista web bastaría con un simple:

``` bash
ionic serve
```

- En cambio si se busca la instalación para Android se debe ejecutar
``` bash
capacitor build android
```

Y abrir el proyecto en Android Studio para poder instalar la aplicación en el dispositivo.
