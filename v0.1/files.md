
# HST + IRAC v0.1

# Contents of this Release

## Fields

We have processed all 33 ALCS cluster fields, summarized [here](./fields.md).
The fields are generally named based on the rough coordinate center following
the CHArGE convention, e.g., ``j001408m3023`` for Abell 2744.

## Hubble optical and near-IR images

The HST mosaics are all available on the individual CHArGE summary pages, for
example
[hff-j001408m3023](https://s3.amazonaws.com/grizli-v1/Pipeline/hff-j001408m3023/Prep/hff-j001408m3023.summary.html).
All WFC3/IR mosaics are created with 0.1" pixels, while the ACS and UVIS
optical/UV images are drizzled to 2x2 subsampled 0.05" grid.
 
These include files like the following, with additional files for all of the separate HST filters as listed on the page.

| File       |    Description  |
| -------    |    -----------  |
| [``hff-j001408m3023-ir_drz_sci.fits.gz``](https://s3.amazonaws.com/grizli-v1/Pipeline/hff-j001408m3023/Prep/hff-j001408m3023-ir_drz_sci.fits.gz)  |  Detection image combined from WFC3/IR images  |
| [``hff-j001408m3023-ir_drz_wht.fits.gz``](https://s3.amazonaws.com/grizli-v1/Pipeline/hff-j001408m3023/Prep/hff-j001408m3023-ir_drz_wht.fits.gz)  |  Detection image, inverse variance             |
| [``hff-j001408m3023-ir_seg.fits.gz``](https://s3.amazonaws.com/grizli-v1/Pipeline/hff-j001408m3023/Prep/hff-j001408m3023-ir_seg.fits.gz)          |  Segmentation map                              |
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
| [``j001408m3023_irac_phot_apcorr.fits``     ](https://s3.amazonaws.com/grizli-v1/Pipeline/hff-j001408m3023/Photometry/j001408m3023_irac_phot_apcorr.fits  ) | "" and aperture corrections (**use this**) |
| [``j001408m3023_irac.eazypy.zout.fits``     ](https://s3.amazonaws.com/grizli-v1/Pipeline/hff-j001408m3023/Photometry/j001408m3023_irac.eazypy.zout.fits  ) | Photometric redshifts and population parameters |
