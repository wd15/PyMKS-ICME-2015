Microstructure informatics is an emerging field of study that
encompasses techniques from signal processing, advanced statistics and
data science. The Materials Knowledge System (MKS) forms an important
subset of microstructure informatics by providing a localization
technique to bridge the micro and macroscales. An MKS model is
calibrated using established numerical models or experimental data at
the microscale by calculating a set of influence coefficients using
regression analysis. The influence coefficients are then scaled up to
provide an approximate model at the macroscale. A Fourier transform is
used to both calibrate the coefficients and predict the response
making the MKS highly efficient when compared to standard numerical
models. The calibrate/predict MKS paradigm enables an existing
inefficient physics-based code to provide approximate results at much
longer length scales and relieves developers from focusing on
efficiency issues when developing new physics-based codes. The main
limitations of the MKS are associated with the geometry of the spatial
domain, which is inherently limited by the Fourier transform. However,
studies of microstructure in materials science often use only
block-like subdomains ideally suited to the MKS.

The PyMKS framework is an object oriented set of tools and examples
written in Python that provides high level access to the MKS method
enabling rapid analysis of microstructure/response relationships. The
PyMKS uses the standard Python libraries making it work well with the
existing scientific Python ecosystem. In particular, it relies on
Scikit-learn for tuning sample sizes and hyperparameters. The
presentation will provide an introduction to the MKS and an overview
of the capabilities and implementation details of PyMKS.


