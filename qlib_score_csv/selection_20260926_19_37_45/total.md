# params 
 {'predict_dates': [{'start': '2026-09-24', 'end': '2026-09-24'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260926_19 313537235425465986 (Recorders: 2/5)

	Recorder: eb05ecbca03745efbdaf3ff8f7e2fe1f

		Model: {'id': 'eb05ecbca03745efbdaf3ff8f7e2fe1f', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.013, 'ICIR': 0.091, 'Rank IC': 0.023, 'Rank ICIR': 0.143}, 'data_train_vec': ['2021-09-26', '2025-06-25'], 'train_time_vec': ['2026-09-26', '2026-09-26'], 'rank_icir': '0.143', 'weight': '0.067'}

	Recorder: 4601a1614aa94e489cfe76441ec8ff6e

		Model: {'id': '4601a1614aa94e489cfe76441ec8ff6e', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.017, 'ICIR': 0.066, 'Rank IC': 0.017, 'Rank ICIR': 0.089}, 'data_train_vec': ['2022-09-26', '2025-09-25'], 'train_time_vec': ['2026-09-26', '2026-09-26'], 'rank_icir': '0.089', 'weight': '0.042'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260926_18 259146719053059104 (Recorders: 3/5)

	Recorder: 5eefb6380858429cb5520ce94d0b80ef

		Model: {'id': '5eefb6380858429cb5520ce94d0b80ef', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.022, 'ICIR': 0.144, 'Rank IC': 0.031, 'Rank ICIR': 0.199}, 'data_train_vec': ['2021-09-26', '2025-06-25'], 'train_time_vec': ['2026-09-26', '2026-09-26'], 'rank_icir': '0.199', 'weight': '0.093'}

	Recorder: 036999d4ce9b459087f6e30576c08397

		Model: {'id': '036999d4ce9b459087f6e30576c08397', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.026, 'ICIR': 0.134, 'Rank IC': 0.034, 'Rank ICIR': 0.198}, 'data_train_vec': ['2022-09-26', '2025-09-25'], 'train_time_vec': ['2026-09-26', '2026-09-26'], 'rank_icir': '0.198', 'weight': '0.092'}

	Recorder: 232cc8fbb4e7416b8bd40e6fb8d3d499

		Model: {'id': '232cc8fbb4e7416b8bd40e6fb8d3d499', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.005, 'ICIR': 0.025, 'Rank IC': 0.008, 'Rank ICIR': 0.041}, 'data_train_vec': ['2023-09-26', '2025-12-25'], 'train_time_vec': ['2026-09-26', '2026-09-26'], 'rank_icir': '0.041', 'weight': '0.019'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260926_16 242306693253638578 (Recorders: 4/5)

	Recorder: ec33df4fdec94d8e99729f5a8ba20bea

		Model: {'id': 'ec33df4fdec94d8e99729f5a8ba20bea', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.033, 'ICIR': 0.17, 'Rank IC': 0.044, 'Rank ICIR': 0.254}, 'data_train_vec': ['2021-09-26', '2025-06-25'], 'train_time_vec': ['2026-09-26', '2026-09-26'], 'rank_icir': '0.254', 'weight': '0.119'}

	Recorder: 5e86025a8dee440e9b4931cc99e7651b

		Model: {'id': '5e86025a8dee440e9b4931cc99e7651b', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.025, 'ICIR': 0.111, 'Rank IC': 0.031, 'Rank ICIR': 0.176}, 'data_train_vec': ['2022-09-26', '2025-09-25'], 'train_time_vec': ['2026-09-26', '2026-09-26'], 'rank_icir': '0.176', 'weight': '0.082'}

	Recorder: 51e30a96968e49d2982dc15d355ee129

		Model: {'id': '51e30a96968e49d2982dc15d355ee129', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.003, 'ICIR': 0.011, 'Rank IC': 0.005, 'Rank ICIR': 0.021}, 'data_train_vec': ['2023-09-26', '2025-12-25'], 'train_time_vec': ['2026-09-26', '2026-09-26'], 'rank_icir': '0.021', 'weight': '0.010'}

	Recorder: 80930acc7f48413ebe7aaee5c3f44542

		Model: {'id': '80930acc7f48413ebe7aaee5c3f44542', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.024, 'ICIR': 0.11, 'Rank IC': 0.001, 'Rank ICIR': 0.008}, 'data_train_vec': ['2024-09-26', '2026-03-25'], 'train_time_vec': ['2026-09-26', '2026-09-26'], 'rank_icir': '0.008', 'weight': '0.004'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260926_16 399551430734304038 (Recorders: 4/5)

	Recorder: d2134bf153504a1492f99fbe114880b9

		Model: {'id': 'd2134bf153504a1492f99fbe114880b9', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.03, 'ICIR': 0.149, 'Rank IC': 0.034, 'Rank ICIR': 0.199}, 'data_train_vec': ['2021-09-26', '2025-06-25'], 'train_time_vec': ['2026-09-26', '2026-09-26'], 'rank_icir': '0.199', 'weight': '0.093'}

	Recorder: 66f206441aed4df1ba0a3ee4875a4955

		Model: {'id': '66f206441aed4df1ba0a3ee4875a4955', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.027, 'ICIR': 0.127, 'Rank IC': 0.018, 'Rank ICIR': 0.099}, 'data_train_vec': ['2022-09-26', '2025-09-25'], 'train_time_vec': ['2026-09-26', '2026-09-26'], 'rank_icir': '0.099', 'weight': '0.046'}

	Recorder: 5699c5378e404f9ca4c1ab762539f7aa

		Model: {'id': '5699c5378e404f9ca4c1ab762539f7aa', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.01, 'ICIR': 0.039, 'Rank IC': 0.003, 'Rank ICIR': 0.014}, 'data_train_vec': ['2023-09-26', '2025-12-25'], 'train_time_vec': ['2026-09-26', '2026-09-26'], 'rank_icir': '0.014', 'weight': '0.007'}

	Recorder: 35ee1bc4ef4343ed933cd79bd1d71dc1

		Model: {'id': '35ee1bc4ef4343ed933cd79bd1d71dc1', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.062, 'ICIR': 0.259, 'Rank IC': 0.034, 'Rank ICIR': 0.171}, 'data_train_vec': ['2024-09-26', '2026-03-25'], 'train_time_vec': ['2026-09-26', '2026-09-26'], 'rank_icir': '0.171', 'weight': '0.080'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260926_16 395601216060995300 (Recorders: 3/5)

	Recorder: 953f508995ff41958a9b83bb2ef70509

		Model: {'id': '953f508995ff41958a9b83bb2ef70509', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.009, 'ICIR': 0.042, 'Rank IC': 0.033, 'Rank ICIR': 0.194}, 'data_train_vec': ['2021-09-26', '2025-06-25'], 'train_time_vec': ['2026-09-26', '2026-09-26'], 'rank_icir': '0.194', 'weight': '0.091'}

	Recorder: 9e9247ee6a5644ed9c0302eeea6e41be

		Model: {'id': '9e9247ee6a5644ed9c0302eeea6e41be', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.003, 'ICIR': 0.013, 'Rank IC': 0.021, 'Rank ICIR': 0.125}, 'data_train_vec': ['2022-09-26', '2025-09-25'], 'train_time_vec': ['2026-09-26', '2026-09-26'], 'rank_icir': '0.125', 'weight': '0.058'}

	Recorder: c8922db3449a4842a92398575cb8a6e8

		Model: {'id': 'c8922db3449a4842a92398575cb8a6e8', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.062, 'ICIR': 0.254, 'Rank IC': 0.03, 'Rank ICIR': 0.21}, 'data_train_vec': ['2024-09-26', '2026-03-25'], 'train_time_vec': ['2026-09-26', '2026-09-26'], 'rank_icir': '0.210', 'weight': '0.098'}
