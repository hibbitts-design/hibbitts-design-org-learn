---
title: Edit/View Page in Git
taxonomy:
    category: docs
---

The ['Edit/View Page in Git' Particle](https://github.com/hibbitts-design/grav-gantry5-particle-edit-view-page-in-git) displays a link to edit the current Grav page stored in a Git repository (i.e. GitHub or GitLab).

#### Download the Gantry 5 Particle
* Download and unzip the ['Edit/View Page in Git' Particle archive](https://github.com/hibbitts-design/grav-gantry5-particle-edit-view-page-in-git/archive/master.zip).

#### Installing the Particle

Before installing and using the Particle, it is suggested you temporarily enable Gantry's [`Development Mode`](http://docs.gantry.org/gantry5/configure/extras)

1. Open the folder for your active theme in the `user/data/gantry5/themes/` folder of your Gantry installation. For example, if you are using the Helium theme open the folder `user/data/gantry5/themes/g5_helium`.
2. If a `particles` folder already exists within the theme folder open it, otherwise create it.
3. Upload `edit_view_page_in_git.html.twig` and `edit_view_page_in_git.yaml` files into the `particles` folder. For example, if you are using the Helium theme copy the two particle files into `user/data/gantry5/themes/g5_helium/particles`.

The perfect companion to this Gantry 5 particle is the [Grav GitSync Plugin](http://www.hibbittsdesign.org/blog/posts/2016-12-22-touchdown-seamless-2-way-syncing-arrives-for-grav).

#### Grav 'Edit/View in Git' Particle Setup
[!['Edit/View in Git' Particle Setup](https://github.com/paulhibbitts/github-repo-images/blob/master/edit-view-this-page-setup-video.png?raw=true)](http://www.youtube.com/watch?v=4cHwJ27jqXM "'Edit/View in Git' Particle Setup")  

#### Particle Options
!['Edit this Page' options](https://github.com/paulhibbitts/github-repo-images/blob/master/edit-view-this-page-options.png?raw=true)

#### Page Options
Once the particle is installed, Grav pages will support the following Page Header/FrontMatter option:

```
hide_git_repo_link: true    # hide Git Repository edit link for this page, up to but not including the '/pages/...' For example, 'https://github.com/paulhibbitts/grav-skeleton-gantry-oer-content/tree/master'.  
git_repo_link_url: https://github.com/hibbitts-design/grav-skeleton-course-hub/tree/master/pages/01.home   # to override the automatically calculated Git Repository URL
git_repo_link_text: View in Markdown   # to override the default URL text label
```

##### Site Config Options
Once the particle is installed, Grav pages will support the following Site Config option:

```
hide_git_repo_link_pages:    # list of pages to hide Git Repository edit link on
    - login
    - logout                        
```
