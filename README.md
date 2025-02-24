# Flutter Social Posts

## Semana 1: Configuración y funcionalidades básicas

### Briefing del Proyecto
Esta aplicación tiene como objetivo permitir a los usuarios crear publicaciones para redes sociales de manera sencilla. Durante esta primera semana, nos enfocaremos en establecer la estructura base del proyecto, configurar las dependencias necesarias y permitir la selección de una imagen desde la galería o la cámara.

### Entregable
Al final de la semana, la aplicación deberá permitir al usuario seleccionar una imagen desde su dispositivo o tomar una foto con la cámara y mostrarla en pantalla.

### Tareas
Configuración del proyecto
Crear un nuevo proyecto Flutter.
Configurar flutter_bloc para la gestión de estado.
Agregar las dependencias necesarias (image_picker, flutter_bloc).

Pantalla de selección de imagen
Crear una pantalla inicial con un Floating Action Button para seleccionar una imagen.
Implementar el ImagePicker para elegir una imagen de la galería o tomar una foto.
Gestionar el estado de la imagen seleccionada con flutter_bloc.
Mostrar la imagen seleccionada en pantalla.

## Semana 2: Edición de Imagen
### Briefing del Proyecto
En esta segunda semana, la aplicación comenzará a incorporar funcionalidades de edición de imagen. Se permitirá a los usuarios agregar textos y otros elementos visuales sobre la imagen seleccionada.

### Entregable
Al finalizar la semana, la aplicación deberá permitir a los usuarios agregar y mover textos sobre la imagen seleccionada.

### Tareas
Implementación de la capa de edición
Crear una nueva pantalla para la edición de imagen.
Diseñar la estructura de la interfaz con un Stack para superponer elementos.

Permitir al usuario agregar un texto sobre la imagen.
Interactividad con los textos
Implementar la funcionalidad para mover los textos arrastrándolos en la imagen.
Agregar la opción de editar el contenido del texto.
Gestionar los cambios con flutter_bloc.

Mejoras visuales
Agregar opciones para cambiar el tamaño y color del texto.
Implementar una barra de herramientas básica para controlar estas opciones.

## Semana 3: Exportación y Compartir
### Briefing del Proyecto
En la tercera y última semana, se añadirá la funcionalidad de exportar la imagen editada y compartirla a través de diferentes plataformas.

### Entregable
Al finalizar la semana, los usuarios podrán descargar la imagen editada y/o compartirla en redes sociales o aplicaciones de mensajería.

### Tareas
Generación de imagen final
Implementar la captura de la vista editada como imagen.
Guardar la imagen en el dispositivo.
Compartir la imagen
Integrar el package share_plus para compartir la imagen en redes sociales o apps de mensajería.
Agregar botones para compartir en WhatsApp, correo y otras aplicaciones disponibles.
Mejoras finales y optimización
Revisar y corregir posibles errores.
Optimizar el rendimiento y la experiencia de usuario.
Refactorizar el código para mejorar su mantenibilidad.
Al finalizar estas tres semanas, se tendrá una aplicación funcional que permitirá a los usuarios crear y compartir publicaciones personalizadas para redes sociales.
