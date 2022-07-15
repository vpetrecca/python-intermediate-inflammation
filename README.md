# Inflam
![Continuous Integration build in GitHub Actions](https://github.com/vpetrecca/python-intermediate-inflammation/workflows/CI/badge.svg?branch=main)

inflam is a data managment system written in Python that manages trial data used in clinical inflammation studies.

## Main features

Here are some key features of Inflam:

- Provide basic statistical analyses over clinical trial data
- Ability to work on trial data in Comma-Separated Value (CSV) format
- Generate plots of trial data
- Analytical functions and views can be easily extended based on its Model-View-Controller architecture

## Prerequisites

Inflam requires the following Python packages:

- [NumPy](https://www.numpy.org/) - makes use of NumPy's statistical functions
- [Matplotlib](https://matplotlib.org/stable/index.html) - uses Matplotlib to generate statistical plots

The following optional packages are required to run Inflam's unit tests:

- [pytest](https://docs.pytest.org/en/stable/) - Inflam's unit tests are written using pytest
- [pytest-cov](https://pypi.org/project/pytest-cov/) - Adds test coverage stats to unit testing

## Installation

Requirements

Python>3.7
cycler==0.11.0
fonttools==4.28.1
kiwisolver==1.3.2
matplotlib==3.5.0
numpy==1.21.4
packaging==21.2
Pillow==8.4.0
pyparsing==2.4.7
python-dateutil==2.8.2
setuptools-scm==6.3.2
six==1.16.0
tomli==1.2.2

For testing install pytest:

>pip3 install pytest



## Basic usage

Testing:
>pytest tests/test_models.py

In command prompt type to start code

>python3 inflammation-analysis.py

basic usage of code in Python shell:

>import inflammation
>from inflammation import  models, serializers,views

## Contributing
Contributors  to open source are sought, with skills in statitistical analysis and vizualization 

## Contact information
vincenzo.petrecca@unina.it

## Acknowedgements
We thank [software carpentry](https://software-carpentry.org/) from Southempton University for their wonderful course.

## Citation
|               | Creation                                                                        | Editing/Updating                                                    | Validation                                                                      | Conversion                                                                                                                                                       |
| ------------- | ------------------------------------------------------------------------------- | ------------------------------------------------------------------- | ------------------------------------------------------------------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| Command line  |                                                                                 |                                                                     | • [cffconvert](#validation-heavy_check_mark)                                    | • [cffconvert](https://pypi.org/project/cffconvert/)<br> • [bibtex-to-cff](https://github.com/monperrus/bibtexbrowser/)                                          |
| GitHub Actions |                                                                                 |                                                                     | [cff-validator](https://github.com/marketplace/actions/cff-validator)           | • [cffconvert](https://github.com/marketplace/actions/cffconvert)<br>• [codemeta2cff](https://github.com/caltechlibrary/codemeta2cff)                            |
| Python        |                                                                                 | • [doi2cff](https://github.com/citation-file-format/doi2cff)        | • [cffconvert](#validation-heavy_check_mark)                                    | • [cffconvert](https://github.com/citation-file-format/cff-converter-python)<br>• [doi2cff](https://github.com/citation-file-format/doi2cff)                     |

## License
Copyright © 2022.

This work is licensed under a [Creative Commons Attribution 4.0 International (CC-BY-4.0)](https://creativecommons.org/licenses/by/4.0/legalcode) license.
