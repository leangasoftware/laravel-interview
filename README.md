# Entrevista Laravel

![](https://www.ikerg1972.com/wp-content/uploads/2019/05/LARAVEL-640x320.png)

Bienvenido a tu prueba de __LARAVEL__, a continuación encontrarás una serie de requerimientos con los cuales deberás realizar un ejercicio práctico.

La prueba general se divide en pequeños ejercicios con los cuales se evaluará en práctica:
- Pensamiento lógico.
- Resolución de problema.
- Tiempo de desarrollo.
- Entre otros.

Se debe manejar migraciones, rutas, modelos, controladores.

Finalizada la prueba recuerda enviar link del proyecto o tu repositorio a [desarrollo@leangasoftware.es](mailto:desarrollo@leangasoftware.es) con tu información de contacto y en el asunto colocar: LARAVEL-INTERVIEW


> Recomendación: No importa terminar todos los ejercicios, lo más importante es la funcionalidad del ejercicio resuelto(s).

### Problema a resolver:

![](https://i.imgur.com/1TBR0tu.png)

__Imaginemos lo siguiente:__ Tenemos un sitio web llamado __solucionesonline.demo__ en el cual cualquier usuario registado puede publicar un servicio ejemplo __"Aprende a tocar el piano"__ el cual tiene un descripción,  entre otras características.

Las vistas la debes realizar en `BLADE`

# Ejercicios

### 1. Chat entre usuario y anfitrión basado en un publicación.

__HABILIDADES:__
```
PHP, MYSQL
```
__PROBLEMA:__
> Usuario __DANIEL485__ publica un servicio de __"Aprende a tocar el piano"__, Usuario __MARIA_1234__ pregunta `Hola Daniel se puede mejorar un precio por 10 horas?` 

__REQUERIMIENTO:__
El objetivo principal es crear un endpoint al cual se realizan las peticiones necesarias para enviar el mensaje, donde se guarde los datos del usuario que emite el mensaje y el usuario que recibe el mensaje, además de fecha, hora, entre otros.

![](https://i.imgur.com/AlXUxeL.png)

### 2. Multiples Chats

__HABILIDADES:__
```
PHP, MYSQL
```

__PROBLEMA:__
> El mismo Usuario __DANIEL485__ del problema anterior,  publica otro servicio llamado __"Aprende a tocar la guitarra"__, donde el mismo Usuario __MARIA_1234__ pregunta `Hola Daniel veo que tambien enseñas Guitarra me puedes dar un descuento 10 horas de guitarra y 10 horas de piano?`. 
¿Por otro lado tenemos un nuevo Usuario __ROBERTO_DIAZ__ el cual realiza una pregunta, `Hola Daniel tengo que llevar mi propia Guitarra?` 

__REQUERIMIENTO:__
Se requiere realizar la lógica necesaria entre rutas y controlados para que un usuario puede tener múltiples hilos de conversión “chats” relaciones a una publicación y relacionados con un usuario.

![](https://i.imgur.com/w6g9wSZ.png)

### 3. Paginacion y Orden.

__HABILIDADES:__
```
PHP, MYSQL
```

__PROBLEMA:__
> Tener en cuenta de que el historial del chat puede llegar a tener cientos de mensajes, por lo cual se necesita paginar en lotes de 15 mensajes. También es necesario basado en la fecha del mensaje ordenarlos desde el más reciente.

__REQUERIMIENTO:__
Realizar la lógica necesaria en el controlador para poder paginar y mostrar la cantidad de mensajes, y ordenarlos por fecha.

### 4. Archivos adjuntos.

__HABILIDADES:__
```
PHP, MYSQL
```

__PROBLEMA:__
> En muchos casos los usuarios necesitaran adjuntar algún tipo de archivo “Foto, Audio” en el hilo de conversación.

__REQUERIMIENTO:__
Se requiere realizar el endpoint y lógica necesaria para utilizar la funcion [Storage](https://laravel.com/docs/5.7/filesystem) de laravel y poder almacenar los archivos adjuntos, relacionados al mensaje.


### Extra.
Si has llegado hasta este punto, y consideras que tienes tiempo se valora el hecho de que puedas desplegar tu proyecto en [Heroku](https://www.heroku.com/) o en cualquier servidor de tu gusto.

¡Gracias por participar!
