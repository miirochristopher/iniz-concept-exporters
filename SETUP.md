### Python 3 or newer

The scripts require Python 3.8+ as stated in the README.md file, however, for python 3, it is important to note that venv does not permit creating virtual environments with other versions of Python. 

For that, install and use the [virtualenv](https://pypi.org/project/virtualenv/) package.

### Virtualenv package

Install virtualenv package by running the following commands: pipx is a tool to help you install and run end-user applications written in Python.


```bash
sudo apt install pipx

pipx install virtualenv

pipx ensurepath

virtualenv --help
```

### Create the environment (creates a folder in your current directory)

```
cd concepts

virtualenv env 
```

On Linux or Mac, activate the new python environment


```
source env/bin/activate
```

Confirm that the env is successfully selected

```
which python3
```
