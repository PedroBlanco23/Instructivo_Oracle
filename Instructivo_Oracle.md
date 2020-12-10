# Instructivo para crear Base Autónoma en Oracle 

## Tabla de contenidos

- [Instructivo para crear Base Autónoma en Oracle](#instructivo-para-crear-base-autónoma-en-oracle)
  - [Objetivo del instructivo](#objetivo-del-instructivo)
  - [Requisitos](#requisitos)
  - [Información a tener en cuenta](#información-a-tener-en-cuenta)
 - [Sección 1 Crear cuenta de Oracle Always Free](#sección-1-crear-cuenta-de-oracle-always-free)
 - [Sección 2 Crear base de datos Autónoma](#sección-2-crear-base-de-datos-autónoma)
 - [Sección 3 Descargar SQL Developer](#sección-3-descargar-sql-developer)
 - [Sección 4 Realizar conexión](#sección-4-realizar-conexión)
 - [Sección 5 Importar datos](#sección-5-importar-datos)
   - [Importar archivos Excel](#importar-archivos-excel)
   - [Importar archivo CSV TXT o DSV](#importar-archivo-csv-txt-o-dsv)
   - [Importar sin cabecera](#importar-sin-cabecera)
 - [Sección 6 Exportar datos](#sección-6-exportar-datos)



### Objetivo del instructivo

- Crear una cuenta en la Nube Always Free.
- Crear una base de datos Oracle Always Free.
- Descargar SQL Developer.
- Conectarse a la base de datos Oracle con SQL Developer. 
- Importar datos a la base utilizando archivos (Excel, TXT, etc).
- Exportar datos desde la base utilizando archivos  (Excel, TXT, etc).



### Requisitos

- Correo electrónico.
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

![](C:/Users/Pedro/OneDrive/Uade/proyecto division sistemas/git/capturas/AVISO.PNG)



## Sección 1 Crear cuenta de Oracle Always Free

Para crear nuestra cuenta dentro de Oracle, debemos dirigirnos al siguiente link.

https://www.oracle.com/ar/cloud/free/


![img1](C:/Users/Pedro/OneDrive/Uade/proyecto division sistemas/git/capturas/img1.png)



Ingresamos nuestra información personal.

![](C:/Users/Pedro/OneDrive/Uade/proyecto division sistemas/git/capturas/img2.png)



Luego, recibiremos un mail para validar el email.

![img3](C:/Users/Pedro/OneDrive/Uade/proyecto division sistemas/git/capturas/img3.png)



Ingresando a través del link, continuaremos el registro.

En nombre de compañía, de forma opcional pueden poner el nombre de UADE.

 ![](C:/Users/Pedro/OneDrive/Uade/proyecto division sistemas/git/capturas/img4.png)



En región elegir **Latin America (Sao Paulo).**

![](C:/Users/Pedro/OneDrive/Uade/proyecto division sistemas/git/capturas/img5.png)



Nuevamente, completamos con información personal.

![](C:/Users/Pedro/OneDrive/Uade/proyecto division sistemas/git/capturas/img6.png)



Ingresamos nuestro número de teléfono.

![](C:/Users/Pedro/OneDrive/Uade/proyecto division sistemas/git/capturas/img7.png)



> **Consejo:** Si no reciben el código SMS pueden contactarse con Oracle con el botón de ayuda. *(necesitaran hablar un poco de Inglés)*.

![](C:/Users/Pedro/OneDrive/Uade/proyecto division sistemas/git/capturas/imgsms.png)



En category and product eligen las siguientes.

![](C:/Users/Pedro/OneDrive/Uade/proyecto division sistemas/git/capturas/img8.png)

![](C:/Users/Pedro/OneDrive/Uade/proyecto division sistemas/git/capturas/img9.png)



Luego de verificar el número de teléfono, debemos ingresar el método de pago.

 ![](C:/Users/Pedro/OneDrive/Uade/proyecto division sistemas/git/capturas/img10.png)



 **AVISO**

> **Puede que se reciba un cobro de 1 dólar pero se cancela AUTOMATICAMENTE es solo para corroborar la cuenta.**



Cuenta creada. Ahora debemos esperar a que se procese. *(Puede tardar horas)*.

![](C:/Users/Pedro/OneDrive/Uade/proyecto division sistemas/git/capturas/img11.png)



## Sección 2 Crear base de datos Autónoma

Primero debemos iniciar sesión.

Nos dirigimos a https://www.oracle.com/index.html

![](C:/Users/Pedro/OneDrive/Uade/proyecto division sistemas/git/capturas/img12.png)



Ingresamos nuestro usuario.

![img13](C:/Users/Pedro/OneDrive/Uade/proyecto division sistemas/git/capturas/img13.png)



Elegimos **Single Sign-On**.

![img14](C:/Users/Pedro/OneDrive/Uade/proyecto division sistemas/git/capturas/img14.png)



Ingresamos con nuestro **correo electrónico**.

![img15](C:/Users/Pedro/OneDrive/Uade/proyecto division sistemas/git/capturas/img15.png)



Una vez que estamos dentro de **Oracle Cloud**, nos dirigimos a "Almacén de datos autónomo".

![img16](C:/Users/Pedro/OneDrive/Uade/proyecto division sistemas/git/capturas/img16.png)



Luego, entramos en "**Crear base de datos autónoma**".

![img17](C:/Users/Pedro/OneDrive/Uade/proyecto division sistemas/git/capturas/img17.png)



Colocamos un nombre *(para mostrar)* y para la base de datos *(interno)*. Pueden ser el mismo.

![img18](C:/Users/Pedro/OneDrive/Uade/proyecto division sistemas/git/capturas/img18.png)



Elegimos tipo de base *(preferentemente almacén de datos)* y compartida para ser gratuita.

![img19](C:/Users/Pedro/OneDrive/Uade/proyecto division sistemas/git/capturas/img19.png)



Marcamos la casilla Siempre gratis.

![img20](C:/Users/Pedro/OneDrive/Uade/proyecto division sistemas/git/capturas/img20.png)



Una vez marcada,  se configurará para **Always Free**.

![img21](C:/Users/Pedro/OneDrive/Uade/proyecto division sistemas/git/capturas/img21.png)



Indicamos la contraseña para **ADMIN** *(Con ella ingresaremos a la base de datos para conectarnos)*.

![img22](C:/Users/Pedro/OneDrive/Uade/proyecto division sistemas/git/capturas/img22.png)



Las configuraciones restantes podemos dejarlas por predeterminado. Clickeamos en **"Crear base de datos autónoma"**. 

![img23](C:/Users/Pedro/OneDrive/Uade/proyecto division sistemas/git/capturas/img23.png)





Esperamos a que la base termine de ser creada.

![img24](C:/Users/Pedro/OneDrive/Uade/proyecto division sistemas/git/capturas/img24.png)



## Sección 3 Descargar SQL Developer

Nos dirigimos a: https://www.oracle.com/ar/tools/downloads/sqldev-v192-downloads.html

Seleccionamos la versión adecuada para nuestro sistema operativo.

> NOTA: La versión JDK de 64 bits viene incluida con el JDK de Java (primer opción). Si tenemos un sistema de 32 bits, deberemos optar por descargar el JDK nosotros. link: https://www.oracle.com/java/technologies/javase/javase-jdk8-downloads.html

![img25](C:/Users/Pedro/OneDrive/Uade/proyecto division sistemas/git/capturas/img25.png)



Nos pedirá crearnos una cuenta **Oracle**. No tendrá relación con la creada para la nube, esta cuenta la usaremos para descargar SQL Developer.

![img26](C:/Users/Pedro/OneDrive/Uade/proyecto division sistemas/git/capturas/img26.png)



Ingresamos nuestros datos.

![img27](C:/Users/Pedro/OneDrive/Uade/proyecto division sistemas/git/capturas/img27.png)



Una vez hayamos iniciado sesión, comenzará la descarga.

![img28](C:/Users/Pedro/OneDrive/Uade/proyecto division sistemas/git/capturas/img28.png)



Luego, extraemos el archivo con WinRar o su programa de preferencia.

![img29](C:/Users/Pedro/OneDrive/Uade/proyecto division sistemas/git/capturas/img29.png)



Dentro de la carpeta extraída, encontraremos el ejecutable.

![img30](C:/Users/Pedro/OneDrive/Uade/proyecto division sistemas/git/capturas/img30.png)

![image-20201121190048553](C:/Users/Pedro/OneDrive/Uade/proyecto division sistemas/git/capturas/img31.png)

## Sección 4 Realizar conexión 

Primero, debemos descargar la credencial de nuestra base. Para ello, ingresamos dentro de la Nube de Oracle. *(Mismo procedimiento que realizamos antes de crear la base)*.



Una vez dentro, nos dirigimos a "**Almacén de datos autónomo**". y seleccionamos nuestra base.

![img32](C:/Users/Pedro/OneDrive/Uade/proyecto division sistemas/git/capturas/img32.png)



Una vez dentro, nos dirigimos a "**Conexión de base de datos**".

![img33](C:/Users/Pedro/OneDrive/Uade/proyecto division sistemas/git/capturas/img33.png)



Descargaremos la cartera.

![img34](C:/Users/Pedro/OneDrive/Uade/proyecto division sistemas/git/capturas/img34.png)



Nos pedirá una contraseña. Es por si perdemos el archivo, **no se utilizará para iniciar sesión.** 

![img35](C:/Users/Pedro/OneDrive/Uade/proyecto division sistemas/git/capturas/img35.png)



Descargamos el archivo. Les recomiendo guardarlo en una carpeta accesible.

![img36](C:/Users/Pedro/OneDrive/Uade/proyecto division sistemas/git/capturas/img36.png)



Una vez descargado, abrimos SQL Developer y nos dirigimos a "**Nueva galería**".

![img37](C:/Users/Pedro/OneDrive/Uade/proyecto division sistemas/git/capturas/img37.png)



Elegimos la opción "**Capa de base de datos**".

![img38](C:/Users/Pedro/OneDrive/Uade/proyecto division sistemas/git/capturas/img38.png)

- En nombre, elegimos el que queremos ya que es visual.
- En usuario colocamos **ADMIN**.
- En contraseña, introducimos la que **asignamos** para ADMIN cuando creamos la base.
- En tipo de conexión, **Cartera de Cloud** y en examinar seleccionamos el archivo que descargamos desde la página(***Wallet_NombreBase.zip***).

![img39](C:/Users/Pedro/OneDrive/Uade/proyecto division sistemas/git/capturas/img39.png)



Nos debería quedar así.

![img40](C:/Users/Pedro/OneDrive/Uade/proyecto division sistemas/git/capturas/img40.png)



Conectamos.

Nos pedirá nuevamente la contraseña.

![img41](C:/Users/Pedro/OneDrive/Uade/proyecto division sistemas/git/capturas/img41.png)



**Ya estamos conectados.** :blush:

![img42](C:/Users/Pedro/OneDrive/Uade/proyecto division sistemas/git/capturas/img42.png)

## Sección 5 Importar datos

Una vez conectados a la base, en la carpeta **Tablas(*Filtrado*)** hacemos click derecho, **importar datos.**

![img43](C:/Users/Pedro/OneDrive/Uade/proyecto division sistemas/git/capturas/img43.png)



Se nos abrirá lo siguiente.

![img44](C:/Users/Pedro/OneDrive/Uade/proyecto division sistemas/git/capturas/img44.png)

### Importar archivos Excel

En archivo, hacemos click en **examinar** y buscamos el archivo Excel.

![img45](C:/Users/Pedro/OneDrive/Uade/proyecto division sistemas/git/capturas/img45.png)



Automáticamente nos detectará la cabecera. De ser necesario, la podemos desmarcar para colocarla nosotros mismos luego. [*(ir a colocar cabecera pasa saber más)*](#importar-sin-cabecera).

![img46](C:/Users/Pedro/OneDrive/Uade/proyecto division sistemas/git/capturas/img46.png)



Luego, definiremos el nombre de la tabla.

![img47](C:/Users/Pedro/OneDrive/Uade/proyecto division sistemas/git/capturas/img47.png)



Aquí podemos elegir que **columnas** deseamos seleccionar y en qué orden. Del lado se encuentran las deseadas con su respectivo orden.

![img48](C:/Users/Pedro/OneDrive/Uade/proyecto division sistemas/git/capturas/img48.png)



Luego, nos permitirá cambiar tipo de datos entre otros o incluso **cambiar los nombres de las columnas**.

![img49](C:/Users/Pedro/OneDrive/Uade/proyecto division sistemas/git/capturas/img49.png)



Y  por último, se importa la tabla.

![img50](C:/Users/Pedro/OneDrive/Uade/proyecto division sistemas/git/capturas/img50.png)

**AVISO**

> Probablemente no podamos ver la tabla en la carpeta de "Tablas *(Filtrado)*" ya que debemos **refrescar** la conexión.

![img51](C:/Users/Pedro/OneDrive/Uade/proyecto division sistemas/git/capturas/img51.png)

 

Resultado.

![img52](C:/Users/Pedro/OneDrive/Uade/proyecto division sistemas/git/capturas/img52.png)

### Importar archivo CSV TXT o DSV

Nos dirigimos a **importar datos**, luego examinamos el archivo.

![img53](C:/Users/Pedro/OneDrive/Uade/proyecto division sistemas/git/capturas/img53.png)



Tendremos **más opciones** que con archivos Excel. Aquí podemos elegir el *delimitador de columnas, terminador de línea, entre otros*.

![img54](C:/Users/Pedro/OneDrive/Uade/proyecto division sistemas/git/capturas/img54.png)



En este caso *(un archivo CSV)*, debemos seleccionar el delimitador que utilizaremos entre columnas. En un CSV es **“;”** pero en un TXT puede ser cualquiera que este incluido ahí.

![img55](C:/Users/Pedro/OneDrive/Uade/proyecto division sistemas/git/capturas/img55.png)

![img56](C:/Users/Pedro/OneDrive/Uade/proyecto division sistemas/git/capturas/img56.png)



Luego, tendremos las mismas opciones que con los demás archivos.

![img57](C:/Users/Pedro/OneDrive/Uade/proyecto division sistemas/git/capturas/img57.png)

![img58](C:/Users/Pedro/OneDrive/Uade/proyecto division sistemas/git/capturas/img58.png)

![img59](C:/Users/Pedro/OneDrive/Uade/proyecto division sistemas/git/capturas/img59.png)

![img60](C:/Users/Pedro/OneDrive/Uade/proyecto division sistemas/git/capturas/img60.png)

![img61](C:/Users/Pedro/OneDrive/Uade/proyecto division sistemas/git/capturas/img61.png)



> **Recordar REFRESCAR!!!!**

Resultado.

![img62](C:/Users/Pedro/OneDrive/Uade/proyecto division sistemas/git/capturas/img62.png)



### Importar sin cabecera 

Seleccionamos el archivo que deseamos importar.

![img63](C:/Users/Pedro/OneDrive/Uade/proyecto division sistemas/git/capturas/img63.png)

Como se observa, el archivo no tiene cabecera. Entonces, desmarcamos "**Cabecera**".



Luego, seleccionamos las columnas deseadas.

![img64](C:/Users/Pedro/OneDrive/Uade/proyecto division sistemas/git/capturas/img64.png)



Ahora, definiremos los nombres de las columnas.

![img65](C:/Users/Pedro/OneDrive/Uade/proyecto division sistemas/git/capturas/img65.png)



Luego, realizamos el mismo procedimiento que con los demás archivos. 

Resultado.

>**Recordar REFRESCAR!!**

![img66](C:/Users/Pedro/OneDrive/Uade/proyecto division sistemas/git/capturas/img66.png)



## Sección 6 Exportar datos

Una vez conectados a la base, realizamos click derecho sobre la tabla *o tablas* que deseamos exportar. Seleccionamos **"Exportar".**

![img67](C:/Users/Pedro/OneDrive/Uade/proyecto division sistemas/git/capturas/img67.png)



Se nos abrirá la siguiente pestaña.

Deseleccionamos DDL *(Está opción guarda otros archivos con información de la tabla que no es pertinente para lo que deseamos)*.

![img68](C:/Users/Pedro/OneDrive/Uade/proyecto division sistemas/git/capturas/img68.png)



Aquí podemos elegir el formato de salida.

![img69](C:/Users/Pedro/OneDrive/Uade/proyecto division sistemas/git/capturas/img69.png)



Tenemos varias opciones de como guardar la/s tabla/s. 

- Puede ser en un archivo único (*Si es Excel, las tablas estarán en el mismo archivo pero en distintas hojas*).
- Nos permite elegir si queremos o no cabecera (Excel 2003 en formato).
- Si es un archivo TXT, nos permite elegir el delimitador.



> *Aviso*
>
> *Cuidado con la extensión del archivo al examinar, ya que si ponemos la extensión incorrecta dará error.*

<img src="C:/Users/Pedro/OneDrive/Uade/proyecto division sistemas/git/capturas/img70.png" alt="img70"/>

<img src="C:/Users/Pedro/OneDrive/Uade/proyecto division sistemas/git/capturas/img71.png" alt="img71"/>







Aquí podemos **Especificar Datos**.

<img src="C:/Users/Pedro/OneDrive/Uade/proyecto division sistemas/git/capturas/img72.png" alt="img72" />



Archivo exportado.

Resultado.

![img73](capturas/img73.png?raw=true)