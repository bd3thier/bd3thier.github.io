---
layout: post
title: Sharing code on GitHub - RStudio vs. Jupyter Notebooks
subtitle: User-, reader-, and collaborator-friendliness
cover-img: /assets/img/mimi-thian-vdXMSiX-n6M-unsplash.jpg
tags: [RStudio,Jupyter,Python,R,GitHub,Portfolio,Data Science,Tutorial]
comments: true
---

Cover image by [Mimi Thian](https://unsplash.com/@mimithian?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText) on [Unsplash](https://unsplash.com/s/photos/share?utm_source=unsplash&amp;utm_medium=referral&amp;utm_content=creditCopyText)

Times and times again, you've heard it: a good portfolio is what will get you that great job in the technical field you're diving into. You worked hard on your project, and made sure it was great in substance and form. You polished your code, commented so anyone could understand, and it's time to showcase your work. Here is how to upload your code to GitHub if you used Jupyter Notebooks and RStudio, respectivey (arguably the most popular Data Science programming languages and IDEs out there). We will go over the pros and cons as a user, for your readers, and if you intent to collaborate (which is what GitHub is for). Buckle up! 


1. Python - Jupyter Notebooks

Files with extension .ipynb can be uploaded directly to GitHub repositories. The output of the cells as well as their statuses will be the exact same as in the notebook when you saved it. 

On GitHub, the rendering will be exactly as in your Notebook (without interactivity, duh!) So convenient and easy! It also means that you need to run your entire notebook at once for clean outputs, and that can be tricky for code that needs hours to execute. The files can also get large depending on the amount of visuals in the doc.

![Download](assets/img/ipynb-download.png)
To be able to run cells, a collaborator would have to follow the following steps:
* Download the raw file and save with the extension .ipynb 
* Open Jupyter Notebook, then go to the location where the .ipynb file was saved
* Open the file and start working (if there are any dependencies, don't forget to place them where they belong - a data folder for example)
* Save the file once modified

After that, the collaborator can upload and commit the file to GitHub. It's straight forward, but not a direct collaboration in GitHub.


2. R - RStudio



