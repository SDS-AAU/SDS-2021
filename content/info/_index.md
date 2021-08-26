---
title: Info and Schedule
weight: 1
chapter: true
---

### Chapter 1

# Basics
 Schedule stuff and a bit of intro about what this part is about
 And now we add a little more.

{{ partial "header.html" . }} [** navigation](#) {{if .Site.Home.Content
}} {{.Site.Home.Content}} {{else}} {{if eq .Site.Language.Lang "fr"}}

Personaliser la page d'accueil
==============================

Le site fonctionne. Ne pas oublier de personaliser cette page avec votre
propre contenu. 3 manières de faire :

-   **1.** Créer un fichier \_index.md dans le dossier **content** et le
    remplir de Markdown
-   **2.** Créer un fichier index.html dans le dossier **static** et le
    remplir de code HTML
-   **3.** Configurer le serveur http pour rediriger automatiquement la
    homepage vers la page de votre choix dans le site

{{else}}

SOCIAL DATA SCIENCE SEMESTER (SDS) {style="text-align:center;"}
----------------------------------

Starting fall semester 2018, the Department of Business and Management
at Aalborg University offers a new option for the 3rd semester of their
master's programmes, the Social Data Science specialization semester
(SDS). Immerse yourself into the increasingly relevant and fast-emerging
sector of data analytics, starting September 2018. Through this
programme, you will learn cutting-edge, requisite skills in, practical
terms, and be able to apply them to real-world issues in various fields.
Data continues to grow exponentially. From Social media posts, sensor
signals on smartphones, smart home devices to the increasing
digitisation of companies and public organisations, data has seen
unprecedented granularity.

### Modules {style="text-align:left;"}

M1: Applied Data Science and Machine Learning

This module will prove a condensed introduction to the “Data Science
Pipeline”, introducing students to methods, techniques, and workflows in
applied data analytics and machine learning, including data acquisition,
preparation, analysis, visualization, and communication.

M2: Network Analysis and Natural Language Processing

Focuses on analyzing a variety of unstructured data sources.
Particularly, students will learn how to explore, analyze, and visualize
natural language (text) as well as relational (network) data.

M3: Deep Learning and Artificial Intelligence for Analytics

Introduces to the most recent developments in machine learning, which
are deep learning and artificial intelligence applications. The module
will provide a solid foundation for this exciting and rapidly developing
field. Students will learn whether and how to apply deep learning
techniques for business analytics, and acquire proficiency in new
methods autonomously.

M4: Semester Project

This modlue is a 15 ECTS project to be completed in collaboration with
an external partner (optimally). External organisations can not only
provide real-life datasets but also motivate students through real
problems, and help to adjust the curriculum to make contents most
relevant in terms of employability. The teaching staff will assist
students with significant guidance and coordination to identify
potential, mutually benefiting areas of project-collaboration with
external partners.

#### Schedule and Calendar {style="text-align:left;"}

+--------------------------+--------------------------+--------------------------+
| Semester                 | Key Dates                | Topics                   |
+==========================+==========================+==========================+
| M1: Week 36-41           | -   In-person workshop   | -   W 36: Introduction & |
|                          |     days: W37 -          |     landing              |
|                          |     08.09.2020, W38 -    | -   W 37: Data           |
|                          |     18.09.2020           |     Manipulation,        |
|                          | -   M1 individual        |     Exploratory Data     |
|                          |     assignment 1:        |     Analysis (EDA), Data |
|                          |     hand-in deadline     |     Visualization        |
|                          |     10.09.2020 23:59:00  | -   W 38: Unsupervised   |
|                          |     at the latest        |     Machine Learning     |
|                          |     (Peergrade)          |     (UML)                |
|                          | -   M1 individual        | -   W 39: Supervised     |
|                          |     assignment 2:        |     Machine Learning     |
|                          |     hand-in deadline     |     (SML)                |
|                          |     22.09.2020 23:59:00  | -   W 40: Project work   |
|                          |     at the latest        |                          |
|                          |     (Peergrade)          |                          |
|                          | -   Group assignment:    |                          |
|                          |     25.09.2020 -         |                          |
|                          |     01.10.2020 (Digital  |                          |
|                          |     Eksamen)             |                          |
+--------------------------+--------------------------+--------------------------+
| M2: Week 41-46           | -   in-person workshop   | -   W 41: Introduction   |
|                          |     days: W42 -          |     to Network Analysis  |
|                          |     12.10.2020, W43 -    | -   W 42: Introduction   |
|                          |     22.10.2020           |     to                   |
|                          | -   M2 individual        |     Natural-Language-Pro |
|                          |     assignment 1:        | cessing                  |
|                          |     hand-in deadline     |     (NLP)                |
|                          |     15.10.2020 23:59:00  | -   W 44: Advanced       |
|                          |     at the latest        |     applications in      |
|                          |     (Peergrade)          |     Network and Text     |
|                          | -   M2 individual        |     Analysis             |
|                          |     assignment 2:        | -   W 45: Project work   |
|                          |     hand-in deadline     |                          |
|                          |     28.10.2020 23:59:00  |                          |
|                          |     at the latest        |                          |
|                          |     (Peergrade)          |                          |
|                          | -   Group assignment:    |                          |
|                          |     30.10.2020-05.11.202 |                          |
|                          | 0                        |                          |
|                          |     (Digital Eksamen)    |                          |
+--------------------------+--------------------------+--------------------------+
| M3: Week 46-51           | -   In-person workshop   | -   W 46: Introduction   |
|                          |     days: W47 -          |     to Artificial Neural |
|                          |     16.11.2020 +         |     Networks (ANN) &     |
|                          |     19.12.2020, W48 -    |     Deep Learning (DL)   |
|                          |     26.11.2020           | -   W 47: Neural         |
|                          | -   M3 individual        |     networks for spatial |
|                          |     assignment 1:        |     data: Recurrent      |
|                          |     hand-in deadline     |     Neural Networks      |
|                          |     01.12.2020 23:59:00  |     (RNN)                |
|                          |     at the latest        | -   W 48: Neural         |
|                          |     (Peergrade)          |     Networks for         |
|                          | -   Group assignment:    |     sequential data:     |
|                          |     03.12.2020-09.12.202 |     Recurrent Neural     |
|                          | 0                        |     networks (RNN &      |
|                          |     (Digital Eksamen)    |     LSTM)                |
|                          |                          | -   W 49&50: AdvancedDL  |
|                          |                          |     applications &       |
|                          |                          |     project work         |
+--------------------------+--------------------------+--------------------------+

#### Main Teaching Reference {style="text-align:left;"}

While this course does not come with a list of mandatory readings, we
will often refer to some central resources in R and python, which for
the most part can always be accessed in a free and updated online
version. We generally recommed you to use these amazing ressources for
problem-solfing and further self-study on the topic.

 

Resources

R

-   Wickham, H., & Grolemund, G. (2016). R for data science: import,
    tidy, transform, visualize, and model data. O'Reilly Media, Inc.
    [Online available here](https://r4ds.had.co.nz)
-   Baumer, B., Kaplan, D. & Horton, N. (2020) Modern Data Science with
    R (2nd Ed.). CRC Press [Online available
    here](https://mdsr-book.github.io/mdsr2e/)
-   Kuhn, M., Silge, J. (2020) Tidy Modeling with R [Online available
    here](https://www.tmwr.org)

Python

-   VanderPlas, J. (2016). Python data science handbook: Essential tools
    for working with data. O'Reilly Media, Inc. [Online available
    here](https://jakevdp.github.io/PythonDataScienceHandbook/index.html)

{{end}} {{ end }} {{ partial "footer.html" . }}
