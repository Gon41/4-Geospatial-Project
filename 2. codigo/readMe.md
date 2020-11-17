# Proyecto -geospatial-data-project-

## 1. Objetivo del proyecto

La empresa que me ha contratado ha decidido cambiar sus oficinas, por lo que me han encargado encontrar la oficina adecuada en función de mínimo tres de los siguientes criterios (sabiendo de antemano que es imposible cubrir todos ellos):

    1) A los diseñadores les gusta ir a charlas de diseño y compartir conocimientos. Debe haber algunas empresas cercanas que también diseñen.
    2) El 30% de la empresa tiene al menos 1 hijo. (guarderias)
    3) A los desarrolladores les gusta estar cerca de nuevas empresas tecnológicas exitosas que hayan recaudado al menos 1 millón de dólares.
    4) A los ejecutivos les gusta mucho Starbucks. Asegúrate de que haya un Starbucks no muy lejos.
    5) Los gerentes de cuentas necesitan viajar mucho.
    6) Todas las personas de la empresa tienen entre 25 y 40 años, dales algún lugar para ir de fiesta.
    7) El CEO es vegano.
    8) Si quieres hacer feliz al encargado de mantenimiento, un estadio de baloncesto debe estar a unos 10 km.
    9) El perro de la oficina "Pepe" necesita un peluquero todos los meses. Asegúrese de que haya uno no demasiado lejos.

He elegido los puntos 1, 7 y 8.

------

## 2. Premisa de desarrollo inicial

La intención preliminar consiste en analizar que empresas dentro del archivo **companies.json** cumplen con uno de los requisitos iniciales.

Después proceder a ubicar mi empresa entre las posibles ubicaciones de las empresas, para después mediante geolocalización y la API obtener los requisitos en base a la cercania de la empresa.

----

## 3. Hoja de ruta

La ubicación de la empresa la he eligido en base a que espacios importantes de diseño se encuentran "cerca" de la empresa.

3.1. Para ello y basándome en la lista proporcionada por: https://gruposaglo.com/2019/05/23/las-mejores-escuelas-de-diseno-en-los-estados-unidos/ hago la primera criba entre costa este y oeste, viendo que en la costa oeste hay dos centros importantes en el estado de Nueva York, concretamente el **Instituto Pratt** y el **Instituto de Tecnología de Rochester**

3.2. El segundo paso es ver cuantas empresas hay en la ciudad de Nueva York como centro neurálgico urbanita del estado y del país.

3.3. Leo la documentación e investigo como conectar la API de FourSquare (elegida entre otras opciones).

3.4. Realizo el *unwinded* de la BBDD en MongoDB, para separar las diferentes oficinas que pueda tener una sola empresa.

3.5. Genero el código para acceder a las querys elegidas con los parámetros que necesito.

3.6. Busco las diferentes querys y genero el código que  automatice la obtención de los datos necesarios.

3.7. Por último genero un mapa con los marcadores encontrados y lo personalizo.

---

## 4. Dificultades encontradas 

    - Visualizar cuál era el primer paso para comenzar el proyecto. 
    - Pelear con la API de FourSquare y no saber obtener los datos.
    - Realizar el *unwinded*.
    - Automatizar la salida de las querys
    - Para automatizar la query pelearme para meterlas en las funciones.

----

## 5. Conclusiones

Este ejercicio está muy entretenido y además es muy visual. Es muy completo para prácticar todo lo que hemos ido dando.

En cuánto al trabajo en sí, he obtenido un punto de cada apartado, y he señalado las dos empresas "finalistas" de mi query.

----

## 6. Posibles mejoras

Desde el principio optimizar el tiempo en determinadas tareas y sobretodo automatizar los procesos, aspecto que no conseguí.