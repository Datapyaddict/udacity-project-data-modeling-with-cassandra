# <u>Data Engineer nanodegree / Udacity project : data modelling with Cassandra</u>
## Table of Contents
1. [Project info](#project-info)
2. [Repository files info](#repository-files-info)
3. [Prerequisite to scripts run](#pre-requisite)


***

### Project info

Sparkify, a startup, wants its analytics team to analyse the data collected on songs and user activity from its music streaming app.
The data are stored in a folder of csv files. 
The purpose of this project is to model the data by creating tables in Apache Cassandra to run queries in order to answer 3 questions.
This is done through a jupyter notebook.

The steps of the process are :
- load the csv files stored in `event_data` folder,
- produce a single file `event_datafile_new.csv` containing all the data from the csv files with the columns described in `/images/image_event_datafile_new.jpg"`




***
### Repository files info

* `event_data` folder contains the csv files 
* `/images/image_event_datafile_new.jpg"` contains the columns expected in the output file `event_datafile_new.csv`.
* `event_datafile_new.csv` is the csv file containing all the data collected from csv files in folder `/event_data` . 
* `Project_cassandra_modelling.ipynb` is the jupyter notebook that loads the csv data  into Cassandra database and runs the queries to answer the 3 questions raised.



***
### Prerequisite to scripts run

* Create a [Cassandra database](https://phoenixnap.com/kb/install-cassandra-on-windows#:~:text=1%20Step%201%3A%20Install%20Java%208%20on%20Windows.,3%3A%20Download%20and%20Set%20Up%20Apache%20Cassandra.%20)
* install cassandra driver for python.
* run `Project_cassandra_modelling.ipynb`.

***