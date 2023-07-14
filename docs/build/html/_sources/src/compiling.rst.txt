.. _compiling:

Compiling source code
=====================

There are two easy options:

* Source -> Object -> Executable
* Source -> Executable

+----------------------+-----------------------------+
| Option               | Command                     |
+======================+=============================+
| Source -> Object     | gfortran -c hello.f90;      |
| -> Executable        | gfortran exe -o hello.o     | 
+----------------------+-----------------------------+
| Source -> Executable | gfortran -o exe hello.f90   |
+----------------------+-----------------------------+

Dependencies
------------

* `gfortran`_ (or another Fortran compiler) is a required dependency

.. _gfortran: https://gcc.gnu.org/

