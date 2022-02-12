
# HST + IRAC v1.0

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
| [``j001408m3023_ch1_components.fits``         ](https://s3.amazonaws.com/grizli-v1/Pipeline/hff-j001408m3023/Photometry/j001408m3023_ch1_components.fits      ) | IRAC ch1 model components |
| [``j001408m3023_ch1_residual.fits``         ](https://s3.amazonaws.com/grizli-v1/Pipeline/hff-j001408m3023/Photometry/j001408m3023_ch1_residual.fits      ) | IRAC ch1 model residual |
| [``j001408m3023-ch2_drz_sci.fits``          ](https://s3.amazonaws.com/grizli-v1/Pipeline/hff-j001408m3023/Photometry/j001408m3023-ch2_drz_sci.fits       ) | IRAC ch2 science mosaic |
| [``j001408m3023-ch2_drz_wht.fits``          ](https://s3.amazonaws.com/grizli-v1/Pipeline/hff-j001408m3023/Photometry/j001408m3023-ch2_drz_wht.fits       ) | IRAC ch2 inverse variance |
| [``j001408m3023-ch2_model.fits``            ](https://s3.amazonaws.com/grizli-v1/Pipeline/hff-j001408m3023/Photometry/j001408m3023-ch2_model.fits         ) | IRAC ch2 model image |
| [``j001408m3023_ch2_components.fits``         ](https://s3.amazonaws.com/grizli-v1/Pipeline/hff-j001408m3023/Photometry/j001408m3023_ch2_components.fits      ) | IRAC ch2 model components |
| [``j001408m3023_ch2_residual.fits``         ](https://s3.amazonaws.com/grizli-v1/Pipeline/hff-j001408m3023/Photometry/j001408m3023_ch2_residual.fits      ) | IRAC ch2 model residual |
| ``r[AOR]-ch[12].log.fits``      | Exposure information for IRAC AORs used to generate PSFs |
| [``j001408m3023_phot.fits``                 ](https://s3.amazonaws.com/grizli-v1/Pipeline/hff-j001408m3023/Photometry/j001408m3023_phot.fits              ) | HST matched-aperture catalog |
| [``j001408m3023_irac_phot.fits``            ](https://s3.amazonaws.com/grizli-v1/Pipeline/hff-j001408m3023/Photometry/j001408m3023_irac_phot.fits         ) | "" with IRAC model photometry |
| [``j001408m3023_irac_phot_apcorr.fits``     ](https://s3.amazonaws.com/grizli-v1/Pipeline/hff-j001408m3023/Photometry/j001408m3023_irac_phot_apcorr.fits  ) | "" and aperture corrections (**use this**).  [Column description](./phot_apcorr_columns.md). |
| [``j001408m3023_irac.eazypy.zout.fits``     ](https://s3.amazonaws.com/grizli-v1/Pipeline/hff-j001408m3023/Photometry/j001408m3023_irac.eazypy.zout.fits  ) | Photometric redshifts and population parameters.  [Column description](./zout_columns.md). |

## Survey Fields

We have processed all 33 ALCS cluster fields, summarized [here](./fields.md).
The fields are generally named based on the rough coordinate center following
the CHArGE convention, e.g., ``j001408m3023`` for Abell 2744 products shown above.

# Methodology

## Image Mosaics

### HST

All HST data are processed with the ``grizli`` pipeline, which creates filter mosaics for all ACS, WFC3/UVIS and WFC3/IR exposures that cover a given area of the sky (e.g., an ALCS field).  The methodology is essentially as described in the ``grizli`` [demonstration notebook](https://github.com/gbrammer/grizli/blob/master/examples/Grizli-Pipeline.ipynb).

1. **"Visits"**

The overlapping exposures are broken into discrete ``visit`` associations, similar to the definition as in the APT Phase II file, but more generally grouping exposures in a given filter that were taken in a single target acquisition.  These associations generally share the same spacecraft orient and (zodi) sky background.

2. **Astrometric alignment**

- All exposures in a ``visit`` are aligned to each other using high S/N sources detected in them, allowing ``x`` and ``y`` shifts between them.  These are analogous to DrizzlePac ``TweakShifts`` and are generally a fairly small fraction of a pixel for dither offsets within a single orbit and a few tenths of a pixel between subsequent orbits that share the same initial target acquisition. [example log file](https://s3.amazonaws.com/grizli-v1/Pipeline/j060008m2008/Prep/rxc-j0600.1-2007-czg-k2-224.0-f160w_shifts.log)

- A source catalog is created from a preliminary mosaic generated from the ``visit`` exposures and aligned (shift, rotation, scale) to some user-provided astrometric reference catalog.  Generally this is PanSTARRS DR1 as it is well aligned to the GAIA DR2 but has a higher source density than the bright GAIA stars alone. [example log](https://s3.amazonaws.com/grizli-v1/Pipeline/j060008m2008/Prep/rxc-j0600.1-2007-czg-k2-224.0-f160w_wcs.log)

- A final fine alignment is performed simultaneously optimizing *a)* alignment between all of the individual visit catalogs and *b)* GAIA DR2 stars with proper motions projected to each visit observation epoch.  This ensures robust internal alignment of the HST images for matched-aperture photometry and the final absolute astrometric precision is generally <100 mas. [example diagnostic figure](https://s3.amazonaws.com/grizli-v1/Pipeline/j060008m2008/Prep/j060008m2008_fine.png)

3. **Background subtraction**

- A pedestal sky background of each exposure is estimated in the ``AstroDrizzle`` preparation of each visit association.  

- A smooth background is subtracted from each visit mosaic to remove gradients that can then appear as sharp discontinuities in the final combined filter mosaics.  This background is estimated with the ``sep`` software analogous to ``SourceExtractor`` with ``BACK_FILTERSIZE = 3`` and ``BACK_SIZE = 32 arcsec``.  While the background estimation includes a mask for detected sources, it can include extended structure for very large, bright galaxies and ICL in the ALCS cluster fields.

4. **Final mosaics**

Final rectified mosaics combining all exposures in each available filter are created with ``AstroDrizzle``.  All WFC3/IR mosaics are created with 0.1" pixels, while the ACS and UVIS optical/UV images are drizzled with 0.05" pixels on a grid that subsamples the IR mosaic 2x2.  Both optical and IR mosaics are drizzled with ``pixfrac = 0.33``.  There are ``sci`` (science) and ``wht`` (inverse variance weights) mosaics provided for each filter.

This is not the most aggressive pixel size for trying to reconstruct the undersampled HST PSFs, but the larger pixels ensure more uniform weights across the diversity of dither coverage across the survey fields (e.g., hundreds of exposures for the Frontier Fields but as few as 2–4 exposures for some pre-RELICS filters).  The larger pixels and small ``pixfrac`` result in lower correlated noise between adjacent pixels, and therefore the inverse variance maps are more reliable estimate of the pixel variances for, e.g., aperture photometry.

The units of the filter mosaics are ``electrons / s``, with the photometric calibration to CGS units provided in the ``PHOTFLAM`` (f-lambda) and ``PHOTFNU`` (f-nu) header keywords.

5. **WFC3/IR PSFs**

We provide PSF models for each IR filter using the effective PSF models created by Jay Anderson at STScI ([Anderson & King 2000](https://ui.adsabs.harvard.edu/abs/2000PASP..112.1360A/abstract); https://www.stsci.edu/~jayander/STDPSFs/).

### IRAC

The script that was used to process the archival data and create the mosaics
can be found in the scripts folder [here](./scripts/alcs_mosaic.ipynb).

1. We download all calibrated "BCD" exposures (``pBCD``) from the Spitzer SHA archive for each field.  

2. Similar to HST, we perform relative alignment of all exposures in an IRAC ``AOR`` (analogous to the HST visits) align AOR mosaics to GAIA DR2 (the larger IRAC FoV generally ensures a sufficient number of reference sources for alignment).  

3. The IRAC background is removed by creating a master background image for each AOR with detected sources masked.

4. The final IRAC mosaics are aligned to the HST pixel grid and drizzled with 0.5 arcsecond pixels and ``pixfrac = 0.2``.

5. With full knowledge of the individual ``pBCD`` exposures that contribute at any location in the final mosaic, we can generate robust models of the IRAC PSF that fully account for the diversity of depth and detector position angle across the mosaic.  These position-dependent PSFs are used for the IRAC model-based photometry, and can be re-generated using [``golfir.irac.IracPSF``](https://github.com/gbrammer/golfir/blob/master/golfir/irac.py#L1623).

6. All IRAC mosaics (``{field}-ch[12]_drz_sci.fits``) have units ``microJansky / pixel``.

## Source Detection

For the HST-selected source catalogs, we first create a master detection image from all available *ACS/WFC* and *WFC3/IR*  filters of a given field, where the filters mosaics are weighted by the ``wht`` maps and the ``f-nu`` calibration that therefore favors redder filters for potential z>10 dropouts.

All source detection and aperture photometry is performed with the SourceExtractor clone ``sep``, with the following parameters:

| Parameter | Value | 
| :--------  | :----- |
| ``BACK_FILTERSIZE`` 	|  4 arcsec 	| 
| ``BACK_FILTER``   	|  3 			| 
| ``FILTER`` 			|  Y 			| 
| ``FILTER_NAME`` 		|  matched kernel from F160W PSF [(see Barak & Ofek, 2017)](https://ui.adsabs.harvard.edu/abs/2017ApJ...836..187Z)  |	 
| ``CLEAN``   			|  Y 			| 
| ``DEBLEND_CONT``   	|  0.001 		| 
| ``DEBLEND_NTHRESH``  	|  32 			| 
| ``MINAREA``		   	|  9 			| 
| ``THRESHOLD``		   	|  1.0 			| 

## Photometry

### HST

The [photometric catalog](./phot_apcorr_columns.md) provides a number of diagnostic columns related to the ``sep`` source detection.  

1. **Aperture fluxes**

We extract aperture photometry within (circular) aperture diameters 0.36, 0.5, 0.7, 1.0, 1.2, 1.5, 3.0 arcsec at the positions derived in the source detection as described above. 

**We do not PSF-match any HST filters for the aperture measurements**.  We feel that blindly "PSF-matching" images has serious deleterious effects on the noise properties of the derived photometry, particularly for faint sources/dropouts where there is truly no signal to "match".  We therefore favor the approach here primarily for simplicity and defer tests on the aperture effects to ongoing work.

2. **Aperture corrections**

The "total" HST flux is defined within an elliptical Kron aperture determined by [sep](https://sep.readthedocs.io/en/v1.0.x/apertures.html), as in [SourceExtractor](https://sextractor.readthedocs.io/en/latest/Photom.html#automatic-aperture-flux-flux-auto).  However, we do not impose the lower limit of 3.5 on ``KRON_RADIUS`` typical with SourceExtractor as we find that in fact most derived values are actually lower than this threshold even for bright, well-measured sources.  We do, however, impose a minimum circularized Kron aperture diameter of 0.7 arcsec, which is our favored "color" aperture.  We calculate a correction for flux outside of the Kron aperture using the PSF curves of growth (i.e., explicitly valid only for point sources).  The "color" aperture fluxes are therefore corrected by 1) ``flux_auto`` / ``flux_aper`` in the detection band and then 2) by the Kron aperture correction.


### IRAC

The low resolution IRAC mosaics generally require source-fitting photometry to account for overlapping sources, particularly at the source densities in the deep ALCS cluster fields.  We perform IRAC modelling with a custom code—[``golfir``](https://github.com/gbrammer/golfir)—inspired on earlier efforts like [Labbe et al. (2015)](https://ui.adsabs.harvard.edu/abs/2015ApJS..221...23L) and [T-Phot](http://www.astrodeep.eu/t-phot/) [(Merlin et al.)](https://ui.adsabs.harvard.edu/abs/2015A%26A...582A..15M).  The methodology is as follows:

1. We first break up the mosaics into "patches" for the source modeling.  There is a small overlap between the patches to ensure that all sources are fully contained in at least one patch.

2. We mask all pixels in the IRAC mosaic for objects in the HST catalog brighter than AB=15 to avoid large residuals in the centers of bright stars.

3. First model pass: we generate IRAC model images for objects in the HST catalog brighter than AB=24 convolving the HST source cutouts with a kernel to transform them to the (position-dependent) IRAC PSF.  We fit the normalizations of all of these IRAC cutouts to the mosaic with linear least squares (``numpy.linalg.lstsq``) and derive any small residual shift between the reference HST and target IRAC mosaics using the generated IRAC model and mosaic images.

4. Second model pass: we generate IRAC models as before but now for every object with AB<27.  The least-squares normalization of these images is adopted as the IRAC flux density measurement for each source, and the diagonal of the covariance of the model design matrix is adopted as the photometric variance.

5. We perform an additional fit of sources brighter than 20 uJy with GALFIT using a single Sersic model.  This often significantly improves the IRAC residuals, which is likely a combination of 1) an imperfect transformation between the HST and IRAC PSFs and 2) true morphological differences between F160W and the IRAC bands (i.e., color gradients).  We note that we are not interested in the GALFIT parameters, but rather in the best empirical description of each IRAC morphological component.   We do not adopt the "mag" of the GALFIT fit but rather refit the model normalizations and covariances as in step **4** but now using the GALFIT model cutouts in place of the HST-based models for the sources that have them.

6. As the IRAC fluxes are based on morphological model fits, we consider them to be on the same "total" scale as the aperture-corrected HST photometry.

## Photometric Redshifts

Photometric Redshift is computed using
[EAZY](https://github.com/gbrammer/eazy-py) with the default template library and using the ``D=0.7"`` HST aperture (corrected) photometry. A full description of the columns in the photo-z tables is provided [here](./zout_columns.md).

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



