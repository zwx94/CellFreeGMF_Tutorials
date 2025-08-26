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

1.1 PyPI: Directly install the package from PyPI.
^^^^^^^^^^^^^^^^^^^^^^^^^^^^

.. code-block:: python

   pip3 install CellFreeGMF
   #Note: you need to make sure that the pip is for python3，or we should install CellFreeGMF by
   python3 -m pip install CellFreeGMF
   pip3 install CellFreeGMF
   #If you do not have permission (when you get a permission denied error), you should install CellFreeGMF by
   pip3 install --user CellFreeGMF

1.2 Github
^^^^^^^^^^^^^^^^^^^^^^^^^^^^

Download the package from Github (https://github.com//zwx94//CellFreeGMF) and install it locally:

.. code-block:: python

   cd CellFreeGMF-main
   python setup.py build
   python setup.py install

.. code-block:: python

   import CellFreeGMF

1.3 Github
^^^^^^^^^^^^^^^^^^^^^^^^^^^^

If you do not have Python3.5 or Python3.6 installed, consider installing Anaconda (see Installing Anaconda). After installing Anaconda, you can create a new environment, for example, CellFreeGMF (you can change to any name you like).

.. code-block:: python

   #create an environment called SpaGCN
   conda create -n SpaGCN python=3.7.9
   #activate your environment 
   conda activate SpaGCN
   git clone https://github.com/jianhuupenn/SpaGCN
   cd SpaGCN/SpaGCN_package/
   python3 setup.py build
   python3 setup.py install
   conda deactivate
