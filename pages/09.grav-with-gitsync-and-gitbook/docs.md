---
title: Grav with Git Sync & GitBook
taxonomy:
    category: docs
---

Using Grav with GitSync, the Grav site content stored within a Git (i.e. GitHub) repository can also be edited using the visual editor [GitBook](https://www.gitbook.com/). There are currently some limitations with this approach (e.g. lack of change requests), as it is based on the use of **Files** (and not **Articles**) within GitBook.

##### Getting Ready

* Install and configure a Grav skeleton package with Git Sync
* Signup for a GitBook account

##### Setting up GitBook for Grav with Git Sync

1. Follow the [GitHub Integration instructions for GitBook](https://help.gitbook.com/github/can-i-host-on-github.html) and choose the repository that contains your Grav site content
1. Create a new GitHub Book, using the **GitHub** Template (tap on the displayed down-arrow to scroll down to the GitHub option)
1. Name your GitHub Book, and choose the repository that contains your Grav site content

At this point you should see a status message indicating that your GitHub content is being synced to your new GitBook book.

##### Setting up Your 'Edit this Page in Git Link'

1. When viewing your GitBook book, tap on the 'Edit' button
2. Next, tap on the **FILES** tab on the left side of the Browser window
3. Expand the **Pages** folder, then expand one of the Grav page folders listed
4. Tap on the Markdown file contained within the chosen folder
5. Copy the entire URL for the chosen Markdown file. For example, `https://www.gitbook.com/book/paulhibbitts/test-oer-content-space/edit#/edit/master/pages/01.home/default.md?_k=7o64m7`
6. Go to the Admin Panel of your Grav site and locate the option to set the **Edit/View in Git** link in your Grav skeleton.
7. Paste the URL you just copied, but with '/pages' and everything following it removed and tap `Save`. For example, `https://www.gitbook.com/book/paulhibbitts/test-oer-content-space/edit#/edit/master`.

That's it! The changes made in your GitHub book should now be synced to GitHub (and to Grav) and visa-versa. While viewing your Grav site, tap the **Edit this Page** link and you will be taken to the related GitBook book page (login required). Fellow GitBook users need to be made **Collaborators** before they are able to propose changes to your GitBook book.

##### Grav + GitBook Setup (OER Content Space Skeleton) 
[plugin:youtube](https://www.youtube.com/watch?v=HVk76h5OWi8)
