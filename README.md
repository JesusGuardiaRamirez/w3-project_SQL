

![Captura de pantalla 2023-05-02 a las 18 58 38](https://user-images.githubusercontent.com/125477881/235735442-76f28554-fa02-4c69-bafb-f1becf8df87b.png)



## Descripción:


Este es el segundo proyecto de Ironhack, del cual consiste en la creción de una base de datos. 

Partimos de unos archivos .csv, que formaban parte de la base de datos de un antiguo video-club, a partir de ellos construiremos una nueva base de datos estableciendo las relaciones correctas entre entidades. Tal y como aparecen en la imagen:

A la hora de crear la base de datos seguiremos las siguientes pautas:

* intentaremos conservar la mayor parte de los datos que se consideren de utilidad, aunque estos estén incompletos. Será una labor futura el decidir si se pueden actualizar estos datos con la información faltante, o eliminar dicha información

## Estas son alguna de las consideraciones a tener en cuenta:

- Consideramos que una película puede tener uno o más idiomas (tanto original como el de la copia)

- Una película solo puede tener una categoría

- Una película puede tener muchas copias, pero una copia sólo puede estar en una tienda

- Un empleado sólo puede estar asociado a una tienda

- Un alquiler sólo puede ser creado por un empleado

- etc.. 


![Captura de pantalla 2023-05-02 a las 15 37 32](https://user-images.githubusercontent.com/125477881/235735838-ea5bb7a8-378b-46dc-824b-37ab88549813.png)




### Este es un pequeño Analisis utiliando las Queries de SQL:

***********************************

En la imagen siguiente, detalla las veces que la misma pelicula ha sido alquilada.

![numero de veces que la pelicula fue alquilada](https://user-images.githubusercontent.com/125477881/235737798-3fc7c223-a106-4ee3-b128-bbc91fbac42a.png)

***********************************


En la imagen siguiente, detalla las veces que el mismo cliente ha alquilado alguna pelicula, por su Customer_ID.

![Captura de pantalla 2023-05-02 a las 17 51 08](https://user-images.githubusercontent.com/125477881/235739063-dfb85cd0-6da2-414e-af4b-9d2a0b2c215d.png)



***********************************


En la imagen siguiente, vemos las veces que el mismo actor ha trabajado en las peliculas.



![Captura de pantalla 2023-05-02 a las 18 42 01](https://user-images.githubusercontent.com/125477881/235739328-cdf1acf8-e826-4621-8650-5f3a28511234.png)




************************************

En la siguiente imagen, vereis cuantas peliculas tenemos dependiendo de su categoria. 


![Captura de pantalla 2023-05-02 a las 16 33 02](https://user-images.githubusercontent.com/125477881/235739596-6de262b9-3d37-4986-978c-0ec9fe3553c3.png)



*************************************


Y por ultimo tenemos un pequeño resumen de la cantidad que ha generado las peliculas por su renta.

![Captura de pantalla 2023-05-02 a las 16 39 49](https://user-images.githubusercontent.com/125477881/235739911-4d1be6ae-dd89-4168-91c5-5591a47af82f.png)




