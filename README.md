# Reward Points Extension

![]((https://github.com/nishadjadhav/Reward_img/blob/master/configurations.png | width=100)

Magento 2 Reward Points module allows the admin to reward their customers with points. The admin can allocate reward points to the customers based on their purchases (product wise/category wise/cart amount wise) or activities (registration/product reviews) they perform in the web store. The customers can redeem their points at the checkout.


> Magento2 Reward Points helps to build an ultimate loyalty program which can grow your number of potential customers. The module not only rewards customers for their purchasing activities but also gives points for their behaviors like registration and reviewing products.

> Using this module, reward your customers with points to create an attachment or hold your potential customers.


### Installation
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

# Features!

  - The module can be enabled or disabled by the admin.
  - Following different set of rules managed by admin
    - Average order amount within defined days
    - Frequency of ordering (Order count within defined days)
    - Minimum total sum or amount of items
    - Customer places order
    - Customer signs up
    - Customer purchases particular product
    - Customer refers a friend
    - Customer adds tag to a product
    - Customer writes a product review
    - Customer has a birthday
    - Customer is inactive for long time
    - Newsletter subscription
    - Sharing on Facebook
    - Likes in Facebook
    - Tweeting in Twitter
 



