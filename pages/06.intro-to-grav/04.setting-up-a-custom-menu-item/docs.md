---
title: Setting Up a Custom Menu Item
taxonomy:
    category: docs
---

[plugin:youtube](https://www.youtube.com/watch?v=zmzc0zv-4Mo)

#### Video Transcript

Hello everyone! Today, we’re going to be creating custom menu items in Grav.

Custom menu items give you the ability to quickly and easily add links to your site’s navigation menu that go beyond your site’s pages and into external resources.

Link to your social media pages, other websites you manage, or even to a GitHub or GitLink content repository containing the content of your Grav site. The choice is yours.

The most common method for achieving this is through creating a redirect page within your site.

Let’s get started!
Step 1: Create a Redirect Page
Even though we’re linking our new menu item to an external page, we still have to create what’s referred to as a Redirect Page which tells Grav that an item should appear in the site menu, and where that item should go.

Here’s how:

**Step 1: Create a Page**

* Navigate to the Grav admin dashboard.
* Select Pages from the sidebar.
* Select ADD+ and then Add Page.
 * This will initiate the Add Page wizard.
* Enter the text you want to appear as your menu item in the Title field.
* The Parent Page setting will enable you to decide where your custom menu item will appear in the menu. For a top-level menu item, stick with the default root option.
* The Auto setting on Visible will usually create a menu item for you, but if you want to ensure this happens, switch it to Yes. To prevent your menu item from appearing, you can switch it to No.
* Finally, select the Continue button to proceed to the page editor.

**Step 2: Add the Redirect**

The next step in the process involves adding the redirect to the page. Here is the simplest method:

Select the Advanced tab.
Scroll down to Overrides and locate the Page Redirect field.
Enter the URL you would like the menu item to go to in the field.
Select Save.

That’s it! We’ve created a new menu item that goes directly to your URL of choice.

There are other ways to achieve the same effect, including manually entering the redirect override in Expert mode or using your text editor of choice. Some themes also have easy-to-configure fields that enable you to add custom menu items along with icons without having to create pages at all.

And that wraps up at our brief look at creating custom menus in Grav!
