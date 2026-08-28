# params 
 {'predict_dates': [{'start': '2026-08-26', 'end': '2026-08-26'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260828_00 472146170810567912 (Recorders: 3/5)

	Recorder: cee60fd74de148b7a945234bfe208965

		Model: {'id': 'cee60fd74de148b7a945234bfe208965', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.005, 'ICIR': 0.031, 'Rank IC': 0.001, 'Rank ICIR': 0.008}, 'data_train_vec': ['2021-08-28', '2025-05-27'], 'train_time_vec': ['2026-08-28', '2026-08-28'], 'rank_icir': '0.008', 'weight': '0.006'}

	Recorder: f91455c669f440a18a1363de816a848c

		Model: {'id': 'f91455c669f440a18a1363de816a848c', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.013, 'ICIR': 0.06, 'Rank IC': 0.031, 'Rank ICIR': 0.22}, 'data_train_vec': ['2022-08-28', '2025-08-27'], 'train_time_vec': ['2026-08-28', '2026-08-28'], 'rank_icir': '0.220', 'weight': '0.166'}

	Recorder: 9c3cf33f397147f3a9a30c9280f1ebf0

		Model: {'id': '9c3cf33f397147f3a9a30c9280f1ebf0', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.006, 'ICIR': 0.022, 'Rank IC': 0.007, 'Rank ICIR': 0.041}, 'data_train_vec': ['2023-08-28', '2025-11-27'], 'train_time_vec': ['2026-08-28', '2026-08-28'], 'rank_icir': '0.041', 'weight': '0.031'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260828_00 335605219898720632 (Recorders: 2/5)

	Recorder: 9c674c369a564969adab0121e6de6980

		Model: {'id': '9c674c369a564969adab0121e6de6980', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.014, 'ICIR': 0.09, 'Rank IC': 0.025, 'Rank ICIR': 0.185}, 'data_train_vec': ['2021-08-28', '2025-05-27'], 'train_time_vec': ['2026-08-28', '2026-08-28'], 'rank_icir': '0.185', 'weight': '0.139'}

	Recorder: b5e58ef442b34471a378ea6e341c2460

		Model: {'id': 'b5e58ef442b34471a378ea6e341c2460', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.005, 'ICIR': 0.027, 'Rank IC': 0.01, 'Rank ICIR': 0.067}, 'data_train_vec': ['2023-08-28', '2025-11-27'], 'train_time_vec': ['2026-08-28', '2026-08-28'], 'rank_icir': '0.067', 'weight': '0.050'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260827_22 514600163650000477 (Recorders: 3/5)

	Recorder: 87377c323214496a8254653a477cfcd3

		Model: {'id': '87377c323214496a8254653a477cfcd3', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.014, 'ICIR': 0.07, 'Rank IC': 0.026, 'Rank ICIR': 0.157}, 'data_train_vec': ['2021-08-27', '2025-05-26'], 'train_time_vec': ['2026-08-27', '2026-08-28'], 'rank_icir': '0.157', 'weight': '0.118'}

	Recorder: 6720193bd323442b8cca4918f5c88e20

		Model: {'id': '6720193bd323442b8cca4918f5c88e20', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.021, 'ICIR': 0.095, 'Rank IC': 0.027, 'Rank ICIR': 0.164}, 'data_train_vec': ['2022-08-27', '2025-08-26'], 'train_time_vec': ['2026-08-27', '2026-08-27'], 'rank_icir': '0.164', 'weight': '0.124'}

	Recorder: bc1ac69310e84e7abad469293fb334e0

		Model: {'id': 'bc1ac69310e84e7abad469293fb334e0', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.001, 'ICIR': 0.006, 'Rank IC': 0.01, 'Rank ICIR': 0.056}, 'data_train_vec': ['2023-08-27', '2025-11-26'], 'train_time_vec': ['2026-08-27', '2026-08-27'], 'rank_icir': '0.056', 'weight': '0.042'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260827_22 289063475779912560 (Recorders: 4/5)

	Recorder: 81485d23d2454aa598e8e5c37471bec9

		Model: {'id': '81485d23d2454aa598e8e5c37471bec9', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.012, 'ICIR': 0.06, 'Rank IC': 0.024, 'Rank ICIR': 0.145}, 'data_train_vec': ['2021-08-27', '2025-05-26'], 'train_time_vec': ['2026-08-27', '2026-08-27'], 'rank_icir': '0.145', 'weight': '0.109'}

	Recorder: 4e644f4b444c48c0803667713d57fb69

		Model: {'id': '4e644f4b444c48c0803667713d57fb69', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.029, 'ICIR': 0.154, 'Rank IC': 0.029, 'Rank ICIR': 0.186}, 'data_train_vec': ['2022-08-27', '2025-08-26'], 'train_time_vec': ['2026-08-27', '2026-08-27'], 'rank_icir': '0.186', 'weight': '0.140'}

	Recorder: 0868f091675e4440b9a22cb82dc4d5ed

		Model: {'id': '0868f091675e4440b9a22cb82dc4d5ed', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.033, 'ICIR': 0.098, 'Rank IC': 0.015, 'Rank ICIR': 0.056}, 'data_train_vec': ['2024-08-27', '2026-02-26'], 'train_time_vec': ['2026-08-27', '2026-08-27'], 'rank_icir': '0.056', 'weight': '0.042'}

	Recorder: 0e983e50f1244006b50665c30e6d6b28

		Model: {'id': '0e983e50f1244006b50665c30e6d6b28', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.036, 'ICIR': 0.175, 'Rank IC': 0.007, 'Rank ICIR': 0.042}, 'data_train_vec': ['2025-08-27', '2026-05-26'], 'train_time_vec': ['2026-08-27', '2026-08-27'], 'rank_icir': '0.042', 'weight': '0.032'}
