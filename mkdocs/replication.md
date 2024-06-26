# Result Replication

All statistical figures and listings in our paper submission were created programmatically.  
The code to produce them, from raw data (which we also provide) is publicly available and well documented.

As part of the [dedicated component](https://github.com/m5c/RestifyJupyter), we provide:

 * The raw data
 * The code used for statistical analysis
 * Instructions on how to rapidly run (and reuse!) the code

## Where to Start

Depending on how-thorough you want to dive into the result replication, here are your four options:

  1. Static **inspection**, rendered Jupyter Notebook: You can view a static, non-executable render of our Notebook [on GitHub. You only need a browser.](https://github.com/m5c/RestifyJupyter/blob/master/Restify.ipynb)
  2. Dynamic **result replication**, using a docker configuration: You can **execute and replicate** all figures and results, with minimal installation effort. See [{--install instructions for Docker--}](https://github.com/m5c/RestifyJupyter#dockerized-notebook) [{==docker install instructions on local snapshot clone==}](../../RestifyJupyter/README.md#dockerized-notebook)
  3. Dynamic **result replication**, using your own Jupyter Notebook: You can replicate and extend our analysis. See [{--install instructions for native Jupyter--}](https://github.com/m5c/RestifyJupyter#manual-notebook) [{==manual install instructions on local snapshot clone==}](../../RestifyJupyter/README.md#manual-notebook)
  4. Dynamic **result replication and function reuse**, using the raw python sources, and an IDE: You have full control over all analysis functions and their internals. See [{--install instructions for PyCharm--}](https://github.com/m5c/RestifyJupyter#pycharm-ide)  [{==PyCharm install instructions on local snapshot clone==}](../../RestifyJupyter/README.md#pycharm-ide)
