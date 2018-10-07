# code-metrics
Python code static analyzer wrapper over radon and pylint with
Confluence/Jira support.

## Setup


[virtualenvwrapper](https://virtualenvwrapper.readthedocs.io/en/latest/) recommended
```
# Create a virtualenv
virtualenv -p /usr/bin/python3 ve
activate ve/bin/activate
# Install
pip install ./code_metrics # Or name of the cloned destination folder
code_metrics --help
code_metrics files_complexity code_metrics
```