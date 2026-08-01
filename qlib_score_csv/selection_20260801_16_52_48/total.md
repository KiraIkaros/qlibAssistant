# params 
 {'predict_dates': [{'start': '2026-07-31', 'end': '2026-07-31'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260801_16 990021238839465518 (Recorders: 2/5)

	Recorder: ec5ffc397aa3480ea8901fbee35ac3bc

		Model: {'id': 'ec5ffc397aa3480ea8901fbee35ac3bc', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.005, 'ICIR': 0.032, 'Rank IC': 0.028, 'Rank ICIR': 0.139}, 'data_train_vec': ['2021-08-01', '2025-04-30'], 'train_time_vec': ['2026-08-01', '2026-08-01'], 'rank_icir': '0.139', 'weight': '0.209'}

	Recorder: 4ad97b0947c14e1bb1969e7b5f0db016

		Model: {'id': '4ad97b0947c14e1bb1969e7b5f0db016', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.004, 'ICIR': 0.02, 'Rank IC': 0.005, 'Rank ICIR': 0.03}, 'data_train_vec': ['2023-08-01', '2025-10-31'], 'train_time_vec': ['2026-08-01', '2026-08-01'], 'rank_icir': '0.030', 'weight': '0.045'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260801_16 800520487201091634 (Recorders: 2/5)

	Recorder: ae0246eff6f4437582b0bc5c8cf68977

		Model: {'id': 'ae0246eff6f4437582b0bc5c8cf68977', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.01, 'ICIR': 0.062, 'Rank IC': 0.029, 'Rank ICIR': 0.176}, 'data_train_vec': ['2021-08-01', '2025-04-30'], 'train_time_vec': ['2026-08-01', '2026-08-01'], 'rank_icir': '0.176', 'weight': '0.265'}

	Recorder: 8c524b26126e4e20ae2ba6f7962fb733

		Model: {'id': '8c524b26126e4e20ae2ba6f7962fb733', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.014, 'ICIR': 0.081, 'Rank IC': 0.018, 'Rank ICIR': 0.132}, 'data_train_vec': ['2023-08-01', '2025-10-31'], 'train_time_vec': ['2026-08-01', '2026-08-01'], 'rank_icir': '0.132', 'weight': '0.199'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260801_14 662609515493699465 (Recorders: 1/5)

	Recorder: b491d5b999b644c2a080a821707c2db2

		Model: {'id': 'b491d5b999b644c2a080a821707c2db2', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.011, 'ICIR': 0.064, 'Rank IC': 0.031, 'Rank ICIR': 0.187}, 'data_train_vec': ['2021-08-01', '2025-04-30'], 'train_time_vec': ['2026-08-01', '2026-08-01'], 'rank_icir': '0.187', 'weight': '0.282'}
