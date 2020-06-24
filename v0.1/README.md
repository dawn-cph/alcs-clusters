
HST + IRAC v0.1
===============


Contents of this Release
========================


Images
------

HST images automatically processed by the [Grizli](https://github.com/gbrammer/grizli)/CHArGE pipeline....

IRAC with [golfir](https://github.com/gbrammer/golfir)....

-science and weight images

-residuals

General Information
===================

fields/

	directory with all the alcs fields

fields/clu+par

	HFF cluster and parallel field photomtry (only for 4 clusters)

-folder naming convention

        {cluster name}_{CHArGE id}

Data Products
-------------

[Fields](./fields.md) summary.

-main photometry catalogue

	_irac_phot.fits

-eazy output

	_irac.eazypy.zout.fits

-irac photometry+aperture corrected HST photometry

	_irac_phot_appcor

-combined photometry and eazy output

	cat_combined.fits


Source Detection
----------------


Photometry
----------

HST

IRAC


Photometric Redshifts
---------------------


.

Tests
=====

Known Issues
============

