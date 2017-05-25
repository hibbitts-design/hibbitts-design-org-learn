---
title: Header Image
taxonomy:
    category: docs
---

#### Download the Gantry 5 Atom
* Download and unzip the ['Header Image' Atom](https://github.com/hibbitts-design/grav-gantry-atom-header-image/archive/master.zip).

#### Installing the Atom

1. Open the folder of your active Gantry theme. For example, if you are using the Hydrogen theme open the folder `/user/themes/g5_helium`.
2. If a `custom` folder already exists open it, otherwise create it.
3. If a `particles` folder already exists within the `custom` folder open it, otherwise create it.
4. Upload `headerimage.html.twig` and `headerimage.yaml` files into the `/custom/particles` folder. For example, if you are using the Helium theme copy the two particle files into `/user/themes/g5_helium/custom/particles`.

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

Note: you may need to clear Gantry's cache to update the display of the Atom
