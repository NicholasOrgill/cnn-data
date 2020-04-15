# cnn-data
This holds the CSVs for all CNN training for my MSci thesis.

The Jupyter Notebook in this repository can be run by installing Jupyter lab locally on your machine—installation instructions can be found here: https://jupyter.org/install

Once installed, you need to install the required dependencies to run the graphing software in the Jupyter Notebook. I would recommend using a virtual environment in Python for this, for which you can find installation instructions here: https://packaging.python.org/guides/installing-using-pip-and-virtual-environments/

Once you have your virtual environment set up, install the required dependencies from requirements.txt using the following command in your terminal:

```bash
jupyter nbextension enable --py widgetsnbextension
```

Finally, run the Jupyter Notebook server by simply typing the following command when in the repository root:

```bash
jupyter notebook
```

This will open up a new web browser window, where you can select `cnn.ipynb`.

Run each cell to see the results in 2D, 3D, and to view the images that the neural network failed to classify in specific training runs.

