# Changelog

### 8.2.9

bugfixes (1/27/25)

* Showing deprecated Instagram grid settings to aid in migrating to new plugin

### 8.2.8

bugfixes (1/23/25)

* Adding notices regarding change in Instagram integration method
* Fixes to WooCommerce layout assignments that weren't resolving correctly
* Galleries on Safari were scaling incorrectly due to lazyloading behavior
* Use of the Polylang plugin was preventing ProPhoto designs from exporting
* A corrupted image in the WordPress media library could break the visual builder if used in a design
* Graphic Modules that didn't have a link could prevent the visual builder from loading
* Certain permalink structures were preventing an assigned 404 layout from displaying

### 8.2.7

regression (2/26/24)

* regression - Fatal error renferencing code removed in previous release

### 8.2.6

bugfixes (2/26/24)

* Sites with many customizations could throw error when trying to save a post
* Bold/Italic styles applied in Text Module were incorrectly overridden by Font Style
* Reverting a font override sometimes caused the override settings to stop working
* Font overrides were missing from ProPhoto's WP Content Module
* Relying fully on CloudFlare for caching static files
* Fixed typo in WordPress admin menu for adding a new gallery
* Background videos weren't autoplaying when there were multiple on a single page

### 8.2.5

regression (9/17/23)

* regression - 8.2.4 sticky block fix had an error that unstuck blocks on front

### 8.2.4

bugfixes (9/15/23)

* WordPress 6.4 broke insertion of ProPhoto Grid/Gallery blocks in block editor
* ProPhoto Sticky blocks were becoming unstuck after a ProPhoto update in some scenarios

### 8.2.3

bugfixes (8/28/23)

* Adding step for migrating legacy gallery/grid block data in not already done
* Dragging a header module into the visual builder was resulting in a white screen

### 8.2.2

bugfix and regression (8/15/2023)

* WordPress 6.3 broke insertion of ProPhoto Grid & Gallery blocks in posts/pages
* regression - Posts and Pages failed to save in some scenarios after 8.2.0

### 8.2.1

bugfixes (7/21/2023)

* Using the ProPhoto button in the classic editor to insert a grid wasn't working
* Visual Builder wouldn't save after adding a block or changing a Layout's settings

### 8.2.0

enhancements and bugfixes (7/17/2023)

* **Enhancement** Added "alt" tag support to galleries, grids, excerpt images, graphic modules and tiles
* **Enhancement** New flexible editing window gives more options for customizing your ProPhoto workspace
* **Enhancement** Collapsable sidebar provides more space to preview your site
* **Enhancement** Inline tile editing lets you work with your tiles right in your design
* **Enhancement** Device override settings now show the value being inherited
* **Enhancement** New link selector makes linking to Pages/Galleries easier
* **Enhancement** New scroll-to link selector eliminates the need to copy/paste scroll-to links
* **Enhancement** New border input provides a simpler, visual way to apply borders
* **Enhancement** Improved the appearance of the menu item selector
* Instagram grid can now retrieve HEIC format images (apple format)
* Vertical menu weren't displaying the collapsable submenu icons in the visual builder

### 8.1.5

bugfix (3/15/2023)

* regression - 8.1.4 broke creation of a new graphic module

### 8.1.4

bugfixes (3/13/2023)

* Graphics module with multiple graphics wasn't retaining their order correctly
* Fixed missing padding in the Settings area

### 8.1.3

enhancements and bugfixes (1/18/2023)

* **WooCommerce Enhancement** You can now assign a layout to product pages withing a product category
* **WooCommerce Enhancement** Product reviews now display as reviews instead of comments
* Fixed issue where Grid style "read more" link font style couldn't be set
* Fixed issue preventing grid item images from displaying in some scenarios

### 8.1.2

bugfixes (9/12/2022)

* One of the left navigations arrows was missing from ProPhoto slideshows
* Fixed issue causing block/row/column background images at breakpoints to disappear when saving

### 8.1.1

bugix (8/31/2022)

* Changes in 8.1.0 caused white screen when adding a new text layer to a tile

### 8.1.0

features, enhancements, and bugfixes (8/10/2022)

* **Feature** Override Font Style size & color at specific breakpoints
* **Feature** Speed enhancements to improve your site's page load speed
* **Enhancement** You can now copy an existing Font Style
* **Enhancement** Improved performance of Tiles both on the front and in the visual builder
* **Enhancement** Improved visual experience when dragging a block into the visual builder
* **Enhancement** Made it easier to locate a newly created layout in the visual builder's Layouts area
* "Click to copy" button for scroll-to links now correctly adds text to your clipboard
* Fixed issue preventing transaction ID from being pasted into footer removal links area
* Fixed occasional mis-alignment of ProPhoto Grid items in Safari browser

### 8.0.1

enhancememnt and bugfixes (5/22/2022)

* **Enhancement** PHP 8.1 compatability
* Fixed errors breaking the block editor in WordPress 5.9
* Fixed issue preventing assigned gallery style from applying on single gallery pages
* Prevent WordPress gallery block from stretching images when a max height was applied
* Fixed encoding issue with special characters in a grid added to a WordPress Post or Page
* Allow font icon files to be loaded from alternate url with plugin (for GDPR compatability)

### 8.0.0

Initial prophoto8 release
