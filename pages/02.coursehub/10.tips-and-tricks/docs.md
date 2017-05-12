---
title: Tips and Tricks
taxonomy:
    category: docs
---

Get the most out of your Open Course Hub!

* [Only display page content (when embedding pages)](#only-display-page-content-when-embedding-pages)
* [Customizing your Open Course
Hub theme](#customizing-your-open-course-hub-theme)
* [Making a homepage blog post 'sticky'](#making-a-homepage-blog-post-sticky)

##### Only display page content (when embedding pages)

When displaying Open Course Hub pages within another system (e.g. LMS) it is often helpful to only display page content and not include header navigation and the sidebar.

To do this, add `onlydisplaypagecontent:true` to your page URLs. For example, to only display the content of the page at [demo.hibbittsdesign.org/grav-course-hub-bootstrap/home/week-03/](http://demo.hibbittsdesign.org/grav-course-hub-bootstrap/home/week-03/) you would use the revised URL of [demo.hibbittsdesign.org/grav-course-hub-bootstrap/home/week-03/onlydisplaypagecontent:true](http://demo.hibbittsdesign.org/grav-course-hub-bootstrap/home/week-03/onlydisplaypagecontent:true)

##### Customizing your Open Course Hub theme

The Open Course Hub skeleton package comes with an [Inherited Theme](https://learn.getgrav.org/themes/customization#theme-inheritance) called 'mytheme' all ready for your further customization.

In addition, this theme is also automatically synced to the Git repository of your site. This means that you can invite other people, such as fellow educators or your students, to assist in the further customization of your site.

##### Making a homepage blog post 'sticky'

To make a blog post precede all other blog posts listed, add a `Featured` tag to it's taxonomy field (located on the `Options` panel when editing a page in the Admin Panel). The frontmatter that is added to the page will look like this:

```
taxonomy:
    tag:
        - Featured
```

##### Hiding a post from the homepage post list

To hide a blog post from the homepage post list, but still make it available on other pages, add the following page frontmatter option:

```
hidefrompostlist: true
```
