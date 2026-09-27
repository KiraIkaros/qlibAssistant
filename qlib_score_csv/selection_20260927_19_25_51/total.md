# params 
 {'predict_dates': [{'start': '2026-09-24', 'end': '2026-09-24'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260927_18 852141933584718982 (Recorders: 3/5)

	Recorder: fdba0d3e18d1454bb446f918019d80c3

		Model: {'id': 'fdba0d3e18d1454bb446f918019d80c3', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.011, 'ICIR': 0.072, 'Rank IC': 0.024, 'Rank ICIR': 0.138}, 'data_train_vec': ['2021-09-27', '2025-06-26'], 'train_time_vec': ['2026-09-27', '2026-09-27'], 'rank_icir': '0.138', 'weight': '0.062'}

	Recorder: 7036b8a9ff6f43409f3bf951898a0673

		Model: {'id': '7036b8a9ff6f43409f3bf951898a0673', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.02, 'ICIR': 0.081, 'Rank IC': 0.027, 'Rank ICIR': 0.146}, 'data_train_vec': ['2022-09-27', '2025-09-26'], 'train_time_vec': ['2026-09-27', '2026-09-27'], 'rank_icir': '0.146', 'weight': '0.066'}

	Recorder: a2851f4279f64acb9534e407394d1691

		Model: {'id': 'a2851f4279f64acb9534e407394d1691', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.004, 'ICIR': 0.012, 'Rank IC': 0.008, 'Rank ICIR': 0.039}, 'data_train_vec': ['2023-09-27', '2025-12-26'], 'train_time_vec': ['2026-09-27', '2026-09-27'], 'rank_icir': '0.039', 'weight': '0.018'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260927_18 244106210095767095 (Recorders: 4/5)

	Recorder: 4b6fbd9cbb454fe492f3942804361630

		Model: {'id': '4b6fbd9cbb454fe492f3942804361630', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.024, 'ICIR': 0.174, 'Rank IC': 0.032, 'Rank ICIR': 0.223}, 'data_train_vec': ['2021-09-27', '2025-06-26'], 'train_time_vec': ['2026-09-27', '2026-09-27'], 'rank_icir': '0.223', 'weight': '0.101'}

	Recorder: 1badbf0aff634cf792c597107188c717

		Model: {'id': '1badbf0aff634cf792c597107188c717', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.026, 'ICIR': 0.139, 'Rank IC': 0.031, 'Rank ICIR': 0.181}, 'data_train_vec': ['2022-09-27', '2025-09-26'], 'train_time_vec': ['2026-09-27', '2026-09-27'], 'rank_icir': '0.181', 'weight': '0.082'}

	Recorder: 597f95750c13456c830d8220cec2376f

		Model: {'id': '597f95750c13456c830d8220cec2376f', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.005, 'ICIR': 0.022, 'Rank IC': 0.009, 'Rank ICIR': 0.046}, 'data_train_vec': ['2023-09-27', '2025-12-26'], 'train_time_vec': ['2026-09-27', '2026-09-27'], 'rank_icir': '0.046', 'weight': '0.021'}

	Recorder: ca5c50fa7cd34e7ea6b329c158a79c1a

		Model: {'id': 'ca5c50fa7cd34e7ea6b329c158a79c1a', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.012, 'ICIR': 0.079, 'Rank IC': 0.003, 'Rank ICIR': 0.026}, 'data_train_vec': ['2024-09-27', '2026-03-26'], 'train_time_vec': ['2026-09-27', '2026-09-27'], 'rank_icir': '0.026', 'weight': '0.012'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260927_17 782503883866402376 (Recorders: 4/5)

	Recorder: 4ca1708284db460b868a780b31d5b047

		Model: {'id': '4ca1708284db460b868a780b31d5b047', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.033, 'ICIR': 0.17, 'Rank IC': 0.042, 'Rank ICIR': 0.245}, 'data_train_vec': ['2021-09-27', '2025-06-26'], 'train_time_vec': ['2026-09-27', '2026-09-27'], 'rank_icir': '0.245', 'weight': '0.111'}

	Recorder: 6269d3c95366429894535f56c9053a7f

		Model: {'id': '6269d3c95366429894535f56c9053a7f', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.028, 'ICIR': 0.132, 'Rank IC': 0.03, 'Rank ICIR': 0.171}, 'data_train_vec': ['2022-09-27', '2025-09-26'], 'train_time_vec': ['2026-09-27', '2026-09-27'], 'rank_icir': '0.171', 'weight': '0.077'}

	Recorder: 34bd50a4ddfe42c7866a4dd31c8790b3

		Model: {'id': '34bd50a4ddfe42c7866a4dd31c8790b3', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.003, 'ICIR': 0.009, 'Rank IC': 0.003, 'Rank ICIR': 0.015}, 'data_train_vec': ['2023-09-27', '2025-12-26'], 'train_time_vec': ['2026-09-27', '2026-09-27'], 'rank_icir': '0.015', 'weight': '0.007'}

	Recorder: da1d05bf943b429090887fa1e4cb9ea2

		Model: {'id': 'da1d05bf943b429090887fa1e4cb9ea2', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.031, 'ICIR': 0.137, 'Rank IC': 0.006, 'Rank ICIR': 0.035}, 'data_train_vec': ['2024-09-27', '2026-03-26'], 'train_time_vec': ['2026-09-27', '2026-09-27'], 'rank_icir': '0.035', 'weight': '0.016'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260927_17 566599871317604158 (Recorders: 3/5)

	Recorder: 8793dc58201b467a937f98db68bf23c6

		Model: {'id': '8793dc58201b467a937f98db68bf23c6', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.03, 'ICIR': 0.148, 'Rank IC': 0.034, 'Rank ICIR': 0.198}, 'data_train_vec': ['2021-09-27', '2025-06-26'], 'train_time_vec': ['2026-09-27', '2026-09-27'], 'rank_icir': '0.198', 'weight': '0.090'}

	Recorder: f9af34dc352743eb8fa0e3b94528a5c2

		Model: {'id': 'f9af34dc352743eb8fa0e3b94528a5c2', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.026, 'ICIR': 0.12, 'Rank IC': 0.015, 'Rank ICIR': 0.085}, 'data_train_vec': ['2022-09-27', '2025-09-26'], 'train_time_vec': ['2026-09-27', '2026-09-27'], 'rank_icir': '0.085', 'weight': '0.038'}

	Recorder: b89584beb89d44d68bce53b39a0849ce

		Model: {'id': 'b89584beb89d44d68bce53b39a0849ce', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.064, 'ICIR': 0.271, 'Rank IC': 0.037, 'Rank ICIR': 0.189}, 'data_train_vec': ['2024-09-27', '2026-03-26'], 'train_time_vec': ['2026-09-27', '2026-09-27'], 'rank_icir': '0.189', 'weight': '0.086'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260927_16 930832239348776733 (Recorders: 3/5)

	Recorder: 188a597681a14b7491f03d63ce20deea

		Model: {'id': '188a597681a14b7491f03d63ce20deea', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.011, 'ICIR': 0.049, 'Rank IC': 0.035, 'Rank ICIR': 0.203}, 'data_train_vec': ['2021-09-27', '2025-06-26'], 'train_time_vec': ['2026-09-27', '2026-09-27'], 'rank_icir': '0.203', 'weight': '0.092'}

	Recorder: b9f0e9e4f473484e90533d27b6687b12

		Model: {'id': 'b9f0e9e4f473484e90533d27b6687b12', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.009, 'ICIR': 0.037, 'Rank IC': 0.029, 'Rank ICIR': 0.169}, 'data_train_vec': ['2022-09-27', '2025-09-26'], 'train_time_vec': ['2026-09-27', '2026-09-27'], 'rank_icir': '0.169', 'weight': '0.076'}

	Recorder: a675f11c7f8c4a679a861049f5b57173

		Model: {'id': 'a675f11c7f8c4a679a861049f5b57173', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.036, 'ICIR': 0.143, 'Rank IC': 0.017, 'Rank ICIR': 0.101}, 'data_train_vec': ['2024-09-27', '2026-03-26'], 'train_time_vec': ['2026-09-27', '2026-09-27'], 'rank_icir': '0.101', 'weight': '0.046'}
