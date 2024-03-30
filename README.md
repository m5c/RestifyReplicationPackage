# Experiment Replication Package

## Contents

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