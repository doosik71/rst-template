## Create package .rst file

### command

```bash
./makerst package sample
```

### output

```rst
sample package
==============

Subpackages
-----------

.. toctree::

    sample.subpackages

Submodules
----------

.. toctree::

    sample.submodules

Module contents
---------------

.. automodule:: sample
    :members:
    :undoc-members:
    :show-inheritance:
```

## Create module .rst file

### command

```bash
./makerst package sample
```

### output

```rst
sample module
=============

.. automodule:: sample
    :members:
    :undoc-members:
    :show-inheritance:
```
