Open Hardware Project Template
=======================================================

This repository will serve as a base template to facilitate the documentation of Open Hardware projects.

The proposed structure of folders within this template is based on the 'Best Practices for Open-Source Hardware' document published by the Open Source Hardware Association.
http://www.oshwa.org/sharing-best-practices/

You are free to modify this document as it best suits your needs, by overwriting the text on each paragraph and adding any information or extra files that you consider useful.

You can start by deleting this section, including this line of text.


Name of Your Project
=====================

Write here a short description (two or three paragraphs long) on which you define: What is your project? What is it good for? How do you make it work?

Try not to use technical jargon or complicated words. Remember that people who will read your description might not have the same level of expertise, or they might not be on the same field of knowledge as you.

Explain how you expect your project to work. It is not necessary, however, that you write every little detail of its functioning. If you need to present a more detailed explanation of your project, we recommend you post a link to a website or another .txt file inside of the 'docs' folder.

To make your documentation more useful, indicate the level of development of your project. Some indicators could be: "stable", "beta", "incomplete" or "barely working".

You can also add to this section the corresponding credits in case your project is a derivative work from another project. You can also add the names or pseudonyms of the people who contributed to your project, the type of copyright/patent license and last date of modification.


Latest Additions
=================

Add to this section the last relevant changes or corrections that you have made to your project. It is important that you notify about changes that modify the behavior of your project or the outputs that you expect it to generate.

Here's an example of changes to the latest version '0.1alpha':

* Text examples added
* Version numbers added

Corrections:

* Typos corrected

You don't need to write down the whole history of changes. Instead, you can make a new file in this folder named 'changelog.txt' with a list of all the changes made (preferably on inverse chronological order):

> You can check the complete log change history in the file 'changelog.txt'.

BOM/Cost Estimate
=========================

If the bill of materials for this project is very short you can put it right here. Otherwise, you can create a file named 'bom.csv' or any spreadsheet file where you can detail the bill of materials and costs. Try to use open formats as much as possible (share an .ods formatted file instead of an Excel .xls file, for example).

Requirements
=============================

Use this section to detail what is required in order to make your project work. You need to put the requirements or previous needs for software in order to make it work, or the tools that are needed to build it.

We give you an example.

Software requirements:
* Arduino IDE

Required tools:
* Cable cutter


Construction and Use
==================

If the construction procedure is simple, you can write it down in this section. However, if you think it will need more details, you can create a file named 'build.txt' where you can elaborate on the construction procedure details.

Likewise, if the procedure for utilizing the associated software to the project is simple you can write down the details in this section. If said instructions are too long, you can create a file named 'usage.txt' and reference it from this section.


Folders
========

The folder structure is very important for your project, because it will allow you to organize your projects and will also allow others to easily share changes or improvements. This structure isn't set in stone, however, so you can modify it so it suits your needs.

Remember that inside every folder we strongly recommend you to include a file named 'readme.txt' where you can describe its contents.

Within the folder structure we recommend to include at least the following folders:

* *doc*: Use this folder to enter all the documentation that you consider as necessary for your project. We recommend that you use free/open formats such as .odf or .txt files. If you wish to create it as a web page, name your main page as 'index.html' so it can be easily accessed in case someone copies the contents of the folders into a web server.
* *src*: Place into this folder all the control software's source code for your Open Hardware project. If you use an IDE such as Eclipse or Arduino, copy your project's folder inside the src folder.
* *dsn* / *design*: Put all files relevant to the design inside of this folder.
  +  *main*: Inside of this folder you can put the original design files that may include, but are not limited to: 2D drawings, 3D designs, CAD files, component libraries and additional blueprints or technical drawings.
  +  *aux*: Put in here all the auxiliary design files that may help to build your project. Design auxiliary files may include 2D or 3D designs saved on data interchange formats, additional technical drawings, manufacture-ready formats, or additional graphic drawings.
* *extra*: This is a folder for the remaining files. Here you can leave other files that may be required to manufacture your project or to make it work. You can add here, for example, a controller driver for a specific device, or links for relevant software, photos or videos.

Acknowledgment of Responsibility/Liability Waiver
==============================

We recommend you to add a text similar to this in your projects:

> The following project is shared "as is", with the sole objective of being useful. The creator(s) of the described piece of hardware and its associated software cannot guarantee its correct functioning under any circumstance. The author(s) of this project will not be held responsible for any material, personal or economic loses to you or any third parties that may arise from using this design. This project will not be used under any circumstances on systems whose responsibility is critical, or from which people's lives depend on, directly or indirectly.


Licensing
==============

Add here the license that your project's source code has been subjected to. We would also love it if you add the attribution note for the template at the end of this file.

> This README.md template has been developed by the openhardware.sv community in order to make project documentation easier. This template has been protected under a CC BY license. You can modify it and redistribute it as long as you keep this author attribution note.
