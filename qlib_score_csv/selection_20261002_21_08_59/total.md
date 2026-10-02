# params 
 {'predict_dates': [{'start': '2026-09-30', 'end': '2026-09-30'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20261002_20 711937192655103530 (Recorders: 4/5)

	Recorder: 7b6d4b9b95fd4f5cb24eadba224a9aa1

		Model: {'id': '7b6d4b9b95fd4f5cb24eadba224a9aa1', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.023, 'ICIR': 0.147, 'Rank IC': 0.041, 'Rank ICIR': 0.243}, 'data_train_vec': ['2021-10-02', '2025-07-01'], 'train_time_vec': ['2026-10-02', '2026-10-02'], 'rank_icir': '0.243', 'weight': '0.090'}

	Recorder: 133de4e0b6bb47bfafd9f6be0180d24d

		Model: {'id': '133de4e0b6bb47bfafd9f6be0180d24d', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.013, 'ICIR': 0.062, 'Rank IC': 0.028, 'Rank ICIR': 0.165}, 'data_train_vec': ['2022-10-02', '2025-10-01'], 'train_time_vec': ['2026-10-02', '2026-10-02'], 'rank_icir': '0.165', 'weight': '0.061'}

	Recorder: 30d8aabd517d415eb136b3b7bbb2bfb6

		Model: {'id': '30d8aabd517d415eb136b3b7bbb2bfb6', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.013, 'ICIR': 0.044, 'Rank IC': 0.016, 'Rank ICIR': 0.078}, 'data_train_vec': ['2023-10-02', '2026-01-01'], 'train_time_vec': ['2026-10-02', '2026-10-02'], 'rank_icir': '0.078', 'weight': '0.029'}

	Recorder: 339394cbb2f04bf0ab8b7702a109efaa

		Model: {'id': '339394cbb2f04bf0ab8b7702a109efaa', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.018, 'ICIR': 0.119, 'Rank IC': 0.01, 'Rank ICIR': 0.067}, 'data_train_vec': ['2024-10-02', '2026-04-01'], 'train_time_vec': ['2026-10-02', '2026-10-02'], 'rank_icir': '0.067', 'weight': '0.025'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20261002_20 213927092531962406 (Recorders: 3/5)

	Recorder: 8a136a52242a46908a8bccdae9131e58

		Model: {'id': '8a136a52242a46908a8bccdae9131e58', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.029, 'ICIR': 0.191, 'Rank IC': 0.038, 'Rank ICIR': 0.235}, 'data_train_vec': ['2021-10-02', '2025-07-01'], 'train_time_vec': ['2026-10-02', '2026-10-02'], 'rank_icir': '0.235', 'weight': '0.087'}

	Recorder: 57f536ee26204aacbb7ea9dbf860972d

		Model: {'id': '57f536ee26204aacbb7ea9dbf860972d', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.031, 'ICIR': 0.164, 'Rank IC': 0.037, 'Rank ICIR': 0.207}, 'data_train_vec': ['2022-10-02', '2025-10-01'], 'train_time_vec': ['2026-10-02', '2026-10-02'], 'rank_icir': '0.207', 'weight': '0.077'}

	Recorder: d81af1e5cbd543058deb6790a34ae2d9

		Model: {'id': 'd81af1e5cbd543058deb6790a34ae2d9', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.013, 'ICIR': 0.053, 'Rank IC': 0.013, 'Rank ICIR': 0.059}, 'data_train_vec': ['2023-10-02', '2026-01-01'], 'train_time_vec': ['2026-10-02', '2026-10-02'], 'rank_icir': '0.059', 'weight': '0.022'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20261002_18 659436690887940807 (Recorders: 4/5)

	Recorder: 999eeb3b7b7c4b38a2cbe014ca8dc212

		Model: {'id': '999eeb3b7b7c4b38a2cbe014ca8dc212', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.036, 'ICIR': 0.181, 'Rank IC': 0.048, 'Rank ICIR': 0.28}, 'data_train_vec': ['2021-10-02', '2025-07-01'], 'train_time_vec': ['2026-10-02', '2026-10-02'], 'rank_icir': '0.280', 'weight': '0.104'}

	Recorder: 74299602bcab4aa995d0c1910a02b819

		Model: {'id': '74299602bcab4aa995d0c1910a02b819', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.027, 'ICIR': 0.114, 'Rank IC': 0.029, 'Rank ICIR': 0.154}, 'data_train_vec': ['2022-10-02', '2025-10-01'], 'train_time_vec': ['2026-10-02', '2026-10-02'], 'rank_icir': '0.154', 'weight': '0.057'}

	Recorder: 724228bb194e4cbebb4b4e6fe21ae37c

		Model: {'id': '724228bb194e4cbebb4b4e6fe21ae37c', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.008, 'ICIR': 0.026, 'Rank IC': 0.008, 'Rank ICIR': 0.037}, 'data_train_vec': ['2023-10-02', '2026-01-01'], 'train_time_vec': ['2026-10-02', '2026-10-02'], 'rank_icir': '0.037', 'weight': '0.014'}

	Recorder: bd2dc05eff5b4a598ef09caa0bcf7f87

		Model: {'id': 'bd2dc05eff5b4a598ef09caa0bcf7f87', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.023, 'ICIR': 0.122, 'Rank IC': 0.004, 'Rank ICIR': 0.021}, 'data_train_vec': ['2024-10-02', '2026-04-01'], 'train_time_vec': ['2026-10-02', '2026-10-02'], 'rank_icir': '0.021', 'weight': '0.008'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20261002_17 692949957651139711 (Recorders: 5/5)

	Recorder: 44cd38d4f49a4476b039cdd66b46e493

		Model: {'id': '44cd38d4f49a4476b039cdd66b46e493', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.037, 'ICIR': 0.184, 'Rank IC': 0.04, 'Rank ICIR': 0.23}, 'data_train_vec': ['2021-10-02', '2025-07-01'], 'train_time_vec': ['2026-10-02', '2026-10-02'], 'rank_icir': '0.230', 'weight': '0.085'}

	Recorder: c5fa4fa02aff42399f0729a64fadb904

		Model: {'id': 'c5fa4fa02aff42399f0729a64fadb904', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.032, 'ICIR': 0.14, 'Rank IC': 0.019, 'Rank ICIR': 0.099}, 'data_train_vec': ['2022-10-02', '2025-10-01'], 'train_time_vec': ['2026-10-02', '2026-10-02'], 'rank_icir': '0.099', 'weight': '0.037'}

	Recorder: 77d081250e364f838dbea3d1438578b9

		Model: {'id': '77d081250e364f838dbea3d1438578b9', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.005, 'ICIR': 0.02, 'Rank IC': 0.001, 'Rank ICIR': 0.006}, 'data_train_vec': ['2023-10-02', '2026-01-01'], 'train_time_vec': ['2026-10-02', '2026-10-02'], 'rank_icir': '0.006', 'weight': '0.002'}

	Recorder: c8bddd1a427842e087dcba828ca7703f

		Model: {'id': 'c8bddd1a427842e087dcba828ca7703f', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.05, 'ICIR': 0.244, 'Rank IC': 0.026, 'Rank ICIR': 0.148}, 'data_train_vec': ['2024-10-02', '2026-04-01'], 'train_time_vec': ['2026-10-02', '2026-10-02'], 'rank_icir': '0.148', 'weight': '0.055'}

	Recorder: 038884b01dfb4be1bd10220be141a03b

		Model: {'id': '038884b01dfb4be1bd10220be141a03b', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.034, 'ICIR': 0.216, 'Rank IC': 0.032, 'Rank ICIR': 0.246}, 'data_train_vec': ['2025-10-02', '2026-07-01'], 'train_time_vec': ['2026-10-02', '2026-10-02'], 'rank_icir': '0.246', 'weight': '0.091'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20261002_17 663742696952283016 (Recorders: 3/5)

	Recorder: 4672b363957a4d3e9d5a2669c32b4ea1

		Model: {'id': '4672b363957a4d3e9d5a2669c32b4ea1', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.007, 'ICIR': 0.035, 'Rank IC': 0.033, 'Rank ICIR': 0.195}, 'data_train_vec': ['2021-10-02', '2025-07-01'], 'train_time_vec': ['2026-10-02', '2026-10-02'], 'rank_icir': '0.195', 'weight': '0.072'}

	Recorder: fa3965c880974418bfc07f416b3517a4

		Model: {'id': 'fa3965c880974418bfc07f416b3517a4', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.01, 'ICIR': 0.04, 'Rank IC': 0.023, 'Rank ICIR': 0.133}, 'data_train_vec': ['2022-10-02', '2025-10-01'], 'train_time_vec': ['2026-10-02', '2026-10-02'], 'rank_icir': '0.133', 'weight': '0.049'}

	Recorder: 4ab0af1bcde64c5bbb64b0d5d589b310

		Model: {'id': '4ab0af1bcde64c5bbb64b0d5d589b310', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.029, 'ICIR': 0.155, 'Rank IC': 0.013, 'Rank ICIR': 0.089}, 'data_train_vec': ['2024-10-02', '2026-04-01'], 'train_time_vec': ['2026-10-02', '2026-10-02'], 'rank_icir': '0.089', 'weight': '0.033'}
