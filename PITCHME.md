##### 



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

template/tips for upcoming amnesty internation hackathon

+++

---

## Data Analytics Worflow

<br>

+++?image=https://cacm.acm.org/system/assets/0001/3678/rp-overview.jpg

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
* The most common way to produce and share results from these sorts of studies is to compose a pdf/powerpoint and attach some graphs. 
* But this means that viewers of the report are unable to review the work in depth, or to extend it themselves. 
* It’s very easy to commit methodological errors when asking questions of data; an unintended bias here, or a missed corner case there, can lead to entirely incorrect conclusions.

+++

#### Reproducible research

<br>

=

**Code** (with infrastructure-as-a-code)

+

**Data** (with metadata)

+

**Documentation** (code+data=literate programming)



+++

#### Literate Programming, Donald Knuth (84)

<br>

"Let us change our traditional attitude to the construction of programs: Instead of imagining that our main task is to instruct a computer what to do, let us concentrate rather on explaining to human beings what we want a computer to do." 

+++

#### Reproducible research

<br>

= Openness 

= Crowd Innovation

---

## How can you make your analysis reproducible?
<span style="font-size:0.6em; color:gray">data carpentry</span> |
<span style="font-size:0.6em; color:gray">software carpentry</span>

+++

#### 1. plan for reproducibility before you begin

<br>

* **project organisation**
* **data management plan**


+++

#### 2. keep track of things

<br>

* **version control**
* **documentation** (code + software environment)

+++

#### 3. let your computer do the work

<br>

- **think about the entire pipeline**: use coded/automated steps as opposed to doing things by hand
- (data) **infrastructure-as-code**
- save **data + code = output**

+++

#### 4. publish and share

<br>

- **knowledge repository**

  <br> 

------

## Tools

* **Project organisation**: Cookiecutter Data Science
* **Version control**: GitHub
* **Code+Documentation**: Jupyter Notebook
* **Data Science Workbench**: Google Datalab
* **Knowledge Repository**



+++

<br>

#### Project organisation: Cookiecutter Data Science

http://drivendata.github.io/cookiecutter-data-science/

+++

<br>

#### Code repository: GitHub

https://try.github.io

![Image-Relative](https://d1z75bzl1vljy2.cloudfront.net/kitchen-sink/octocat-daftpunkocat.gif)

+++

<br>

+++?image=https://stripe.com/img/blog/posts/reproducible-research/git-diagram@2x.png

#### Code+Documentation: Jupyter Notebook

<br>

**Ju-py-te-R**

- **Ju**lia
- **Py**thon
- La**Te**X
- **R**

+++ 

<br>

`https://github.com/jupyter/jupyter/wiki/A-gallery-of-interesting-Jupyter-Notebooks`

+++ 

<br>

**Best practices for organising your jupyter notebooks**:

* Differentiate the kinds of notebooks into two main categories - **lab notebooks** and **deliverable notebooks**

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

  <br>

  **Data Sharing**

  * How to share data: https://github.com/jtleek/datasharing
  * Dataset Marketplace: https://datahub.io

  ​

#### Data Science Workbench: Docker and Google Datalab

<br>

Configuring a data science environment can be a pain. Can you "code" our development environment so others can run our analytics code is exactly the same environment used to develop the code?

+++

<br>

**Docker**

If you haven't used Docker before, a good place to start is the [Docker User Guide](https://docs.docker.com/userguide/).

`docker pull wiseio/datascience-docker`

+++

<br>

**Google Datalab**

So far we have introduced a number of tools, wouldn't it be nice to have all of these tools packages into one component?

+++

<br>

Google Datalab = 

GitHub+Jupyter+Docker

+Google Cloud Analytics Services (BigQuery, Tensorflow, Speech API, NLP API,...)

+++

<br>

#### Knowledge repository

<br>

Knowledge Repository is focused on facilitating the sharing of knowledge between data scientists and other technical roles using data formats and tools to better promote reproducible research.

[Airbnb Knowledge Repository Project](https://medium.com/airbnb-engineering/scaling-knowledge-at-airbnb-875d73eff091)

+++

<br>

?+++image=https://cdn-images-1.medium.com/max/1600/1*MPdpSg36RzBeinrL0wIGwQ.png

