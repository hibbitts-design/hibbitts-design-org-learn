---
title: Editing Grav Pages Locally using Git (e.g. GitHub)
menu: Editing Pages Locally using Git
taxonomy:
    category: docs
---

[plugin:youtube](https://www.youtube.com/watch?v=f4QMU1WVu10)

#### Video Transcript

Once you have configured Git Sync on your Grav site, it’s time to put it to use! One of the great things about Git Sync is that it gives you a ton of different options for editing your website’s content and syncing those changes to your Git provider of choice, such as GitHub, GitLab, Bitbucket and others.

To demonstrate these options, we’re going to use our Grav site and a GitHub repository we synced in a previous video.

We’re going to examine three ways to edit that site’s content: including  the Admin Panel, on GitHub.com, and locally using Git.

##### Admin
Git Sync works automatically in the background, so once you’ve configured it, you can create and edit pages directly from the Grav admin like you normally would and see those changes synchronized in real-time to GitHub.

Let’s say we have a page here we would like to change the title for. Since we have Git Sync set up, the page also appears in the GitHub repo.

Now, we just edit the title and save our changes in the Grav Admin. Once we have done that, we can refresh the page in our repo and see the changes.

That’s all there is to it! Your content is synced and backed up on GitHub without any extra steps.

##### GitHub.com
The same process works in the other direction. You can edit or create a page on GitHub’s website and it will automatically appear on your website thanks to Git Sync. This is done by using the Webhook that was initially setup with the repo.

That page we edited earlier could use another small change. Simply navigate to the page in your repo and select the edit icon.

You can make any changes you’d like to make here, then commit the changes at the bottom of the page. Your changes should appear on the website automatically.

Since your content is now on GitHub, Pull Requests from other GitHub members are now possible. A Pull Request is a suggested change to your content, where you can first review those changes before deciding to accept them, discuss possible further modifications, or decide not to accept them.

##### Local Clone
Finally, let’s look at another great option. Because your content is being saved in a git repo, you can clone it down locally using your git client of choice and edit the page files in a text editor and push those changes to GitHub and your website all without having to even open your browser.

Using the free GitHub Desktop app for Windows and MacOS, we are going to clone my repository to my local drive by either finding it through the interface or copying the HTTPs git URL from GitHub.com.

Once the files are downloaded, you can open them in a code editor of your choice. Keep in mind this is a more advanced method and you will need to become familiar with Grav’s YAML frontmatter to edit such items as the title and taxonomy of your pages.

In this example, we’ll edit the title of our page and create a new opening sentence. Once we’ve saved the changes to the file we create a git commit using the GitHub app and push it to GitHub like so.

That’s it! Your changes should automatically appear on your website once having been pushed to the GitHub repo and then synced to your site.
