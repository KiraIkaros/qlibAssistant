# params 
 {'predict_dates': [{'start': '2026-09-10', 'end': '2026-09-10'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260910_18 279928158355692297 (Recorders: 2/5)

	Recorder: 924c0d3ef586466290e63b6cff5e3aa5

		Model: {'id': '924c0d3ef586466290e63b6cff5e3aa5', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.035, 'ICIR': 0.17, 'Rank IC': 0.044, 'Rank ICIR': 0.282}, 'data_train_vec': ['2022-09-10', '2025-09-09'], 'train_time_vec': ['2026-09-10', '2026-09-10'], 'rank_icir': '0.282', 'weight': '0.128'}

	Recorder: 00e1313e2c7c449bbc67e564c26f7b84

		Model: {'id': '00e1313e2c7c449bbc67e564c26f7b84', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.011, 'ICIR': 0.04, 'Rank IC': 0.015, 'Rank ICIR': 0.083}, 'data_train_vec': ['2023-09-10', '2025-12-09'], 'train_time_vec': ['2026-09-10', '2026-09-10'], 'rank_icir': '0.083', 'weight': '0.038'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260910_18 862485093784778153 (Recorders: 3/5)

	Recorder: 2814f31946874eb3977fbc22c65183bc

		Model: {'id': '2814f31946874eb3977fbc22c65183bc', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.019, 'ICIR': 0.134, 'Rank IC': 0.027, 'Rank ICIR': 0.185}, 'data_train_vec': ['2021-09-10', '2025-06-09'], 'train_time_vec': ['2026-09-10', '2026-09-10'], 'rank_icir': '0.185', 'weight': '0.084'}

	Recorder: 1123bb9714e44c8da8c4e973635ab98f

		Model: {'id': '1123bb9714e44c8da8c4e973635ab98f', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.021, 'ICIR': 0.144, 'Rank IC': 0.032, 'Rank ICIR': 0.245}, 'data_train_vec': ['2022-09-10', '2025-09-09'], 'train_time_vec': ['2026-09-10', '2026-09-10'], 'rank_icir': '0.245', 'weight': '0.111'}

	Recorder: 4a2824c5837b413d801ca2b084dacf28

		Model: {'id': '4a2824c5837b413d801ca2b084dacf28', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.008, 'ICIR': 0.048, 'Rank IC': 0.008, 'Rank ICIR': 0.051}, 'data_train_vec': ['2023-09-10', '2025-12-09'], 'train_time_vec': ['2026-09-10', '2026-09-10'], 'rank_icir': '0.051', 'weight': '0.023'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260910_16 387296031060311954 (Recorders: 3/5)

	Recorder: 508b92f99858444e8c4e49b3ec4a7376

		Model: {'id': '508b92f99858444e8c4e49b3ec4a7376', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.025, 'ICIR': 0.122, 'Rank IC': 0.038, 'Rank ICIR': 0.221}, 'data_train_vec': ['2021-09-10', '2025-06-09'], 'train_time_vec': ['2026-09-10', '2026-09-10'], 'rank_icir': '0.221', 'weight': '0.100'}

	Recorder: fc5aa8cc8b6642dd8c3cd01e9d6b2cff

		Model: {'id': 'fc5aa8cc8b6642dd8c3cd01e9d6b2cff', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.031, 'ICIR': 0.142, 'Rank IC': 0.041, 'Rank ICIR': 0.245}, 'data_train_vec': ['2022-09-10', '2025-09-09'], 'train_time_vec': ['2026-09-10', '2026-09-10'], 'rank_icir': '0.245', 'weight': '0.111'}

	Recorder: 06bb930c7b95494c9dc44363bcd43970

		Model: {'id': '06bb930c7b95494c9dc44363bcd43970', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.012, 'ICIR': 0.044, 'Rank IC': 0.015, 'Rank ICIR': 0.077}, 'data_train_vec': ['2023-09-10', '2025-12-09'], 'train_time_vec': ['2026-09-10', '2026-09-10'], 'rank_icir': '0.077', 'weight': '0.035'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260910_16 496929044089565987 (Recorders: 5/5)

	Recorder: 763bd051259f48b18998d3926d8cc817

		Model: {'id': '763bd051259f48b18998d3926d8cc817', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.025, 'ICIR': 0.12, 'Rank IC': 0.033, 'Rank ICIR': 0.196}, 'data_train_vec': ['2021-09-10', '2025-06-09'], 'train_time_vec': ['2026-09-10', '2026-09-10'], 'rank_icir': '0.196', 'weight': '0.089'}

	Recorder: 7991066acb9b422794f563e679958528

		Model: {'id': '7991066acb9b422794f563e679958528', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.037, 'ICIR': 0.192, 'Rank IC': 0.033, 'Rank ICIR': 0.206}, 'data_train_vec': ['2022-09-10', '2025-09-09'], 'train_time_vec': ['2026-09-10', '2026-09-10'], 'rank_icir': '0.206', 'weight': '0.093'}

	Recorder: fffc32871acf4ab08097b9b49f6f4ce4

		Model: {'id': 'fffc32871acf4ab08097b9b49f6f4ce4', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.011, 'ICIR': 0.043, 'Rank IC': 0.004, 'Rank ICIR': 0.018}, 'data_train_vec': ['2023-09-10', '2025-12-09'], 'train_time_vec': ['2026-09-10', '2026-09-10'], 'rank_icir': '0.018', 'weight': '0.008'}

	Recorder: 80b6ecdb93a14cd0a1c1d115b51c96f4

		Model: {'id': '80b6ecdb93a14cd0a1c1d115b51c96f4', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.025, 'ICIR': 0.078, 'Rank IC': 0.014, 'Rank ICIR': 0.051}, 'data_train_vec': ['2024-09-10', '2026-03-09'], 'train_time_vec': ['2026-09-10', '2026-09-10'], 'rank_icir': '0.051', 'weight': '0.023'}

	Recorder: 0b87fb0d943047efa7c98c7a4a05c8d4

		Model: {'id': '0b87fb0d943047efa7c98c7a4a05c8d4', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.044, 'ICIR': 0.204, 'Rank IC': 0.027, 'Rank ICIR': 0.137}, 'data_train_vec': ['2025-09-10', '2026-06-09'], 'train_time_vec': ['2026-09-10', '2026-09-10'], 'rank_icir': '0.137', 'weight': '0.062'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260910_16 536608437640205542 (Recorders: 1/5)

	Recorder: 8cedf4998d6c4f94bd0b961a5ddfd4dc

		Model: {'id': '8cedf4998d6c4f94bd0b961a5ddfd4dc', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.016, 'ICIR': 0.073, 'Rank IC': 0.033, 'Rank ICIR': 0.21}, 'data_train_vec': ['2022-09-10', '2025-09-09'], 'train_time_vec': ['2026-09-10', '2026-09-10'], 'rank_icir': '0.210', 'weight': '0.095'}
