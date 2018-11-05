# Course on Data Visualization with Python (Winter Term 2018/19)

This is the repository for our data visualization course (https://ekvv.uni-bielefeld.de/kvv_publ/publ/vd?id=140903966)

- Why visualize data, why programming, why Python?  
    - [General Introduction](notebooks/01_general_introduction.ipynb)  
    - [Example Visualization](notebooks/01_dinosaur_dozen_example.ipynb)   
- Introduction to Python  
    - [First steps with Python](notebooks/02_intro_to_python.ipynb)  
- Introduction to Pandas and
    - [First steps with Pandas and Matplotlib](notebooks/03_intro_to_pandas.ipynb)  
- Using 'for' Loops and Plotting with Matplotlib and Seaborn
    - [First plot](notebooks/04_annotated_scatterplot.ipynb)

### Running this repository

Data analysis is performed with Python 3 using mainly numpy, scipy, pandas, scikit-learn, matplotlib, seaborn and jupyter.

To run all the scipts, you can create a virtual environment, by first installing miniconda  
  
https://conda.io/miniconda.html  

Then you can create a virtual environment in the folder into which you cloned this repository

```shell
conda create --name abbildungen --file requirements.txt
```

if this does not work, try installing the modules by hand, like this


```shell
conda create --name abbildungen -c conda-forge numpy scipy matplotlib seaborn scikit-learn pandas nilearn jupyter jupyterlab statsmodels jupyter_contrib_nbextensions jupyter_nbextensions_configurator rise -c r r-essentials

```


Then you can start the environment like this


```shell
source activate abbildungen
jupyter notebook
```

or, under Windows, start 'anaconda prompt' and try

```shell
conda activate abbildungen
jupyter notebook
```

### Contact

For questions or comments please write to [martin.wegrzyn@uni-bielefeld.de](mailto:martin.wegrzyn@uni-bielefeld.de)

