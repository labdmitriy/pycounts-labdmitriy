# pycounts-labdmitriy

Calculate word counts in a text file

[![GitHub Release](https://img.shields.io/github/v/release/labdmitriy/pycounts-labdmitriy?style=flat-square)](https://github.com/labdmitriy/pycounts-labdmitriy/releases)
[![GitHub Actions Workflow Status](https://img.shields.io/github/actions/workflow/status/labdmitriy/pycounts-labdmitriy/ci-cd.yml?style=flat-square)](https://github.com/labdmitriy/pycounts-labdmitriy/actions/workflows/ci-cd.yml)
[![GitHub License](https://img.shields.io/github/license/labdmitriy/pycounts-labdmitriy?style=flat-square)](https://opensource.org/license/MIT)
[![GitHub Downloads (all assets, all releases)](https://img.shields.io/github/downloads/labdmitriy/pycounts-labdmitriy/total?style=flat-square)](https://pypistats.org/packages/pycounts-labdmitriy)
[![GitHub Repo stars](https://img.shields.io/github/stars/labdmitriy/pycounts-labdmitriy?style=flat-square)](https://star-history.com/#labdmitriy/pycounts-labdmitriy)
[![GitHub Open Issues](https://img.shields.io/github/issues-raw/labdmitriy/pycounts-labdmitriy)](https://github.com/labdmitriy/pycounts-labdmitriy/issues)
[![Read the Docs](https://img.shields.io/readthedocs/pycounts-labdmitriy)](https://pycounts-labdmitriy.readthedocs.io/)

## Installation

```bash
$ pip install pycounts-labdmitriy
```

## Usage

`pycounts-labdmitriy` can be used to count words in a text file and plot results
as follows:

```python
from pycounts.pycounts import count_words
from pycounts.plotting import plot_words
import matplotlib.pyplot as plt

file_path = "test.txt"  # path to your file
counts = count_words(file_path)
fig = plot_words(counts, n=10)
plt.show()
```

## Contributing

Interested in contributing? Check out the contributing guidelines. Please note that this project is released with a Code of Conduct. By contributing to this project, you agree to abide by its terms.

## License

`pycounts-labdmitriy` was created by Dmitry Labazkin. It is licensed under the terms of the MIT license.

## Credits

`pycounts-labdmitriy` was created with [`cookiecutter`](https://cookiecutter.readthedocs.io/en/latest/) and the `py-pkgs-cookiecutter` [template](https://github.com/py-pkgs/py-pkgs-cookiecutter).
