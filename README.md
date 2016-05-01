# Programming Language Classifier

The Programming Language Classifier is designed to take a snippet of code and identify the programming language used.

The IPython notebook included in this repository, [polyglot.ipynb](https://github.com/JonathanKross/programming-language-classifier/blob/master/polyglot.ipynb), uses a MultinomialNB classifier


The training data used in this program was downloaded from the [Computer Language Benchmarks Game](http://benchmarksgame.alioth.debian.org/). It can be downloaded [here](https://alioth.debian.org/snapshots.php?group_id=100815).

## Compatible Languages
* C (.gcc, .c)
* C#
* Common Lisp (.sbcl)
* Clojure
* Haskell
* Java
* JavaScript
* OCaml
* Perl
* PHP (.hack, .php)
* Python
* Ruby (.jruby, .yarv)
* Scala
* Scheme (.racket)

## To View This Notebook

* The Programming Language Classifier notebook can be viewed here [polyglot.ipynb](https://github.com/JonathanKross/programming-language-classifier/blob/master/polyglot.ipynb).

## To Run This Notebook

* You will need to have **python3** installed.
* Clone this repo.
* Layout a virtual environment in your working directory.
* Install the requirements file by runnning **`pip install -r requirements.txt`** in your command-line program.

### Opening the Notebook

* Within your working directory, using a command-line program, run the following line: **`ipython notebook polyglot.ipynb`**
