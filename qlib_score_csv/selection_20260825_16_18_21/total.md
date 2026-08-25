# params 
 {'predict_dates': [{'start': '2026-08-25', 'end': '2026-08-25'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260825_15 319617897661874673 (Recorders: 1/5)

	Recorder: 4bdfd04c0c714dd486d29847d8ef37ca

		Model: {'id': '4bdfd04c0c714dd486d29847d8ef37ca', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.003, 'ICIR': 0.012, 'Rank IC': 0.02, 'Rank ICIR': 0.142}, 'data_train_vec': ['2023-08-25', '2025-11-24'], 'train_time_vec': ['2026-08-25', '2026-08-25'], 'rank_icir': '0.142', 'weight': '0.094'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260825_15 916670412775375696 (Recorders: 2/5)

	Recorder: 2f8cf38500564a5f8eeda73a0e4328d9

		Model: {'id': '2f8cf38500564a5f8eeda73a0e4328d9', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.008, 'ICIR': 0.056, 'Rank IC': 0.02, 'Rank ICIR': 0.136}, 'data_train_vec': ['2021-08-25', '2025-05-24'], 'train_time_vec': ['2026-08-25', '2026-08-25'], 'rank_icir': '0.136', 'weight': '0.090'}

	Recorder: c5df846be35e4a129b7d6e605ae245f7

		Model: {'id': 'c5df846be35e4a129b7d6e605ae245f7', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.008, 'ICIR': 0.066, 'Rank IC': 0.011, 'Rank ICIR': 0.091}, 'data_train_vec': ['2023-08-25', '2025-11-24'], 'train_time_vec': ['2026-08-25', '2026-08-25'], 'rank_icir': '0.091', 'weight': '0.060'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260825_13 488863562053188549 (Recorders: 4/5)

	Recorder: 1c1d8517520841e4a2dd42c9a3c86b30

		Model: {'id': '1c1d8517520841e4a2dd42c9a3c86b30', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.015, 'ICIR': 0.073, 'Rank IC': 0.027, 'Rank ICIR': 0.156}, 'data_train_vec': ['2021-08-25', '2025-05-24'], 'train_time_vec': ['2026-08-25', '2026-08-25'], 'rank_icir': '0.156', 'weight': '0.103'}

	Recorder: 4b59f2988cff4c3db11101b58516b7cf

		Model: {'id': '4b59f2988cff4c3db11101b58516b7cf', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.028, 'ICIR': 0.125, 'Rank IC': 0.035, 'Rank ICIR': 0.203}, 'data_train_vec': ['2022-08-25', '2025-08-24'], 'train_time_vec': ['2026-08-25', '2026-08-25'], 'rank_icir': '0.203', 'weight': '0.134'}

	Recorder: d11178bc103248debeb1105954fca226

		Model: {'id': 'd11178bc103248debeb1105954fca226', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.004, 'ICIR': 0.016, 'Rank IC': 0.01, 'Rank ICIR': 0.054}, 'data_train_vec': ['2023-08-25', '2025-11-24'], 'train_time_vec': ['2026-08-25', '2026-08-25'], 'rank_icir': '0.054', 'weight': '0.036'}

	Recorder: 395385762816442096eca209b868607a

		Model: {'id': '395385762816442096eca209b868607a', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.013, 'ICIR': 0.048, 'Rank IC': 0.009, 'Rank ICIR': 0.039}, 'data_train_vec': ['2025-08-25', '2026-05-24'], 'train_time_vec': ['2026-08-25', '2026-08-25'], 'rank_icir': '0.039', 'weight': '0.026'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260825_13 807279019285153788 (Recorders: 4/5)

	Recorder: a716ea83cf2841cebce14b6e42d157b3

		Model: {'id': 'a716ea83cf2841cebce14b6e42d157b3', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.01, 'ICIR': 0.05, 'Rank IC': 0.022, 'Rank ICIR': 0.139}, 'data_train_vec': ['2021-08-25', '2025-05-24'], 'train_time_vec': ['2026-08-25', '2026-08-25'], 'rank_icir': '0.139', 'weight': '0.092'}

	Recorder: 6bd8a519f58348c8b0db5c037e32280d

		Model: {'id': '6bd8a519f58348c8b0db5c037e32280d', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.029, 'ICIR': 0.15, 'Rank IC': 0.03, 'Rank ICIR': 0.193}, 'data_train_vec': ['2022-08-25', '2025-08-24'], 'train_time_vec': ['2026-08-25', '2026-08-25'], 'rank_icir': '0.193', 'weight': '0.127'}

	Recorder: 6390197280854ded9966a4938f34ffe8

		Model: {'id': '6390197280854ded9966a4938f34ffe8', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.031, 'ICIR': 0.095, 'Rank IC': 0.018, 'Rank ICIR': 0.066}, 'data_train_vec': ['2024-08-25', '2026-02-24'], 'train_time_vec': ['2026-08-25', '2026-08-25'], 'rank_icir': '0.066', 'weight': '0.044'}

	Recorder: 465e9615272b4252996ffb9dc66f5b6f

		Model: {'id': '465e9615272b4252996ffb9dc66f5b6f', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.062, 'ICIR': 0.285, 'Rank IC': 0.033, 'Rank ICIR': 0.205}, 'data_train_vec': ['2025-08-25', '2026-05-24'], 'train_time_vec': ['2026-08-25', '2026-08-25'], 'rank_icir': '0.205', 'weight': '0.135'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260825_13 997575494734595470 (Recorders: 1/5)

	Recorder: 409f6283fdec4560b3dc0edad831ec5a

		Model: {'id': '409f6283fdec4560b3dc0edad831ec5a', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.053, 'ICIR': 0.156, 'Rank IC': 0.021, 'Rank ICIR': 0.092}, 'data_train_vec': ['2025-08-25', '2026-05-24'], 'train_time_vec': ['2026-08-25', '2026-08-25'], 'rank_icir': '0.092', 'weight': '0.061'}
