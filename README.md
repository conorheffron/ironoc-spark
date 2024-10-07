# ironoc-spark

Run Jupyter Notebook via Docker & map workspace location:
```shell
docker run -p 8888:8888 -v /Users/conorheffron/workspace/ironoc-spark:/home/jovyan jupyter/minimal-notebook
```
Run Jupyter Notebook via Docker with PySpark & JDK pre-installed:
```shell
docker run -it --rm -p 8888:8888 jupyter/pyspark-notebook
```
- Add csv, json & ipynb files to workspace directory
