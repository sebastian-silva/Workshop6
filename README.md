# Workshop6

### Sensor ###
* Se utiliza el sensor BME280
![image](https://user-images.githubusercontent.com/85096310/166853001-33dcfa83-e75a-40b3-a2d6-c4211eb1f6fe.png)

### Embedded System ###
* Hardware: Se utilizo la raspberry PI 3 model B v1.2
![image](https://user-images.githubusercontent.com/85096310/166853050-8c57b041-836c-432e-aa28-53cfe3a51ea7.png)
* Software Se desarrollo la solucion por medio de NODE.JS, que se implementa en el sistema de la raspberry.

### Connectivity ###
* Se hizo todo a traves del cloud computing, por medio del servicio de Azure.
![image](https://user-images.githubusercontent.com/85096310/166851968-5524a97d-97c5-4a8d-a47e-586f1a8ffef3.png)


### Data Analytic ###
* Se uso la plataforma de azure IOT para desarrollar esto.
![image](https://user-images.githubusercontent.com/85096310/166851990-b728abfe-0e58-4063-bb64-f4975a857cc4.png)


## Pasos para desarrollarlo: ##
* 1. Se creo un recurso del tipo Centro de IOT en azure
![image](https://user-images.githubusercontent.com/85096310/166852278-fdb4fa5e-a9a4-4091-a205-084d031a4ca0.png)
* 2. Luego elegimos las opciones que nos ofrece Azure para configurar el paquete, ademas creamos un grupo de recursos para el:
*   - Nombre: Workshop 6
*   - Region: East US 
*   - Conectividad: publico
*   - Precios y escala: S1 
* 3. Al crearlo veremos esta pantalla
![image](https://user-images.githubusercontent.com/85096310/166852592-d26a53bf-80f0-4844-9fcf-b9209ee97c88.png)
* 4. Ahora nos dirigimos a dispositivos y creamos uno
![image](https://user-images.githubusercontent.com/85096310/166852673-c4b67aa1-9a14-4e89-be9a-b460ad46f43b.png)
* 5. Luego de agregarlo vemos el dispositivo y lo abrimos
![image](https://user-images.githubusercontent.com/85096310/166852756-6744afe3-5284-4537-8962-8331ccefe221.png)
* 6. Ahora solamente copiamos la llave y la ponemos en el codigo de nuestra raspberry, en este caso en la simulacion
![image](https://user-images.githubusercontent.com/85096310/166852851-37fd261c-9d97-486c-832c-1e6b28f4a2e2.png)
![image](https://user-images.githubusercontent.com/85096310/166852873-268972cb-1178-468f-a4d6-f32d51816550.png)}
* 7. Luego de ingresar la llave veremos el dispositivo en pantalla funcionando, al mostrarnos la temperatura
![image](https://user-images.githubusercontent.com/85096310/166852947-0d7e67df-5659-4f93-b152-346de15da913.png)
 


