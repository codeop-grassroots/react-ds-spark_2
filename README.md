# Apache Spark

## Introduction
Becoming a pro with Apache Spark and PySpark


## Getting started

### Requirements
- Docker
- Docker compose

##### With Docker Compose: the easy way

`````
docker-compose up
`````

#### With Docker

To run the project first we need to pull the docker image:
````
docker pull jupyter/pyspark-notebook
````

Once we have the image downloaded, we can run it:
````
docker run -v ~/nbs:/home/jovyan/work -d -p 8888:8888 jupyter/pyspark-notebook
````

To preserve your work:
`````
sudo chown 1000 ~/nbs
`````
#### Get Started
In order to load the data into the notebook you will need to create a folder called **data** (work/data/) and put the 3 folders with the parquet files that has been already provided to you.

### The project

`becoming_pro.ipynb` => In this notebook you will find the questions you need to find an answer. Here is when you will became a Spark pro user!!<br>
Hint: Your gonna need to expand your Spark knowledge through its documentation, look for window functions for the quation number 2.
