.. spelling::

    clBLAS

.. index:: math ; clBLAS

.. _pkg.clBLAS:

clBLAS
======

.. warning::

    This page is a template and contains no real information.
    Please send pull request with real description.

-  `Official <https://github.com/clMathLibraries/clBLAS>`__
-  `Hunterized <https://github.com/hunter-packages/clBLAS>`__
-  `Example <https://github.com/ruslo/hunter/blob/master/examples/clBLAS/CMakeLists.txt>`__
-  Available since `v2.12 <https://github.com/ruslo/hunter/releases/tag/v2.12>`__
-  Added by `<https://github.com/gheaeckkseqrz>`__ (`__FIXME__ pr-N <https://github.com/ruslo/hunter/pull/N>`__)

.. code-block:: cmake

    hunter_add_package(clBLAS)
    find_package(clBLAS CONFIG REQUIRED)
    target_link_libraries(... clBLAS::libclBLAS)

