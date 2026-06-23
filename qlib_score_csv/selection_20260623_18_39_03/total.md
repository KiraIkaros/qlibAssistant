# params 
 {'predict_dates': [{'start': '2026-06-23', 'end': '2026-06-23'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260623_18 579250105078437964 (Recorders: 4/5)

	Recorder: 3fc5e24deae241928cfe1034475e5559

		Model: {'id': '3fc5e24deae241928cfe1034475e5559', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.005, 'ICIR': 0.039, 'Rank IC': 0.027, 'Rank ICIR': 0.183}, 'data_train_vec': ['2021-06-23', '2025-03-22'], 'train_time_vec': ['2026-06-23', '2026-06-23'], 'rank_icir': '0.183', 'weight': '0.048'}

	Recorder: b7d229665d7d42fbb137b9f70030faef

		Model: {'id': 'b7d229665d7d42fbb137b9f70030faef', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.007, 'ICIR': 0.058, 'Rank IC': 0.042, 'Rank ICIR': 0.239}, 'data_train_vec': ['2022-06-23', '2025-06-22'], 'train_time_vec': ['2026-06-23', '2026-06-23'], 'rank_icir': '0.239', 'weight': '0.063'}

	Recorder: 94babfa8f59c48019ee2b961f1e2c652

		Model: {'id': '94babfa8f59c48019ee2b961f1e2c652', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.038, 'ICIR': 0.353, 'Rank IC': 0.042, 'Rank ICIR': 0.376}, 'data_train_vec': ['2023-06-23', '2025-09-22'], 'train_time_vec': ['2026-06-23', '2026-06-23'], 'rank_icir': '0.376', 'weight': '0.099'}

	Recorder: b1922573f5e14e608f964d2d97450158

		Model: {'id': 'b1922573f5e14e608f964d2d97450158', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.039, 'ICIR': 0.371, 'Rank IC': 0.036, 'Rank ICIR': 0.415}, 'data_train_vec': ['2024-06-23', '2025-12-22'], 'train_time_vec': ['2026-06-23', '2026-06-23'], 'rank_icir': '0.415', 'weight': '0.109'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260623_18 500959478131028949 (Recorders: 3/5)

	Recorder: 7b62e5fc95fb487a96f872d94bad0e2d

		Model: {'id': '7b62e5fc95fb487a96f872d94bad0e2d', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.007, 'ICIR': 0.044, 'Rank IC': 0.025, 'Rank ICIR': 0.138}, 'data_train_vec': ['2021-06-23', '2025-03-22'], 'train_time_vec': ['2026-06-23', '2026-06-23'], 'rank_icir': '0.138', 'weight': '0.036'}

	Recorder: 0c0d89b91b9e4bd787868b761bd07178

		Model: {'id': '0c0d89b91b9e4bd787868b761bd07178', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.026, 'ICIR': 0.211, 'Rank IC': 0.035, 'Rank ICIR': 0.275}, 'data_train_vec': ['2023-06-23', '2025-09-22'], 'train_time_vec': ['2026-06-23', '2026-06-23'], 'rank_icir': '0.275', 'weight': '0.072'}

	Recorder: dd69dcabfcd54082a2f3e0a245df7827

		Model: {'id': 'dd69dcabfcd54082a2f3e0a245df7827', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.016, 'ICIR': 0.125, 'Rank IC': 0.012, 'Rank ICIR': 0.103}, 'data_train_vec': ['2024-06-23', '2025-12-22'], 'train_time_vec': ['2026-06-23', '2026-06-23'], 'rank_icir': '0.103', 'weight': '0.027'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260623_15 337906463082915270 (Recorders: 4/5)

	Recorder: 3ce9347ffec34d6db70d6676f14834c3

		Model: {'id': '3ce9347ffec34d6db70d6676f14834c3', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.015, 'ICIR': 0.092, 'Rank IC': 0.046, 'Rank ICIR': 0.283}, 'data_train_vec': ['2021-06-23', '2025-03-22'], 'train_time_vec': ['2026-06-23', '2026-06-23'], 'rank_icir': '0.283', 'weight': '0.074'}

	Recorder: afcf15bf986d40c08daea3bc234e58f1

		Model: {'id': 'afcf15bf986d40c08daea3bc234e58f1', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.016, 'ICIR': 0.101, 'Rank IC': 0.05, 'Rank ICIR': 0.298}, 'data_train_vec': ['2022-06-23', '2025-06-22'], 'train_time_vec': ['2026-06-23', '2026-06-23'], 'rank_icir': '0.298', 'weight': '0.078'}

	Recorder: df8be4acca45469686360f3b31b12aaf

		Model: {'id': 'df8be4acca45469686360f3b31b12aaf', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.019, 'ICIR': 0.139, 'Rank IC': 0.032, 'Rank ICIR': 0.225}, 'data_train_vec': ['2023-06-23', '2025-09-22'], 'train_time_vec': ['2026-06-23', '2026-06-23'], 'rank_icir': '0.225', 'weight': '0.059'}

	Recorder: 6335a0bf9c2d48a094c9d3cebff4e60b

		Model: {'id': '6335a0bf9c2d48a094c9d3cebff4e60b', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.014, 'ICIR': 0.098, 'Rank IC': 0.017, 'Rank ICIR': 0.133}, 'data_train_vec': ['2024-06-23', '2025-12-22'], 'train_time_vec': ['2026-06-23', '2026-06-23'], 'rank_icir': '0.133', 'weight': '0.035'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260623_15 409463938386999718 (Recorders: 3/5)

	Recorder: 67adfa4abe624302bd7014792cfeb8fa

		Model: {'id': '67adfa4abe624302bd7014792cfeb8fa', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.003, 'ICIR': 0.018, 'Rank IC': 0.036, 'Rank ICIR': 0.274}, 'data_train_vec': ['2021-06-23', '2025-03-22'], 'train_time_vec': ['2026-06-23', '2026-06-23'], 'rank_icir': '0.274', 'weight': '0.072'}

	Recorder: dd1e9b4c9b50435ba8c01422fa08afb9

		Model: {'id': 'dd1e9b4c9b50435ba8c01422fa08afb9', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.003, 'ICIR': 0.021, 'Rank IC': 0.021, 'Rank ICIR': 0.163}, 'data_train_vec': ['2023-06-23', '2025-09-22'], 'train_time_vec': ['2026-06-23', '2026-06-23'], 'rank_icir': '0.163', 'weight': '0.043'}

	Recorder: 85942c28596e4762b7692f1ca95a130d

		Model: {'id': '85942c28596e4762b7692f1ca95a130d', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.013, 'ICIR': 0.077, 'Rank IC': 0.011, 'Rank ICIR': 0.063}, 'data_train_vec': ['2024-06-23', '2025-12-22'], 'train_time_vec': ['2026-06-23', '2026-06-23'], 'rank_icir': '0.063', 'weight': '0.017'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260623_15 326485211771795575 (Recorders: 3/5)

	Recorder: 0d71bcb7529448cfa4c3d108caa4fb9b

		Model: {'id': '0d71bcb7529448cfa4c3d108caa4fb9b', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.001, 'ICIR': 0.009, 'Rank IC': 0.049, 'Rank ICIR': 0.287}, 'data_train_vec': ['2022-06-23', '2025-06-22'], 'train_time_vec': ['2026-06-23', '2026-06-23'], 'rank_icir': '0.287', 'weight': '0.075'}

	Recorder: 45ae4f33428c43da99c279f5b1c17a22

		Model: {'id': '45ae4f33428c43da99c279f5b1c17a22', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.002, 'ICIR': 0.012, 'Rank IC': 0.016, 'Rank ICIR': 0.109}, 'data_train_vec': ['2023-06-23', '2025-09-22'], 'train_time_vec': ['2026-06-23', '2026-06-23'], 'rank_icir': '0.109', 'weight': '0.029'}

	Recorder: 9fa81158343c43b7aad22fc29c361cac

		Model: {'id': '9fa81158343c43b7aad22fc29c361cac', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.022, 'ICIR': 0.17, 'Rank IC': 0.026, 'Rank ICIR': 0.252}, 'data_train_vec': ['2024-06-23', '2025-12-22'], 'train_time_vec': ['2026-06-23', '2026-06-23'], 'rank_icir': '0.252', 'weight': '0.066'}
