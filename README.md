# Presentation for UA ResBaz 2020

This is the code and setup instructions for my presentation 19 May 2020 for the University of Arizona's [Research Bazaar](https://researchbazaar.arizona.edu/).

## Setup

I will be covering the first chapter of [Tiny Python Projects](http://tinypythonprojects.com/) to explain how to write a Python program that is

* parameterized (will accept arguments)
* documented (will generate a "usage" statement when asked)
* tested 
* reproducible

I will live-code the `hello.py` example that starts from printing "Hello, World!" and moves through how to write a more flexible version that can greet a given argument.
If you would like to code along, you can work locally on your own machine or use a free instance on repl.it to write in your browser.

### Setting up a local dev environment

If you have Python installed and/or are comfortable setting up a development environment on your own machine, I recommend you clone the GitHub repo and write/test your programs locally:

1. Create an account on GitHub.com
2. Go to https://github.com/kyclark/tiny_python_projects and click the "Fork" button to make a copy of the repo into your account
3. Clone your forked repo onto your local machine. For instance, you could open a terminal and use `git clone git@github.com:YOUR_GITHUB_ID/tiny_python_projects`, or you might like to use GitHub Desktop.
4. Be sure you have Python version 3.6 or later. You may need to download [Python](https://www.python.org/downloads/).
5. Optionally install `make` if do not already have it.
6. Change into the GitHub checkout and install the dependencies with `python3 -m pip install -r requirements.txt`

### Using repl.it to code in your browser

If you are unable to set up a local development environment, e.g., you are using a Chromebook with no local storage or you do not have administrative privileges on your machine, you can use [repl.it](http://repl.it) for free:

1. Create an account on http://repl.it
2. Create a new REPL by clicking on the “+ repl” button in the upper right corner. Select Python and optionally name it.
3. Click on the “version control” icon on the left
4. Click on “Existing git repository”
5. Click on “Import from GitHub”. Authorize repl.it to use your GitHub.
6. Select your “tiny_python_projects” from the dropdown list.
7. In the terminal window, run "python3 -m pip install -r requirements.txt” to install the required modules.
