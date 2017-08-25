---
layout: post
title:  "Ovation Summer Academy alpha (OSA-alpha)"
date: 2017-09-25 10:02:00
categories:
- blog
- publications
- arxiv
img: ovation.png
thumb: ovation.png
author: Marcus Liwicki
---

# **What is Ovation Summer Academy alpha (OSA-alpha)?**

The MindGarage and Insiders Technologies GmbH are working on Conversational Intelligence (CI) to make machines understand Natural Language as well as humans do. CI includes Chat-Bots to core modules like Named Entity Recognition, Intent Classification, Visual Question Answering, Question Answering and Reasoning, etc.. We deal with all these challenging tasks in our everyday work. To give Conversational Intelligence a lateral perspective and to figure out fresh solutions for them, we are bringing together computer scientists from all around Europe to what we call the **Ovation Summer Academy alpha** (OSA-alpha). The goal is to come up with innovative ideas to tackle the challenges in Conversational Intelligence, work as a team, program like there is no tomorrow, and build Jarvis by the end (or at least try to :-P). This is a pre announcement for the Ovation Summer Academy alpha. The official announcement will be made tomorrow on the <a href="mindgarage.ai" target="_blank">MindGarage</a> homepage.

If you want to quickly apply for the OSA-alpha, you can do it <a href="https://goo.gl/forms/2SUbIT4wm03RL8DC3" target="_blank">here</a>.

<br>
# **TL;DR**
 
 * ## **What**: Ovation Summer Academy alpha
 * ## **When**: 18/09/2017 till 22/09/2017
 * ## **Where**: Berlin, Germany
 * ## **Where to Register**: **<a href="https://goo.gl/forms/2SUbIT4wm03RL8DC3" target="_blank">here</a>** till **01/09/2017**
 * ## **Registration Fees**: **None**
 * ## **Costs for the hotel, rooms, food, social events, and (some) drinks will be covered by Insiders Technologies**

<br>

# **Participation Requirements**

<br>

## **1. AI for Natural Language Processing**
 Experience in AI for NLP is a minimum requirement for participating in the event.

## **2. Deep Learning**
 Experience in Deep Learning models for NLP is an added advantage. We will provide a generic framework for handelling datasets and boilerplate code for training Deep Learning models. These can be used out of the box and can be easily extended as well. Frameworks that we will support are Tensorflow, Keras, Tflearn, Spacy and NLTK.

## **3. Knowledge about the Current Methods**
 Knowledge about the current methods like Word2Vec, Attention Mechanism, Recurrent Neural Networks, etc. Knowledge about all of these methods is not a strict requirement but is a good-to-have.

<br>

# **Where is it going to happen?**
This year OSA-alpha is going to take place in Berlin, Germany at the innovative Campus (Saarbrücker Str. 36). Insiders Technologies is going to host all the participants of OSA-alpha and all our sessions will take place in the old backery.
<br>

<img src="https://mg-git.cs.uni-kl.de/mg-admin/OSA-alpha/uploads/b382e5a856ea4fff5ceb08683713fc80/BeFunky_Collage.jpg" alt="Collage Berlin" style="width: 100%;">
<br>
<br>

# **What are we going to do at OSA-alpha?**

As mentioned above, we are going to come up with innovative solutions and tools (demonstrators) for the challenges in Conversational Intelligence and try to build a curated framework for it by using the models that the participants develop in OSA-alpha. The topics that we are going to cover are the following:

<br>

## **1. Intent Classification (IC)**
Classifying the intent of what a person says. Intent Classifiers are the core of Chat-Bots. For a machine to give a response to a Natural Language query by a human, it needs to understand the intent of the human and once the intent is classified, a response can be generated.

We will cover the following sub-tasks under Intent Classifications which will be the building blocks of an Intent Classifier.

<br>

### **1.1 Semantic Relatedness of Sentences**

Given pairs of similar and dissimilar sentences, predict the semantic relatedness between them. One possibility would be to develop Machine Learning models to do the prediction and combine it with conventional approaches.

<br>

### **1.2 Text Classification**

Given a sentence, classify it given a predefined set of classes. Train your models on labelled sentences and perform classification.

<br>

### **1.3 Text Classification with very less Data**

Try to perform one-shot learning on a very small dataset to classify sentences.

<br>

## **2. Entity Recognition (ER)**
Once the machine has extracted the intent of a person's query, it will need to parse this and gather useful information from it. To do so, the machine needs to identify <a href="https://en.wikipedia.org/wiki/Named-entity_recognition" target="_blank">Named Entities</a> from the queries. These Entities are used to reason with the query and generate an answer or select an answer from a given template. For example, if the query is "What is Germany?", then the machine needs to parse the query into "What is Germany **[Country]** ?" 

This task has two subtasks, which are:

<br>

### **2.1 Named Entity Recognition (NER)**

Given a sentence, predict which entities are present in it and where.

<br>

### **2.2 NER with less Data**
Do the same as NER but with extremely fewer data.

<br>
## **3. Question Answering (QA)**

Generate or sample an answer given a question. For example, if a person asks "Am I alive?", then the machine should be able to generate an answer "yes/no" or sample from a set of predefined answers. After understanding the intent of a query and the entities in it, the machine would use a QA model to give an answer to the query.

There are many subtasks under the category of QA and they are the following:
<br>
### **3.1 Non-Factoid QA**
Given a question, sample an answer from a set of predefined answers or generate it.
<br>
### **3.2 Factoid QA**
Given a question and a set of facts related to the question, sample an answer from a set of predefined answers or generate it.
<br>
### **3.3 Reading Comprehension (RC)**
Given a comprehension passage and a question, find the answer in the passage.
<br>
### **3.4 Visual QA**
Given an image and a question related to the image or objects in the image, sample an answer from a set of predefined answers or generate it.

<br>
## **4. Sentiment Analysis (SA)**

We focus on the task of Sentiment Classification, where a sentence or phrase has to be classified according to the emotions it expresses. Sentences may express positive or negative emotions about certain elements contained in it. For example, the sentence _the battery is bad, but I find it a good cellphone._ expresses negative emotions about a small part of the cellphone (namely, its battery), while still expressing positive emotions about the cellphone as a whole. 
<br>
### **4.1 Coarse-Grained Sentiment Classification**
We say we perform _Coarse-Grained_ Sentiment Classification when there are only two possible classes: Positive or Negative.
<br>
### **4.2 Fine-Grained Sentiment Classification**
On the other hand, the task of _Fine-Grained_ Sentiment Classification is generally related to classifying several types of emotion, such as anger, sadness, disgust or happiness.

<br>

# **How do I apply for the OSA-alpha?**

Good that you asked! If you are interested in participating on the Ovation Summer Academy alpha, please fill in the application form <a href="https://goo.gl/forms/2SUbIT4wm03RL8DC3" target="_blank">here</a>. It will be open until September, 1st, 2017. The selected participants will be announced a few days later here in our blog. We are looking forward to see you in Berlin in September!

<br>

# **Organization Committee**
<br>

<table>
<tr>
    <th><img src="https://mg-git.cs.uni-kl.de/mg-admin/OSA-alpha/uploads/20d694dd8e4a0283fb087e3361077115/marcus.jpg" alt="Marcus Liwicki" style="width: 90%;margin-left:6px;">
    </th>
    <th><img src="https://mg-git.cs.uni-kl.de/mg-admin/OSA-alpha/uploads/97cd3ae286e5a2064c7f876cfabce461/john_new.jpeg" alt="John Gamboa" style="width: 90%;margin-left:6px;"></th>
    <th><img src="https://mg-git.cs.uni-kl.de/mg-admin/OSA-alpha/uploads/56882ca535691b153f8a94fc934e1711/ayush.jpg" alt="Ayushman Dash" style="width: 90%;margin-left:6px;"></th>
    <th><img src="https://mg-git.cs.uni-kl.de/mg-admin/OSA-alpha/uploads/b448fc1dcd74879b5aab3bf23ae9d488/shan_team.jpg" alt="Afzal" style="width: 90%;margin-left:6px;"></th>
</tr>
<tr>
    <th style="text-align: center;width: 25%;">
            <span style="font-size: 120%;"><a href="http://blog.mindgarage.de/liwicki/" target="_blank">Marcus Liwicki</a></span>
            <br> <span style="font-size: 110%;">General Chair</span> 
            <br> <span style="font-size: 100%;"><a href="http://mindgarage.ai/" target="_blank">MindGarage</a></span>
            <br><span style="font-size: 100%;"><a href="http://www.insiders-technologies.de/" target="_blank">Insiders Technologies</a></span>
    </th>
    <th style="text-align: center;width: 25%;">
            <span style="font-size: 120%;"><a href="https://vaulttech.github.io/" target="_blank">John Gamboa</a></span>
            <br> <span style="font-size: 110%;">Co-Chair</span> 
            <br> <span style="font-size: 100%;"><a href="http://mindgarage.ai/" target="_blank">MindGarage</a></span>
            <br><span style="font-size: 100%;"><a href="http://www.insiders-technologies.de/" target="_blank">Insiders Technologies</a></span>
    </th>
    <th style="text-align: center;width: 25%;">
            <span style="font-size: 120%;"><a href="https://dashayushman.github.io/" target="_blank">Ayushman Dash</a></span>
            <br> <span style="font-size: 110%;">Co-Chair</span> 
            <br> <span style="font-size: 100%;"><a href="http://mindgarage.ai/" target="_blank">MindGarage</a></span>
            <br><span style="font-size: 100%;"><a href="http://www.insiders-technologies.de/" target="_blank">Insiders Technologies</a></span>
    </th>
    <th style="text-align: center;width: 25%;">
            <span style="font-size: 120%;">Muhammad Zeshan Afzal</span>
            <br> <span style="font-size: 110%;">Scientific Co-Chair</span> 
            <br> <span style="font-size: 100%;"><a href="http://mindgarage.ai/" target="_blank">MindGarage</a></span>
            <br><span style="font-size: 100%;"><a href="http://www.insiders-technologies.de/" target="_blank">Insiders Technologies</a></span>
    </th>
</tr>
</table>


<table style="width: 50%;margin-top:10px">
<tr>
    <th><img src="https://mg-git.cs.uni-kl.de/mg-admin/OSA-alpha//uploads/2e5db0d17c83437dce73df33972f824a/weiss_team.jpg" alt="Werner Weiss" style="width: 90%;margin-left:6px;"></th>
    <th><img src="http://www.insiders-technologies.de/fileadmin/images/Presse/Presse_Bildmaterial/technologies_logo/rgb/insiders_technologies_rgb.png" alt="Insiders Technologies" style="width: 90%;margin-left:6px;">
    </th>
    
</tr>
<tr>
    <th style="text-align: center;width: 25%;">
            <span style="font-size: 120%;">Werner Weiss</span>
            <br> <span style="font-size: 110%;">CEO</span> 
            <br><span style="font-size: 100%;"><a href="http://www.insiders-technologies.de/" target="_blank">Insiders Technologies</a></span>
    </th>
    <th style="text-align: center;width: 25%;">
            <span style="font-size: 120%;"><a href="http://www.insiders-technologies.de/" target="_blank">Insiders Technologies GmbH</a></span>
            <br> <span style="font-size: 110%;">Sponsor</span>
    </th>
</tr>
</table>

