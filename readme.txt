=== ReadyToShip WooCommerce Tracking Integration ===
Contributors: bslinger
Donate Link: http://www.readytoship.com.au
Tags: shipping, woocommerce, ecommerce, e-commerce, store, sales, tracking, readytoship
Requires at least: 4.1
Tested up to: 4.6
Stable tag: 0.3
License: GPLv3
License URI: http://www.gnu.org/licenses/gpl-3.0.html

Provides additional API methods for WooCommerce to allow ReadyToShip to send and receive tracking numbers to WooCommerce orders.

== Description ==

Provides additional API methods for WooCommerce to allow ReadyToShip to send and receive tracking numbers to WooCommerce orders.

The following API endpoints are created:
GET /orders/<order_id>/tracking
POST /orders/<order_id>/tracking

This plugin currently supports the following WooCommerce tracking plugins:
 - Shipment Tracking by WooThemes ( https://www.woothemes.com/products/shipment-tracking/ )

About ReadyToShip:

URL: http://www.readytoship.com.au

ReadyToShip is a simple, powerful and affordable tool that automates the manual parts in your shipping process, saving you hours every day. For small and large online sellers alike, we seamlessly connect your store with your shipping carriers. Automatically fixing customer addresses, generating labels, invoices and picklists, and updating your customers with tracking numbers becomes a breeze.

We know you'll love using ReadyToShip. That's why we back our product with a 3 month Free Trial so you can really experience all of the benefits.

== Installation ==

= Minimum Requirements =
* WooCommerce 2.2 or greater
* WooCommerce Shipment Tracking 1.4.2 or greater

1. Upload the plugin files to the `/wp-content/plugins/readytoship-wootracking-api` directory, or install the plugin through the WordPress plugins screen directly.
2. Activate the plugin through the 'Plugins' screen in WordPress

== Frequently Asked Questions ==

= What tracking plugins does ReadyToShip WooCommerce Tracking Integration support =

 - Shipment Tracking by WooThemes ( https://www.woothemes.com/products/shipment-tracking/ )

== Screenshots ==

1. Tracking data inserted via ReadyToShip

== Changelog ==

= 0.3 =
* Changed the dependency checking to account for the new name of Shipment Tracking module in 1.6.0

= 0.2 =
* Added delete endpoint for tracking numbers
* Improved dependency checking

= 0.1 =
* First version with Shipment Tracking by WooThemes support

== Upgrade Notice ==

= 0.2 =
* Added delete endpoint for tracking numbers
* Improved dependency checking

= 0.1 =
* First version