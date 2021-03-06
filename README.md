## Taxonomies and WooCommerce

<br />

WooCommerce adds a product post_type attribute to the wp_posts database table. In wordpress-speak a new taxonomy. A taxonomy needs to be supported by a theme. Before we activate the WooCommerce plugin we need to activate a theme that knows about the product taxonomy.

![WooCommerce friendly theme](https://rhildred.github.io/UX320-database-child-theme/READMEImages/economicsTheme.png "WooCommerce friendly theme")

Once we activate the theme we can also activate WooCommerce. WooCommerce takes you through a setup wizard:

![Setup Wizard](https://rhildred.github.io/UX320-database-child-theme/READMEImages/WooCommerceScreen1.png "Setup Wizard")

Woo Commerce installs some pages for shopping cart ...

![Setup Pages](https://rhildred.github.io/UX320-database-child-theme/READMEImages/WooCommercePageSetup.png "Setup Pages")

Then Woo Commerce sets your locale:

![Setup Locale](https://rhildred.github.io/UX320-database-child-theme/READMEImages/StoreLocale.png "Setup Locale")

Then shipping and tax:

![Setup Shipping and Tax](https://rhildred.github.io/UX320-database-child-theme/READMEImages/ShippingAndTaxSetup.png "Setup Shipping and Tax")

## Payments

Woo Commerce integrates directly with PayPal and Beanstream for payments. Both Beanstream and PayPal offer a sandbox to set up your store. We will be using Paypal's sandbox <a href="https://sandbox.paypal.com" target="_blank">sandbox.paypal.com.</a> You can set up sandbox buyer and seller accounts at <a href="https://developer.paypal.com" target="_blank">developer.paypal.com.</a> You will want to use a seller account in Woo Commerce:

![Sandbox Seller Account](https://rhildred.github.io/UX320-database-child-theme/READMEImages/PayPalSandboxAccounts.png "Sandbox Seller Account")

Put a seller account in the Woo Commerce `payments` screen:

![Payments](https://rhildred.github.io/UX320-database-child-theme/READMEImages/Payments.png "Payments")

At the end you will be faced with this screen:

![Ready](https://rhildred.github.io/UX320-database-child-theme/READMEImages/StoreIsReady.png "Ready")

There is one other step to make your store use the paypal sandbox. In the Woo Commerce settings screen you will need to `enable paypal sandbox.` I also turned on logging.

![enable paypal sandbox](https://rhildred.github.io/UX320-database-child-theme/READMEImages/otherPaypalOptions.png "enable paypal sandbox")

## Make a product

Add a product by going to WooCommerce/Add Product. Don't forget to set a price and a featured image.

![add a product](https://rhildred.github.io/UX320-database-child-theme/READMEImages/AddProduct.png "add a product")

Now you should be able to test all of the features of Woo Commerce and the Paypal Sandbox.



