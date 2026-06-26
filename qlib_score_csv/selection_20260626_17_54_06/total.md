# params 
 {'predict_dates': [{'start': '2026-06-26', 'end': '2026-06-26'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260626_17 191549625464406711 (Recorders: 2/5)

	Recorder: e322f38175d04f6395825e445e3366fa

		Model: {'id': 'e322f38175d04f6395825e445e3366fa', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.033, 'ICIR': 0.267, 'Rank IC': 0.028, 'Rank ICIR': 0.232}, 'data_train_vec': ['2023-06-26', '2025-09-25'], 'train_time_vec': ['2026-06-26', '2026-06-26'], 'rank_icir': '0.232', 'weight': '0.102'}

	Recorder: 3cfaae7c42084a8d875d3a2d18a3589a

		Model: {'id': '3cfaae7c42084a8d875d3a2d18a3589a', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.029, 'ICIR': 0.268, 'Rank IC': 0.03, 'Rank ICIR': 0.311}, 'data_train_vec': ['2024-06-26', '2025-12-25'], 'train_time_vec': ['2026-06-26', '2026-06-26'], 'rank_icir': '0.311', 'weight': '0.137'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260626_17 678776444709704987 (Recorders: 3/5)

	Recorder: c29bbf4592044d54bb6f3d08e6d72ffe

		Model: {'id': 'c29bbf4592044d54bb6f3d08e6d72ffe', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.025, 'ICIR': 0.249, 'Rank IC': 0.03, 'Rank ICIR': 0.249}, 'data_train_vec': ['2023-06-26', '2025-09-25'], 'train_time_vec': ['2026-06-26', '2026-06-26'], 'rank_icir': '0.249', 'weight': '0.109'}

	Recorder: 55085cd2f5a84aba9d983fa2824ebbc8

		Model: {'id': '55085cd2f5a84aba9d983fa2824ebbc8', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.033, 'ICIR': 0.264, 'Rank IC': 0.024, 'Rank ICIR': 0.234}, 'data_train_vec': ['2024-06-26', '2025-12-25'], 'train_time_vec': ['2026-06-26', '2026-06-26'], 'rank_icir': '0.234', 'weight': '0.103'}

	Recorder: 5210fdff1f564bb69c5c7adf4f335015

		Model: {'id': '5210fdff1f564bb69c5c7adf4f335015', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.041, 'ICIR': 0.165, 'Rank IC': 0.005, 'Rank ICIR': 0.024}, 'data_train_vec': ['2025-06-26', '2026-03-25'], 'train_time_vec': ['2026-06-26', '2026-06-26'], 'rank_icir': '0.024', 'weight': '0.011'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260626_14 317931336699191994 (Recorders: 3/5)

	Recorder: 3eeaaa4599ba4dee91a12552ccb48b08

		Model: {'id': '3eeaaa4599ba4dee91a12552ccb48b08', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.009, 'ICIR': 0.056, 'Rank IC': 0.042, 'Rank ICIR': 0.256}, 'data_train_vec': ['2021-06-26', '2025-03-25'], 'train_time_vec': ['2026-06-26', '2026-06-26'], 'rank_icir': '0.256', 'weight': '0.113'}

	Recorder: ed6914b9dc1f47c3b5581edc957a67d3

		Model: {'id': 'ed6914b9dc1f47c3b5581edc957a67d3', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.016, 'ICIR': 0.106, 'Rank IC': 0.047, 'Rank ICIR': 0.285}, 'data_train_vec': ['2022-06-26', '2025-06-25'], 'train_time_vec': ['2026-06-26', '2026-06-26'], 'rank_icir': '0.285', 'weight': '0.125'}

	Recorder: 91d58572e55f4ad39e95339e8551d746

		Model: {'id': '91d58572e55f4ad39e95339e8551d746', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.025, 'ICIR': 0.194, 'Rank IC': 0.036, 'Rank ICIR': 0.276}, 'data_train_vec': ['2023-06-26', '2025-09-25'], 'train_time_vec': ['2026-06-26', '2026-06-26'], 'rank_icir': '0.276', 'weight': '0.121'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260626_14 901289217872964605 (Recorders: 2/5)

	Recorder: 5ecbd122bf454f2a99ec5b7da488e8e2

		Model: {'id': '5ecbd122bf454f2a99ec5b7da488e8e2', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.001, 'ICIR': 0.008, 'Rank IC': 0.037, 'Rank ICIR': 0.221}, 'data_train_vec': ['2021-06-26', '2025-03-25'], 'train_time_vec': ['2026-06-26', '2026-06-26'], 'rank_icir': '0.221', 'weight': '0.097'}

	Recorder: 13acd4483c284a918d8464cf0c245ad8

		Model: {'id': '13acd4483c284a918d8464cf0c245ad8', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.01, 'ICIR': 0.078, 'Rank IC': 0.026, 'Rank ICIR': 0.186}, 'data_train_vec': ['2023-06-26', '2025-09-25'], 'train_time_vec': ['2026-06-26', '2026-06-26'], 'rank_icir': '0.186', 'weight': '0.082'}
