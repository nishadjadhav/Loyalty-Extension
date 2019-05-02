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
  </br>
    <img src="https://github.com/nishadjadhav/Reward_img/blob/master/configurations.png" height="350" width="700">
 
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
    </br>
    <img src="https://github.com/nishadjadhav/Reward_img/blob/master/admin_rule.png" height="350" width="700">

  - #### Manage Customer Transactions in admin panel
     There is transaction history of every customer. admin see the number of points in customer account in the Rewards tab. admin can be able to manually add or deduct the points from customer’s balance
    </br>
    <img src="https://github.com/nishadjadhav/Reward_img/blob/master/admin_cust_history.png" height="350" width="700">

- #### Manage Customer Refferals in admin panel
     The admin see the details of referrral of a customers
     
 - #### Show Loyalty program information on customer account
      Customers shall gain full access to loyalty program via their account in store. They can see their current balance, transaction history.customers will easily understand how loyalty program works.
    </br>
    <img src="https://github.com/nishadjadhav/Reward_img/blob/master/customer_pt.png" height="350" width="700">
    </br>
    <img src="https://github.com/nishadjadhav/Reward_img/blob/master/history.png" height="350" width="700">
    </br>
    
 - #### Customers get notifications based on conditions rules and also earn the points
   ##### 1) For Customer registration
      Customers to earn reward points for registration activity. This feature will attract new customers for the admin.
      <img src="https://github.com/nishadjadhav/Reward_img/blob/master/registration.png" height="350" width="700">
       </br>
       
   ##### 2) For Product Review
      Customers to earn reward points for submitting the product review. These product reviews increase the product sales for the sellers
      </br>
      <img src="https://github.com/nishadjadhav/Reward_img/blob/master/product.png" height="350" width="700">
      
   ##### 3) Based On Specific Product
      The customers can earn the reward points on the basis of the specific product they carry in their cart while checkout.

   ##### 4) Based On Customers for Social Media Activities
      Customers can earn points by sharing your product and category pages in the social media. You have a complete control over this process. Currently, extension allows rewarding the points for the following activities:
      - Sharing on Facebook
      - Tweets on Twitter
      - Likes in Google+
      </br>
      <img src="https://github.com/nishadjadhav/Reward_img/blob/master/share.png" height="350" width="700">
      
   ##### 5) For Inviting Friends
      Customers can invite their friend and family members through their account in your store. They can also send them an invitation link. Extension will link new visitors to the customer who referred them and earned reward points.
      </br>
      <img src="https://github.com/nishadjadhav/Reward_img/blob/master/customer_refer.png" height="350" width="700">
      
   ##### 6) For Inviting Friends based on order subselection
      Generate discounts based on customer order amounts to reward shoppers for making purchases in your store. Retain existing clients and attract new ones by creating tempting offers for those who purchase more.
      Order subselection includes:
      ###### i) Average order value
      ###### ii) Total sales amount
      ###### iii) Number of placed orders
