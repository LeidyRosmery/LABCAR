# LABCAR

LabCAr es una empresa de taxis que te permite pedir un taxi cuando quieras y en donde quieras. Tenemos una gran cantidad de conductores por todo el departamento. Se a comprobado que Labcar tiene las tarifas mas bajas del mercado.
Sabemos que tu tiempo es dinero, por lo que si nuestro servicio se demora en llegar mas de lo establecido te daremos un 10% de descuento en tu viaje. Puedes ver el demo del website haciendo click [aquí](https://laboratoriasprint05.herokuapp.com/).

## Secciones:
La web de LabCar esta conformada por :
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

![navbar](https://lh3.googleusercontent.com/7CJrwNvoaKJUEoriB9TyjQkEW22mAcseyELIeVSE-NnewDrpDoYeET-iuLOubPyw1gpqHxYAL9QxadfR69fgjQElmHN-HeCeDE0YUYeghzPJYI9AdHt_4pK0rNv8OTZMiHxtjArws-4)
- Y en la vista mobile solo se muestra el logo y las demas opciones pasan a ser parte de un menu desplegable.

![navbar](https://lh5.googleusercontent.com/oBtXyFQfu4pJ2nKXSiC5duzllNdoFPcQMEdkPixFQJeG9mZIfaslH459YUK_1kBA7NUoexJ-yHEPeAXv9CL4-_PHx062OKU-GZGcDQgGSGJLArEtKQ56_W-HYpQug5wSAV7K8BfZrC4)

__***Hero***__
- Tiene como fondo la imagen "taxi" y a la derecha la opcion de registrarse o convertirse en conductor.
![hero](https://lh3.googleusercontent.com/eIRzfce1wiwtX3vfJ2wY873wsn1SZ1BONcXEyuC3qFuc3n2ER9OcLsFqiRhpbKMwbq8Vcsj_7U_Jj1wQQ71JU3qk_ChTHFmcrnG9qQ21d6uoGCdh3flJU-OUJB07Oia6vI_oAegJdpQ)
- En la vista mobil se ve de la siguiente manera : Como se puede observar tanto como el texto y los botones cambian.
![hero-mobil](https://lh4.googleusercontent.com/bhoZ2NlQUswFwvFbOgCpMmhqLToN8bdTvtLyjnEi8kstfzEjTpFpLXT_QRErx-uT4vhoKNO3tHJ12OdZ0BDstsmFu8Em9UMjaeFBYJYjmnCeufIU-fyQ1PZ-UgHilFgNIg1wrWky7oc)

__***Informacion***__
- En la seccion de Informacion se encuentra el celular y la info de la aplicacion.
![informacion](https://lh4.googleusercontent.com/Ys_9M2aI2DAk1O_DQqKKxQDBWJ65xWnkR-M1djfFnx9N4n1nxJOrWr9qNUvUZMPxBzwpY7J7y5KTumxwemlFKeey7bTrf02JFdDiEwd7e3uhs6PmxnmB6hB5s5r-y0ZMQb-8eovg-TY)
- En la vista mobile cambia : El titulo, el texto se esconde, aparece un texto debajo del contenedor del celular.
![informacion-mobil](https://lh6.googleusercontent.com/1xICr_WaE4Xfy3eyP9Zur345-VkYzj0koJFfiDl66JGF6WiAC07NuOAK4mAWMo2TQaPLW56CWjMhY9dIy43rhkki47XlsFSm-YbMREpJHDRUumKHHVa6r_TcDqaMox9W-XStoRRWnY4)

__***Conductor***__
- En esta seccion de "Conductor" encontramos la imagen ***conduce*** con un contenido a la derecha.
![Conductor](https://lh6.googleusercontent.com/HdewahvgVBbttwGbUsL45H6HC5lx7yUOsAviQ5CZTjpOIDoJcucmwFOOD4YhcQhRpYKf3om5r08ME9liJGOCU9YkFxgpJYMBMXMLq_WYHG6PgClSZDgPVJxvMLkC8WoYbOt3_Vx72YI)
- En la vista mobile cambia, la parte del contenido que solo estaba a la derecha pasa a ocupar todo el ancho.
![Conductor-mobil](https://lh3.googleusercontent.com/3jkMqtH11I2bFK1o9rJhrZ6-zGrgrINIZrNhbxUYzRzFUpacIIVDIIh2uNrco20Z8e4-FrgZnRCt7A6xszsYyqJfF4XQ8dKJ5RGCY6XPu3lpufuanwz_fQYKQOARH9Wm1_A433u0D2A)

__***Tarifa***__
- La seccion de "tarifa" cuenta con texto, dos input, un boton y un mapa.
- Por medio de la API geolocation nos mostrara en donde nos encontramos.
- Su funcionalidad es que se trace una ruta entre los puntos escritos en los input y que estime la tarifa en base a la distancia entre los puntos.

![tarifa](https://lh3.googleusercontent.com/Y30EqIqw54kGHN32m21REOxpz5WM_AbhGu7XvfTdw1bVPni0nSH_M-E7Af15LAVs4xJzZHbktDqeRAQp4mvwW4iG6ojMrQbxTvEuw1J9mNR-7BDfN3X22p_FMROMu9vUUlgBXHFf_dc)
- En la vista mobile solo estimara la tarifa entre los puntos que escriban en los inputs.

![tarifa-mobil](https://lh4.googleusercontent.com/mzF88VW5ktT6xhNt2hCxKJxrPBUI9SZAFvDxx5zafIbmLwVBGGp0HSS2EkF5vxSYc8XqH1u2lXT51BX8Dnb_Ci8-zr4w76vFIAPL24IiV2PwB9QQmxrhet2RCweDlpO2qsj5-dCdbl8)

__***Footer***__
- En el footer encontramos el logo, las redes sociales, link, tiendas y nombre.

![footer](https://lh6.googleusercontent.com/HoK8e-eVZnAZmMJJkgrSbiURZ5wZloGLZ4Hps8h-NPB4MuF639mtkGOwGddxrjYWsW4n8q4lTMRwL2NSqyDQSYQrPoFrxU_qIRH7EGiTnpq6e8KKOg-8_JNmLrZd736x1sIMvJlpITY)
- En la vista mobile desaparece un bloque de links, los iconos parecen a la derecha, las tiendas debajo de los iconos y el nombre al final.

![footer-mobil](https://lh5.googleusercontent.com/q0qqN5RHtGuqCEdEWUhD3S_fgk3jARsXnQ1R2rusv7s_lZdh2rRJq1M0u1zrSqP7WiVyISYory_xaa0s6j7k2IMGmqZ_b8LfY_cA-5UzpQ6Mhvs9JZ_GOYjepSckX9dUp9h1cmO923Y)
