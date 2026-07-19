# params 
 {'predict_dates': [{'start': '2026-07-17', 'end': '2026-07-17'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260719_16 638153836667111498 (Recorders: 2/5)

	Recorder: e85281581f0c476c83de4fbd27307750

		Model: {'id': 'e85281581f0c476c83de4fbd27307750', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.003, 'ICIR': 0.02, 'Rank IC': 0.028, 'Rank ICIR': 0.137}, 'data_train_vec': ['2021-07-19', '2025-04-18'], 'train_time_vec': ['2026-07-19', '2026-07-19'], 'rank_icir': '0.137', 'weight': '0.111'}

	Recorder: 4252ce0db9784e5694e66cb3c8a20fc2

		Model: {'id': '4252ce0db9784e5694e66cb3c8a20fc2', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.007, 'ICIR': 0.048, 'Rank IC': 0.013, 'Rank ICIR': 0.113}, 'data_train_vec': ['2023-07-19', '2025-10-18'], 'train_time_vec': ['2026-07-19', '2026-07-19'], 'rank_icir': '0.113', 'weight': '0.091'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260719_16 123141448141786259 (Recorders: 2/5)

	Recorder: 54c0af061ca94d86af22011574ffaad7

		Model: {'id': '54c0af061ca94d86af22011574ffaad7', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.013, 'ICIR': 0.085, 'Rank IC': 0.037, 'Rank ICIR': 0.221}, 'data_train_vec': ['2021-07-19', '2025-04-18'], 'train_time_vec': ['2026-07-19', '2026-07-19'], 'rank_icir': '0.221', 'weight': '0.179'}

	Recorder: 268839448c7c4fc99d16079416d66e4c

		Model: {'id': '268839448c7c4fc99d16079416d66e4c', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.011, 'ICIR': 0.078, 'Rank IC': 0.019, 'Rank ICIR': 0.151}, 'data_train_vec': ['2023-07-19', '2025-10-18'], 'train_time_vec': ['2026-07-19', '2026-07-19'], 'rank_icir': '0.151', 'weight': '0.122'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260719_14 457400091197514287 (Recorders: 3/5)

	Recorder: 13cc8d8367854b84b2b925c95fe7853b

		Model: {'id': '13cc8d8367854b84b2b925c95fe7853b', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.016, 'ICIR': 0.098, 'Rank IC': 0.042, 'Rank ICIR': 0.26}, 'data_train_vec': ['2021-07-19', '2025-04-18'], 'train_time_vec': ['2026-07-19', '2026-07-19'], 'rank_icir': '0.260', 'weight': '0.210'}

	Recorder: 7f6be08c931a49f58cbd9626acc0a3ad

		Model: {'id': '7f6be08c931a49f58cbd9626acc0a3ad', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.006, 'ICIR': 0.037, 'Rank IC': 0.023, 'Rank ICIR': 0.153}, 'data_train_vec': ['2022-07-19', '2025-07-18'], 'train_time_vec': ['2026-07-19', '2026-07-19'], 'rank_icir': '0.153', 'weight': '0.124'}

	Recorder: 89ea57579e3c4122a2ef962977ebef52

		Model: {'id': '89ea57579e3c4122a2ef962977ebef52', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.008, 'ICIR': 0.05, 'Rank IC': 0.027, 'Rank ICIR': 0.201}, 'data_train_vec': ['2023-07-19', '2025-10-18'], 'train_time_vec': ['2026-07-19', '2026-07-19'], 'rank_icir': '0.201', 'weight': '0.163'}
