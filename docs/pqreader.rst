Module ``pqreader``
===================

.. automodule:: phconvert.pqreader

List of functions
-----------------

High-level functions to load and decode several PicoQuant file formats:

.. autofunction:: phconvert.pqreader.load_ptu

.. autofunction:: phconvert.pqreader.load_ht3

.. autofunction:: phconvert.pqreader.load_pt3


Low-level functions
'''''''''''''''''''

These functions are the building blocks for loading and decoding the different
files:

.. autofunction:: phconvert.pqreader.ptu_reader

.. autofunction:: phconvert.pqreader.ht3_reader

.. autofunction:: phconvert.pqreader.pt3_reader

.. autofunction:: phconvert.pqreader.process_t3records
