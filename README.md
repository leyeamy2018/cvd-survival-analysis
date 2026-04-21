# cvd-survival-analysis
Using a rigorous reproducible framework, we develop and compare three survival ML models (RSF, GBSA, and DeepSurv) trained on the same set of clinical predictors as the FRS-SP, and evaluate their calibration and discrimination for 10-year CVD risk prediction. 

Ensemble-based survival ML models (RSF and GBSA) achieved acceptable discrimination and excellent calibration for 10-year CVD risk prediction using FRS-SP predictors in a Canadian prospective cohort, whereas DeepSurv substantially miscalibrated risk, particularly among women. To our knowledge, this is the first study to apply survival ML (RSF, GBSA, and DeepSurv) using the predictor set of an established clinical risk score — the FRS-SP — within a Canadian prospective cohort, and to directly compare their calibration performance in this setting using a fully reproducible methodological framework (Bayesian hyperparameter optimization, stratified cross-validation, calibration-focused evaluation, sex-stratified performance). 

Performance measures : Calibration and discrimination were used to evaluate the performance of prediction models. 
Calibration was assessed  using mean calibration and discordance. Calibration was also examined qualitatively using calibration curves (decile and diagonal approaches).

Discrimination was assessed using two performance measures: the C-index (C-statistics) and the area under the ROC (Receiver Operating Characteristic) curve, widely used to evaluate the discriminatory capacity of a model . 
Overall performance was quantified by the Brier score, which simultaneously integrates calibration and discrimination and whose low values reflect greater accuracy. 

Finally, stratified analyses were also performed according to sex and risk categories (<10%, 10-19%, ≥ 20%) to assess the robustness of performance within different subgroups.
