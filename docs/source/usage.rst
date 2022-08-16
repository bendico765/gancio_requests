Usage
=====

Installation
------------

To install the latest version of the library just download (or clone) the current project, open a terminal and run the following commands:

.. code-block:: console
   
   pip install -r requirements.txt
   pip install .
   
At the moment I have tested the library only on python == 3.10.4 The library requires the dependencies specified in requirements.txt and 
I haven't still tested other versions.

Command Line Interface
----------------------

.. code-block:: console
   
   python3 -m gancio_requests [-h] gancio_instance
   
*gancio_instance* is the URL of the instance from which we want to fetch the data. 
The output displays the list of events starting of 00\:00\:00 of the current day. The information about an event is shown this way:

.. code-block::

   EVENT_NAME
   [STARTING_TIME | END_TIME]
   PLACE_NAME - ADDRESS
   LIST_OF_TAGS (optional)
   EVENT_URL
   

Python package
--------------

After the installation, it is possible to use the package directly from the python interpreter by using ``import gancio_requests``.
For more info, you can check the module's documentation.
