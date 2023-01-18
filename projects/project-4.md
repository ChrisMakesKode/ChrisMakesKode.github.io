---
layout: project
type: project
image: images/ERD_sample.png
title: Image Recognition Fashion Images
permalink: projects/online-furniture-ordering
# All dates must be YYYY-MM-DD format!
# Sentence: Bob joined this [club](URL to the club's site).
date: 2022-03-30
labels:
  - Python
  - Data Science
  - Machine Learning
summary: Employed data science algorithms to recognize categories of clothing from images. Formatted input images in uniform manner for efficient analysis. Compiled a report closely documenting various techniques and results.
---
<div style="background-color:rgba(238, 241, 255, 1); padding: 10px; border: 7px groove; border-color: lightblue; border-radius: 10px;">
  <center><figure>
    <img class="ui medium rounded image" src="../images/Proj4/mnistSample.png" style="vertical-align: middle;" float = "none">
    <figcaption style="vertical-align: middle;">Fig. 1. Sample of Data Dictionary <br /></figcaption>
  </figure></center>
  
  <span style="color: black">
    <br />During Spring 2022, I took a course titled, "Data Science: A Programming Approach". I was already familiar with coding in Python, but I gained firsthand experience in employing that code for various machine learning algorithms. To challenge our knowledge, an individual project was assigned where I applied several supervised learning models torwards the MNIST Fashion Image dataset. The objective was to find the best predictive model that would accurately predict clothes based on their category. Once accomplished, I was expected to apply my selected best model with new out-of-sample data, or personal photos of my own clothes. The entire project and its documented findings was carried out in Jupyter Notebook. <br /><br /></span>
  
  <a href="../images/CK Image Fashion Recognizer.pdf" download>A copy of my report can be downloaded and read here. Click here.</a>

  <span style="color: black">
    <br />In determining the optimal model, 4 categories were considered in my analysis:<br />
    - Wall (Clock) Time. The relative speed for a model to fit the data. <br />
    - Accuracy. This indicates how proficient a predictive model accurately predicts the out-of-sample data.<br />
    - Precision. Ratio of the true positives to the sum of true and false positives. <br />
    - Recall. Ratio of the true positives to the sum of the true positives and the false negatives. <br />
    <br />
    <br />Five models, or algorithms were considered:<br />
    - Linear Regression.<br />
    - K-Nearest Neighbor (KNN).<br />
    - Naive Bayes. <br />
    - Decision Tree. <br />
    - Random Forest. <br /><br />
    <br />Ultimately, I selected Decision Trees as my best model for its favorable overall efficiency and simplicity. <br />
  </span>

  <center><figure>
    <img class="ui medium rounded image" src="../images/Proj4/task2sample.png" style="vertical-align: middle;" float = "none">
    <figcaption style="vertical-align: middle;">Fig. 2. Five Images of New Testing Data <br /></figcaption>
  </figure></center>
  <span style="color: black">
    <br />With my selected model, it was time to apply it towards new data outside of the MNIST fashion dataset. I sampled some articles of clothes that I owned -- carefully positioning them to closely format them towards the other images in the MNIST dataset. <br /> <br /> <br /> <br /> <br /> <br /> <br /></span>
</div>
