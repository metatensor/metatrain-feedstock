About metatrain-feedstock
=========================

Feedstock license: [BSD-3-Clause](https://github.com/metatensor/metatrain-feedstock/blob/main/LICENSE.txt)

Home: https://github.com/metatensor/metatrain

Package license: BSD-3-Clause

Summary: Training and evaluating machine learning models for atomistic systems.

Documentation: https://metatensor.github.io/metatrain

Current build status
====================


<table><tr>
    <td>All platforms:</td>
    <td>
      <img src="https://img.shields.io/badge/noarch-disabled-lightgrey.svg" alt="noarch disabled">
    </td>
  </tr>
</table>

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-metatrain-green.svg)](https://anaconda.org/metatensor/metatrain) | [![Conda Downloads](https://img.shields.io/conda/dn/metatensor/metatrain.svg)](https://anaconda.org/metatensor/metatrain) | [![Conda Version](https://img.shields.io/conda/vn/metatensor/metatrain.svg)](https://anaconda.org/metatensor/metatrain) | [![Conda Platforms](https://img.shields.io/conda/pn/metatensor/metatrain.svg)](https://anaconda.org/metatensor/metatrain) |

Installing metatrain
====================

Installing `metatrain` from the `metatensor` channel can be achieved by adding `metatensor` to your channels with:

```
conda config --add channels metatensor
conda config --set channel_priority strict
```

Once the `metatensor` channel has been enabled, `metatrain` can be installed with `conda`:

```
conda install metatrain
```

or with `mamba`:

```
mamba install metatrain
```

It is possible to list all of the versions of `metatrain` available on your platform with `conda`:

```
conda search metatrain --channel metatensor
```

or with `mamba`:

```
mamba search metatrain --channel metatensor
```

Alternatively, `mamba repoquery` may provide more information:

```
# Search all versions available on your platform:
mamba repoquery search metatrain --channel metatensor

# List packages depending on `metatrain`:
mamba repoquery whoneeds metatrain --channel metatensor

# List dependencies of `metatrain`:
mamba repoquery depends metatrain --channel metatensor
```




Updating metatrain-feedstock
============================

If you would like to improve the metatrain recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`metatensor` channel, whereupon the built conda packages will be available for
everybody to install and use from the `metatensor` channel.
Note that all branches in the metatensor/metatrain-feedstock are
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

* [@Luthaf](https://github.com/Luthaf/)

