About r-easydescribe-feedstock
==============================

Feedstock license: [BSD-3-Clause](https://github.com/conda-forge/r-easydescribe-feedstock/blob/main/LICENSE.txt)

Home: https://CRAN.R-project.org/package=EasyDescribe

Package license: GPL-3.0-only

Summary: Descriptive Statistics is essential for publishing articles. This package can perform descriptive statistics according to different data types. If the data is a continuous variable, the mean and standard deviation or median and quartiles are automatically output; if the data is a categorical variable, the number and percentage are automatically output. In addition, if you enter two variables, the first variable will be described hierarchically based on the second variable and the statistical differences between different groups will be compared using appropriate statistical methods. And for groups more than two, the post hoc test will be applied. For more information on the methods we used, please see the following references: Libiseller, C. and Grimvall, A. (2002) <doi:10.1002/env.507>, Patefield, W. M. (1981) <doi:10.2307/2346669>, Hope, A. C. A. (1968) <doi:10.1111/J.2517-6161.1968.TB00759.X>, Mehta, C. R. and Patel, N. R. (1983) <doi:10.1080/01621459.1983.10477989>, Mehta, C. R. and Patel, N. R. (1986) <doi:10.1145/6497.214326>, Clarkson, D. B., Fan, Y. and Joe, H. (1993) <doi:10.1145/168173.168412>, Cochran, W. G. (1954) <doi:10.2307/3001616>, Armitage, P. (1955) <doi:10.2307/3001775>, Szabo, A. (2016) <doi:10.1080/00031305.2017.1407823>, David, F. B. (1972) <doi:10.1080/01621459.1972.10481279>, Joanes, D. N. and Gill, C. A. (1998) <doi:10.1111/1467-9884.00122>, Dunn, O. J. (1964) <doi:10.1080/00401706.1964.10490181>, Copenhaver, M. D. and Holland, B. S. (1988) <doi:10.1080/00949658808811082>, Chambers, J. M., Freeny, A. and Heiberger, R. M. (1992) <doi:10.1201/9780203738535-5>, Shaffer, J. P. (1995) <doi:10.1146/annurev.ps.46.020195.003021>, Myles, H. and Douglas, A. W. (1973) <doi:10.2307/2063815>, Rahman, M. and Tiwari, R. (2012) <doi:10.4236/health.2012.410139>. Thode, H. J. (2002) <doi:10.1201/9780203910894>.

Current build status
====================


<table><tr><td>All platforms:</td>
    <td>
      <a href="https://dev.azure.com/conda-forge/feedstock-builds/_build/latest?definitionId=16199&branchName=main">
        <img src="https://dev.azure.com/conda-forge/feedstock-builds/_apis/build/status/r-easydescribe-feedstock?branchName=main">
      </a>
    </td>
  </tr>
</table>

Current release info
====================

| Name | Downloads | Version | Platforms |
| --- | --- | --- | --- |
| [![Conda Recipe](https://img.shields.io/badge/recipe-r--easydescribe-green.svg)](https://anaconda.org/conda-forge/r-easydescribe) | [![Conda Downloads](https://img.shields.io/conda/dn/conda-forge/r-easydescribe.svg)](https://anaconda.org/conda-forge/r-easydescribe) | [![Conda Version](https://img.shields.io/conda/vn/conda-forge/r-easydescribe.svg)](https://anaconda.org/conda-forge/r-easydescribe) | [![Conda Platforms](https://img.shields.io/conda/pn/conda-forge/r-easydescribe.svg)](https://anaconda.org/conda-forge/r-easydescribe) |

Installing r-easydescribe
=========================

Installing `r-easydescribe` from the `conda-forge` channel can be achieved by adding `conda-forge` to your channels with:

```
conda config --add channels conda-forge
conda config --set channel_priority strict
```

Once the `conda-forge` channel has been enabled, `r-easydescribe` can be installed with `conda`:

```
conda install r-easydescribe
```

or with `mamba`:

```
mamba install r-easydescribe
```

It is possible to list all of the versions of `r-easydescribe` available on your platform with `conda`:

```
conda search r-easydescribe --channel conda-forge
```

or with `mamba`:

```
mamba search r-easydescribe --channel conda-forge
```

Alternatively, `mamba repoquery` may provide more information:

```
# Search all versions available on your platform:
mamba repoquery search r-easydescribe --channel conda-forge

# List packages depending on `r-easydescribe`:
mamba repoquery whoneeds r-easydescribe --channel conda-forge

# List dependencies of `r-easydescribe`:
mamba repoquery depends r-easydescribe --channel conda-forge
```


About conda-forge
=================

[![Powered by
NumFOCUS](https://img.shields.io/badge/powered%20by-NumFOCUS-orange.svg?style=flat&colorA=E1523D&colorB=007D8A)](https://numfocus.org)

conda-forge is a community-led conda channel of installable packages.
In order to provide high-quality builds, the process has been automated into the
conda-forge GitHub organization. The conda-forge organization contains one repository
for each of the installable packages. Such a repository is known as a *feedstock*.

A feedstock is made up of a conda recipe (the instructions on what and how to build
the package) and the necessary configurations for automatic building using freely
available continuous integration services. Thanks to the awesome service provided by
[Azure](https://azure.microsoft.com/en-us/services/devops/), [GitHub](https://github.com/),
[CircleCI](https://circleci.com/), [AppVeyor](https://www.appveyor.com/),
[Drone](https://cloud.drone.io/welcome), and [TravisCI](https://travis-ci.com/)
it is possible to build and upload installable packages to the
[conda-forge](https://anaconda.org/conda-forge) [anaconda.org](https://anaconda.org/)
channel for Linux, Windows and OSX respectively.

To manage the continuous integration and simplify feedstock maintenance
[conda-smithy](https://github.com/conda-forge/conda-smithy) has been developed.
Using the ``conda-forge.yml`` within this repository, it is possible to re-render all of
this feedstock's supporting files (e.g. the CI configuration files) with ``conda smithy rerender``.

For more information please check the [conda-forge documentation](https://conda-forge.org/docs/).

Terminology
===========

**feedstock** - the conda recipe (raw material), supporting scripts and CI configuration.

**conda-smithy** - the tool which helps orchestrate the feedstock.
                   Its primary use is in the construction of the CI ``.yml`` files
                   and simplify the management of *many* feedstocks.

**conda-forge** - the place where the feedstock and smithy live and work to
                  produce the finished article (built conda distributions)


Updating r-easydescribe-feedstock
=================================

If you would like to improve the r-easydescribe recipe or build a new
package version, please fork this repository and submit a PR. Upon submission,
your changes will be run on the appropriate platforms to give the reviewer an
opportunity to confirm that the changes result in a successful build. Once
merged, the recipe will be re-built and uploaded automatically to the
`conda-forge` channel, whereupon the built conda packages will be available for
everybody to install and use from the `conda-forge` channel.
Note that all branches in the conda-forge/r-easydescribe-feedstock are
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

* [@conda-forge/r](https://github.com/orgs/conda-forge/teams/r/)

