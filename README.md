# Project-Guide
this is intended to provide you with orientation and assistance during the project.

## Project-Management
- Define cleare goals and responsibilities for individual milestones and subtasks. 
- Define a fixed meeting at least every two weeks to discuss progress together
- if you have any questions, contact your mentor

## Collaboration Tools
The following tools should make it easier for you to work together
- Trello: Use it to define goals and tasks and responsibilities (https://trello.com/home)
- Git resp. Github: in consultation with your mentor and the Techlabs team, an official Techlabs project repo where you can work together on your code and version it with git - just like real software development. (https://github.com/)

## Integrated Development Environment (the place where to do the coding)
We recommend to use the following
- R Studio for R: https://www.rstudio.com/
- Pycharm (Community) for Python: https://www.jetbrains.com/pycharm/
- Or more general Visual Studio Code: https://code.visualstudio.com/

## Useful Frameworks
- Python Basics: Pandas, SciPy, Numpy, Matplotlib
- Python Machine Learning: scikit-learn, Keras, Pytorch, Tensorflow

### Backend Frameworks
- Python: Flask, Django

### Frontend  Frameworks
- JavaScript: React, Vue, Angular

### Data Science Code Structure Example

Project Organization
------------

    ├── LICENSE
    ├── Makefile           <- Makefile with commands like `make data` or `make train`
    ├── README.md          <- The top-level README for developers using this project
    ├── data
    │   ├── external       <- Data from third party sources.
    │   ├── interim        <- Intermediate data that has been transformed
    │   ├── processed      <- The final, canonical data sets for modeling
    │   └── raw            <- The original, immutable data dump
    │
    ├── models             <- Trained and serialized models, model predictions, or model summaries
    │
    ├── notebooks          <- Jupyter notebooks
    │
    ├── references         <- Data dictionaries, manuals, and all other explanatory materials
    │
    ├── reports            <- Generated analysis as HTML, PDF, LaTeX, etc
    │   └── figures        <- Generated graphics and figures to be used in reporting
    │
    ├── requirements.txt   <- The requirements file for reproducing the analysis environment, 
    │                         e.g. generated with `pip freeze > requirements.txt`
    │
    ├── setup.py           <- makes project pip installable (pip install -e .) so src can be imported
    ├── src                <- Source code for use in this project.
        ├── __init__.py    <- Makes src a Python module
        │
        ├── data           <- Scripts to download or generate data
        │   └── make_dataset.py
        │
        ├── features       <- Scripts to turn raw data into features for modeling
        │   └── build_features.py
        │
        ├── models         <- Scripts to train models and then use trained models to make
        │   │                 predictions
        │   ├── predict_model.py
        │   └── train_model.py
        │
        └── visualization  <- Scripts to create exploratory and results oriented visualizations
            └── visualize.py

--------

## More Information
Take some time to search for for smaller examples that are already publicly available on Github, so you can get a quick first overview of how different problems could be solved.

## Deployment 
- DigitalOcean: https://www.digitalocean.com/
- Heroku: https://www.heroku.com/


Happy Coding :-) 
