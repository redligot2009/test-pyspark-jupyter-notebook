## Testing PySpark + Apache Spark with Jupyter Notebook + Conda

Testing out basic features of PySpark locally on a Jupyter Notebook. This assumes you already have PySpark (and Apache Spark by extension) set up on your machine however.

Set up virtual environment (Anaconda):
```cmd
conda env create -n hello-spark -f environment.yml
```

Activate virtual environment

```cmd
Activate hello-spark
```

Open Jupyter notebook for dev / testing purposes.
```cmd
jupyter notebook
```

Resources consulted:
- http://www.learnbymarketing.com/1100/pyspark-joins-by-example/
- https://www.kdnuggets.com/2019/08/learn-pyspark-installation-tutorial.html
- https://bigdata-madesimple.com/guide-to-install-spark-and-use-pyspark-from-jupyter-in-windows/