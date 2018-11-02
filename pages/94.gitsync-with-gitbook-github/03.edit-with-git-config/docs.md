---
title: Edit Page in Git link Configuration
taxonomy:
    category: docs
published: false
---

1. When viewing your GitBook book, tap on the 'Edit' button
2. Next, tap on the **FILES** tab on the left side of the Browser window
3. Expand the **Pages** folder, then expand one of the Grav page folders listed
4. Tap on the Markdown file contained within the chosen folder
5. Copy the entire URL for the chosen Markdown file. For example, `https://www.gitbook.com/book/paulhibbitts/test-oer-content-space/edit#/edit/master/pages/01.home/default.md?_k=7o64m7`
6. Go to the Admin Panel of your Grav site and locate the option to set the **Edit/View in Git** link in your Grav skeleton.
7. Paste the URL you just copied, but with '/pages' and everything following it removed and tap `Save`. For example, `https://www.gitbook.com/book/paulhibbitts/test-oer-content-space/edit#/edit/master`.

The changes made in your GitHub book should now be synced to GitHub (and to Grav) and visa-versa. While viewing your Grav site, tap the **Edit this Page** link and you will be taken to the related GitBook book page (login required). Fellow GitBook users need to be made **Collaborators** before they are able to propose changes to your GitBook book.
