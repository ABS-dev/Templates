# Software Templates <img src="man/figures/logo.png" alt="Package Logo" width="100" align="right" />

These are **example** files (that need to be carefully adapted for specific
products/assays) that were released in early 2014 to illustrate CVBSOP 0102.

These files were formerly available on the vendors’ community sharing websites,
which no longer exist. They are now posted here for convenience only and are not
actively being supported. No endorsement, claim, or warranty is implied for
these files. They are made available for investigational or pedagogical use only.

# SMP

SoftMax Pro *example* protocol files for estimating relative potency.

|                        Curve Type / Shape   |    Version    |                   Sample File                                             |                          Title                           |   RP Estimate    |
|:-------------------------------------------:|:-------------:|:----------------------------------------------------------------------------:|:--------------------------------------------------------:|:----------------:|
| Full dose response<br>(3PL)                 |     6.3       | [fulldose.sprx](fulldose.sprx)                                            | Estimating Relative Potency<br>for Full Dose Curves      | `1 / RelPotPLA`  |
| Partial Linear<br>Straight line             |     6.3       | [partiallylinear.sprx](partiallylinear.sprx)                              | Estimating Relative Potency<br>for Partially Linear Data | `1 / RelPotPLA`  |
| Full dose response<br>(3PL)                 |   7.0.3 GXP   | [fulldose.sprx](Softmax_v7.0.3 GXP/fulldose.sprx)                         | Estimating Relative Potency<br>for Full Dose Curves      | `1 / RelPotPLA`  |
| Partial Linear<br>Straight line             |   7.0.3 GXP   | [partiallylinear.sprx](Softmax_v7.0.3 GXP/partiallylinear.sprx)           | Estimating Relative Potency<br>for Partially Linear Data | `1 / RelPotPLA`  |
| Full dose response<br>(3PL)                 |   7.1.2 GXP   | [fulldose 2023.sdax](Softmax_v7.1.2 GXP/fulldose_2023.sdax)               | Estimating Relative Potency<br>for Full Dose Curves      | `1 / RelPotPLA`  |
| Partial Linear<br>Straight line             |   7.1.2 GXP   | [partiallylinear 2023.sdax](Softmax_v7.1.2 GXP/partiallylinear_2023.sdax) | Estimating Relative Potency<br>for Partially Linear Data | `1 / RelPotPLA`  |



Estimating Relative Potency for Full Dose Curves
Estimating Relative Potency for Partially Linear Data


# Gen5

At the time these templates were developed, BioTek (Now Agilent) created a document titled
"**Estimating Relative Potency for CVB using Gen5™ Software**".  Users of Gen5 may find this
document useful when developing their own experiment files.  This document has been archived
by Agilent but as of March 23, 2026, was still discoverable by performing a web search on
title.


Gen5 *example* experiment files for estimating relative potency.

|                        Curve Type / Shape                        |                   Sample File                  |                        Description                      | RP Estimate |
|:----------------------------------------------------------------:|:----------------------------------------------:|:-------------------------------------------------------:|:-----------:|
| Full dose response (3PL)<br>descending left to right             | [RP_descending_dil.xpt](RP_descending_dil.xpt) | Non-competitive,<br>$x$-axis is dilution                |  `1 / REP`  |
| Full dose response (3PL)<br>ascending left to right              | [RP_ascending_dil.xpt](RP_ascending_dil.xpt)   | Competitive,<br>$x$-axis is dilution                    |  `1 / REP`  |
| Partial or Fully Linear/Straight<br>line ascending or descending | [RP_linear_dil.xpt](RP_linear_dil.xpt)         | Competitive or Non-competitive,<br>$x$-axis is dilution |  `1 / REP`  |
