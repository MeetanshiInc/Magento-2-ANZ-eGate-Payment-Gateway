# Magento 2 ANZ eGate Payment Gateway

Integrate ANZ payment gateway, the largest bank in Australia and New Zealand, with Magento 2, the most popular E-commerce platform, with Meetanshi's ***[Magento 2 ANZ eGate Payment Gateway](https://meetanshi.com/magento-2-anz-egate-payment-gateway.html)*** 

Security, which is of foremost importance in the online store, is taken care of, in the module. Avoid any hacks or theft in Magento 2 store with the Magento 2 ANZ extension.

Magento 2 ANZ eGate Payment Gateway offers a hosted payment process. It saves admin to process important credit card details in the Magento 2 environment. Accept customers' payments via Visa, Mastercard, American Express and Diners Club.

All you need to do is, register with a merchant account with ANZ bank. Connect the merchant account with Magento 2 store using the API key or PSIID, provided during the registration.

## How does Magento 2 ANZ eGate Payment Gateway work?:
* ANZ hosted payment page: Customers are directed to the ANZ hosted page to enter their card information and the transactions are managed   by ANZ.
* ANZ API: The customer’s card information is collected on their web browser and sent to the merchant’s server before sending it back to   ANZ.

##  Benefits of Magento 2 ANZ eGate Payment Gateway extension:

* Offers hosted payment gateway for security against thefts.

* The API uses encrypted data on the website.

* Direct and quick refund option.

* Supports Visa, Mastercard, American Express and Diners Club.

* Easy to use module.

* Easily manage the payment, refund, and cancellation process.

For more information, visit [https://meetanshi.com/magento-2-anz-egate-payment-gateway.html](https://meetanshi.com/magento-2-anz-egate-payment-gateway.html)

### Magento 2 ANZ eGate Payment Gateway Extension

---

#### Installation

**For Magento Marketplace Customers**  
1. Locate the Composer name and version in the `composer.json` file.
2. Run the following commands in SSH:
   ```bash
   composer require meetanshi/magento-2-anz-egate-payment-gateway --ignore-platform-reqs
   php bin/magento module:status Meetanshi_Anz
   php bin/magento module:enable Meetanshi_Anz --clear-static-content
   php bin/magento setup:upgrade
   php bin/magento cache:flush
   ```

**For Meetanshi Customers**  
1. Upload the extracted zip file to the root of your Magento 2 directory via FTP.
2. Run the following commands:
   ```bash
   php bin/magento setup:upgrade
   php bin/magento cache:flush
   ```

---

#### Configuration
1. Navigate to:  
   `Stores → Configuration → Sales → Payment Methods → ANZ eGate Payment Gateway`.
2. Configure settings like:  
   - **Enable/Disable**  
   - **Sandbox Mode**  
   - **Merchant Access Code**, **Merchant ID**, etc.  
   
For full configuration, refer to the [ANZ Merchant Admin Guide](https://www.anz.com.au/content/dam/anzcomau/documents/pdf/egate-merchadmin-quickrefguide.pdf).

---

#### Features
- **Frontend**: Customers can pay via ANZ by entering their card details during checkout.
- **Backend**: Admin can view and process orders using the ANZ payment method.

---



