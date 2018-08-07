---
title: Getting Started with Grav
taxonomy:
    category: docs
---

##### Expected Technical Skills

* Markdown or HTML basics
* Understanding folder hierarchies (i.e. relative links)

##### Web Installation
**Pre-flight Checklist**  
1. Confirm Web server PHP version (PHP 5.5.9 or higher)
1. Web server login credentials (username and password)

**Installation Steps**  
1. Download the [Grav Open Matter Blog Skeleton](http://hibbittsdesign.org/blog/downloads/grav-skeleton-open-matter-blog-site.zip)
1. Unzip the package onto your desktop
1. Copy the _entire_ Grav folder to your Web server
1. Point your browser to the Web server folder
1. Create your site administrator account when prompted
1. And you're done! (press the <i class="fa fa-arrow-circle-right"></i> icon in the Admin Panel to preview site)

##### Desktop Installation
**Pre-flight Checklist**  
1. Confirm Web server PHP version (PHP 5.5.9 or higher)
1. Download and install [MAMP](https://www.mamp.info/) (mamp.info)

**Desktop Installation Steps**  
1. Download the [Grav Open Matter Blog Skeleton](http://hibbittsdesign.org/blog/downloads/grav-skeleton-open-matter-blog-site.zip)
1. Unzip the Grav package onto your desktop
1. Copy the _entire_ Grav folder into the 'htdocs' folder within your MAMP application folder
1. Launch MAMP
1. Press the MAMP 'Start Servers' button
1. Enter 'localhost:8888' as the URL in your Web Browser
1. Choose the displayed Grav folder name
1. Create your site administrator account when prompted
1. And you're done! (press the <i class="fa fa-arrow-circle-right"></i> icon in the Admin Panel to preview site)

##### Editing a Page

To edit a page, you can either use the installed Admin Panel plugin (accessed by adding '/admin/ to the URL of your **Grav** site) or work with files locally using a text editor of choice such as [Atom.io](http://atom.io) or [Adobe Brackets](http://brackets.io).

**Admin Panel**  
![Image of Grav Admin Panel](admin-panel-pages.png?resize=600,400)  
Press on the **Pages** button on the left-hand toolbar and then choose the **Home** page.

**Working with Files**  
Navigate to the folder you installed **Grav** into, and then browse to the `user/pages/01.home` folder and open the `default.md` file in the text editor of your choice. You will see the content of this page in [Markdown format](http://learn.getgrav.org/content/markdown).

##### Create a New Page

**Admin Panel**  
1. In the **Pages** panel press the **Add Page** button and then enter `My Page` as the **Page Title**. Make sure that the **Page Template** is set to `Default`.  
2. Enter the below page content of your choice on the newly created page, and then tap the `Save` button:

        # My New Page!

        This is the body of **my new page** and I can easily use _Markdown_ syntax here.

Pages in **Grav** can also include the content of other pages (i.e. Modular pages).

**Working with Files**  
1. Navigate to your pages folder: `user/pages/` and create a new folder.  In this example, we will use [explicit default ordering](http://learn.getgrav.org/content/content-pages) and call the folder `06.another-page`.
2. Launch your text editor and paste in the following:

        ---
        title: Another Page
        ---
        # Another New Page!

        This is the body of **a new page** and I can easily use _Markdown_ syntax here.

3. Save this file in the `user/pages/06.another-page/` folder as `default.md`. This will tell **Grav** to render the page using the **default** template.
4. That is it! Reload your browser to see your new page in the menu.

_**Want to learn even more about using Grav?** Check out the [Next Steps](/learnmore) section!_
