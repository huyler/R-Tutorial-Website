---
date: "2016-04-27T00:00:00Z"
external_link: ""
image:
  caption: Photo by rawpixel on Unsplash
  focal_point: Smart
summary: Read this to learn how to create your own Temple-affiliated dissertation!
tags:
- APA Article
title: APA Article Tutorial
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""
authors: ["preston"]
---

Welcome. Here is a template for an APA article tailored for Psychology students at Temple University.

# Uploading the file

**Step 1:** Download Rstudio or log into your Rstudio.cloud account. Here, you should open a new project and title it so that you can remember where it is.

**Step 2:** Download the .zip file [here](http://www.filefactory.com/file/2rd5t8ovuxa9/diss410.zip)


**Step 3:** Open a new project. On RStudio, use the upload button (shown below) to upload the .zip file. 

{{< figure library="true" src="Upload.png" lightbox="true" >}}

**Step 4:** Once you have upload the .zip file, open the TempleArticleAPA6th folder. Then, click on the *TempleArticleAPA6th.Rproj* file and click "yes" to open the project.

# Install necessary packages

This template requires a few packages, namely tinytex and papaja. Tinytex and papaja can be installed through the following command placed inside chunk:

if(!"tinytex" %in% rownames(installed.packages())) install.packages("tinytex")

devtools::install_github("crsh/papaja")

# Start writing your APA Article.

**Step 1:** Open the TempleArticleAPA6th file, and then the *TempleArticleAPA6th.Rmd* file.

**Step 2:** To ensure that your packages are all in line, press the "knit" button at the top of the script.

*If you get a pop-up saying you need more packages, say "yes" to install the necessary packages*

# Editing the YAML

**Step 1:** Edit the YAML (beginning of the document) with your title, running head (shorttitle), author name and email, and University.

*Tip: It is helpful to try to knit your document every few times you change the document, just so that you don't finish the whole dissertation and then find out something is wrong.*

# Authornote

  In your Psychology paper, author notes are not always required. This section includes the **complete department/insistution affiliation**, any changes in affiliation since completion of the paper, acknowledgements, and contact information. 
  This section may be **deleted**. R is an intuitive copy-paste way to create your own documents. It looks impressive too! Keep in mind, try to maintain active voice, past tense, and restrain from using casual wording throughout your paper.

# Abstract

Your College-level Psychology paper's abstract is typically structured based on your professor's requirements. It may not require one at all. Typically, the abstract contains one or two sentences providing a **basic introduction** to the field. Next are two to three sentences of **more detailed background** to the field, comprehensible to your fellow college-level peers. Next is one sentence clearly stating the **general problem** being addressed by your study. Next is one sentence summarizing the main result. Next is two or three sentences explaining what the **main result** reveals in direct comparison to what was thought to be the case previously, or how the  main result adds to previous knowledge. Next is one or two sentences to put the results into a more **general context**. Finally, two or three sentences to provide a **broader perspective**, typically providing ideas for future studies.
  keywords are effectively chosen by the author. Your paper may not require this, but good articles contain around 10-12 keywords. Keywords to choose will potentially help search engines pick up your article for readers.

# Introduction
  Your introduction is the opening paragraph to your article. It should in one or two sentences introduce the **general purpose** of your study. Next in two or three sentences **address your research problem** in a relatable way to the general public. Next introduce the definitions of your constructs of interest--describe what you're measuring and why you chose to measure it for your dependent variable. Then, in one or two sentences describe in your own words the **importance of the study** that you discussed.
  Your introduction does not end here, however. Depending on how many sources your professor requires, you will need to do a **literature review**. Each paragraph in a lit review briefly describes what researchers did and found. Next, you must provide a reason for including the reference in the first place.
  In the next paragraph, in one or two sentences explain how your current study builds upon the existing research--state how it helps understand the problem. In one or two sentences, briefly describe **how you conducted the study** (methods). Finally, in one sentence state your **hypothesis and prediction** clearly.

## Participants
In the first paragraph, describe the participants of your study. Describe who the participants are, how they were recruited, demographic info like gender or age, and explain any prerequisites to participating. 

## Experimental Design
This paragraph states the **experimental design** of the study--was it a within subjects design? A between subjects? In two to three sentences state the operational definitions of the **Independent variable** and **dependent variable**. State any and all control variables used, like randomization.

## Material
The Materials section states in detail descriptions of the **stimuli** used in the study in one or two sentences. Next, in one or two sentences give a detailed description of the **measurement**, making sure to include one of your references for scale, if applicable.

## Procedure
In this paragraph, in three to four sentences provide a **clear order of events** that pertain to your study. Next, provide a **description of the methods used** for each participant group. Finally, provide the 

# Results
Depending on your experiment type, you will need to calculate and gather data points. In one or two sentences explain in **plain english** the **hypothesis**, state the correct inferential test (this could be a two sided t-test etc.), and use the correct statistical language. Imagine explaining what you did to your grandmother in this section. Next, report what the test concluded in APA style including **means, standard devation of each group, and directionality**. Next in one sentence report the **control variable testing**.

# Discussion
The discussion section is essentially a **summary of the problem with results**. Restate in one or two sentences the **main purpose of the experiment**. Next in two sentences or three, write the **summary of the findings in everyday language**. Next, take as long as you want to compare results to **past literature** (use as many sources as necessary). Finally, write your **general concussions** after reviewing the literature.

The next paragraph(s) should concern your limitations. In one or two sentences, write **potential critiques and confounding variables** that you reported in your findings. Next, in one or two sentences **summarize exactly what the findings are** that you are referring to. Continue writing these paragraphs depending on how many limitations you found.

Finally in the last paragraph, brainstorm in one or two sentences **what future studies may want to do** to alleviate this issue. Directions to future studies must be based in logic and in the current study's results. These directions must be unique, relevant, and list all important directions... just writing "increase small sample size" is considered inadequate.

# References

**Note** that references are pulled directly from your .bib file. I will show you how to update this .bib file. Go online to the source you want to cite. If there is an option, you may most likely find a BibTeX citiation option. Copy this citiation and paste it directly into your .bib file. To ensure your citation appears in the references page, copy the intext citation and place it in parentheses like so: (@R-base).

# Figures
According to APA6 guidelines, all figures must be in the page after the references. Pictures may be uploaded to RStudio or Rstudio Cloud from your personal files using the Upload option.

# You're all done!

Thank you for reading my blogpost on how to make your own APA article! The task may seem daunting, however learning R is a fantastic and versatile skill.

Dr. Erin M. Buchanan has created a 20 minute in-depth tutorial featuring papaja that you can watch here:

https://www.youtube.com/watch?v=I_HW5Rraqg8
