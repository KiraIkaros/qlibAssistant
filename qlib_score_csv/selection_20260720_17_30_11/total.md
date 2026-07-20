# params 
 {'predict_dates': [{'start': '2026-07-17', 'end': '2026-07-17'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260720_17 544468404281916802 (Recorders: 3/5)

	Recorder: 6bd575135e93416a9b6030d96445c4cd

		Model: {'id': '6bd575135e93416a9b6030d96445c4cd', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.007, 'ICIR': 0.044, 'Rank IC': 0.029, 'Rank ICIR': 0.177}, 'data_train_vec': ['2021-07-20', '2025-04-19'], 'train_time_vec': ['2026-07-20', '2026-07-20'], 'rank_icir': '0.177', 'weight': '0.175'}

	Recorder: 2a2e4943f3ec463b8e2dcb9c891b4f10

		Model: {'id': '2a2e4943f3ec463b8e2dcb9c891b4f10', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.007, 'ICIR': 0.075, 'Rank IC': 0.015, 'Rank ICIR': 0.13}, 'data_train_vec': ['2022-07-20', '2025-07-19'], 'train_time_vec': ['2026-07-20', '2026-07-20'], 'rank_icir': '0.130', 'weight': '0.129'}

	Recorder: 61ff675da4524263a6f0d11868821b59

		Model: {'id': '61ff675da4524263a6f0d11868821b59', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.01, 'ICIR': 0.069, 'Rank IC': 0.018, 'Rank ICIR': 0.146}, 'data_train_vec': ['2023-07-20', '2025-10-19'], 'train_time_vec': ['2026-07-20', '2026-07-20'], 'rank_icir': '0.146', 'weight': '0.145'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260720_14 611446934240748384 (Recorders: 3/5)

	Recorder: fdc7fd246a904e03988c7fa56b8f9d46

		Model: {'id': 'fdc7fd246a904e03988c7fa56b8f9d46', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.013, 'ICIR': 0.078, 'Rank IC': 0.041, 'Rank ICIR': 0.259}, 'data_train_vec': ['2021-07-20', '2025-04-19'], 'train_time_vec': ['2026-07-20', '2026-07-20'], 'rank_icir': '0.259', 'weight': '0.256'}

	Recorder: 60ab9fe65b634f44a4eec10920c86b92

		Model: {'id': '60ab9fe65b634f44a4eec10920c86b92', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.008, 'ICIR': 0.056, 'Rank IC': 0.027, 'Rank ICIR': 0.181}, 'data_train_vec': ['2022-07-20', '2025-07-19'], 'train_time_vec': ['2026-07-20', '2026-07-20'], 'rank_icir': '0.181', 'weight': '0.179'}

	Recorder: e6903b18f34043efb7b00420cb37c022

		Model: {'id': 'e6903b18f34043efb7b00420cb37c022', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.003, 'ICIR': 0.017, 'Rank IC': 0.016, 'Rank ICIR': 0.117}, 'data_train_vec': ['2023-07-20', '2025-10-19'], 'train_time_vec': ['2026-07-20', '2026-07-20'], 'rank_icir': '0.117', 'weight': '0.116'}
