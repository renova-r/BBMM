# BBMM

Brownian bridge movement model: an empirical estimate of a movement path from discrete location data obtained at relatively short time intervals.

Compatibility updates by Renova.

Version 3.0.9001: `NAMESPACE` imports the graphics and stats functions the package calls (`contour`, `lines`, `points`, `na.omit`, `optimize`, `sd`). No other file changed.

## Install

```r
install.packages("BBMM", repos = c(
  Renova = "https://renova-r.r-universe.dev",
  CRAN = "https://cloud.r-project.org"
))
```

See the [R-universe package page](https://renova-r.r-universe.dev/BBMM) for builds and installation. This release is tagged on GitHub as `renova-3.0.9001`:

```r
remotes::install_github("renova-r/BBMM@renova-3.0.9001")
```

[Release notes](NEWS.md) · [Renova package directory](https://github.com/renova-r/revival-catalog)

BBMM is by R. M. Nielson, H. Sawyer and T. L. McDonald (WEST, Inc.); Ryan Nielson is the maintainer; the original CRAN package is at <https://CRAN.R-project.org/package=BBMM>. License: GNU General Public License; no version is specified; [COPYING](COPYING) holds the GNU GPL version 2 text for reference.

Original author credits: Nielson, R. M., H. Sawyer, and T. L. McDonald (WEST, Inc., www.west-inc.com)

Author metadata is formatted consistently with Authors@R; original authors and maintainer roles are retained.

### Metadata compatibility

Added structured author metadata, capitalized the title, and removed the historical optional Date field.
