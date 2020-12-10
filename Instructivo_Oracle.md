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

![](capturas/AVISO.PNG?raw=true)



## Sección 1 Crear cuenta de Oracle Always Free

Para crear nuestra cuenta dentro de Oracle, debemos dirigirnos al siguiente link.

https://www.oracle.com/ar/cloud/free/

![img1](capturas/img1.png?raw=true)



Ingresamos nuestra información personal.

![](capturas/img2.png?raw=true)



Luego, recibiremos un mail para validar el email.

![img3](capturas/img3.png?raw=true)



Ingresando a través del link, continuaremos el registro.

En nombre de compañía, de forma opcional pueden poner el nombre de UADE.

![](capturas/img4.png?raw=true)



En región elegir **Latin America (Sao Paulo).**

![](capturas/img5.png?raw=true)



Nuevamente, completamos con información personal.

![](capturas/img6.png?raw=true)



Ingresamos nuestro número de teléfono.

![](capturas/img7.png?raw=true)



> **Consejo:** Si no reciben el código SMS pueden contactarse con Oracle con el botón de ayuda. *(necesitaran hablar un poco de Inglés)*.

![](capturas/imgsms.png?raw=true)



En category and product eligen las siguientes.

![](capturas/img8.png?raw=true)

![](capturas/img9.png?raw=true)



Luego de verificar el número de teléfono, debemos ingresar el método de pago.

![](capturas/img10.png?raw=true)



 **AVISO**

> **Puede que se reciba un cobro de 1 dólar pero se cancela AUTOMATICAMENTE es solo para corroborar la cuenta.**



Cuenta creada. Ahora debemos esperar a que se procese. *(Puede tardar horas)*.

![](capturas/img11.png?raw=true)



## Sección 2 Crear base de datos Autónoma

Primero debemos iniciar sesión.

Nos dirigimos a https://www.oracle.com/index.html

![](capturas/img12.png?raw=true)



Ingresamos nuestro usuario.

![img13](capturas/img13.png?raw=true)



Elegimos **Single Sign-On**.

![img14](capturas/img14.png?raw=true)



Ingresamos con nuestro **correo electrónico**.

![img15](capturas/img15.png?raw=true)



Una vez que estamos dentro de **Oracle Cloud**, nos dirigimos a "Almacén de datos autónomo".

![img16](capturas/img16.png?raw=true)



Luego, entramos en "**Crear base de datos autónoma**".

![img17](capturas/img17.png?raw=true)



Colocamos un nombre *(para mostrar)* y para la base de datos *(interno)*. Pueden ser el mismo.

![img18](capturas/img18.png?raw=true)



Elegimos tipo de base *(preferentemente almacén de datos)* y compartida para ser gratuita.

![img19](capturas/img19.png?raw=true)



Marcamos la casilla Siempre gratis.

![img20](capturas/img20.png?raw=true)



Una vez marcada,  se configurará para **Always Free**.

![img21](capturas/img21.png?raw=true)



Indicamos la contraseña para **ADMIN** *(Con ella ingresaremos a la base de datos para conectarnos)*.

![img22](capturas/img22.png?raw=true)



Las configuraciones restantes podemos dejarlas por predeterminado. Clickeamos en **"Crear base de datos autónoma"**. 

![img23](capturas/img23.png?raw=true)





Esperamos a que la base termine de ser creada.

![img24](capturas/img24.png?raw=true)



## Sección 3 Descargar SQL Developer

Nos dirigimos a: https://www.oracle.com/ar/tools/downloads/sqldev-v192-downloads.html

Seleccionamos la versión adecuada para nuestro sistema operativo.

> NOTA: La versión JDK de 64 bits viene incluida con el JDK de Java (primer opción). Si tenemos un sistema de 32 bits, deberemos optar por descargar el JDK nosotros. link: https://www.oracle.com/java/technologies/javase/javase-jdk8-downloads.html

![img25](capturas/img25.png)



Nos pedirá crearnos una cuenta **Oracle**. No tendrá relación con la creada para la nube, esta cuenta la usaremos para descargar SQL Developer.

![img26](capturas/img26.png)



Ingresamos nuestros datos.

![img27](capturas/img27.png?raw=true)



Una vez hayamos iniciado sesión, comenzará la descarga.

![img28](capturas/img28.png?raw=true)



Luego, extraemos el archivo con WinRar o su programa de preferencia.

![img29](capturas/img29.png?raw=true)



Dentro de la carpeta extraída, encontraremos el ejecutable.

![img30](capturas/img30.png?raw=true)

![image-20201121190048553](capturas/img31.png?raw=true)

## Sección 4 Realizar conexión 

Primero, debemos descargar la credencial de nuestra base. Para ello, ingresamos dentro de la Nube de Oracle. *(Mismo procedimiento que realizamos antes de crear la base)*.



Una vez dentro, nos dirigimos a "**Almacén de datos autónomo**". y seleccionamos nuestra base.

![img32](capturas/img32.png?raw=true)



Una vez dentro, nos dirigimos a "**Conexión de base de datos**".

![img33](capturas/img33.png?raw=true)



Descargaremos la cartera.

![img34](capturas/img34.png?raw=true)



Nos pedirá una contraseña. Es por si perdemos el archivo, **no se utilizará para iniciar sesión.** 

![img35](capturas/img35.png?raw=true)



Descargamos el archivo. Les recomiendo guardarlo en una carpeta accesible.

![img36](capturas/img36.png?raw=true)



Una vez descargado, abrimos SQL Developer y nos dirigimos a "**Nueva galería**".

![img37](capturas/img37.png?raw=true)



Elegimos la opción "**Capa de base de datos**".

![img38](capturas/img38.png?raw=true)

- En nombre, elegimos el que queremos ya que es visual.
- En usuario colocamos **ADMIN**.
- En contraseña, introducimos la que **asignamos** para ADMIN cuando creamos la base.
- En tipo de conexión, **Cartera de Cloud** y en examinar seleccionamos el archivo que descargamos desde la página(***Wallet_NombreBase.zip***).

![img39](capturas/img39.png?raw=true)



Nos debería quedar así.

![img40](capturas/img40.png?raw=true)



Conectamos.

Nos pedirá nuevamente la contraseña.

![img41](capturas/img41.png?raw=true)



**Ya estamos conectados.** :blush:

![img42](capturas/img42.png?raw=true)

## Sección 5 Importar datos

Una vez conectados a la base, en la carpeta **Tablas(*Filtrado*)** hacemos click derecho, **importar datos.**

![img43](capturas/img43.png?raw=true)



Se nos abrirá lo siguiente.

![img44](capturas/img44.png?raw=true)

### Importar archivos Excel

En archivo, hacemos click en **examinar** y buscamos el archivo Excel.

![img45](capturas/img45.png?raw=true)



Automáticamente nos detectará la cabecera. De ser necesario, la podemos desmarcar para colocarla nosotros mismos luego. [*(ir a colocar cabecera pasa saber más)*](#importar-sin-cabecera).

![img46](capturas/img46.png?raw=true)



Luego, definiremos el nombre de la tabla.

![img47](capturas/img47.png?raw=true)



Aquí podemos elegir que **columnas** deseamos seleccionar y en qué orden. Del lado se encuentran las deseadas con su respectivo orden.

![img48](capturas/img48.png?raw=true)



Luego, nos permitirá cambiar tipo de datos entre otros o incluso **cambiar los nombres de las columnas**.

![img49](capturas/img49.png?raw=true)



Y  por último, se importa la tabla.

![img50](capturas/img50.png?raw=true)

**AVISO**

> Probablemente no podamos ver la tabla en la carpeta de "Tablas *(Filtrado)*" ya que debemos **refrescar** la conexión.

![img51](capturas/img51.png?raw=true)

 

Resultado.

![img52](capturas/img52.png?raw=true)

### Importar archivo CSV TXT o DSV

Nos dirigimos a **importar datos**, luego examinamos el archivo.

![img53](capturas/img53.png?raw=true)



Tendremos **más opciones** que con archivos Excel. Aquí podemos elegir el *delimitador de columnas, terminador de línea, entre otros*.

![img54](capturas/img54.png?raw=true)



En este caso *(un archivo CSV)*, debemos seleccionar el delimitador que utilizaremos entre columnas. En un CSV es **“;”** pero en un TXT puede ser cualquiera que este incluido ahí.

![img55](capturas/img55.png?raw=true)

![img56](capturas/img56.png?raw=true)



Luego, tendremos las mismas opciones que con los demás archivos.

![img57](capturas/img57.png?raw=true)

![img58](capturas/img58.png?raw=true)

![img59](capturas/img59.png?raw=true)

![img60](capturas/img60.png?raw=true)

![img61](capturas/img61.png?raw=true)



> **Recordar REFRESCAR!!!!**

Resultado.

![img62](capturas/img62.png?raw=true)



### Importar sin cabecera 

Seleccionamos el archivo que deseamos importar.

![img63](capturas/img63.png?raw=true)

Como se observa, el archivo no tiene cabecera. Entonces, desmarcamos "**Cabecera**".



Luego, seleccionamos las columnas deseadas.

![img64](capturas/img64.png?raw=true)



Ahora, definiremos los nombres de las columnas.

![img65](capturas/img65.png?raw=true)



Luego, realizamos el mismo procedimiento que con los demás archivos. 

Resultado.

>**Recordar REFRESCAR!!**

![img66](capturas/img66.png?raw=true)



## Sección 6 Exportar datos

Una vez conectados a la base, realizamos click derecho sobre la tabla *o tablas* que deseamos exportar. Seleccionamos **"Exportar".**

![img67](capturas/img67.png?raw=true)



Se nos abrirá la siguiente pestaña.

Deseleccionamos DDL *(Está opción guarda otros archivos con información de la tabla que no es pertinente para lo que deseamos)*.

![img68](capturas/img68.png?raw=true)



Aquí podemos elegir el formato de salida.

![img69](capturas/img69.png?raw=true)



Tenemos varias opciones de como guardar la/s tabla/s. 

- Puede ser en un archivo único (*Si es Excel, las tablas estarán en el mismo archivo pero en distintas hojas*).
- Nos permite elegir si queremos o no cabecera (Excel 2003 en formato).
- Si es un archivo TXT, nos permite elegir el delimitador.



> *Aviso*
>
> *Cuidado con la extensión del archivo al examinar, ya que si ponemos la extensión incorrecta dará error.*

![img70](capturas/img70.png?raw=true)

![img71](capturas/img71.png?raw=true)



Aquí podemos **Especificar Datos**.

![img72](capturas/img72.png?raw=true)



Archivo exportado.

Resultado.

![img73](capturas/img73.png?raw=true)