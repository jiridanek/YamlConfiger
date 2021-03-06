# Getting started

* python 3.5+ or python2.7
* current requirements from setup.py (runtime requirements only)
* python virtualenv recommended (install via system package manager
or `pip install --user virtualenv`)

for contributors:
* requirements from requirements.txt (there are Dev and QA requirements as well)

## From git

```bash
git clone git@bitbucket.org:msgqe/amqcfg.git
python -m virtualenv -p python3 venv3
source venv3/bin/activate
./setup.py install
amqcfg --help
```

## From PyPI

```bash
python -m virtualenv -p python3 venv3
source venv3/bin/activate
pip install amqcfg
amqcfg --help
```