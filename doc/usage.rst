

Usage
=====


How to clone the code
---------------------

Write me ...


Make
----

Generate all results:

::

  $ make -f Makefile_all


Snakemake
---------

We create a file called "Snakefile" with the following contents:

::

  # Count words.
  rule count_words:
      input: 'data/isles.txt'
      output: 'processed_data/isles.dat'
      shell: 'python source/wordcount.py data/isles.txt processed_data/isles.dat'
      
and run it with

::

  $ snakemake


Where to find the results
-------------------------

Write me ...
