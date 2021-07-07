# RISE boilerplate

### Install RISE

```
conda create --name rise python=3.8
conda activate rise
pip install jupyter RISE
conda install -c conda-forge jupyter_contrib_nbextensions
jupyter contrib nbextension install --user
conda install -c conda-forge jupyter_nbextensions_configurator
```

### Enable Jupyter Notebook extension for RISE


![Jupyter Notebook Extension RISE](extension.png)


### Run Notebook 

![Modified theme](theme_overview.png)

* Run `01_rise_theme_install.ipynb`
* Restart notebook and verify theme has been applied


### How to use RISE

![Activate slide type](activate_slider_type.png)
![Select slide type](select_slider_type.png)


## Using conda env yml file

To recreate the env using conda use `environment.yml`.


### Reference:

* https://www.youtube.com/watch?v=dAxWpE7_v1A
* https://github.com/firasm/altair_talk