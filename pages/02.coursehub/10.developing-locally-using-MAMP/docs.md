---
title: Developing Locally with MAMP
taxonomy:
    category: docs
---

If you have not yet installed and configured the Course Hub on your Webserver please do that before continuing.

##### 1. Download and install MAMP

![][1]

[1]: ../../images/course-hub-with-git-sync---desktop-development/download-and-install-mamp.png

##### 2. Download Course Hub skeleton package

From the getgrav.org site at [https://getgrav.org/downloads/skeletons](https://getgrav.org/downloads/skeletons) or via this direct link: [http://hibbittsdesign.org/blog/downloads/grav-skeleton-course-hub-site.zip](http://hibbittsdesign.org/blog/downloads/grav-skeleton-oer-content-space-site.zip)

##### 3. Extract the downloaded ZIP archive and copy folder to the "htdocs" folder within your MAMP application folder

##### 4. Launch MAMP, start the MAMP server and view the Course Hub in your "htdocs" folder

##### 5. Download and Install a Symbolic Link Maker

###### 5.1 For Mac, download and install SymbolicLinker

From the MacUpdate site at [https://www.macupdate.com/app/mac/10433/symboliclinker](https://www.macupdate.com/app/mac/10433/symboliclinker)

###### 5.2 For PC, download and install Link Shell Extension

From the software author's site at [http://schinagl.priv.at/nt/hardlinkshellext/linkshellextension.html.](http://schinagl.priv.at/nt/hardlinkshellext/linkshellextension.html) More information is available at [https://www.howtogeek.com/howto/16226/complete-guide-to-symbolic-links-symlinks-on-windows-or-linux/](https://www.howtogeek.com/howto/16226/complete-guide-to-symbolic-links-symlinks-on-windows-or-linux/)

##### 6. Download and Install GitHub Desktop

![][2]

[2]: ../../images/course-hub-with-git-sync---desktop-development/download-and-install-github-desktop.png

##### 7. Go to your own Course Hub GitHub repository

##### 8. Tap "Clone or download" and then choose "Open in Desktop"

##### 9. Choose where to save the cloned repository and tap "Clone"

##### 10. Open the folder holding the cloned Course Hub repository on your computer

##### 11. Create a symbolic link for the "pages" folder, move it to your desktop, and then name this link "pages"

##### 12. Create a symbolic link for the "themes" folder, move it to your desktop, and name this link "theme"

##### 13. Replace the "pages" folder within your local install of Course Hub with the newly created "pages" symbolic link on your desktop

##### 14. Replace the "themes" folder within your local install of Course Hub with the newly created "themes" symbolic link on your desktop

Congratulations! You now have a local copy of your own Course Hub running.
