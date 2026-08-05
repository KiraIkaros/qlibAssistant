# params 
 {'predict_dates': [{'start': '2026-08-04', 'end': '2026-08-04'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260805_17 841198984468432164 (Recorders: 1/5)

	Recorder: 60537a850d514332a5f3fa5c3885b082

		Model: {'id': '60537a850d514332a5f3fa5c3885b082', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.002, 'ICIR': 0.009, 'Rank IC': 0.011, 'Rank ICIR': 0.063}, 'data_train_vec': ['2023-08-05', '2025-11-04'], 'train_time_vec': ['2026-08-05', '2026-08-05'], 'rank_icir': '0.063', 'weight': '0.104'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260805_17 661751994827266088 (Recorders: 3/5)

	Recorder: 12650272421741b2b6ac0cadbad3502f

		Model: {'id': '12650272421741b2b6ac0cadbad3502f', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.008, 'ICIR': 0.053, 'Rank IC': 0.025, 'Rank ICIR': 0.16}, 'data_train_vec': ['2021-08-05', '2025-05-04'], 'train_time_vec': ['2026-08-05', '2026-08-05'], 'rank_icir': '0.160', 'weight': '0.263'}

	Recorder: 9f6adb6a3ca34b6b829c7583cb3b4269

		Model: {'id': '9f6adb6a3ca34b6b829c7583cb3b4269', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.005, 'ICIR': 0.046, 'Rank IC': 0.009, 'Rank ICIR': 0.068}, 'data_train_vec': ['2022-08-05', '2025-08-04'], 'train_time_vec': ['2026-08-05', '2026-08-05'], 'rank_icir': '0.068', 'weight': '0.112'}

	Recorder: 1d80ef96c12c46f6974200c3413e03ac

		Model: {'id': '1d80ef96c12c46f6974200c3413e03ac', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.018, 'ICIR': 0.091, 'Rank IC': 0.023, 'Rank ICIR': 0.148}, 'data_train_vec': ['2023-08-05', '2025-11-04'], 'train_time_vec': ['2026-08-05', '2026-08-05'], 'rank_icir': '0.148', 'weight': '0.243'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260805_14 881751405371849637 (Recorders: 1/5)

	Recorder: 0ab16fe30b944947864f5b010bbe6d31

		Model: {'id': '0ab16fe30b944947864f5b010bbe6d31', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.01, 'ICIR': 0.053, 'Rank IC': 0.03, 'Rank ICIR': 0.169}, 'data_train_vec': ['2021-08-05', '2025-05-04'], 'train_time_vec': ['2026-08-05', '2026-08-05'], 'rank_icir': '0.169', 'weight': '0.278'}
