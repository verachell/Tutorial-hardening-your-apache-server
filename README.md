# Tutorial-hardening-your-apache-server
A step by step tutorial of some changes to make to the default Apache installation on a Linux VPS server. For beginners

This tutorial follows on from https://github.com/verachell/tutorial-setup-linux-VPS-server-with-apache and assumes you have completed the steps in that tutorial. At this point, you should have a VPS server with Apache installed, SSL certificates installed, and the Webmin control panel installed. If you don't have Webmin you can do the steps in this tutorial from the command line, editing configuration files directly, but that part is up to you. The tutorial here makes as much use of Webmin as possible.

Please read this README file completely before moving on to the tutorial (in this repo's Wiki - link below)

## These settings are not suitable for every application
These settings are my defaults for many of the applications I use, but they won't be suitable for every application. In particular, some of the settings in this tutorial will NOT work with Rails. 

What constitutes a suitable level of security for your application is up to you. As the license says, I am not responsible for any damages, security breaches, etc from any security holes in the setup in this tutorial. 

It is up to YOU to ensure your server is set up appropriately and securely for YOUR purpose.

I have made a good faith effort to ensure sensible choices are made, but understand that this tutorial is just an example of things to change in Apache after installation. You may need to make different changes, and/or further changes beyond those listed in this tutorial to achieve your desired security profile.

