---
title: Advanced Grav Markdown Tips
taxonomy:
    category: docs
---

[plugin:youtube](https://www.youtube.com/watch?v=iKfvtu3AvpY)

#### Video Transcript

Markdown is the cornerstone of all Grav content. If you know some basics about Markdown, you’re going to get a lot out of Grav. In this video, we’ll show you some more advanced techniques that take advantage of Grav’s built-in features to get the most out of Markdown for your site’s content.

**Links**  
There are times when you want to give links specific attributes, like making them open links in new tabs rather than in the current window. Here’s how:

Create a standard link using the traditional markdown link rules.
Add a question mark at the end of the link’s URL.
Add `target=_blank`. This will tell Grav that the link should be opened in a new, blank tab.

You can also add other features such as CSS classes, IDs, and nofollow attributes using this method.

**Media**  
Next, let’s talk about media handling. This is one area where Grav puts in a lot of great features that go well beyond traditional Markdown.

Let’s say you have an image. Adding the image to a page is easy, but what if you want that image to appear in black and white? You could open an image editor and edit it yourself, but you can use markdown to do this for you. Here’s how.

Create the image link as you normally would using the basic markdown technique. At the end of the image’s filename, add a question mark and the word grayscale.

Now, let’s say you wanted to change the size of the image by performing a crop and zoom. This is easy, too. Simply add an ampersand to the end and the words cropZoom=300,200. This will create a cropped and zoomed version of the grayscale image that is 300 pixels wide by 200 pixels high.

There are a lot of other tricks you can apply to media files in Grav, many of which are detailed in Grav’s official documentation.

**Tables**  
Tables are an incredible way to bring large amounts of organized content into focus in a clean, easy-to-digest way. Markdown takes a lot of the work out of creating a web-based table. Let’s get started with one!

Let’s put together a simple table listing staff members by name and area of expertise. We have three staff members, each focusing on a different subject.

To create a table, we will use vertical bars to separate cells. Each bar indicating the start of a new cell.

The top row sets the titles of each column of our table. Depending on the theme, this particular row may be emboldened or treated with a different font or weight than the rows below it.

Next, we want to configure how the next set of rows aligns. So, we can do that using a series of dashes and colons. The colons indicate which side of the cell the text aligns to. A colon on each side of the dashes tells Grav to align content in the center.

Finally, we’ll fill in the next few rows with our content.

That’s it! We’ve created a simple table using Markdown.

**Code**  
And finally, let’s look at sharing code or specific blocks of text meant to be copied exactly as it is written. This is another important tool for websites that convey information.

There are two different types of code blocks in Grav, supported by Markdown.

The first is inline code. This is code blocks that live within paragraphs. One example of this might be a specific command or name you want users to copy and paste. To create an inline code block, simply wrap the content in backticks.

The next type is a standalone code block. This is the method of choice for blocks of code with multiple lines and specific syntax rules.

For these, you’ll want to wrap the entire block in triple backticks. Three on top, three on bottom. With the help of a plugin like Highlight you can add syntax highlighting to make your codeblocks even better.

Highlight allows you to add a syntax style to your codeblocks. So, for example, if you have a block of HTML you want users to see, you can write HTML after the first group of backticks to let the plugin know it should highlight your code using HTML rules.

This has been another collection of useful markdown tips for Grav. With additional plugins and other built-in features of the platform, you can create compelling, feature-rich content with Markdown.
