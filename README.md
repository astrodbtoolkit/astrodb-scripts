# astrodb-scripts
[![Test astrodb-scripts](https://github.com/astrodbtoolkit/astrodb-scripts/actions/workflows/run_tests.yml/badge.svg)](https://github.com/astrodbtoolkit/astrodb-scripts/actions/workflows/run_tests.yml)
[![Documentation Status](https://readthedocs.org/projects/astrodb-scripts/badge/?version=latest)](https://astrodb-scripts.readthedocs.io/en/latest/?badge=latest)
[![PyPI version](https://badge.fury.io/py/astrodb-scripts.svg)](https://badge.fury.io/py/astrodb-scripts)

The following tables are expected by AstroDB Toolkit and the AstroDB_scripts package:
- Sources
- Publications
- Names
- Telescopes
- Instruments
You may modify these tables, but doing so may decrease the interoperability of your database with other tools.

# Developer Setup Instructions
- Make new environment with Python=3.10
- Install dependecies using an editable install:
  ```
  pip install -e ".[test]"
  ```
- In the `tests/` directory, clone the `astrodb-template` repo:
  ```
  git clone git@github.com:astrodbtoolkit/astrodb-template-db.git
  ```
- Be sure to run tests from the top level directory.
