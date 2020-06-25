Columns in ``{field}_irac.eazypy.zout.fits``.
=============================================


|                     Column     |                                                                                        Description   |
|:------------------------------:|:----------------------------------------------------------------------------------------------------|
|                         ``id`` |                                                                                    Object identifier |
|                         ``ra`` |                                                                                 Right Ascension, deg |
|                        ``dec`` |                                                                                     Declination, deg |
|                     ``z_spec`` |                                                               Spectroscopic redshift [empty for now] |
|                   ``nusefilt`` |                                                                   Number of filters used for photo-z |
|                     ``lc_min`` |                                              Minimum effective wavelength of valid filters, Angstrom |
|                     ``lc_max`` |                                              Maximum effective wavelength of valid filters, Angstrom |
|                   ``numpeaks`` |                                                   Number of separate peaks identified in ``pdf(z)``. |
|                     ``z_phot`` |                                             Best photometric redshift, integral of `` z pdf(z) dz``. |
|                ``z_phot_chi2`` |                                                                 Redshift where chi-squared maximized |
|                ``z_phot_risk`` |                                                                                        ``R(z_phot)`` |
|                 ``z_min_risk`` |                                                                    Redshift where ``R(z)`` minimized |
|                   ``min_risk`` |                                                                                    ``R(z_min_risk)`` |
|             ``z_chi2_noprior`` |                                        Redshift where chi-squared maximized, before adding the prior |
|               ``chi2_noprior`` |                                                                             ``chi2(z_chi2_noprior)`` |
|                       ``z025`` |                                                               2.5 percentile of ``pdf(z)`` (2-sigma) |
|                       ``z160`` |                                                                16 percentile of ``pdf(z)`` (1-sigma) |
|                       ``z500`` |                                                                          50 percentile of ``pdf(z)`` |
|                       ``z840`` |                                                                84 percentile of ``pdf(z)`` (1-sigma) |
|                       ``z975`` |                                                              97.5 percentile of ``pdf(z)`` (2-sigma) |
|                      ``restU`` |                                            Rest-frame U-band flux (units of catalog fluxes, ``uJy``) |
|                  ``restU_err`` |                                                                                          Uncertainty |
|                      ``restB`` |                                            Rest-frame B-band flux (units of catalog fluxes, ``uJy``) |
|                  ``restB_err`` |                                                                                          Uncertainty |
|                      ``restV`` |                                            Rest-frame V-band flux (units of catalog fluxes, ``uJy``) |
|                  ``restV_err`` |                                                                                          Uncertainty |
|                      ``restJ`` |                                            Rest-frame j-band flux (units of catalog fluxes, ``uJy``) |
|                  ``restJ_err`` |                                                                                          Uncertainty |
|                         ``dL`` |                                                           Luminosity distance at ``z_phot``, ``Mpc`` |
|                         ``Lv`` |                                                                         V-band luminosity, ``L_sun`` |
|                        ``MLv`` |                                                                        Mass-to-light ratio in V-band |
|                         ``Av`` |                                                                        Extinction in V-band, ``mag`` |
|                       ``mass`` |                                                                              Stellar mass, ``M_sun`` |
|                        ``SFR`` |                                                                Star formation rate, ``M_sun / year`` |
|                        ``LIR`` |                                                                 Total 8-1000 µm luminosty, ``L_sun`` |
|                 ``energy_abs`` |                                            Implied absorbed energy associated with ``Av``, ``L_sun`` |
|                      ``massp`` |                                                                          Percentiles of stellar mass |
|                       ``SFRp`` |                                                                                   Percentiles of SFR |
|                      ``sSFRp`` |                                                           Percentiles of specific SFR (``SFR/mass``) |
|                       ``LIRp`` |                                                                                  Percentiles of LIRR |
|               ``line_flux_Ha`` |                                                                           Template line flux, Halpha |
|                 ``line_EW_Ha`` |                                                                             Template line EW, Halpha |
|               ``line_flux_O3`` |                                                                           Template line flux, [OIII] |
|                 ``line_EW_O3`` |                                                                             Template line EW, [OIII] |
|               ``line_flux_Hb`` |                                                                            Template line flux, Hbeta |
|                 ``line_EW_Hb`` |                                                                              Template line EW, Hbeta |
|               ``line_flux_O2`` |                                                                            Template line flux, [OII] |
|                 ``line_EW_O2`` |                                                                              Template line EW, [OII] |
|              ``line_flux_Lya`` |                                                                         Template line flux, Ly-alpha |
|                ``line_EW_Lya`` |                                                                           Template line EW, Ly-alpha |
