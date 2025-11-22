---
layout: home
title: FPGA VGA Driver Project
tags: fpga vga verilog
categories: demo
---

Add a short welcome message or introduction here. Aim to get the viewer interested in what follows! Guideline: 1 or 2 sentences. 
# *The TV Screen LIES....!!!!*
Taking advantage of the refresh rate of the screen, essentially fooling our brains into thinking we see a complete image when actually we are watching a trace of RGB pixels turning on and off at different rates generating different colours which collectivly begin to build an image as the trace makes its way across and down the screen line by line until it gets to the end and returns to the start to repeat the process 
# This Web page is documenting the progress of my FPGA VGA Project

For my FPGA VGA project, initially I set up the project with the downloaded template files which displayed Colours cycling 

<"insert image">  
and then progressed to the second step to display colour stripes through the VGA I added rows and coloumns to the stripes Verilog code, see below updated code *`.row(row), .col(col)`*

<img src="https://github.com/FirstGit178/SoC_Lab_Week6/blob/8c119d26bccc3a40a8fc1c72d7f75620b280881b/docs/assets/images/VGACodeAlterationFMC.png">

## **Template VGA Design**
### **Project Set-Up**
Summarise the project set-up and design flow. 
This FPGA VGA Project is showning me at a code level how VGA displays operate. Taking advantage of the refresh rate of the screen, essentially fooling our brains into thinking we see a complete image when actually we are watching a trace of RGB pixels turning on and off at different rates generating different colours which collectivly begin to build an image as the trace makes its way across and down the screen line by line until it gets to the end and returns to the start to repeat the process 


Guideline 1 short paragraph.


 
<img src="https://github.com/FirstGit178/SoC_Lab_Week6/blob/8c119d26bccc3a40a8fc1c72d7f75620b280881b/docs/assets/images/VGAPrjSumFMC.png">

**Project Summary window**

### **Template Code**
Outline the structure and design of the Verilog code templates you were given. What do they do? Include reference to how a VGA interface works. Guideline: 2/3 short paragraphs, 

Verilog code templates are to display a colourCycle screen wash and then colours in rows and then in coloumns 
consider including screenshot(s).

### **Simulation**
Explain the simulation process. Reference any important details, include a well-selected screenshot of the simulation. Guideline: 1/2 short paragraphs.

### **Synthesis**
Describe the synthesis and implementation processes. Consider including 1/2 useful screenshot(s). Guideline: 1/2 short paragraphs.

### **Demonstration**
Perhaps add a picture of your demo. Guideline: 1/2 sentences.

## **My VGA Design Edit**
Introduce your own design idea. Consider how complex/achievabble this might be or otherwise. Reference any research you do online (use hyperlinks).

### **Code Adaptation**
Briefly show how you changed the template code to display a different image. Demonstrate your understanding. Guideline: 1-2 short paragraphs.

### **Simulation**
Show how you simulated your own design. Are there any things to note? Demonstrate your understanding. Add a screenshot. Guideline: 1-2 short paragraphs.

### **Synthesis**
Describe the synthesis & implementation outputs for your design, are there any differences to that of the original design? Guideline 1-2 short paragraphs.

### **Demonstration**
If you get your own design working on the Basys3 board, take a picture! Guideline: 1-2 sentences.

## **More Markdown Basics**
This is a paragraph. Add an empty line to start a new paragraph.

Font can be emphasised as *Italic* or **Bold**.

Code can be highlighted by using `backticks`.

Hyperlinks look like this: [GitHub Help](https://help.github.com/).

A bullet list can be rendered as follows:
- vectors
- algorithms
- iterators

Images can be added by uploading them to the repository in a /docs/assets/images folder, and then rendering using HTML via githubusercontent.com as shown in the example below.

<img src="https://github.com/FirstGit178/SoC_Lab_Week6/blob/8c119d26bccc3a40a8fc1c72d7f75620b280881b/docs/assets/images/VGAPrjSrcsFMC.png">
