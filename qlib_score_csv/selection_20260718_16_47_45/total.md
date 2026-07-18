# params 
 {'predict_dates': [{'start': '2026-07-17', 'end': '2026-07-17'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260718_16 934193149739085416 (Recorders: 2/5)

	Recorder: 0ad97971def64bf2ab3be49f9475bad6

		Model: {'id': '0ad97971def64bf2ab3be49f9475bad6', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.011, 'ICIR': 0.079, 'Rank IC': 0.033, 'Rank ICIR': 0.189}, 'data_train_vec': ['2021-07-18', '2025-04-17'], 'train_time_vec': ['2026-07-18', '2026-07-18'], 'rank_icir': '0.189', 'weight': '0.152'}

	Recorder: b006ac36bbbb471db6662845dbf77122

		Model: {'id': 'b006ac36bbbb471db6662845dbf77122', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.018, 'ICIR': 0.113, 'Rank IC': 0.024, 'Rank ICIR': 0.203}, 'data_train_vec': ['2023-07-18', '2025-10-17'], 'train_time_vec': ['2026-07-18', '2026-07-18'], 'rank_icir': '0.203', 'weight': '0.164'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260718_16 359327908082217388 (Recorders: 2/5)

	Recorder: ad2b089fe0f14b89a5f0aed174297eff

		Model: {'id': 'ad2b089fe0f14b89a5f0aed174297eff', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.005, 'ICIR': 0.037, 'Rank IC': 0.031, 'Rank ICIR': 0.202}, 'data_train_vec': ['2021-07-18', '2025-04-17'], 'train_time_vec': ['2026-07-18', '2026-07-18'], 'rank_icir': '0.202', 'weight': '0.163'}

	Recorder: ac084f17fb3447f4b0aa67d161349feb

		Model: {'id': 'ac084f17fb3447f4b0aa67d161349feb', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.02, 'ICIR': 0.162, 'Rank IC': 0.024, 'Rank ICIR': 0.203}, 'data_train_vec': ['2023-07-18', '2025-10-17'], 'train_time_vec': ['2026-07-18', '2026-07-18'], 'rank_icir': '0.203', 'weight': '0.164'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260718_13 900604482075358543 (Recorders: 2/5)

	Recorder: ae28ad71bea24ba3828408ac09e739b0

		Model: {'id': 'ae28ad71bea24ba3828408ac09e739b0', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.014, 'ICIR': 0.091, 'Rank IC': 0.043, 'Rank ICIR': 0.265}, 'data_train_vec': ['2021-07-18', '2025-04-17'], 'train_time_vec': ['2026-07-18', '2026-07-18'], 'rank_icir': '0.265', 'weight': '0.214'}

	Recorder: c7d4dae574b4412c8a3b111455348092

		Model: {'id': 'c7d4dae574b4412c8a3b111455348092', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.009, 'ICIR': 0.062, 'Rank IC': 0.028, 'Rank ICIR': 0.178}, 'data_train_vec': ['2022-07-18', '2025-07-17'], 'train_time_vec': ['2026-07-18', '2026-07-18'], 'rank_icir': '0.178', 'weight': '0.144'}
