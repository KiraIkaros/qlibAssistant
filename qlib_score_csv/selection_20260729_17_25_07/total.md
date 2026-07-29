# params 
 {'predict_dates': [{'start': '2026-07-29', 'end': '2026-07-29'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260729_17 113421405120413319 (Recorders: 1/5)

	Recorder: f7ba38e9603a49a5ac51ef3548a9b1d7

		Model: {'id': 'f7ba38e9603a49a5ac51ef3548a9b1d7', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.008, 'ICIR': 0.049, 'Rank IC': 0.013, 'Rank ICIR': 0.088}, 'data_train_vec': ['2023-07-29', '2025-10-28'], 'train_time_vec': ['2026-07-29', '2026-07-29'], 'rank_icir': '0.088', 'weight': '0.144'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260729_16 408143260622778786 (Recorders: 2/5)

	Recorder: 6a8fbc33ed044d8d8ac4f4b50fa6c36e

		Model: {'id': '6a8fbc33ed044d8d8ac4f4b50fa6c36e', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.012, 'ICIR': 0.075, 'Rank IC': 0.03, 'Rank ICIR': 0.193}, 'data_train_vec': ['2021-07-28', '2025-04-27'], 'train_time_vec': ['2026-07-29', '2026-07-29'], 'rank_icir': '0.193', 'weight': '0.315'}

	Recorder: 54fd78fc70f74dce9edba253cda52a75

		Model: {'id': '54fd78fc70f74dce9edba253cda52a75', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.018, 'ICIR': 0.101, 'Rank IC': 0.022, 'Rank ICIR': 0.149}, 'data_train_vec': ['2023-07-29', '2025-10-28'], 'train_time_vec': ['2026-07-29', '2026-07-29'], 'rank_icir': '0.149', 'weight': '0.243'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260729_14 968666512369533113 (Recorders: 1/5)

	Recorder: e2bd77e605ef48c8b00c74e01b83eb93

		Model: {'id': 'e2bd77e605ef48c8b00c74e01b83eb93', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.01, 'ICIR': 0.057, 'Rank IC': 0.031, 'Rank ICIR': 0.182}, 'data_train_vec': ['2021-07-28', '2025-04-27'], 'train_time_vec': ['2026-07-29', '2026-07-29'], 'rank_icir': '0.182', 'weight': '0.297'}
