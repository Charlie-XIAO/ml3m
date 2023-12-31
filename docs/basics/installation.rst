Installation
============

ml3m requires Python 3.8+ and can work on Linux/MacOS/Windows. Its dependencies include
the following:

- `numpy <https://numpy.org/>`_
- `openai <https://platform.openai.com/docs/api-reference/introduction?lang=python>`_
- `pandas <https://pandas.pydata.org/>`_
- `tqdm <https://tqdm.github.io/>`_

The recommended way to install ml3m is via pip:

.. code-block::

    pip install ml3m

After you have installed the package, you can use the following command to check the
versions and dependencies:

.. code-block::

    python -c "import ml3m; ml3m.show_versions()"

Since this package is still unstable and may frequently have new releases, you can
always keep up whenever there is a new version available:

.. code-block::

    pip install --upgrade ml3m
