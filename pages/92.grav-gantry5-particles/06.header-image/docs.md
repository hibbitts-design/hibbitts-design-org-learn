---
title: Header Image
taxonomy:
    category: docs
published: false
---

The ['Header Image' Atom](https://github.com/hibbitts-design/grav-gantry5-particle-edit-view-page-in-git) displays a header image above the menubar on your Grav site.

#### Download the Gantry 5 Atom
* Download and unzip the ['Header Image' Atom article](https://github.com/hibbitts-design/grav-gantry-atom-header-image/archive/master.zip).

#### Installing the Atom

Before installing and using the Atom, it is suggested you temporarily enable Gantry's [`Development Mode`](http://docs.gantry.org/gantry5/configure/extras)

1. Open the folder for your active theme in the `user/data/gantry5/themes/` folder of your Gantry installation. For example, if you are using the Helium theme open the folder `user/data/gantry5/themes/g5_helium`.
2. If a `particles` folder already exists within the theme folder open it, otherwise create it.
3. Upload `headerimage.html.twig` and `headerimage.yaml` files into the `particles` folder. For example, if you are using the Helium theme copy the two particle files into `user/data/gantry5/themes/g5_helium/particles`.

#### Using the Atom
1. Add the Atom to your theme's 'Atoms' area on the 'Page Settings' panel.
2. Create a folder called 'headerimage' at root level of your site or within any page folder
3. Copy the image you want to be displayed for your headerimage
4. Create a file called `default.md` and include the following with that file:

```
---
title: HeaderImage
published: false
routable: false
---
```

#### Required CSS
If this Atom was not included in a Grav Skeleton Package, you will need to add the following CSS to your Gantry theme's `custom.css` file. For example, if you are using the Helium theme the `custom.css` file should be located at `user/data/gantry5/themes/g5_helium/scss/custom.css`.

```
.myheader {
  background-color: #464646;
  background-repeat: no-repeat;
  -webkit-background-size: cover;
  -moz-background-size: cover;
  -o-background-size: cover;
  background-size: cover;
  background-position: center;
  width: auto;
  height: 230px
}

@media only all and (min-width:48rem) and (max-width:59.938rem) {
  .myheader {
    height: 190px
  }
}

@media only all and (min-width:30.062rem) and (max-width:47.938rem) {
  .myheader {
    height: 150px
  }
  #g-offcanvas {
    margin-top: 150px
  }
}

@media only all and (max-width:30rem) {
  .myheader {
    height: 110px
  }
  #g-offcanvas {
    margin-top: 110px
  }
}
```

Note: you may need to clear Gantry's cache to update the display of the Atom and also tap the 'Recompile CSS' command.
