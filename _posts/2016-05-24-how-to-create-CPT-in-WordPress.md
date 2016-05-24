---
layout: post
title: How to Create Custom Post Types in WordPress
tags: [WordPress, Custom Post Types]
---
<a target="_blank" href="http://www.wpbeginner.com/wp-tutorials/how-to-create-custom-post-types-in-wordpress/">http://www.wpbeginner.com/wp-tutorials/how-to-create-custom-post-types-in-wordpress/</a>

## Creating a Custom Post Type – The Easy Way

The easiest way to create a custom post type in WordPress is by using a plugin. This method is recommended for beginner because it is safe and super easy.

First thing you need to do is install and activate the  <a href="https://wordpress.org/plugins/custom-post-type-ui/">Custom Post Type UI plugin</a>. Upon activation, the plugin will add a new menu item in your WordPress admin menu called CPT UI.

Now go to <b>CPT UI » Add New</b> to create a new custom post type.

The Custom Post Type UI plugin also allows you to create custom taxonomies.

This is why the Add new custom post type page is divided into two columns. On your left, you have the form you need to fill to create your custom post type. On your right, you have a form to create a custom taxonomy if you need one.

In the custom post type column, first you need to provide a name for your custom post type. This name cannot exceed more than 20 characters, e.g. movies, recipe, deal, glossary, etc.

In the next field, you need to provide a label for your custom post type. This label will appear in your WordPress admin bar just like posts and pages. It also needs to be plural to make sense. e.g. Movies, Recipes, Deals, Glossary, etc.

After that you need to provide a singular form for your label. This singular form will be used by WordPress to show instructions and other user interface elements.
Lastly enter a description for your custom post type. This description is simply used to describe what your post type does.

Now you can click on the ‘Create Custom Post Type’ button to add your new custom post type. That’s all.
You can also click on the Advanced Label Options and Advanced Options links to customize more options for your custom post type.

##Creating a Custom Post Type Manually

The problem with using a plugin is that your custom post types will disappear when the plugin is deactivated. Any data you have in those custom post types will still be there, but your custom post type will be unregistered and will not be accessible from the admin area.

If you are working on a client site and do not want to install another plugin, then you can manually create your custom post type by adding the required code in your theme’s functions.php file or in a site-specific plugin (See: Custom Post Types Debate functions.php or Plugin).