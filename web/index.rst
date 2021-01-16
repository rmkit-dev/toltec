======
Toltec
======

.. class:: center

a community-maintained repository of free software for the reMarkable tablet.

.. image:: ./logo.png
  :height: 400
  :class: logo


Install Toltec
==============

::

    $ wget http://toltec-dev.org/bootstrap
    $ echo "cbe83d1ae2d3ef6291a2b57202bb59aace14f2f1849bbdb09552a7419995294a bootstrap" | sha256sum -c
    $ bash bootstrap

.. class:: twocolumn

  To install Toltec, run the bootstrap script in a SSH session on your reMarkable

.. class:: twocolumn

  This script installs the toltec package repository and related tools.


What does Toltec do?
====================

.. class:: twocolumn

  Toltec is a repository of homebrew applications for the remarkable tablet, similar to homebrew for Mac or linux package repositories.

.. class:: twocolumn

::

     $ opkg install nao



How to use
==========

.. class:: twocolumn

  the **opkg** command is used to add/remove/update packages.

.. class:: twocolumn

::

     $ opkg update
     $ opkg upgrade
     $ opkg install <package>
     $ opkg remove <package>
     $ opkg info <package>

---------------------------------------------------------------

Frequently Asked Questions
==========================

* Where can I see all the packages available?

  at https://toltec-dev.org/stable

* Do you support reMarkable 2?

  Yes, but you need to install the rm2fb package if you want to use any applications that use the display.

* Is this supported by reMarkable AS?

  No, it is a community project

* Where can I get help?

  `please open an issue on github <#>`_

* Will this brick my remarkable?

  No, but `standard disclaimers apply <https://github.com/toltec-dev/toltec/blob/stable/LICENSE>`_
