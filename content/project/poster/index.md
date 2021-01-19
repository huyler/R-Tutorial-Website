---
date: "2020-04-19T00:00:00Z"
external_link: ""
image:
  focal_point: Smart
links:
- icon: file-download
  icon_pack: fas
  name: Poster Example
  url: "/img/Posterdown.png"
- icon: file-archive
  icon_pack: fas
  name: Download Zip File
  url: "/zip/Posterdown.zip"
summary: Read this to learn how to create your own Temple-affiliated poster!
tags:
- poster
title: Poster Tutorial
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""
authors: ["preston", "timothy"]
---


Welcome. Here is a template for an academic poster, which can be used for a variety of applications. Posterdown was created by Brent Thorne.

# Uploading the file

**Step 1:** Download Rstudio or log into your Rstudio.cloud account. Here, you should open a new project and title it so that you can remember where it is. If you need help with this step, refer the the R Markdown tutorial located [here](https://chuyler.shinyapps.io/final_projcet_final/#section-lets-learn-r).

**Step 2:** Download the .zip file linked at the top of this article.


**Step 3:** Open a new project. On RStudio, use the upload button (shown below) to upload the .zip file. 

{{< figure library="true" src="Upload.png" lightbox="true" >}}

**Step 4:** Once you have uploaded the .zip file, open the Posterdown folder. Then, click on the *Posterdown.Rproj* file and click "yes" to open the project.

# Install necessary packages

This template only requires the package posterdown. You can install posterdown by copying the following code and running it in console.

install.packages("posterdown")

# Choosing the template style

There are several styles of posters that Brent Thorne has included. Of these are html, betterland, and betterport.

Landscape Orientation: 
- posterdown_html 
- posterdown_betterland 

Portrait Orientation: 
- posterdown_betterport 

**Step 1:** Go to File > New File > R Markdown.

**Step 2:** Choose "from template" and choose a {posterdown} template. Please explore each template or visit Brent Thorne's Github for more information:

https://github.com/brentthorne/posterdown#getting-started

# Start editing your poster

**Step 1:** Open the Poster file, and then the *Poster.Rmd* file.

**Step 2:** To ensure that your packages are all in line, press the "knit" button at the top of the script.

*If you get a pop-up saying you need more packages, say "yes" to install the necessary packages.*

# Editing the YAML

**Step 1:** Edit the YAML (beginning of the document) with your title, author name, and University.

*Tip: It is helpful to try to knit your document every few times you change the document, just so that you don't finish the whole dissertation and then find out something is wrong.*

# A majority of editing templates involves...

Copy-paste and tweak! Let us explore how to replace the main image in the template.

**Step 1:** Find an image you want online.

**Step 2:** Simply paste the image url into the template replacing the old url. The location of the main center image may be found in the YAML under main findings. You may also replace the bottom two images.

**Step 3:** If you want to insert an image into Posterdown, refer to our template and examine how it is properly formatted. Images may also be uploaded to Rstudio Cloud into the project's working directory. From there, the filename of the image is simply used instead of the image url.


# Changing poster color

**Step 1:** Locate in the YAML Primary_color, Secondary_color, accent_color

**Step 2:** These data values use a hexadecimal scale to display color. Insert whatever color you please. Even basic names for colors like "red" or "blue" work!

# You're all done!

Thank you for reading my blogpost on how to make your own Poster! The task may seem daunting, however learning R is a fantastic and versatile skill.

Please visit Brent Thorne's GitHub for more information and resources.

https://github.com/brentthorne/posterdown

Brent Thorne has streamlined the customization process, giving your poster the perfect look for school clubs and events. Please refer to the following page for more YAML options:

https://github.com/brentthorne/posterdown/wiki/posterdown_betterland