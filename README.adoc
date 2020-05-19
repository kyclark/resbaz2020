= Presentation for UA ResBaz 2020

This is the code and setup instructions for my presentation 19 May 2020 for the University of Arizona's https://researchbazaar.arizona.edu/[Research Bazaar].

== Setup

I will be covering the first chapter of http://tinypythonprojects.com/[Tiny Python Projects] to explain how to write a Python program that is:

* parameterized (will accept arguments)
* documented (a README, program will generate a "usage" statement when asked)
* tested (using `pytest`)
* reproducible 

I will live-code the `hello.py` example that starts from printing "Hello, World!" and then goes on to a more flexible version that can greet a given argument.
If you would like to code along, you can work locally on your own machine or use a free instance on repl.it to write in your browser.

A PDF of the chapter is included as `tpp-ch1-hello.pdf`.

== Getting the code

I will be using the `test.py` program found in the `code` directory to test our program.
You can copy this program to your local machine or you might prefer to clone this repo to your local machine with this command:

----
git clone https://github.com/kyclark/resbaz2020.git
----

Another alternative is to "fork" the repo to copy it into your own account:

1. Create an account on GitHub.com
2. Click on the "Fork" button on this page.

This is a copy of the first chapter of https://github.com/kyclark/tiny_python_projects[Tiny Python Projects repo].
If you think you might like to work further into the material, you might instead fork that repo. 

Both repos have a `requirements.txt` file that lists modules we will need to format and test our code.
You can install them with this command:

----
python3 -m pip install -r requirements.txt
----

IMPORTANT: We will be writing a program called `hello.py` which must live in the same directory as the included `test.py` in order for the tests to work.

=== Writing and testing on your own machine

Check if you have a recent version of Python installed.
You can open a terminal and type:

----
python3 --version
----

If you have 3.6 or better, you are fine.
If Python is not installed or you have an earlier version, you can download the latest version from https://www.python.org/downloads.

You can also install `make` if you do not already have it.
I demonstrate the command `make test` as a shortcut for running the test suite.
If you would like to know more about `make`, I wrote https://github.com/kyclark/make-tutorial[a tutorial you can read].

=== Using repl.it to code in your browser

If you are unable to set up a local development environment, e.g., you are using a Chromebook with no local storage or you do not have administrative privileges on your machine, you can use http://repl.it for free.
For this, you will really need to fork the https://github.com/kyclark/tiny_python_projects into your own GitHub account.

Then do the following:

1. Create an account on http://repl.it
2. Create a new REPL by clicking on the “+ repl” button in the upper right corner. Select Python and optionally name it.
3. Click on the “version control” icon on the left
4. Click on “Existing git repository”
5. Click on “Import from GitHub”. Authorize repl.it to use your GitHub.
6. Select your “tiny_python_projects” from the dropdown list.
7. In the terminal window, run `python3 -m pip install -r requirements.txt` to install the required modules.
