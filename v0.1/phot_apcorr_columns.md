Columns in ``{field}_irac_phot_apcorr.fits``.
=============================================

All flux densities are given in units of ``microJansky`` (AB zeropoint = 23.9).

|                   *Column*     |                                                                                        *Description* |
|     :--------------------:     |                                                         :------------------------------------------- |
|                                | **Columns derived from the IR detection image**                                                      |
|                     ``thresh`` |                        See [sep.extract](https://sep.readthedocs.io/en/v1.0.x/api/sep.extract.html). |
|                       ``npix`` |                                                                                                  ... |
|                      ``tnpix`` |                                                                                                  ... |
|                       ``xmin`` |                                                                                                  ... |
|                       ``xmax`` |                                                                                                  ... |
|                       ``ymin`` |                                                                                                  ... |
|                       ``ymax`` |                                                                                                  ... |
|                          ``x`` |                                                                                                  ... |
|                          ``y`` |                                                                                                  ... |
|                   ``x2_image`` |                                                                                                  ... |
|                   ``y2_image`` |                                                                                                  ... |
|                   ``xy_image`` |                                                                                                  ... |
|                      ``errx2`` |                                                                                                  ... |
|                      ``erry2`` |                                                                                                  ... |
|                      ``errxy`` |                                                                                                  ... |
|                    ``a_image`` |                                                                                                  ... |
|                    ``b_image`` |                                                                                                  ... |
|                ``theta_image`` |                                                                                                  ... |
|                  ``cxx_image`` |                                                                                                  ... |
|                  ``cyy_image`` |                                                                                                  ... |
|                  ``cxy_image`` |                                                                                                  ... |
|                      ``cflux`` |                                                                                                  ... |
|                       ``flux`` |                                                                                                  ... |
|                      ``cpeak`` |                                                                                                  ... |
|                       ``peak`` |                                                                                                  ... |
|                     ``xcpeak`` |                                                                                                  ... |
|                     ``ycpeak`` |                                                                                                  ... |
|                      ``xpeak`` |                                                                                                  ... |
|                      ``ypeak`` |                                                                                                  ... |
|                       ``flag`` |                                                                                                  ... |
|                    ``x_image`` |                                                                        unit-indexed image coordinate |
|                    ``y_image`` |                                                                        unit-indexed image coordinate |
|                         ``id`` |                                                                                    object identifier |
|                         ``ra`` |                                                                                 Right Ascension, deg |
|                        ``dec`` |                                                                                     Declination, deg |
|                    ``x_world`` |                                                                                      duplicate of ra |
|                    ``y_world`` |                                                                                     duplicate of dec |
|                   ``flux_iso`` |                                                       Isophotal flux within the segmentation polygon |
|                ``fluxerr_iso`` |                                                                                          uncertainty |
|                   ``area_iso`` |                                                                    Area of the isophotal region, pix |
|                    ``mag_iso`` |                                                                  magnitude corresponding to flux_iso |
|                ``kron_radius`` |                                                            Kron radius (in units of semi-major axis) |
|                 ``kron_rcirc`` |                                                                        Circularized Kron radius, pix |
|                  ``flux_auto`` |                                                                 Flux within elliptical Kron aperture |
|               ``fluxerr_auto`` |                                                                                         uncertainity |
|                   ``bkg_auto`` |                                                           Background within elliptical Kron aperture |
|                  ``flag_auto`` |                                                                      `sep` flag within Kron aperture |
|                  ``area_auto`` |                                                                            Area of the Kron aperture |
|           ``flux_radius_flag`` |                                                                      ``sep`` flag on ``flux_radius`` |
|             ``flux_radius_20`` |                                                                                 20% flux radius, pix |
|                ``flux_radius`` |                                                                                 50% flux radius, pix |
|             ``flux_radius_90`` |                                                                                 90% flux radius, pix |
|                   ``tot_corr`` |                                         Correction for flux outside the Kron aperture (point source) |
|                   ``mag_auto`` |                                                                                       Kron magnitude |
|                ``magerr_auto`` |                                                                                          Uncertainty |
|             ``flux_aper_{ap}`` |                       Flux in circular aperture, diameters 0.36, 0.5, 0.7, 1.0, 1.2, 1.5, 3.0 arcsec |
|          ``fluxerr_aper_{ap}`` |                                                                                          Uncertainty |
|             ``flag_aper_{ap}`` |                                                               ``sep`` flag for the circular aperture |
|              ``bkg_aper_{ap}`` |                                                 Background that was removed within circular aperture |
|             ``mask_aper_{ap}`` |                                                 number of masked pixels within the circular aperture |
|                                | **Aperture measurements in each HST filter**                                                         |
|      ``{filt}_flux_aper_{ap}`` |                                           Same as all ``aper`` columns above, but in each HST filter |
|   ``{filt}_fluxerr_aper_{ap}`` |                                                                                                  ... |
|      ``{filt}_flag_aper_{ap}`` |                                                                                                  ... |
|       ``{filt}_bkg_aper_{ap}`` |                                                                                                  ... |
|      ``{filt}_mask_aper_{ap}`` |                                                                                                  ... |
|            ``{filt}_tot_corr`` |                                                                                                  ... |
|                ``apcorr_{ap}`` |                                                  Aperture correction: ``flux_auto / flux_aper_{ap}`` |
|            ``{filt}_corr{ap}`` |                   Aperture-corrected flux, ``{filt}_corr_{ap} = {filt_flux_aper_{ap} * apcorr_{ap}`` |
|          ``{filt}_ecorr_{ap}`` |                                                                                          Uncertainty |
|            ``{filt}_tot_{ap}`` |       Total flux derived from the aperture, ``{filt}_tot_{ap} = {filt}_corr_{ap} * {filt}_tot_corr`` |
|           ``{filt}_etot_{ap}`` |                                                                                          Uncertainty |
|                                | **IRAC channel 3.6 and 4.5 µm photometry**                                                           |
|              ``irac_ch1_nexp`` |                                                         Number of CH1 BCDs that cover a given object |
|           ``irac_ch1_exptime`` |                                                                               IRAC CH1 exposure time |
|              ``irac_ch1_flux`` |                                                                        IRAC CH1 flux density (total) |
|               ``irac_ch1_err`` |                                                                                          uncertainty |
|             ``irac_ch1_patch`` |                                                                                  ``golfir`` patch ID |
|            ``irac_ch1_bright`` |                                                                        ``golfir`` Bright object flag |
|              ``irac_ch2_nexp`` |                                                         Number of CH1 BCDs that cover a given object |
|           ``irac_ch2_exptime`` |                                                                               IRAC CH2 exposure time |
|              ``irac_ch2_flux`` |                                                                        IRAC CH2 flux density (total) |
|               ``irac_ch2_err`` |                                                                                         uncertainity |
|             ``irac_ch2_patch`` |                                                                                  ``golfir`` patch ID |
|            ``irac_ch2_bright`` |                                                                        ``golfir`` Bright object flag |
|                                | **Other columns**                                                                                |
|                      ``dr_nn`` |                                                                 Distance to nearest neighbor, arcsec |
|                    ``dmag_nn`` |                                                                   Magnitude difference with neighbor |
|                      ``id_nn`` |                                                                                       ID of neighbor |
|                     ``z_spec`` |                                                               Spectroscopic redshift (empty for now) |
|                  ``dummy_err`` |                                                                                             [ignore] |
|                 ``dummy_flux`` |                                                                                             [ignore] |
