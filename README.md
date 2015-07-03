# Custom Post Type Generator

WordPress Plugin: Custom Post Type Generator

Generate Custom Post Types and Custom Taxonomies.

## Description

Generate Custom Post Types and Custom Taxonomies, from the admin interface which is easy to understand.
it's a must have for any user working with WordPress.

## Installation

1. Upload 'custom-post-type-generator' folder to the `/wp-content/plugins/` directory
2. Activate the plugin through the 'Plugins' menu in WordPress
3. Navigate to the Custom Post Type Generator Menu

## Screenshots

1. Regist Custom Post Type
2. Regist Custom Taxonomy
3. Export to PHP

## Changelog

**2.3.6**

* Delete flush_rewrite_rules() from 'init' hook.

**2.3.5**

* Bug fixed
 - Exported PHP Code

**2.3.4**

* Bug fixed

**2.3.3**

* Bug fixed
 - priority 'init' hook of cptg_generate().

**2.3.2**

* Validation of input values improved.

**2.3.1**

* Activation improved.
* Support non public objects( show_ui=true, show_in_menu=true ).
* Admin UI improved.

**2.3.0**

* Support for the most parameters.
* Admin UI improved.
* Objects List improved.
* Exported PHP Code improved.
* Bug fixed

**2.2.4**

* Bug fixed
 - flush_rewrite_rules() of PHP code.

**2.2.3**

* Support for the 'rewrite' settings.
* Support fot the 'sort' setting of Custom Taxonomy.
* Admin UI improved.
* Input error check improved.
* Bug fixed
 - flush_rewrite_rules()

**2.2.2**

* Bug fixed

**2.2.1**

* Bug fixed

**2.2.0**

* Export to PHP
* Add 'Other Objects' List.
* Bug fixed

**2.1.3**

* Bug fixed
 - Order Custom Post Types.

**2.1.2**

* Bug fixed

**2.1.1**

* Order Custom Post Types using a Drag and Drop Sortable JavaScript.

**2.0.1**

* Bug fixed
 - The Configuration of 'Publicly Queryable'.

**2.0.0**

* WordPress Options Structure was Renovated.
* Fatal Error(500 Error) solved.

**1.0.2**

*Bug fixed
 - menu_icon (Default: null - defaults to the posts icon)

**1.0.1**

*Bug fixed
 - 500 Error

**1.0.0**

*Initial Release

## Upgrade Notice

**2.0.0**

There was the Fatal Error in ver1.0.x.
This problem is solved in ver.2.0.0.
However, WordPress Option Data Structure has been modified fundamentally.
Please be sure to do backup of 'Custom Post Type Name' and 'Taxonomy Name'.
But Contents will not delete which belong to.
Thanks.
