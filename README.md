# PythonProteomics
This repository contains a list of open source Python tools for Proteomics analysis. The list is very likely incomplete and we are happy to take pull request with new tools.

# Contents

* [Introduction](#intro)
* Packages
  * Full Libraries
    * [pyOpenMS](#pyOpenMS)
    * [pyteomics](#pyteomics)
    * [multiplierz](#multiplierz)
    * [pyproteome](#pyproteome)
  * Specialized packages
    * [pyMzML](#pyMzML)
    * [pyProphet](#pyProphet)
    * [msproteomicstools](#msproteomicstools)
  
<a name="intro"></a>
# Intro

Python is a versatile scripting language that is widely used in industry and academia. In bioinformatics, there are multiple packages supporting data analysis with Python that range from biological sequence analysis with Biopython to structural modeling and visualization with packages like PyMOL and PyRosetta, to numerical computation and advanced plotting with NumPy/SciPy. In the proteomics community, Python began to be widely used around 2012 when several mature Python packages were published including pymzML, Pyteomics and pyOpenMS. This has led to an ever-increasing interest in the Python programming language in the proteomics and mass spectrometry community. The number of publications referencing or using Python has risen eight fold since 2012 (compared with the same time period before 2012), with multiple open-source Python packages now supporting mass spectrometric data analysis and processing. Computing and data analysis in mass spectrometry is very diverse and in many cases must be tailored to a specific experiment. Often, multiple analysis steps have to be performed (identification, quantification, post-translational modification analysis, filtering, FDR analysis etc.) in an analysis pipeline, which requires high flexibility in the analysis. This is where Python truly shines, due to its flexibility, visualization capabilities and the ability to extend computation with a large number of powerful libraries. Python can be used to quickly prototype software, combine existing libraries into powerful analysis workflows while avoiding the trap of re-inventing the wheel for a new project.

# Libraries

## Full libraries

These packages contain full-fledged Python libraries that can process Proteomics data

<a name="pyOpenMS"></a>
### pyOpenMS

[pyOpenMS ](https://pyopenms.readthedocs.io/en/latest/) is an open-source Python library for mass spectrometry, specifically for the analysis of proteomics and metabolomics data in Python. pyOpenMS implements a set of Python bindings to the OpenMS library for computational mass spectrometry and is available for Windows, Linux and OSX.

<a name="pyteomics"></a>
### pyteomics

[Pyteomics](https://pyteomics.readthedocs.io/en/latest/) is a collection of lightweight and handy tools for Python that help to handle various sorts of proteomics data. Pyteomics provides a growing set of modules to facilitate the most common tasks in proteomics data analysis, such as:

<a name="multiplierz"></a>
### multiplierz
[multiplierz](https://github.com/BlaisProteomics/multiplierz) is a Python software library and associated GUI desktop environment for managing proteomic mass spectrometry workflows and data analysis. Using the mzAPI interface to native instrument data formats, multiplierz is provides a complete toolset for a variety of methods for peptide identification, quantitation, and experimental reporting.

<a name="pyproteome"></a>
### pyproteome

[pyproteome](https://github.com/white-lab/pyproteome): Python library for analyzing mass spectrometry proteomics data.

## Specialized packages

These packages contain specialized functions that help with a specific aspect of Proteomics data processing

<a name="pyMzML"></a>
### pyMzML

<a name="pyProphet"></a>
### pyProphet

[PyProphet](https://github.com/PyProphet/pyprophet): Semi-supervised learning and scoring of OpenSWATH results.



<a name="msproteomicstools"></a>
### msproteomicstools

[msproteomicstools](http://msproteomicstools.roestlab.org/): is a Python library that can be used in LC-MS/MS based proteomics. It features a core library called msproteomicstoolslib and several associated executable scripts that use the library as well as a GUI for visualizing chromatograms, specifically output from OpenSWATH.
