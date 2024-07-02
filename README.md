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

Donde se muestran como opciones seis tipos de conversión de monedas, sin embargo se muestra una séptima opción en la que podremos ingresar una conversión diferente a las seis mostradas.

Si ingresa una opción fuera de las ocho mostradas en el menú se mostrara el siguiente texto.

<img src="https://github.com/Kpp94/ConversorDeMonedas/blob/main/img/Opc_Novalida_conversor.png">

Cuando escogemos una de las opciones válidas se realizara la consulta en la API ExchangeRate y mediante la biblioteca Gson se devolverá los datos de la consulta como son:

La cantidad a convertir, la moneda base, la moneda destino, el resultado de la conversión y factor de conversión de la moneda consultada.

<img src="https://github.com/Kpp94/ConversorDeMonedas/blob/main/img/Opciones_conversor.png">

Otra consulta.

<img src="https://github.com/Kpp94/ConversorDeMonedas/blob/main/img/Opc_3_conversor.png">

Cada que se haga una consulta se volverá al menú de inicio hasta que se seleccione salir del programa.

Al seleccionar la opción 7 se piden los siguientes datos.

- La cantidad a convertir.

- La moneda base a convertir.

- La moneda de destino.

Tal como se menciona en el programa las monedas base y destino deben ser ingresadas con el código de 3 letras basado en el formato ISO-4217 (https://www.iso.org/iso-4217-currency-codes.html)

<img src="https://github.com/Kpp94/ConversorDeMonedas/blob/main/img/opc_7_conversor.png">

Una vez que hayamos realizado todas nuestras consultas seleccionaremos la opción 8 de salida, esto nos retornara una despedida y un listado de las consultas realizadas en el programa.

<img src="https://github.com/Kpp94/ConversorDeMonedas/blob/main/img/salida_conversor.png">

<h5>Autor. Kevin Pérez Pérez</h5>
