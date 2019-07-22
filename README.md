# spark-python-talk
Content for a talk on Spark using Python (UDF, Pandas_UDF, Koalas)

## Running the Notebooks

With Docker installed, run the following command to run the Jupyter notebooks:

```bash
docker run --rm -p 8888:8888 -v "$PWD":/home/jovyan/work jupyter/pyspark-notebook
```

This command will display the Jupyter notebook URL.

## Generating slides

Run this command to generate the html slides for the presentation from a Jupyter terminal.
This will output an html file that can be opened on the host machine:

```bash
jupyter nbconvert work/pyspark_talk.ipynb --to slides
```
