---
title: Theme Customization
taxonomy:
    category: docs
---

The easiest method to customize the Learn2 with Git Sync theme is to use Grav’s [theme inheritance](https://learn.getgrav.org/themes/customization#theme-inheritance) feature. However, as the Learn2 with Git Sync is actually an inherited theme, your `/user/themes/mytheme/mytheme.yaml` file will need to include a total of three theme references:

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
