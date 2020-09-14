## How to install a Python version

See which Python versions are available: `pyenv install -l`

Intsall a suitable version: `pyenv install 3.7.8`

See which Python versions you have installed: `pyenv versions`

## How to set the Python version for your context

Set the Python version you just installed to be the global version on your system: `pyenv global 3.7.8`

- or -

Set the Python version you just installed to the be the version for this specific directory with: `pyenv local 3.7.8`

This won't do anything yet, for this to work you have to inject pyenv into the shell or whatever environment you are using.

## How to enable pyenv

This is where it gets messy. You have to paste in some specific commands into a specific file for your particular environment.

With [fish](https://fishshell.com/), this is handled by a plugin which makes it incredibly easy: `omf install pyenv`
