# Wheels for Python on Windows, linked to oneAPI MKL

This repository provides unofficial binary wheels for open-source extension packages for Python on Windows, linked to the [Intel(r) oneAPI Math Kernel Library](https://software.intel.com/en-us/intel-mkl/) (oneAPI MKL).

The files are unofficial (meaning: informal, unrecognized, personal, unsupported, no warranty, no liability, provided "as is") and made available for testing and evaluation purposes.

Source code changes, if any, have been submitted to the project maintainers or are included in the wheels.

The wheels can be downloaded from the [Releases](https://github.com/cgohlke/numpy-mkl-wheels/releases) page.

## Release 2025.1.4

Linked to oneAPI MKL 2025 (64-bit) and 2024.2 (32-bit).

Depends on the latest
[Microsoft Visual C++ Redistributable](https://learn.microsoft.com/en-US/cpp/windows/latest-supported-vc-redist)
and the
[mkl](https://pypi.org/project/mkl/),
[intel-openmp](https://pypi.org/project/intel-openmp/), and
[intel-fortran-rt](https://pypi.org/project/intel-fortran-rt/) packages.

- [numpy](https://github.com/numpy/numpy) 2.2.1
- [scipy](https://github.com/scipy/scipy) 1.15.0
- [numexpr](https://github.com/pydata/numexpr) 2.10.2
- [mkl_fft](https://github.com/IntelPython/mkl_fft) 1.3.11
- [mkl_random](https://github.com/IntelPython/mkl_random) 1.2.8
- [mkl_service](https://github.com/IntelPython/mkl-service) 2.4.2

## Build system

- Windows 11 Pro for Workstations
- [Visual Studio](https://visualstudio.microsoft.com/vs/community/) 2022 Community 17.12
- [Intel oneAPI Base and HPC Toolkit](https://www.intel.com/content/www/us/en/developer/tools/oneapi/base-toolkit.html#gs.miarqe) 2025 (64-bit) and 2024.2 (32-bit and ifort)
- [LLVM](https://github.com/llvm/llvm-project/releases) 19.1.6
- [CPython](https://www.python.org/downloads/windows/) 3.10, 3.11, 3.12, 3.13

## Alternatives

Binaries for Python packages linked to the oneAPI MKL are also available as part of the [Intel(r) Distribution for Python](https://www.intel.com/content/www/us/en/developer/tools/oneapi/distribution-for-python.html).
