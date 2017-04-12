3D Forest Tools
###############

|license_badge| |travis_badge| |docs_badge|

|pypi_badge| |version_badge| |status_badge|

.. |license_badge| image:: https://img.shields.io/pypi/l/forestutils.svg
   :target: https://en.wikipedia.org/wiki/GNU_General_Public_License

.. |travis_badge| image:: https://travis-ci.org/borevitzlab/3D-tools.svg?branch=master
   :target: https://travis-ci.org/borevitzlab/3D-tools

.. |docs_badge| image:: https://readthedocs.org/projects/3d-tools/badge
   :target: https://3d-tools.readthedocs.org

.. |pypi_badge| image:: https://img.shields.io/pypi/v/forestutils.svg
   :target: https://pypi.python.org/pypi/forestutils

.. |version_badge| image:: https://img.shields.io/pypi/pyversions/forestutils.svg
   :target: https://pypi.python.org/pypi/forestutils

.. |status_badge| image:: https://img.shields.io/pypi/status/forestutils.svg
   :target: https://pypi.python.org/pypi/forestutils

.. END_BADGES_TAG

``forest3D`` is a set of tools for analysing pointclouds of a forest. Updated form
of 3D-tools.

Running a packaged module as a script gives an error on the relative import;
it is recommended to write a script which imports forestutils and calls
forestutils.main()


Features:

- Detect, map, and extract trees from the full pointcloud
- Calculate location, height, canopy area, and colour of each tree
- Losslessly reduce pointcloud size by discarding ground points

It is written in pure Python (3.4+), available under the GPL3 license,
and can analyse multi-gigabyte datasets in surprisingly little memory.

.. END_DESCRIPTION_TAG

Useful links
============

- `documentation <https://3d-tools.readthedocs.org>`_
- `processed pointclouds <https://pointclouds.phenocam.org.au>`_
- `maps (from output) <https://www.google.com/maps/d/viewer?mid=zH6cETTFeU6A.kawPmizn8suk>`_
- `source code <https://github.com/borevitzlab/3D-tools>`_
- `forestutils package <https://pypi.python.org/pypi/forestutils>`_ on PyPi

Contact: *zac.hatfield.dodds at gmail.com*
