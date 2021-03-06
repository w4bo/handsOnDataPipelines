# Hands On Data Pipelines

[![build](https://github.com/w4bo/handsOnDataPipelines/actions/workflows/build.yml/badge.svg)](https://github.com/w4bo/handsOnDataPipelines/actions/workflows/build.yml)

## Some feedback

- Migrare a COLAB? Così da evitare Docker del tutto
- Tagliare di molto i dettagli tecnici (non c'è tempo per farli)
- La parte Big Data è praticamente inutile, magari integrare al volo PySpark per fare vedere che anche lì esiste la metafora del dataframe
 
## Contents

This lab will cover:

- Data cleaning and preprocessing (hands on Python and Pandas)
- Machine learning (hands on Python and Sklearn)
- Big data elaboration (hands on Scala and Spark)
- OLAP and data visualization (hands on Tableau)

Each steps covers both theory and practice.

To start working on this project:
- Download and unzip this repo: https://github.com/w4bo/handsOnDataPipelines/archive/refs/heads/main.zip
- Enter the unzipped directory
- Run the build script
    - in Windows (both cmd and powershell) run `.\build.bat`
    - in Linux run `./build.sh`

## Technical requirements

Tu run this lab you need to install
- Docker. Ensure that docker is running by executing `docker run hello-world`
- Tableau

How many of you are familiar with...

- Virtualization (`docker`)
- Project versioning (`git`), dependency management (`venv`), and build automation (`gradle`)
- Coding (`python`, `scala`)
- Data manipulation (`pandas`), and machine learning (`sklearn`)
- Big data processing (`spark`) 
- OLAP and data visualization (`tableau`)

Besides Tableau, all the necessary software is shipped with docker containers
