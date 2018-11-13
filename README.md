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

#### Notebooks

Here is a table with a brief description of each notebook contained in the repository.

Notebook | About
-------- | -----
`python/0-fantasy-football.ipynb` | Read NFL data from `nflgame` and store relevant information in `sql` database.
`python/1-fantasy-football.ipynb` | Very basic and simple approach for making predictions for one player.
`python/2-fantasy-football.ipynb` | Preliminary attempt to use play-level information for making game-level predictions.



# Misc.

Some references for performing the work in this repository:

- Python
    - [keras](https://keras.io/)
    - [tensorflow](https://www.tensorflow.org/)
    - [pytorch](https://pytorch.org/)
- Julia
    - [JuliaLang](https://julialang.org/)
    - [Flux](http://fluxml.ai/)
- Remote Work
    - [Google Colab](https://colab.research.google.com/)
    - [JuliaBox](https://juliabox.com/)
- Technical
    - [Elements of Statistical Learning](https://web.stanford.edu/~hastie/ElemStatLearn/)
    - [Julia Tutorials](https://github.com/JuliaComputing/JuliaBoxTutorials)

# Questions, Comments, and Concerns

Please post an issue or submit a PR.

_The image represents Figment the dragon from 
[Disney's EPCOT Imagination Land](https://disneyworld.disney.go.com/attractions/epcot/journey-into-imagination-with-figment/)._
