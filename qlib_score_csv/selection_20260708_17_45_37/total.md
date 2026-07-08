# params 
 {'predict_dates': [{'start': '2026-07-03', 'end': '2026-07-03'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260708_17 414318823021076842 (Recorders: 2/5)

	Recorder: e80874458feb4b67bc76234f3ebdf339

		Model: {'id': 'e80874458feb4b67bc76234f3ebdf339', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.032, 'ICIR': 0.269, 'Rank IC': 0.035, 'Rank ICIR': 0.294}, 'data_train_vec': ['2023-07-08', '2025-10-07'], 'train_time_vec': ['2026-07-08', '2026-07-08'], 'rank_icir': '0.294', 'weight': '0.102'}

	Recorder: e2ee3a6b53b64bdbbadb1856f75e2950

		Model: {'id': 'e2ee3a6b53b64bdbbadb1856f75e2950', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.034, 'ICIR': 0.292, 'Rank IC': 0.028, 'Rank ICIR': 0.267}, 'data_train_vec': ['2024-07-08', '2026-01-07'], 'train_time_vec': ['2026-07-08', '2026-07-08'], 'rank_icir': '0.267', 'weight': '0.093'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260708_17 111156294267381190 (Recorders: 4/5)

	Recorder: 3d1a4629366941e18f68f126c283072e

		Model: {'id': '3d1a4629366941e18f68f126c283072e', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.013, 'ICIR': 0.112, 'Rank IC': 0.032, 'Rank ICIR': 0.238}, 'data_train_vec': ['2022-07-08', '2025-07-07'], 'train_time_vec': ['2026-07-08', '2026-07-08'], 'rank_icir': '0.238', 'weight': '0.083'}

	Recorder: 423d8866400a46dd938530b326f4b339

		Model: {'id': '423d8866400a46dd938530b326f4b339', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.033, 'ICIR': 0.271, 'Rank IC': 0.034, 'Rank ICIR': 0.27}, 'data_train_vec': ['2023-07-08', '2025-10-07'], 'train_time_vec': ['2026-07-08', '2026-07-08'], 'rank_icir': '0.270', 'weight': '0.094'}

	Recorder: 574b69f3be1646fdbb4c42c834a84681

		Model: {'id': '574b69f3be1646fdbb4c42c834a84681', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.014, 'ICIR': 0.106, 'Rank IC': 0.018, 'Rank ICIR': 0.138}, 'data_train_vec': ['2024-07-08', '2026-01-07'], 'train_time_vec': ['2026-07-08', '2026-07-08'], 'rank_icir': '0.138', 'weight': '0.048'}

	Recorder: c06b594489ae40de81ced52fd3e4bee6

		Model: {'id': 'c06b594489ae40de81ced52fd3e4bee6', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.042, 'ICIR': 0.158, 'Rank IC': 0.027, 'Rank ICIR': 0.112}, 'data_train_vec': ['2025-07-08', '2026-04-07'], 'train_time_vec': ['2026-07-08', '2026-07-08'], 'rank_icir': '0.112', 'weight': '0.039'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260708_14 305083276996610108 (Recorders: 4/5)

	Recorder: b517c8c8491840a181324c407c6e0722

		Model: {'id': 'b517c8c8491840a181324c407c6e0722', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.008, 'ICIR': 0.048, 'Rank IC': 0.041, 'Rank ICIR': 0.246}, 'data_train_vec': ['2021-07-08', '2025-04-07'], 'train_time_vec': ['2026-07-08', '2026-07-08'], 'rank_icir': '0.246', 'weight': '0.086'}

	Recorder: e77abe4bf7cc44f0822c8cd810a34350

		Model: {'id': 'e77abe4bf7cc44f0822c8cd810a34350', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.024, 'ICIR': 0.152, 'Rank IC': 0.047, 'Rank ICIR': 0.293}, 'data_train_vec': ['2022-07-08', '2025-07-07'], 'train_time_vec': ['2026-07-08', '2026-07-08'], 'rank_icir': '0.293', 'weight': '0.102'}

	Recorder: 27a5ddb4f75a42588677c64afa1c6b1b

		Model: {'id': '27a5ddb4f75a42588677c64afa1c6b1b', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.029, 'ICIR': 0.218, 'Rank IC': 0.039, 'Rank ICIR': 0.299}, 'data_train_vec': ['2023-07-08', '2025-10-07'], 'train_time_vec': ['2026-07-08', '2026-07-08'], 'rank_icir': '0.299', 'weight': '0.104'}

	Recorder: f0e7ef1a67984b809c2bd8e4f8bf27ec

		Model: {'id': 'f0e7ef1a67984b809c2bd8e4f8bf27ec', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.012, 'ICIR': 0.059, 'Rank IC': 0.007, 'Rank ICIR': 0.035}, 'data_train_vec': ['2025-07-08', '2026-04-07'], 'train_time_vec': ['2026-07-08', '2026-07-08'], 'rank_icir': '0.035', 'weight': '0.012'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260708_14 531389001278226091 (Recorders: 2/5)

	Recorder: 2e13a81dfa864cd9b5cacb29850da94a

		Model: {'id': '2e13a81dfa864cd9b5cacb29850da94a', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.01, 'ICIR': 0.067, 'Rank IC': 0.021, 'Rank ICIR': 0.154}, 'data_train_vec': ['2023-07-08', '2025-10-07'], 'train_time_vec': ['2026-07-08', '2026-07-08'], 'rank_icir': '0.154', 'weight': '0.054'}

	Recorder: a2f7184d7d964dbf8b0e7ced026bf2be

		Model: {'id': 'a2f7184d7d964dbf8b0e7ced026bf2be', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.023, 'ICIR': 0.109, 'Rank IC': 0.006, 'Rank ICIR': 0.034}, 'data_train_vec': ['2025-07-08', '2026-04-07'], 'train_time_vec': ['2026-07-08', '2026-07-08'], 'rank_icir': '0.034', 'weight': '0.012'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260708_14 639024691473020450 (Recorders: 2/5)

	Recorder: 2b28aaaa627b4ad096fb816214639076

		Model: {'id': '2b28aaaa627b4ad096fb816214639076', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.007, 'ICIR': 0.048, 'Rank IC': 0.046, 'Rank ICIR': 0.288}, 'data_train_vec': ['2022-07-08', '2025-07-07'], 'train_time_vec': ['2026-07-08', '2026-07-08'], 'rank_icir': '0.288', 'weight': '0.100'}

	Recorder: f1d67bdc8ff64bad9b62d4ead93d9825

		Model: {'id': 'f1d67bdc8ff64bad9b62d4ead93d9825', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.008, 'ICIR': 0.062, 'Rank IC': 0.028, 'Rank ICIR': 0.204}, 'data_train_vec': ['2023-07-08', '2025-10-07'], 'train_time_vec': ['2026-07-08', '2026-07-08'], 'rank_icir': '0.204', 'weight': '0.071'}
