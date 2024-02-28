# raccoon-spotter

## Overview

This project utilizes the Kedro framework to build and manage a deep learning pipeline for a simple raccoon object detection. We also incorporate Weights & Biases for monitoring and tracking experiments.

## Rules and guidelines
* Don't remove any lines from the provided `.gitignore` file
* Make sure your results can be reproduced by following a [data engineering convention](https://docs.kedro.org/en/stable/faq/faq.html#what-is-data-engineering-convention)
* Don't commit data to the repository
* Don't commit any credentials or local configuration to the repository. Keep all the credentials and local configuration in `conf/local/`
* Adhere to the following [commit conventions](<https://www.conventionalcommits.org/en/v1.0.0/>)

## Installing dependencies

Declare any dependencies in `requirements.txt` for `pip` installation.

To install them, run:
```
pip install -r requirements.txt
```

## How to run your Kedro pipeline

You can run your Kedro project with:

```
kedro run
```

## How to test your Kedro project

Have a look at the files `src/tests/test_run.py` and `src/tests/pipelines/test_data_science.py` for instructions on how to write your tests. Run the tests as follows:

```
pytest
```

To configure the coverage threshold, look at the `.coveragerc` file.
