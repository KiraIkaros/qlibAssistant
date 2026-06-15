# params 
 {'predict_dates': [{'start': '2026-06-15', 'end': '2026-06-15'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260615_16 904793072365939174 (Recorders: 3/5)

	Recorder: e4a1c2ba85314f94a67ad7cb3afc5fd0

		Model: {'id': 'e4a1c2ba85314f94a67ad7cb3afc5fd0', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.006, 'ICIR': 0.037, 'Rank IC': 0.028, 'Rank ICIR': 0.179}, 'data_train_vec': ['2021-06-15', '2025-03-14'], 'train_time_vec': ['2026-06-15', '2026-06-15'], 'rank_icir': '0.179', 'weight': '0.041'}

	Recorder: 8e0da145d037401a92c4d5f4a0c60b41

		Model: {'id': '8e0da145d037401a92c4d5f4a0c60b41', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.016, 'ICIR': 0.139, 'Rank IC': 0.035, 'Rank ICIR': 0.218}, 'data_train_vec': ['2023-06-15', '2025-09-14'], 'train_time_vec': ['2026-06-15', '2026-06-15'], 'rank_icir': '0.218', 'weight': '0.050'}

	Recorder: 808bee0e88954e2b8d406d12d1ecd649

		Model: {'id': '808bee0e88954e2b8d406d12d1ecd649', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.013, 'ICIR': 0.127, 'Rank IC': 0.035, 'Rank ICIR': 0.333}, 'data_train_vec': ['2024-06-15', '2025-12-14'], 'train_time_vec': ['2026-06-15', '2026-06-15'], 'rank_icir': '0.333', 'weight': '0.076'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260615_16 445107700356273181 (Recorders: 4/5)

	Recorder: 1cbce367e9dc416ba1eeb34d1d7cfe93

		Model: {'id': '1cbce367e9dc416ba1eeb34d1d7cfe93', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.002, 'ICIR': 0.019, 'Rank IC': 0.022, 'Rank ICIR': 0.151}, 'data_train_vec': ['2021-06-15', '2025-03-14'], 'train_time_vec': ['2026-06-15', '2026-06-15'], 'rank_icir': '0.151', 'weight': '0.034'}

	Recorder: 05a2d34b8c39490fae20c0c4aa192072

		Model: {'id': '05a2d34b8c39490fae20c0c4aa192072', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.005, 'ICIR': 0.033, 'Rank IC': 0.036, 'Rank ICIR': 0.278}, 'data_train_vec': ['2022-06-15', '2025-06-14'], 'train_time_vec': ['2026-06-15', '2026-06-15'], 'rank_icir': '0.278', 'weight': '0.063'}

	Recorder: 42e6b93af07848a99a35075d24e438ef

		Model: {'id': '42e6b93af07848a99a35075d24e438ef', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.016, 'ICIR': 0.155, 'Rank IC': 0.032, 'Rank ICIR': 0.253}, 'data_train_vec': ['2023-06-15', '2025-09-14'], 'train_time_vec': ['2026-06-15', '2026-06-15'], 'rank_icir': '0.253', 'weight': '0.058'}

	Recorder: 7a21705555d44415af6e33f6b0c23a44

		Model: {'id': '7a21705555d44415af6e33f6b0c23a44', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.017, 'ICIR': 0.159, 'Rank IC': 0.025, 'Rank ICIR': 0.257}, 'data_train_vec': ['2024-06-15', '2025-12-14'], 'train_time_vec': ['2026-06-15', '2026-06-15'], 'rank_icir': '0.257', 'weight': '0.059'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260615_13 111373813740810999 (Recorders: 4/5)

	Recorder: e125ada04dde4e70aee517ef7ba44159

		Model: {'id': 'e125ada04dde4e70aee517ef7ba44159', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.023, 'ICIR': 0.148, 'Rank IC': 0.05, 'Rank ICIR': 0.324}, 'data_train_vec': ['2021-06-15', '2025-03-14'], 'train_time_vec': ['2026-06-15', '2026-06-15'], 'rank_icir': '0.324', 'weight': '0.074'}

	Recorder: 522dbf58d1b24817b990bf70a33187e2

		Model: {'id': '522dbf58d1b24817b990bf70a33187e2', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.024, 'ICIR': 0.156, 'Rank IC': 0.051, 'Rank ICIR': 0.305}, 'data_train_vec': ['2022-06-15', '2025-06-14'], 'train_time_vec': ['2026-06-15', '2026-06-15'], 'rank_icir': '0.305', 'weight': '0.070'}

	Recorder: f48ae9a937b748f784931358b8bd6678

		Model: {'id': 'f48ae9a937b748f784931358b8bd6678', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.021, 'ICIR': 0.164, 'Rank IC': 0.035, 'Rank ICIR': 0.244}, 'data_train_vec': ['2023-06-15', '2025-09-14'], 'train_time_vec': ['2026-06-15', '2026-06-15'], 'rank_icir': '0.244', 'weight': '0.056'}

	Recorder: ea21d09f22bb42759f30f026fa80cada

		Model: {'id': 'ea21d09f22bb42759f30f026fa80cada', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.012, 'ICIR': 0.093, 'Rank IC': 0.021, 'Rank ICIR': 0.192}, 'data_train_vec': ['2024-06-15', '2025-12-14'], 'train_time_vec': ['2026-06-15', '2026-06-15'], 'rank_icir': '0.192', 'weight': '0.044'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260615_13 836897872836846652 (Recorders: 4/5)

	Recorder: 56862a5131574d9c99761bc33032397e

		Model: {'id': '56862a5131574d9c99761bc33032397e', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.016, 'ICIR': 0.115, 'Rank IC': 0.043, 'Rank ICIR': 0.363}, 'data_train_vec': ['2021-06-15', '2025-03-14'], 'train_time_vec': ['2026-06-15', '2026-06-15'], 'rank_icir': '0.363', 'weight': '0.083'}

	Recorder: 7c53d98168d04ea5a402a7c2d00c2a33

		Model: {'id': '7c53d98168d04ea5a402a7c2d00c2a33', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.007, 'ICIR': 0.044, 'Rank IC': 0.043, 'Rank ICIR': 0.317}, 'data_train_vec': ['2022-06-15', '2025-06-14'], 'train_time_vec': ['2026-06-15', '2026-06-15'], 'rank_icir': '0.317', 'weight': '0.072'}

	Recorder: 826176ee6a6b4b7dadf99ff2fb66c433

		Model: {'id': '826176ee6a6b4b7dadf99ff2fb66c433', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.009, 'ICIR': 0.081, 'Rank IC': 0.034, 'Rank ICIR': 0.291}, 'data_train_vec': ['2023-06-15', '2025-09-14'], 'train_time_vec': ['2026-06-15', '2026-06-15'], 'rank_icir': '0.291', 'weight': '0.066'}

	Recorder: 906cf1c5a312457b964daa71b1da2178

		Model: {'id': '906cf1c5a312457b964daa71b1da2178', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.016, 'ICIR': 0.102, 'Rank IC': 0.022, 'Rank ICIR': 0.158}, 'data_train_vec': ['2024-06-15', '2025-12-14'], 'train_time_vec': ['2026-06-15', '2026-06-15'], 'rank_icir': '0.158', 'weight': '0.036'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260615_13 718464182076631175 (Recorders: 2/5)

	Recorder: f37b45301a6944afbce7d0559b66cfda

		Model: {'id': 'f37b45301a6944afbce7d0559b66cfda', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.005, 'ICIR': 0.034, 'Rank IC': 0.039, 'Rank ICIR': 0.239}, 'data_train_vec': ['2021-06-15', '2025-03-14'], 'train_time_vec': ['2026-06-15', '2026-06-15'], 'rank_icir': '0.239', 'weight': '0.054'}

	Recorder: b9ec87cefcf046658a1aac5aa50f80e6

		Model: {'id': 'b9ec87cefcf046658a1aac5aa50f80e6', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.019, 'ICIR': 0.143, 'Rank IC': 0.048, 'Rank ICIR': 0.284}, 'data_train_vec': ['2022-06-15', '2025-06-14'], 'train_time_vec': ['2026-06-15', '2026-06-15'], 'rank_icir': '0.284', 'weight': '0.065'}
