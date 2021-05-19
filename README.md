About pyston
============

Home: https://github.com/astrorama/pyston

Package license: LGPLv3+

Feedstock license: [BSD-3-Clause](https://github.com/astrorama/pyston-feedstock/blob/master/LICENSE.txt)

Summary: Pyston is a "quick and dirty" C++ library that can be used to build kind-of AST leveraging the Python interpreter.

Current build status
====================


<table>
    
  <tr>
    <td>Azure</td>
    <td>
      <details>
        <summary>
          <a href="https://dev.azure.com/astrorama/feedstock-builds/_build/latest?definitionId=7&branchName=master">
            <img src="https://dev.azure.com/astrorama/feedstock-builds/_apis/build/status/pyston-feedstock?branchName=master">
          </a>
        </summary>
        <table>
          <thead><tr><th>Variant</th><th>Status</th></tr></thead>
          <tbody><tr>
              <td>linux_64_python3.6.____cpython</td>
              <td>
                <a href="https://dev.azure.com/astrorama/feedstock-builds/_build/latest?definitionId=7&branchName=master">
                  <img src="https://dev.azure.com/astrorama/feedstock-builds/_apis/build/status/pyston-feedstock?branchName=master&jobName=linux&configuration=linux_64_python3.6.____cpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_64_python3.7.____cpython</td>
              <td>
                <a href="https://dev.azure.com/astrorama/feedstock-builds/_build/latest?definitionId=7&branchName=master">
                  <img src="https://dev.azure.com/astrorama/feedstock-builds/_apis/build/status/pyston-feedstock?branchName=master&jobName=linux&configuration=linux_64_python3.7.____cpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_64_python3.8.____cpython</td>
              <td>
                <a href="https://dev.azure.com/astrorama/feedstock-builds/_build/latest?definitionId=7&branchName=master">
                  <img src="https://dev.azure.com/astrorama/feedstock-builds/_apis/build/status/pyston-feedstock?branchName=master&jobName=linux&configuration=linux_64_python3.8.____cpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>linux_64_python3.9.____cpython</td>
              <td>
                <a href="https://dev.azure.com/astrorama/feedstock-builds/_build/latest?definitionId=7&branchName=master">
                  <img src="https://dev.azure.com/astrorama/feedstock-builds/_apis/build/status/pyston-feedstock?branchName=master&jobName=linux&configuration=linux_64_python3.9.____cpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx_64_python3.6.____cpython</td>
              <td>
                <a href="https://dev.azure.com/astrorama/feedstock-builds/_build/latest?definitionId=7&branchName=master">
                  <img src="https://dev.azure.com/astrorama/feedstock-builds/_apis/build/status/pyston-feedstock?branchName=master&jobName=osx&configuration=osx_64_python3.6.____cpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx_64_python3.7.____cpython</td>
              <td>
                <a href="https://dev.azure.com/astrorama/feedstock-builds/_build/latest?definitionId=7&branchName=master">
                  <img src="https://dev.azure.com/astrorama/feedstock-builds/_apis/build/status/pyston-feedstock?branchName=master&jobName=osx&configuration=osx_64_python3.7.____cpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx_64_python3.8.____cpython</td>
              <td>
                <a href="https://dev.azure.com/astrorama/feedstock-builds/_build/latest?definitionId=7&branchName=master">
                  <img src="https://dev.azure.com/astrorama/feedstock-builds/_apis/build/status/pyston-feedstock?branchName=master&jobName=osx&configuration=osx_64_python3.8.____cpython" alt="variant">
                </a>
              </td>
            </tr><tr>
              <td>osx_64_python3.9.____cpython</td>
              <td>
                <a href="https://dev.azure.com/astrorama/feedstock-builds/_build/latest?definitionId=7&branchName=master">
                  <img src="https://dev.azure.com/astrorama/feedstock-builds/_apis/build/status/pyston-feedstock?branchName=master&jobName=osx&configuration=osx_64_python3.9.____cpython" alt="variant">
                </a>
              </td>
            </tr>
          </tbody>
        </table>
      </details>
    </td>
  </tr>
</table>

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-pyston-green.svg)](https://anaconda.org/astrorama/pyston) | [![Conda Downloads](https://img.shields.io/conda/dn/astrorama/pyston.svg)](https://anaconda.org/astrorama/pyston) | [![Conda Version](https://img.shields.io/conda/vn/astrorama/pyston.svg)](https://anaconda.org/astrorama/pyston) | [![Conda Platforms](https://img.shields.io/conda/pn/astrorama/pyston.svg)](https://anaconda.org/astrorama/pyston) |

Installing pyston
=================

Installing `pyston` from the `astrorama` channel can be achieved by adding `astrorama` to your channels with:

```
conda config --add channels astrorama
conda config --set channel_priority strict
```

Once the `astrorama` channel has been enabled, `pyston` can be installed with:

```
conda install pyston
```

It is possible to list all of the versions of `pyston` available on your platform with:

```
conda search pyston --channel astrorama
```




Updating pyston-feedstock
=========================

If you would like to improve the pyston recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`astrorama` channel, whereupon the built conda packages will be available for
everybody to install and use from the `astrorama` channel.
Note that all branches in the astrorama/pyston-feedstock are
immediately built and any created packages are uploaded, so PRs should be based
on branches in forks and branches in the main repository should only be used to
build distinct package versions.

In order to produce a uniquely identifiable distribution:
 * If the version of a package **is not** being increased, please add or increase
   the [``build/number``](https://docs.conda.io/projects/conda-build/en/latest/resources/define-metadata.html#build-number-and-string).
 * If the version of a package **is** being increased, please remember to return
   the [``build/number``](https://docs.conda.io/projects/conda-build/en/latest/resources/define-metadata.html#build-number-and-string)
   back to 0.

Feedstock Maintainers
=====================


