# Visual Search Experiment

Homework to the "Informatics and Coginitive Science 1" course - Visual search experiment. 
View the render of the report: 
[visual_search_experiment-report](https://raw.githack.com/dbeinhauer/visual_search_experiment/main/visual-search-experiment-report.html)

## Setup

Firstly, you need to have [poetry](https://python-poetry.org/docs/) installed.
```sh
curl -sSL https://install.python-poetry.org | python3 -
```

Then setup the environment by running.
```sh
poetry install
```

Finally, enter the environment.
```sh
poetry shell
```

You can run ```jupyter lab``` from within the environment with all the required dependencies present.


## Generating report

To generate a html report run

```
jupyter nbconvert --to html visual-search-experiment-report.ipynb --execute --template pj
```
