# Topical Lectures, Controls 2021
Material for Nikhef topical lectures 2021

Andreas Freise, Bas Swinkels 13.04.2021

This repository provides the material for the hands-on session on control system.

All the work in this module will be done with Python inside Jupyter notebooks. We provide you with several notebooks which contain task descriptions and suggestions. You will then complete the task by working inside the notebook.

## Installing Jupyter and Python
We expect you to have installed Python and Jupyter as described in the file: [SoftwareInstall.pdf](https://raw.githubusercontent.com/freise/controls_2021/main/SoftwareInstall.pdf)

Download all files from this repository, store them in the same folder and open the notebooks listed below with Jupyter.

If you cannot install Python and Jupyter on your own computer you can still follow parts of the course by using [Google Colab](#colab), however this is not recommended and we cannot provide help with the Google Colab system.

## The course material

The work is divided into 6 notebooks that you should work through in sequence:

 * **student0_example_notebook.ipynb**: a simple example, to step you through the basics of using a Jupyter notebook. If you are already familiar with Jupyter you should skip this notebook. 
 * **student1_keyboard.ipynb**: a quick interactive demonstration of the drone model code
 * **student2_system_identification.ipynb**: In this notebook you will perform experiments to measure specific parameters of your virtual drone.
 * **student3_basic_control.ipynb**: Now we design and test simple feedback control systems for the drone.
 * **student4a_racing.ipynb**: Here we will find out if our controls are fit for purpose: race your drone through a track and compare your time with others!
 * **student4b_racing_noninteractive.ipynb**: This is a non-interactive version of the race, which is a bit more difficult.

### <a name="colab"></a> Running the notebooks in Google Colab

If you cannot install Python and Jupyter on your own computer, you can run some of the provided notebooks online, using the Google Colab project. Do do that follow the link to open one of the notebooks. You will need a Google account to save your work to Google Drive.

https://colab.research.google.com/github/freise/controls_2021/

You cannot run the following notebooks because Colab does not provide the QT interface for interactive plots:
 - student1_keyboard.ipynb
 - student4a_racing.ipynb

The following notebooks will work:
- student2_system_identification.ipynb
- student3_basic_control.ipynb
- student4_advanced_control.ipynb
- student4b_racing_noninteractive.ipynb

You must add a new code cell in the top of each notebook and add (and execute) this command:

```!wget https://raw.githubusercontent.com/freise/controls_2021/main/module.py```

