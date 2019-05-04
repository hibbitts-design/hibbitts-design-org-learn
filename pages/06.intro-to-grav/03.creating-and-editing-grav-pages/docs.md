---
title: Creating and Editing Grav Pages
menu: Creating and Editing Pages
taxonomy:
    category: docs
---

[plugin:youtube](https://www.youtube.com/watch?v=JNkWCmuP5hM)

#### Video Transcript

Hello everyone! In this video, we’re going to be discussing creating and editing Grav pages.

Pages are the heart of your Grav site, and since they are stored as individual files (and not within a database) they offer some unique possibilities.

These include being editable in either the Admin Panel (as shown in this video) or using the text editor of your choice. In addition, since all the options for each page are stored at the start of a page file [try to have video to show example of YAML], they can also be edited by either method .

Let’s start by looking at the different types of pages you can create for your Grav site.

The first type is the Standard Page. This is the most common type of page, consisting of a single markdown file and any associated images.

Second, we have the Listing Page. A Listing Page is a variation of the Standard page that contains a collection of child-pages where each page can also be separately viewed, for example, blog posts.

Lastly, we have the Modular Page. A Modular Page is a special type of a Listing page, where a collection of pages are stacked on top of each other to create a unified, single page. This enables you to present different types of content on a single page.

So, now that we’ve covered the types of pages you can create, let’s create one using the Grav Admin!

Once you’re in your site’s Admin, you’ll notice a Pages link in the sidebar.
Clicking on the Pages link will take you to a list of pages on your site.
Using the provided round (+) buttons you can expand the view to include any page sub-folders
To create a new page, simply select the + Add button and choose Add Page.

The Add Page button creates a non-modular page for your site. Once selected, a popup will appear enabling you to enter a Title and Folder Name, assign a Parent Page and Display Template, as well as to set whether the page should be visible or hidden.

The Title is pretty straightforward. The Folder Name will be the name of the folder as it appears in your site’s file system under the /pages directory. You don’t have to set anything custom here since a folder name is automatically generated based on the title. The folder name will also used to create the URL path to the page, for example for the page folder /blog the full URL to that page would be something like http://mysite.com/blog.

The Parent Page option gives you the opportunity to assign a parent to the new page you’re creating. A common example would be choosing the blog page when you’re creating a blog post.

The Page Template option will determine which template is used to present the content for the new page. When creating a new page for a Listing Page the appropriate Child Page Template is usually automatically selected.

The Visible option determines if the page will be added to your site’s navigation menu for most Grav themes - by using the Auto option Grav will set visibility to the most appropriate setting. If you want, you can also manually set the option to Yes or No.

Once you have filled out this information, selecting Continue will take you to the new page's editor.

**Content Tab**

The Editor is your one-stop-shop for creating a new Grav page. The first tab gives you a simple set of fields to update the page’s title and to write content.

At the top of the content area is the Editor Toolbar. Here you can format text, create links, insert images and more.

In Grav, content is written in markdown format. Markdown is a simple, human-readable alternative to HTML or more complex code languages. In addition, Markdown can also contain standard HTML elements. You can find a lot of great tutorials on Markdown around the Web, including in Grav’s official documentation.

You’ll notice a toolbar at the top of the editor that gives you quick access to some of the more common markdown bits and pieces.

The Page Media section at the bottom of the page allows you to drag and drop files such as images and make them available to the page. Any images you drop here will be stored in the same folder as the page’s markdown file.

You will need to save your Page before adding media to your page this way since the initial save creates the folder that media will be saved to.

**Options Tab**

The Options tab gives you the ability to refine some important information about your page. Whether it’s customizing the page’s date, publish date, or its category and taxonomy information, this tab is where you can easily make these changes.

**Advanced Tab**

The Advanced tab is home to some more advanced customization options for your page. This is where you would go to change some of the information we set up when we initially created the page, including the folder name and parent. You can also change the visibility of a page here.

**Custom Page Settings Tab**

Some types of Pages have a fourth tab, based on the specific purpose of the page. For example, a Listing Page containing blog posts often has a tab called something like Blog Config or Blog List which contains such options as sorting and the maximum number of list items to show at once.

**Page Administrative Controls**

Finally, let’s take a moment to look at this collection of command buttons at the top-right of the page. Once you have created your page’s content and configured any options, you can hit the Save button here to save any changes. Other commands are also available, such as making a copy of the current page or deleting a page.

And that wraps up our look at creating and editing Grav pages!
