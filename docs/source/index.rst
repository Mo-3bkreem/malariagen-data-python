MalariaGEN Python API documentation
===================================

**Useful links**: `Source Repository <https://github.com/malariagen/malariagen-data-python>`_ | `Issues & Ideas <https://github.com/malariagen/malariagen-data-python/issues>`_ | `Q&A Support <https://github.com/malariagen/malariagen-data-python/discussions>`_ | `Online Training <https://anopheles-genomic-surveillance.github.io/>`_

The ``malariagen_data`` Python package provides a library of functions (API) for accessing and analysing
data from the `Malaria Genomic Epidemiology Network (MalariaGEN) <https://www.malariagen.net/>`_.

API documentation
-----------------

.. grid::

   .. grid-item-card:: ``Ag3``
      :link: Ag3
      :link-type: doc

      *Anopheles gambiae* complex.

      .. image:: https://upload.wikimedia.org/wikipedia/commons/0/0a/AnophelesGambiaemosquito.jpg

   .. grid-item-card:: ``Af1``
      :link: Af1
      :link-type: doc

      *Anopheles funestus* subgroup.

     .. image::data:image/webp;base64,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.jpg

   .. grid-item-card:: ``Amin1``
      :link: Amin1
      :link-type: doc

      *Anopheles minimus*.

     .. image:: _static/mi/Anopheles_minimus.jpg

   .. grid-item-card:: ``Adir1``
      :link: Adir1
      :link-type: doc

      *Anopheles dirus* complex.

      .. image:: https://phil.cdc.gov//PHIL_Images/8777/8777_lores.jpg

Documentation for the `Pf7 <https://malariagen.github.io/parasite-data/pf7/api.html>`_ (*Plasmodium falciparum*)
and `Pv4 <https://malariagen.github.io/parasite-data/pv4/api.html>`_ (*Plasmodium vivax*) APIs is also available,
currently hosted on a separate site.


Installation
------------

The ``malariagen_data`` package is available from the Python package index (PyPI) and can be installed
via pip::

   pip install malariagen_data

For accessing data in Google Cloud Storage (GCS) you will also need to authenticate with Google Cloud.

If you are using ``malariagen_data`` from within Google Colab, authentication will be automatically
initiated, please allow access when requested.

If you are using ``malariagen_data`` from any location other than Google Colab, you will need to `set up application
default credentials <https://cloud.google.com/docs/authentication/provide-credentials-adc>`_. Generally
the best way to do this will be to `install the Google Cloud CLI <https://cloud.google.com/sdk/docs/install>`_
and then run the following command::

   gcloud auth application-default login


Training
--------

If you would like to learn more about how to use ``malariagen_data`` to analyse data for genomic
surveillance of malaria vectors, please see the associated `online training course <https://anopheles-genomic-surveillance.github.io>`_.


About the data
--------------

This software package provides access to data from MalariaGEN. MalariaGEN is a network
of malaria researchers and control programmes using genomics to learn more about malaria
transmission and control in Africa and Asia.

MalariaGEN generates **genome variation data** from whole-genome sequencing (WGS) of malaria
parasites (*Plasmodium*) or malaria-transmitting mosquitoes (*Anopheles*). Parasite and mosquitoes
are generally sampled from natural infections and mosquito populations, and so these are data on
natural genetic variation.

Some data from MalariaGEN are subject to **terms of use** which may include an embargo on
public communication of any analysis results without permission from data owners. If you
have any questions about terms of use please email support@malariagen.net.

By default, this software package accesses data directly from the **MalariaGEN cloud data repository**
hosted in Google Cloud Storage in the US. Note that data access will be more efficient if your
computations are also run within the same region. Google Colab provides a convenient and free
service which you can use to explore data and run computations. If you have any questions about
other options for running computations please `open a discussion <https://github.com/malariagen/malariagen-data-python/discussions>`_.
