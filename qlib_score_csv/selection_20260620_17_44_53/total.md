# params 
 {'predict_dates': [{'start': '2026-06-18', 'end': '2026-06-18'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260620_17 615878467617913928 (Recorders: 3/5)

	Recorder: 94df2b93c3a145fb9c59beaf14b3f8a8

		Model: {'id': '94df2b93c3a145fb9c59beaf14b3f8a8', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.008, 'ICIR': 0.061, 'Rank IC': 0.035, 'Rank ICIR': 0.216}, 'data_train_vec': ['2022-06-20', '2025-06-19'], 'train_time_vec': ['2026-06-20', '2026-06-20'], 'rank_icir': '0.216', 'weight': '0.051'}

	Recorder: 9766f280f1a84156bab03da6bb1fdca2

		Model: {'id': '9766f280f1a84156bab03da6bb1fdca2', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.016, 'ICIR': 0.153, 'Rank IC': 0.028, 'Rank ICIR': 0.202}, 'data_train_vec': ['2023-06-20', '2025-09-19'], 'train_time_vec': ['2026-06-20', '2026-06-20'], 'rank_icir': '0.202', 'weight': '0.048'}

	Recorder: 02d12043256349ad996235a1d52aeb8b

		Model: {'id': '02d12043256349ad996235a1d52aeb8b', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.031, 'ICIR': 0.273, 'Rank IC': 0.038, 'Rank ICIR': 0.355}, 'data_train_vec': ['2024-06-20', '2025-12-19'], 'train_time_vec': ['2026-06-20', '2026-06-20'], 'rank_icir': '0.355', 'weight': '0.084'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260620_17 910654241959701435 (Recorders: 4/5)

	Recorder: 22bea0dde95d4ca98dbd9d67a8a99b81

		Model: {'id': '22bea0dde95d4ca98dbd9d67a8a99b81', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.006, 'ICIR': 0.041, 'Rank IC': 0.028, 'Rank ICIR': 0.213}, 'data_train_vec': ['2022-06-20', '2025-06-19'], 'train_time_vec': ['2026-06-20', '2026-06-20'], 'rank_icir': '0.213', 'weight': '0.050'}

	Recorder: 8255cbbf5912429e974de4d9c1887ea6

		Model: {'id': '8255cbbf5912429e974de4d9c1887ea6', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.029, 'ICIR': 0.249, 'Rank IC': 0.038, 'Rank ICIR': 0.304}, 'data_train_vec': ['2023-06-20', '2025-09-19'], 'train_time_vec': ['2026-06-20', '2026-06-20'], 'rank_icir': '0.304', 'weight': '0.072'}

	Recorder: 4222a944c19f4155b2d93a72b0640380

		Model: {'id': '4222a944c19f4155b2d93a72b0640380', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.039, 'ICIR': 0.304, 'Rank IC': 0.041, 'Rank ICIR': 0.339}, 'data_train_vec': ['2024-06-20', '2025-12-19'], 'train_time_vec': ['2026-06-20', '2026-06-20'], 'rank_icir': '0.339', 'weight': '0.080'}

	Recorder: 164ca849b3cc41a1a3dd6db3e8c9e851

		Model: {'id': '164ca849b3cc41a1a3dd6db3e8c9e851', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.052, 'ICIR': 0.195, 'Rank IC': 0.02, 'Rank ICIR': 0.083}, 'data_train_vec': ['2025-06-20', '2026-03-19'], 'train_time_vec': ['2026-06-20', '2026-06-20'], 'rank_icir': '0.083', 'weight': '0.020'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260620_14 970847930107741005 (Recorders: 4/5)

	Recorder: 82579d7053a94a76a5493710aead4099

		Model: {'id': '82579d7053a94a76a5493710aead4099', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.017, 'ICIR': 0.101, 'Rank IC': 0.048, 'Rank ICIR': 0.286}, 'data_train_vec': ['2021-06-20', '2025-03-19'], 'train_time_vec': ['2026-06-20', '2026-06-20'], 'rank_icir': '0.286', 'weight': '0.068'}

	Recorder: b02167027d05421c8a0e55c0d66333ac

		Model: {'id': 'b02167027d05421c8a0e55c0d66333ac', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.021, 'ICIR': 0.131, 'Rank IC': 0.052, 'Rank ICIR': 0.307}, 'data_train_vec': ['2022-06-20', '2025-06-19'], 'train_time_vec': ['2026-06-20', '2026-06-20'], 'rank_icir': '0.307', 'weight': '0.072'}

	Recorder: f316b3160223450794453111d17aa999

		Model: {'id': 'f316b3160223450794453111d17aa999', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.024, 'ICIR': 0.182, 'Rank IC': 0.037, 'Rank ICIR': 0.26}, 'data_train_vec': ['2023-06-20', '2025-09-19'], 'train_time_vec': ['2026-06-20', '2026-06-20'], 'rank_icir': '0.260', 'weight': '0.061'}

	Recorder: ec3b8743f3e14b0bb97076d2b02f099e

		Model: {'id': 'ec3b8743f3e14b0bb97076d2b02f099e', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.028, 'ICIR': 0.206, 'Rank IC': 0.029, 'Rank ICIR': 0.225}, 'data_train_vec': ['2024-06-20', '2025-12-19'], 'train_time_vec': ['2026-06-20', '2026-06-20'], 'rank_icir': '0.225', 'weight': '0.053'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260620_14 843827456706988396 (Recorders: 3/5)

	Recorder: 7570deaecf084ab1a009ff8ca390c7e2

		Model: {'id': '7570deaecf084ab1a009ff8ca390c7e2', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.003, 'ICIR': 0.02, 'Rank IC': 0.036, 'Rank ICIR': 0.28}, 'data_train_vec': ['2021-06-20', '2025-03-19'], 'train_time_vec': ['2026-06-20', '2026-06-20'], 'rank_icir': '0.280', 'weight': '0.066'}

	Recorder: 1a890bb6a1a04b5fa8cc9ebebc5fc8e7

		Model: {'id': '1a890bb6a1a04b5fa8cc9ebebc5fc8e7', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.006, 'ICIR': 0.05, 'Rank IC': 0.023, 'Rank ICIR': 0.185}, 'data_train_vec': ['2023-06-20', '2025-09-19'], 'train_time_vec': ['2026-06-20', '2026-06-20'], 'rank_icir': '0.185', 'weight': '0.044'}

	Recorder: 7d55de04e00e491d9d148e843a182c7a

		Model: {'id': '7d55de04e00e491d9d148e843a182c7a', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.023, 'ICIR': 0.143, 'Rank IC': 0.021, 'Rank ICIR': 0.137}, 'data_train_vec': ['2024-06-20', '2025-12-19'], 'train_time_vec': ['2026-06-20', '2026-06-20'], 'rank_icir': '0.137', 'weight': '0.032'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260620_14 631897654159108251 (Recorders: 3/5)

	Recorder: d7c6c0b33273499bbd6437b7d190c391

		Model: {'id': 'd7c6c0b33273499bbd6437b7d190c391', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.005, 'ICIR': 0.034, 'Rank IC': 0.042, 'Rank ICIR': 0.237}, 'data_train_vec': ['2021-06-20', '2025-03-19'], 'train_time_vec': ['2026-06-20', '2026-06-20'], 'rank_icir': '0.237', 'weight': '0.056'}

	Recorder: a50e338698914069a08d976c31cd017c

		Model: {'id': 'a50e338698914069a08d976c31cd017c', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.004, 'ICIR': 0.03, 'Rank IC': 0.044, 'Rank ICIR': 0.254}, 'data_train_vec': ['2022-06-20', '2025-06-19'], 'train_time_vec': ['2026-06-20', '2026-06-20'], 'rank_icir': '0.254', 'weight': '0.060'}

	Recorder: 2f7c955a303b4e4ab0b8ddf6ca4daf75

		Model: {'id': '2f7c955a303b4e4ab0b8ddf6ca4daf75', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.024, 'ICIR': 0.196, 'Rank IC': 0.035, 'Rank ICIR': 0.353}, 'data_train_vec': ['2024-06-20', '2025-12-19'], 'train_time_vec': ['2026-06-20', '2026-06-20'], 'rank_icir': '0.353', 'weight': '0.083'}
