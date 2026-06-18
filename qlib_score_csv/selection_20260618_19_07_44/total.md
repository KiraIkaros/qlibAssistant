# params 
 {'predict_dates': [{'start': '2026-06-18', 'end': '2026-06-18'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260618_18 468534304440690422 (Recorders: 3/5)

	Recorder: 49f022020c2b4e9db2026dba86b5ef27

		Model: {'id': '49f022020c2b4e9db2026dba86b5ef27', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.002, 'ICIR': 0.016, 'Rank IC': 0.025, 'Rank ICIR': 0.154}, 'data_train_vec': ['2021-06-18', '2025-03-17'], 'train_time_vec': ['2026-06-18', '2026-06-18'], 'rank_icir': '0.154', 'weight': '0.041'}

	Recorder: 276d7f0b6b7e4538bc987c01b29044e6

		Model: {'id': '276d7f0b6b7e4538bc987c01b29044e6', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.02, 'ICIR': 0.183, 'Rank IC': 0.036, 'Rank ICIR': 0.258}, 'data_train_vec': ['2023-06-18', '2025-09-17'], 'train_time_vec': ['2026-06-18', '2026-06-18'], 'rank_icir': '0.258', 'weight': '0.068'}

	Recorder: 8c51bc8b99f34918b48f3bcd2c264ca9

		Model: {'id': '8c51bc8b99f34918b48f3bcd2c264ca9', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.034, 'ICIR': 0.31, 'Rank IC': 0.038, 'Rank ICIR': 0.363}, 'data_train_vec': ['2024-06-18', '2025-12-17'], 'train_time_vec': ['2026-06-18', '2026-06-18'], 'rank_icir': '0.363', 'weight': '0.096'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260618_18 976086453012082287 (Recorders: 4/5)

	Recorder: 71a45bab2422453cb89fe78edf262629

		Model: {'id': '71a45bab2422453cb89fe78edf262629', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.005, 'ICIR': 0.043, 'Rank IC': 0.035, 'Rank ICIR': 0.255}, 'data_train_vec': ['2022-06-18', '2025-06-17'], 'train_time_vec': ['2026-06-18', '2026-06-18'], 'rank_icir': '0.255', 'weight': '0.067'}

	Recorder: fa5b8e427cf54bda8c0ef35ed193660c

		Model: {'id': 'fa5b8e427cf54bda8c0ef35ed193660c', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.027, 'ICIR': 0.266, 'Rank IC': 0.036, 'Rank ICIR': 0.301}, 'data_train_vec': ['2023-06-18', '2025-09-17'], 'train_time_vec': ['2026-06-18', '2026-06-18'], 'rank_icir': '0.301', 'weight': '0.080'}

	Recorder: b7bd6a9c95ae440cbab5b2d74d301b23

		Model: {'id': 'b7bd6a9c95ae440cbab5b2d74d301b23', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.026, 'ICIR': 0.211, 'Rank IC': 0.033, 'Rank ICIR': 0.302}, 'data_train_vec': ['2024-06-18', '2025-12-17'], 'train_time_vec': ['2026-06-18', '2026-06-18'], 'rank_icir': '0.302', 'weight': '0.080'}

	Recorder: 940c4b0333e4478bbeb5bd0339abdff9

		Model: {'id': '940c4b0333e4478bbeb5bd0339abdff9', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.04, 'ICIR': 0.165, 'Rank IC': 0.009, 'Rank ICIR': 0.04}, 'data_train_vec': ['2025-06-18', '2026-03-17'], 'train_time_vec': ['2026-06-18', '2026-06-18'], 'rank_icir': '0.040', 'weight': '0.011'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260618_16 522971266247219862 (Recorders: 4/5)

	Recorder: 84ff1edfa9c24376af5de54ad345d1df

		Model: {'id': '84ff1edfa9c24376af5de54ad345d1df', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.012, 'ICIR': 0.077, 'Rank IC': 0.044, 'Rank ICIR': 0.282}, 'data_train_vec': ['2021-06-18', '2025-03-17'], 'train_time_vec': ['2026-06-18', '2026-06-18'], 'rank_icir': '0.282', 'weight': '0.075'}

	Recorder: acf96cf57da4480188d8473dcb057481

		Model: {'id': 'acf96cf57da4480188d8473dcb057481', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.023, 'ICIR': 0.15, 'Rank IC': 0.056, 'Rank ICIR': 0.334}, 'data_train_vec': ['2022-06-18', '2025-06-17'], 'train_time_vec': ['2026-06-18', '2026-06-18'], 'rank_icir': '0.334', 'weight': '0.088'}

	Recorder: f1a1aa722e0245a6ae2303a7c842616e

		Model: {'id': 'f1a1aa722e0245a6ae2303a7c842616e', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.012, 'ICIR': 0.087, 'Rank IC': 0.031, 'Rank ICIR': 0.216}, 'data_train_vec': ['2023-06-18', '2025-09-17'], 'train_time_vec': ['2026-06-18', '2026-06-18'], 'rank_icir': '0.216', 'weight': '0.057'}

	Recorder: 4ca62f2a62d6425aa68fdce5cfbdbf63

		Model: {'id': '4ca62f2a62d6425aa68fdce5cfbdbf63', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.021, 'ICIR': 0.161, 'Rank IC': 0.023, 'Rank ICIR': 0.199}, 'data_train_vec': ['2024-06-18', '2025-12-17'], 'train_time_vec': ['2026-06-18', '2026-06-18'], 'rank_icir': '0.199', 'weight': '0.053'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260618_15 793915510638130515 (Recorders: 3/5)

	Recorder: 2c062bde75b94c73a2dc1c81b612e9c6

		Model: {'id': '2c062bde75b94c73a2dc1c81b612e9c6', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.003, 'ICIR': 0.017, 'Rank IC': 0.035, 'Rank ICIR': 0.288}, 'data_train_vec': ['2021-06-18', '2025-03-17'], 'train_time_vec': ['2026-06-18', '2026-06-18'], 'rank_icir': '0.288', 'weight': '0.076'}

	Recorder: a3305388387a4fda930cabfa5d7d6131

		Model: {'id': 'a3305388387a4fda930cabfa5d7d6131', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.002, 'ICIR': 0.017, 'Rank IC': 0.026, 'Rank ICIR': 0.207}, 'data_train_vec': ['2023-06-18', '2025-09-17'], 'train_time_vec': ['2026-06-18', '2026-06-18'], 'rank_icir': '0.207', 'weight': '0.055'}

	Recorder: 85cb1b0f0567441f9d69cb323d141b9f

		Model: {'id': '85cb1b0f0567441f9d69cb323d141b9f', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.021, 'ICIR': 0.129, 'Rank IC': 0.019, 'Rank ICIR': 0.131}, 'data_train_vec': ['2024-06-18', '2025-12-17'], 'train_time_vec': ['2026-06-18', '2026-06-18'], 'rank_icir': '0.131', 'weight': '0.035'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260618_15 804696013093673719 (Recorders: 2/5)

	Recorder: 27a8ec5753d14e65a44df74b170ecfd0

		Model: {'id': '27a8ec5753d14e65a44df74b170ecfd0', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.004, 'ICIR': 0.025, 'Rank IC': 0.037, 'Rank ICIR': 0.22}, 'data_train_vec': ['2021-06-18', '2025-03-17'], 'train_time_vec': ['2026-06-18', '2026-06-18'], 'rank_icir': '0.220', 'weight': '0.058'}

	Recorder: 52910c4199e74068b706bc4243fe588d

		Model: {'id': '52910c4199e74068b706bc4243fe588d', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.006, 'ICIR': 0.049, 'Rank IC': 0.022, 'Rank ICIR': 0.23}, 'data_train_vec': ['2024-06-18', '2025-12-17'], 'train_time_vec': ['2026-06-18', '2026-06-18'], 'rank_icir': '0.230', 'weight': '0.061'}
