# RESTify Experiment Replication Package

All you need to replicate our findings, reuse our data or tools.

 > **THIS VERSION IS A STATIC, SELF-CONTAINED SNAPSHOT, CREATED FOR THE MODELS ARTIFACT EVALUATION. UNLESS YOU ARE A REVIEWER, PLEASE [ACCESS THE ORIGINAL](https://m5c.github.io/RestifyReplicationPackage/)**.

**A few things to consider for this STATIC SNAPSHOT version**:

 * To ensure self-containment of this artifact submission, references to individual package components are provided as additional file system links.
     * Links to the original components are indicated like this: {--original link sample--}
     * Links to local file system snapshot alternatives are indicated like this: {==local filesystem snapshot==}
 * In some cases, this reduces convenience, for e.g. README.md files of software artifacts are not nicely rendered, when accessed as file system links.
 
*Hint, for result replication*:

 > **The simplest way to replicate our study findings**, is [{--the prepared docker image--}](https://github.com/m5c/RestifyJupyter#dockerized-notebook) [{==snapshot-contained link==}](../../RestifyJupyter/README.md#dockerized-notebook) (Section: "*Dockerized Notebook*"). Within just a few minutes you can power up a Jupyter Notebook and replicate all statistics and figures of our paper. You only need docker and a browser.


## About

This webpage servers as entry point for the artifact submission of our [MODELS 2024 conference](https://conf.researchr.org/track/models-2024/models-2024-technical-track#Practice-Track) contribution.

 * Main purpose of this replication package is to allow fast and independent replication of all our results and interpretations.
 * We carefully documented all our methodology, and automated our analysis. E.g. all paper figures are generated from raw data, and we provide you with the means to conveniently replicate them and validate correctness of our findings on your local machine.  
 * Furthermore we publish all study material and tools used to conduct the study, so you can easily replicate the experiment, or reuse parts of our material for follow-up research.


## Package Content

We now present the various components of our artifact submission. Each of the items enumerated in the remainder also corresponds to matching entry on the left-side navigation bar.

### Replication

* [Result Replication](replication.md): Center-piece of our replication package is a Jupyter Notebook that takes you through the data analysis and replicates all paper figures on your machine.
    * We offer various levels of inspection, from static prerendered notebook, to dockerized local replication, to in-depth analysis of the implementation in PyCharm.
    * For the replication we provide you with the raw data collected throughout the experiment. Then you crunch it locally and replicate the findings, all using convenient scripts.
    * The data analysis was coded for easy inspection and transparency. You can at any point in time inspect the well-documented codebase, and verify our implementation.
  

### Material

In addition to *replication* of our findings, we provide everything needed to replicate the experiment itself, i.e. we publish the sources for all material and tools involved the study conduct. We do so to provide transparency on all details of our methodology, and ease replication of our study by colleagues, as well as reuse of our tools for future related work.

 * [Recruitment Material](recruitment.md): Sources and rendered HTML version of the webpage used for participant recruitment.
 * [Group Allocation Algo](allocation.md): Source code and documentation of the algorithm implemented to create a balanced participant groups (optimizes comparable group skillsets).
 * [Task Instruction Material](material.md): Sources and rendered HTML version with textual and video task instructions for all four control groups.
 * [Sample Legacy Applications (Objects)](objects.md): The sample applications used task for training or actual conversion task.

### Data and Evaluation

 * [Submission Correctness Evaluation Tool](analyzer.md): Sources and documentation of the analyzer tool that we implemented to assess correctness of participant submissions. A reusable tool to test REST APIs against a predefined interface and produce correctness reports.
 * [Raw Experiment Collected Data](data.md): Raw data collected throughout the experiment: CSV and textual summary files that conclude data extracted from video material viewing, such as transcript of observations and time measurements for the individual conversion tasks.

