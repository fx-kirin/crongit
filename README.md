# crongit

[![Latest PyPI version](https://img.shields.io/pypi/v/package_name.svg)](https://pypi.python.org/pypi/crongit)

Manage crontab with git easily.

## Usage

```
# Move to a new directory to manage crontab files with git.
git init

# get current crontab setting.
# it will generate the file named `$USER.crontab`
crongit init

# Modify your crontab setting
vim $USER.crontab

# Update crontab with `$USER.crontab` and if it's been done without an error, commit the crontab file automatically.
crongit update
```

## Installation

```
pip install crongit
```

## Authors

crongit was written by [fx-kirin](fx.kirin@gmail.com).
