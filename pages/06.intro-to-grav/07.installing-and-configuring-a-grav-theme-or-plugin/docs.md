---
title: Installing and Configuring a Grav Theme or Plugin
menu: Installing a Theme or Plugin
taxonomy:
    category: docs
process:
    twig: true
---

[plugin:youtube](https://www.youtube.com/watch?v=vdEWeHf3Ejo)

#### Video Transcript

Hello everyone! Today, we’re going to be installing a new plugin and theme to our Grav site.

Grav comes with a default theme called Quark, but what if we wanted to try out one of the over 100 other free and open source themes available for Grav?

What if we wanted to add features to our site using one or more of the nearly 300 free plugins Grav has to offer?

We can do both of these things very easily in Grav. Here’s how:

**Plugin Installation**  
Let’s use the YouTube Plugin as our example - this Plugin will let you to seamlessly embed YouTube videos into your Grav Markdown content, and will even add a YouTube button to your Page Editor area to help you more easily add a YouTube video.

To install this plugin, we’ll need to access the Grav admin and head over to the Plugin tab. Here, you can see a list of your currently installed plugins.

Next, we will select the Add button and use the search bar to find the plugin called YouTube.

Clicking the Install button gives you a popup where you can initiate the installation process. When you do this, the plugin and any dependencies will be installed automatically.

Upon successful installation, you should be taken directly to the plugin’s configuration page. Here, you can see any options the plugin has and set them as you like. You can also usually access the ReadMe file for the Plugin from this page.

You should also make sure your plugin is enabled using the toggle buttons in the Plugin Status field.

If you have made any changes to the configuration of the plugin click Save and you are now ready to use the Plugin.

Using this plugin is a breeze. All you need to do now to add a youtube video to your page is to click the “YouTube” icon now in your page content editor toolbar and enter the URL of the YouTube video you would like to add ([https://www.youtube.com/watch?v=avcGP0FAzB8](https://www.youtube.com/watch?v=avcGP0FAzB8)) You can also type out the Shortcode by using`[plugin:youtube]` followed by `(https://www.youtube.com/watch?v=avcGP0FAzB8)`

That’s it! Just save and take a look at your new embedded video.  

**Theme Installation**  
Let’s say we want to give our Grav site a new look. To do this, we’ll need to give our site a new theme. One of Grav’s most popular free themes is Bootstrap4. It’s a simple theme featuring the flexible Bootstrap framework.

To install a new theme, select Themes from the sidebar of the admin. This will take you to a page that displays all of your currently-installed themes.

From here, click Add and use the Filter field to search for your theme. Once you’ve located your theme of choice, click Install and Continue on the popup that appears.  If the theme requires any dependencies they will be installed automatically.

After the theme installation is complete you will then be directed to your new theme’s configuration page where you can set any options.

There is one more step to go! Simply go back to the Themes page using the link in the Admin sidebar and click the Activate link under the theme you would like to activate on your site. Confirm this, and check the results.

Changing Page Templates

It’s important to note here that not all themes have the same template names or supply the same set of templates. You may have to rename or reassign templates to pages that don’t display properly after switching themes. Here’s one way to do that:

Go to the Pages area of the Admin and choose the page you would like to assign a new template to. Click the Advanced tab, and choose a new template from the Page Template dropdown. Save your changes and you’re done!
