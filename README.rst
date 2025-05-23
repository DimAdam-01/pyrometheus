Pyrometheus: Code Generation for Combustion Mechanisms
======================================================

.. image:: doc/pyro.png
	   :width: 640
.. image:: https://github.com/pyrometheus/pyrometheus/actions/workflows/ci.yml/badge.svg
    :alt: Github Build Status
    :target: https://github.com/pyrometheus/pyrometheus/actions
.. image:: https://readthedocs.org/projects/pyrometheus/badge/?version=latest
    :alt: Documentation Status
    :target: https://pyrometheus.readthedocs.io/en/latest/?badge=latest
.. image:: https://img.shields.io/pypi/v/pyrometheus
    :alt: Python Package Index Release Page
    :target: https://pypi.org/project/pyrometheus/
.. image:: https://img.shields.io/badge/License-MIT-red.svg
    :alt: MIT License
    :target: https://opensource.org/license/mit

.. When you update this description, consider also updating the one in doc/index.rst.

Pyrometheus is a code generator for chemical mechanisms based on `Cantera
<https://cantera.org>`__::

    $ python3 -m pip install pyrometheus
    $ python3 -m pyrometheus --help
    usage: pyrometheus [-h] [--version] -l {python,cpp,fortran} -m MECH -o OUTPUT -n NAME [-p PHASE]
    
    Code generation for combustion thermochemistrybased on Cantera.
    
    options:
      -h, --help            show this help message and exit
      --version             show program's version number and exit
      -l {python,cpp,fortran}, --lang {python,cpp,fortran}, --language {python,cpp,fortran}
                            Language to generate code for.
      -m MECH, --mech MECH, --mechanism MECH
                            Path to the mechanism file.
      -o OUTPUT, --output OUTPUT
                            Path to the output file.
      -n NAME, --name NAME, --namespace NAME
                            Namespace to use for the generated code.
      -p PHASE, --phase PHASE
                            Phase name to use for the generated code.

Links:

* `Documentation <https://pyrometheus.readthedocs.io/en/latest/>`__

* `GitHub <https://github.com/pyrometheus/pyrometheus>`__
