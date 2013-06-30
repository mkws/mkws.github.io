Student-run Machine Learning website at University of Chicago.

Prerequisites
=============

 * [Jekyll](http://jekyllbootstrap.com)
 * pygments
 * docutils
 * RbST (`gem install RbST`)

If you have pip and gem you can easily install these:

    $ gem install jekyll RbST
    $ pip install docutils pygments

Installation
============
Fetch the repository:

    $ git clone git@github.com:johnsanterre/johnsanterre.github.io.git
    $ cd johnsanterre.github.io

Now initialize and fetch the submodules:

    $ git submodule init
    $ git submodule update

Now you should be able to build and test it:

    $ jekyll build
    $ jekyll serve

Check go to http://localhost:4000/.
