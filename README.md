<!-- @file Instructions on how to sub-theme the Drupal Bootstrap base theme using the CDN Starterkit. -->
<!-- @defgroup subtheme_cdn -->
<!-- @ingroup subtheme -->

# Setup
##Prerequisites
* Drupal 8
* NodeJs
* Gulp
* Bootstrap 3 Module

###Working with Bootstrap
Install Bootstrap 3. Download drupal 8 version https://www.drupal.org/project/bootstrap or install via drush command <code>drush dl bootstrap</code>

###Working with Gulp
To install Gulp:
**Windows**
<pre>
<code>npm install</code><br>
<code>npm install gulp -g</code>
</pre>
**Ubuntu**
<pre>
<code>sudo npm install</code><br>
<code>sudo npm install gulp -g</code>
</pre>

##Directory Setup
1. <code>git clone https://github.com/dreamypixy/d8bootstrap-subtheme.git</code>
Inside ~themes/ directory
2. <code>cd themes/clonedfolder</code>
3. Type in <code>npm install</code>
4. Go inside drupal administration page and select **Appearance**
5. Enable **Bootstrap Subtheme**

## CDN Starterkit

The CDN Starterkit is rather simple to set up. You don't have to do anything
until you wish to override the default [Drupal Bootstrap] base theme settings
or provide additional custom CSS.

- [Prerequisite](#prerequisite)
- [Override Styles](#styles)
- [Override Settings](#settings)
- [Override Templates and Theme Functions](#registry)

### Prerequisite
Read the @link subtheme Sub-theming @endlink parent topic.

### Override Styles {#styles}
Open `./subtheme/css/style.css` and modify the file to your liking.

### Override Settings {#settings}
Please refer to the @link subtheme_settings Sub-theme Settings @endlink topic.

### Override Templates and Theme Functions {#registry}
Please refer to the @link registry Theme Registry @endlink topic.

[Drupal Bootstrap]: https://www.drupal.org/project/bootstrap
[Bootstrap Framework]: http://getbootstrap.com
[jsDelivr CDN]: http://www.jsdelivr.com
