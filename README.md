# Cardinity Payment Gateway for Magento 2
This module will enable Cardinity payments system in your Magento e-shop. If you are using older version of Magento refer to <a href="https://github.com/cardinity/cardinity-magento/tree/1.9.x">1.9 branch</a>.

### Table of Contents  
[<b>How to install? →</b>](#how-to-install)<br>
      [Using marketplace](#using-marketplace)   
      [Using app/code](#using-appcode)   
 [<b>Changelog →</b>](#changelog)<br>
 [<b>FAQ →</b>](#faq)<br>
 [<b>About us →</b>](#-aboutus)<br>     
<a name="headers"/>  

## How to install?

### Downloads
Find the latest Cardinity Payment Module for Magento 2 here: https://github.com/cardinity/cardinity-magento/releases
### Requirements
• Cardinity account  
• Magento Community Edition v2.0.0 or above  
• PHP ≥ 7.2  

 
<br>
-----
### Installation
Recommended to install via marketplace. You can click on each step for screenshot to appear with clearer instructions. 
#### Using marketplace
<details>
<summary>1. Go to Magento marketplace and search for "Cardinity payment gateway" or navigate directly to → https://marketplace.magento.com/cardinity-magento.html</summary>
 <img src="https://user-images.githubusercontent.com/76772655/105848170-45ea5000-5fe7-11eb-8d94-64450da5476c.png" width="600">
 </details>
 <details>
<summary>2. Select your store version and click "Add to cart".</summary>
 <img src="https://user-images.githubusercontent.com/76772655/105849360-f147d480-5fe8-11eb-9b71-7d26bd82c432.png" width="600"></details>
<details><summary>3. Proceed to checkout, fill in the billing form (do not worry its free) and obtain the extension via Magento Marketplace Platform by clicking ".</summary>
 <img src="https://user-images.githubusercontent.com/76772655/105849767-8054ec80-5fe9-11eb-8ccd-6ab94adcfd83.png" width="600"> <br> <img src="https://user-images.githubusercontent.com/76772655/105850356-4a643800-5fea-11eb-8db0-56dfb21ffe45.png" width="600"></details>
<details>
<summary>4. Once the order is complete, click Install.</summary>
 <img src="https://user-images.githubusercontent.com/76772655/105850558-8eefd380-5fea-11eb-8fbd-48e3c482ea79.png" width="600"></details>
<details>
<summary>5. Once you are redirected to "My Access Keys" page, copy private and public access keys.</summary>
 <img src="https://user-images.githubusercontent.com/76772655/105851009-29501700-5feb-11eb-958d-081b10120578.png" width="600"></details>
<details>
<summary>6. Next, login to your store admin panel. Go to "System" → "Web setup wizard", then choose "Component manager".</summary>
<img src="https://user-images.githubusercontent.com/76772655/105851839-4a653780-5fec-11eb-85a4-f89b917a42a2.png" width="600"></details>
<details>
<summary>7. Click on Sign in and paste Public access and Private access keys.</summary>
<img src="https://user-images.githubusercontent.com/76772655/105852370-0cb4de80-5fed-11eb-909a-5fd5948fb560.png" width="600"></details>
 <details>
<summary>8. After successfully putting in the keys, click "Sync". Then, click "Install" under "New purchases".</summary>
<img src="https://user-images.githubusercontent.com/76772655/105852901-ba27f200-5fed-11eb-9b86-06722d956ed8.png" width="600"></details>
 <details>
<summary>9. Among new purchases, find Cardinity payment module and click install. Wait while readiness check is finished. Click next. During step 2, create a backup if needed (highly recommended) and click next again. Finally, click install on "step 3: Component install".</summary>
<br>Step 1.<br><img src="https://user-images.githubusercontent.com/76772655/105853823-ca8c9c80-5fee-11eb-9991-1bcebea5e40e.png" width="600">
<br>Step 2.<br><img src="https://user-images.githubusercontent.com/76772655/105854356-79c97380-5fef-11eb-9e8c-a1167e305314.png" width="600">
<br>Step 3.<br><img src="https://user-images.githubusercontent.com/76772655/105854542-af6e5c80-5fef-11eb-91ec-be277f5147a9.png" width="600"></details>
 <details>
<summary>10. If everything is done correctly, you should be prompted that Cardinity extension has been installed.</summary>
<img src="https://user-images.githubusercontent.com/76772655/105855047-4dfabd80-5ff0-11eb-8570-1e0aeb7dd44c.png" width="600"></details>

After installation you can setup configurations in Store -> Configuration -> Payment Methods
#### Using app/code
Put this inside app/code/Cardinity/Payment in magento composer.json and composer update

add
```
"require": {
    "cardinity/cardinity-sdk-php": "~3.0",
    *** 
```

 
<br>
-----


### Changelog 
For Magento 2
| Date          | Changes                                             |Version     |
| ------------- |-----------------------------------------------------|------------|
| 2020.12.23    | bug fix, minor update related to refund issues.     | v2.0.1     |
| 2020.12.08    | • Updated cardinity sdk to version 3,<br>• 3D secured version 2 with fallback to version 1,<br>• External hosted payments                  | v2.0.0      |

For Magento 1 (1.7 - 1.9)
| Date          | Changes                                             |Version     |
| ------------- |-----------------------------------------------------|------------|
| 2020.12.09    | Added payment by external hosted gateway            |magento-1.9 |

 
<br>
-----

### FAQ
<details>
  <summary>Question1 →</summary>
  Answer1
  </details>
  <details>
  <summary>Question2 →</summary>
  Answer2
  </details>
  <details>
<summary>Question2 →</summary>
  Answer2
  </details>  
 
<br>
-----

### ► About us
Cardinity is a licensed payment institution, active in the European Union, registered on VISA Europe and MasterCard International associations to provide <b>e-commerce credit card processing services</b> for online merchants. We operate not only as a <u>payment gateway</u> but also as an <u>acquiring Bank</u>. With over 10 years of experience in providing reliable online payment services, we continue to grow and improve as a perfect payment service solution for your businesses. Cardinity is certified as PCI-DSS level 1 payment service provider and always assures a secure environment for transactions. We assure a safe and cost-effective, all-in-one online payment solution for e-commerce businesses and sole proprietorships.<br>
#### Our features
• Fast application and boarding procedure.   
• Global payments - accept payments in major currencies with credit and debit cards from customers all around the world.   
• Recurring billing for subscription or membership based sales.  
• One-click payments - let your customers purchase with a single click.   
• Mobile payments. Purchases made anywhere on any mobile device.   
• Payment gateway and free merchant account.   
• PCI DSS level 1 compliance and assured security with our enhanced protection measures.   
• Simple and transparent pricing model. Only pay per transaction and receive all the features for free.
### Get started
<a href="https://cardinity.com/sign-up">Click here</a> to sign-up and start accepting credit and debit card payments on your website or <a href="https://cardinity.com/company/contact-us">here</a> to contact us 
#### Keywords
payment gateway, credit card payment, online payment, credit card processing, online payment gateway, cardinity for X.     

  
 [▲ back to top](#Cardinity-Payment-Gateway-for-PrestaShop)
<!--
**fjundzer/fjundzer** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

