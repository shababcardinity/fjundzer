# Cardinity Payment Gateway for Magento 2
This module will enable Cardinity payments system in your Magento e-shop. If you are using older version of Magento refer to <a href="https://github.com/cardinity/cardinity-magento/tree/1.9.x">1.9 branch</a>.

### Table of Contents  
 [► How to install?](#-how-to-install)   
      [Downloads](#Downloads)   
      [Requirements](#requirements)   
      [Installation](#installation)   
      [Screenshots](#Screenshots)  
 [► Changelog](#-changelog)  
 [► FAQ](#-faq)
  
 [► About us](#-aboutus)   
     [Our features](#our-features)         
     [Get started](#get-started)   
 [Keywords](#keywords)   
<a name="headers"/>    
## ► How to install?

### Downloads
Find the latest Cardinity Payment Module for Magento 2 here: https://github.com/cardinity/cardinity-magento/releases
### Requirements
• Cardinity account  
• Magento Community Edition v2.0.0 or above  
• PHP ≥ 7.2  
### Installation
Recommended to install via marketplace. After install you can set configurations from Store -> Configuration -> Payment Methods
#### Using marketplace
<details>
<summary>1. Go to Magento marketplace and search for "Cardinity payment gateway" or navigate directly to → https://marketplace.magento.com/cardinity-magento.html</summary>
 <img src="https://user-images.githubusercontent.com/76772655/105848170-45ea5000-5fe7-11eb-8d94-64450da5476c.png" width="800">
 </details>
 <details>
<summary>2. Select your store version and add extension to cart.</summary>
 <img src="https://user-images.githubusercontent.com/76772655/105849360-f147d480-5fe8-11eb-9b71-7d26bd82c432.png" width="500">
<details>
<summary>3. Proceed to checkout, fill in the billing form (do not worry its free) and obtain the extension via Magento Marketplace Platform by clicking ".</summary>
 <img src="https://user-images.githubusercontent.com/76772655/105849767-8054ec80-5fe9-11eb-8ccd-6ab94adcfd83.png" width="500">
 <img src="https://user-images.githubusercontent.com/76772655/105850356-4a643800-5fea-11eb-8db0-56dfb21ffe45.png" width="500">
</details>
<details>
<summary>
4. Once the order is complete, click install extension.</summary>
 <img src="https://user-images.githubusercontent.com/76772655/105850558-8eefd380-5fea-11eb-8fbd-48e3c482ea79.png" width="500">
 </details>
<details>
<summary>5. Once you are redirected to "My Access Keys" page, copy private and public access keys.
 <img src="https://user-images.githubusercontent.com/76772655/105851009-29501700-5feb-11eb-958d-081b10120578.png" width="500"></details>
6. Login to your store admin panel.

#### Using app/code
Put this inside app/code/Cardinity/Payment

add
```
"require": {
    "cardinity/cardinity-sdk-php": "~3.0",
    *** 
```
    
in magento composer.json and composer update

### Screenshots


1. Magento keys page<br>
![Magento Keys page](https://raw.githubusercontent.com/cardinity/cardinity-magento/master/screen.png)
## ► Changelog 
For Magento 2
| Date          | Changes                                             |Version     |
| ------------- |-----------------------------------------------------|------------|
| 2020.12.23    | bug fix, minor update related to refund issues.     | v2.0.1     |
| 2020.12.08    | • Updated cardinity sdk to version 3,<br>• 3D secured version 2 with fallback to version 1,<br>• External hosted payments                  | v2.0.0      |

For Magento 1 (1.7 - 1.9)
| Date          | Changes                                             |Version     |
| ------------- |-----------------------------------------------------|------------|
| 2020.12.09    | Added payment by external hosted gateway            |magento-1.9 |
## ► FAQ
<details shown>
<summary>What do I do if integration fails?</summary>
     - Maybe, try again?
</details>
<details shown>
<summary>What do I do if I have a question?</summary>
     - Ask
</details>

<br>

## ► About us
Cardinity is a licensed payment institution, active in the European Union, registered on VISA Europe and MasterCard International associations to provide <b>e-commerce credit card processing services</b> for online merchants. 

We operate not only as a <u>payment gateway</u> but also as an <u>acquiring Bank</u>. With over 10 years of experience in providing reliable online payment services, we continue to grow and improve as a perfect payment service solution for your businesses.

Cardinity is certified as PCI-DSS level 1 payment service provider and always assures a secure environment for transactions.

We assure a safe and cost-effective, all-in-one online payment solution for e-commerce businesses and sole proprietorships.
### Our features
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
### Keywords
payment gateway, credit card payment, online payment, credit card processing, online payment gateway, cardinity for X.     

  
 [▲ back to top](#Cardinity-Payment-Gateway-for-PrestaShop)
<!--
**fjundzer/fjundzer** is a ✨ _special_ ✨ repository because its `README.md` (this file) appears on your GitHub profile.

