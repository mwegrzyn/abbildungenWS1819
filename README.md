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
- Visualizing data for exploration and communication
    - [Examples](notebooks/05_exploring_and_communicating.ipynb)  

- Projects:
    - [Perception of being old](notebooks/age_project_example.ipynb)
    - [Number of births on certain holidays](notebooks/birthDates_project.ipynb)
  
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

### Ressources

A list of recommended courses to learn Python and data analysis/visualisation  

- General Introduction to programming with Python:
    - Dave Evans, [Intro to Computer Science](https://eu.udacity.com/course/intro-to-computer-science--cs101)
    - Tal Yarkoni, [NeuroHackademy 2018: Introduction to Python](https://youtu.be/d1QZU-ZPOm0)

- Data analysis with Python
    - Tal Yarkoni, [NeuroHackademy 2018: Data manipulation in Python and Pandas](https://youtu.be/dHBPbBNsKKk)
    - Christopher Fonnesbeck, [Statistical Data Analysis in Python](https://youtu.be/DXPwSiRTxYY)

- Theory of data visualisation
    - Bang Wong, Martin Krzywinski, et al. [Points of View](http://blogs.nature.com/methagora/2013/07/data-visualization-points-of-view.html)

- Working with notebooks
    - Peter Bull & Isaac Slavitt [Data Science is Software | SciPy 2016 Tutorial](https://youtu.be/EKUy0TSLg04)
    - Perez, F., & Granger, B. E. (2015). [Project Jupyter: Computational narratives as the engine of collaborative data science](http://archive.ipython.org/JupyterGrantNarrative-2015.pdf)
    - Rule, A., Tabard, A., & Hollan, J. D. (2018). [Exploration and Explanation in Computational Notebooks](https://hal.archives-ouvertes.fr/hal-01676633/file/chi_2018_computational_notebooks_v32_hal.pdf). In Proceedings of the 2018 CHI Conference on Human Factors in Computing Systems (p. 32).

### Contact

For questions or comments please write to [martin.wegrzyn@uni-bielefeld.de](mailto:martin.wegrzyn@uni-bielefeld.de)

