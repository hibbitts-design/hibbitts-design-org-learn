---
title: Customizing Learn2 with Git Sync
taxonomy:
    category: docs
---

The easiest method to customize the Learn2 with Git Sync theme is to use Grav’s theme inheritance feature. However, as the Learn2 with Git Sync is actually an inherited theme, the following should be included in your /user/themes/mytheme/mytheme.yaml file:

```
streams:
 schemes:
   theme:
     type: ReadOnlyStream
     prefixes:
       '':
       - user/themes/mytheme
       - user/themes/learn2-git-sync
       - user/themes/learn2
```
