# params 
 {'predict_dates': [{'start': '2026-07-24', 'end': '2026-07-24'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260726_15 572064744018168498 (Recorders: 1/5)

	Recorder: 0f30aea2438042bebff41466a0fe653b

		Model: {'id': '0f30aea2438042bebff41466a0fe653b', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.007, 'ICIR': 0.054, 'Rank IC': 0.035, 'Rank ICIR': 0.178}, 'data_train_vec': ['2021-07-26', '2025-04-25'], 'train_time_vec': ['2026-07-26', '2026-07-26'], 'rank_icir': '0.178', 'weight': '0.233'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260726_15 570236526363096696 (Recorders: 1/5)

	Recorder: 65b221c1c7a142ca82db4fda2d5d5b89

		Model: {'id': '65b221c1c7a142ca82db4fda2d5d5b89', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.012, 'ICIR': 0.075, 'Rank IC': 0.016, 'Rank ICIR': 0.128}, 'data_train_vec': ['2023-07-26', '2025-10-25'], 'train_time_vec': ['2026-07-26', '2026-07-26'], 'rank_icir': '0.128', 'weight': '0.168'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260726_14 728277385136602934 (Recorders: 3/5)

	Recorder: c5b6a12c9eb44cb481469dddc8c38783

		Model: {'id': 'c5b6a12c9eb44cb481469dddc8c38783', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.017, 'ICIR': 0.095, 'Rank IC': 0.041, 'Rank ICIR': 0.232}, 'data_train_vec': ['2021-07-26', '2025-04-25'], 'train_time_vec': ['2026-07-26', '2026-07-26'], 'rank_icir': '0.232', 'weight': '0.304'}

	Recorder: a303b31b5a85459db67ce3db1e5764ad

		Model: {'id': 'a303b31b5a85459db67ce3db1e5764ad', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.008, 'ICIR': 0.048, 'Rank IC': 0.024, 'Rank ICIR': 0.156}, 'data_train_vec': ['2022-07-26', '2025-07-25'], 'train_time_vec': ['2026-07-26', '2026-07-26'], 'rank_icir': '0.156', 'weight': '0.204'}

	Recorder: 73e93928512f49f5816644a4d3724434

		Model: {'id': '73e93928512f49f5816644a4d3724434', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.002, 'ICIR': 0.011, 'Rank IC': 0.012, 'Rank ICIR': 0.069}, 'data_train_vec': ['2023-07-26', '2025-10-25'], 'train_time_vec': ['2026-07-26', '2026-07-26'], 'rank_icir': '0.069', 'weight': '0.090'}
