# HSCWISEAGN-Gfitting
This contains the data of ~31k HSC-WISE AGN candidates at 0.5<z<1.5 within our angular mask, plus the most relevant data columns estimated by the GRAHSP fitting code

| Column           | Description                |
| ---------------- | -------------------------- |
| ra, dec          | Right ascention and declination  |
| photoz_best_pz   | Photometric redsfhit from HSC       |
| photoz_conf_best_pz   | Photometric redsfhit confidence. Could be useful to filter out catastrophic fits    |
| photoz_risk_best_pz   | Photometric redsfhit risk. Again, useful to filter out catastrophic fits    |
| W1mag, W2mag, W3mag   | WISE magntiudes in W1, W2 and W3 bands    |
| g_cmodel_mag, r_cmodel_mag, i_cmodel_mag   | HSC magntiudes, corrected for stellar locus shift    |
| z_cmodel_mag, y_cmodel_mag   | HSC magntiudes, corrected for stellar locus shift    |
| W1snr, W2snr, W3snr   | WISE signal to noise ratios in W1, W2 and W3 bands    |
| p_unobsc   | Probability of unobscured (type1) AGN. Derivde from multi-lognormal fits in g-W3 vs redshift figure.      |
| p_obsc   | Probability of obscured (type2) AGN. Derivde from multi-lognormal fits in g-W3 vs redshift figure.      |
| ang_class   | Classification: 0:(unobscured, type1) 1:(obscured, type2) 2:(unclassificable)      |
| log_stellar_mass_mean   | GRAHSP: mean stellar mass      |
| log_stellar_mass_mean   | GRAHSP: likelihood-weighted mean stellar  |
| log_L_AGN_mean   | GRAHSP: luminosity of AGN      |
| log_L_AGN_lmean   | GRAHSP: likelihood-weighted luminosity of AGN  |
| chi2_mean   | GRAHSP: chi2      |
| chi2_lmean   | GRAHSP: likelihood-weighted chi2   |
