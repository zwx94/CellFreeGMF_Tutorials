Installation
============


Software dependencies
---------------------
.. code-block:: python

   scanpy
   pytorch
   pyG
   
The use of the mclust algorithm requires the rpy2 package and the mclust package. See https://pypi.org/project/rpy2/for detail.

Installation
------------
Downloading CellFreeGMF code from https://github.com//zwx94//CellFreeGMF


.. code-block:: python

   cd CellFreeGMF-main
   python setup.py build
   python setup.py install

.. code-block:: python

   import CellFreeGMF
