About pillow-feedstock
======================

Feedstock license: [BSD-3-Clause](https://github.com/conda-forge/pillow-feedstock/blob/main/LICENSE.txt)

Home: https://pillow.readthedocs.io

Package license: LicenseRef-PIL

Summary: Pillow is the friendly PIL fork by Alex Clark and Contributors

Development: https://github.com/python-pillow/Pillow/

Current build status
====================


<table>
</table>

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-pillow-green.svg)](https://anaconda.org/freecad/pillow) | [![Conda Downloads](https://img.shields.io/conda/dn/freecad/pillow.svg)](https://anaconda.org/freecad/pillow) | [![Conda Version](https://img.shields.io/conda/vn/freecad/pillow.svg)](https://anaconda.org/freecad/pillow) | [![Conda Platforms](https://img.shields.io/conda/pn/freecad/pillow.svg)](https://anaconda.org/freecad/pillow) |

Installing pillow
=================

Installing `pillow` from the `freecad/label/dev` channel can be achieved by adding `freecad/label/dev` to your channels with:

```
conda config --add channels freecad/label/dev
conda config --set channel_priority strict
```

Once the `freecad/label/dev` channel has been enabled, `pillow` can be installed with `conda`:

```
conda install pillow
```

or with `mamba`:

```
mamba install pillow
```

It is possible to list all of the versions of `pillow` available on your platform with `conda`:

```
conda search pillow --channel freecad/label/dev
```

or with `mamba`:

```
mamba search pillow --channel freecad/label/dev
```

Alternatively, `mamba repoquery` may provide more information:

```
# Search all versions available on your platform:
mamba repoquery search pillow --channel freecad/label/dev

# List packages depending on `pillow`:
mamba repoquery whoneeds pillow --channel freecad/label/dev

# List dependencies of `pillow`:
mamba repoquery depends pillow --channel freecad/label/dev
```




Updating pillow-feedstock
=========================

If you would like to improve the pillow recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`freecad` channel, whereupon the built conda packages will be available for
everybody to install and use from the `freecad` channel.
Note that all branches in the conda-forge/pillow-feedstock are
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

* [@h-vetinari](https://github.com/h-vetinari/)
* [@jakirkham](https://github.com/jakirkham/)
* [@ocefpaf](https://github.com/ocefpaf/)
* [@patricksnape](https://github.com/patricksnape/)
* [@pelson](https://github.com/pelson/)

