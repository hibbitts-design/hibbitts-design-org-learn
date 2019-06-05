---
title: Installing the Grav CMS
taxonomy:
    category: docs
---

[plugin:youtube](https://www.youtube.com/watch?v=T-3qy6njFAw)

#### Video Transcript

Hello everyone! Today we’re going to be installing Grav on our server. In this tutorial, we’ll go over the installation the core Grav CMS with the Admin plugin.

Prerequisites
* Server (Apache, NGINX, IIS, etc.)
* PHP 7.1.3 or Greater

Before we can dive into the installation process, we need to have a web server handy running PHP 7.1.3 or higher.

Methods of Installing Grav
* Directly on File System (CPANEL, FTP, etc.)
* Command Line (Terminal, SSH)
* Hosting Service One-click Installation

Ideally, you will want to have access to the server’s file system either directly or remotely through a solution like CPANEL or FTP.

You can also install Grav using the server’s command line. Additionally, some hosting providers even provide a one-click installation option through their service that takes care of the whole installation process for you. Check with your hosting provider to see if this is an option for you.

Types of Grav Installations
* Core Grav + Admin
* Grav Skeleton
* Core Grav Without Admin (Advanced)

Let’s start by going over the different types of Grav packages you can install. You can choose the Core Grav with Admin package, which will give you everything you need to get started with Grav.

You can also pick up a skeleton package giving you everything the core grav and admin package includes, in a styled site pre-installed demo content, plugins, and a theme.

For advanced users that prefer to live in the command line, you can install Grav by itself.

The initial installation process for all three of these options is very much the same. In this video, however, we’ll stick to installing the core Grav and admin package.

##### Installation from a Zip File

You can do this directly through your operating system’s file manager if you have access to your server’s file system directly, or through a tool like CPANEL or FTP client.

**Step 1: Download the Grav Core + Admin Package**

Step 1 is simple. Just download the Grav + Admin package from GetGrav.org. You can find the latest version of Grav by hitting the Get Grav button on the home page, then selecting Grav Core + Admin Plugin.

You do have the option here to download a beta version of Grav Core and Admin which is a great solutionif you want the latest and most cutting-edge version of Grav and don’t mind beta testing new features.

Once you select the Grav Core + Admin Plugin link, you will download a zip file containing everything you need to get started.

**Step 2: Extract the Zip file in the Webroot of Your Server**

The next step is equally simple. Navigate to the webroot of your server and upload the ZIP file where you would like your Grav installation to reside. Then, extract the zip file.

You should have a folder named grav-admin containing several directories and other files. You can rename this directory or move its contents to a more specific location within your server. Just be sure to also move the HTACCESS file as it’s important to Grav and is hidden by default on many file managers.

**Step 3: Set Up the Administrator**

Your server-side work is done here. All you need to do now is open your browser and navigate to your new Grav site and set up the administrator.

You should see a page like this, with fields for your username, email address, and password. Filling these out will create an admin account for your site. This account will be how you log in and make changes in Grav’s admin, so we advise keeping the username and password memorable but not easy to guess.

Once you’ve done this, your Grav site is ready to go!
