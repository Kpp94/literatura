# Literatura (Consulta de libros) <img src="https://w7.pngwing.com/pngs/776/145/png-transparent-books-illustration-book-book-rectangle-presentation-desktop-wallpaper-thumbnail.png" width="30px">

Para este Challenge de Alura Latam se presenta una app para consulta de libros consumiendo la API libre Gutendex



## Caracteristicas 

- Lenguaje de programacion. Java
- API Gutendex
- Base de Datos PostgreSQL 


## Preparando el Ambiente <img src="https://cdn-icons-png.flaticon.com/512/2071/2071756.png" width="30px">

- Descargue el proyecto desde el repositorio.
- Cree su base de Datos en Postgresql
- Modifique sus variables de entorno para poder hacer la conexión a la base de datos
- Ejecute el archivo el su IDE de preferencia.
- Ejecute el archivo LiteraturaApplication del proyecto.

## Funcionalidad

Al inicializar el programa te encontrarás con el siguiente menú

<img src="https://github.com/Kpp94/literatura/blob/master/img/MenuL.png">

Tendremos el siguiente listado de Opciones:

- Buscar Libro por Titulo
- Listar Libros Registrados
- Listar Autores registrados
- Listar Autores vivos en determinado año
- Listar libros por idioma


Algunas de las funciones es buscar libro por titulo que al seleccionarla nos pide que escribamos el nombre del libro que queremos consultar, aqui si no escribieramos el titulo completo y solo usamos una palabra del mismo, el programa buscara dicha palabra y arrojara el primer resultado que se presente.
Posteriormente retornara los datos del libro encontrado. En caso de no encontrar ningun libro se avisara.

<img src="https://github.com/Kpp94/literatura/blob/master/img/Opcion1L.png">

Todos los ibros consultados se iran guardando en la base de datos donde podran ser consultados nuevamente, estos datos se guardaran tanto como el autor y el idioma del libro.

Ya guardado los libros consultados podemos hacer una consulta de los mismos asi como la lista de autores dependiendo de los libros que hemos consultado.

<img src="https://github.com/Kpp94/literatura/blob/master/img/Opcion2L.png">

<img src="https://github.com/Kpp94/literatura/blob/master/img/Opcion3L.png">

Podemos consultar en la base de datos las listas generadas a paritr de cada consulta.

<img src="https://github.com/Kpp94/literatura/blob/master/img/Lista%20libros.png">

## Datos a considerar <img src="https://w7.pngwing.com/pngs/973/727/png-transparent-amplifier-owner-s-manual-product-manuals-sign-electric-potential-difference-importance-thumbnail.png" width="30px">
- Si se selecciona una opcion fuera de las mostradas en el menu, se mostrara una alerta mencionando que la opcion no es valida.
- No se pueden registrar dos veces el mismo libro.
- Se pueden consutlar varios libros de un mismo autor.
- La consulta de libros por idioma se usa escribiendo las dos letras del idioma con base a la norma ISO 639-1

<h5>Autor. Kevin Pérez Pérez</h5>
