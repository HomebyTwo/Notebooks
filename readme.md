## Installation

Clone the repository on your machine and open the project directory:

```sh
$ git clone --recursive https://github.com/homebytwo/notebooks.git && cd notebooks
```

Make a new virtualenv and install the required libraries with pip:

```sh
$ pip install -r requirements.txt
```

Open the notebook with Jupyter:

```sh
$ jupyter notebook
```

## Configuration

Retrieve your Strava API token from https://www.strava.com/settings/api and put it in a file named `STRAVA_TOKEN` in the base directory of the project.
