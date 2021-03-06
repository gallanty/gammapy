.. include:: references.txt

.. _tutorials:

Gammapy tutorial notebooks
==========================

What is this?
-------------

-  This is an overview of tutorial `Jupyter <http://jupyter.org/>`__
   notebooks for `Gammapy <http://gammapy.org>`__, a Python package for
   gamma-ray astronomy.
-  The notebooks complement the Gammapy Sphinx-based documentation at
   http://docs.gammapy.org
-  The notebooks and example datasets are available at
   https://github.com/gammapy/gammapy-extra

Set up
------

If you want to execute the notebooks locally, to play around with the
examples, or to try to do one of the exercises, you have to first
install Gammapy and get the ``gammapy-extra`` repository. This is
described in `Gammapy tutorial
setup <notebooks/tutorial_setup.html>`__.

You can also download for each version of *gammapy* a
`HTMLZip pack <http://readthedocs.org/projects/gammapy/downloads/>`__
containing the whole documentation and full collection of notebooks, so you can execute
them in your local desktop inside the `_static/notebooks/` folder.

The basics
----------

Gammapy is a Python package built on Numpy and Astropy, and the
tutorials are Jupyter notebooks. If you're already familar with those,
you can skip to the next section and start learning about Gammapy.

If you're new to Python or scientific Python, we can recommmend the
following resources:

-  `A Whirlwind tour of Python <http://nbviewer.jupyter.org/github/jakevdp/WhirlwindTourOfPython/blob/master/Index.ipynb>`__ (learn Python)
-  `Python data science handbook <http://nbviewer.jupyter.org/github/jakevdp/PythonDataScienceHandbook/blob/master/notebooks/Index.ipynb>`__ (learn IPython, Numpy, matplotlib)
-  `Scipy lectures <http://www.scipy-lectures.org/>`__ (another intro to scientific Python)

If you're new to Astropy, here's some good resources:

-  http://www.astropy.org/astropy-tutorials
-  http://astropy.readthedocs.io
-  https://python4astronomers.github.io/

Notebooks
---------

If you're new to Astro (haven't used ``Table``, ``SkyCoord`` and
``Time`` much), start here:

-  `Astropy introduction for Gammapy users <notebooks/astropy_introduction.html>`__  | *astropy_introduction.ipynb*
-  `Astropy Hands On (1st ASTERICS-OBELICS International School) <https://github.com/Asterics2020-Obelics/School2017/blob/master/astropy/astropy_hands_on.ipynb>`__

For a quick introduction to Gammapy, go here:

-  `First steps with Gammapy <notebooks/first_steps.html>`__  | *first_steps.ipynb*

Interested to do a first analysis of simulated CTA data?

-  `CTA first data challenge (1DC) with Gammapy <notebooks/cta_1dc_introduction.html>`__ | *cta_1dc_introduction.ipynb*
-  `CTA data analysis with Gammapy <notebooks/cta_data_analysis.html>`__ | *cta_data_analysis.ipynb*

To learn how to work with gamma-ray data with Gammapy:

-  `IACT DL3 data with Gammapy <notebooks/data_iact.html>`__ (H.E.S.S data example) | *data_iact.ipynb*
-  `Fermi-LAT data with Gammapy <notebooks/data_fermi_lat.html>`__ (Fermi-LAT data example) | *data_fermi_lat.ipynb*

2-dimensional sky image analysis:

-  `Image analysis with Gammapy (run pipeline) <notebooks/image_pipe.html>`__ (H.E.S.S. data example) | *image_pipe.ipynb*
-  `Image analysis with Gammapy (individual steps) <notebooks/image_analysis.html>`__ (H.E.S.S. data example) | *image_analysis.ipynb*
-  `Source detection with Gammapy <notebooks/detect_ts.html>`__ (Fermi-LAT data example) | *detect_ts.ipynb*

1-dimensional spectral analysis:

-  `Spectral models in Gammapy <notebooks/spectrum_models.html>`__ | *spectrum_models.ipynb*
-  `Spectral analysis with Gammapy (run pipeline) <notebooks/spectrum_pipe.html>`__ (H.E.S.S. data example) | *spectrum_pipe.ipynb*
-  `Spectral analysis with Gammapy (individual steps) <notebooks/spectrum_analysis.html>`__ (H.E.S.S. data example) | *spectrum_analysis.ipynb*
-  `Spectrum simulation and fitting <notebooks/cta_simulation.html>`__ (CTA data example with AGN / EBL) | *cta_simulation.ipynb*
-  `Flux point fitting with Gammapy <notebooks/sed_fitting_gammacat_fermi.html>`__ | *sed_fitting_gammacat_fermi.ipynb*

3-dimensional cube analysis:

-  `Cube analysis with Gammapy (part 1) <notebooks/cube_analysis_part1.html>`__ (compute cubes and mean PSF / EDISP) | *cube_analysis_part1.ipynb*
-  `Cube analysis with Gammapy (part 2) <notebooks/cube_analysis_part2.html>`__ (likelihood fit) | *cube_analysis_part2.ipynb*

Time-related analysis:

-  `Light curve estimation with Gammapy <notebooks/light_curve.html>`__ | *light_curve.ipynb*
-  `Time analysis with Gammapy <notebooks/time_analysis.html>`__ (not written yet) | *time_analysis.ipynb*

Extra topics
~~~~~~~~~~~~

These notebooks contain examples on some more specialised functionality in Gammapy.

Most users will not need them. It doesn't make much sense that you read
through all of them, but maybe browse the list and see if there's
something that could be interesting for your work (or contribute to
Gammapy if something is missing!).

-  `Template background model production with Gammapy <notebooks/background_model.html>`__ | *background_model.ipynb*
-  `Continuous wavelet transform on gamma-ray images <notebooks/cwt.html>`__ | *cwt.ipynb*
-  `Interpolation using the NDDataArray class <notebooks/nddata_demo.html>`__ | *nddata_demo.ipynb*
-  `Rapid introduction on using numpy, scipy, matplotlib <notebooks/using_numpy.html>`__ | *using_numpy.ipynb*

Work in progress
~~~~~~~~~~~~~~~~

The following notebooks are work in progress or broken.

Please help make these better, or write new, better ones!

-  TODO: joint Fermi-IACT analysis with Gammpy
-  TODO: simulate Fermi and CTA sky with Gammapy

-  `Astrophysical source population modeling with Gammapy <notebooks/source_population_model.html>`__ | *source_population_model.ipynb*
-  `Source catalogs <notebooks/source_catalogs.html>`__ (working with gamma-ray source catalogs) | *source_catalogs.ipynb*
-  `Diffuse model computation <notebooks/diffuse_model_computation.html>`__ (diffuse model computation) | *diffuse_model_computation.ipynb*
-  `Fermi Vela model <notebooks/fermi_vela_model.html>`__ (Fermi Vela model) | *fermi_vela_model.ipynb*
-  `Simulating and analysing sources and diffuse emission <notebooks/source_diffuse_estimation.html>`__ | *source_diffuse_estimation.ipynb*

List of notebooks
~~~~~~~~~~~~~~~~~~

Here's a complete list of all notebooks. Note that some are for experts and debugging.
All end-user notebooks are listed above grouped by topic.

.. toctree::
   :titlesonly:
   :glob:

   notebooks/*
