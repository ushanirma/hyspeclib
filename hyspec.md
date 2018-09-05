Hyspec Setup
===========
### Setup Python and pip
**For Linux (prefer Ubuntu LTS version)**
: Linux/Ubuntu Python will already exist and can be invoked as `python3` and `pip3`

**For Windows**
: If program is not installed for all users the path of python will be:

`%LOCALAPPDATA%\Programs\Python\Python36`

### Setup virtualenv

    pip install virtualenv

> Note: if multiple python version then make sure it is installed using correct python-pip you desire to code in.

### create activate Virtualenv
	virtualenv hyspec
> virtual environment hysec is created in current working directory where command virtualenv is executed
> 

**Requirements**
tensorflow
matplotlib
pandas
sklearn
psutill
scipy
jupyterlab
spectral
