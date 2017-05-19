##### 

?image=https://cdn-images-1.medium.com/max/1000/1*xzILVOWjZq9ReweYlODFsw.jpeg

---

## Reproducible Research in Data Science

##### <span style="font-family:Helvetica Neue; font-weight:bold"> <span style="color:#e49436">Shifath Nafis</span>

---

## Welcome!

+++

#### Objective

<br>

lay the groundwork for a culture of reproducibility in our data analytics projects

+++

template for upcoming amnesty internation hackathon

+++

---

## Data Analysis Worflow

?image=https://cacm.acm.org/system/assets/0001/3678/rp-overview.jpg

+++

#### Key steps

<br>

- define the question
- identify data sets
- obtain the data 
- clean the data
- exploratory data analysis
- statistical modelling/prediction
- interpret results
- challenge results
- synthesise/write up results
- create reproducible code




+++

#### Case Study 1

<br>

Mining Mobile Device Usage and Data for a recommendation platform

+++

#### Case Study 2

<br>

Benford's Law and Stripe Transcation Amounts



---

## Observations
The most common way to produce and share results from these sorts of studies is to compose a pdf/powerpoint and attach some graphs. 

But this means that viewers of the report are unable to review the work in depth, or to extend it themselves. 

It’s very easy to commit methodological errors when asking questions of data; an unintended bias here, or a missed corner case there, can lead to entirely incorrect conclusions.

+++

#### Reproducible research

<br>

=

Code (with infrastructure-as-a-code)

+

Data (with metadata)

+

Documentation (code+data=literate programming)



+++

#### Literate Programming, Donald Knuth (84)

<br>

Let us change our traditional attitude to the construction of programs: Instead of imagining that our main task is to instruct a computer what to do, let us concentrate rather on explaining to human beings what we want a computer to do. 

+++

#### Reproducible research

<br>

= Openness 

= Crowd Innovation

---

## How can you make your analysis reproducible
<span style="font-size:0.6em; color:gray">data carpentry</span> |
<span style="font-size:0.6em; color:gray">software carpentry</span>

+++

#### 1. plan for reproducibility before you begin

<br>

* project organisation
* data management plan


+++

#### 2. keep track of things

<br>

* version control
* documentation (code + software environment)

+++

#### 3. let your computer do the work

<br>

- think about the entire pipeline: use coded/automated steps as opposed to doing things by hand
- (data) infrastructure-as-code
- save data + code = output

+++

#### 4. publish and share

<br>

- knowledge repository 

------

## Tools

* Project organisation: Cookiecutter Data Science
* Code repository: GitHub
* Code+Documentation: Jupyter Notebook
* Data Science Workbench: Google Datalab
* Knowledge Repository




+++

#### Project organisation: Cookiecutter Data Science

http://drivendata.github.io/cookiecutter-data-science/

+++

#### Code repository: GitHub

https://try.github.io

![Image-Relative](https://d1z75bzl1vljy2.cloudfront.net/kitchen-sink/octocat-daftpunkocat.gif)

+++

#### Code+Documentation: Jupyter Notebook

Ju-py-te-R

Julia

Python

LaTeX

R

How do we organize our Jupyter notebooks so that our work is:

- collaborative (we work on teams)


- reliably captured and transparently shared


- clearly deliver insights to our clients

+++

Best practices:

* Differentiate the kinds of notebooks into two main categories - lab notebooks and deliverable notebooks

* Name the develop/lab-notebooks with the following convention:

  - [ISO 8601 date]-**[DS-initials]**-[2-4 word description].ipynb
  - 2017-05-19-**sn**-transactions-first-digit-distribution.ipynb

* Organisation of notebook folder: 

  * data # Backed up outside of version control
  * deliver # Final polished Notebooks for publication
  * develop # Lab Notebooks stored here
  * figures # Figures stored here
  * src # Scripts/modules stored here

* Sharing/Publication: 

  * Each Data Scientist has their own dev branch

  * Work is saved and pushed on dev branch daily

  * When ready to merge to master, pull request

    And, finally... commit:

    * `.ipynb`
    * `.py`
    * `.html`
    * and figures

    of all Notebooks (develop and deliver).

    ​

  +++ 

  #### Data Science Workbench: Google Datalab





​	+++

​	Knowledge repository

## 