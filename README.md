About dargs
===========

Home: https://github.com/deepmodeling/dargs

Package license: LGPL-3.0

Feedstock license: [BSD-3-Clause](https://github.com/deepmd-kit-recipes/dargs-feedstock/blob/master/LICENSE.txt)

Summary: 

Development: https://github.com/deepmodeling/dargs

Documentation: https://github.com/deepmodeling/dargs

Current build status
====================


<table><tr><td>All platforms:</td>
    <td>
      <a href="https://dev.azure.com/deepmd-kit-recipes/feedstock-builds/_build/latest?definitionId=&branchName=master">
        <img src="https://dev.azure.com/deepmd-kit-recipes/feedstock-builds/_apis/build/status/dargs-feedstock?branchName=master">
      </a>
    </td>
  </tr>
</table>

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-dargs-green.svg)](https://anaconda.org/deepmodeling/dargs) | [![Conda Downloads](https://img.shields.io/conda/dn/deepmodeling/dargs.svg)](https://anaconda.org/deepmodeling/dargs) | [![Conda Version](https://img.shields.io/conda/vn/deepmodeling/dargs.svg)](https://anaconda.org/deepmodeling/dargs) | [![Conda Platforms](https://img.shields.io/conda/pn/deepmodeling/dargs.svg)](https://anaconda.org/deepmodeling/dargs) |

Installing dargs
================

Installing `dargs` from the `deepmodeling` channel can be achieved by adding `deepmodeling` to your channels with:

```
conda config --add channels deepmodeling
conda config --set channel_priority strict
```

Once the `deepmodeling` channel has been enabled, `dargs` can be installed with:

```
conda install dargs
```

It is possible to list all of the versions of `dargs` available on your platform with:

```
conda search dargs --channel deepmodeling
```




Updating dargs-feedstock
========================

If you would like to improve the dargs recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`deepmodeling` channel, whereupon the built conda packages will be available for
everybody to install and use from the `deepmodeling` channel.
Note that all branches in the deepmd-kit-recipes/dargs-feedstock are
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

* [@njzjz](https://github.com/njzjz/)

