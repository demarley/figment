<img src="data/figment.png" width="100">

# Figment

Collection of projects for data science, attempts at kaggle competitions, and learning new languages/techniques.

## Getting Started

In the different directories, 
I have Jupyter notebooks that are written in the respective languages for each project.
This is structured so that I can organize different notebooks and test
the relevant libraries and techniques.

_Not all 'projects' will be written in multiple languages, 
but I will try to do that to have a nice comparison._

### Python

The `*/python/` notebooks are designed to work on [Google Colab](https://colab.research.google.com/).  
Where possible, I'm trying to use Python3 because I have little experience with it compared to Python2.

My previous experience with Python has mostly involved high-energy physics analysis 
(software frameworks, plotting, and neural networks).
Here I am developing some solutions to kaggle competitions and trying out new libraries and techniques.

### Julia

I don't have any prior experience with [Julia](https://julialang.org/), 
so this is also a way for me to experiment with the language and develop some computer science skills.
The `*/julia/` notebooks are designed to work on [JuliaBox](https://juliabox.com/).

_NB: There may be unintended incompatibilities based on what packages JuliaBox
lets you download versus what I have available locally._

### R

I also don't have any prior experience with R,
so this is another way for me to practice with this language.  
The `*/r/` notebooks are only tested locally, for now, 
but I will be investigating open source platforms in the future 
(Google Colab, Azure Notebooks, etc.).

_NB: I downloaded R onto my macbook from [here](https://cran.r-project.org/bin/macosx/), version 3.5.1.
And I used [this](https://irkernel.github.io/installation/) reference for installing a jupyter kernel._


## Projects

### Housing Prices

The kaggle housing prices [challenge](https://www.kaggle.com/c/house-prices-advanced-regression-techniques)
is being explored with a different set of notebooks in both `python` and `julia`.

#### Notebooks

Here is a table with a brief description of each notebook contained in the repository.

Notebook | About
-------- | -----
`python/0-housing_prices.ipynb` | Very basic and simple approach using one variable.
`python/1-housing_prices.ipynb` | Basic multivariate / ML techniques (including BDT with `XGBoost`)
`python/2-housing_prices.ipynb` | Basic deep learning approach with `keras+tensorflow`
`python/3-housing_prices.ipynb` | Basic deep learning approach with `pytorch`
`julia/housing_prices.ipynb`    | Learning `Julia` with basic deep learning approach with `Flux`



### Fantasy Football

As a personal exercise in data science, I'm attempting to make some (basic) fantasy football
predictions using information from [nflgame](https://github.com/derek-adair/nflgame).

_For now this is only a python project so I can practice SQL (via `sqlite`)._

#### Notebooks

Here is a table with a brief description of each notebook contained in the repository.

Notebook | About
-------- | -----
`python/0-fantasy-football.ipynb` | Read NFL data from `nflgame` and store relevant information in `sql` database.
`python/1-fantasy-football.ipynb` | Very basic and simple approach for making predictions for one player.
`python/2-fantasy-football.ipynb` | Preliminary attempt to use play-level information for making game-level predictions.



### Personalized Medicine

To practice with natural language processing and using R, this project will explore the Kaggle challenge
[Personalized Medicine: Redefining Cancer Treatment](https://www.kaggle.com/c/msk-redefining-cancer-treatment).  
_NB: The training dataset was too large for GitHub, and will need to be downloaded separately from the Kaggle site._


#### Notebooks

Here is a table with a brief description of each notebook contained in the repository.

Notebook | About
-------- | -----
`r/0-medicine.ipynb` | Exploring the dataset and getting familiar with R.




# Misc.

Some references for performing the work in this repository:

- Python
    - [keras](https://keras.io/)
    - [tensorflow](https://www.tensorflow.org/)
    - [pytorch](https://pytorch.org/)
- Julia
    - [JuliaLang](https://julialang.org/)
    - [Flux](http://fluxml.ai/)
- R
    - [R language](https://cran.r-project.org/)
    - [EDA example](https://www.kaggle.com/headsortails/personalised-medicine-eda-with-tidy-r)
- Remote Work
    - [Google Colab](https://colab.research.google.com/)
    - [JuliaBox](https://juliabox.com/)
- Technical
    - [Elements of Statistical Learning](https://web.stanford.edu/~hastie/ElemStatLearn/)
    - [Julia Tutorials](https://github.com/JuliaComputing/JuliaBoxTutorials)

# Questions, Comments, and Concerns

Please post an issue or submit a PR.
