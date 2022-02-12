## Notes

- All flux densities are given in units of ``microJansky`` (AB zeropoint = 23.9).
- Photometry **is not** corrected for Galactic extinctions
- Missing data (e.g., filter coverage doesn't overlap) indicated with flux/error ``-99``.

## Columns in ``{field}_irac_phot_apcorr.fits``.


|                   *Column*     |                                                                                        *Description* |
|     :--------------------:     |                                                         :------------------------------------------- |
|                                | **Columns derived from the IR detection image (``CHArGE`` / ``grizli``) **                           |
| ``id``| Object Identifier|
| ``x``| sep: object barycenter (first moments)|
| ``y``| sep: object barycenter (first moments)|
| ``x2``| sep: Second moments|
| ``y2``| sep: Second moments|
| ``xy``| sep: Second moments|
| ``a``| ellipse semimajor axis|
| ``b``| ellipse semiminor axis|
| ``theta``| sep: Ellipse parameters|
| ``peak``| sep: Peak value in unconvolved data|
| ``flux``| sep: Sum of member pixels in unconvolved data|
| ``background``| sep: Background value in unconvolved data|
| ``xpeak``| sep: Coordinate of unconvolved peak pixel|
| ``ypeak``| sep: Coordinate of unconvolved peak pixel|
| ``npix``| sep: Number of pixels belonging to the object|
| ``flag``| sep: Extraction flags|
| ``a_image``| see sep.extract|
| ``b_image``| see sep.extract|
| ``theta_image``| see sep.extract|
| ``x_image``| see sep.extract|
| ``y_image``| see sep.extract|
| ``ra``| Right Ascension|
| ``dec``| Declination|
| ``layer``| Multi-level detection layer|
| ``ymin``| bounds of the image segment associated with the object|
| ``xmin``| bounds of the image segment associated with the object|
| ``ymax``| bounds of the image segment associated with the object|
| ``xmax``| bounds of the image segment associated with the object|
| ``kron_radius``| Kron radius (in units of semi-major axis)|
| ``kron_rcirc``| Circularized Kron radius|
| ``flux_auto``| Flux within elliptical Kron aperture|
| ``fluxerr_auto``| Uncertainty|
| ``bkg_auto``| Background within elliptical Kron aperture|
| ``flag_auto``| sep: flag within Kron aperture|
| ``area_auto``| Area of the Kron aperture|
| ``flux_radius_flag``| sep: flag on flux_radius|
| ``flux_radius_20``| 20% flux radius|
| ``flux_radius``| 50% flux radius|
| ``flux_radius_90``| 90% flux radius|
| ``mag_auto``| Kron magnitude|
| ``flux_aper_0``| Flux in D=0.36 arcsec circular aperture, detection image|
| ``fluxerr_aper_0``| Uncertainty in D=0.36 arcsec circular aperture, detection image|
| ``flag_aper_0``| sep: flag for the circular aperture|
| ``bkg_aper_0``| Background that was removed within D=0.36 arcsec circular aperture|
| ``mask_aper_0``| Number of masked pixels within D=0.36 arcsec circular aperture|
| ``flux_aper_1``| Flux in D=0.5 arcsec circular aperture, detection image|
| ``fluxerr_aper_1``| Uncertainty in D=0.5 arcsec circular aperture, detection image|
| ``flag_aper_1``| sep: flag for the circular aperture|
| ``bkg_aper_1``| Background that was removed within D=0.5 arcsec circular aperture|
| ``mask_aper_1``| Number of masked pixels within D=0.5 arcsec circular aperture|
| ``flux_aper_2``| Flux in D=0.7 arcsec circular aperture, detection image|
| ``fluxerr_aper_2``| Uncertainty in D=0.7 arcsec circular aperture, detection image|
| ``flag_aper_2``| sep: flag for the circular aperture|
| ``bkg_aper_2``| Background that was removed within D=0.7 arcsec circular aperture|
| ``mask_aper_2``| Number of masked pixels within D=0.7 arcsec circular aperture|
| ``flux_aper_3``| Flux in D=1.0 arcsec circular aperture, detection image|
| ``fluxerr_aper_3``| Uncertainty in D=1.0 arcsec circular aperture, detection image|
| ``flag_aper_3``| sep: flag for the circular aperture|
| ``bkg_aper_3``| Background that was removed within D=1.0 arcsec circular aperture|
| ``mask_aper_3``| Number of masked pixels within D=1.0 arcsec circular aperture|
| ``flux_aper_4``| Flux in D=1.2 arcsec circular aperture, detection image|
| ``fluxerr_aper_4``| Uncertainty in D=1.2 arcsec circular aperture, detection image|
| ``flag_aper_4``| sep: flag for the circular aperture|
| ``bkg_aper_4``| Background that was removed within D=1.2 arcsec circular aperture|
| ``mask_aper_4``| Number of masked pixels within D=1.2 arcsec circular aperture|
| ``flux_aper_5``| Flux in D=1.5 arcsec circular aperture, detection image|
| ``fluxerr_aper_5``| Uncertainty in D=1.5 arcsec circular aperture, detection image|
| ``flag_aper_5``| sep: flag for the circular aperture|
| ``bkg_aper_5``| Background that was removed within D=1.5 arcsec circular aperture|
| ``mask_aper_5``| Number of masked pixels within D=1.5 arcsec circular aperture|
| ``flux_aper_6``| Flux in D=3.0 arcsec circular aperture, detection image|
| ``fluxerr_aper_6``| Uncertainty in D=3.0 arcsec circular aperture, detection image|
| ``flag_aper_6``| sep: flag for the circular aperture|
| ``bkg_aper_6``| Background that was removed within D=3.0 arcsec circular aperture|
| ``mask_aper_6``| Number of masked pixels within D=3.0 arcsec circular aperture|
| ``flux_iso``| Isophotal flux within the segmentation polygon|
| ``fluxerr_iso``| Uncertainty|
| ``area_iso``| Area of the isophotal region|
| ``{filt}_flux_aper``| HST WFC3/IR, WFC3/UVIS or ACS/WFC flux density, D=0.7 arcsec aperture|
| ``{filt}_fluxerr_aper``| HST WFC3/IR, WFC3/UVIS or ACS/WFC flux uncertainty, D=0.7 arcsec aperture|
| ``{filt}_flux``| Total HST WFC3/IR, WFC3/UVIS or ACS/WFC flux density|
| ``{filt}_err``| Total HST WFC3/IR, WFC3/UVIS or ACS/WFC flux uncertainty|
| ``irac_ch1_nexp``| Number of IRAC exposures covering the source in CH1|
| ``irac_ch1_exptime``| Total exposure time in CH1|
| ``irac_ch1_flux``| IRAC CH1 model flux|
| ``irac_ch1_err``| IRAC CH1 model uncertainty|
| ``irac_ch2_nexp``| Number of IRAC exposures covering the source in CH2|
| ``irac_ch2_exptime``| Total exposure time in CH2|
| ``irac_ch2_flux``| IRAC CH2 model flux|
| ``irac_ch2_err``| IRAC CH2 model uncertainty|
| ``irac_ch1_flux_aper``| IRAC CH1 aperture flux within 3" |
| ``irac_ch2_flux_aper``| IRAC CH2 aperture flux within 3" |
| ``irac_ch1_err_aper``| Aperture flux uncertainty|
| ``irac_ch2_err_aper``| Aperture flux uncertainty|
| ``irac_ch1_flux_apertot``| IRAC CH1 total flux|
| ``irac_ch2_flux_apertot``| IRAC CH2 total flux|
| ``irac_ch1_err_apertot``| Total flux uncertainty|
| ``irac_ch2_err_apertot``| Total flux uncertainty|
| ``bad_phot``| Central pixel mask boolean|
| ``n_masked``| Number of masked pixels in the 3x3 pixel grid around the centre|
| ``nusefilt``| Number of filters used for photo-z|
| ``z_ml``| Maximum likelihood redshift|
| ``z_ml_chi2``| Chi2 of maximum likelihood redshift|
| ``z_ml_risk``| Redshift where R(z) minimized|
| ``lc_min``| Minimum effective wavelength of valid filters|
| ``lc_max``| Maximum effective wavelength of valid filters|
| ``z_phot``| Best photometric redshift, integral of z pdf(z) dz|
| ``z_phot_chi2``| Redshift where chi-squared maximized|
| ``z_phot_risk``| R(z_phot)|
| ``z_min_risk``| Redshift where R(z) minimized|
| ``min_risk``| R(z_min_risk)|
| ``z_raw_chi2``| Redshift where chi-squared maximized, before adding the (optional) prior|
| ``raw_chi2``| chi2(z_raw_chi2)|
| ``z025``| 2.5 percentile of pdf(z) (2-sigma)|
| ``z160``| 16 percentile of pdf(z) (1-sigma)|
| ``z500``| 50 percentile of pdf(z)|
| ``z840``| 84 percentile of pdf(z) (1-sigma)|
| ``z975``| 97.5 percentile of pdf(z) (2-sigma)|
| ``restU``| Rest-frame U-band flux|
| ``restU_err``| Uncertainty|
| ``restB``| Rest-frame B-band flux|
| ``restB_err``| Uncertainty|
| ``restV``| Rest-frame V-band flux|
| ``restV_err``| Uncertainty|
| ``restJ``| Rest-frame J-band flux|
| ``restJ_err``| Uncertainty|
| ``dL``| Luminosity distance at z_phot|
| ``Lv``| V-band luminosity, L_sun|
| ``mass``| Stellar mass|
| ``sfr``| Star formation rate over last 100 Myr|
| ``LIR``| Total 8-1000 micron luminosty|
| ``energy_abs``| Implied absorbed energy associated with Av|
| ``Av``| Extinction in V-band|
| ``lw_age_V``| Light-weighted age in the V band|
| ``MLv``| Mass-to-light ratio in V-band|
| ``Lv_p``| Percentiles of Lv [2.5,16,50,84,97.5]|
| ``mass_p``| Percentiles of Lv [2.5,16,50,84,97.5]|
| ``LIR_p``| Percentiles of LIR [2.5,16,50,84,97.5]|
| ``sfr_p``| Percentiles of SFR [2.5,16,50,84,97.5]|
| ``Av_p``| Percentiles of Av [2.5,16,50,84,97.5]|
| ``ssfr_p``| Percentiles of sSFR [2.5,16,50,84,97.5]|
| ``DISTMOD``| Distance modulus|
| ``restNUV``| Rest-frame NUV-band flux|
| ``restNUV_err``| Uncertainty|
| ``restr``| Rest-frame r-band flux|
| ``restr_err``| Uncertainty|
| ``j_id``| Unique object identifier|
| ``mu``| Magnification from the Zitrin NFW models|
| ``alma_coverage``| 2 - in ALMA continuum catalogue, 1 - upper limit, 0 - no coverage|
| ``alma_flux``| ALMA flux density at 1.2 mm|
| ``alma_err``| ALMA flux uncertainty at 1.2 mm|
| ``z_spec``| Spectroscopic redshift|
