---
date: "2020-04-20T00:00:00Z"
external_link: ""
image:
  focal_point: Smart
links:
- icon: file-download
  icon_pack: fas
  name: APA Paper Example
  url: "/pdf/TempleAPA6th.pdf"
- icon: file-archive
  icon_pack: fas
  name: Download Zip File
  url: "/zip/TempleArticleAPA6th.zip"
summary: Read this to learn how to create your own Temple-affiliated APA paper!
tags:
- paper
title: APA Paper Tutorial
url_code: ""
url_pdf: ""
url_slides: ""
url_video: ""
authors: ["preston"]
---


Welcome. Here is a template for an APA article tailored for Psychology students at Temple University.

# Uploading the file

**Step 1:** Download Rstudio or log into your Rstudio.cloud account. Here, you should open a new project and title it so that you can remember where it is.

**Step 2:** Download the .zip file above.


**Step 3:** Open a new project. On RStudio, use the upload button (shown below) to upload the .zip file. 

{{< figure library="true" src="Upload.png" lightbox="true" >}}

**Step 4:** Once you have uploaded the .zip file, open the TempleArticleAPA6th folder. Then, click on the *TempleArticleAPA6th.Rproj* file and click "yes" to open the project.

# Install necessary packages

This template requires a few packages, namely tinytex and papaja. Tinytex and papaja can be installed through the following command placed inside chunk:

```
if(!"tinytex" %in% rownames(installed.packages())) install.packages("tinytex")

devtools::install_github("crsh/papaja")
```

If you need a refresher on
code chunks, check out the R Markdown tutorial located [here](https://chuyler.shinyapps.io/final_projcet_final/#section-lets-learn-r).

# Start writing your APA Article.

**Step 1:** Open the TempleArticleAPA6th file, and then the *TempleArticleAPA6th.Rmd* file.

**Step 2:** To ensure that your packages are all in line, press the "knit" button at the top of the script.

*If you get a pop-up saying you need more packages, say "yes" to install the necessary packages*

# Editing the YAML

**Step 1:** Edit the YAML (beginning of the document) with your title, running head (shorttitle), author name and email, and University. If you forget how to do this, please refer to the [R Markdown tutorial](https://chuyler.shinyapps.io/final_projcet_final/#section-lets-learn-r)

*Tip: It is helpful to try to knit your document every few times you change the document, just so that you do not finish the whole paper and then find out something is wrong.*

## Authornote

  In your Psychology paper, author notes are not always required. This section includes the **complete department/institution affiliation**, any changes in affiliation since completion of the paper, acknowledgements, and contact information. 
  This section may be **deleted**. R is an intuitive copy-paste and tweak way to create your own documents. It looks impressive too! Keep in mind, try to maintain active voice, past tense, and restrain from using casual wording throughout your paper.

# Abstract

Your College-level Psychology paper's abstract is typically structured based on your professor's requirements. It may not require one at all. Typically, the abstract contains one or two sentences providing a **basic introduction** to the field. Next are two to three sentences of **more detailed background** to the field, comprehensible to your fellow college-level peers. Next, there is one sentence clearly stating the **general problem** being addressed by your study. Next, there is one sentence summarizing the main result. Next, there are two or three sentences explaining what the **main result** reveals in direct comparison to what was thought to be the case previously, or how the  main result adds to previous knowledge. Next, there is one or two sentences to put the results into a more **general context**. Finally, there are two or three sentences to provide a **broader perspective**, typically providing ideas for future studies.
  keywords are effectively chosen by the author. Your paper may not require this, but good articles contain around 10-12 keywords. Keywords to choose will potentially help search engines pick up your article for readers.

# Introduction
  Your introduction is the opening paragraph to your article. It should introduce the **general purpose** of your study in one or two sentences. Next, in two or three sentences, **address your research problem**. Next introduce the definitions of your constructs of interest--describe what you are measuring and why you chose to measure it for your dependent variable. Then, in one or two sentences describe in your own words the **importance of the study** that you discussed.
  Your introduction does not end here, however. Depending on how many sources your professor requires, you will need to do a **literature review**. Each paragraph in a literature review briefly describes what researchers did and found. Next, you must provide a reason for including the reference in the first place.
  In the next paragraph, in one or two sentences, explain how your current study builds upon the existing research and how it helps understand the problem. In one or two sentences, briefly describe **how you conducted the study** (methods). Finally, use one sentence to state your **hypothesis and prediction** clearly.

## Participants
In the first paragraph, describe the participants of your study. Describe who the participants are, how they were recruited, demographic info like gender or age, and explain any prerequisites to participating. 

## Experimental Design
This paragraph states the **experimental design** of the study--was it a within-subjects design or a between-subjects design? In two to three sentences, state the operational definitions of the **independent variable** and **dependent variable**. State all control variables used, like randomization.

## Materials

This section provides descriptions of the **stimuli** used in the study in one or two sentences. Next, in one or two sentences, give a detailed description of the **measurement**, making sure to include one of your references for scale, if applicable.

## Procedure
In this paragraph, in three to four sentences, provide a **clear order of events** that pertain to your study. Next, provide a **description of the methods used** for each participant group. 

# Results
Depending on your experiment type, you will need to calculate and gather data points. In one or two sentences, explain in **plain English** the **hypothesis**, state the correct inferential test (this could be a two-sided t-test, etc.), and use the correct statistical language. Imagine explaining what you did to your grandmother in this section. Next, report what the test concluded in APA style including **means, standard deviation of each group, and directionality**. Next, in one sentence, report the **control variable testing**.

# Discussion

Restate in one or two sentences the **main purpose of the experiment**. Next, in two or three sentences, write the **summary of the findings in everyday language**. Next, take as long as you want to compare results to **past literature** (use as many sources as necessary). Finally, write your **general conclusions** after reviewing the literature.

The next paragraph(s) should concern your limitations. In one or two sentences, discuss **potential critiques and confounding variables** that you reported in your findings. Next, in one or two sentences **summarize exactly what the findings are** that you are referring to. Continue writing these paragraphs depending on how many limitations you found.

For last paragraph, brainstorm in one or two sentences **what future researchers may want to do** to improve future studies. Directions to future studies must be based in logic and in the current study's results. These directions must be unique, relevant, and list all important directions... just writing "increase small sample size" is considered inadequate.

# References

**Note** that references are pulled directly from your .bib file. For a detailed explanation of how to include a bibliography, see the end of the Dissertation Tutorial.

# Figures
According to APA6 guidelines, all figures must be in the page after the references. Pictures may be uploaded to RStudio or Rstudio Cloud from your personal files using the Upload option.

# You are all done!

Thank you for reading my blogpost on how to make your own APA article! The task may seem daunting, however learning R is a fantastic and versatile skill.

Dr. Erin M. Buchanan has created a 20-minute in-depth tutorial featuring papaja that you can watch here:

https://www.youtube.com/watch?v=I_HW5Rraqg8
