# AWS-EMR-setup

Installing pip3:

```bash
sudo yum install python34-setuptools
sudo easy_install-3.4 pip
```
Using python3 with pyspark (use python3 with pyspark):
```bash
export PYSPARK_PYTHON=python3
```
Install findspark (to use pyspark with Jupyter notebook):
```bash
sudo /usr/local/bin/pip3 install findspark
```
Set SPARK_HOME (for findspark package):
```bash
export SPARK_HOME=/usr/lib/spark
```

Setup Jupyter Notebook:

https://github.com/justinng1/AWS-EC2-setup/blob/master/docs/jupyter_notebook.md


Notes:

m1.medium instances will not work with Spark.
