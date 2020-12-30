About eman-deps-dev
===================

Home: 

Package license: 

Feedstock license: [BSD-3-Clause](https://github.com/cryoem/eman-deps-feedstock/blob/master/LICENSE.txt)

Summary: Meta-package for eman2 dependencies

Current build status
====================


<table><tr>
    <td>CircleCI</td>
    <td>
      <a href="https://circleci.com/gh/cryoem/eman-deps-feedstock">
        <img alt="Linux,osx_arm64" src="https://img.shields.io/circleci/project/github/cryoem/eman-deps-feedstock/master.svg?label=Linux,osx_arm64">
      </a>
    </td>
  </tr><tr>
    <td>Travis</td>
    <td>
      <a href="https://travis-ci.com/cryoem/eman-deps-feedstock">
        <img alt="macOS" src="https://img.shields.io/travis/com/cryoem/eman-deps-feedstock/master.svg?label=macOS">
      </a>
    </td>
  </tr><tr>
    <td>Appveyor</td>
    <td>
      <a href="https://ci.appveyor.com/project/cryoem/eman-deps-feedstock/branch/master">
        <img alt="windows" src="https://img.shields.io/appveyor/ci/cryoem/eman-deps-feedstock/master.svg?label=Windows">
      </a>
    </td>
  </tr>
</table>

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-eman--deps-green.svg)](https://anaconda.org/cryoem/eman-deps) | [![Conda Downloads](https://img.shields.io/conda/dn/cryoem/eman-deps.svg)](https://anaconda.org/cryoem/eman-deps) | [![Conda Version](https://img.shields.io/conda/vn/cryoem/eman-deps.svg)](https://anaconda.org/cryoem/eman-deps) | [![Conda Platforms](https://img.shields.io/conda/pn/cryoem/eman-deps.svg)](https://anaconda.org/cryoem/eman-deps) |
| [![Conda Recipe](https://img.shields.io/badge/recipe-eman--deps--cli-green.svg)](https://anaconda.org/cryoem/eman-deps-cli) | [![Conda Downloads](https://img.shields.io/conda/dn/cryoem/eman-deps-cli.svg)](https://anaconda.org/cryoem/eman-deps-cli) | [![Conda Version](https://img.shields.io/conda/vn/cryoem/eman-deps-cli.svg)](https://anaconda.org/cryoem/eman-deps-cli) | [![Conda Platforms](https://img.shields.io/conda/pn/cryoem/eman-deps-cli.svg)](https://anaconda.org/cryoem/eman-deps-cli) |
| [![Conda Recipe](https://img.shields.io/badge/recipe-eman--deps--cxx-green.svg)](https://anaconda.org/cryoem/eman-deps-cxx) | [![Conda Downloads](https://img.shields.io/conda/dn/cryoem/eman-deps-cxx.svg)](https://anaconda.org/cryoem/eman-deps-cxx) | [![Conda Version](https://img.shields.io/conda/vn/cryoem/eman-deps-cxx.svg)](https://anaconda.org/cryoem/eman-deps-cxx) | [![Conda Platforms](https://img.shields.io/conda/pn/cryoem/eman-deps-cxx.svg)](https://anaconda.org/cryoem/eman-deps-cxx) |

Installing eman-deps-dev
========================

Installing `eman-deps-dev` from the `cryoem` channel can be achieved by adding `cryoem` to your channels with:

```
conda config --add channels cryoem
```

Once the `cryoem` channel has been enabled, `eman-deps, eman-deps-cli, eman-deps-cxx` can be installed with:

```
conda install eman-deps eman-deps-cli eman-deps-cxx
```

It is possible to list all of the versions of `eman-deps` available on your platform with:

```
conda search eman-deps --channel cryoem
```




Updating eman-deps-dev-feedstock
================================

If you would like to improve the eman-deps-dev recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`cryoem` channel, whereupon the built conda packages will be available for
everybody to install and use from the `cryoem` channel.
Note that all branches in the cryoem/eman-deps-dev-feedstock are
immediately built and any created packages are uploaded, so PRs should be based
on branches in forks and branches in the main repository should only be used to
build distinct package versions.

In order to produce a uniquely identifiable distribution:
 * If the version of a package **is not** being increased, please add or increase
   the [``build/number``](https://conda.io/docs/user-guide/tasks/build-packages/define-metadata.html#build-number-and-string).
 * If the version of a package **is** being increased, please remember to return
   the [``build/number``](https://conda.io/docs/user-guide/tasks/build-packages/define-metadata.html#build-number-and-string)
   back to 0.

Feedstock Maintainers
=====================


