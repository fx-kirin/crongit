# crongit

[![Latest PyPI version](https://img.shields.io/pypi/v/package_name.svg)](https://pypi.python.org/pypi/crongit)

## Usage

```
# get current crontab setting.
# it will generate the file `$USER.crontab`
crongit init

# Modify your crontab setting
vim $USER.crontab

# Update crontab and if it's been done without an error, commit the crontab file.
crongit update
```

## Installation

```
pip install crongit
```

## Authors

crongit was written by [fx-kirin](fx.kirin@gmail.com).
