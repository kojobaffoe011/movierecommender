# MLLIB

## Description

This repo contains

- a dataset from movie lens which contains 1,000,209 anonymous ratings of approximately 3,900 movies made by 6,040 MovieLens users who joined MovieLens in 2000. More info about the dataset can be found in the `ml-1m/README.md`
- a jupiter notebook that uses the spark mllib to identify what users like and make movie recommendations using apache spark's mllib ALS model

## Prerequisites

- Python 3.x installed
- `pip` package manager
- Spark installed and running
- Jupiter Notebook

## Setup Instructions

1. **Create a virtual environment (optional but recommended):**
   `python -m venv venv`

2. **Activate the virtual environment:**

- On Windows:
  ```
  venv\Scripts\activate
  ```
- On macOS/Linux:
  ```
  source venv/bin/activate
  ```

4. **Install the dependencies:**
   pip install -r requirements.txt

## Running the Code

After installing the dependencies, make sure Spark is running and locate the main file `recommendation.ipynb`

## Additional Information

To deactivate the virtual environment, use:
`deactivate`
