Welcome to Ctrl RAD Symfony Standard's documentation!
=====================================================

Quick start
-----------

.. code-block:: sh

   composer create-project ctrl-f5/symfony-rad

   # create database
   bin/console doctrine:database:create
   bin/console doctrine:schema:update --force

   # create default admin user
   bin/console fos:user:create admin admin@local.com admin --super-admin

   # run the server
   bin/console server:run

Documentation
-------------

.. toctree::
   :maxdepth: 1

   installation
   templates
   menu-builder
   ctrl-rad-bundle

Indices and tables
------------------

* :ref:`genindex`
* :ref:`modindex`

