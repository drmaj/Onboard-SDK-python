# dji-sdk-python
DJISDKPY - DJI SDK python interface

DJISDKPY is a python module interface to DJI's Onboard and Guidance SDK on linux platforms. It is built with pybind11 and uses the DJI SDK
apis to provide full control of supported DJI vehicles Matrices 100, Matrice 600, Matrice 210/210-RTK or flight
controllers A3 or N3.

## Dependencies

This module has the following depenendencies:

* python
* python-dev
* pip
* setuptools
* build-essential
* cmake

## Compilation and Usage

### Install dependencies

```
sudo apt-get update
sudo apt-get install python python-dev python-pip build-essential cmake
pip install setuptools

```

### Compilation

```
git clone https://github.com/drmaj/dji-sdk-python
cd dji-sdk-python
git submodule update --init --recursive
python setup.py build_ext -i

```

### Usage

After compilation, 
