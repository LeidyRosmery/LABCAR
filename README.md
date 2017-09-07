# LABCAR

LabCAr es una empresa de taxis que te permite pedir un taxi cuando quieras y en donde quieras. Tenemos una gran cantidad de conductores por todo el departamento. Se a comprobado que Labcar tiene las tarifas mas bajas del mercado.
Sabemos que tu tiempo es dinero, por lo que si nuestro servicio se demora en llegar mas de lo establecido te daremos un 10% de descuento en tu viaje. Puedes ver el demo del website haciendo click [aquí](https://laboratoriasprint05.herokuapp.com/).

## Secciones:
- La web de LabCar esta conformada por :
* Navbar
* Hero
* Informacion
* Conduce
* Tarifa
* Footer

## Resumen:
1. El proyecto es una replica del diseño requerido.
2. Permite realizar la geolocalización del usuario y marca en el mapa con Google MAps.
3. Posee el marker de destino y origen y marcar la ruta en el mapa.
4. Con la data de kilometros , permite mostrar la tarifa.
5. Los inputs incluyen un ***autocompletado***.
6. Estructura con ***buenas practicas*** (Html , CSS, JS).
7. Utilizacion de ***API GOOGLE***.

## Desarrollo de la app

__***Navbar***__
- En el navbar encontraremos el logo y la opcion de : viaja, conduce, e inicia sesion.
![carrousel-img1](https://lh5.googleusercontent.com/oBtXyFQfu4pJ2nKXSiC5duzllNdoFPcQMEdkPixFQJeG9mZIfaslH459YUK_1kBA7NUoexJ-yHEPeAXv9CL4-_PHx062OKU-GZGcDQgGSGJLArEtKQ56_W-HYpQug5wSAV7K8BfZrC4)
- Y en la vista mobile solo se muestra el logo y las demas opciones pasan a ser parte de un menu desplegable.
![carrousel-img2](readme/carrusel2.png)

__***Hero***__
- Tiene como fondo la imagen "taxi" y a la derecha la opcion de registrarse o convertirse en conductor.
![carrousel-img2](readme/carrusel2.png)
- En la vista mobil se ve de la siguiente manera : Como se puede observar tanto como el texto y los botones cambian.
![carrousel-img2](readme/carrusel2.png)

__***Informacion***__
- En la seccion de Informacion se encuentra el celular y la info de la aplicacion.
![carrousel-img1](readme/pantalla1.png)
- En la vista mobile cambia : El titulo, el texto se esconde, aparece un texto debajo del contenedor del celular.
![carrousel-img1](readme/pantalla1.png)

__***Conductor***__
- En esta seccion de "Conductor" encontramos la imagen ***conduce*** con un contenido a la derecha.
![Carrusel](readme/pantalla2.png)
- En la vista mobile cambia, la parte del contenido que solo estaba a la derecha pasa a ocupar todo el ancho.
![Carrusel](readme/pantalla2.png)

__***Tarifa***__
- La seccion de "tarifa" cuenta con texto, dos input, un boton y un mapa.
- Por medio de la API geolocation nos mostrara en donde nos encontramos.
- Su funcionalidad es que se trace una ruta entre los puntos escritos en los input y que estime la tarifa en base a la distancia entre los puntos.
![Carrusel](readme/pantalla2.png)
- En la vista mobile solo estimara la tarifa entre los puntos que escriban en los inputs.
![Carrusel](readme/pantalla2.png)

__***Footer***__
- En el footer encontramos el logo, las redes sociales, link, tiendas y nombre.
![Carrusel](readme/pantalla2.png)
- En la vista mobile desaparece un bloque de links, los iconos parecen a la derecha, las tiendas debajo de los iconos y el nombre al final.
![Carrusel](readme/pantalla5.png)
