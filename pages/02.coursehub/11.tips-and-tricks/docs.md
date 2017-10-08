---
title: Tips and Tricks
taxonomy:
    category: docs
---

Get the most out of your Open Course Hub!

* [Editing Course Hub content on your desktop](#editing-site-content-on-your-desktop)
* [Customizing your Course
Hub theme](#customizing-your-course-hub-theme)
* [Only display page content (when embedding pages)](#only-display-page-content-when-embedding-pages)
* [Making a homepage blog post 'sticky'](#making-a-homepage-blog-post-sticky)

##### Editing site content on your desktop

You can use the [GitHub Desktop](https://desktop.github.com/) application with either [GitLab](https://about.gitlab.com/) or [GitHub](https://github.com/) to clone and edit your Open Course Hub pages on your own computer:

* [GitHub & GitHub Desktop](/github-githubdesktop)
* [GitLab & new Electron-based GitHub Desktop Beta](/gitlab-githubdesktop-beta)
* [GitLab & GitHub Desktop](/gitlab-githubdesktop)

##### Customizing your Course Hub theme

The Open Course Hub skeleton package comes with an [Inherited Theme](https://learn.getgrav.org/themes/customization#theme-inheritance) called 'mytheme' all ready for your further customization.

In addition, this theme is also automatically synced to the Git repository of your site. This means that you can invite other people, such as fellow educators or your students, to assist in the further customization of your site.

##### Only display page content (when embedding pages)

When displaying Open Course Hub pages within another system (e.g. LMS) it is often helpful to only display page content and not include header navigation and the sidebar.

To do this, add `chromeless:true` to your page URLs. For example, to only display the content of the page at [demo.hibbittsdesign.org/grav-course-hub-bootstrap/home/week-03/](http://demo.hibbittsdesign.org/grav-course-hub-bootstrap/home/week-03/) you would use the revised URL of [demo.hibbittsdesign.org/grav-course-hub-bootstrap/home/week-03/chromeless:true](http://demo.hibbittsdesign.org/grav-course-hub-bootstrap/home/week-03/chromeless:true)

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

##### Override a page's automatically calculated Git Repository URL

To override the automatically calculated Git Repository URL on a page (i.e. to view a folder containing child pages), add the desired URL to the page frontmatter like this:

```
gitrepoeditlinkurl: https://github.com/hibbitts-design/grav-skeleton-course-hub/tree/master/pages/01.home
```
