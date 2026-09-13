# params 
 {'predict_dates': [{'start': '2026-09-11', 'end': '2026-09-11'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260913_18 112300959540133383 (Recorders: 2/5)

	Recorder: 039c1fe7d2b44ce7bf4a55c2c570b98b

		Model: {'id': '039c1fe7d2b44ce7bf4a55c2c570b98b', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.004, 'ICIR': 0.029, 'Rank IC': 0.018, 'Rank ICIR': 0.117}, 'data_train_vec': ['2021-09-13', '2025-06-12'], 'train_time_vec': ['2026-09-13', '2026-09-13'], 'rank_icir': '0.117', 'weight': '0.044'}

	Recorder: 5d0ae85c61f64aa794908de7f5f4b5d6

		Model: {'id': '5d0ae85c61f64aa794908de7f5f4b5d6', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.04, 'ICIR': 0.176, 'Rank IC': 0.046, 'Rank ICIR': 0.293}, 'data_train_vec': ['2022-09-13', '2025-09-12'], 'train_time_vec': ['2026-09-13', '2026-09-13'], 'rank_icir': '0.293', 'weight': '0.110'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260913_18 769039411834618542 (Recorders: 3/5)

	Recorder: a80664f153f743869fa95a611786ced0

		Model: {'id': 'a80664f153f743869fa95a611786ced0', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.016, 'ICIR': 0.112, 'Rank IC': 0.026, 'Rank ICIR': 0.203}, 'data_train_vec': ['2021-09-13', '2025-06-12'], 'train_time_vec': ['2026-09-13', '2026-09-13'], 'rank_icir': '0.203', 'weight': '0.076'}

	Recorder: ce013dadd2734f50ae4a86a740b0a4ae

		Model: {'id': 'ce013dadd2734f50ae4a86a740b0a4ae', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.035, 'ICIR': 0.188, 'Rank IC': 0.049, 'Rank ICIR': 0.349}, 'data_train_vec': ['2022-09-13', '2025-09-12'], 'train_time_vec': ['2026-09-13', '2026-09-13'], 'rank_icir': '0.349', 'weight': '0.131'}

	Recorder: 070c4c6c10924948bf7017967864272d

		Model: {'id': '070c4c6c10924948bf7017967864272d', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.01, 'ICIR': 0.068, 'Rank IC': 0.007, 'Rank ICIR': 0.049}, 'data_train_vec': ['2023-09-13', '2025-12-12'], 'train_time_vec': ['2026-09-13', '2026-09-13'], 'rank_icir': '0.049', 'weight': '0.018'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260913_16 127368022226111404 (Recorders: 3/5)

	Recorder: dd7076925a814a588354b1bdde5d1f80

		Model: {'id': 'dd7076925a814a588354b1bdde5d1f80', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.029, 'ICIR': 0.146, 'Rank IC': 0.04, 'Rank ICIR': 0.234}, 'data_train_vec': ['2021-09-13', '2025-06-12'], 'train_time_vec': ['2026-09-13', '2026-09-13'], 'rank_icir': '0.234', 'weight': '0.088'}

	Recorder: 1b2fde31282b4e7f917138d2309a7d17

		Model: {'id': '1b2fde31282b4e7f917138d2309a7d17', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.034, 'ICIR': 0.154, 'Rank IC': 0.044, 'Rank ICIR': 0.26}, 'data_train_vec': ['2022-09-13', '2025-09-12'], 'train_time_vec': ['2026-09-13', '2026-09-13'], 'rank_icir': '0.260', 'weight': '0.097'}

	Recorder: 4761af090a78434c81655edb087ceca8

		Model: {'id': '4761af090a78434c81655edb087ceca8', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.011, 'ICIR': 0.042, 'Rank IC': 0.014, 'Rank ICIR': 0.073}, 'data_train_vec': ['2023-09-13', '2025-12-12'], 'train_time_vec': ['2026-09-13', '2026-09-13'], 'rank_icir': '0.073', 'weight': '0.027'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260913_16 248477192465951584 (Recorders: 5/5)

	Recorder: 304331f689cd4606939254efae356c4d

		Model: {'id': '304331f689cd4606939254efae356c4d', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.028, 'ICIR': 0.136, 'Rank IC': 0.036, 'Rank ICIR': 0.214}, 'data_train_vec': ['2021-09-13', '2025-06-12'], 'train_time_vec': ['2026-09-13', '2026-09-13'], 'rank_icir': '0.214', 'weight': '0.080'}

	Recorder: 7140fd8a6d8444cba552fb94bf88efab

		Model: {'id': '7140fd8a6d8444cba552fb94bf88efab', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.037, 'ICIR': 0.188, 'Rank IC': 0.033, 'Rank ICIR': 0.202}, 'data_train_vec': ['2022-09-13', '2025-09-12'], 'train_time_vec': ['2026-09-13', '2026-09-13'], 'rank_icir': '0.202', 'weight': '0.076'}

	Recorder: d24efb773aeb410ea81f857d291edce7

		Model: {'id': 'd24efb773aeb410ea81f857d291edce7', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.007, 'ICIR': 0.028, 'Rank IC': 0.004, 'Rank ICIR': 0.018}, 'data_train_vec': ['2023-09-13', '2025-12-12'], 'train_time_vec': ['2026-09-13', '2026-09-13'], 'rank_icir': '0.018', 'weight': '0.007'}

	Recorder: d110ff164dbc462bb200573bda84f7fc

		Model: {'id': 'd110ff164dbc462bb200573bda84f7fc', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.028, 'ICIR': 0.093, 'Rank IC': 0.017, 'Rank ICIR': 0.065}, 'data_train_vec': ['2024-09-13', '2026-03-12'], 'train_time_vec': ['2026-09-13', '2026-09-13'], 'rank_icir': '0.065', 'weight': '0.024'}

	Recorder: 243f59eccd2b4e7fb08cb2dc757f9b19

		Model: {'id': '243f59eccd2b4e7fb08cb2dc757f9b19', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.034, 'ICIR': 0.184, 'Rank IC': 0.023, 'Rank ICIR': 0.122}, 'data_train_vec': ['2025-09-13', '2026-06-12'], 'train_time_vec': ['2026-09-13', '2026-09-13'], 'rank_icir': '0.122', 'weight': '0.046'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260913_16 264561357298794173 (Recorders: 3/5)

	Recorder: 89085b4bb74748d39e0522669097d0c2

		Model: {'id': '89085b4bb74748d39e0522669097d0c2', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.008, 'ICIR': 0.04, 'Rank IC': 0.033, 'Rank ICIR': 0.183}, 'data_train_vec': ['2021-09-13', '2025-06-12'], 'train_time_vec': ['2026-09-13', '2026-09-13'], 'rank_icir': '0.183', 'weight': '0.068'}

	Recorder: f1626ca619e14eba9bd5ba3566684716

		Model: {'id': 'f1626ca619e14eba9bd5ba3566684716', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.005, 'ICIR': 0.021, 'Rank IC': 0.042, 'Rank ICIR': 0.268}, 'data_train_vec': ['2022-09-13', '2025-09-12'], 'train_time_vec': ['2026-09-13', '2026-09-13'], 'rank_icir': '0.268', 'weight': '0.100'}

	Recorder: 9cf66e57f9494302b032754805be97e5

		Model: {'id': '9cf66e57f9494302b032754805be97e5', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.006, 'ICIR': 0.02, 'Rank IC': 0.005, 'Rank ICIR': 0.023}, 'data_train_vec': ['2024-09-13', '2026-03-12'], 'train_time_vec': ['2026-09-13', '2026-09-13'], 'rank_icir': '0.023', 'weight': '0.009'}
