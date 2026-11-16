# BBMM 3.0.9001

Renova release, based on CRAN BBMM 3.0 (archived on CRAN 2022-05-23).

- `NAMESPACE`: `importFrom()` directives added for `graphics` (`contour`, `lines`, `points`) and `stats` (`na.omit`, `optimize`, `sd`).
- No DESCRIPTION, R code or documentation changes in the accepted repair.

Release preparation:

- `DESCRIPTION`: `Version` set to `3.0.9001`; "Compatibility updates by Renova." appended to `Description`.
- The stale `MD5` file was removed.
- `COPYING` (GNU GPL version 2 text, as a reference copy for the unversioned GNU General Public License) was added; the `License` field is unchanged.
- `README.md` was added and is excluded from the R build.
- `NEWS.md` was added and is excluded from the R build.

Original author credits: Nielson, R. M., H. Sawyer, and T. L. McDonald (WEST, Inc., www.west-inc.com)

Author metadata is formatted consistently with Authors@R; original authors and maintainer roles are retained.

### Metadata compatibility

Added structured author metadata, capitalized the title, and removed the historical optional Date field.
