# Wheels for Python on Windows, linked to oneAPI MKL

This repository provides unofficial binary wheels for open-source extension packages for Python on Windows, linked to the [Intel(r) oneAPI Math Kernel Library](https://software.intel.com/en-us/intel-mkl/) (oneAPI MKL).

The files are unofficial (meaning: informal, unrecognized, personal, unsupported, no warranty, no liability, provided "as is") and made available for testing and evaluation purposes.

Source code changes, if any, have been submitted to the project maintainers or are included in the wheels.

The wheels can be downloaded from the [Releases](https://github.com/cgohlke/numpy-mkl-wheels/releases) page.

## Release 2024.1.3

Linked to oneAPI MKL 2024.0.0.
Depends on the latest
[Microsoft Visual C++ Redistributable](https://learn.microsoft.com/en-US/cpp/windows/latest-supported-vc-redist?view=msvc-170)
and the
[mkl](https://pypi.org/project/mkl/),
[intel-openmp](https://pypi.org/project/intel-openmp/), and
[intel-fortran-rt](https://pypi.org/project/intel-fortran-rt/) 2024 packages.

- [numpy](https://github.com/numpy/numpy) 1.26.3
- [scipy](https://github.com/scipy/scipy) 1.11.4
- [numexpr](https://github.com/pydata/numexpr) 2.8.8
- [mkl_fft](https://github.com/IntelPython/mkl_fft) 1.3.8
- [mkl_random](https://github.com/IntelPython/mkl_random) 1.2.4
- [mkl_service](https://github.com/IntelPython/mkl-service) 2.4.0

## Release 2023.11.5

<details>
  <summary>Details</summary>

Linked to oneAPI MKL 2022.2.1.

- [numpy](https://github.com/numpy/numpy) 1.26.1
- [scipy](https://github.com/scipy/scipy) 1.11.3
- [numexpr](https://github.com/pydata/numexpr) 2.8.7
- [mkl_fft](https://github.com/IntelPython/mkl_fft) 1.3.8
- [mkl_random](https://github.com/IntelPython/mkl_random) 1.2.4

</details>

## Release 2023.7.17

<details>
  <summary>Details</summary>

Linked to oneAPI MKL 2022.2.1.

- [numpy](https://github.com/numpy/numpy) 1.25.1
- [scipy](https://github.com/scipy/scipy) 1.11.1
- [numexpr](https://github.com/pydata/numexpr) 2.8.4
- [mkl_fft](https://github.com/IntelPython/mkl_fft) 1.3.1
- [mkl_random](https://github.com/IntelPython/mkl_random) 1.2.2
- [mkl_service](https://github.com/IntelPython/mkl-service) 2.4.0

</details>

## Release 2023.1.4

<details>
  <summary>Details</summary>

Linked to oneAPI MKL 2022.2.1.

- [numpy](https://github.com/numpy/numpy) 1.23.5
- [scipy](https://github.com/scipy/scipy) 1.9.3
- [numexpr](https://github.com/pydata/numexpr) 2.8.4

</details>

## Build system

- Windows 11 Pro for Workstations
- [Visual Studio](https://visualstudio.microsoft.com/vs/community/) 2022 Community 17.8
- [Intel oneAPI Base and HPC Toolkit](https://www.intel.com/content/www/us/en/developer/tools/oneapi/base-toolkit.html#gs.miarqe) 2024.0
- [LLVM](https://github.com/llvm/llvm-project/releases) 17.0
- [CPython](https://www.python.org/downloads/windows/) 3.9, 3.10, 3.11, 3.12

## Alternatives

Binaries for Python packages linked to the oneAPI MKL are also available as part of the [Intel(r) Distribution for Python](https://www.intel.com/content/www/us/en/developer/tools/oneapi/distribution-for-python.html).
