# Python Repository Template

A simple Python repository template that uses Pipenv as a package manager and has a commit message template.

## Installation

### Prerequisites

You will need an working installation of Python. It is recommended to use the latest version. You can download Python [here](https://www.python.org/downloads/). Don't forget to add Python to PATH and install Pip.

To verify that Python and Pip are installed, follow these steps:

1. Open the command prompt or terminal.
2. Type `python --version` or `python3 --version`.
3. Type `pip --version`.

If the versions are presented correctly, both are installed properly.

Finally, you need Pipenv installed in the Python environment. Open the command prompt or terminal and type `pip install pipenv`. You may need to open the command prompt or the terminal as an administrator.

### Clone

No commit or merge is allowed in this repository, so the cloning of that repository is done only for the download of the files to be used. The clone itself can be replaced by downloading files.

The files in this repository should be placed in your project's repository, as they only serve as a template.

So, the steps to use these files are:

1. Clone or download the files from this repository.
2. Create your own Git repository (see more [here](https://git-scm.com/book/en/v2/Appendix-C%3A-Git-Commands-Getting-and-Creating-Projects)).
3. Copy the downloaded files to your own repository.
4. Open the command prompt or the terminal in your own repository folder.
5. Type `pipenv install`.
6. Type `git config commit.template .gitcommittemplate`.

After that, your repository will be using this template.

## Features

This template makes it easy to create a new Git repository for use with Python. It uses Pipenv for package management and has its own commit template.

## Usage

The use of this repository is the same as the other Git repositories. Only a few differences need to be pointed out.

You **NEED** to use Pipenv for package management. Because of this it was installed and should be used from now on. You can learn how to use Pipenv [here](https://github.com/pypa/pipenv) and [here](https://pipenv.kennethreitz.org/en/latest/).

You should **NEVER** commit using the command `git commit -m <message>`. The `-m` parameter bypass the commit template. You should **ALWAYS** commit using just the command `git commit`.

## Documentation

Documentation is not necessary because it is just a template, but it is here for you to **ALWAYS** remember to document your repositories.
