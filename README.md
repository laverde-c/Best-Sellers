<h1> Best Sellers project </h1>

<p> Este proyecto nace a partir del curso tomado en Platzi de Manipulación y Transformación de datos con **Pandas** y **Numpy** </p>

<p> Tengo un archivo CSV descargado de Kaggle, este corresponde a una base de datos que relaciona los 50 libros mas vendidos (Best Sellers) en Estado Unidos por año en la decada de 2009 a 2019. Hago una primera exploración de la data para ver como está organizada y en el proceso me surgen las siguientes preguntas, que espero, poder responder en el proceso </p>

<ul>
        <li> ¿Cual es el autor que más Best Sellers ha publicado? </li>
        <li> ¿La ficción le gana a la realidad ? jaja </li>
        <li> ¿Cual es la distribución general de los precios de los libros y de los libros publicados por los 10 autores más vendidos? </li>
        <li> Si supongo que cada review es un lector, podría estimar cuanto dinero ganó cada autor, ¿Entonces, cuales fueron los autores que más ganaron dinero en esa decada? 
</ul>

<p> Haciendo el ejercicio de responder estás preguntas llegue a las siguientes conclusiones:

<ul>
        <li> 
        De de manera general, la ficción no supera a la relidad (jaja), pues si se venden más libros de 'non fiction'. Aunque hay una distribución equitativa entre el genero que escriben los 10 autores más vendidos.
        </li>
        <li>
        Podemos pensar que el precio de los libros influye en la cantidad de lectores (pues finalmente la compra de estos es lo que los hace Best Sellers) evidenciando que los libros de menos de 20 dolares son los que mayor acogida tienen 
        </li>
        <li>
        Sin embargo no necesariamente los más baratos son los que más ganancia dejan, aunque claro, no se puede asegurar dado que tengo mi data sesgada. Pero si supongo que cada lector es un review, y lo multiplico por el precio del libro, podría estimar el dinero ganado. En ese sentido lo que más atrajo mi atención fue que los autores que más 'Best Sellers' han publicado no aparecieron en el 10% de los autores que más dinero ganaron. 
        </li>
        <li>
        Vemos una tendencia positiva en la cantidad de lectores por año, bajo la hipotesis de que cada review corresponde a un lector.
        </li>
        <li> Continuando con nuestra hipotesis, podriamos estimar cuales fueron los libros más vendidos por año, obteniendo la sorpresa de que estos corresponden en su gran mayoría a libros de ficción</li>
</ul>

<p> Entonces, si yo fuera escritor, interesado más por llegar a más personas, me dedicaría a escribir libros de ficción pensando en que estos lleguen a las masas por un valor inferior a los 20$ </p>

<p> Fue interesentr hacer el ejercicio, utilizamos unicamente las librerías de pandas y matplotlib, ambas muy sencillas de utilizar </p>

<p> Si leiste hasta aquí, gracias por tu interes y espero que de alguna manera esto te pueda servir </p>