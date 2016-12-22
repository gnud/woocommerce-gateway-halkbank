=== WooCommerce Showroom Gateway ===

 - Contributors: skyverge, beka.rice, mattrad
 - Tags: woocommerce, payment gateway, gateway, manual payment
 - Requires at least: 3.8
 - Tested up to: 4.7
 - Requires WooCommerce at least: 2.1
 - Tested WooCommerce up to: 2.4
 - Stable Tag: 1.1.0
 - License: GPLv3
 - License URI: http://www.gnu.org/licenses/gpl-3.0.html

== Description ==

> **Requires: WooCommerce 2.1+**

This plugin clones the WooCommerce Cheque gateway to create another offline payment method, intended for card payment via the Showroom. When an order is submitted via the Showroom payment method, the order will be placed "on-hold".

Forked from the SkyVerge plugin.

= More Details =
 - See the [product page](http://www.skyverge.com/product/woocommerce-offline-gateway/) for full details and documentation
 - View more of SkyVerge's [free WooCommerce extensions](http://profiles.wordpress.org/skyverge/)
 - View all [SkyVerge WooCommerce extensions](http://www.skyverge.com/shop/)

== Installation ==

1. Be sure you're running WooCommerce 2.1+ in your shop.
2. You can: (1) upload the entire `woocommerce-gateway-showroom` folder to the `/wp-content/plugins/` directory, (2) upload the .zip file with the plugin under **Plugins &gt; Add New &gt; Upload**
3. Activate the plugin through the **Plugins** menu in WordPress
4. Go to **WooCommerce &gt; Settings &gt; Checkout** and select "Offline" to configure

== Frequently Asked Questions ==

**What is the text domain for translations?**
The text domain is `wc-gateway-showroom`.

**Can I fork this?**
Please do! This is meant to be a simple starter offline gateway, and can be modified easily.

== Changelog ==

= 2016.12.22 - version 1.1.0 =
 * Sample Offline Gateway changed to Showroom Gateway

= 2015.07.27 - version 1.0.1 =
 * Misc: WooCommerce 2.4 Compatibility

= 2015.05.04 - version 1.0.0 =
 * Initial Release