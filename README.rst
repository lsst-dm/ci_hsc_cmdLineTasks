==========
``ci_hsc_cmdLineTasks``
==========

``ci_hsc_cmdLineTasks`` provides scripts which exercises the LSST stack
through single frame and coadd processing based on engineering test data from
Hyper Suprime-Cam provided by ``ci-hsc``.

Running the tests
=================

Set up the package
------------------

The package must be set up in the usual way before running::

  $ cd ci_hsc_cmdLineTasks
  $ setup -j -r .

Running the tests
-----------------

Execute ``scons``. On a Mac running OSX 10.11 or greater, you must specify a
Python interpreter followed by a full path to ``scons``::

  $ python $(which scons)

On other systems, simply running ``scons`` should be sufficient.
