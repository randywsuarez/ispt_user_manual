# **RECEIVED - ISPT**

## Pre-Alerts

### FEDEX

1. Look for the pre-alert to be loaded in the email, we will have 4 files of which we should save the ones that start with BOL and PACKLIST. Example:

   ![Files ss](https://drive.google.com/uc?export=download&id=1o38HYChmpg5jM_Cn4JktwudxUsFSaa3Y)

2. Go to **menu -> SFIS Admin Applications -> Pre-Alerts** and click on it

   ![Menu](https://drive.google.com/uc?export=download&id=1uosC8g2fAPR2CeJNaHgEIZM99ik2buw9)

   We will see buttons similar to these, and we will follow the order in the following list:

   ![Pre-alert Menu](https://drive.google.com/uc?export=download&id=1Gieh7l6c9qU9uJ8El8BKmOXlXFya-pN5)

   1. **<span style="color:green; text-shadow: 1px 2px 2px black; font-weight: bold;">Import Bol File:</span>** This is where we will upload the file that starts with BOL.
   2. **<span style="color:blue; text-shadow: 1px 2px 2px black; font-weight: bold;">Import BOL Details File:</span>** Upload the file that starts with PACKLIST.
   3. **<span style="color:yellow; text-shadow: 1px 2px 2px black; font-weight: bold;">Generate Order:</span>** Processes the information in the system to move to the first station.

Here is an example of the complete process:

![Upload Pre-alert](<https://drive.google.com/uc?export=download&id=12tIyr65lejuDd-ElXAOilZHfvYTAUnvZ>)

### DIRECT BUY OR ISP-TX

#### Step-by-step to create the pre-alert

1. Review the email received regarding this pre-alert; if it does not include a serial number like the following image, we should request it from the administration:

   ![Pre-Alert](https://drive.google.com/uc?export=download&id=1pC9wQKxCFi_JkD8-PtcJLV5jNfbmaygQ)

2. The administration will send you a similar file, but this one includes the serial numbers of each item.

   ![Pre-alert with serial numbers](https://drive.google.com/uc?export=download&id=1PhkJjk58Fk61dyUrSZlag4feGK-Tb8Wa)

3. We proceed to create our pre-alert in the format required by the system. You can download the document from [here](https://drive.google.com/uc?export=download&id=1REM3FfUpX5WXRuRatYYMBGETFXZfLnup)

   [![File](https://drive.google.com/uc?export=download&id=1S3ErZS2mAbZbV_TgvRETqeK3YJGYBckV)](https://drive.google.com/uc?export=download&id=1REM3FfUpX5WXRuRatYYMBGETFXZfLnup)

   **Structure**

   ![Template](https://drive.google.com/uc?export=download&id=12xaqUUh32Mj8eJHQli6HIHyycA4BXSsM)

   - **BOL (B1):** Enter the value of the ***Customer PO*** from step 2. (Add it only once)

   - **SKU (A3):** It is the product number, model, or SKU. (It should be complete, e.g., 50V33UA#ABA)

   - **Description (B3):** It is the product description.

   -  **Pallet (B4):**  It is the pallet identifier. You can use the same ***Customer PO*** if it is a pallet that arrived or use the ***Item*** value as the pallet number if multiple pallets arrive since they can arrive on different days, values that we can see in step 2.

   - **SN and Label (D3 and D4):** Enter the same value as the article's serial number, and if it doesn't have one, use the FEDEX Label, which is the SLP.

   - **QTY (F3):** It is the quantity of the product. If each article has its serial, the value of this would be 1. But if it does not have a serial but has a Label and more than one article, enter the Label and the quantity of articles that arrived.

     > Repeat the process until all products are in the template.

     ![Structure](https://drive.google.com/uc?export=download&id=1CnF5Z5_H0qvOfCpV6HeMweMlDb_es2if)

     | ![Label for 1 article](https://drive.google.com/uc?export=download&id=1wZjlLYQTb-PPdodcdSVpkIydzt_GhnA0) | ![Label for more than 1 article](https://drive.google.com/uc?export=download&id=1FZOBk_h1uuo-PDpUEkkqJ71SEpQR61te) |
     | ------------------------------------------------------------ | ------------------------------------------------------------ |

     **Note:** (We must separate the products according to the projects)

4. A sample of how to populate the template:

   ![Template](https://drive.google.com/uc?export=download&id=1qdC5NpdSIffmUeMS0zkIio4PNjaWhu5R)