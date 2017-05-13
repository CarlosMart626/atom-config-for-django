# Atom Packages for Python/Django Development

### Install these python packages
```
pip install flake8
pip install flake8-docstrings
```
## Atom packages
Inside Atom / Init Script add the following:
```
process.env.PATH = ['/usr/local/bin/', process.env.PATH].join(':')
```

### Install Atom packages steps and update configuration
1. Install packages from **package-list.txt**
```
apm install --packages-file package-list.txt
```
2. Update configuration using as example **config.txt** remember to replace Python paths!
