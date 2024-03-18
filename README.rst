QDarkGray Stylesheet
====================

.. image:: https://img.shields.io/travis/Uvemode/qcrimsostyle/master.svg?style=flat-square
    :target: https://travis-ci.org/Uvemode/qcrimsostyle

.. image:: https://img.shields.io/pypi/v/qcrimsostyle.svg?style=flat-square
    :target: https://pypi.org/project/qcrimsostyle

.. image:: https://img.shields.io/pypi/pyversions/qcrimsostyle.svg?style=flat-square
    :target: https://pypi.org/project/qcrimsostyle

.. image:: https://img.shields.io/pypi/l/qcrimsostyle.svg?style=flat-square
    :target: https://github.com/Uvemode/qcrimsostyle/blob/master/LICENSE

A dark gray stylesheet for PyQt5 applications. This theme is a gray variation of `QDarkStyleSheet <https://github.com/ColinDuquesnoy/QDarkStyleSheet>`_ theme.

Installation
============

Install **qcrimsostyle** package using the *setup* script or using *pip*

.. code:: bash

    python setup.py install

or

.. code:: bash

    pip install qcrimsostyle

The *PySide* and *PyQt4* support was dropped in version *1.0.0*. To use `qcrimsostyle` with *PySide* or *PyQt4* or with *Python 2.7*, please use the version *0.0.3*.

.. code:: bash

    pip install qcrimsostyle==0.0.3

The support to *PySide2* will be add in future.

Usage
============

Here is an example using PyQt5.

.. code:: python

    import sys
    import qcrimsostyle
    from PyQt5 import QtWidgets

    # create the application and the main window
    app = QtWidgets.QApplication(sys.argv)
    window = QtWidgets.QMainWindow()

    # setup stylesheet
    app.setStyleSheet(qcrimsostyle.load_stylesheet())

    # run
    window.show()
    app.exec_()

There is an example included in the *example* folder.

.. code:: bash

    python example/example_pyqt5.py

You can run the script without installing `qcrimsostyle`. You only need to have
PyQt5 installed on your system.


Contribute
==========

- Issue Tracker: https://github.com/Uvemode/qcrimsostyle/issues
- Source Code: https://github.com/Uvemode/qcrimsostyle

Snapshots
=========

Here are a few snapshots:

* `Screenshot 1 <https://github.com/Uvemode/qcrimsostyle/blob/master/screenshots/screen-01.png>`_
* `Screenshot 2 <https://github.com/Uvemode/qcrimsostyle/blob/master/screenshots/screen-02.png>`_
* `Screenshot 3 <https://github.com/Uvemode/qcrimsostyle/blob/master/screenshots/screen-03.png>`_

Contributing
============

1. Fork it (https://github.com/Uvemode/qcrimsostyle/fork)
2. Create your feature branch (``git checkout -b feature/fooBar``)
3. Commit your changes (``git commit -am 'Add some fooBar'``)
4. Push to the branch (``git push origin feature/fooBar``)
5. Create a new Pull Request

Credits
=======
This package is totally based on `QDarkStyleSheet <https://github.com/ColinDuquesnoy/QDarkStyleSheet>`_ theme created by `Colin Duquesnoy <https://github.com/ColinDuquesnoy>`_.

Copyright (C) 2017-2018 by Michell Stuttgart
