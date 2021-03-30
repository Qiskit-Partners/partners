###########################
Qiskit Partner requirements
###########################

Location
########

All Partner plugin repositories for Qiskit shall be located in the Qiskit Partners
organization on GitHub and will be subject to the terms of the Qistkit Partners
requirements and contribution standards.

Code of Conduct
###############

All Qiskit Partners are to abide by the
`Qiskit Code of Conduct <https://github.com/Qiskit/qiskit/blob/master/CODE_OF_CONDUCT.md>`_.

Administration
##############

In order to better streamline the integration, testing, and validation
processes, all Partner repositories will be jointly administered by the
Partner and Qiskit, and will be subject to mutually agreed upon continuous
integration/continuous deployment build processes to ensure timely updates
and continued compatibility.  Partners will be evaluated on an annual basis
to ensure they meet the requirements of membership in the Qiskit Partner program.  

Partners working with Qiskit will make good faith efforts to maintain compatibility
with latest version of Qiskit.

Documentation
#############

Documentation is a critical resource for enabling users to correctly and efficiently
use a specific piece of quantum hardware or software.  As such, having in-depth
documentation is at the very heart of what it means to be a Qiskit Partner.  To this end,
every Qiskit Partner must have documentation that follows the below requirements:

- Indicates how to install the provider software, and/or software needed to access quantum hardware, if any.
- Tutorials and/or user guides that demonstrate the feature set of the software / hardware, and how it integrates into Qiskit, e.g. usage of the transpiler to convert to the native system gate set.
- Examples and tutorials must be tested for compatibility and faithful execution.
- Links to any supported backends and their connectivity/topology.
- With calibration/noise models, show how to simulate with Qiskit Aer or a provider supplied simulator.
- There should be a complete set of API documentation for user facing functionality, with documentation following the Google-style of doc-strings.

Code
####

Code standards
--------------

- Code for integrating with Qiskit must be open source, and licensed equivalently to Apache 2.0, e.g. MIT, BSD, etc. GPL and LGPL licenses cannot be used.

- Continuous Integration testing:
  - Code must be under agreed upon continuous integration testing.
  - Unit testing should include testing against a mock device API if needed.
  - If necessary, tests should ensure that API handles responses correctly, e.g. testing using a API-based simulator.

  - Code documentation and styling:
    - Code must be documented using Google-style doc-strings.
    - Code must follow PEP8 style guidelines, e.g. there must be tests that check for lint and style errors.
    - There must be a set of release notes corresponding to each release of the package once it becomes a Partner.

  - Compatibility:
    - The Partner code should be kept up to date with Qiskit.
    - Code must follow standard Qiskit deprecation guidelines: https://qiskit.org/documentation/contributing_to_qiskit.html#deprecation-policy

Expanding the Qiskit ecosystem
##############################

The Qiskit ecosystem is only as strong as the commitment from its developers, users,
and Partners.  To this end, it is expected that Partners maintain an active role in
the development of Qiskit and the community as a whole.  Such contributions could
include code contributions for better compilation strategies for the Partners quantum
system, Qiskit tutorials, active engagement in the Qiskit Community Slack channel, etc.

.. Hiding - Indices and tables
   :ref:`genindex`
   :ref:`modindex`
   :ref:`search`
