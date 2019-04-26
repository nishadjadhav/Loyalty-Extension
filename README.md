# Reward Points Extension
![alt text](http://www.cardexpert.in/wp-content/uploads/2015/07/credit_card_reward_points-cashback.png)

Magento 2 Reward Points module allows the admin to reward their customers with points. The admin can allocate reward points to the customers based on their purchases (product wise/category wise/cart amount wise) or activities (registration/product reviews) they perform in the web store. The customers can redeem their points at the checkout.


> Magento2 Reward Points helps to build an ultimate loyalty program which can grow your number of potential customers. The module not only rewards customers for their purchasing activities but also gives points for their behaviors like registration and reviewing products.

> Using this module, reward your customers with points to create an attachment or hold your potential customers.


## Installation
#### Step 1: Upload the extension

1) Unzip extension package and upload them into Magento root directory
2) Enter the following at the command line

```sh
$ php bin/magento cache:flush
$ php bin/magento cache:clean
$ php bin/magento setup:upgrade
$ php bin/magento setup:di:compile
$ php bin/magento setup:static-content:deploy

```
#### Step 2: Configuration

 - Admin can enable or disable module on following path
 
 - Stores >> Configurations >> Reward Points Extensions

## Features!

- #### Module Configuration

  The Admin can configure the magento 2 Reward Points module 
  * Enable/disable the module.
  * Set the value of one reward points(Discount value %).
  * Set the maximum limit of the reward points that the customer can get.
  * Set the expiration peroid of points (day)
  * Store the Facebook App Id (Usefull for Facebook Share)
  
   <img src="https://github.com/nishadjadhav/Reward_img/blob/master/configurations.png" height="300" width="650">
 
 - #### Manage Earning Rules/Notification Rules in admin panel
   Manage the terms and conditions of your loyalty program. You establish the rules to calculate an amount of earned or used points in store.
   Different set of rules managed by admin
    * Average order amount within defined days
    * Frequency of ordering (Order count within defined days)
    * Minimum total sum or amount of items
    * Customer places order
    * Customer signs up
    * Customer purchases particular product
    * Customer refers a friend
    * Customer adds tag to a product
    * Customer writes a product review
    * Customer has a birthday
    * Customer is inactive for long time
    * Newsletter subscription
    * Sharing on Facebook
    * Likes in Facebook
    * Tweeting in Twitter

   <img src="https://github.com/nishadjadhav/Reward_img/blob/master/admin_rule.png" height="300" width="650">

  - #### Manage Customer Transactions in admin panel
     There is transaction history of every customer. admin see the number of points in customer account and a current tier in the Rewards tab. admin can be able to manually add or deduct the points from customer’s balance
     
 - #### Manage Customer Refferals in admin panel
     The admin see the details of referrral of a customers
     
 - #### Show Loyalty program information on customer account
 
   <img src="https://github.com/nishadjadhav/Reward_img/blob/master/customer_pt.png" height="300" width="650">
 

     
     
