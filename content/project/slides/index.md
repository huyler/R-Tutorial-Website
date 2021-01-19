---
date: "2020-04-19T00:00:00Z"
external_link: ""
image:
  focal_point: Smart
links:
- icon: file-download
  icon_pack: fas
  name: Slides Example
  url: "/pdf/xaringan.pdf"
- icon: file-archive
  icon_pack: fas
  name: Download Zip File
  url: "/zip/AdaptTemplateSlide.zip"
summary: Read this to learn how to create your own Temple-affiliated slides!
tags:
- slides
title: Slides Tutorial
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""
authors: ["timothy"]
---


Welcome to the tutorial for creating your own Temple Xaringan Slides. If you are a student looking for an easy way to create your own slideshow presentation, you have come to the right place. Simply follow these steps and you will have your own one of a kind Xaringan Slides in no time.

# How to get started in RStudio

**Step 1:** Download Rstudio or create an Rstudio account.

**Step 2:** Open a new project and title it so that you can remember where it is.

{{< figure library="true" src="project.png" lightbox="true" >}}

# How to install Xaringan

**Step 1:** Go to your **Packages** tab and click on the Install tab to open your install packages window. Here you can type the word 'Xaringan' in the empty Packages space so you can install it to your **User Library**.

{{< figure library="true" src="packages.png" lightbox="true" >}}


**Step 2:** Search for **Xaringan** within your user library and check the empty box next to its name.

# Open your Xaringan File

**Step 1:** Click on **File**

**Step 2:** Click on **New File**

**Step 3:** Click on **RMarkdown**. This will cause a new window called **New R Markdown** to pop up.

{{< figure library="true" src="rmarkdown.png" lightbox="true" >}}


**Step 4:** Click on **From Template** and scroll down to a file named **Ninja Presentation** with **Xaringan** as the subheading.

**Step 5:** You can view the **Xaringan** file itself by clicking on the **Knit** tab. You need to create a file name for it.

{{< figure library="true" src="ninja.png" lightbox="true" >}}

# Editing Title Slide

**Step 1:** Edit the YAML (beginning of the document) with your title, author name, institute, and date. Including the Subtile is optional. If you need a refresher on how to
navigate the YAML, look at our [R Markdown tutorial](https://chuyler.shinyapps.io/final_projcet_final/#section-how-to-write-in-r).

*Tip: It is helpful to try and knit your file every few times you change the file, so you can check and
make sure everything is working properly.*

# How to format your Xaringan Slide

**Step 1:** To create a slide page, you need to start by typing "- - -" from top to bottom between what you wrote in the slides.

**Step 2:** To format the slide to have a dark background, first type "class: inverse" . You can also add "center, middle"" and etc to have your texts be formated according to the class function.

**Step 3:** To have each sentence within the slide pop up one at a time, you need to type "- -" in a new line.

**Step 4:** To put spaces between your sentences, type "<br>" two times. One on top and the second below it from the neighboring sentence you wrote for the slide.


# Font Sizes & Themes

**To change font size:** You can change the font size of single words, sentences, or complete slides by defining two new classes in **my-theme.css** which change the font size relative to its default. Here, they are named .small and .large:

```
.large { font-size: 130% } & .small { font-size: 70% }

``` 
**To change font:** If you want to have your slide be in a different font and color design, type "css:" You can look up various themes in the Xaringan's Wiki!
```
[default, metropolis, metropolis-fonts]
```

**Bolding:** You can also bold words and sentences on a slide as shown below.

```
**Example Text**
```

# Add Links to the Slide

**Step 1:** To add a link to one of the words on your slide, you need to type "[]()".

```
[The Wiki](https://github.com/yihui/xaringan/wiki)
```
# How to add images on a slide

**Step 1:** Type "background-image: url()".

**Step 2:** If you want to determine the image's size, type "background-size:".

**Step 3:** To determine the image's position on the slide, type "background-position:" 
*Note: Experiment with the numbers and percentage, this will help to be familiar with it.*
```
background-image: url(https://upload.wikimedia.org/wikipedia/commons/b/be/Sharingan_triple.svg)
background-size: 100px
background-position: 90% 8%
```
# You're all done!

That's the end of this basic tutorial. All credit goes to Yihui Xie, creator of Xaringan. 