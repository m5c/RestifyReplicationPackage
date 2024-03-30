# RESTify Experiment Replication Package

All you need to replicate our findings, in one place.

> **tl;dr:** We offer  [a pre-rendered Jupyter Notebook](https://github.com/m5c/RestifyJupyter/blob/master/Restify.ipynb). (No installation required)

> If you want to actually *replicate*, try [the *docker*](https://github.com/m5c/RestifyJupyter#dockerized-notebook) for minimal effort. (Takes about 2 minutes of your time)


## About

As part of our submission to the [MODELS 2024 conference](https://conf.researchr.org/track/models-2024/models-2024-technical-track#Practice-Track), we offer a replication package that allows fast and independent replication of all our results and interpretations.  
This page serves as starting point for the various components needed.

## Package Content

This section hot-links package content by scope

### Replication

* [Result Replication](replication.md): Center-piece of our replication package. 
    * You can recreate all paper figures and numbers using an interactive notebook.
    * We provide the raw data. You crunch it yourself, using our provided statistical scripts.
    * You can inspect a pre-rendered notebook or run a one liner-docker command for local replication.
  

### Material

 * [Recruitment Material](recruitment.md): A reference to the webpage used for participant recruitment.
 * [Group Allocation Algo](allocation.md): Source code and documentation of the algorithm implemented to create a balanced group allocation.
 * [Task Instruction Material](material.md): Collection with instructions for the task instructions. There are four, since the experiment had four groups with diverging task context and order.
 * [Sample Legacy Applications (Objects)](applications.md): The sample applications used task for training or actual conversion task.

### Collected Data

 * [Raw Experiment Collected Data](data.md): Raw data collected throughout the experiment.
 * [Submission Correctness Evaluation Tool](analyzer.md): Sources and documentation of the analyzer tool that we implemented to assess correctness of participant submissions. 
 * [Extracted Times and Video Observations](data).md: CSV and textual summary files that conclude data extracted from video material viewing, such as transcript of observations and time measurements for the individual conversion tasks.

