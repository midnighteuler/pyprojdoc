Documented Project
==================

## To install: 

You need to be able to build python, have rvm installed, have node.js installed.

On ubuntu you can accomplish the first requirement with:

  sudo apt-get install build-essential

  sudo apt-get build-dep python2.7

### Run: "source setup_pyenv.sh"

This will set up a local install of python and the packages in requirements.txt

### Then run: "source setup_wiki.sh"

This will set up what's needed to edit the static site generator in /notes (cabin.js)

## To develop:

### Run: "source pyenv_paths.sh"

Sets up the pyenv shims so that "python" refers to the local environment

### Run: "source wiki_paths.sh"

Sets up paths to run project wiki

### Run: cd code && ipython notebook

Runs ipython in the code directory, serves at http://127.0.0.1:8888

### Run: cd notes && grunt

Runs cabin.js to continuously build/serve wiki at http://127.0.0.1:5445
