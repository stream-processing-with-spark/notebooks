# Notebooks
This repository contains interactive notebooks that support the code materials found in the book.
Notebooks provide us with an interactive environement where we can directly execute code and inspect the result of our operations.

---
**NOTE**

We are aware of an issue of the Spark Notebook not correctly loading the Kafka dependencies. 
We are working on a solution for this.

---

## Using the Spark Notebook
The Spark Notebook is a reactive notebook implementation based on the IPython UI. 
It provides dedicated support for Spark using Scala, making is an easy-to-use choice to work with Spark and Scala.

To install the Spark Notebook to use with the notebooks in this repository, download a `master` version of the notebook from the distribution site: http://spark-notebook.io/
Clone this repository somewhere on your Linux or Mac machine (Windows support is precarious. When using Windows, we recommend to use a Linux VM instead)
With this repository cloned, set an environment variable to point to it:
```
export NOTEBOOKS_DIR=`pwd`/notebooks
```
and start the Spark Notebook:
```
cd <notebook-install-dir>
./bin/spark-notebook
```

If you need to ask a question or require additional support, please open an [issue](https://github.com/stream-processing-with-spark/notebooks/issues) in this project
