# params 
 {'predict_dates': [{'start': '2026-08-07', 'end': '2026-08-07'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260809_15 289619233803643407 (Recorders: 1/5)

	Recorder: d264c1222df04ccea79d1fd194296afb

		Model: {'id': 'd264c1222df04ccea79d1fd194296afb', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.022, 'ICIR': 0.094, 'Rank IC': 0.036, 'Rank ICIR': 0.252}, 'data_train_vec': ['2023-08-09', '2025-11-08'], 'train_time_vec': ['2026-08-09', '2026-08-09'], 'rank_icir': '0.252', 'weight': '0.159'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260809_15 329122729379737489 (Recorders: 3/5)

	Recorder: 8b23d2c0d46549bda371ff57a2fb4f87

		Model: {'id': '8b23d2c0d46549bda371ff57a2fb4f87', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.007, 'ICIR': 0.048, 'Rank IC': 0.018, 'Rank ICIR': 0.112}, 'data_train_vec': ['2021-08-09', '2025-05-08'], 'train_time_vec': ['2026-08-09', '2026-08-09'], 'rank_icir': '0.112', 'weight': '0.071'}

	Recorder: 25649197adbf4dc4a8f7576c4ca200db

		Model: {'id': '25649197adbf4dc4a8f7576c4ca200db', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.008, 'ICIR': 0.075, 'Rank IC': 0.011, 'Rank ICIR': 0.09}, 'data_train_vec': ['2022-08-09', '2025-08-08'], 'train_time_vec': ['2026-08-09', '2026-08-09'], 'rank_icir': '0.090', 'weight': '0.057'}

	Recorder: b8da9d1d1a47445eb4b0e09c7c708956

		Model: {'id': 'b8da9d1d1a47445eb4b0e09c7c708956', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.029, 'ICIR': 0.153, 'Rank IC': 0.029, 'Rank ICIR': 0.209}, 'data_train_vec': ['2023-08-09', '2025-11-08'], 'train_time_vec': ['2026-08-09', '2026-08-09'], 'rank_icir': '0.209', 'weight': '0.132'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260809_13 465665236222997884 (Recorders: 2/5)

	Recorder: eb6e9cfcced749e48362e5584a3c2048

		Model: {'id': 'eb6e9cfcced749e48362e5584a3c2048', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.017, 'ICIR': 0.088, 'Rank IC': 0.034, 'Rank ICIR': 0.196}, 'data_train_vec': ['2021-08-09', '2025-05-08'], 'train_time_vec': ['2026-08-09', '2026-08-09'], 'rank_icir': '0.196', 'weight': '0.124'}

	Recorder: fd6e19b0afa54e32afd2de9726771905

		Model: {'id': 'fd6e19b0afa54e32afd2de9726771905', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.012, 'ICIR': 0.058, 'Rank IC': 0.024, 'Rank ICIR': 0.14}, 'data_train_vec': ['2022-08-09', '2025-08-08'], 'train_time_vec': ['2026-08-09', '2026-08-09'], 'rank_icir': '0.140', 'weight': '0.088'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260809_13 960390015810978383 (Recorders: 2/5)

	Recorder: 8e630db1e1564b308961981f88fbdbe8

		Model: {'id': '8e630db1e1564b308961981f88fbdbe8', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.009, 'ICIR': 0.044, 'Rank IC': 0.025, 'Rank ICIR': 0.158}, 'data_train_vec': ['2021-08-09', '2025-05-08'], 'train_time_vec': ['2026-08-09', '2026-08-09'], 'rank_icir': '0.158', 'weight': '0.100'}

	Recorder: 320501ed094943a18f92fe964afe2565

		Model: {'id': '320501ed094943a18f92fe964afe2565', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.012, 'ICIR': 0.06, 'Rank IC': 0.021, 'Rank ICIR': 0.132}, 'data_train_vec': ['2022-08-09', '2025-08-08'], 'train_time_vec': ['2026-08-09', '2026-08-09'], 'rank_icir': '0.132', 'weight': '0.083'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260809_13 258986909231696915 (Recorders: 3/5)

	Recorder: 667c6f2283cf4be284a874a08231b774

		Model: {'id': '667c6f2283cf4be284a874a08231b774', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.01, 'ICIR': 0.049, 'Rank IC': 0.034, 'Rank ICIR': 0.187}, 'data_train_vec': ['2021-08-09', '2025-05-08'], 'train_time_vec': ['2026-08-09', '2026-08-09'], 'rank_icir': '0.187', 'weight': '0.118'}

	Recorder: ab9c0c44d4f44d70bca02e9e5051e9e3

		Model: {'id': 'ab9c0c44d4f44d70bca02e9e5051e9e3', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.004, 'ICIR': 0.016, 'Rank IC': 0.014, 'Rank ICIR': 0.089}, 'data_train_vec': ['2023-08-09', '2025-11-08'], 'train_time_vec': ['2026-08-09', '2026-08-09'], 'rank_icir': '0.089', 'weight': '0.056'}

	Recorder: 8cd4afd3132240d9933fb2ea2412fe6e

		Model: {'id': '8cd4afd3132240d9933fb2ea2412fe6e', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.027, 'ICIR': 0.074, 'Rank IC': 0.005, 'Rank ICIR': 0.022}, 'data_train_vec': ['2025-08-09', '2026-05-08'], 'train_time_vec': ['2026-08-09', '2026-08-09'], 'rank_icir': '0.022', 'weight': '0.014'}
