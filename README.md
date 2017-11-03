## Add Miscellaneous HTML and Scripts to Magento2 Checkout Success Page 


Add miscellaneous HTML and scripts quickly and easily to your Magento2 checkout success page. Also, ideal for testing new styling of your thank your page, adding new static blocks or other customization to your checkout page.

### Order Variables

- Order ID
- Total
- Sub Total
- Shipping Cost
- Tax
- Coupon Code
- Discount


#### 1 - Installation
##### Using Composer

```
composer require magepal/magento2-checkoutsuccessmiscscript
```

##### Manually
 * Download the extension
 * Unzip the file
 * Create a folder {Magento 2 root}/app/code/MagePal/CheckoutSuccessMiscScript
 * Copy the content from the unzip folder


#### 2 - Enable Reindex (from {Magento root} folder)
 * php -f bin/magento module:enable --clear-static-content MagePal_CheckoutSuccessMiscScript
 * php -f bin/magento setup:upgrade


![success page miscellaneous html and scripts](https://user-images.githubusercontent.com/1415141/32399662-4081c186-c0ce-11e7-9389-26db6ead8e4c.gif)



----

Need help setting up or want to customize this extension to meet your business needs? Please email support@magepal.com and if we like your idea we will add this feature for free or at a discounted rate.
