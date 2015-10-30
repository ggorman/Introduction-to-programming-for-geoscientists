---
layout: post
title:  "Lecture 1"
date:   2015-10-15 14:10:00
categories: Lecture notes
---

The lecture is written in IPython notebook format. You will quickly see that you can edit these notebooks yourself to add your own notes and do the exercises. You can view it directly using
[nbviewer](http://nbviewer.ipython.org/github/ggorman/Introduction-to-programming-for-geoscientists/blob/master/notebook/Lecture-1-Introduction-to-programming-for-geoscientists.ipynb) or [download the notebook here](http://raw.githubusercontent.com/ggorman/Introduction-to-programming-for-geoscientists/master/notebook/Lecture-1-Introduction-to-programming-for-geoscientists.ipynb) (Note: you may need to right-click and use *Save Link As...*).

### Initial setup
We recommend that you download the notebooks for the lecture and store them in the H: drive. 

1. Create a folder on the H: drive called `notebooks` (or any other sensible name) in the file explorer:
![Create a new folder](https://raw.githubusercontent.com/ggorman/Introduction-to-programming-for-geoscientists/gh-pages/images/new_folder_on_h_drive.jpg "Create a new folder called 'notebooks' on your H: drive.")

2. At the beginning of each lecture, download the relevant `.ipynb` file and place it in this folder. Once you've saved the notebook, you can open it in one of two ways in the computer lab, each of which are described in the following sections. Both of these solutions will also work on your personal computer, and you can download the software needed to do this for free.

### [Enthought: Canopy](https://www.enthought.com/products/canopy/)
1. Go to the Windows Start menu and start the Canopy *Code Editor*:<br>
![Canopy menu item](https://raw.githubusercontent.com/ggorman/Introduction-to-programming-for-geoscientists/gh-pages/images/canopy_menu_item.jpg "The Canopy menu item in the Windows Start menu.")

2. If asked, change the folder that you want to work with to your `H:\notebooks` folder:
![Canopy change folder](https://raw.githubusercontent.com/ggorman/Introduction-to-programming-for-geoscientists/gh-pages/images/canopy_change_directory.jpg "Changing the Canopy working directory.")

3. Click *File* > *Open*, and select the .ipynb notebook file(s) that you want to open.

4. If the mathematical formulae are hard to read, right-click on any formula, and select *Math Settings* > *Scale All Math...* and set the value to 200%.
![Scale mathematical formulae](https://raw.githubusercontent.com/ggorman/Introduction-to-programming-for-geoscientists/gh-pages/images/scale.jpg "Scale mathematical formulae.")

### [Continuum Analytics - Anaconda](https://store.continuum.io/cshop/anaconda/)
1. First, we strongly recommend setting your default browser to Google Chrome or Firefox. In Firefox, go to *Tools* > *Options* > *Advanced* tab, and click the *Make Firefox the default browser* button. In Chrome, go to the *Settings* window and click *Make Google Chrome the default browser*.

2. From the Windows Start menu, search for and open the `cmd` command line tool:
![cmd](https://raw.githubusercontent.com/ggorman/Introduction-to-programming-for-geoscientists/gh-pages/images/cmd_menu_item.jpg "The cmd command line tool.")

3. At the command line, type the following 3 commands, pressing Enter after each one:<br>
```
H:
```<br>
```
cd notebooks
```<br>
```
ipython notebook
```<br>
This will start up IPython Notebook in your default web browser. From there you should see the `.ipynb` files that you have saved in the `notebooks` folder.

