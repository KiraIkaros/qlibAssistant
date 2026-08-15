# params 
 {'predict_dates': [{'start': '2026-08-14', 'end': '2026-08-14'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260815_15 287592012638006279 (Recorders: 1/5)

	Recorder: 351bf690c8b345d2848145c6b5c83c9f

		Model: {'id': '351bf690c8b345d2848145c6b5c83c9f', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.003, 'ICIR': 0.013, 'Rank IC': 0.025, 'Rank ICIR': 0.163}, 'data_train_vec': ['2023-08-15', '2025-11-14'], 'train_time_vec': ['2026-08-15', '2026-08-15'], 'rank_icir': '0.163', 'weight': '0.106'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260815_15 584591693981779797 (Recorders: 3/5)

	Recorder: 4da1be2617304c4b8180ae886378ffe5

		Model: {'id': '4da1be2617304c4b8180ae886378ffe5', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.01, 'ICIR': 0.06, 'Rank IC': 0.023, 'Rank ICIR': 0.163}, 'data_train_vec': ['2021-08-15', '2025-05-14'], 'train_time_vec': ['2026-08-15', '2026-08-15'], 'rank_icir': '0.163', 'weight': '0.106'}

	Recorder: 407218ff3eb74b00887c1abdeb854c83

		Model: {'id': '407218ff3eb74b00887c1abdeb854c83', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.002, 'ICIR': 0.013, 'Rank IC': 0.016, 'Rank ICIR': 0.1}, 'data_train_vec': ['2022-08-15', '2025-08-14'], 'train_time_vec': ['2026-08-15', '2026-08-15'], 'rank_icir': '0.100', 'weight': '0.065'}

	Recorder: 68c9fe56db0e43e8a4c024800257c05c

		Model: {'id': '68c9fe56db0e43e8a4c024800257c05c', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.012, 'ICIR': 0.083, 'Rank IC': 0.015, 'Rank ICIR': 0.125}, 'data_train_vec': ['2023-08-15', '2025-11-14'], 'train_time_vec': ['2026-08-15', '2026-08-15'], 'rank_icir': '0.125', 'weight': '0.081'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260815_13 967466274700316974 (Recorders: 3/5)

	Recorder: 03529264b5584062938a660d97ad0ba4

		Model: {'id': '03529264b5584062938a660d97ad0ba4', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.013, 'ICIR': 0.067, 'Rank IC': 0.028, 'Rank ICIR': 0.162}, 'data_train_vec': ['2021-08-15', '2025-05-14'], 'train_time_vec': ['2026-08-15', '2026-08-15'], 'rank_icir': '0.162', 'weight': '0.105'}

	Recorder: c579cb823c444dde93f827b4e2125894

		Model: {'id': 'c579cb823c444dde93f827b4e2125894', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.023, 'ICIR': 0.109, 'Rank IC': 0.031, 'Rank ICIR': 0.18}, 'data_train_vec': ['2022-08-15', '2025-08-14'], 'train_time_vec': ['2026-08-15', '2026-08-15'], 'rank_icir': '0.180', 'weight': '0.117'}

	Recorder: add2f1453c824577aaa4460eafb15087

		Model: {'id': 'add2f1453c824577aaa4460eafb15087', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.006, 'ICIR': 0.027, 'Rank IC': 0.012, 'Rank ICIR': 0.064}, 'data_train_vec': ['2023-08-15', '2025-11-14'], 'train_time_vec': ['2026-08-15', '2026-08-15'], 'rank_icir': '0.064', 'weight': '0.042'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260815_13 376484018876871593 (Recorders: 3/5)

	Recorder: b39647545ebf453b91f4b0d643fb139e

		Model: {'id': 'b39647545ebf453b91f4b0d643fb139e', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.005, 'ICIR': 0.025, 'Rank IC': 0.022, 'Rank ICIR': 0.139}, 'data_train_vec': ['2021-08-15', '2025-05-14'], 'train_time_vec': ['2026-08-15', '2026-08-15'], 'rank_icir': '0.139', 'weight': '0.090'}

	Recorder: ae1457ebc68d445dbae16c153a62a61d

		Model: {'id': 'ae1457ebc68d445dbae16c153a62a61d', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.024, 'ICIR': 0.123, 'Rank IC': 0.032, 'Rank ICIR': 0.207}, 'data_train_vec': ['2022-08-15', '2025-08-14'], 'train_time_vec': ['2026-08-15', '2026-08-15'], 'rank_icir': '0.207', 'weight': '0.134'}

	Recorder: 9ceb6c1111b748ee9b03ed50b9a896e8

		Model: {'id': '9ceb6c1111b748ee9b03ed50b9a896e8', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.041, 'ICIR': 0.124, 'Rank IC': 0.015, 'Rank ICIR': 0.061}, 'data_train_vec': ['2025-08-15', '2026-05-14'], 'train_time_vec': ['2026-08-15', '2026-08-15'], 'rank_icir': '0.061', 'weight': '0.040'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260815_12 899358797697556628 (Recorders: 1/5)

	Recorder: 1a827671a58f4b40afb1f6fa5d0cb64e

		Model: {'id': '1a827671a58f4b40afb1f6fa5d0cb64e', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.006, 'ICIR': 0.029, 'Rank IC': 0.03, 'Rank ICIR': 0.176}, 'data_train_vec': ['2021-08-15', '2025-05-14'], 'train_time_vec': ['2026-08-15', '2026-08-15'], 'rank_icir': '0.176', 'weight': '0.114'}
