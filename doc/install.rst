.. index:: install

.. _install:


Install
=======

The latest release of VASPRUN can be found on `GitHub`_.

.. _GitHub: https://github.com/smarkov/vasprun/


User (w/o sudo or root privilege):
----------------------------------


.. code:: bash

      pip3 install --upgrade --user vasprun


Developer:
----------


Clone the repository and go to the newly created directory of the repository.

.. code:: bash

      git clone https://github.com/smarkov/vasprun.git
      cd vasprun

Issue the following command from the root directory of the repository.

.. code:: bash

      pip3 install --upgrade --user -e .


.. note::
      Please omit the ``--user`` above if installing within a virtual environment.

      If installing with ``--user``, ensure that ``~/.local/bin`` is
      in your ``$PATH`` environment variable.

Dependencies
------------

* numpy
* matplotlib
* lxml
* json_tricks
* ase


Uninstall:
----------


.. code:: bash

      pip3 uninstall skpar
