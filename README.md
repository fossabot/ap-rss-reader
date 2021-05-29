# AP RSS-reader

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![PRs Welcome](https://img.shields.io/badge/PRs-welcome-brightgreen.svg?style=flat-square)](http://makeapullrequest.com)
[![Python: 3.8+](https://img.shields.io/badge/Python-3.8+-blue.svg)](https://www.python.org/)
[![MyPy](https://img.shields.io/badge/MyPy-passing-success.svg)](https://mypy.readthedocs.io/en/stable/)
[![pre-commit.ci status](https://results.pre-commit.ci/badge/github/aplatkouski/ap-rss-reader/main.svg)](https://results.pre-commit.ci/latest/github/aplatkouski/ap-rss-reader/main)
[![Imports: isort](https://img.shields.io/badge/%20imports-isort-%231674b1?style=flat&labelColor=ef8336)](https://pycqa.github.io/isort/)
[![Code style: black](https://img.shields.io/badge/code%20style-black-000000.svg)](https://github.com/psf/black)
[![Run tests](https://github.com/aplatkouski/ap-rss-reader/workflows/Run%20tests/badge.svg)](https://github.com/aplatkouski/ap-rss-reader/actions?query=workflow%3A%22Run+tests%22+branch%3Amaster)
[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2Faplatkouski%2Fap-rss-reader.svg?type=shield)](https://app.fossa.com/projects/git%2Bgithub.com%2Faplatkouski%2Fap-rss-reader?ref=badge_shield)

## How to use it

### Add 'src' directory to PYTHONPATH beforehand

```shell
export PYTHONPATH=".:src/"
```

### Run module

Run from source

```shell
python -m ap_rss_reader
```

or run from Python console:

```python
# Python version 3.8+
from ap_rss_reader import cli
cli.main()
```


## License
[![FOSSA Status](https://app.fossa.com/api/projects/git%2Bgithub.com%2Faplatkouski%2Fap-rss-reader.svg?type=large)](https://app.fossa.com/projects/git%2Bgithub.com%2Faplatkouski%2Fap-rss-reader?ref=badge_large)