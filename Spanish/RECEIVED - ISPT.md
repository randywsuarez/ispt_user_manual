# **RECEIVED - ISPT**

## Pre-Alerts

### FEDEX

1. Buscar en el email la pre-alerta a cargar, tendremos 4 archivos de los cuales debemos de guardar los que comiencen con BOL. y PACKLIST. Ejemplo:

   ![Files ss](https://drive.google.com/uc?export=download&id=1o38HYChmpg5jM_Cn4JktwudxUsFSaa3Y)

2. Ir al **menu -> SFIS Admin Applications -> Pre-Alerts** y le damos click

   ![Menu](https://drive.google.com/uc?export=download&id=1uosC8g2fAPR2CeJNaHgEIZM99ik2buw9)

   Vamos a ver unos botones similar a estos y seguiremos el orden la lista siguiente:

   ![Menu de Pre-alert](https://drive.google.com/uc?export=download&id=1Gieh7l6c9qU9uJ8El8BKmOXlXFya-pN5)

   1. **<span style="color:green; text-shadow: 1px 2px 2px black;font-weight: bold;">Import Bol File:</span>** Es donde vamos a subir el archivo que comienza por BOL. 
   2. **<span style="color:blue; text-shadow: 1px 2px 2px black;font-weight: bold;">Import BOL Details File:</span>** Subir el archivo que comienza por PACKLIST.
   3. **<span style="color:yellow; text-shadow: 1px 2px 2px black; font-weight: bold;">Generate Order:</span>** Procesa la información en el sistema para avanzar a la primera estación.

A continuación tenemos un ejemplo del proceso completo:

![Upload Pre-alert](<https://drive.google.com/uc?export=download&id=12tIyr65lejuDd-ElXAOilZHfvYTAUnvZ>)

### DIRECT BUY OR ISP-TX

#### Paso a paso para crear la pre-alerta

1. Revisar el correo recibido sobre esta pre-alerta si esta no tiene serial incluido como la siguiente imagen debamos de solicitarla a la administración:

   ![Pre-Alert](https://drive.google.com/uc?export=download&id=1pC9wQKxCFi_JkD8-PtcJLV5jNfbmaygQ)

2. La administración le enviara un archivo parecido pero este incluye los números de series de cada articulo.

   ![Pre-alert con series](https://drive.google.com/uc?export=download&id=1PhkJjk58Fk61dyUrSZlag4feGK-Tb8Wa)

3. Procedemos a crear nuestra pre-alerta a la estructura que necesita el sistema. Podemos bajar el documento de [aquí](https://docs.google.com/spreadsheets/d/1REM3FfUpX5WXRuRatYYMBGETFXZfLnup/edit?usp=drive_link&ouid=115837206541748972044&rtpof=true&sd=true)

   [![File](https://drive.google.com/uc?export=download&id=1S3ErZS2mAbZbV_TgvRETqeK3YJGYBckV)](https://docs.google.com/spreadsheets/d/1REM3FfUpX5WXRuRatYYMBGETFXZfLnup/edit?usp=drive_link&ouid=115837206541748972044&rtpof=true&sd=true)

   **Estructura**

   ![Template](https://drive.google.com/uc?export=download&id=12xaqUUh32Mj8eJHQli6HIHyycA4BXSsM)

   - **BOL (B1):** Colocaremos el valor ***Customer PO*** del paso 2. (Se agrega una única vez)

   - **SKU (A3):** Es el numero del producto, modelo o SKU. (Debe de ir completo Ej. 50V33UA#ABA)

   - **Description (B3):** Es la descripción del producto.

   -  **Pallet (B4):**  Es el identificador de la paleta se puede usar el mismo ***Customer PO*** si es una paleta la que llego o usar el valor de ***Item*** como numero de pallet si estos llegan mas de una paleta ya que puede llegar en diferentes días valores que podemos ver en el paso 2. 

   - **SN y Label (D3 y D4):** Colocaremos el mismo valor del serie del articulo y si este no trae usaremos el Label de FEDEX que es el SLP.

   - **QTY (F3):** Es la cantidad del producto. Si cada articulo tiene su seria el valor de este seria 1 pero si este no tiene Serial sino Label y mas de un articulo colocamos el label y x cantidad de articulo que llego.

     | ![Label 1 articulo](https://drive.google.com/uc?export=download&id=1wZjlLYQTb-PPdodcdSVpkIydzt_GhnA0) | ![Label mas de un articulo](https://drive.google.com/uc?export=download&id=1FZOBk_h1uuo-PDpUEkkqJ71SEpQR61te) |
     | ------------------------------------------------------------ | ------------------------------------------------------------ |

     **Observación:** (Debemos de separar los productos de acuerdo a los proyectos)

4. Una muestra de como se alimenta la plantilla:

   ![Plantilla](https://drive.google.com/uc?export=download&id=1qdC5NpdSIffmUeMS0zkIio4PNjaWhu5R)

   

   
