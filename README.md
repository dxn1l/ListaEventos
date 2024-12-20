# Lista de Eventos

LINK al repositorio: https://github.com/dxn1l/ListaEventos

## Descripción

**Lista de Eventos** es una aplicación móvil que permite gestionar los eventos de los usuarios. A través de esta aplicación, los usuarios pueden agregar, ver y consultar los eventos actuales de forma sencilla y eficiente.
tiene soporte para español e inglés.

## Características

- **Agregar evento**: Los usuarios pueden registrar un nuevo evento, incluyendo información como el nombre, fecha, precio y duración.
- **Consultar eventos**: Los usuarios pueden ver todos los eventos registrados.
- **Detalles del evento**: Los usuarios pueden consultar los detalles de un evento específico.
- **Validación de datos**: La aplicación valida que los datos ingresados estén en el formato correcto.

## Tecnologías utilizadas

- **Jetpack Compose**: Para construir la interfaz de usuario de forma declarativa.
- **Firebase**: Para el manejo de almacenamiento de datos en tiempo real.
- **Kotlin**: El lenguaje de programación utilizado para desarrollar la aplicación.
- **Navigation Compose**: Para la navegación entre pantallas de forma sencilla y eficiente.
- **Material 3**: Para el diseño y los componentes visuales de la aplicación.

## Estructura de la aplicación

1. **Pantallas**:
    - **ViewEventScreen**: Pantalla principal donde el usuario puede ver todos los eventos registrados.
    - **AddEventScreen**: Pantalla para agregar un nuevo evento.
    - **DetailsEventScreen**: Pantalla para visualizar los detalles de un evento.

2. **Firebase**:
    - **Firebase Firestore**: Para almacenar los eventos de los usuarios.