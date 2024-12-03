# **Magento 2 ANZ eGate Payment Gateway**

The **Magento 2 ANZ eGate Payment Gateway** extension integrates seamlessly with Magento stores, enabling secure and reliable payment processing via the ANZ eGate platform. This extension helps online merchants in Australia and New Zealand to accept credit card payments effortlessly, providing an enhanced payment experience for their customers. By integrating ANZ eGate, merchants can offer customers a secure, fast and efficient way to complete their transactions.

## **How It Works**

The **Magento 2 ANZ eGate Payment Gateway** extension works by facilitating secure payment transactions between customers and online merchants. Once a customer chooses to make a purchase, the extension ensures that the payment details are securely transmitted to ANZ eGate, which processes the payment and returns a response to the Magento store. The transaction is then completed, and the customer receives an instant confirmation.

This payment gateway is designed to be easy to install and configure within the Magento environment, allowing merchants to quickly integrate it into their stores without technical complications.

## **Key Features**

* The ANZ Direct API enables quicker payment processing.  
* Tokenization is used to securely transmit card details to ANZ.  
* Set minimum and maximum order totals to control when ANZ payment can be used in Magento 2\.

## **Secure and Encrypted Transactions**

With **ANZ eGate**, all transactions are encrypted using the latest security protocols to ensure that both merchants and customers are protected from fraud and data breaches. The extension supports secure payments, meeting PCI-DSS compliance requirements.

## **Easy Installation and Configuration**

Installing the **Magento 2 ANZ eGate Payment Gateway** extension is quick and easy. Once installed, merchants can configure it directly from the Magento admin panel, customizing settings such as payment options, currency, and transaction management preferences. The extension is optimized for both mobile and desktop devices, ensuring a seamless experience for customers. Additionally, it offers comprehensive transaction response management, providing detailed logs that allow merchants to easily track the status of payments, including successful transactions, failures and pending payments.

## **Multiple Payment Methods**

Support for credit and debit card payments, including Visa, MasterCard, and American Express, ensures a flexible checkout process for customers. This feature gives online store owners the ability to accept a wide range of payments from their customers.

## **Automated Refunds**

The extension provides a built-in option to automatically process refunds directly from the Magento admin panel. This reduces manual effort and ensures a smoother customer experience.

## **Extension Installation**

To install the **Magento 2 ANZ eGate Payment Gateway** extension:

### **Step 1:** 

Extract the ZIP folder and upload the extension to the root directory of your Magento 2 installation using FTP.

### **Step 2:**

### Login to your SSH and run below commands step by step:

* php bin/magento setup:upgrade  
* For Magento version 2.0.x to 2.1.x \- php bin/magento setup:static-content:deploy  
* For Magento version 2.2.x & above \- php bin/magento setup:static-content:deploy –f  
* php bin/magento cache:flush

## **How to Configure the Magento 2 ANZ eGate Payment Gateway Extension**

To set up and configure the **Magento 2 ANZ eGate Payment Gateway**, follow these steps:

### **Step 1: Configure Settings**

To configure the **Magento 2 ANZ eGate Payment Gateway** extension, log in to your Magento 2 admin panel and navigate to **Stores** \> **Configuration** \> **Sales** \> **Payment Methods** \> **ANZ eGate Payment Gateway (General Configuration)**. Here, you can customize various settings for the extension. For **ANZ Direct Payment**, you will need to provide an SSL-secured page on your website for buyers to enter their credit card and order details.

![anz _Configuration](https://github.com/user-attachments/assets/8d5916f2-996d-4d31-80f5-02fca9b9a6b4)

* **Enabled**: Enable or disable the ANZ Direct (Merchant Hosted) payment method.  
* **Debug**: Set to **YES** to enable debug mode for troubleshooting.  
* **Title**: Enter the title to display for the ANZ merchant hosted payment method on the frontend.  
* **Show ANZ Logo**: Set to **YES** to display the ANZ logo on the checkout page.  
* **Sandbox Mode**: Select **YES** to enable sandbox mode for testing purposes.  
* **Merchant Access Code**: Enter the merchant access code provided by ANZ during registration.  
* **Merchant ID**: Enter the merchant ID you received from the ANZ payment gateway.  
* **Secure Secret**: Enter the secure secret provided by ANZ.  
* **AMA User**: Enter the AMA user provided by ANZ.  
* **AMA Password**: Enter the AMA password provided by ANZ.

**Note**: For details on obtaining your **Merchant Access Code**, **Merchant ID**, **Secure Secret**, **AMA User**, and **AMA Password**, refer to [ANZ's Merchant Admin Quick Reference Guide](https://www.anz.com.au/content/dam/anzcomau/documents/pdf/egate-merchadmin-quickrefguide.pdf).

* **Payment Action**: Choose the payment action to capture payments (e.g., authorize or capture).  
* **New Order Status**: Set the order status for new orders placed using the ANZ payment method.  
* **Credit Card Types**: Select the credit card types that can be used with this payment method.  
* **Payment From Applicable Countries**: Choose the countries that can use the ANZ payment method.  
* **Instructions**: Add any instructions that should appear on the checkout page with the payment method.  
* **Minimum Order Total**: Set the minimum order total to allow payments via ANZ.  
* **Maximum Order Total**: Set the maximum order total to allow payments via ANZ.  
* **Sort Order**: Set the sort order for the payment method on the checkout page.

### **Step 2: Check ANZ Payment Method on the Frontend**

![Check ANZ Payment Method on the Frontend](https://github.com/user-attachments/assets/b88d4312-0157-40f4-ac43-096a8aca45e3)

After configuring the extension and enabling the direct payment method, customers will see it as an option on the checkout page. They can then enter their card details (use test card details from here) and click the "Place Order" button to complete their purchase successfully.

### **Step 3: Check ANZ Payment Details in the "My Account" Section**

![Check ANZ Payment Details in the](https://github.com/user-attachments/assets/a4d349c4-eecd-4073-8442-8c6a131b0b07)

After successfully placing an order, customers can view the payment details in the "My Account" section.

### **Step 4: Check ANZ Payment Details in the Backend**

![Check ANZ Payment Details in the Backend](https://github.com/user-attachments/assets/05fa079b-f0e6-4eef-b206-e5ab54789953)

In addition to customers, admins can view the payment details in the **Sales** \> **Orders** \> **Order View** section in the backend.

### **Step 5: Check ANZ Payment Method for Backend Orders**

![Check ANZ Payment Method for Backend Orders](https://github.com/user-attachments/assets/e494147b-1e85-4251-8dea-4062c1eae38c)

Similar to the frontend, the ANZ direct payment method can also be used for backend orders. Admins can create a new order, select the ANZ payment method, enter the card details and click "Submit Order" to process the payment and place the order from the backend.

## Download our [Magento 2 ANZ eGate Payment Gateway](https://meetanshi.com/magento-2-anz-egate-payment-gateway.html) Extension
