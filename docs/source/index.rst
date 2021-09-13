.. UAB CINL documentation master file

========================================
Welcome to UAB CINL's documentation!
========================================

The Civitan International Neuroimaging Laboratory provides a core resource at
UAB for state-of-the-art MRI neuroimaging experiments and analyses for examining
brain and body anatomy and function both in health and disease. 

This houses technical information for CINL mainly pertaining to data storage,
organization, pre-processing, and processing on UAB's computing cluster Cheaha.
Cheaha provides researchers with both data storage space as well as a large
amount of computational power necessary for high-throughput neuroimaging
analysis. Access to the Cheaha cluster is free for UAB researchers. Request an
account using the following `instructions <https://docs.uabgrid.uab.edu/wiki/Cheaha_GettingStarted>`_

.. note::

   This project is under active development. To request changes or additions to
   the documentation, please submit an issue to the `main Github Repository <https://github.com/mdefende/CINL-Docs>`_


XNAT
====================


About XNAT
--------------------

XNAT is an open-source imaging imformatics platform developed at Washington
Univeristy with a deployment here at UAB. It facilitates both MRI data storage
in a common structure as well as sharing across labs both internal and external
to UAB. It is free to use for all researchers at UAB. More information can be
found at www.xnat.org


Why Use XNAT
--------------------
- Can send data directly from the scanner to XNAT without copying to a flash drive
- Easy to add collaborators to projects and share data across labs
- Can act as a data backup
- Common storage system makes data preprocessing pipelines more generalizeable

.. toctree::
    :maxdepth: 2
    :hidden:
    :caption: XNAT

    /xnat/account
    /xnat/projects
    /xnat/file-management

This documenatation contains information on how to :doc:`create and manage
accounts </xnat/account>`, :doc:`create projects </xnat/projects>`, and
:doc:`upload and download data </xnat/projects>`.