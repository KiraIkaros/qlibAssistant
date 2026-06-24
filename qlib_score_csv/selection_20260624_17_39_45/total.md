# params 
 {'predict_dates': [{'start': '2026-06-24', 'end': '2026-06-24'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260624_17 839579194973750728 (Recorders: 2/5)

	Recorder: 9231479c120848fe8e31f06f386dd64b

		Model: {'id': '9231479c120848fe8e31f06f386dd64b', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.026, 'ICIR': 0.224, 'Rank IC': 0.029, 'Rank ICIR': 0.222}, 'data_train_vec': ['2023-06-24', '2025-09-23'], 'train_time_vec': ['2026-06-24', '2026-06-24'], 'rank_icir': '0.222', 'weight': '0.118'}

	Recorder: 9fdcebb4411c40829e15c4fa0aa6f438

		Model: {'id': '9fdcebb4411c40829e15c4fa0aa6f438', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.018, 'ICIR': 0.183, 'Rank IC': 0.018, 'Rank ICIR': 0.185}, 'data_train_vec': ['2024-06-24', '2025-12-23'], 'train_time_vec': ['2026-06-24', '2026-06-24'], 'rank_icir': '0.185', 'weight': '0.098'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260624_17 671506387169510907 (Recorders: 2/5)

	Recorder: f209a5c78ebe4552ad59a6ecfb8c0f43

		Model: {'id': 'f209a5c78ebe4552ad59a6ecfb8c0f43', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.031, 'ICIR': 0.256, 'Rank IC': 0.036, 'Rank ICIR': 0.282}, 'data_train_vec': ['2023-06-24', '2025-09-23'], 'train_time_vec': ['2026-06-24', '2026-06-24'], 'rank_icir': '0.282', 'weight': '0.150'}

	Recorder: b5627fb748054d23bee9b9dfcfc94ab4

		Model: {'id': 'b5627fb748054d23bee9b9dfcfc94ab4', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.032, 'ICIR': 0.219, 'Rank IC': 0.028, 'Rank ICIR': 0.208}, 'data_train_vec': ['2024-06-24', '2025-12-23'], 'train_time_vec': ['2026-06-24', '2026-06-24'], 'rank_icir': '0.208', 'weight': '0.110'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260624_15 680313775325589966 (Recorders: 3/5)

	Recorder: 540f6312905b44de800212b29668a520

		Model: {'id': '540f6312905b44de800212b29668a520', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.014, 'ICIR': 0.081, 'Rank IC': 0.049, 'Rank ICIR': 0.294}, 'data_train_vec': ['2021-06-24', '2025-03-23'], 'train_time_vec': ['2026-06-24', '2026-06-24'], 'rank_icir': '0.294', 'weight': '0.156'}

	Recorder: f11db09f47c448eeabcdbd58bb4a412b

		Model: {'id': 'f11db09f47c448eeabcdbd58bb4a412b', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.017, 'ICIR': 0.102, 'Rank IC': 0.048, 'Rank ICIR': 0.286}, 'data_train_vec': ['2022-06-24', '2025-06-23'], 'train_time_vec': ['2026-06-24', '2026-06-24'], 'rank_icir': '0.286', 'weight': '0.152'}

	Recorder: 4c2d9591e4b84ea5939f8e805b26c6f7

		Model: {'id': '4c2d9591e4b84ea5939f8e805b26c6f7', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.017, 'ICIR': 0.123, 'Rank IC': 0.03, 'Rank ICIR': 0.214}, 'data_train_vec': ['2023-06-24', '2025-09-23'], 'train_time_vec': ['2026-06-24', '2026-06-24'], 'rank_icir': '0.214', 'weight': '0.113'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260624_14 819909021272208600 (Recorders: 2/5)

	Recorder: 195f679841f9491a8ccc675b9bcce947

		Model: {'id': '195f679841f9491a8ccc675b9bcce947', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.004, 'ICIR': 0.033, 'Rank IC': 0.021, 'Rank ICIR': 0.164}, 'data_train_vec': ['2023-06-24', '2025-09-23'], 'train_time_vec': ['2026-06-24', '2026-06-24'], 'rank_icir': '0.164', 'weight': '0.087'}

	Recorder: af97d6b70b9844668f96e13fc1902504

		Model: {'id': 'af97d6b70b9844668f96e13fc1902504', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.007, 'ICIR': 0.042, 'Rank IC': 0.005, 'Rank ICIR': 0.031}, 'data_train_vec': ['2024-06-24', '2025-12-23'], 'train_time_vec': ['2026-06-24', '2026-06-24'], 'rank_icir': '0.031', 'weight': '0.016'}
