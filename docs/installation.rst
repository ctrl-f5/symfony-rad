.. py:module:: Installation

Installation
============

Composer
--------

::

   composer create-project ctrl-f5/symfony-rad
   # you can optionally set var/ permissions using setfacl with the following script
   bin/set_cache_permissions

Install Database
----------------

::

   bin/console doctrine:database:create
   bin/console doctrine:schema:update --force

Create User
-----------

::

   bin/console fos:user:create admin admin@local.com admin --super-admin

Run Server
----------

::

   bin/console server:run
