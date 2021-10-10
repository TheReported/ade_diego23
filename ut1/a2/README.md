# **U1_A2.- Instalación de MySQL Server en Ubuntu Server 20.04 LTS**

## **1. Instalación y configuración de Ubuntu Server 20.04 LTS**

![](img/001.png)

![](img/002.png)

![](img/003.png)

![](img/004.png)

![](img/005.png)

![](img/006.png)

![](img/018.png)

![](img/019.png)

![](img/009.png)

![](img/010.png)

![](img/011.png)

![](img/012.png)

![](img/021.png)

![](img/014.png)

![](img/015.png)

#### **1.1 Instalaremos un escritorio**

![](img/022.png)

![](img/023.png)

## **2. Instalamos MySQL Server**

![](img/024.png)

## **3. Comprobamos la versión de MySQL**

![](img/025.png)

## **4. Pararemos el demonio desde el init.d, comprobaremos de que el proceso este parado. Y lo reiniciamos**

![](img/053.png)

![](img/026.png)


## **5. Ejecutamos la siguiente consulta**

![](img/029.png)

![](img/054.png)

- Comprobamos que cuando entramos con ``mysql -u root -p`` ya no se autentifica usando el plugin ``auth_socket`` , sino ``mysql_native_password``, esto significa que el usuario root de MySQL se autentifica usando una contraseña.

## **6. Entraremos en la BD MySQL y modificaremos la tabla**

![](img/030.png)

![](img/031.png)

## **7. Instalamos MySQL Workbench y probaremos la conexión local con el servidor MySQL**

![](img/032.png)

![](img/033.png)

![](img/034.png)

![](img/035.png)

![](img/036.png)

![](img/037.png)

![](img/040.png)

![](img/039.png)

## **8. Instalamos Adminer sobre Apache y probaremos la conexión. Además instalaremos el PHPmyAdmin y comprobamos la conexión.**

![](img/041.png)

![](img/042.png)

![](img/044.png)

![](img/045.png)

![](img/046.png)

![](img/047.png)

![](img/051.png)

![](img/049.png)

![](img/050.png)

![](img/052.png)

## **9. Explicaciones finales.**

- **Directorio de instalación base**:

![](img/055.png)

- Ejecutamos el siguiente comando ``sudo mysqladmin -u root -p shutdown``.

![](img/056.png)

- Lo que sucede es que se apaga el servicio.

- **Directorio del servicio o proceso demonio, directorio alestar de MySQL.**

![](img/057.png)

- **Directorio de datos**

![](img/058.png)

- En este directorio se encuentran todos los datos, registros, estructura de tablas y bases de datos.

- **Fichero de configuración**

![](img/059.png)

- **Propietario de las bases de datos**

![](img/060.png)
