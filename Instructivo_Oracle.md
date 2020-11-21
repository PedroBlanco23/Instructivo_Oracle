# Instructivo Base Autónoma en Oracle 

[TOC]

### Objetivo del instructivo

- Crear una base de datos Oracle Always Free.
- Descargar SQL Developer.
- Conectarse a la base de datos Oracle con SQL Developer. 
- Importar datos a la base utilizando archivos (Excel, TXT, etc).
- Exportar datos desde la base utilizando archivos  (Excel, TXT, etc).



### Requisitos

- Correo electrónico,
- Información personal.
- Contar con una tarjeta de crédito no prepaga (Solo para que Oracle corrobore la identidad, no se realizará ningún cobro).
- Número telefónico.



### Información a tener en cuenta

Una cuenta free de Oracle Cloud proporciona lo siguientes servicios de por vida:

- 2 bases de datos en total, cada una con 1 CPU y 20GB de almacenamiento.
- 2 máquinas virtuales con 1/8 CPU y 1 GB de memoria c/u.
- 2 volúmenes de bloque ( 100gb en total).
- 10 GB de almacenamiento de objetos.
- 10 GB de almacenamiento de archivos.
- Además de $300 dólares de crédito por 1 mes para probar cualquier producto o servicio dentro de la nube.

![](capturas\AVISO.PNG)



## Sección 1: Crear cuenta de Oracle Always Free

Para crear nuestra cuenta dentro de Oracle, debemos dirigirnos al siguiente link:

https://www.oracle.com/ar/cloud/free/

![img1](capturas\img1.jpg?raw=true)

Ingresamos nuestra información personal.

![](capturas\img2.jpg?raw=true)

Luego, recibiremos un mail para validar el email.

<img src="\capturas\img3.png?raw=true"  />

Ingresando a través del link, continuaremos el registro.

En nombre de compañía, de forma opcional pueden poner el nombre de UADE.

 ![](capturas\img4.jpg?raw=true)

En región elegir **Latin America (Sao Paulo)**

![](capturas\img5.jpg?raw=true)

Nuevamente, completamos con información personal.

![](capturas\img6.jpg?raw=true)

Ingresamos nuestro número de teléfono.

![](capturas\img7.jpg?raw=true)

**Consejo:** Si no reciben el código SMS pueden contactarse con Oracle con el botón de ayuda. (necesitan hablar un poco de Inglés)

![](capturas\imagen sms.jpg?raw=true)

En category and product eligen las siguientes:

![](capturas\img8.jpg?raw=true)

![](capturas\img9.jpg?raw=true)

Luego de verificar el número de teléfono, debemos ingresar el método de pago.



 ![](capturas\img10.jpg?raw=true)

**AVISO: Puede que se reciba un cobro de 1 dólar pero se cancela AUTOMATICAMENTE es solo para corroborar la cuenta.**



Cuenta creada. Ahora debemos esperar a que se procese. (Puede tardar horas)

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

Colocamos un nombre (para mostrar) y para la base de datos(interno). Pueden ser el mismo.

![img18](capturas\img18.jpg?raw=true)

Elegimos tipo de base (preferentemente almacén de datos) y compartida para ser gratuita.

![img19](capturas\img19.jpg?raw=true)

Marcamos la casilla Siempre gratis.

![img20](capturas\img20.jpg?raw=true)

Una vez marcada,  se configurará para **Always Free**.

![img21](capturas\img21.jpg?raw=true)

Indicamos la contraseña para **ADMIN** (Con ella ingresaremos a la base de datos para conectarnos).

![img22](capturas\img22.jpg?raw=true)

Las configuraciones restantes podemos dejarlas por predeterminado. Clickeamos en **"Crear base de datos autónoma"**. 

![img23](capturas\img23.jpg?raw=true)



Esperamos a que la base termine de ser creada.

![img24](capturas\img24.jpg?raw=true)

## Sección 3: Descargar SQL Developer

