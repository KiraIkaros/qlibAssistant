# params 
 {'predict_dates': [{'start': '2026-09-01', 'end': '2026-09-01'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260901_19 425939482298966880 (Recorders: 2/5)

	Recorder: 726bfa7c310a4701bff5fa4f3f064760

		Model: {'id': '726bfa7c310a4701bff5fa4f3f064760', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.025, 'ICIR': 0.115, 'Rank IC': 0.04, 'Rank ICIR': 0.278}, 'data_train_vec': ['2022-09-01', '2025-08-31'], 'train_time_vec': ['2026-09-01', '2026-09-01'], 'rank_icir': '0.278', 'weight': '0.137'}

	Recorder: 6333d10a1ee442bd98af5b5b9a70e1d9

		Model: {'id': '6333d10a1ee442bd98af5b5b9a70e1d9', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.019, 'ICIR': 0.073, 'Rank IC': 0.019, 'Rank ICIR': 0.116}, 'data_train_vec': ['2023-09-01', '2025-11-30'], 'train_time_vec': ['2026-09-01', '2026-09-01'], 'rank_icir': '0.116', 'weight': '0.057'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260901_19 259593607557335389 (Recorders: 2/5)

	Recorder: fc1f265ad16b43aeba85d365c25efc29

		Model: {'id': 'fc1f265ad16b43aeba85d365c25efc29', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.016, 'ICIR': 0.134, 'Rank IC': 0.023, 'Rank ICIR': 0.204}, 'data_train_vec': ['2022-09-01', '2025-08-31'], 'train_time_vec': ['2026-09-01', '2026-09-01'], 'rank_icir': '0.204', 'weight': '0.100'}

	Recorder: 725c5b801d0b4b108f24516f1b8c11a7

		Model: {'id': '725c5b801d0b4b108f24516f1b8c11a7', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.009, 'ICIR': 0.051, 'Rank IC': 0.008, 'Rank ICIR': 0.054}, 'data_train_vec': ['2023-09-01', '2025-11-30'], 'train_time_vec': ['2026-09-01', '2026-09-01'], 'rank_icir': '0.054', 'weight': '0.027'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260901_16 503470899782791390 (Recorders: 4/5)

	Recorder: 67c2c38310fa46999fce47a28d6c441d

		Model: {'id': '67c2c38310fa46999fce47a28d6c441d', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.011, 'ICIR': 0.058, 'Rank IC': 0.023, 'Rank ICIR': 0.139}, 'data_train_vec': ['2021-09-01', '2025-05-31'], 'train_time_vec': ['2026-09-01', '2026-09-01'], 'rank_icir': '0.139', 'weight': '0.068'}

	Recorder: 671cb8ef8e0942dab1a229a2d9951c2e

		Model: {'id': '671cb8ef8e0942dab1a229a2d9951c2e', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.027, 'ICIR': 0.119, 'Rank IC': 0.039, 'Rank ICIR': 0.231}, 'data_train_vec': ['2022-09-01', '2025-08-31'], 'train_time_vec': ['2026-09-01', '2026-09-01'], 'rank_icir': '0.231', 'weight': '0.114'}

	Recorder: f6101a1e41e94540813cdf992bbe0293

		Model: {'id': 'f6101a1e41e94540813cdf992bbe0293', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.003, 'ICIR': 0.012, 'Rank IC': 0.008, 'Rank ICIR': 0.045}, 'data_train_vec': ['2023-09-01', '2025-11-30'], 'train_time_vec': ['2026-09-01', '2026-09-01'], 'rank_icir': '0.045', 'weight': '0.022'}

	Recorder: cb10bfa4d7234a1ba8f2d45665ae76eb

		Model: {'id': 'cb10bfa4d7234a1ba8f2d45665ae76eb', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.014, 'ICIR': 0.053, 'Rank IC': 0.005, 'Rank ICIR': 0.02}, 'data_train_vec': ['2025-09-01', '2026-05-31'], 'train_time_vec': ['2026-09-01', '2026-09-01'], 'rank_icir': '0.020', 'weight': '0.010'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260901_16 664577428938211378 (Recorders: 5/5)

	Recorder: 83c1b614caab459cb7e0a467884f6fbe

		Model: {'id': '83c1b614caab459cb7e0a467884f6fbe', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.017, 'ICIR': 0.079, 'Rank IC': 0.026, 'Rank ICIR': 0.16}, 'data_train_vec': ['2021-09-01', '2025-05-31'], 'train_time_vec': ['2026-09-01', '2026-09-01'], 'rank_icir': '0.160', 'weight': '0.079'}

	Recorder: 01798e0f85d14a56881107d4e39c3572

		Model: {'id': '01798e0f85d14a56881107d4e39c3572', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.036, 'ICIR': 0.182, 'Rank IC': 0.035, 'Rank ICIR': 0.213}, 'data_train_vec': ['2022-09-01', '2025-08-31'], 'train_time_vec': ['2026-09-01', '2026-09-01'], 'rank_icir': '0.213', 'weight': '0.105'}

	Recorder: c613d217e8aa47549a52463665b406ac

		Model: {'id': 'c613d217e8aa47549a52463665b406ac', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.008, 'ICIR': 0.032, 'Rank IC': 0.003, 'Rank ICIR': 0.014}, 'data_train_vec': ['2023-09-01', '2025-11-30'], 'train_time_vec': ['2026-09-01', '2026-09-01'], 'rank_icir': '0.014', 'weight': '0.007'}

	Recorder: 15879367f38242109829ade9c65e7593

		Model: {'id': '15879367f38242109829ade9c65e7593', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.013, 'ICIR': 0.039, 'Rank IC': 0.008, 'Rank ICIR': 0.029}, 'data_train_vec': ['2024-09-01', '2026-02-28'], 'train_time_vec': ['2026-09-01', '2026-09-01'], 'rank_icir': '0.029', 'weight': '0.014'}

	Recorder: 21c32863f6c04688837360ba0d1a4929

		Model: {'id': '21c32863f6c04688837360ba0d1a4929', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.077, 'ICIR': 0.365, 'Rank IC': 0.05, 'Rank ICIR': 0.271}, 'data_train_vec': ['2025-09-01', '2026-05-31'], 'train_time_vec': ['2026-09-01', '2026-09-01'], 'rank_icir': '0.271', 'weight': '0.133'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260901_16 970978094962608295 (Recorders: 3/5)

	Recorder: e7026e43a9dc4836a314e4c2a401e2da

		Model: {'id': 'e7026e43a9dc4836a314e4c2a401e2da', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.002, 'ICIR': 0.008, 'Rank IC': 0.023, 'Rank ICIR': 0.139}, 'data_train_vec': ['2022-09-01', '2025-08-31'], 'train_time_vec': ['2026-09-01', '2026-09-01'], 'rank_icir': '0.139', 'weight': '0.068'}

	Recorder: 041f76a2df0143fa9e22a45c4cfa3111

		Model: {'id': '041f76a2df0143fa9e22a45c4cfa3111', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.004, 'ICIR': 0.016, 'Rank IC': 0.015, 'Rank ICIR': 0.09}, 'data_train_vec': ['2023-09-01', '2025-11-30'], 'train_time_vec': ['2026-09-01', '2026-09-01'], 'rank_icir': '0.090', 'weight': '0.044'}

	Recorder: 8a0d6e8eb32a4706995bc347b5a7a54c

		Model: {'id': '8a0d6e8eb32a4706995bc347b5a7a54c', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.031, 'ICIR': 0.103, 'Rank IC': 0.007, 'Rank ICIR': 0.032}, 'data_train_vec': ['2025-09-01', '2026-05-31'], 'train_time_vec': ['2026-09-01', '2026-09-01'], 'rank_icir': '0.032', 'weight': '0.016'}
