# Isaac Walter documentation 

This repository includes Jupyter notebooks of the code that I have used to produce my report. Use of Jupyter notebooks is fairly straight forward.

## Usage

### Requirements
- Python2 or Python3
- Jupyter 

### Instructions
1. Open up a command prompt (CMD) terminal and open Python
2. Type "jupyter notebook" in the terminal
3. Navigate to one of the following documents with an .ipynb extension

-----------------------------------------------



:Name: EinsteinPy
:Website: https://einsteinpy.org/
:Version: 0.4.dev0


**EinsteinPy** is an open source pure Python package dedicated to problems arising
in General Relativity and gravitational physics, such as geodesics plotting for
Schwarzschild, Kerr and Kerr Newman space-time model, calculation of Schwarzschild
radius, calculation of Event Horizon and Ergosphere for Kerr space-time. Symbolic
Manipulations of various tensors like Metric, Riemann, Ricci, Ricci Scalar, Weyl,
Schouten, Stress-Energy-Momentum, Einstein and Christoffel Symbols is also possible
using the library. EinsteinPy also features Hypersurface Embedding of Schwarzschild
space-time, which will soon lead to modelling of Gravitational Lensing!
It is released under the MIT license.

Documentation
=============

|docs|

Complete documentation, including a user guide and an API reference, can be read on
the wonderful `Read the Docs`_.

https://docs.einsteinpy.org/

.. _`Read the Docs`: https://readthedocs.org/

Examples
========

.. |mybinder| image:: https://img.shields.io/badge/launch-binder-e66581.svg?style=flat-square
   :target: https://beta.mybinder.org/v2/gh/einsteinpy/einsteinpy/main?filepath=index.ipynb

|mybinder|

In the examples directory, you can find several Jupyter notebooks with specific
applications of einsteinpy. You can consider theses Jupyter Notebooks as tutorials for einsteinpy.
You can launch a cloud Jupyter server using `binder`_ to edit
the notebooks without installing anything. Try it out!

https://beta.mybinder.org/v2/gh/einsteinpy/einsteinpy/main?filepath=index.ipynb

.. _binder: https://beta.mybinder.org/

Requirements
============

EinsteinPy requires the following Python packages:

* NumPy, for basic numerical routines
* Astropy, for physical units and time handling
* Matplotlib, for static geodesics plotting and visualizations.
* Plotly, for interactive geodesics plotting and visualizations.
* SciPy, for solving ordinary differential equations.
* SymPy, for symbolic calculations related to GR.
* Numba, for accelerating the code
* EinsteinPy Geodesics, for calculating geodesics in Kerr geometries

EinsteinPy is usually tested on Linux, Windows and macOS on Python 3.7 and 3.8, against latest NumPy.

==============  ===============  ===================
Platform        Site             Status
==============  ===============  ===================
Linux           CircleCI         |circleci|
OS X            Github Actions   |ghactions|
Windows x64     Appveyor         |appveyor|
==============  ===============  ===================

Installation
============

The easiest and fastest way to get the package up and running is to
install EinsteinPy using `conda <http://conda.io>`_::

  $ conda install einsteinpy --channel conda-forge
  
Or you can simply install it from `PyPI <https://pypi.org/>`_::

  $ pip install einsteinpy

Or for Debian/Ubuntu/Mint users, the package is installable (Ubuntu 19.04 onwards) from `apt <https://packages.debian.org/sid/python3-einsteinpy>`_::

  $ sudo apt install python3-einsteinpy

Please note that the package version in Debian Repositories might not be the latest.
But it will be definitely the most stable version of EinsteinPy available till date.

Please check out the `guide for alternative installation methods`_.

.. _`guide for alternative installation methods`: https://einsteinpy.github.io/installation/


Problems
========

If the installation fails or you find something that doesn't work as expected,
please open an issue in the `issue tracker`_.

.. _`issue tracker`: https://github.com/einsteinpy/einsteinpy/issues

Contributing
============

EinsteinPy is a community project, hence all contributions are more than
welcome! For more information, head to `CONTRIBUTING.rst`_.

.. _`CONTRIBUTING.rst`: https://github.com/einsteinpy/einsteinpy/blob/main/CONTRIBUTING.rst

Developers Documentation can be found here.

Support
=======

|mailing|

Release announcements and general discussion take place on our `mailing list`_.
Feel free to join!

.. _`mailing list`: https://groups.io/g/einsteinpy-dev

https://groups.io/g/einsteinpy-dev

Please join our `[matrix]`_ channel or `gitter`_ chat room for further queries.

.. _`[matrix]`: https://matrix.to/#/#einsteinpy:matrix.org

.. _`gitter`: https://gitter.im/EinsteinPy-Project/EinsteinPy

If you still have a doubt, write a mail directly to `all@einsteinpy.org <mailto:all@einsteinpy.org>`_.

Citing
======

If you use EinsteinPy on your project, please
`drop us a line <mailto:all@einsteinpy.org>`_.

You can also use the DOI to cite it in your publications. This is the latest
one:

|doi|

And this is an example citation format::

 Shreyas Bapat et al.. (2019). EinsteinPy: einsteinpy 0.1.0. Zenodo. 10.5281/zenodo.2582388


License
=======

|license|

EinsteinPy is released under the MIT license, hence allowing commercial
use of the library. Please refer to `COPYING`_.

.. _`COPYING`: https://github.com/einsteinpy/einsteinpy/blob/main/COPYING

FAQ
===

Why Einstein-Py?
----------------

EinsteinPy comes from the name of the famous physicist, Nobel laureate, revolutionary person, Prof. Albert Einstein.
This is a small tribute from our part for the amazing work he did for the humanity!


Can I do <insert nerdy thing> with EinsteinPy?
----------------------------------------------

EinsteinPy is focused on general relativity.  One can always discuss probable features on the mailing list and try to implement it.
We welcome every contribution and will be happy to include it in EinsteinPy.

What's the future of the project?
---------------------------------

EinsteinPy is actively maintained and we hope to receive an influx of new contributors.
The best way to get an idea of the roadmap is to see the `Milestones`_ of
the project.

.. _`Milestones`: https://github.com/einsteinpy/einsteinpy/milestones

Inspiration
-----------

The whole documentation and code structure is shamelessly inspired by `poliastro`_ . We really thank the poliastro
developers to make this possible. EinsteinPy is nothing without it's supporters.

.. _`poliastro`: https://docs.poliastro.space/
