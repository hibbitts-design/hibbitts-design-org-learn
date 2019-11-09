---
title: Tips and Tricks
taxonomy:
    category: docs
---

Get the most out of your Open Publishing Space!

* [Editing Open Publishing Space content on your desktop](#editing-open-publishing-space-content-on-your-desktop)
* [Customizing your Open Publishing Space theme](#customizing-your-open-publishing-space-theme)
* [Only display page content (when embedding pages)](#only-display-page-content-when-embedding-pages)  
* [Making a homepage blog post 'sticky'](#making-a-homepage-blog-post-sticky)
* [Hiding a post from the homepage post list](#hiding-a-post-from-the-homepage-post-list)
* [Built-in ShortCodes](#built-in-shortcodes)

##### Editing Open Publishing Space content on your desktop

You can use the [GitHub Desktop](https://desktop.github.com/) application with either [GitLab](https://about.gitlab.com/) or [GitHub](https://github.com/) to clone and edit your Open Publishing Space pages on your own computer:

* [GitHub & GitHub Desktop](/github-githubdesktop)
* [GitLab & new Electron-based GitHub Desktop Beta](/gitlab-githubdesktop-beta)
* [GitLab & GitHub Desktop](/gitlab-githubdesktop)

##### Customizing your Open Publishing Space theme

The Open Publishing Space skeleton package comes with an [Inherited Theme](https://learn.getgrav.org/themes/customization#theme-inheritance) called 'mytheme' all ready for your further customization.

In addition, this theme is also automatically synced to the Git repository of your site. This means that you can invite other people, such as fellow educators or your students, to assist in the further customization of your site.

##### Only display page content (when embedding pages)

When displaying Open Publishing Space pages within another system (e.g. LMS) it is often helpful to only display page content and not include header navigation and the sidebar.

To do this, add `chromeless:true` to your page URLs. For example, to only display the content of the page at [http://demo.hibbittsdesign.org/grav-open-publishing-quark/blog/the-urban-jungle](http://demo.hibbittsdesign.org/grav-open-publishing-quark/blog/the-urban-jungle) you would use the revised URL of [http://demo.hibbittsdesign.org/grav-open-publishing-quark/blog/the-urban-jungle/chromeless:true](http://demo.hibbittsdesign.org/grav-open-publishing-quark/blog/the-urban-jungle/chromeless:true)

##### Making a homepage blog post 'sticky'

To make a blog post precede all other blog posts listed, add a `featured` tag to it's taxonomy field (located on the `Options` panel when editing a page in the Admin Panel). The frontmatter that is added to the page will look like this:

```
taxonomy:
    tag:
        -featured
```

##### Hiding a post from the homepage post list

To hide a blog post from the homepage post list, but still make it available on other pages, add the following page frontmatter option:

```
hide_from_post_list: true
```

##### Override a page's automatically calculated Git Repository URL

To override the automatically calculated Git Repository URL on a page (i.e. to view a folder containing child pages), add the desired URL to the page frontmatter like this:

```
git_sync_repo_link: https://github.com/hibbitts-design/grav-skeleton-open-publishing-space/tree/master/pages/01.blog
```

##### Built-in ShortCodes

**iFrame**

This ShortCode embeds an iFrame.

```
[iframe url="http://getgrav.org"]
[iframe url="http://getgrav.org" aspectratio="4-3"]
[iframe url="http://getgrav.org" aspectratio="16-9"] (default)
```

**Markdown File**

This ShortCode embeds an external [Markdown](https://en.wikipedia.org/wiki/Markdown) file.

```
[markdownfile url="https://raw.githubusercontent.com/hibbitts-design/grav-skeleton-open-publishing-space/master/README.md"]
```

**Embed.ly**

This ShortCode embeds an [Embed.ly](http://embed.ly/) card Webpage preview.

```
[embedly url="http://getgrav.org"]
```

Example (image)

![](embedly.png)

**H5P**

This ShortCode embeds an [H5P](https://h5p.org) content item.

```
[h5p id="712"]
[h5p url="https://h5p.org/h5p/embed/712"]
```

When using the `[h5p id=""]` format the H5P Content Embed Source URL must be set in the Active Theme settings.

Example (image)

![](h5p.png)

**Swipe**

This shortcode embeds a [Swipe](https://www.swipe.to) slidedeck.

```
[swipe id="97940k6h8r7cnfw"]
```

Example (image)

![](swipe.png)
