# Materials for a coding workshop at Jahrestagung der Gesellschaft für orale Epidemiologie und Versorgungsforschung (DGoEV)

## _Und nun: gute epidemiologische Datenpraxis – müssen wir alle demnächst coden können?_

### 2019-05-21


[![Binder](https://mybinder.org/badge.svg)](https://mybinder.org/v2/gh/eotp/dgoev19/master?urlpath=lab)

Requirements
* Bring you own laptop
* Have access to internet

*** 

This repository contains materials for the workshop __Und nun: gute epidemiologische Datenpraxis – müssen wir alle demnächst coden können?__, Berlin, Germany.

In order to re-run the workshop materials we encourage you to use the [conda](https://conda.io/docs/) package manager. Once installed, create an environment and install all required dependencies on your machine by typing 

`conda env create -f environment.yml`

into your console. You activate your new environment by typing 

`source activate dgoev19` (on LINUX and Mac) or

`activate dgoev19` (on WINDOWS). 

Then you are ready to go (if you are stuck check out the [conda documentation site](https://conda.io/docs/user-guide/tasks/manage-environments.html#)). 

> Alternatively, you may launch [binder](https://mybinder.org/) to get a reproducible executable environment immediately in your browser. Simply click the _launch binder_ icon in the upper left corner, or go [here](https://mybinder.org/v2/gh/eotp/dgoev19/master?urlpath=lab).


***

All data sets, all code snippets, all [Jupyter](http://jupyter.org/) notebooks and the `environment.yml` file for reproducibility are available through this self contained repository.

The structure of this repository is outlined below:

    python-charite
    │.git                  # git internals
    │.gitignore            # specify files/folders to be ignored by git
    └───datas
    │   │...               # find all the raw data files
    └───figures
    │   │...               # saved figures go here
    └───notebooks
    │   └───_img
    │   │   │...           # rendered images are placed here
    │   │...               # find all Jupyter notebooks here
    │   │conf.py           # configuration file for nbsphinx
    │   │start.rst         # configuration file for nbsphinx
    │
    │README.md
    │LICENSE   
    │environment.yml       # conda environment specifications for reproducibility
    └───src
        │...               # here go the code snippets and scripts
        └───_solutions
            │...           # solutions for coding challenges (don't cheat yourself ;-))


 ***
 
 




