WSB Brands is a complete Brands management solution for WooCommerce. If term "Manufacturer" is more suitable for you, you can easily change all the labels using "Brand / Manufacturer" switch in plugin settings. You can create unlimited number of brands, assign them to the products and show on desired positions. You can also enable a "Brand info" tab on product details page. 
Using shortcode, you can create "Shop by brand" page with brands in responsive grid.
Widgets included: Brands menu and Brands Carousel slider with many configuration options.
Since version 1.0.5 you can limit WooCommerce coupon usage to brand(s) and combine it with other filters. For example, you can set perecentage or fixed discount for all LG products or SONY products from TVs category.


[Live Demo](http://demo.webstudiobrana.com/)
[Detailed documentation](https://www.webstudiobrana.com/wsb-brands-plugin-for-woocommerce/)

### Requirements ###

- PHP version 5.6 and above
- Wordpress version 4.7 and above
- Woocommerce plugin installed and enabled (v 3.3 and above)

### Features ###

* WooCommerce Coupon restriction per brands
* Unlimited number of brands
* Name, slug, description, website url and logo
* Choose the term to use on the website (Brand or Manufacturer)
* Woocommerce product export and import supported
* Filtering products by brands in administration panel
* Brands carousel (slider) widget
* Brands menu (list) widget 
* Shortcode with additional options for responsive brands grid ( 1-6 columns)
* Brand can be shown on category page and single product page
* “Brand info” tab on product details page, can be turned off /on
* Show or hide label “Brand:” on product and category pages
* Display brand name or logo on product page
* Display brand in a shopping cart
* Choose one of several predefined positions for display brand on product and category pages
* Set max logo height in pixels
* Ready for translations (Croatian and English languages included)


### Shortcode ###

Shortcode with all default values: [brands_page grid="4" logo_height="40" show="both" hide_empty="no" count="yes"]
If you are happy with default values, you can use just [brands_page] instead. Also you can use only 
those parameters that you want to change, for example: [brands_page logo_height="50" grid="3"]

Parameters and possible values:
- grid: 1-6 (number of columns)
- logo_height: any numeric value for height in pixels
- show: name, logo, both
- hide_empty: yes, no (show or hide brands which are not assigned to any product)
- count: yes, no (Show number of products next to brand name)

### Menu Widget ###

Shows list of brand names as menu. 
Links point to the brand archive pages.
Options: 
* Show/Hide empty Brands
* Show/Hide products count

### Carousel Widget ###

Shows selected brands in a carousel slider. 
Options: 
* Show or hide selected brands
* Set speed of slides
* Set number of slides
* Sorting brands, logo height, navigation arrows and many other options

### Automatic installation ###

With automatic installation WordPress handles the file transfers so it is the easiest option and you can do it from your 
WordPress dashboard. Just navigate to the Plugins menu and click Add New. In the search field type "WSB Brands" to find 
the plugin. When it appears in a search results, use "Install now" button. When it is installed, activate it and plugin
is ready to use.

### Manual installation ###

1. Using FTP, upload entire `wsb-brands` folder to your site's `/wp-content/plugins/` directory. If you have downloaded 
a zip file, then you can also use the *Add new* option in the *Plugins* menu in WordPress and upload it and install in a
few clicks.  
2. Activate the plugin from the *Plugins* menu in WordPress and you are ready to go.


### Frequently Asked Questions ###

= Where can I add/edit brands? =

Link to brands management page can be found in submenu of *Products* menu

= Where is the settings page? =

Settings page is on a separate tab named *Brands* under Woocommerce settings page.

= How can I assign a brand to my product? =

On a product add/edit form you can find a brand select list in a custom metabox on the right side. Select brand and 
save/update the product.

= Can my customers see all the products of desired brand in one page? =

Of course, each brand has its own archive page. The link to this page can be found in product details, brands widget,
shortcode grid view, or you can simply create a new menu item for any brand.

= Can I show all the brands on a single page? =

Yes, this can be done using shortcode for brands grid with several display options.

= Where can I find a detailed documentation =

Detailed documentation is located at the [WSB Brands](https://www.webstudiobrana.com/wsb-brands-plugin-for-woocommerce/) page.

== Changelog ==

== 1.0.7 ==
* Fix: error with logo alignment on Brand archive page

== 1.0.6 ==
* Fix: error with "Brand info" tab when no brand selected for product
* Feature: added options for display product brand in the shopping cart

== 1.0.5 ==
* Feature: added Brands filter for coupon usage restriction in admin panel
* Enhancement: Shortcode fully compatible with Gutenberg blocks

== 1.0.4 ==
* Feature: added brands filter to the top of product list in admin panel
* Feature: Brands carousel / slider widget for frontend
* Feature: Added selector for main term used on website (brand/manufacturer)

= 1.0.3 =
* Fix: error on saving options (php < 5.6)

= 1.0.2 =
* Feature: added support for Woocommerce product import/export
* Enhancement: improved basic styling and layout options for brand page header
* Enhancement: improved layout and style of shortcode grid
* Feature: color picker for header background on brand page
* Feature: options for border color and thickness of brand page header

= 1.0.1 =
* Fix: Brand is not copied when duplicate product 
* Fix: correction to readme.txt description

= 1.0.0 =
* Initial release of the plugin.
