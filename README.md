# Northwestern Research Computing Services - Webscraping with Selenium (Python) Workshop

## General Information
Selenium is a browser automation tool that allows users to interact with html elements from any website. In this workshop, we will introduce attendees to Selenium and ChromeDriver, a separate executable that facilitate communication between Selenium and Google Chrome. Attendees will learn to deploy these tools to automatically search for and grab data from websites.

## Preworkshop Setup
Please have Anaconda installed as we will use Jupyter Notebook/Lab. 

It is also a good practice to create a new environment to avoid any issue with dependencies. Make sure to launch Jupyter Notebook/Lab from this environment. To create a new environment named webscraping, from your terminal:

```console
conda create -n webscraping python=3.9 pandas matplotlib jupyterlab selenium
```
After this line finishes, you will have created a conda environment that includes selenium. To activate the environment.

```console
conda activate webscraping
```
If you launch Jupyter Lab from terminal, remember to activate the environment first.

As mentioned in the introduction, we will need a webdriver, and in our case ChromeDriver, to interact with websites. In the webscraping environment, run

```console
pip install webdriver-manager
```

