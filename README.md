# pyenv-pip-update
[![MIT License](http://img.shields.io/badge/license-MIT-blue.svg?style=flat)](LICENSE.txt)  
Update all libraries managed by `pip` or `conda` in all environments ([pyenv](https://github.com/pyenv/pyenv) plugin).

## Version
0.0.3

## Installation
    git clone https://github.com/massongit/pyenv-pip-update $(pyenv root)/plugins/pyenv-pip-update

## Usage
    pyenv pip-update

## History
See [HISTORY.md](HISTORY.md)

## Note
In the environments using `conda` (anaconda or miniconda), this plugin only updates all libraries managed by `conda`.

## Development
### Config
You should install pre-commit by the following instruction: https://pre-commit.com/
This will check if your commit contains credentials.
