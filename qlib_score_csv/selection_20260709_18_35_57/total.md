# params 
 {'predict_dates': [{'start': '2026-07-03', 'end': '2026-07-03'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260709_18 135557531781601621 (Recorders: 4/5)

	Recorder: 24324ae4191e4d03b814a0b2238b3499

		Model: {'id': '24324ae4191e4d03b814a0b2238b3499', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.017, 'ICIR': 0.151, 'Rank IC': 0.027, 'Rank ICIR': 0.207}, 'data_train_vec': ['2022-07-09', '2025-07-08'], 'train_time_vec': ['2026-07-09', '2026-07-09'], 'rank_icir': '0.207', 'weight': '0.055'}

	Recorder: d1654fe83929466992b3ee371281937c

		Model: {'id': 'd1654fe83929466992b3ee371281937c', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.036, 'ICIR': 0.317, 'Rank IC': 0.039, 'Rank ICIR': 0.343}, 'data_train_vec': ['2023-07-09', '2025-10-08'], 'train_time_vec': ['2026-07-09', '2026-07-09'], 'rank_icir': '0.343', 'weight': '0.092'}

	Recorder: 6bb30bfd40a849709708999c97414c2e

		Model: {'id': '6bb30bfd40a849709708999c97414c2e', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.059, 'ICIR': 0.446, 'Rank IC': 0.028, 'Rank ICIR': 0.245}, 'data_train_vec': ['2024-07-09', '2026-01-08'], 'train_time_vec': ['2026-07-09', '2026-07-09'], 'rank_icir': '0.245', 'weight': '0.066'}

	Recorder: a2050bf725184ad3a6f65e1cba155be3

		Model: {'id': 'a2050bf725184ad3a6f65e1cba155be3', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.034, 'ICIR': 0.301, 'Rank IC': 0.016, 'Rank ICIR': 0.082}, 'data_train_vec': ['2025-07-09', '2026-04-08'], 'train_time_vec': ['2026-07-09', '2026-07-09'], 'rank_icir': '0.082', 'weight': '0.022'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260709_18 364883552016465598 (Recorders: 4/5)

	Recorder: d651407ba83544308984d5814badeaad

		Model: {'id': 'd651407ba83544308984d5814badeaad', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.007, 'ICIR': 0.047, 'Rank IC': 0.03, 'Rank ICIR': 0.185}, 'data_train_vec': ['2022-07-09', '2025-07-08'], 'train_time_vec': ['2026-07-09', '2026-07-09'], 'rank_icir': '0.185', 'weight': '0.050'}

	Recorder: 71e6603223dc43a4b368c6bd5d065859

		Model: {'id': '71e6603223dc43a4b368c6bd5d065859', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.034, 'ICIR': 0.294, 'Rank IC': 0.038, 'Rank ICIR': 0.302}, 'data_train_vec': ['2023-07-09', '2025-10-08'], 'train_time_vec': ['2026-07-09', '2026-07-09'], 'rank_icir': '0.302', 'weight': '0.081'}

	Recorder: 27badf1dd9ca458383150f628f2b945c

		Model: {'id': '27badf1dd9ca458383150f628f2b945c', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.015, 'ICIR': 0.112, 'Rank IC': 0.013, 'Rank ICIR': 0.1}, 'data_train_vec': ['2024-07-09', '2026-01-08'], 'train_time_vec': ['2026-07-09', '2026-07-09'], 'rank_icir': '0.100', 'weight': '0.027'}

	Recorder: f77dee07b84c41a0a94a6aff26b92710

		Model: {'id': 'f77dee07b84c41a0a94a6aff26b92710', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.066, 'ICIR': 0.264, 'Rank IC': 0.05, 'Rank ICIR': 0.214}, 'data_train_vec': ['2025-07-09', '2026-04-08'], 'train_time_vec': ['2026-07-09', '2026-07-09'], 'rank_icir': '0.214', 'weight': '0.057'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260709_15 282657192265575837 (Recorders: 4/5)

	Recorder: c4cb9f79a347482dafbde18dc47ee667

		Model: {'id': 'c4cb9f79a347482dafbde18dc47ee667', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.01, 'ICIR': 0.059, 'Rank IC': 0.043, 'Rank ICIR': 0.253}, 'data_train_vec': ['2021-07-09', '2025-04-08'], 'train_time_vec': ['2026-07-09', '2026-07-09'], 'rank_icir': '0.253', 'weight': '0.068'}

	Recorder: 0fd49dd02c90487ca702553a0774c56e

		Model: {'id': '0fd49dd02c90487ca702553a0774c56e', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.029, 'ICIR': 0.197, 'Rank IC': 0.052, 'Rank ICIR': 0.321}, 'data_train_vec': ['2022-07-09', '2025-07-08'], 'train_time_vec': ['2026-07-09', '2026-07-09'], 'rank_icir': '0.321', 'weight': '0.086'}

	Recorder: 8a1436da3f12466dae6d5298f7f8bfea

		Model: {'id': '8a1436da3f12466dae6d5298f7f8bfea', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.031, 'ICIR': 0.243, 'Rank IC': 0.041, 'Rank ICIR': 0.324}, 'data_train_vec': ['2023-07-09', '2025-10-08'], 'train_time_vec': ['2026-07-09', '2026-07-09'], 'rank_icir': '0.324', 'weight': '0.087'}

	Recorder: b0894d80787240b19723b18bedb43d6f

		Model: {'id': 'b0894d80787240b19723b18bedb43d6f', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.037, 'ICIR': 0.181, 'Rank IC': 0.032, 'Rank ICIR': 0.176}, 'data_train_vec': ['2025-07-09', '2026-04-08'], 'train_time_vec': ['2026-07-09', '2026-07-09'], 'rank_icir': '0.176', 'weight': '0.047'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260709_15 863262847043256759 (Recorders: 2/5)

	Recorder: 104ff3c6ee9043fd97f05cb55226e80a

		Model: {'id': '104ff3c6ee9043fd97f05cb55226e80a', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.012, 'ICIR': 0.082, 'Rank IC': 0.023, 'Rank ICIR': 0.171}, 'data_train_vec': ['2023-07-09', '2025-10-08'], 'train_time_vec': ['2026-07-09', '2026-07-09'], 'rank_icir': '0.171', 'weight': '0.046'}

	Recorder: 93a3fbfc865f45e893146b9a4e6ce72f

		Model: {'id': '93a3fbfc865f45e893146b9a4e6ce72f', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.05, 'ICIR': 0.264, 'Rank IC': 0.032, 'Rank ICIR': 0.189}, 'data_train_vec': ['2025-07-09', '2026-04-08'], 'train_time_vec': ['2026-07-09', '2026-07-09'], 'rank_icir': '0.189', 'weight': '0.051'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260709_15 361292300044548261 (Recorders: 3/5)

	Recorder: 31786aad7d1748f09669c0b6a4bc883b

		Model: {'id': '31786aad7d1748f09669c0b6a4bc883b', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.003, 'ICIR': 0.02, 'Rank IC': 0.043, 'Rank ICIR': 0.273}, 'data_train_vec': ['2022-07-09', '2025-07-08'], 'train_time_vec': ['2026-07-09', '2026-07-09'], 'rank_icir': '0.273', 'weight': '0.073'}

	Recorder: d0a92cc4811948208fc7899eb5eb83cd

		Model: {'id': 'd0a92cc4811948208fc7899eb5eb83cd', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.01, 'ICIR': 0.081, 'Rank IC': 0.034, 'Rank ICIR': 0.263}, 'data_train_vec': ['2023-07-09', '2025-10-08'], 'train_time_vec': ['2026-07-09', '2026-07-09'], 'rank_icir': '0.263', 'weight': '0.070'}

	Recorder: cf547dfe5f3d4408a7e8942542c1dc65

		Model: {'id': 'cf547dfe5f3d4408a7e8942542c1dc65', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.003, 'ICIR': 0.027, 'Rank IC': 0.01, 'Rank ICIR': 0.085}, 'data_train_vec': ['2024-07-09', '2026-01-08'], 'train_time_vec': ['2026-07-09', '2026-07-09'], 'rank_icir': '0.085', 'weight': '0.023'}
