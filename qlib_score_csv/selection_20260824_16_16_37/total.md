# params 
 {'predict_dates': [{'start': '2026-08-24', 'end': '2026-08-24'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260824_15 388117208898321264 (Recorders: 1/5)

	Recorder: 00981bcdeafe478f86f604225ac4c3a3

		Model: {'id': '00981bcdeafe478f86f604225ac4c3a3', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.002, 'ICIR': 0.01, 'Rank IC': 0.023, 'Rank ICIR': 0.164}, 'data_train_vec': ['2022-08-24', '2025-08-23'], 'train_time_vec': ['2026-08-24', '2026-08-24'], 'rank_icir': '0.164', 'weight': '0.109'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260824_15 603215454633775598 (Recorders: 1/5)

	Recorder: 03349870b7ef45b48f4f8858f404aa8d

		Model: {'id': '03349870b7ef45b48f4f8858f404aa8d', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.006, 'ICIR': 0.059, 'Rank IC': 0.01, 'Rank ICIR': 0.083}, 'data_train_vec': ['2023-08-24', '2025-11-23'], 'train_time_vec': ['2026-08-24', '2026-08-24'], 'rank_icir': '0.083', 'weight': '0.055'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260824_13 467214019303826881 (Recorders: 3/5)

	Recorder: 464397b78200470c8d82ef064cb7ffaf

		Model: {'id': '464397b78200470c8d82ef064cb7ffaf', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.017, 'ICIR': 0.085, 'Rank IC': 0.03, 'Rank ICIR': 0.177}, 'data_train_vec': ['2021-08-24', '2025-05-23'], 'train_time_vec': ['2026-08-24', '2026-08-24'], 'rank_icir': '0.177', 'weight': '0.118'}

	Recorder: 82cd972c3d5a4432a28a25aa4962b2bb

		Model: {'id': '82cd972c3d5a4432a28a25aa4962b2bb', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.019, 'ICIR': 0.083, 'Rank IC': 0.029, 'Rank ICIR': 0.17}, 'data_train_vec': ['2022-08-24', '2025-08-23'], 'train_time_vec': ['2026-08-24', '2026-08-24'], 'rank_icir': '0.170', 'weight': '0.113'}

	Recorder: 11aae99afab24b9fa774c2084bfea14c

		Model: {'id': '11aae99afab24b9fa774c2084bfea14c', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.007, 'ICIR': 0.029, 'Rank IC': 0.014, 'Rank ICIR': 0.076}, 'data_train_vec': ['2023-08-24', '2025-11-23'], 'train_time_vec': ['2026-08-24', '2026-08-24'], 'rank_icir': '0.076', 'weight': '0.051'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260824_13 415476200921430339 (Recorders: 4/5)

	Recorder: b5f9a0bc0a264a639e0d4375a1c79f5b

		Model: {'id': 'b5f9a0bc0a264a639e0d4375a1c79f5b', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.011, 'ICIR': 0.056, 'Rank IC': 0.024, 'Rank ICIR': 0.148}, 'data_train_vec': ['2021-08-24', '2025-05-23'], 'train_time_vec': ['2026-08-24', '2026-08-24'], 'rank_icir': '0.148', 'weight': '0.098'}

	Recorder: 12835b8b25264ccb82d292bab30b69c2

		Model: {'id': '12835b8b25264ccb82d292bab30b69c2', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.031, 'ICIR': 0.159, 'Rank IC': 0.035, 'Rank ICIR': 0.218}, 'data_train_vec': ['2022-08-24', '2025-08-23'], 'train_time_vec': ['2026-08-24', '2026-08-24'], 'rank_icir': '0.218', 'weight': '0.145'}

	Recorder: 1404c891e4e5494dae7a60d73815cec6

		Model: {'id': '1404c891e4e5494dae7a60d73815cec6', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.029, 'ICIR': 0.089, 'Rank IC': 0.016, 'Rank ICIR': 0.061}, 'data_train_vec': ['2024-08-24', '2026-02-23'], 'train_time_vec': ['2026-08-24', '2026-08-24'], 'rank_icir': '0.061', 'weight': '0.041'}

	Recorder: 380855c7ebc04ac78aa77c4dec990f68

		Model: {'id': '380855c7ebc04ac78aa77c4dec990f68', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.038, 'ICIR': 0.145, 'Rank IC': 0.02, 'Rank ICIR': 0.107}, 'data_train_vec': ['2025-08-24', '2026-05-23'], 'train_time_vec': ['2026-08-24', '2026-08-24'], 'rank_icir': '0.107', 'weight': '0.071'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260824_13 421444981244255362 (Recorders: 3/5)

	Recorder: c955fc2638ce4bbd85dc8b3abeb000c0

		Model: {'id': 'c955fc2638ce4bbd85dc8b3abeb000c0', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.003, 'ICIR': 0.012, 'Rank IC': 0.023, 'Rank ICIR': 0.132}, 'data_train_vec': ['2021-08-24', '2025-05-23'], 'train_time_vec': ['2026-08-24', '2026-08-24'], 'rank_icir': '0.132', 'weight': '0.088'}

	Recorder: 0d422b110e624fc2ab3f053183dd6e79

		Model: {'id': '0d422b110e624fc2ab3f053183dd6e79', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.004, 'ICIR': 0.014, 'Rank IC': 0.019, 'Rank ICIR': 0.113}, 'data_train_vec': ['2023-08-24', '2025-11-23'], 'train_time_vec': ['2026-08-24', '2026-08-24'], 'rank_icir': '0.113', 'weight': '0.075'}

	Recorder: 5aef738650614b7699012c81ded25d7f

		Model: {'id': '5aef738650614b7699012c81ded25d7f', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.03, 'ICIR': 0.082, 'Rank IC': 0.013, 'Rank ICIR': 0.055}, 'data_train_vec': ['2025-08-24', '2026-05-23'], 'train_time_vec': ['2026-08-24', '2026-08-24'], 'rank_icir': '0.055', 'weight': '0.037'}
