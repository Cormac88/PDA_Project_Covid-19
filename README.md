![Coronavirus](https://upload.wikimedia.org/wikipedia/commons/thumb/9/94/Coronavirus._SARS-CoV-2.png/768px-Coronavirus._SARS-CoV-2.png)

# PDA_Project_Covid-19
Using statistics available about Ireland to simulate data about Covid-19

## Objectives of this Project

The objective of this project was to synthesise and simulate some data about Covid-19 cases using the NumPy Random package and basing this off real data from sources such as the Central Statistics Office (CSO) and the HSE. <br>

To breakdown this project, I started by creating the Age variable first. I got some statistics from the web and got the age data simulated and put this into a Pandas DataFrame using NumPy. This was achieved  along with simulating some data on:

- Age
- Gender
- Underlying Conditions
- Vaccination Status
- Hospitalisation
- Admission to ICU
- Death/Recovery

These statistics have been added to a pandas dataframe called `dfcovid`. I also created 2 smaller dataframes called `dfcovid_hospitalised` and  `dfcovid_icu` to analyse the deaths.<br>

I then did some data analysis using Seaborn. The plots that I used are as seen below:
1. Countplots
2. Histograms
3. Pieplots
4. Boxplots
5. Catplots <br>

# Quick Steps

### nbviewer:

[![nbviewer](https://raw.githubusercontent.com/jupyter/design/master/logos/Badges/nbviewer_badge.svg)](https://nbviewer.org/github/Cormac88/PDA_Project_Covid-19/tree/main/)

### Binder:

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/Cormac88/PDA_Project_Covid-19/HEAD)

# Install

## Installing Python and Jupyter Notebook

1. Python and jupyter lab are needed to run the `.ipnb` files in this repository.

2. Download `Python` from https://www.python.org/.

3. Type `pip install jupyterlab` and press enter.

4. Wait for jupyter to finish installing.

Please see the [official Installation](https://jupyterlab.readthedocs.io/en/stable/getting_started/installation.html) of Jupyter Lab page if you are having issues.

# Running the Code

1. Change directory to the folder that contains the.ipynb file you wish to run.

2. Type `jupyter lab`.

3. Jupyter lab will open in your browser as a new tab. Keep the command prompt window open as it needs to stay running while Jupyter Notebook is active.

4. Click on the `.ipynb` file you wish to run.

5. Click on `Kernel` and then select `Restart Kernal and Run All Cells`.

6. When finished, close the tab in your browser and then press press 'ctrl + C' in the command prompt to end the session.

# Credits

I heavily relied on the following YouTube channels:

[Kimberly Fessel](https://www.youtube.com/channel/UCirb0k3PnuQnRjh8tTJHJuA)<br>
[Corey Schafer](https://www.youtube.com/c/Coreyms)<br>

# Contact

[Cormac Hennigan](mailto:G00398284@gmit.ie)