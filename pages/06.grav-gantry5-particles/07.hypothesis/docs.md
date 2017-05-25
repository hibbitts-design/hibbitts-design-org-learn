---
title: Hypothesis
taxonomy:
    category: docs
---

>>>Not using a Gantry 5 theme with Grav? No problem! There is also a [Hypothesis plugin](https://getgrav.org/downloads/plugins) available.

#### Download the Gantry 5 Atom
* Download and unzip the ['Hypothesis' Atom](https://github.com/hibbitts-design/grav-gantry5-particle-hypothesis/archive/master.zip).

#### Installing the Atom

Before installing and using the Atom, it is suggested you temporarily enable Gantry's [`Development Mode`](http://docs.gantry.org/gantry5/configure/extras)

1. Open the folder of your active Gantry theme. For example, if you are using the Hydrogen theme open the folder `/user/themes/g5_hydrogen`.
2. If a `custom` folder already exists open it, otherwise create it.
3. If a `particles` folder already exists within the `custom` folder open it, otherwise create it.
4. Upload `hypothesis.html.twig` and `hypothesis.yaml` files into the `/custom/particles` folder. For example, if you are using the Hydrogen theme copy the two particle files into `/user/themes/g5_hydrogen/custom/particles`.

#### Using the Atom
1. Add the Atom to your theme's 'Atoms' area on the 'Page Settings' panel.

#### Page Options
Once the particle is installed, Grav pages will support the following Page Header/FrontMatter option:

```
hide_hypothesis: true    # hide Hypothesis sidebar on this page
```
