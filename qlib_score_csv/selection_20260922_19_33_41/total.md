# params 
 {'predict_dates': [{'start': '2026-09-22', 'end': '2026-09-22'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260922_19 651222138416197209 (Recorders: 3/5)

	Recorder: d5813f3a28d4429b8b3836a72ccccaa1

		Model: {'id': 'd5813f3a28d4429b8b3836a72ccccaa1', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.008, 'ICIR': 0.055, 'Rank IC': 0.018, 'Rank ICIR': 0.097}, 'data_train_vec': ['2021-09-22', '2025-06-21'], 'train_time_vec': ['2026-09-22', '2026-09-22'], 'rank_icir': '0.097', 'weight': '0.053'}

	Recorder: 946a89e276aa48f9a2aa2175f1fd8ed7

		Model: {'id': '946a89e276aa48f9a2aa2175f1fd8ed7', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.015, 'ICIR': 0.07, 'Rank IC': 0.024, 'Rank ICIR': 0.146}, 'data_train_vec': ['2022-09-22', '2025-09-21'], 'train_time_vec': ['2026-09-22', '2026-09-22'], 'rank_icir': '0.146', 'weight': '0.080'}

	Recorder: 456d1db4015f43c28c51994f2216a26d

		Model: {'id': '456d1db4015f43c28c51994f2216a26d', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.003, 'ICIR': 0.011, 'Rank IC': 0.007, 'Rank ICIR': 0.041}, 'data_train_vec': ['2023-09-22', '2025-12-21'], 'train_time_vec': ['2026-09-22', '2026-09-22'], 'rank_icir': '0.041', 'weight': '0.022'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260922_19 638016672428372731 (Recorders: 2/5)

	Recorder: bb0e0fa8a86d4c3a939d9cdaf79176f9

		Model: {'id': 'bb0e0fa8a86d4c3a939d9cdaf79176f9', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.019, 'ICIR': 0.147, 'Rank IC': 0.027, 'Rank ICIR': 0.187}, 'data_train_vec': ['2021-09-22', '2025-06-21'], 'train_time_vec': ['2026-09-22', '2026-09-22'], 'rank_icir': '0.187', 'weight': '0.102'}

	Recorder: 84a4c3767e7d4dc1819e309312b1f7a9

		Model: {'id': '84a4c3767e7d4dc1819e309312b1f7a9', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.013, 'ICIR': 0.098, 'Rank IC': 0.018, 'Rank ICIR': 0.141}, 'data_train_vec': ['2022-09-22', '2025-09-21'], 'train_time_vec': ['2026-09-22', '2026-09-22'], 'rank_icir': '0.141', 'weight': '0.077'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260922_17 370594044817185857 (Recorders: 3/5)

	Recorder: 484c4c053a324e7690172096701be60d

		Model: {'id': '484c4c053a324e7690172096701be60d', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.029, 'ICIR': 0.152, 'Rank IC': 0.037, 'Rank ICIR': 0.23}, 'data_train_vec': ['2021-09-22', '2025-06-21'], 'train_time_vec': ['2026-09-22', '2026-09-22'], 'rank_icir': '0.230', 'weight': '0.126'}

	Recorder: cb41463cb3b74aa687d9aab8c83d8691

		Model: {'id': 'cb41463cb3b74aa687d9aab8c83d8691', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.022, 'ICIR': 0.098, 'Rank IC': 0.029, 'Rank ICIR': 0.165}, 'data_train_vec': ['2022-09-22', '2025-09-21'], 'train_time_vec': ['2026-09-22', '2026-09-22'], 'rank_icir': '0.165', 'weight': '0.090'}

	Recorder: 8a9365a0fff2432d8c4f8ea418b24bec

		Model: {'id': '8a9365a0fff2432d8c4f8ea418b24bec', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.003, 'ICIR': 0.012, 'Rank IC': 0.003, 'Rank ICIR': 0.015}, 'data_train_vec': ['2023-09-22', '2025-12-21'], 'train_time_vec': ['2026-09-22', '2026-09-22'], 'rank_icir': '0.015', 'weight': '0.008'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260922_16 489022819119306768 (Recorders: 3/5)

	Recorder: 7c6227833974424b931acd636251c9fe

		Model: {'id': '7c6227833974424b931acd636251c9fe', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.029, 'ICIR': 0.14, 'Rank IC': 0.032, 'Rank ICIR': 0.191}, 'data_train_vec': ['2021-09-22', '2025-06-21'], 'train_time_vec': ['2026-09-22', '2026-09-22'], 'rank_icir': '0.191', 'weight': '0.105'}

	Recorder: 794953f593324c72a5b80d373ee29a28

		Model: {'id': '794953f593324c72a5b80d373ee29a28', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.027, 'ICIR': 0.13, 'Rank IC': 0.016, 'Rank ICIR': 0.095}, 'data_train_vec': ['2022-09-22', '2025-09-21'], 'train_time_vec': ['2026-09-22', '2026-09-22'], 'rank_icir': '0.095', 'weight': '0.052'}

	Recorder: f90b299beea54613b089f7087c5664de

		Model: {'id': 'f90b299beea54613b089f7087c5664de', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.06, 'ICIR': 0.258, 'Rank IC': 0.031, 'Rank ICIR': 0.155}, 'data_train_vec': ['2024-09-22', '2026-03-21'], 'train_time_vec': ['2026-09-22', '2026-09-22'], 'rank_icir': '0.155', 'weight': '0.085'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260922_16 566361912059109904 (Recorders: 2/5)

	Recorder: 6440ba86a05248e4a2652550d68c3040

		Model: {'id': '6440ba86a05248e4a2652550d68c3040', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.004, 'ICIR': 0.022, 'Rank IC': 0.028, 'Rank ICIR': 0.175}, 'data_train_vec': ['2021-09-22', '2025-06-21'], 'train_time_vec': ['2026-09-22', '2026-09-22'], 'rank_icir': '0.175', 'weight': '0.096'}

	Recorder: 4746bb9f5d144e79b84099738b4d669e

		Model: {'id': '4746bb9f5d144e79b84099738b4d669e', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.017, 'ICIR': 0.077, 'Rank IC': 0.031, 'Rank ICIR': 0.189}, 'data_train_vec': ['2022-09-22', '2025-09-21'], 'train_time_vec': ['2026-09-22', '2026-09-22'], 'rank_icir': '0.189', 'weight': '0.103'}
