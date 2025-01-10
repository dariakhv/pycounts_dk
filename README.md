# pycounts_dk

a toy package that helps to calculate a word cound from a text file

## Installation

```bash
$ pip install pycounts_dk_20250110
```

## Usage

`pycounts` can be used to count words in a text file and plot results
as follows:

```python
from pycounts.pycounts import count_words
from pycounts.plotting import plot_words
import matplotlib.pyplot as plt

counts = count_words(file_path)
fig = plot_words(counts, n=10)
plt.show()
```
## Contributing

Interested in contributing? Check out the contributing guidelines. Please note that this project is released with a Code of Conduct. By contributing to this project, you agree to abide by its terms.

## License

`pycounts_dk` was created by Daria Khon. It is licensed under the terms of the MIT license.

## Credits

`pycounts_dk` was created with [`cookiecutter`](https://cookiecutter.readthedocs.io/en/latest/) and the `py-pkgs-cookiecutter` [template](https://github.com/py-pkgs/py-pkgs-cookiecutter).
