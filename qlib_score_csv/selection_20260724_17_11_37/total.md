# params 
 {'predict_dates': [{'start': '2026-07-23', 'end': '2026-07-23'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260724_16 227800065670124509 (Recorders: 2/5)

	Recorder: 8944b32ff773409e94393001661823aa

		Model: {'id': '8944b32ff773409e94393001661823aa', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.003, 'ICIR': 0.025, 'Rank IC': 0.029, 'Rank ICIR': 0.156}, 'data_train_vec': ['2021-07-24', '2025-04-23'], 'train_time_vec': ['2026-07-24', '2026-07-24'], 'rank_icir': '0.156', 'weight': '0.141'}

	Recorder: 097e7a0128874855b089a2df82771813

		Model: {'id': '097e7a0128874855b089a2df82771813', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.012, 'ICIR': 0.063, 'Rank IC': 0.022, 'Rank ICIR': 0.176}, 'data_train_vec': ['2023-07-24', '2025-10-23'], 'train_time_vec': ['2026-07-24', '2026-07-24'], 'rank_icir': '0.176', 'weight': '0.159'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260724_16 328876432209784830 (Recorders: 2/5)

	Recorder: bfdab77e497741708982eef2cbb78af6

		Model: {'id': 'bfdab77e497741708982eef2cbb78af6', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.015, 'ICIR': 0.1, 'Rank IC': 0.037, 'Rank ICIR': 0.22}, 'data_train_vec': ['2021-07-24', '2025-04-23'], 'train_time_vec': ['2026-07-24', '2026-07-24'], 'rank_icir': '0.220', 'weight': '0.198'}

	Recorder: 2ac95bdadfc74c718a80e91fea026269

		Model: {'id': '2ac95bdadfc74c718a80e91fea026269', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.02, 'ICIR': 0.129, 'Rank IC': 0.026, 'Rank ICIR': 0.206}, 'data_train_vec': ['2023-07-24', '2025-10-23'], 'train_time_vec': ['2026-07-24', '2026-07-24'], 'rank_icir': '0.206', 'weight': '0.186'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260724_14 434911725160684498 (Recorders: 2/5)

	Recorder: 6061a6ca60774a51b53faecd28c8cf39

		Model: {'id': '6061a6ca60774a51b53faecd28c8cf39', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.009, 'ICIR': 0.051, 'Rank IC': 0.036, 'Rank ICIR': 0.207}, 'data_train_vec': ['2021-07-24', '2025-04-23'], 'train_time_vec': ['2026-07-24', '2026-07-24'], 'rank_icir': '0.207', 'weight': '0.186'}

	Recorder: 612524be517c48db92d0c9deec19eb8b

		Model: {'id': '612524be517c48db92d0c9deec19eb8b', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.004, 'ICIR': 0.024, 'Rank IC': 0.023, 'Rank ICIR': 0.145}, 'data_train_vec': ['2022-07-24', '2025-07-23'], 'train_time_vec': ['2026-07-24', '2026-07-24'], 'rank_icir': '0.145', 'weight': '0.131'}
