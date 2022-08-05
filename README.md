Sample Py Cli 
---

A sample project implementing a basic command line script with click. Used as scaffoling to spin up distributable command line python projects. 

Resources:

- https://setuptools.pypa.io/
- https://click.palletsprojects.com/
- https://packaging.python.org/en/latest/tutorials/packaging-projects/


Test from source
---


```
virtualenv venv 
source venv/bin/activate
pip install -e .
```


```
cat <<\EOF > setup.py
from setuptools import setup

setup()
EOF
```
