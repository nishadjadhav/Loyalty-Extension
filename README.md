# Reward Points Extension

![alt text](http://www.cardexpert.in/wp-content/uploads/2015/07/credit_card_reward_points-cashback.png)

Magento 2 Reward Points module allows the admin to reward their customers with points. The admin can allocate reward points to the customers based on their purchases (product wise/category wise/cart amount wise) or activities (registration/product reviews) they perform in the web store. The customers can redeem their points at the checkout.

 

# Features!

  - The module can be enabled or disabled by the admin.
  - different set of rules managed by admin 
 
Magento2 Reward Points helps to build an ultimate loyalty program which can grow your number of potential customers. The module not only rewards customers for their purchasing activities but also gives points for their behaviors like registration and reviewing products.

Using this module, reward your customers with points to create an attachment or hold your potential customers.Markdown is a lightweight markup language based on the formatting conventions that people naturally use in email.  As [John Gruber] writes on the [Markdown site][df1]

> Magento2 Reward Points helps to build an ultimate loyalty program which can grow your number of potential customers. The module not only rewards customers for their purchasing activities but also gives points for their behaviors like registration and reviewing products.

Using this module, reward your customers with points to create an attachment or hold your potential customers.The overriding design goal for Markdown's
> formatting syntax is to make it as readable
> as possible. The idea is that a
> Markdown-formatted document should be
> publishable as-is, as plain text, without
> looking like it's been marked up with tags
> or formatting instructions.

Magento2 Reward Points helps to build an ultimate loyalty program which can grow your number of potential customers. The module not only rewards customers for their purchasing activities but also gives points for their behaviors like registration and reviewing products.

Using this module, reward your customers with points to create an attachment or hold your potential customers.This text you see here is *actually* written in Markdown! To get a feel for Markdown's syntax, type some text into the left window and watch the results in the right.


### Installation

Dillinger requires [Node.js](https://nodejs.org/) v4+ to run.

Install the dependencies and devDependencies and start the server.

```sh
$ cd dillinger
$ npm install -d
$ node app
```

For production environments...

```sh
$ npm install --production
$ NODE_ENV=production node app
```

### Plugins

Dillinger is currently extended with the following plugins. Instructions on how to use them in your own application are linked below.

| Plugin | README |
| ------ | ------ |
| Dropbox | [plugins/dropbox/README.md][PlDb] |
| Github | [plugins/github/README.md][PlGh] |
| Google Drive | [plugins/googledrive/README.md][PlGd] |
| OneDrive | [plugins/onedrive/README.md][PlOd] |
| Medium | [plugins/medium/README.md][PlMe] |
| Google Analytics | [plugins/googleanalytics/README.md][PlGa] |


### Development

Want to contribute? Great!

Dillinger uses Gulp + Webpack for fast developing.
Make a change in your file and instantanously see your updates!

Open your favorite Terminal and run these commands.

First Tab:
```sh
$ node app
```

Second Tab:
```sh
$ gulp watch
```

(optional) Third:
```sh
$ karma test
```
#### Building for source
For production release:
```sh
$ gulp build --prod
```
Generating pre-built zip archives for distribution:
```sh
$ gulp build dist --prod
```
