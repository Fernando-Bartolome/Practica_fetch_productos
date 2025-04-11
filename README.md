# Practica_fetch_productos

En este proyecto La función fetch realiza una solicitud HTTP a la URL que declaramos (URLmain) para obtener datos de una API en este caso es de la pagina fakeStoreAPI.

Devuelve una promesa que convierte la respuesta en JSON (response.json()) para procesar los datos.
Estos datos se pasan a la función createCards, que genera dinámicamente tarjetas HTML con la información de cada producto y las inserta en el contenedor main.

En dado caso de que ocurra un error, fetch lo captura y muestra un mensaje de alerta en el DOM. Este enfoque permite obtener datos de manera asíncrona y mostrarlos en tiempo real en la página web.

1. Aqui esta la pagina del index donde declaramos el main con la clase container para que pueda ser llamado

![Image](https://raw.githubusercontent.com/Fernando-Bartolome/Practica_fetch_productos/refs/heads/main/img/index.png)

2. Aqui en el JS usamos la funcion fetch para que como menciona en la descripcion realizara una solicitud para obtener los datos de la API y devuelve la promesa convirtiendola en JSON

Utilice un Foreach para que sea un ciclo y se muestren todos los campos requeridos en las cards.
![Image](https://raw.githubusercontent.com/Fernando-Bartolome/Practica_fetch_productos/refs/heads/main/img/JS.png) 3. Aqui solo son parametros CSS para que aparezcan con formato las cards declaradas en el JS
![Image](https://raw.githubusercontent.com/Fernando-Bartolome/Practica_fetch_productos/refs/heads/main/img/CSS.png) 4. Visualizacion de la pagina en funcionamiento

![Image](https://raw.githubusercontent.com/Fernando-Bartolome/Practica_fetch_productos/refs/heads/main/img/page.png)
