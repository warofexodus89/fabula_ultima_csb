# Fabula Ultima Templates for Foundry VTT v10

<p align="center"><img src="../media/fabula-ultima-cover.webp"></p>

**Dislaimer:** These templates are **NOT** official. I personally use them in my own games but it can be used as a basic character sheet for new players trying out the game. As of current release, the template only caters for the **base game**. So feel free to draw inspiration from it to apply to your own CSB sheets (or modify it for your own use)! :)

You can find both PC/NPC and item templates under '**Templates**'. The CSS file is mostly meant for styling the PC template; though you might notice some of it applying to the item templates as well (it still look pleasant!).

There will be updates and changes to the templates as I improve on it to cater for my own game sessions.

## Table of Contents

- [1. Dependencies](https://github.com/warofexodus89/fabula_ultima_csb/edit/main/README.md#1-dependencies)
- [2. Installation](https://github.com/warofexodus89/fabula_ultima_csb/edit/main/README.md#2-how-to-use-this-module)
- [3. Downloading the CSB templates](https://github.com/warofexodus89/fabula_ultima_csb/edit/main/README.md#3-downloading-the-csb-templates)
- [4. Using the CSB templates](https://github.com/warofexodus89/fabula_ultima_csb/edit/main/README.md#3-using-the-csb-templates)
  - [4.1  Creating a new world](https://github.com/warofexodus89/fabula_ultima_csb/edit/main/README.md#31-creating-a-new-world)
  - [4.2 Importing the template](https://github.com/warofexodus89/fabula_ultima_csb/edit/main/README.md#32-importing-the-template)
  - [4.2 Styling the sheets](https://github.com/warofexodus89/fabula_ultima_csb/edit/main/README.md#33-styling-the-sheets)
- [5. Frequently asked questions](https://github.com/warofexodus89/fabula_ultima_csb/blob/main/README.md#5-frequently-asked-questions)
  

## 1. Dependencies

The template runs on **Custom System Builder**. You will need to install this using the manifest URL.

- [Custom System Builder](https://gitlab.com/custom-system-builder/custom-system-builder/-/tree/main#how-to-install-the-system)

**Note:** This sheet works on non-beta version of CSB. I can't guarantee that it will work properly on the beta version.


## 2. How to use this module?

The **Custom System Builder** (aka **CSB**) allows you to create custom sheets for Actors (PC and NPC) and Objects (accessories, armors and weapons). Through this functionality you will also be able to import templates found in this repository to create:

- Your PC and NPC sheets
- Accessories and armor sheets that can be attached to the PCs

It is very important to note that Templates should **NOT** be used as fillable sheets, they are used to generate new Actors or Objects sheets.

## 3. Downloading the CSB templates

In case you can't find it, you can download the ZIP file by clicking on the green "**Code**" button.

![image](https://github.com/warofexodus89/fabula_ultima_csb/assets/4443200/397bc943-e0f7-455c-bfb4-cd217c3db2e5)


## 4. Using the CSB templates

### 4.1 Creating a new world

To get things started, first you will need to install CSB (you can find the link under Dependencies). Once CSB is installed, create a new world using CSB as the system.

<p align="center"><img src="../media/create_world.png"></p>

Once the world is created you are ready to import the templates.

### 4.2 Importing the template

https://github.com/warofexodus89/fabula_ultima_csb/assets/4443200/751859fd-51c3-4134-b9d8-e9bf075359bb

**Note:** If the template is blank after importing, try closing and reopening Foundry again as a workaround.

### 4.3 Styling the sheets

You got your template to show but you are not done yet! You still need to install the CSS to make it fancy! By default, Foundry doesn't auto detect CSS files (no idea why, security reasons maybe?). So you will have to manually specify the CSS file.

https://github.com/warofexodus89/fabula_ultima_csb/assets/4443200/42decde1-3fa2-434d-9e7c-3d7cf4e98a4b

Press F5 to refresh your Foundry so that it will load your CSS file. It's good to note that you have to trigger a refresh everytime you make changes to your CSS file (especially when you start tempering with the CSS) for the changes to show.

...And with that you are done! Feel free to check out the [wiki](https://github.com/warofexodus89/fabula_ultima_csb/wiki) if you want to learn more on how to use and customize the sheet!

## 5. Frequently asked questions

### 5.1 My gears doesn't appear after dragging them into the character sheet!

**Answer:** Most likely due to the item container filters not being imported over with the templates. Here is what you need to do:

1. Go to the "__Fabula Ultima PC template_".
2. Navigate to the tab with faulty item container and click on it.
3. At the item container window, ensure that right templates are selected in the filter section.

![image](https://github.com/warofexodus89/fabula_ultima_csb/assets/4443200/f3ab01cf-a804-4181-88a8-d526357e7119)

When it comes to missing equipped items, this is always the main culprit.

### 5.2 The sheet is too big or profile picture on the sheets is too big!

**Answer:** The size of the sheet is fixed to accomodate the components on the sheet but if you want to adjust you can still do so from **"Configure sheet display"** on the respective templates!

![image](https://github.com/warofexodus89/fabula_ultima_csb/assets/4443200/8b96a6c3-a32b-474f-be99-3eb42279a2bd)
