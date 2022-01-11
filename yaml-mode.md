---
title: Yaml-mode
parent: Installation
nav_order: 2
---
# Installation for yaml-mode
This “theme” needs a little work and configuration before you can first use it, but don’t worry, we have made it as easy as possible. This “tutorial” shows you, how to set this “theme” up in yaml-mode until the first use.

Note: these are the installation instructions, if you use yaml-mode! We do not recommend UI-mode, but if you really need to go with it, than use these instructions.

Let’s get started!

What you should have before you start installing this “theme”
You should have a HomeAssistant (HA) instance running, preferrably with HACS installed and you should know the basics in using HA, eg. how to change settings in your lovelace configuration.
You have access to your config folder of HA. Doesn’t matter which way this is, but you need to be able to upload and change files in your config. If you’re running HA-OS or a supervised install of HA, we highly recommend the Samba AddOn (see the AddOn page for instructions) and for editing the File editor AddOn or a good editor like Notepad++ or SublimeText for your OS.
Prepare your HomeAssistant installation
To install this “theme” together with other themes in HA, you need to setup your configuration.yaml to use a themes folder.
Create a folder themes in your config folder
Add this under the section frontend in your configuration.yaml:
