# params 
 {'predict_dates': [{'start': '2026-06-25', 'end': '2026-06-25'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260625_17 189221412004239690 (Recorders: 2/5)

	Recorder: 9d4e8d554cc049bea315ee86df4710c2

		Model: {'id': '9d4e8d554cc049bea315ee86df4710c2', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.024, 'ICIR': 0.191, 'Rank IC': 0.026, 'Rank ICIR': 0.206}, 'data_train_vec': ['2023-06-25', '2025-09-24'], 'train_time_vec': ['2026-06-25', '2026-06-25'], 'rank_icir': '0.206', 'weight': '0.123'}

	Recorder: 2b71c1e969724ee9a01f206d539d50a9

		Model: {'id': '2b71c1e969724ee9a01f206d539d50a9', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.029, 'ICIR': 0.25, 'Rank IC': 0.025, 'Rank ICIR': 0.25}, 'data_train_vec': ['2024-06-25', '2025-12-24'], 'train_time_vec': ['2026-06-25', '2026-06-25'], 'rank_icir': '0.250', 'weight': '0.149'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260625_17 956972919668446066 (Recorders: 3/5)

	Recorder: 9ad55a8e89d2421da6c34fa4ea7de15b

		Model: {'id': '9ad55a8e89d2421da6c34fa4ea7de15b', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.023, 'ICIR': 0.21, 'Rank IC': 0.03, 'Rank ICIR': 0.248}, 'data_train_vec': ['2023-06-25', '2025-09-24'], 'train_time_vec': ['2026-06-25', '2026-06-25'], 'rank_icir': '0.248', 'weight': '0.148'}

	Recorder: c821bac6d4274e468178fa6e7b40db96

		Model: {'id': 'c821bac6d4274e468178fa6e7b40db96', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.024, 'ICIR': 0.188, 'Rank IC': 0.023, 'Rank ICIR': 0.205}, 'data_train_vec': ['2024-06-25', '2025-12-24'], 'train_time_vec': ['2026-06-25', '2026-06-25'], 'rank_icir': '0.205', 'weight': '0.122'}

	Recorder: 11c2fcbf76954ddf885f6431fba78232

		Model: {'id': '11c2fcbf76954ddf885f6431fba78232', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.046, 'ICIR': 0.175, 'Rank IC': 0.005, 'Rank ICIR': 0.021}, 'data_train_vec': ['2025-06-25', '2026-03-24'], 'train_time_vec': ['2026-06-25', '2026-06-25'], 'rank_icir': '0.021', 'weight': '0.013'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260625_15 739669584027718612 (Recorders: 3/5)

	Recorder: 066012cb88d047149bcc147c61c4295c

		Model: {'id': '066012cb88d047149bcc147c61c4295c', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.011, 'ICIR': 0.063, 'Rank IC': 0.045, 'Rank ICIR': 0.27}, 'data_train_vec': ['2021-06-25', '2025-03-24'], 'train_time_vec': ['2026-06-25', '2026-06-25'], 'rank_icir': '0.270', 'weight': '0.161'}

	Recorder: 9cc0aa6b15ee43b68444ec0210897183

		Model: {'id': '9cc0aa6b15ee43b68444ec0210897183', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.012, 'ICIR': 0.076, 'Rank IC': 0.045, 'Rank ICIR': 0.266}, 'data_train_vec': ['2022-06-25', '2025-06-24'], 'train_time_vec': ['2026-06-25', '2026-06-25'], 'rank_icir': '0.266', 'weight': '0.158'}

	Recorder: 9a4f798c5186415e95f2b0c32251c323

		Model: {'id': '9a4f798c5186415e95f2b0c32251c323', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.017, 'ICIR': 0.123, 'Rank IC': 0.028, 'Rank ICIR': 0.205}, 'data_train_vec': ['2023-06-25', '2025-09-24'], 'train_time_vec': ['2026-06-25', '2026-06-25'], 'rank_icir': '0.205', 'weight': '0.122'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260625_14 547901209042851854 (Recorders: 1/5)

	Recorder: 71c8f1c4dd194056b7fe686ec4b7e8c6

		Model: {'id': '71c8f1c4dd194056b7fe686ec4b7e8c6', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.004, 'ICIR': 0.02, 'Rank IC': 0.001, 'Rank ICIR': 0.008}, 'data_train_vec': ['2024-06-25', '2025-12-24'], 'train_time_vec': ['2026-06-25', '2026-06-25'], 'rank_icir': '0.008', 'weight': '0.005'}
