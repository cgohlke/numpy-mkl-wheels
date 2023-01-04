# Experimental Wheels for Python on Windows linked to oneAPI MKL

This repository provides experimental binary wheels for open-source extension packages for Python on Windows linked to the [Intel(r) oneAPI Math Kernel Library](https://software.intel.com/en-us/intel-mkl/) (oneAPI MKL).

The files are experimental (meaning: unofficial, informal, unrecognized, unsupported, no warranty, no liability, provided "as is") and made available for testing and evaluation purposes.

Source code changes, if any, have been submitted to the project maintainers or are included in the wheels.

The required redistributable oneAPI runtime files are packaged in the numpy.DLLs directory.

The wheels can be downloaded from the [Releases](https://github.com/cgohlke/numpy-mkl.whl/releases) page.

## Release 2023.1.4

Linked to oneAPI MKL 2022.2.1.

- [numpy](https://github.com/numpy/numpy) 1.23.5
- [scipy](https://github.com/scipy/scipy) 1.9.3
- [numexpr](https://github.com/pydata/numexpr) 2.8.4

## Build system

- Windows 10 Pro for Workstations
- [Visual Studio](https://visualstudio.microsoft.com/vs/community/) 2022 Community 17.4
- [Intel oneAPI Base and HPC Toolkit](https://www.intel.com/content/www/us/en/developer/tools/oneapi/base-toolkit.html#gs.miarqe) 2022.3
- [LLVM](https://github.com/llvm/llvm-project/releases) 15.0
- [CPython](https://www.python.org/downloads/windows/) 3.9, 3.10, 3.11
- [PyPy](https://www.pypy.org/download.html) 3.9

## Alternatives

Binaries for Python packages linked to the oneAPI MKL are also available as part of the [Intel(r) Distribution for Python](https://www.intel.com/content/www/us/en/developer/tools/oneapi/distribution-for-python.html).
