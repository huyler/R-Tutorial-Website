---
date: "2020-04-17T00:00:00Z"
external_link: ""
image:
  caption: Photo by rawpixel on Unsplash
  focal_point: Smart
summary: Read this to learn how to create your own Temple-affiliated Xaringan Slides!
tags:
- Xaringan
title: Xaringan Tutorial
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""
authors: ["Timothy Laosiri"]
---


Hello extraordinary people! Welcome to the tutorial for creating your own Temple Xaringan Slides. If you are a undergrade or graduate student looking for an easy way to create your own Xaringan Slides, you've come to the right place! Simply follow these steps and you'll have your own one of a kind Xaringan Slides in no time.

# How to get started in RStudio!!!

**Step 1:** Download Rstudio or create an Rstudio account so you can log into your Rstudio.cloud account. Here, you should open a new project and title it so that you can remember where it is.

**Step 2:** Open a new project.

# How to install Xaringan!!!

**Step 1:** Go to your **Packages** tab and click on the Install tab to open your install packages window. Here you can type the word 'Xaringan' in the empty Packages space so you can install it to your **User Library**.

**Step 2:** Search for **Xaringan** within your user library and check it in the empty box next to its name.

# Open your Xaringan File!

**Step 1:** Click on **File**, click on **New File** then click to **RMarkdown**. This will cause a new window called **New R Markdown** to pop up.

**Step 2:** Click on the **From Template** and scroll down to a file named **Ninja Presentation** with **Xaringan** as the subname. 

**Step 3:** When popped up, You can view the **Xaringan** file itself by clicking on the **Knit** tab. You need to create a file name for it, I would recommend the name with special symbols or spaces.

# Editing Title Slide

**Step 1:** Edit the YAML (beginning of the document) with your title, author name, institute, date. Including the Subtile is optional.

*Tip: It is helpful to try to knit your file every few times you change the file, this is so that you can check if your Slides are able to pop up without any errors. Think of this as a save checkpoint.*

# How to format your Xaringan Slide?

**Step 1:** To create a slide page, you need to start by typing "- - -" from top to bottom between what you wrote in the slides.

**Step 2:** To format the slide have a dark background, first type "class: inverse" . You can also add "center, middle"" and etc to have your texts be formated according to the class function.

**Step 3:** To have the each sentence within the slide pop up one of a time, you need to type "- -" in a new line.

**Step 4:** To put spaces between your sentences, type "<br>" two times. One on top and the second below it from the neighboring sentence you wrote for the slide.


# Font Sizes & Themes

**Step 1:** You can change the font size of single words, sentences or complete slides by defining two new classes in **my-theme.css** which change the font size relative to its default. Here, they are named .small and .large:

*Example: .large { font-size: 130% } & .small { font-size: 70% }*
 
**Step 2:** If you want to have your slide be in a different font and color design, type "css:" You can look up various themes in the Xaringan's Wiki!

*Example: [default, metropolis, metropolis-fonts]*

**Step 3:** You can also bold words and sentences on a slide by typing "****Example***".

*Note: The star symbol is supposed to be type two times per side of a word in order to bold a word or sentence*

# Add Links to the Slide!

**Step 1:** To add impliment a link to one of the words on your slide, you need to type "[]()"

*Example: [The Wiki](https://github.com/yihui/xaringan/wiki)*

# How to add images on a slide?

**Step 1:** Type "background-image: url()"

**Step 2:** If you want to determine the image's size, type "background-size:"

**Step 3:** To determine the image's position on the slide, type "background-position:" 
*Note: Experiment with the numbers and percentage, this will help to be familiar with it.*

*Example: background-image: url(https://upload.wikimedia.org/wikipedia/commons/b/be/Sharingan_triple.svg)*
*background-size: 100px*
*background-position: 90% 8%*

# You're all done!

That's the end of this basic tutorial!!! All credit goes to Yihui Xie, creator of Xaringan!!! Master the Xaringan!!!
