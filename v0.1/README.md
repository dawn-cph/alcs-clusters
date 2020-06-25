
# HST + IRAC v0.1

# Contents of this Release

## Images

HST images automatically processed by the [Grizli](https://github.com/gbrammer/grizli)/CHArGE pipeline....

IRAC with [golfir](https://github.com/gbrammer/golfir)....

-science and weight images

## Source Detection
TBD

## Photometry
TBD

### HST

### IRAC

-residuals

## General Information

``fields/``

	directory with all the alcs fields

``fields/clu+par``

	HFF cluster and parallel field photomtry (only for 4 clusters)

-folder naming convention

        ``{cluster name}_{CHArGE id}``

## Data Products

[Fields](./fields.md) summary.

### Main photometric catalog

``{CHArGE id}_irac_phot_apcorr.fits``: [Columns](./phot_apcorr_columns.md)

### ``eazy-py`` output

``{CHArGE id}_irac.eazypy.zout.fits``: [Columns](./zout_columns.md)

### Combined catalog

``cat_combined.fits``

# Methodology

## Source Detection

Extraction of IRAC sources was performed by using finely aligned HST f160w and IRAC images. We model IRAC fluxes based on the H-band prior positions and fluxes with [golfir](https://github.com/gbrammer/golfir). We mask all objects <15 mag and set a s/n=30 threshold for masked pixels of bright objects. We additionally refit all sources brighter than 20 uJy with galfit.


## Photometric Redshifts

Photometric Redshift is computed using [EAZY](https://github.com/gbrammer/eazy-py) with the default template library. We provide the best fit photometric redshift for each object,
as well as the corresponding Chi2.


Scripts for both photometry and the photometric redshifts (photoz) are available within the [scripts](./scripts) folder.

.

Tests
=====

A document containing test for Abell 2744 photometry and its comparison to the Shipley et al. (2018) and the Astrodeep catalogue (Merlin et al.  2016, Castellano et al.  2016) is available in the reposittory.

Known Issues
============

In the comparison with Shipley et al. (2018), we find that the H-band magnitudes and IRAC colours show good agreements,while there exists a 0.3 mag offset in the IRAC band.  However in the comparison with Astrodeep catalogue, the offset is reduced significantly, which can by explained by scatter.  Currently, it is hard to conclude which catalogu evalues are the most reliable.  We thus do not apply any corrections to our v0.1 catalogue related to this offset.

