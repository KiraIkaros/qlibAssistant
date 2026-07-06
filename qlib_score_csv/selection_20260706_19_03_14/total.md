# params 
 {'predict_dates': [{'start': '2026-07-03', 'end': '2026-07-03'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260706_18 178301319843990170 (Recorders: 2/5)

	Recorder: 7b4e1f256619427e9400534f01d084e6

		Model: {'id': '7b4e1f256619427e9400534f01d084e6', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.012, 'ICIR': 0.115, 'Rank IC': 0.028, 'Rank ICIR': 0.228}, 'data_train_vec': ['2023-07-06', '2025-10-05'], 'train_time_vec': ['2026-07-06', '2026-07-06'], 'rank_icir': '0.228', 'weight': '0.091'}

	Recorder: 5e0ba047be2b4803adcd32469e86979c

		Model: {'id': '5e0ba047be2b4803adcd32469e86979c', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.008, 'ICIR': 0.072, 'Rank IC': 0.015, 'Rank ICIR': 0.127}, 'data_train_vec': ['2024-07-06', '2026-01-05'], 'train_time_vec': ['2026-07-06', '2026-07-06'], 'rank_icir': '0.127', 'weight': '0.050'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260706_18 811272607104803182 (Recorders: 4/5)

	Recorder: 0775fc85a3e9422a81422e7338b1ac9a

		Model: {'id': '0775fc85a3e9422a81422e7338b1ac9a', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.004, 'ICIR': 0.032, 'Rank IC': 0.033, 'Rank ICIR': 0.225}, 'data_train_vec': ['2022-07-06', '2025-07-05'], 'train_time_vec': ['2026-07-06', '2026-07-06'], 'rank_icir': '0.225', 'weight': '0.089'}

	Recorder: b646e43aa9614560bff12a3da3a8e3cd

		Model: {'id': 'b646e43aa9614560bff12a3da3a8e3cd', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.032, 'ICIR': 0.266, 'Rank IC': 0.033, 'Rank ICIR': 0.258}, 'data_train_vec': ['2023-07-06', '2025-10-05'], 'train_time_vec': ['2026-07-06', '2026-07-06'], 'rank_icir': '0.258', 'weight': '0.103'}

	Recorder: 5f4bfb43eb4b403fba1704d0815d85ee

		Model: {'id': '5f4bfb43eb4b403fba1704d0815d85ee', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.026, 'ICIR': 0.202, 'Rank IC': 0.026, 'Rank ICIR': 0.213}, 'data_train_vec': ['2024-07-06', '2026-01-05'], 'train_time_vec': ['2026-07-06', '2026-07-06'], 'rank_icir': '0.213', 'weight': '0.085'}

	Recorder: a01913763a364315a6a7144e537ca4e8

		Model: {'id': 'a01913763a364315a6a7144e537ca4e8', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.039, 'ICIR': 0.155, 'Rank IC': 0.022, 'Rank ICIR': 0.088}, 'data_train_vec': ['2025-07-06', '2026-04-05'], 'train_time_vec': ['2026-07-06', '2026-07-06'], 'rank_icir': '0.088', 'weight': '0.035'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260706_16 266800809854721362 (Recorders: 3/5)

	Recorder: 4a3833dd5e344a159f1c08a6aaff7c5e

		Model: {'id': '4a3833dd5e344a159f1c08a6aaff7c5e', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.007, 'ICIR': 0.043, 'Rank IC': 0.04, 'Rank ICIR': 0.235}, 'data_train_vec': ['2021-07-06', '2025-04-05'], 'train_time_vec': ['2026-07-06', '2026-07-06'], 'rank_icir': '0.235', 'weight': '0.093'}

	Recorder: ce3071c8a6cd460da865c7fc2e1eda97

		Model: {'id': 'ce3071c8a6cd460da865c7fc2e1eda97', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.019, 'ICIR': 0.121, 'Rank IC': 0.046, 'Rank ICIR': 0.278}, 'data_train_vec': ['2022-07-06', '2025-07-05'], 'train_time_vec': ['2026-07-06', '2026-07-06'], 'rank_icir': '0.278', 'weight': '0.111'}

	Recorder: 0d037899de8e4bf7a1e3cf55247d7acc

		Model: {'id': '0d037899de8e4bf7a1e3cf55247d7acc', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.027, 'ICIR': 0.21, 'Rank IC': 0.034, 'Rank ICIR': 0.273}, 'data_train_vec': ['2023-07-06', '2025-10-05'], 'train_time_vec': ['2026-07-06', '2026-07-06'], 'rank_icir': '0.273', 'weight': '0.109'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260706_16 826010652441627186 (Recorders: 2/5)

	Recorder: 39afcaecead846ea8447508b1d7fd982

		Model: {'id': '39afcaecead846ea8447508b1d7fd982', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.007, 'ICIR': 0.051, 'Rank IC': 0.018, 'Rank ICIR': 0.133}, 'data_train_vec': ['2023-07-06', '2025-10-05'], 'train_time_vec': ['2026-07-06', '2026-07-06'], 'rank_icir': '0.133', 'weight': '0.053'}

	Recorder: 2cf065f006784d5faa63f79936b305f6

		Model: {'id': '2cf065f006784d5faa63f79936b305f6', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.022, 'ICIR': 0.104, 'Rank IC': 0.004, 'Rank ICIR': 0.021}, 'data_train_vec': ['2025-07-06', '2026-04-05'], 'train_time_vec': ['2026-07-06', '2026-07-06'], 'rank_icir': '0.021', 'weight': '0.008'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260706_15 925924329728081365 (Recorders: 2/5)

	Recorder: 2436f80072c549f7a91bb6be67b0c0ce

		Model: {'id': '2436f80072c549f7a91bb6be67b0c0ce', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.004, 'ICIR': 0.024, 'Rank IC': 0.038, 'Rank ICIR': 0.223}, 'data_train_vec': ['2022-07-06', '2025-07-05'], 'train_time_vec': ['2026-07-06', '2026-07-06'], 'rank_icir': '0.223', 'weight': '0.089'}

	Recorder: 9cb838abbaa54bcb90a11e4e98673cf9

		Model: {'id': '9cb838abbaa54bcb90a11e4e98673cf9', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.018, 'ICIR': 0.145, 'Rank IC': 0.028, 'Rank ICIR': 0.213}, 'data_train_vec': ['2023-07-06', '2025-10-05'], 'train_time_vec': ['2026-07-06', '2026-07-06'], 'rank_icir': '0.213', 'weight': '0.085'}
