---
title: Hypothesis
taxonomy:
    category: docs
---

>>>Not using a Gantry 5 theme with Grav? No problem! There is also a [Hypothesis plugin](https://getgrav.org/downloads/plugins) available.

The ['Hypothesis' Atom](https://github.com/hibbitts-design/grav-gantry5-atom-hypothesis) displays the [Hypothesis](https://web.hypothes.is/) sidebar on your Grav site.

#### Download the Gantry 5 Atom
* Download and unzip the ['Hypothesis' Atom archive](https://github.com/hibbitts-design/grav-gantry5-particle-hypothesis/archive/master.zip).

#### Installing the Atom

Before installing and using the Atom, it is suggested you temporarily enable Gantry's [`Development Mode`](http://docs.gantry.org/gantry5/configure/extras)

1. Open the folder for your active theme in the `user/data/gantry5/themes/` folder of your Gantry installation. For example, if you are using the Helium theme open the folder `user/data/gantry5/themes/g5_helium`.
2. If a `particles` folder already exists within the theme folder open it, otherwise create it.
3. Upload `hypothesis.html.twig` and `hypothesis.yaml` files into the `particles` folder. For example, if you are using the Helium theme copy the two particle files into `user/data/gantry5/themes/g5_helium/particles`.

#### Using the Atom
1. Add the Atom to your theme's 'Atoms' area on the 'Page Settings' panel.

#### Page Options
Once the particle is installed, Grav pages will support the following Page Header/FrontMatter option:

```
hide_hypothesis: true    # hide Hypothesis sidebar on this page
```
