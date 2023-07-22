# Revisiting My Python Knowledge: Basics Of Python

In this repository, I tried to write down what I know about Python programming language.

## What is Python?

Python is a high-level, versatile, and easy-to-read programming language known for its simplicity and readability. Created by Guido van Rossum and first released in 1991, Python has grown to become one of the most popular programming languages worldwide. Its design philosophy emphasizes code readability and a clean syntax, which allows programmers to express concepts in fewer lines of code compared to other languages.

## Installing Python

Visit the official website of [Python](https://www.python.org/downloads/ "Download Python") to download python for your OS. I also use [Miniconda](https://docs.conda.io/en/main/miniconda.html# "Miniconda") for managing different python versions and environments.

## Package Managers

* `pip`: Default package manager for Python. Used for installing packages from PyPI and other repositories. It comes pre-installed with python.
* `Anaconda`: A comprehensive distribution of Python for data science and scientific computing, including its own package manager `conda`.
* `Miniconda`: A minimal version of Anaconda that includes only the Python interpreter and `conda` package manager, allowing users to build a more customized Python environment.

## Managing Packages

Both `pip` and `conda` are powerful package managers, and your choice between them may depend on the specific use case and the Python distribution you are using. If you're working with **Anaconda** or **Miniconda**, it's recommended to use `conda` for managing packages to avoid potential conflicts in your environment. If you have a standard Python installation, `pip` is the default and widely-used package manager for most Python projects.


### Installing Packages

To install a package using `pip`, use the following command:

```
pip install package_name
```

For example:

```
pip install numpy
```

To install a package using `conda`, use the following command:

```
conda install package_name
```

For example:

```
conda install numpy
```

### Updating Packages

To update a package to using `pip`, use the `--upgrade ` or `-U ` flag with the `install` command:

```
pip install --upgrade package_name
pip install -U package_name
```

For example:

```
pip install -U numpy
```

To update a package using `conda`, use the following command:

```
conda update package_name
```

For example:

```
conda update numpy
```

### Removing Packages

To remove a package to using `pip`, use the `--upgrade ` or `-U ` flag with the `install` command:

```
pip uninstall package_name
```

For example:

```
pip uninstall  numpy
```

To update a package using `conda`, use the following command:

```
conda remove package_name
```

For example:

```
conda remove numpy
```
