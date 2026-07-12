# params 
 {'predict_dates': [{'start': '2026-07-10', 'end': '2026-07-10'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260712_16 633171385474781311 (Recorders: 2/5)

	Recorder: 59ef8813ab914d1cbee5e37d0b1eeff4

		Model: {'id': '59ef8813ab914d1cbee5e37d0b1eeff4', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.02, 'ICIR': 0.145, 'Rank IC': 0.023, 'Rank ICIR': 0.202}, 'data_train_vec': ['2023-07-12', '2025-10-11'], 'train_time_vec': ['2026-07-12', '2026-07-12'], 'rank_icir': '0.202', 'weight': '0.084'}

	Recorder: ee9f6f9437854546807f73bfc20af01a

		Model: {'id': 'ee9f6f9437854546807f73bfc20af01a', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.008, 'ICIR': 0.058, 'Rank IC': 0.007, 'Rank ICIR': 0.057}, 'data_train_vec': ['2024-07-12', '2026-01-11'], 'train_time_vec': ['2026-07-12', '2026-07-12'], 'rank_icir': '0.057', 'weight': '0.024'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260712_16 650333056420717161 (Recorders: 4/5)

	Recorder: d8d48f61e02d477cbc04a372e8e8c85d

		Model: {'id': 'd8d48f61e02d477cbc04a372e8e8c85d', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.004, 'ICIR': 0.027, 'Rank IC': 0.026, 'Rank ICIR': 0.17}, 'data_train_vec': ['2021-07-12', '2025-04-11'], 'train_time_vec': ['2026-07-12', '2026-07-12'], 'rank_icir': '0.170', 'weight': '0.071'}

	Recorder: 1d3cbadad9c7483389dfdb80d455f963

		Model: {'id': '1d3cbadad9c7483389dfdb80d455f963', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.03, 'ICIR': 0.266, 'Rank IC': 0.03, 'Rank ICIR': 0.273}, 'data_train_vec': ['2023-07-12', '2025-10-11'], 'train_time_vec': ['2026-07-12', '2026-07-12'], 'rank_icir': '0.273', 'weight': '0.114'}

	Recorder: f19f25945135440d86c682fd9e8a426a

		Model: {'id': 'f19f25945135440d86c682fd9e8a426a', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.012, 'ICIR': 0.087, 'Rank IC': 0.014, 'Rank ICIR': 0.107}, 'data_train_vec': ['2024-07-12', '2026-01-11'], 'train_time_vec': ['2026-07-12', '2026-07-12'], 'rank_icir': '0.107', 'weight': '0.045'}

	Recorder: 99088c3411f646ea9731e542248b152f

		Model: {'id': '99088c3411f646ea9731e542248b152f', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.024, 'ICIR': 0.094, 'Rank IC': 0.004, 'Rank ICIR': 0.016}, 'data_train_vec': ['2025-07-12', '2026-04-11'], 'train_time_vec': ['2026-07-12', '2026-07-12'], 'rank_icir': '0.016', 'weight': '0.007'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260712_14 242482213705402397 (Recorders: 3/5)

	Recorder: d8a23b776444404e9eeeada3008adf42

		Model: {'id': 'd8a23b776444404e9eeeada3008adf42', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.012, 'ICIR': 0.069, 'Rank IC': 0.038, 'Rank ICIR': 0.234}, 'data_train_vec': ['2021-07-12', '2025-04-11'], 'train_time_vec': ['2026-07-12', '2026-07-12'], 'rank_icir': '0.234', 'weight': '0.098'}

	Recorder: 46cf8edd9e2c426ba89746332c54c152

		Model: {'id': '46cf8edd9e2c426ba89746332c54c152', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.021, 'ICIR': 0.139, 'Rank IC': 0.04, 'Rank ICIR': 0.263}, 'data_train_vec': ['2022-07-12', '2025-07-11'], 'train_time_vec': ['2026-07-12', '2026-07-12'], 'rank_icir': '0.263', 'weight': '0.110'}

	Recorder: e03872039df348db8932aa964fc3c8eb

		Model: {'id': 'e03872039df348db8932aa964fc3c8eb', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.027, 'ICIR': 0.203, 'Rank IC': 0.037, 'Rank ICIR': 0.305}, 'data_train_vec': ['2023-07-12', '2025-10-11'], 'train_time_vec': ['2026-07-12', '2026-07-12'], 'rank_icir': '0.305', 'weight': '0.128'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260712_13 902446884827329851 (Recorders: 1/5)

	Recorder: 64c0c0df61f24e7d87213303791b253a

		Model: {'id': '64c0c0df61f24e7d87213303791b253a', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.009, 'ICIR': 0.058, 'Rank IC': 0.021, 'Rank ICIR': 0.144}, 'data_train_vec': ['2023-07-12', '2025-10-11'], 'train_time_vec': ['2026-07-12', '2026-07-12'], 'rank_icir': '0.144', 'weight': '0.060'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260712_13 387370791360114007 (Recorders: 3/5)

	Recorder: 8062b02a6da04a81be1e5c92642fa051

		Model: {'id': '8062b02a6da04a81be1e5c92642fa051', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.001, 'ICIR': 0.008, 'Rank IC': 0.034, 'Rank ICIR': 0.206}, 'data_train_vec': ['2021-07-12', '2025-04-11'], 'train_time_vec': ['2026-07-12', '2026-07-12'], 'rank_icir': '0.206', 'weight': '0.086'}

	Recorder: 322dc6c7983c4cf0a721e1b6809a3a25

		Model: {'id': '322dc6c7983c4cf0a721e1b6809a3a25', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.006, 'ICIR': 0.038, 'Rank IC': 0.035, 'Rank ICIR': 0.217}, 'data_train_vec': ['2022-07-12', '2025-07-11'], 'train_time_vec': ['2026-07-12', '2026-07-12'], 'rank_icir': '0.217', 'weight': '0.091'}

	Recorder: 3cac3b2bcb5d4a2887c674279080b9b6

		Model: {'id': '3cac3b2bcb5d4a2887c674279080b9b6', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.001, 'ICIR': 0.011, 'Rank IC': 0.025, 'Rank ICIR': 0.197}, 'data_train_vec': ['2023-07-12', '2025-10-11'], 'train_time_vec': ['2026-07-12', '2026-07-12'], 'rank_icir': '0.197', 'weight': '0.082'}
