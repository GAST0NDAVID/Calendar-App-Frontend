<!-- # Calendar App :calendar: -->
# Calendar App :calendar:

Este es un proyecto simple de un calendario implementado utilizando React y Redux Toolkit. El objetivo principal de este proyecto es aprender y practicar el uso de los estados globales, hooks personalizados, integración de API con axios, y la administración del estado con Redux Toolkit en una aplicación de React. Esta aplicación se integra con un backend que fue programado utilizando Node js, Express y MongoDB que se encuentra en otro repositorio [Link del repositorio del Backend Calendar App](https://github.com/mirianalejandra1996/Calendar-backend).

### Características

- **Autenticación de Usuario:** Los usuarios pueden crear una cuenta personalizada y luego iniciar sesión para acceder a la aplicación y gestionar sus eventos de manera segura.

- **Vista de calendario detallado:** Permite al usuario visualizar eventos y actividades en un calendario limpio y organizado en el que podrá cambiar su apariencia (en forma de agenda, diario, semanal y mensual).

- **Agregar, editar y remover sus propios eventos:** Los usuarios pueden agregar nuevos eventos al calendario, así como actualizar y eliminar los detalles de sus propios eventos existentes.

- **Visualización de eventos de otras personas:** Los usuarios pueden visualizar los eventos de otras personas, lo que facilita la coordinación y la planificación en grupo.

## Uso

### Pantalla para autenticación

Para crear e ingresar a la cuenta podrá ingresar sus datos para poder generar una cuenta. En caso de ya haberla creado, puede loguearse.

<img src="/src/assets/readme/login.png" alt="Login" width="400" >

### Pantalla de carga durante la verificación del usuario

<img src="/src/assets/readme/loading.png" alt="Login" width="400" >

### Pantalla del calendario

Los eventos creados por el usuario se mostrarán en color azul. En caso de que no sean creados por el usuario, se mostrarán en color gris.

- Creación y actualización de eventos

Se podrá crear y actualizar el evento con el uso del botón de color rojo. El usuario podrá ingresar los detalles del evento como fecha y hora exacta, además de agregar una descripción.

<img src="/src/assets/readme/create-event-antonella.png" alt="Agenda" width="400" >

- Eliminación de eventos

El usuario debe hacer click en el evento a eliminar para que se mantenga activo, y se visualizará el botón rojo para poder remover el evento.

<img src="/src/assets/readme/remove-event-antonella.png" alt="remove-event" width="400" >

- Visualización mensual de los eventos

El usuario deberá presionar el botón "Mes" ubicado en la parte superior derecha para visualizar los eventos del mes

<img src="/src/assets/readme/mensual-events.png" alt="mensual-events" width="400" >

- Visualización diaria de los eventos

El usuario deberá presionar el botón "Día" ubicado en la parte superior derecha para visualizar los eventos del día

<img src="/src/assets/readme/all-events-antonella.png" alt="all-events" width="400" >

- Visualización en forma de agenda de los eventos

El usuario deberá presionar el botón "Agenda" ubicado en la parte superior derecha para visualizar los eventos en un listado

<img src="/src/assets/readme/agenda.png" alt="agenda" width="400" >

## Contribución

<img src="/src/assets/readme/team.gif" alt="agenda" width="400" >

Si te gustaría contribuir a este proyecto y mejorar aún más la aplicación de calendario, ¡te doy la bienvenida! Siéntete libre de hacer un fork del repositorio, realizar tus cambios y enviar una solicitud de pull. ¡Espero ver tus contribuciones pronto!

## Autor

- Nombre: [Mirian Alejandra Arévalo 🙋](https://github.com/mirianalejandra1996).
- Correo Electrónico: [mirianalejandra1996@gmail.com](mailto:mirianalejandra1996@gmail.com).
- GitHub: [https://github.com/mirianalejandra1996](https://github.com/mirianalejandra1996).
- Linkedin: [https://www.linkedin.com/in/mirian-arevalo/](https://www.linkedin.com/in/mirian-arevalo/).



## Instalación y Desarrollo
Este proyecto ha sido inspirado en el curso de Fernando Herrera de React js.

1. Clona este repositorio en tu máquina local.

```
    git clone https://github.com/mirianalejandra1996/Calendar-App-Frontend.git
    
```

1. Renombra el archivo **.env.template** file a **.env**


3. Reemplaza los valores a las variables de entorno.

```
    REACT_APP_API_URL="http://localhost:4000/api"
    
```

4. Navega al directorio del proyecto.

```
    cd calendar-app
    
```
5. Instala las dependencias.

```
    npm install
    
```

6. Inicia la aplicación.

```
    npm start
    
```

## Inspiración

Este proyecto ha sido inspirado en el curso de Fernando Herrera de React js.
