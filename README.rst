===============
Composite-Plate
===============

A Python library for performing basic composite plate calculations.

Reading the Docs
----------------
.. image:: https://readthedocs.org/projects/composite-plate/badge/?version=latest
  :target: http://composite-plate.readthedocs.org/en/latest/?badge=latest
  :alt: Documentation Status
  
Head on over to http://composite-plate.readthedocs.org/en/latest/

Or build them yourself.  In the cloned repo, type:

.. code::
  
  Composite-Plate$ cd docs
  Composite-Plate$ make html
  
Look in the :code:`Composite-Plate/docs/_build/html` directory and open :code:`index.html` in any browser.

Installing
----------
Directly to Python on Your Machine
``````````````````````````````````
Install from the newest dev version in the master branch:

.. code::
  
  $ pip install git+https://github.com/johnrbnsn/Composite-Plate.git
  
To a Specific Project via *requirements.txt*
````````````````````````````````````````````
Place this in your *requirements.txt*:

.. code::

  git+https://github.com/johnrbnsn/Composite-Plate.git#egg=Composite-Plate
  
and then run:

.. code::

  $ pip install -r requirements.txt

Testing
-------
.. image:: https://travis-ci.org/johnrbnsn/Composite-Plate.svg?branch=master
    :target: https://travis-ci.org/johnrbnsn/Composite-Plate
    
Testing is done with :code:`unittest` and continuously checked via `travis-ci <https://travis-ci.org/johnrbnsn/Composite-Plate>`_.  Tests are based upon known textbook example problems (see test file for details).  

License
-------
Released under MIT license, see `LICENSE <https://github.com/johnrbnsn/Composite-Plate/blob/master/LICENSE>`_ for details.
