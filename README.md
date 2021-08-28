About smirnoffee
================

Home: https://github.com/SimonBoothroyd/smirnoffee

Package license: MIT

Feedstock license: [BSD-3-Clause](https://github.com/simonboothroyd/smirnoffee-feedstock/blob/master/LICENSE.txt)

Summary: Differentiably evaluate energies of molecules using SMIRNOFF force fields.

Development: https://github.com/SimonBoothroyd/smirnoffee

Documentation: https://github.com/SimonBoothroyd/smirnoffee

A framework that aims to offer a simple API for differentiably evaluating the energy
of SMIRNOFF force fields applied to single molecules using pytorch.


Current build status
====================


<table><tr><td>All platforms:</td>
    <td>
      <a href="https://dev.azure.com/simonboothroyd/feedstock-builds/_build/latest?definitionId=8&branchName=master">
        <img src="https://dev.azure.com/simonboothroyd/feedstock-builds/_apis/build/status/smirnoffee-feedstock?branchName=master">
      </a>
    </td>
  </tr>
</table>

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-smirnoffee-green.svg)](https://anaconda.org/simonboothroyd/smirnoffee) | [![Conda Downloads](https://img.shields.io/conda/dn/simonboothroyd/smirnoffee.svg)](https://anaconda.org/simonboothroyd/smirnoffee) | [![Conda Version](https://img.shields.io/conda/vn/simonboothroyd/smirnoffee.svg)](https://anaconda.org/simonboothroyd/smirnoffee) | [![Conda Platforms](https://img.shields.io/conda/pn/simonboothroyd/smirnoffee.svg)](https://anaconda.org/simonboothroyd/smirnoffee) |

Installing smirnoffee
=====================

Installing `smirnoffee` from the `simonboothroyd` channel can be achieved by adding `simonboothroyd` to your channels with:

```
conda config --add channels simonboothroyd
conda config --set channel_priority strict
```

Once the `simonboothroyd` channel has been enabled, `smirnoffee` can be installed with:

```
conda install smirnoffee
```

It is possible to list all of the versions of `smirnoffee` available on your platform with:

```
conda search smirnoffee --channel simonboothroyd
```




Updating smirnoffee-feedstock
=============================

If you would like to improve the smirnoffee recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`simonboothroyd` channel, whereupon the built conda packages will be available for
everybody to install and use from the `simonboothroyd` channel.
Note that all branches in the simonboothroyd/smirnoffee-feedstock are
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

* [@simonboothroyd](https://github.com/simonboothroyd/)

