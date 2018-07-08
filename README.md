# sci-pkg

A Python 3 package or simply a collection of functions used in scientific computing 


## design goals

1. simplicity: wrap frequently used workflows into simple functions that make life easier for scientists.  
2. functional programming paradigm: While using classes is permitted we encourage: write fewer classes and more functions (perhaps with decorators) 
3. easy to use docstrings 
4. Cross-platform


## How to contribute

1. `git clone git@github.com:FredHutch/sci-pkg.git`
2. create a new branch (eg : sci-yourname)
3. paste your function into module sci-pkg/sci/scinew.py and add a new import statement for the required packages. 
4. Make sure you add an example call in the first line of the doc string.
5. Add your testcase to sci-pkg/tests


