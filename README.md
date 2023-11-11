# Fabula Ultima Templates for Foundry VTT v11

![image](https://github.com/warofexodus89/fabula_ultima_csb/assets/4443200/98e24042-307e-4551-8375-5dc187e565c3)

**Dislaimer:** These templates are **NOT** official and does not support Foundry version **before v11**. I personally use them in my own games but it can be used as a npc/character sheet for new players trying out the game. As of current release, the template only caters for the **base, high fantasy, natural fantasy and technofantasy book (excluding technosphere support)**. So feel free to draw inspiration from it to apply to your own CSB sheets (or modify it for your own use)! :)

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
  - [5.1 The sheet is too big or profile picture on the sheet is too big! ](https://github.com/warofexodus89/fabula_ultima_csb/blob/main/README.md#52-the-sheet-is-too-big-or-profile-picture-on-the-sheet-is-too-big)
  - [5.2 The equipment section is missing on new character sheets ](https://github.com/warofexodus89/fabula_ultima_csb/blob/main/README.md#52-the-equipment-section-is-missing-on-new-character-sheets)

## 1. Dependencies

The template runs on **Custom System Builder**. You will need to install this using the manifest URL.

- [Custom System Builder](https://gitlab.com/custom-system-builder/custom-system-builder/-/tree/main#how-to-install-the-system)

I will also suggest to go through the wiki if you want to learn more in-depth sheet customization. Their Discord is also very active. If you have questions on modification (which you will have), do join the Discord to ask the devs themselves!

**Note:** This sheet works on non-beta version of CSB. I can't guarantee that it will work properly on the beta version.


## 2. How to use this module?

The **Custom System Builder** (aka **CSB**) allows you to create custom sheets for Actors (PC and NPC) and Objects (accessories, armors and weapons). Through this functionality you will also be able to import templates found in this repository to create:

- Your PC and NPC sheets
- Items, potions, utilities and accessories and armor sheets that can be attached to the PCs

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

### 5.1 The sheet is too big or profile picture on the sheet is too big! Can I adjust it?

**Answer:** The size of the sheet is fixed to accomodate the components on the sheet but if you want to adjust you can still do so from **"Configure sheet display"** on the respective templates!

![image](https://github.com/warofexodus89/fabula_ultima_csb/assets/4443200/8b96a6c3-a32b-474f-be99-3eb42279a2bd)

### 5.2 The equipment section is missing on new character sheets

![image](https://github.com/warofexodus89/fabula_ultima_csb/assets/4443200/5b4b2964-8c20-4d6a-97ae-0dcb3b16d35d)

Newly generated character sheets might be missing the equipment section. 

- You will need to navigate to the 'Class features' tab. If you do not see this tab, you will need to uncheck and check the 'Class features' checkbox at the settings tab (cogwheel icon). ![image](https://github.com/warofexodus89/fabula_ultima_csb/assets/4443200/72ab097f-0cef-4d6d-941e-80fabddfe906)
- At the 'Class features' tab, check 'Vehicle'. This will unlock the mount button at the 'Inventory' tab. ![image](https://github.com/warofexodus89/fabula_ultima_csb/assets/4443200/00ffffb1-471d-4959-85dc-ed24160a8539)
- Click the 'Mount' button. This should show the equipment and personal vehicle section to show again. Toggle the 'Mount' button so that it shows the equipment section. ![image](https://github.com/warofexodus89/fabula_ultima_csb/assets/4443200/95d030b8-c9d9-465f-85e7-cba6492836e0)
- (Optional) Uncheck 'Vehicle' checkbox if you are not character is not a Pilot.

  
