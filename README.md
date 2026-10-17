## Connect Python workflows to DICOMweb services

This is a development fork of [DICOMweb Client](https://github.com/ImagingDataCommons/dicomweb-client), a Python client for DICOMweb RESTful services. Upstream provides both a Python package and a command-line interface, making it useful when imaging-data access needs to fit into scripts, notebooks, or repeatable data-transfer workflows.

**Contribution to review:** [PR #130](https://github.com/ImagingDataCommons/dicomweb-client/pull/130) proposes constraining command-line output paths derived from DICOM UIDs. The work focuses on output-file handling; the linked pull request contains the proposed implementation and review status.

Begin with the [official documentation](https://dicomweb-client.readthedocs.io), which includes user examples, installation guidance, and Python and CLI API references. The original README and scientific citation follow below. The [branch comparison](https://github.com/ImagingDataCommons/dicomweb-client/compare/master...jdotc1:master) shows the default branch's relationship to upstream.

---

# DICOMweb Client

[![Build Status](https://github.com/ImagingDataCommons/dicomweb-client/actions/workflows/run_unit_tests.yml/badge.svg)](https://github.com/ImagingDataCommons/dicomweb-client/actions)
[![PyPi Distribution](https://img.shields.io/pypi/v/dicomweb-client.svg)](https://pypi.python.org/pypi/dicomweb-client/)
[![Python Versions](https://img.shields.io/pypi/pyversions/dicomweb-client.svg)](https://pypi.org/project/dicomweb-client/)
[![Downloads](https://pepy.tech/badge/dicomweb-client)](https://pepy.tech/project/dicomweb-client)


Python client for DICOMweb services.


## Documentation

Please refer to the online documentation at [dicomweb-client.readthedocs.io](https://dicomweb-client.readthedocs.io), which includes a user guide with examples, a developer guide, and complete documentation of the application programming interface of the `dicomweb_client` Python package as well as the command line interface of the `dicomweb_client` program.


## Citation

Please cite the following article when using the client for scientific studies: [Herrmann et al. J Path Inform. 2018](http://www.jpathinformatics.org/article.asp?issn=2153-3539;year=2018;volume=9;issue=1;spage=37;epage=37;aulast=Herrmann):

```None
@article{jpathinform-2018-9-37,
    Author={
        Herrmann, M. D. and Clunie, D. A. and Fedorov A. and Doyle, S. W. and Pieper, S. and
        Klepeis, V. and Le, L. P. and Mutter, G. L. and Milstone, D. S. and Schultz, T. J. and
        Kikinis, R. and Kotecha, G. K. and Hwang, D. H. and Andriole, K, P. and Iafrate, A. J. and
        Brink, J. A. and Boland, G. W. and Dreyer, K. J. and Michalski, M. and
        Golden, J. A. and Louis, D. N. and Lennerz, J. K.
    },
    Title={Implementing the {DICOM} standard for digital pathology},
    Journal={Journal of Pathology Informatics},
    Year={2018},
    Number={1},
    Volume={9},
    Number={37}
}

```

