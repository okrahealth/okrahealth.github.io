---
title: "Origin of OkraHealth and Pre-Alpha Release"
description: "OkraHealth recognized a need for interpretable software health."
date: 2019-05-23T12:24:47+01:00
publishDate: 2019-03-28T12:24:47+01:00
author: "Tyler Brown"
draft: false
images: []
tags: []
---

OkraHealth came out of a project-based course I took while finishing my
[MS in Data Science](https://www.khoury.northeastern.edu/program/data-science-ms/) at 
Northeastern University. [DS 6050 - Expeditions in Data Science](http://janvitek.org/events/NEU/6050/) was being piloted as an alternative to the core capstone class
DS 5500, Information Visualization, in Spring 2019 only. The DS 6050 course
encouraged students to solve **real-world data science problems** by applying
the skills they obtained in previous classes of their Data Science program. Successful
completion of the DS 6050 course required practical experience with key steps 
of any Data Science project. All projects were individual. An expert panel from industry 
reviewed each of the projects and provided feedback.

## DS 6050 Course Structure and Requirements

The projects focused on analyzing a large dataset extracted from GitHub. This
dataset required each student to overcome challenges related to large scale data
acquisition (the target was 1 million projects), data cleaning, data representation
(how the data is modeled), data storage (define a storage format and location using
a relational database), how to analyze the data, and choosing machine learning 
techniques, as well as visualizing the results. The Data Science practices discussed
in previous classes can be summarized as follows (adopted from Prof. Jan Vitek and
“The levels of data science class” by Jeff Leek):

* *Asking:* How to define a question, identify relevant data, and design the experiment.
* *Telling:* Writing about data science, interpreting model figures and results.
* *Practicing:* Implementation skills required to perform the analysis.
* *Scaling:* Figuring out how to deal with large real world datasets.
* *Solving:* Use real data examples, often small, working through them as a case study.
* *Science:* Formulate your defined question, then solve it at scale.

All work from the project was submitted as an open source project in a GitHub repository.
My classwork can be reviewed in [github.com/tbonza/EDS19](https://github.com/tbonza/EDS19).
A more in depth reading of my findings are available for review in my [DS 6050 project report](https://github.com/tbonza/EDS19/blob/master/project/report/report.pdf). You can
also review the [initial Okra Python package](https://github.com/tbonza/EDS19/tree/master/okra) if it's of interest.

## US PyCon 2019 Sprints

PyCon is a the largest annual gathering for the community using and developing the
open-source Python programming language. [US PyCon 2019](https://us.pycon.org/2019/)
consists of five events in a row: (1) tutorial days, (2) conference days, 
(3) development sprints, (4) summits, (5) and a job fair. Development sprints help 
advance your favorite open source project. Space and infrastructure is provided and
all experience levels are welcome. OkraHealth was initially migrated from a DS 6050 
class project to an open source project during the development sprints at US PyCon 2019.

## Releasing a Pre-Alpha Version

A pre-Alpha version of OkraHealth is scheduled to be released by June 27th, 2019. This
release is scheduled to be presented at the [Django Boston Meetup Group](https://www.meetup.com/djangoboston/). We anticipate the pre-Alpha version having the following features:

1. Interpretable software health analytics for [OPENedX](https://open.edx.org/) and its
   corresponding Python dependencies.
1. RESTful API for consumption of the software health analytics ([Okra-API](https://github.com/okrahealth/okra-api)). 
1. Open source statistical library used for the software health analytics and data pipeline 
   ([Okra-Core](https://github.com/okrahealth/okra)).
   
Please direct any feature enhancements or issues to the corresponding GitHub issues 
pages for each of the linked, [Okra-API](https://github.com/okrahealth/okra-api/issues) 
and [Okra-Core](https://github.com/okrahealth/okra/issues), repositories.
