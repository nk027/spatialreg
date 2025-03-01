# Version 1.2-1 (development)

* Add Fortran character handling USE_FC_LEN_T WRE §6.6.1

* Add **spdep** split-out functionality

# Version 1.1-8 (2021-05-03)

* #18 standardize use of `coef()` methods for (some) fitted model summary objects

* https://github.com/tidymodels/broom/issues/1003#issuecomment-798694400 changing **spatialreg** model output class names: **spdep** `sarlm` -> **spatialreg** `Sarlm`, `spautolm` -> `Spautolm`, `stsls` -> `Stsls`, `gmsar` -> `Gmsar`, `lagmess` -> `Lagmess`, `SLX` -> , `SlX`, `MCMC_s*_g` -> `MCMC_s*_G`, `SFResult` -> `SfResult`, `ME_res` -> `Me_res`, `lagImpact` -> `LagImpact`, `WXImpact` -> `WXimpact`

* #16 merged coordination of impacts methods (Gianfranco Piras)

* #14 merged correction to SDEM and SLX impacts when a lagged intercept is present (Tobias Rüttenauer).

# Version 1.1-5 (2019-12-01)

* #6, #11 na.action and precomputed eigenvalue bug

* #9 Griddy Gibbs issue

* #8 Predict method for SLX

* #7, #13-14 Offset impacts for SDEM/SLX

* #5, #10 Panel Durbin= argument


# Version 1.1-3 (2019-04-01)

* #2 Split spatialreg from spdep; spdep functions still present there as deprecated

