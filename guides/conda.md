# Test
## Create environment

- Create an empty ‘.nonadmin’ file
	> https://github.com/conda/conda/issues/2136

	```bash
	echo “”> c:\Anaconda3\.nonadmin
	```
- Create the environment named ‘environment_name’

    ```bash
    conda create -n environment_name
    ```

## Activate environment

```bash
activate environment_name
```

# Prod
## Install miniconda
http://conda.pydata.org/miniconda.html


# Shared
## Install libraries

```bash
conda install pandas -y
conda install matplotlib -y
conda install jupyter -y
conda install plotly -y
conda install scikit-learn -y
pip install jupyter_dashboards
jupyter dashboards quick-setup --sys-prefix
pip install jupyter_cms
jupyter cms quick-setup --sys-prefix
pip install jupyter_dashboards_bundlers
jupyter dashboards_bundlers quick-setup --sys-prefix
pip install jupyter_declarativewidgets
jupyter declarativewidgets quick-setup --sys-prefix
conda install xlwings -y
conda install numpydoc -y
conda install pyodbc -y
conda install pytest -y
pip install google-api-python-client
conda install psycopg2 -y
conda install cython -y
pip install dotmap
pip install dill
conda install ujson -y
conda install -c conda-forge jupyter_contrib_nbextensions=0.2.1 -y
```
