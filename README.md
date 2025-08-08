**Proton Accelerator Neutron Shielding Dataset and ML Analysis**
This repository contains datasets and Python codes used for curve fitting and machine learning (ML) analysis in our study on secondary neutron dose attenuation in various shielding environments for high-energy proton accelerators.

**Dataset Information**
Source of data: FLUKA Monte Carlo simulations (performed by Demet Sarıyer)

**Energy levels:** 50, 100, 250, and 1000 MeV proton beams

**Shielding configurations:**

- Standard Concrete – Air
- Standard Concrete – Shield
- Ferro-Boron – Air
- Ferro-Boron – Shield

**Data type:** Dose rate values (µSv/h) at various distances or shield thicknesses

**File format:** .xlsx

**Code Information**
**Curve fitting:** Classical exponential attenuation model using SciPy’s curve_fit function

_Machine learning models:_

1. Linear Regression (LR)
2. Decision Tree Regressor (DTR)
3. Random Forest Regressor (RFR)

**Evaluation metrics:** R², RMSE, MAE, and 5-fold cross-validation

**Programming language:** Python 3.x

**Attribution & Citation**
If you use this dataset or code, please cite the related study as follows:

Ali Osman Gökcan, Demet Sarıyer. Machine learning-based prediction of neutron dose attenuation in shielding materials for high-energy proton accelerators (unpublished).

We kindly request that you give appropriate credit when using this dataset or code in any form of research or publication.
