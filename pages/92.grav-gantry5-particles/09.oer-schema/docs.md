---
title: OER Schema
taxonomy:
    category: docs
published: false
---

The ['OER Schema' Atom](https://github.com/hibbitts-design/grav-gantry5-atom-oer-schema) provides initial support for [OER Schema](http://oerschema.org/).

#### Download the Atom
* Download and unzip the ['OER Schema' Atom archive](https://github.com/hibbitts-design/grav-gantry5-particle-oer-schema/archive/master.zip).

#### Installing the Gantry 5 Atom

Before installing and using the Atom, it is suggested you temporarily enable Gantry's [`Development Mode`](http://docs.gantry.org/gantry5/configure/extras)

1. Open the folder for your active theme in the `user/data/gantry5/themes/` folder of your Gantry installation. For example, if you are using the Helium theme open the folder `user/data/gantry5/themes/g5_helium`.
2. If a `particles` folder already exists within the theme folder open it, otherwise create it.
3. Upload `oer_schema.html.twig` and `oer_schema.yaml` files into the `particles` folder. For example, if you are using the Helium theme copy the two particle files into `user/data/gantry5/themes/g5_helium/particles`.

#### Using the Atom
1. Add the Atom to your theme's 'Atoms' area on the 'Page Settings' panel.

#### Setting Your Site Body Tags

1. Go to the `Page Settings` for your active Gantry theme.
2. Create a new `Tag` with the `Key` = `Prefix` and `Value` =`oer: http://oerschema.org/`
3. Press the `Save Page Settings` button.

## Particle Options
!['OER Schema' options](https://github.com/paulhibbitts/github-repo-images/blob/master/oer-schema-options.png?raw=true)
