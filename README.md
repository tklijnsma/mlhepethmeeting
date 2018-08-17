# Example notebooks from the MLHEP2018 school

This repository contains a bunch of edited iPython notebooks that were used in the MLHEP2018 summer school. Some of them run out of the box, some need a bit more setup.

The environment was tested with Python version 3.6.5 (3.7 is currently not supported by TensorFlow). The versions of the packages used are in `requirements.txt`.

The recommended setup is:

    virtualenv -p python3 mlhepenvironment
    source mlhepenvironment/bin/activate
    pip install -r requirements.txt

(This may take some time to install all the packages). This will let you run most notebooks, although some need extra packages.