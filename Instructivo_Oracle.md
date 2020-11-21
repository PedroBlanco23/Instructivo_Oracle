# Instructivo para crear Base Autónoma en Oracle 

[TOC]

### Objetivo del instructivo

- Crear una cuenta en la Nube Always Free

- Crear una base de datos Oracle Always Free.
- Descargar SQL Developer.
- Conectarse a la base de datos Oracle con SQL Developer. 
- Importar datos a la base utilizando archivos (Excel, TXT, etc).
- Exportar datos desde la base utilizando archivos  (Excel, TXT, etc).



### Requisitos

- Correo electrónico,
- Información personal.
- Contar con una tarjeta de crédito no prepaga (*Solo para que Oracle corrobore la identidad, no se realizará ningún cobro)*.
- Número telefónico.



### Información a tener en cuenta

Una cuenta free de Oracle Cloud proporciona lo siguientes servicios de por vida:

- 2 bases de datos en total, cada una con 1 CPU y 20GB de almacenamiento.
- 2 máquinas virtuales con 1/8 CPU y 1 GB de memoria c/u.
- 2 volúmenes de bloque *(100gb en total)*.
- 10 GB de almacenamiento de objetos.
- 10 GB de almacenamiento de archivos.
- Además de $300 dólares de crédito por 1 mes para probar cualquier producto o servicio dentro de la nube.

![](capturas\AVISO.PNG?raw=true)



## Sección 1: Crear cuenta de Oracle Always Free

Para crear nuestra cuenta dentro de Oracle, debemos dirigirnos al siguiente link:

https://www.oracle.com/ar/cloud/free/

![img1](capturas\img1.jpg?raw=true)



Ingresamos nuestra información personal.

![](capturas\img2.jpg?raw=true)



Luego, recibiremos un mail para validar el email.

![img3](C:\Users\Pedro\OneDrive\Uade\proyecto division sistemas\git\capturas\img3.jpg)



Ingresando a través del link, continuaremos el registro.

En nombre de compañía, de forma opcional pueden poner el nombre de UADE.

 ![](capturas\img4.jpg?raw=true)



En región elegir **Latin America (Sao Paulo)**

![](capturas\img5.jpg?raw=true)



Nuevamente, completamos con información personal.

![](capturas\img6.jpg?raw=true)



Ingresamos nuestro número de teléfono.

![](capturas\img7.jpg?raw=true)



**Consejo:** Si no reciben el código SMS pueden contactarse con Oracle con el botón de ayuda. *(necesitaran hablar un poco de Inglés)*

![](capturas\imgsms.jpg?raw=true)



En category and product eligen las siguientes:

![](capturas\img8.jpg?raw=true)

![](capturas\img9.jpg?raw=true)



Luego de verificar el número de teléfono, debemos ingresar el método de pago.

 ![](capturas\img10.jpg?raw=true)



**AVISO: Puede que se reciba un cobro de 1 dólar pero se cancela AUTOMATICAMENTE es solo para corroborar la cuenta.**



Cuenta creada. Ahora debemos esperar a que se procese. *(Puede tardar horas)*

![](capturas\img11.jpg?raw=true)



## Sección 2: Crear base de datos Autónoma

Primero debemos iniciar sesión.

Nos dirigimos a https://www.oracle.com/index.html

![](capturas\img12.jpg?raw=true)



Ingresamos nuestro usuario.

![img13](capturas\img13.jpg?raw=true)



Elegimos **Single Sign-On**.

![img14](capturas\img14.jpg?raw=true)



Ingresamos con nuestro **correo electrónico**.

![img15](capturas\img15.jpg?raw=true)



Una vez que estamos dentro de **Oracle Cloud**, nos dirigimos a "Almacén de datos autónomo".

![img16](capturas\img16.jpg?raw=true)



Luego, entramos en "**Crear base de datos autónoma**".

![img17](capturas\img17.jpg?raw=true)



Colocamos un nombre *(para mostrar)* y para la base de datos *(interno)*. Pueden ser el mismo.

![img18](capturas\img18.jpg?raw=true)



Elegimos tipo de base *(preferentemente almacén de datos)* y compartida para ser gratuita.

![img19](capturas\img19.jpg?raw=true)



Marcamos la casilla Siempre gratis.

![img20](capturas\img20.jpg?raw=true)



Una vez marcada,  se configurará para **Always Free**.

![img21](capturas\img21.jpg?raw=true)



Indicamos la contraseña para **ADMIN** *(Con ella ingresaremos a la base de datos para conectarnos)*.

![img22](capturas\img22.jpg?raw=true)



Las configuraciones restantes podemos dejarlas por predeterminado. Clickeamos en **"Crear base de datos autónoma"**. 

![img23](capturas\img23.jpg?raw=true)





Esperamos a que la base termine de ser creada.

![img24](capturas\img24.jpg?raw=true)



## Sección 3: Descargar SQL Developer

Nos dirigimos a: https://www.oracle.com/ar/tools/downloads/sqldev-v192-downloads.html

Seleccionamos la versión adecuada para nuestro sistema operativo.

![img25](capturas\img25.jpg)



Nos pedirá crearnos una cuenta **Oracle**. No tendrá relación con la creada para la nube, esta cuenta la usaremos para descargar SQL Developer.

![img26](capturas\img26.jpg)



Ingresamos nuestros datos

![img27](C:\Users\Pedro\OneDrive\Uade\proyecto division sistemas\git\capturas\img27.jpg)



Una vez hayamos iniciado sesión, comenzará la descarga.

![img28](C:\Users\Pedro\OneDrive\Uade\proyecto division sistemas\git\capturas\img28.jpg)



Luego, extraemos el archivo con WinRar o su programa de preferencia.

![img29](C:\Users\Pedro\OneDrive\Uade\proyecto division sistemas\git\capturas\img29.jpg)



Dentro de la carpeta extraída, encontraremos el ejecutable.

![img30](C:\Users\Pedro\OneDrive\Uade\proyecto division sistemas\git\capturas\img30.jpg)

![image-20201121190048553](C:\Users\Pedro\AppData\Roaming\Typora\typora-user-images\image-20201121190048553.png)

## Sección 4: Realizar conexión 

Primero, debemos descargar la credencial de nuestra base. Para ello, ingresamos dentro de la Nube de Oracle. *(Mismo procedimiento que realizamos antes de crear la base)*.



Una vez dentro, nos dirigimos a "**Almacén de datos autónomo**". y seleccionamos nuestra base.

![img32](C:\Users\Pedro\OneDrive\Uade\proyecto division sistemas\git\capturas\img32.jpg)



Una vez dentro, nos dirigimos a "**Conexión de base de datos**".

![img33](C:\Users\Pedro\OneDrive\Uade\proyecto division sistemas\git\capturas\img33.jpg)



Descargaremos la cartera.

![img34](C:\Users\Pedro\OneDrive\Uade\proyecto division sistemas\git\capturas\img34.jpg)



Nos pedirá una contraseña. Es por si perdemos el archivo, **no se utilizará para iniciar sesión.** 

![img35](C:\Users\Pedro\OneDrive\Uade\proyecto division sistemas\git\capturas\img35.jpg)



Descargamos el archivo. Les recomiendo guardarlo en una carpeta accesible.

![img36](C:\Users\Pedro\OneDrive\Uade\proyecto division sistemas\git\capturas\img36.jpg)



Una vez descargado, abrimos SQL Developer y nos dirigimos a "**Nueva galería**".

![img37](C:\Users\Pedro\OneDrive\Uade\proyecto division sistemas\git\capturas\img37.jpg)



Elegimos la opción "**Capa de base de datos**".

![img38](C:\Users\Pedro\OneDrive\Uade\proyecto division sistemas\git\capturas\img38.jpg)

- En nombre, elegimos el que queremos ya que es visual.
- En usuario colocamos **ADMIN**.
- En contraseña, introducimos la que **asignamos** para ADMIN cuando creamos la base.
- En tipo de conexión, **Cartera de Cloud** y en examinar seleccionamos el archivo que descargamos desde la página(**Wallet_NombreBase.zip**).

![img39](C:\Users\Pedro\OneDrive\Uade\proyecto division sistemas\git\capturas\img39.jpg)



Nos debería quedar así.

![img40](C:\Users\Pedro\OneDrive\Uade\proyecto division sistemas\git\capturas\img40.jpg)



Conectamos.

Nos pedirá nuevamente la contraseña.

![img41](C:\Users\Pedro\OneDrive\Uade\proyecto division sistemas\git\capturas\img41.jpg)



**Ya estamos conectados.** :blush:

![img42](C:\Users\Pedro\OneDrive\Uade\proyecto division sistemas\git\capturas\img42.jpg)

## Sección 5: Importar datos

Una vez conectados a la base, en la carpeta **Tablas(Filtrado)** hacemos click derecho, **importar datos.**

![img43](C:\Users\Pedro\OneDrive\Uade\proyecto division sistemas\git\capturas\img43.jpg)



Se nos abrirá lo siguiente.

![img44](C:\Users\Pedro\OneDrive\Uade\proyecto division sistemas\git\capturas\img44.jpg)

### Importar archivos Excel

En archivo, hacemos click en **examinar** y buscamos el archivo Excel.

![img45](C:\Users\Pedro\OneDrive\Uade\proyecto division sistemas\git\capturas\img45.jpg)



Automáticamente nos detectará la cabecera. De ser necesario, la podemos desmarcar para colocarla nosotros mismos luego. (ir a colocar cabecera pasa saber más).

![img46](C:\Users\Pedro\OneDrive\Uade\proyecto division sistemas\git\capturas\img46.jpg)



Luego, definiremos el nombre de la tabla.

![img47](C:\Users\Pedro\OneDrive\Uade\proyecto division sistemas\git\capturas\img47.jpg)



Aquí podemos elegir que **columnas** deseamos seleccionar y en qué orden. Del lado se encuentran las deseadas con su respectivo orden.

![img48](C:\Users\Pedro\OneDrive\Uade\proyecto division sistemas\git\capturas\img48.jpg)



Luego, nos permitirá cambiar tipo de datos entre otros o incluso **cambiar los nombres de las columnas**.

![img49](C:\Users\Pedro\OneDrive\Uade\proyecto division sistemas\git\capturas\img49.jpg)



Y  por último, se importa la tabla.

![img50](C:\Users\Pedro\OneDrive\Uade\proyecto division sistemas\git\capturas\img50.jpg)

**AVISO**

Probablemente no podamos ver la tabla en la carpeta de "Tablas (Filtrado)" ya que debemos **refrescar** la conexión.

![img51](C:\Users\Pedro\OneDrive\Uade\proyecto division sistemas\git\capturas\img51.jpg)

 

Resultado.

![img52](C:\Users\Pedro\OneDrive\Uade\proyecto division sistemas\git\capturas\img52.jpg)

### Importar archivo CSV, TXT o DSV

Nos dirigimos a **importar datos**, luego examinamos el archivo.

![img53](C:\Users\Pedro\OneDrive\Uade\proyecto division sistemas\git\capturas\img53.jpg)



Tendremos **más opciones** que con archivos Excel. Aquí podemos elegir el *delimitador de columnas, terminador de línea, entre otros*.

![img54](C:\Users\Pedro\OneDrive\Uade\proyecto division sistemas\git\capturas\img54.jpg)



En este caso *(un archivo CSV)*, debemos seleccionar el delimitador que utilizaremos entre columnas. En un CSV es **“;”** pero en un TXT puede ser cualquiera que este incluido ahí.

![img55](C:\Users\Pedro\OneDrive\Uade\proyecto division sistemas\git\capturas\img55.jpg)

![img56](C:\Users\Pedro\OneDrive\Uade\proyecto division sistemas\git\capturas\img56.jpg)



Luego, tendremos las mismas opciones que con los demás archivos.

![img57](C:\Users\Pedro\OneDrive\Uade\proyecto division sistemas\git\capturas\img57.jpg)

![img58](C:\Users\Pedro\OneDrive\Uade\proyecto division sistemas\git\capturas\img58.jpg)

![img59](C:\Users\Pedro\OneDrive\Uade\proyecto division sistemas\git\capturas\img59.jpg)

![img60](C:\Users\Pedro\OneDrive\Uade\proyecto division sistemas\git\capturas\img60.jpg)

![img61](C:\Users\Pedro\OneDrive\Uade\proyecto division sistemas\git\capturas\img61.jpg)



**Recordar REFRESCAR!!!!**

Resultado.

![img62](C:\Users\Pedro\OneDrive\Uade\proyecto division sistemas\git\capturas\img62.jpg)



### Importar sin cabecera 

Seleccionamos el archivo que deseamos importar.

![img63](C:\Users\Pedro\OneDrive\Uade\proyecto division sistemas\git\capturas\img63.jpg)

Como se observa, el archivo no tiene cabecera. Entonces, desmarcamos "**Cabecera**".



Luego, seleccionamos las columnas deseadas.

![img64](C:\Users\Pedro\OneDrive\Uade\proyecto division sistemas\git\capturas\img64.jpg)



Ahora, definiremos los nombres de las columnas.

![img65](C:\Users\Pedro\OneDrive\Uade\proyecto division sistemas\git\capturas\img65.jpg)



Luego, realizamos el mismo procedimiento que con los demás archivos. 

Resultado.

**Recordar REFRESCAR!!**

![img66](C:\Users\Pedro\OneDrive\Uade\proyecto division sistemas\git\capturas\img66.jpg)



## Sección 6: Exportar datos

Una vez conectados a la base, realizamos click derecho sobre la tabla *o tablas* que deseamos exportar. seleccionamos **"Exportar"**

![img67](C:\Users\Pedro\OneDrive\Uade\proyecto division sistemas\git\capturas\img67.jpg)



Se nos abrirá la siguiente pestaña.

Deseleccionamos DDL *(Está opción guarda otros archivos con información de la tabla que no es pertinente para lo que deseamos)*

![img68](C:\Users\Pedro\OneDrive\Uade\proyecto division sistemas\git\capturas\img68.JPG)



Aquí podemos elegir el formato de salida.

![img69](C:\Users\Pedro\OneDrive\Uade\proyecto division sistemas\git\capturas\img69.jpg)



Tenemos varias opciones de como guardar la tabla/s. 

- Puede ser en un archivo único (*Si es Excel, las tablas estarán en el mismo archivo pero en distintas hojas.*)
- Nos permite elegir si queremos o no cabecera (Excel 2003 en formato).
- Si es un archivo TXT, nos permite elegir el delimitador



*Aviso: Cuidado con la extensión del archivo al examinar, ya que si ponemos la extensión correcta dará error.*

<img src="C:\Users\Pedro\OneDrive\Uade\proyecto division sistemas\git\capturas\img70.jpg" alt="img70" style="zoom: 50%;" />

<img src="C:\Users\Pedro\OneDrive\Uade\proyecto division sistemas\git\capturas\img71.JPG" alt="img71" style="zoom: 80%;" />







Aquí podemos **Especificar Datos**

<img src="C:\Users\Pedro\OneDrive\Uade\proyecto division sistemas\git\capturas\img72.JPG" alt="img72" style="zoom:80%;" />



Archivo exportado.

Resultado.

![img73](C:\Users\Pedro\OneDrive\Uade\proyecto division sistemas\git\capturas\img73.JPG)