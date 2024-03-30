# Result Replication

 > tl;dr: We offer  [a pre-rendered Jupyter Notebook](https://github.com/m5c/RestifyJupyter/blob/master/Restify.ipynb). (No installation required)
 > If you want to actually *replicate*, try [the *docker*](https://github.com/m5c/RestifyJupyter#dockerized-notebook) for minimal effort. (Takes about 2 minutes of your time) 

All statistical figures and listings in our paper submission were created programmatically.  
The code to produce them is publicly available and well documented.

On the [dedicated project page](https://github.com/m5c/RestifyJupyter), we provide:

 * The raw data (but you get that also here, for your convenience ;) )
 * The code used for statistical analysis
 * Instructions on how to very rapidly replicate / reproduce our results

> Spoiler alert: we use docker + jupyter, so you don't need to install anything.

## Where to Start

We provide several access points, for fast to thorough replication:

 * Static, rendered Jupyter Notebook: You can inspect a static one-shot render of our Notebook [on GitHub. You only need a browser.](https://github.com/m5c/RestifyJupyter/blob/master/Restify.ipynb)  
Please note that the anonymization process damaged some of the integrated figures. We apologize for the inconvenience.
 * Dynamic, using a docker configuration. See [install instructions for Docker](https://github.com/m5c/RestifyJupyter#dockerized-notebook).
 * Dynamic, your own Jupyter Notebook. See [install instructions for native Jupyter](https://github.com/m5c/RestifyJupyter#manual-notebook)
 * Dynamic, using the raw python sources, and an IDE. See [install instructions for PyCharm](https://github.com/m5c/RestifyJupyter#pycharm-ide)
