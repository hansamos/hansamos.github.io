---
layout: archive
title: "CV"
permalink: /cv/
author_profile: true
redirect_from:
  - /resume
---

{% include base_path %}


Education
======
* Ph.D in Statistics, [KAUST](https://stat.kaust.edu.sa/), 2026 (expected)
* M.S. in Statistics, [USP-UfScar](https://www.pipges.ufscar.br/pt-br), 2021
* B.S. in Applied Math, [FURG](https://www.furg.br/graduacao/matematica-aplicada), 2016

Professional experience
======
* **[Transunion](https://transunion.com) (Jan 20 - Aug 22): Data Scientist**
  * Developed credit score, Collection, Fraud prevention, Insurance risk models and
  Income prediction models for financial, retail and insurance institutions in Brazil 
  * Structured queries to create new set of attributes
  * Structured template for deploying ML models using Flask framework
  * RD: Research on applications of unsupervised and Bayesian deep learning methods to credit data. 
  * **Techs**: R, Python, SQL, Spark, Hive, Github.

Research experience
======
* **[PART Lab-KAUST](https://part.kaust.edu.sa/) (Aug 21- Dec 21):  Visiting Student Researcher**
  * Machine Unlearning: unlearn deep learning model without retraining from scratch.
  * Supervisor: Dr Di Wang
  * **Techs**: Python (Pytorch mainly), Github.


* **[Small Lab - UfScar](https://part.kaust.edu.sa/) (Feb 19- Dec 19):  Visiting Student Researcher**
  * Goodness of fit using the nonparametric full Bayesian Significance Test.
  * Supervisor: Dr Rafael Izbicki, Dr. Luis Salasar
  * **Techs**: R, Github.
  

Publications
======
  <ul>{% for post in site.publications reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  
Talks
======
  <ul>{% for post in site.talks reversed %}
    {% include archive-single-talk-cv.html  %}
  {% endfor %}</ul>
  
Teaching
======
  <ul>{% for post in site.teaching reversed %}
    {% include archive-single-cv.html %}
  {% endfor %}</ul>
  

