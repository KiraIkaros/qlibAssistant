# params 
 {'predict_dates': [{'start': '2026-08-21', 'end': '2026-08-21'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260823_15 101250557729483164 (Recorders: 2/5)

	Recorder: bd0341b2e7954ed5b4708db142a8d88e

		Model: {'id': 'bd0341b2e7954ed5b4708db142a8d88e', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.009, 'ICIR': 0.059, 'Rank IC': 0.025, 'Rank ICIR': 0.185}, 'data_train_vec': ['2022-08-23', '2025-08-22'], 'train_time_vec': ['2026-08-23', '2026-08-23'], 'rank_icir': '0.185', 'weight': '0.116'}

	Recorder: 25cfc90640bf4ecb9c489f7ba21005ae

		Model: {'id': '25cfc90640bf4ecb9c489f7ba21005ae', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.019, 'ICIR': 0.068, 'Rank IC': 0.019, 'Rank ICIR': 0.115}, 'data_train_vec': ['2023-08-23', '2025-11-22'], 'train_time_vec': ['2026-08-23', '2026-08-23'], 'rank_icir': '0.115', 'weight': '0.072'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260823_15 660430232651053520 (Recorders: 1/5)

	Recorder: a104e1d0f3ce4737b5886cbe6b8077f3

		Model: {'id': 'a104e1d0f3ce4737b5886cbe6b8077f3', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.005, 'ICIR': 0.033, 'Rank IC': 0.014, 'Rank ICIR': 0.107}, 'data_train_vec': ['2023-08-23', '2025-11-22'], 'train_time_vec': ['2026-08-23', '2026-08-23'], 'rank_icir': '0.107', 'weight': '0.067'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260823_13 726674510597910543 (Recorders: 4/5)

	Recorder: 509c549b46e14f96a455adb48b7e2210

		Model: {'id': '509c549b46e14f96a455adb48b7e2210', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.015, 'ICIR': 0.079, 'Rank IC': 0.026, 'Rank ICIR': 0.156}, 'data_train_vec': ['2021-08-23', '2025-05-22'], 'train_time_vec': ['2026-08-23', '2026-08-23'], 'rank_icir': '0.156', 'weight': '0.098'}

	Recorder: 6f3973c380be4bb0af9b0a18b2d2fe86

		Model: {'id': '6f3973c380be4bb0af9b0a18b2d2fe86', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.026, 'ICIR': 0.12, 'Rank IC': 0.032, 'Rank ICIR': 0.191}, 'data_train_vec': ['2022-08-23', '2025-08-22'], 'train_time_vec': ['2026-08-23', '2026-08-23'], 'rank_icir': '0.191', 'weight': '0.120'}

	Recorder: 7c8d5d000f2f4cf7b3b6b4a097cdaa7e

		Model: {'id': '7c8d5d000f2f4cf7b3b6b4a097cdaa7e', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.002, 'ICIR': 0.006, 'Rank IC': 0.008, 'Rank ICIR': 0.045}, 'data_train_vec': ['2023-08-23', '2025-11-22'], 'train_time_vec': ['2026-08-23', '2026-08-23'], 'rank_icir': '0.045', 'weight': '0.028'}

	Recorder: 3f2af9bcb53a4c98b799adbd324c7a99

		Model: {'id': '3f2af9bcb53a4c98b799adbd324c7a99', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.004, 'ICIR': 0.014, 'Rank IC': 0.005, 'Rank ICIR': 0.021}, 'data_train_vec': ['2025-08-23', '2026-05-22'], 'train_time_vec': ['2026-08-23', '2026-08-23'], 'rank_icir': '0.021', 'weight': '0.013'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260823_13 695754402698599271 (Recorders: 4/5)

	Recorder: 0d4f9deb18c74975baf0d391c2a61a46

		Model: {'id': '0d4f9deb18c74975baf0d391c2a61a46', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.012, 'ICIR': 0.059, 'Rank IC': 0.025, 'Rank ICIR': 0.153}, 'data_train_vec': ['2021-08-23', '2025-05-22'], 'train_time_vec': ['2026-08-23', '2026-08-23'], 'rank_icir': '0.153', 'weight': '0.096'}

	Recorder: 3880048296aa412ebe97f0dc2f7b0bbd

		Model: {'id': '3880048296aa412ebe97f0dc2f7b0bbd', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.028, 'ICIR': 0.148, 'Rank IC': 0.033, 'Rank ICIR': 0.211}, 'data_train_vec': ['2022-08-23', '2025-08-22'], 'train_time_vec': ['2026-08-23', '2026-08-23'], 'rank_icir': '0.211', 'weight': '0.133'}

	Recorder: daeab7ec81c4425d8b05dcfe6193d587

		Model: {'id': 'daeab7ec81c4425d8b05dcfe6193d587', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.027, 'ICIR': 0.081, 'Rank IC': 0.016, 'Rank ICIR': 0.058}, 'data_train_vec': ['2024-08-23', '2026-02-22'], 'train_time_vec': ['2026-08-23', '2026-08-23'], 'rank_icir': '0.058', 'weight': '0.036'}

	Recorder: 7cdc78e0724246719c3cecef3e21c389

		Model: {'id': '7cdc78e0724246719c3cecef3e21c389', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.054, 'ICIR': 0.2, 'Rank IC': 0.029, 'Rank ICIR': 0.15}, 'data_train_vec': ['2025-08-23', '2026-05-22'], 'train_time_vec': ['2026-08-23', '2026-08-23'], 'rank_icir': '0.150', 'weight': '0.094'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260823_12 773844476129813315 (Recorders: 2/5)

	Recorder: a6d258b78c324118bb432aa7db26fd74

		Model: {'id': 'a6d258b78c324118bb432aa7db26fd74', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.003, 'ICIR': 0.012, 'Rank IC': 0.009, 'Rank ICIR': 0.055}, 'data_train_vec': ['2023-08-23', '2025-11-22'], 'train_time_vec': ['2026-08-23', '2026-08-23'], 'rank_icir': '0.055', 'weight': '0.035'}

	Recorder: 4971383fde6741e3815902f74adadf69

		Model: {'id': '4971383fde6741e3815902f74adadf69', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.061, 'ICIR': 0.167, 'Rank IC': 0.034, 'Rank ICIR': 0.145}, 'data_train_vec': ['2025-08-23', '2026-05-22'], 'train_time_vec': ['2026-08-23', '2026-08-23'], 'rank_icir': '0.145', 'weight': '0.091'}
