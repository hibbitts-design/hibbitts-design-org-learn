---
title: Tips and Tricks
taxonomy:
    category: docs
---

Get the most out of your Learn2 with Git Sync site!

* [Customizing your Learn2 with Git Sync theme](#customizing-your-learn2-with-git-sync-theme)
* [Add RSS/Atom feed buttons to your site](#add-rssatom-feed-buttons-to-your-site)

##### Customizing your Learn2 with Git Sync theme

The easiest method to customize the Learn2 with Git Sync theme is to use Grav’s [theme inheritance](https://learn.getgrav.org/themes/customization#theme-inheritance) feature. However, as the Learn2 with Git Sync is actually an inherited theme, your `/user/themes/mytheme/mytheme.yaml` file will need to include a total of three theme references:

```
streams:
 schemes:
   theme:
     type: ReadOnlyStream
     prefixes:
       '':
       - user/themes/mytheme
       - user/themes/learn2-git-sync
       - user/themes/learn2
```

A customizable 'mytheme' inherited theme is also provided with the Learn2 with Git Sync skeleton package, available for download at [getgrav.org/downloads/skeletons](https://getgrav.org/downloads/skeletons).

##### Add RSS/Atom feed buttons to your site

Once you upgrade to the newest release of the Learn2 with Git Sync theme, create a new root-level page folder with the name `feed` containing a file called `docs.md`, add then the following content to that page file:

```
---
visible: false
content:
    items:
        '@taxonomy.category': 'docs'
    order:
        by: date
        dir: desc
---

Non-visible page for RSS feed page collection. RSS feed URL is ../feed.rss

```

You can view an example **Feed** page at [github.com/hibbitts-design/grav-skeleton-learn2-with-git-sync/tree/master/pages/feed](https://github.com/hibbitts-design/grav-skeleton-learn2-with-git-sync/tree/master/pages/feed)

Refresh your Browser window and the RSS/Atom feed buttons should now appear at the bottom of the left sidebar (make sure that the Feed plugin is installed and enabled).

A ready-to-go set of RSS/Atom feed buttons are provided with the Learn2 with Git Sync skeleton package, available for download at getgrav.org/downloads/skeletons.

##### Ordering pages on your site

<!--
Paul, perhaps this should be a new page, or perhaps not. It took me a while to sort out why my ToC wasn't matching with the navigation order.
-->

Grav comes packaged with the capability to quickly and easily set the order of your pages. All you need to do is use the hamburger menu icon to drag your pages into the order that you would like them to appear in your table of contents.

<!--
I don't have push access to upload images, I'll email the screenshots.
-->
![](../../images/order-toc.png)


However, you may find that, even though you have the ToC set up as you want it, the navigation in your Learn2 documentation site doesn't match the ToC, or that a chapter or page gets skipped when you use the arrows to navigate.

To fix this, please ensure that all of the following settings on your chapters and pages match the following:

###### Ensure that you are using the proper page template.

![](../../images/page-template.png)


###### Ensure that you are using the correct page category.

![](../../images/page-category.png)
