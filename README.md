# Interactive dashboard using panel and hvplot.

This project was used as a way of learning and practicing different python vizualization tools. 
Through this code I could learn more about panel and hvplot as also about different kinds of widgets and pipelines and their returns. 

The dataset used in here is a car information dataset which I chose because my amazing husband loves cars and I wanted to show him some magic in action, but there are many different possibilities, use your imagination!!. 

But before we talk about It, I will clarify how to start implementing using jupyter lab and anaconda. 

1 - "Panel provides tools for easily composing widgets, plots, tables, and other viewable objects and controls into control panels, apps, and dashboards." [Panel from Anaconda](https://anaconda.org/anaconda/panel)
So, since Panel is provided by Anaconda, we will start installing and activating conda.
To install you can [click here](https://www.anaconda.com/download/) to choose the best version for you.

2 - Next, we will create an empty folder and inside It we will create and activate a conda env with python 3.9.7.
Use the following command (if you're using a macbook):

### conda create --name (name of your env) python==3.9.7
### conda activate (name of your env)
### conda install pandas numpy panel hvplot jupyterlab

3 - Now, we have our environment completely configured, so We can open jupyterlab and create our notebook to start coding. Use the command jupyter lab after conda completed installing all the packages and let's begin.

4 - Once Jupyter Lab started, open a terminal inside It so We can activate our conda env and install ipykernel and activate python 3.9.7 inside It. 

Use the following steps:

### conda activate (name of your env)
### python -m ipykernel install --user --name=(your ipykernel name)
### conda activate (your ipykernel name)

Open your ipykernel in your notebook inside jupyterlab and choose the one you created.

<img width="953" alt="Captura de Tela 2023-05-01 às 17 09 40" src="https://user-images.githubusercontent.com/101155921/235522534-f7d07c33-fa93-43db-9d95-363cbcff6274.png">

5 - Now you can start coding. After your code is complete, go back to the terminal and run:
### panel serve (your_notebook_name.ipynb) 

It will run locally your dashboard. You will have somthing like this:


https://user-images.githubusercontent.com/101155921/235524245-987102ad-25e5-4175-8382-5f03c3de08b0.mov

Hope you liked It, have a nice day and thanks for your attention!!
