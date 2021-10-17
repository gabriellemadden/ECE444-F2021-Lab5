# ECE444 Lab 5
Gabrielle Madden

This repo is a clone of https://github.com/nelaturuk/education_pathways.

## Activity 1
![repo](https://github.com/gabriellemadden/ECE444-F2021-Lab5/blob/styling-practice/lab_submission/repo.png?raw=true)

## Activity 2-5

Home Page

![home](https://github.com/gabriellemadden/ECE444-F2021-Lab5/blob/styling-practice/lab_submission/home.png?raw=true)

Results Page - Form

![form](https://github.com/gabriellemadden/ECE444-F2021-Lab5/blob/styling-practice/lab_submission/results-form.png?raw=true)

Results Page - Results Table

![table](https://github.com/gabriellemadden/ECE444-F2021-Lab5/blob/styling-practice/lab_submission/results.png?raw=true)

## Activity 6
In the old UI, the results table is difficult to understand because there are no dividers between the cell items and the table headers are right-aligned. In the new  UI, the borders clearly divide the cell information and the centre-alignment of the headers makes
it much easier to tell what the column information is representing.

# CARTE Education Pathways

## Description
Welcome to CARTE's in-development tool for course selection at UofT. Education Pathways allows for more intelligent course searching, by matching not just the terms you search, but ones relevant to them. The more terms you search for, the more relevant your results will be! Even try searching across disciplines for the courses that best cover each.

Whatever year you are looking for, Education Pathways will also suggest courses in earlier years that will best help you to prepare. To get the most out of this, try searching for courses in a later year and see what is suggested for your current one.

We are looking for feedback to improve Education Pathways and make it more useful for students. If you have ideas or suggestions, please email us!

## Setup Instructions

### With Docker



## Repository files:

`./Procfile ./wsgi.py` *tells gunicorn how to run the program*

`./environment.yml  ./requirements.txt` *specifies python requirements for anaconda and pip respectively*

`./__init__.py` *main flask code*

`./readme.md` *this file*

`./resources:` *contains datasets used in the program*

`course_vectorizer.pickle df_processed.pickle`

`course_vectors.npz       graph.pickle`

`./static:` *contains any static elements of the webpage, in this case just the CARTE logo*
`CARTE_logo.jpg`

`./templates:` *contains flask templates for rendering HTML*

`_formhelpers.html course.html       index.html        results.html`
