# Princeton AI4ALL Fragile Families Project 2018
Authors and collaborators: Agata Foryciarz, Desmond Zhong, Renato Pagliara Vasquez, Jonathan Lu, Kristin Catena, Prof. Matt Salganik, Prof. Barbara Engelhardt

# Background
The Fragile Families & Child Wellbeing Study is following a cohort of nearly 5,000 children born in large U.S. cities between 1998 and 2000 (roughly three-quarters of whom were born to unmarried parents). We refer to unmarried parents and their children as “fragile families” to underscore that they are families and that they are at greater risk of breaking up and living in poverty than more traditional families.

The core Study was originally designed to primarily address four questions of great interest to researchers and policy makers: (1) What are the conditions and capabilities of unmarried parents, especially fathers?; (2) What is the nature of the relationships between unmarried parents?; (3) How do children born into these families fare?; and (4) How do policies and environmental conditions affect families and children?

The core Study consists of interviews with both mothers, fathers, and/or primary caregivers at birth and again when children are ages one, three, five, nine, and fifteen. The parent interviews collect information on attitudes, relationships, parenting behavior, demographic characteristics, health (mental and physical), economic and employment status, neighborhood characteristics, and program participation. Additionally, in-home assessments of children and their home environments were conducted at ages three, five, nine, and fifteen. The in-home interview collects information on children’s cognitive and emotional development, health, and home environment. Several collaborative studies provide additional information on parents’ medical, employment and incarceration histories, religion, child care and early childhood education. 

Six waves of data are publicly available through the Office of Population Research data archive:

- Wave 1 (Baseline)
- Wave 2 (Year 1)
- Wave 3 (Year 3)
- Wave 4 (Year 9)
- Wave 5 (Year 15)

Researchers have used this data to develop models that predict key attributes affecting disadvantaged children and to suggest new policies to improve child outcomes. In this project, you will use data collected as a part of the Fragile Families Challenge to uncover factors that influence young people’s academic performance, confidence and grit, and psychological well-being. You will generate scientific questions and perform data exploration, feature selection, and machine learning to evaluate your hypotheses. You will explore alternative explanations for your results and work closely with the project instructors to refine your hypotheses. You will also work together to design and discuss policy proposals based on your findings that would help provide services and programs to facilitate children’s success.

More information:

  http://www.fragilefamilies.princeton.edu/
  
Documentation:

  https://fragilefamilies.princeton.edu/documentation
  
Watch the "getting started" video:

  https://www.youtube.com/watch?v=HrYPtdXeSaM&feature=youtu.be
  
See the "getting started" slides here:

  https://github.com/fragilefamilieschallenge/slides/blob/master/ffchallenge_getting_started_cos424.pdf
  
# Data
We use the Fragile Families Challenge data. The data has been collected since children's birth at 5 time points: birth, year 1, 3, 5, 9 and 15. Our challenge is to predict outcomes at age 15 based on the variables from earlier time points.

The data is split into three CSV (comma separated values) files:

- background.csv contains all the data up to year 9.
- train.csv and test.csv contain data for age 15. The training set consists of 12,000 variables across 3,200 families. The test set consists of 6 variables across ~2,000 families. 

Our goal by the end of the 3 weeks is to predict some of the six variables in the testing data.

# Data Download

We will provide the data to you through a USB stick. Note that although this data is anonymized, it is still highly sensitive and should only be used for research purposes. Please do not copy the data to any other device besides your AI4All computer and do not share your local copies with anyone outside of AI4All.

# Metadata - variable description

Each variable in the data has a dictionary of features associated with it, such as: source (constructed/weight/id number/...), respondent (father/mother/teacher), umbrella category (parental relationship, health and health behavior,...) and others. You can view variables by their features here: http://metadata.fragilefamilies.princeton.edu/variables.

# Setup:
- Create a folder on your Desktop with the name "Fragile_Families".

- Inside this folder, create two new folders with the names "ff_data" and "ff_notebooks".

- Open a terminal by clicking on the Spotlight Search (magnifying glass icon) on the upper right corver of the desktop, entering "Terminal", and pressing enter. 

- Point to the "Fragile_Families" folder
  `cd Fragile_Families`

  `git clone https://github.com/agataf/ai4all`

- To run a Jupyter notebook:

  `source ~/miniconda3/bin/activate`

  `jupyter notebook`
