
# comment to highlights

## Comment to highlight is a python script that runs on Jupiter and Binder. The goal is to transform the log of the chat of a zoom meeting into an object ready to be paste in Strapi as highlights. 

1. Paste comments download into the same folder as this script
2. open the script. 
3. in the 3 box input the time stamp manually And the starttime of the meeting in seconds in case the command -start wasn't used. 
4. run all boxes. 
5. The Jupyter book will display the information of the comments as well as the object for strapi. CHECK EVERYTHING MAKES SENSE, DOUBLE CHECK!. This is a Beta version.










---------------------------------------------------------------------------------------------------------------------------


# Conda environment with environment.yml

[![Binder](http://mybinder.org/badge_logo.svg)](http://mybinder.org/v2/gh/binder-examples/conda_environment/master?filepath=index.ipynb)

A Binder-compatible repo with an `environment.yml` file.

Access this Binder by clicking the blue badge above or at the following URL:

http://mybinder.org/v2/gh/binder-examples/conda_environment/master?filepath=index.ipynb

## Notes
The `environment.yml` file should list all Python libraries on which your notebooks
depend, specified as though they were created using the following `conda` commands:

```
source activate example-environment
conda env export --no-builds -f environment.yml
```

Note that the only libraries available to you will be the ones specified in
the `environment.yml`, so be sure to include everything that you need! 

Also note that conda will possibly try to include OS-specific packages in `environment.yml`, so you
may have to manually prune `environment.yml` to get rid of these packages. Confirmed Mac-OSX-specific
packages that should be removed are:

* libcxxabi=4.0.1
* appnope=0.1.0
* libgfortran=3.0.1
* libcxx=4.0.1
