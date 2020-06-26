
# HST + IRAC v0.1

# Contents of this Release

A summary of the HST and IRAC data products provided by this release is given below.  

A few identified issues with the v0.1 release as provided are listed in the
GitHub [issues](https://github.com/dawn-cph/alcs-clusters/issues) page.
**Please log any additional issues you find there so that they can be logged and addressed efficiently.**


## Hubble optical and near-IR images

The HST mosaics are all available on the individual CHArGE summary pages, for
example
[hff-j001408m3023.summary.html](https://s3.amazonaws.com/grizli-v1/Pipeline/hff-j001408m3023/Prep/hff-j001408m3023.summary.html).
 
These include files like the following, with additional files for all of the separate HST filters as listed on the page.

| File       |    Description  |
| -------    |    -----------  |
| [``hff-j001408m3023-ir_drz_sci.fits.gz``](https://s3.amazonaws.com/grizli-v1/Pipeline/hff-j001408m3023/Prep/hff-j001408m3023-ir_drz_sci.fits.gz)  |  Detection image combined from WFC3/IR images  |
| [``hff-j001408m3023-ir_drz_wht.fits.gz``](https://s3.amazonaws.com/grizli-v1/Pipeline/hff-j001408m3023/Prep/hff-j001408m3023-ir_drz_wht.fits.gz)  |  Detection image, inverse variance             |
| [``hff-j001408m3023-ir_seg.fits.gz``](https://s3.amazonaws.com/grizli-v1/Pipeline/hff-j001408m3023/Prep/hff-j001408m3023-ir_seg.fits.gz)          |  Segmentation map associated with the photometric catalog                              |
| [``hff-j001408m3023-f160w_drz_sci.fits.gz``](https://s3.amazonaws.com/grizli-v1/Pipeline/hff-j001408m3023/Prep/hff-j001408m3023-f160w_drz_sci.fits.gz)  |  F160W science image                     |
| [``hff-j001408m3023-f160w_drz_wht.fits.gz``](https://s3.amazonaws.com/grizli-v1/Pipeline/hff-j001408m3023/Prep/hff-j001408m3023-f160w_drz_sci.fits.gz)  |  F160W inverse variance                 |
| [``hff-j001408m3023-f814w_drc_sci.fits.gz``](https://s3.amazonaws.com/grizli-v1/Pipeline/hff-j001408m3023/Prep/hff-j001408m3023-f814w_drc_sci.fits.gz)  |  F814W science image                    |
| [``hff-j001408m3023-f814w_drc_wht.fits.gz``](https://s3.amazonaws.com/grizli-v1/Pipeline/hff-j001408m3023/Prep/hff-j001408m3023-f814w_drc_wht.fits.gz)  |  F814W inverse variance                 |


## Spitzer IRAC images and photometric catalogs

The IRAC products are listed on pages like
[``hff-j001408m3023/Photometry/index.html``](https://s3.amazonaws.com/grizli-v1/Pipeline/hff-j001408m3023/Photometry/index.html).

Note that a full list of all of the IRAC products can be found at
[all_files.v0.1.txt](./all_files.v0.1.txt), suitable for automatic retrieval
with ``curl`` or ``wget``.

| File       |    Description  |
| -------    |    -----------  |
| [``j001408m3023-ch1_drz_sci.fits``          ](https://s3.amazonaws.com/grizli-v1/Pipeline/hff-j001408m3023/Photometry/j001408m3023-ch1_drz_sci.fits       ) | IRAC ch1 science mosaic |
| [``j001408m3023-ch1_drz_wht.fits``          ](https://s3.amazonaws.com/grizli-v1/Pipeline/hff-j001408m3023/Photometry/j001408m3023-ch1_drz_wht.fits       ) | IRAC ch1 inverse variance |
| [``j001408m3023-ch1_model.fits``            ](https://s3.amazonaws.com/grizli-v1/Pipeline/hff-j001408m3023/Photometry/j001408m3023-ch1_model.fits         ) | IRAC ch1 model image |
| [``j001408m3023_ch1_residual.fits``         ](https://s3.amazonaws.com/grizli-v1/Pipeline/hff-j001408m3023/Photometry/j001408m3023_ch1_residual.fits      ) | IRAC ch1 model residual |
| [``j001408m3023-ch2_drz_sci.fits``          ](https://s3.amazonaws.com/grizli-v1/Pipeline/hff-j001408m3023/Photometry/j001408m3023-ch2_drz_sci.fits       ) | IRAC ch2 science mosaic |
| [``j001408m3023-ch2_drz_wht.fits``          ](https://s3.amazonaws.com/grizli-v1/Pipeline/hff-j001408m3023/Photometry/j001408m3023-ch2_drz_wht.fits       ) | IRAC ch2 inverse variance |
| [``j001408m3023-ch2_model.fits``            ](https://s3.amazonaws.com/grizli-v1/Pipeline/hff-j001408m3023/Photometry/j001408m3023-ch2_model.fits         ) | IRAC ch2 model image |
| [``j001408m3023_ch2_residual.fits``         ](https://s3.amazonaws.com/grizli-v1/Pipeline/hff-j001408m3023/Photometry/j001408m3023_ch2_residual.fits      ) | IRAC ch2 model residual |
| [``j001408m3023_phot.fits``                 ](https://s3.amazonaws.com/grizli-v1/Pipeline/hff-j001408m3023/Photometry/j001408m3023_phot.fits              ) | HST matched-aperture catalog |
| [``j001408m3023_irac_phot.fits``            ](https://s3.amazonaws.com/grizli-v1/Pipeline/hff-j001408m3023/Photometry/j001408m3023_irac_phot.fits         ) | "" with IRAC model photometry |
| [``j001408m3023_irac_phot_apcorr.fits``     ](https://s3.amazonaws.com/grizli-v1/Pipeline/hff-j001408m3023/Photometry/j001408m3023_irac_phot_apcorr.fits  ) | "" and aperture corrections (**use this**).  [Column description](./phot_apcorr_columns.md). |
| [``j001408m3023_irac.eazypy.zout.fits``     ](https://s3.amazonaws.com/grizli-v1/Pipeline/hff-j001408m3023/Photometry/j001408m3023_irac.eazypy.zout.fits  ) | Photometric redshifts and population parameters.  [Column description](./zout_columns.md). |

## Survey Fields

We have processed all 33 ALCS cluster fields, summarized [here](./fields.md).
The fields are generally named based on the rough coordinate center following
the CHArGE convention, e.g., ``j001408m3023`` for Abell 2744 products shown above.

# Methodology

Full description here TBD.

## Image Mosaics

### HST

All WFC3/IR mosaics are created with 0.1" pixels, while the ACS and UVIS
optical/UV images are drizzled to 2x2 subsampled 0.05" grid.

### IRAC

The script that was used to process the archival data and create the mosaics
can be found in the scripts folder [here](./scripts/alcs_mosaic.ipynb)

## Source Detection

## Photometry

### HST

### IRAC

Extraction of IRAC sources was performed by using finely aligned HST f160w and
IRAC images. We model IRAC fluxes based on the H-band prior positions and
fluxes with [golfir](https://github.com/gbrammer/golfir). We mask all objects
<15 mag and set a ``S/N=30`` threshold for masked pixels of bright objects. We
additionally refit all sources brighter than 20 uJy with galfit.

#### IRAC PSF

## Photometric Redshifts

Photometric Redshift is computed using
[EAZY](https://github.com/gbrammer/eazy-py) with the default template library.
We provide the best fit photometric redshift for each object, as well as the
corresponding Chi2.

Scripts for both photometry and the photometric redshifts (photoz) are
available within the [scripts](./scripts/alcs_photometry.ipynb) folder.

# Catalog Verification

A [document](./test_report.pdf) containing test for Abell 2744 photometry and its comparison to the
[Shipley et al. (2018)](https://ui.adsabs.harvard.edu/abs/2018ApJS..235...14S)
/ [[HFFDS]](http://cosmos.phy.tufts.edu/~danilo/HFF/Home.html) and the
Astrodeep ([Merlin et al.
2016](https://ui.adsabs.harvard.edu/abs/2016A%26A...590A..30M), [Castellano et
al. 2016](https://ui.adsabs.harvard.edu/abs/2016A%26A...590A..31C)) catalogues is
available in this repository.



