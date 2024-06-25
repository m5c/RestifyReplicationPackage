# RESTify Experiment Replication Package

Markdown sources for instructions on how to replicate and reuse any component of the *RESTify Experiment*.

 * The sources are compiled to a static HTML page, using MkDocs.
 * An official export of the HTML instructions is hosted [here, on github pages](https://m5c.github.io/RestifyReplicationPackage/).

## Contents

> Deployment on github pages is a bit contrived, for MkDocs wants to host markdown files in the `docs` directory and GitHub wants to deploy HTML sources from the `docs` directory. For updated, use the [`deploy.sh`](deploy.sh) script to move content around until everyone is happy.

* `docs`: is only generated content. Never edit.
* `mkdocs`: the actual page sources. Edit here.

## To test / visualize locally

```bash
 * rm -rf docs
 * ln -snf mkdocs docs
 * mkdocs serve
```

* Now you can live edit the contents of **mkdocs**.

## To build and redeploy:

```bash
  ./deploy.sh
```

## Author

[Maximilian Schiedermeier](https://github.com/m5c)