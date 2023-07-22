# Revisiting My Python Knowledge: Basics Of Python

In this repository, I tried to write down what I know about Python programming language.

## Table Of Contents

  - [What is Python?](#what-is-python)
  - [Installing Python](#installing-python)
  - [Package Managers](#package-managers)
  - [Managing Packages](#managing-packages)
    - [Installing Packages](#installing-packages)
    - [Updating Packages](#updating-packages)
    - [Removing Packages](#removing-packages)
  - [Writing And Executing Code](#writing-and-executing-code)
    - [Using IDEs (Visual Studio Code, PyCharm, etc.)](#using-ides-visual-studio-code-pycharm-etc)
    - [Using Text Editors (Notepad, Notepad++, Sublime Text, etc.)](#using-text-editors-notepad-notepad-sublime-text-etc)
    - [Using Python IDLE (Python Shell)](#using-python-idle-python-shell)

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

## Writing And Executing Code

Python, being a versatile programming language, allows you to write and execute code using various development environments. Whether you prefer the feature-rich experience of IDEs like Visual Studio Code and PyCharm or the simplicity of text editors like Notepad, Notepad++, or Sublime Text, Python ensures a smooth and enjoyable coding experience as it can be comfortably written and executed in any of these environments.

Additionally, for quick code testing, Python IDLE provides an interactive shell that allows you to experiment with Python code directly. Choose the development environment that suits your needs and start coding in Python!

### Using IDEs (Visual Studio Code, PyCharm, etc.)

**Step 1:** Install Python on your computer by downloading the official setup from the [Python website](https://www.python.org/downloads/ "Download Python"). Ensure that you add Python to your system's PATH during the installation.

**Step 2:** Install your preferred IDE (e.g., Visual Studio Code or PyCharm).

**Step 3:** Create a new Python file with the `.py` extension in your IDE.

**Step 4:** Write your Python code in the file using the editor.

**Step 5:** Save the file and click on the "Run" or "Execute" button in your IDE to run the code.

### Using Text Editors (Notepad, Notepad++, Sublime Text, etc.)

**Step 1:** Install Python on your computer, as mentioned in the IDE section above.

**Step 2:** Open your preferred text editor (e.g., Notepad, Notepad++, Sublime Text or any other).

**Step 3:** Create a new file and write your Python code in the file.

**Step 4:** Save the file with the `.py` extension (e.g., `my_script.py`).

**Step 5:** Open a terminal or command prompt, navigate to the directory where your Python file is located.

**Step 6:** Run the Python script by typing `python my_script.py` in the terminal (replace `my_script.py` with the actual name of your file).

### Using Python IDLE (Python Shell)

**Step 1:** If you've installed Python on your computer, you should have access to Python IDLE.

**Step 2:** Open Python IDLE from your system's start menu or applications.

**Step 3:** A Python shell will appear where you can directly type and execute Python code.

**Step 4:** Write your Python code directly in the shell and press Enter to execute it.
