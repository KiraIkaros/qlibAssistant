# params 
 {'predict_dates': [{'start': '2026-09-30', 'end': '2026-09-30'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20261004_19 498739131914852406 (Recorders: 5/5)

	Recorder: cf4e6a38bb32404fb8d3c6990fef3bec

		Model: {'id': 'cf4e6a38bb32404fb8d3c6990fef3bec', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.022, 'ICIR': 0.145, 'Rank IC': 0.037, 'Rank ICIR': 0.198}, 'data_train_vec': ['2021-10-04', '2025-07-03'], 'train_time_vec': ['2026-10-04', '2026-10-04'], 'rank_icir': '0.198', 'weight': '0.059'}

	Recorder: 38dceb8548d0420f9b1591d69a995b83

		Model: {'id': '38dceb8548d0420f9b1591d69a995b83', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.015, 'ICIR': 0.067, 'Rank IC': 0.028, 'Rank ICIR': 0.161}, 'data_train_vec': ['2022-10-04', '2025-10-03'], 'train_time_vec': ['2026-10-04', '2026-10-04'], 'rank_icir': '0.161', 'weight': '0.048'}

	Recorder: f317e468665341b7b65f7a1e8a713bfb

		Model: {'id': 'f317e468665341b7b65f7a1e8a713bfb', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.014, 'ICIR': 0.046, 'Rank IC': 0.017, 'Rank ICIR': 0.08}, 'data_train_vec': ['2023-10-04', '2026-01-03'], 'train_time_vec': ['2026-10-04', '2026-10-04'], 'rank_icir': '0.080', 'weight': '0.024'}

	Recorder: 654950d1f5114d3eaf43344c3170af96

		Model: {'id': '654950d1f5114d3eaf43344c3170af96', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.03, 'ICIR': 0.196, 'Rank IC': 0.013, 'Rank ICIR': 0.076}, 'data_train_vec': ['2024-10-04', '2026-04-03'], 'train_time_vec': ['2026-10-04', '2026-10-04'], 'rank_icir': '0.076', 'weight': '0.023'}

	Recorder: 791f8f8ad0b045c1b606983af004456e

		Model: {'id': '791f8f8ad0b045c1b606983af004456e', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.033, 'ICIR': 0.295, 'Rank IC': 0.022, 'Rank ICIR': 0.202}, 'data_train_vec': ['2025-10-04', '2026-07-03'], 'train_time_vec': ['2026-10-04', '2026-10-04'], 'rank_icir': '0.202', 'weight': '0.060'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20261004_19 786597504380267904 (Recorders: 5/5)

	Recorder: ae357cbe8fe744a5bd96e8b5887c5d2a

		Model: {'id': 'ae357cbe8fe744a5bd96e8b5887c5d2a', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.029, 'ICIR': 0.193, 'Rank IC': 0.038, 'Rank ICIR': 0.239}, 'data_train_vec': ['2021-10-04', '2025-07-03'], 'train_time_vec': ['2026-10-04', '2026-10-04'], 'rank_icir': '0.239', 'weight': '0.071'}

	Recorder: 75fe885988284d4ebb4c419e341f7a03

		Model: {'id': '75fe885988284d4ebb4c419e341f7a03', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.03, 'ICIR': 0.161, 'Rank IC': 0.035, 'Rank ICIR': 0.195}, 'data_train_vec': ['2022-10-04', '2025-10-03'], 'train_time_vec': ['2026-10-04', '2026-10-04'], 'rank_icir': '0.195', 'weight': '0.058'}

	Recorder: cfe116c8033b4750b083f76bf6b0a134

		Model: {'id': 'cfe116c8033b4750b083f76bf6b0a134', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.009, 'ICIR': 0.037, 'Rank IC': 0.012, 'Rank ICIR': 0.06}, 'data_train_vec': ['2023-10-04', '2026-01-03'], 'train_time_vec': ['2026-10-04', '2026-10-04'], 'rank_icir': '0.060', 'weight': '0.018'}

	Recorder: 9290879eb0b045e4a0675bdecf7201bd

		Model: {'id': '9290879eb0b045e4a0675bdecf7201bd', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.02, 'ICIR': 0.134, 'Rank IC': 0.005, 'Rank ICIR': 0.045}, 'data_train_vec': ['2024-10-04', '2026-04-03'], 'train_time_vec': ['2026-10-04', '2026-10-04'], 'rank_icir': '0.045', 'weight': '0.013'}

	Recorder: 1c19d0a6448f40d2b1f1b4f7369d9550

		Model: {'id': '1c19d0a6448f40d2b1f1b4f7369d9550', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.016, 'ICIR': 0.169, 'Rank IC': 0.023, 'Rank ICIR': 0.304}, 'data_train_vec': ['2025-10-04', '2026-07-03'], 'train_time_vec': ['2026-10-04', '2026-10-04'], 'rank_icir': '0.304', 'weight': '0.090'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20261004_17 710920991505632617 (Recorders: 3/5)

	Recorder: 8dbf1ab3700848ca8f7181c1ccc91d0f

		Model: {'id': '8dbf1ab3700848ca8f7181c1ccc91d0f', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.037, 'ICIR': 0.18, 'Rank IC': 0.048, 'Rank ICIR': 0.28}, 'data_train_vec': ['2021-10-04', '2025-07-03'], 'train_time_vec': ['2026-10-04', '2026-10-04'], 'rank_icir': '0.280', 'weight': '0.083'}

	Recorder: 4307140ca6674d139b29e9c94fe18420

		Model: {'id': '4307140ca6674d139b29e9c94fe18420', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.026, 'ICIR': 0.115, 'Rank IC': 0.028, 'Rank ICIR': 0.148}, 'data_train_vec': ['2022-10-04', '2025-10-03'], 'train_time_vec': ['2026-10-04', '2026-10-04'], 'rank_icir': '0.148', 'weight': '0.044'}

	Recorder: f7e9819d50b547929f86eb0871025e17

		Model: {'id': 'f7e9819d50b547929f86eb0871025e17', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.008, 'ICIR': 0.028, 'Rank IC': 0.008, 'Rank ICIR': 0.035}, 'data_train_vec': ['2023-10-04', '2026-01-03'], 'train_time_vec': ['2026-10-04', '2026-10-04'], 'rank_icir': '0.035', 'weight': '0.010'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20261004_16 490000852604823015 (Recorders: 5/5)

	Recorder: 25dea49996a4411cbc77b1ca573d1fc2

		Model: {'id': '25dea49996a4411cbc77b1ca573d1fc2', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.038, 'ICIR': 0.191, 'Rank IC': 0.041, 'Rank ICIR': 0.237}, 'data_train_vec': ['2021-10-04', '2025-07-03'], 'train_time_vec': ['2026-10-04', '2026-10-04'], 'rank_icir': '0.237', 'weight': '0.070'}

	Recorder: 5fa60ed02c6b44aabab2a7a3b4b985ef

		Model: {'id': '5fa60ed02c6b44aabab2a7a3b4b985ef', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.031, 'ICIR': 0.136, 'Rank IC': 0.018, 'Rank ICIR': 0.095}, 'data_train_vec': ['2022-10-04', '2025-10-03'], 'train_time_vec': ['2026-10-04', '2026-10-04'], 'rank_icir': '0.095', 'weight': '0.028'}

	Recorder: f1c7d2e4dacf43f991759c340654ca18

		Model: {'id': 'f1c7d2e4dacf43f991759c340654ca18', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.006, 'ICIR': 0.024, 'Rank IC': 0.003, 'Rank ICIR': 0.015}, 'data_train_vec': ['2023-10-04', '2026-01-03'], 'train_time_vec': ['2026-10-04', '2026-10-04'], 'rank_icir': '0.015', 'weight': '0.004'}

	Recorder: 64a3e2e6aeb84446b7eb1b02fe27200a

		Model: {'id': '64a3e2e6aeb84446b7eb1b02fe27200a', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.042, 'ICIR': 0.204, 'Rank IC': 0.023, 'Rank ICIR': 0.126}, 'data_train_vec': ['2024-10-04', '2026-04-03'], 'train_time_vec': ['2026-10-04', '2026-10-04'], 'rank_icir': '0.126', 'weight': '0.037'}

	Recorder: 3a2c154bbea446818b3554bd43199354

		Model: {'id': '3a2c154bbea446818b3554bd43199354', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.032, 'ICIR': 0.243, 'Rank IC': 0.039, 'Rank ICIR': 0.329}, 'data_train_vec': ['2025-10-04', '2026-07-03'], 'train_time_vec': ['2026-10-04', '2026-10-04'], 'rank_icir': '0.329', 'weight': '0.097'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20261004_16 645089809944866962 (Recorders: 4/5)

	Recorder: 810cc1e2ba34409995e99d58487e6861

		Model: {'id': '810cc1e2ba34409995e99d58487e6861', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.012, 'ICIR': 0.055, 'Rank IC': 0.042, 'Rank ICIR': 0.253}, 'data_train_vec': ['2021-10-04', '2025-07-03'], 'train_time_vec': ['2026-10-04', '2026-10-04'], 'rank_icir': '0.253', 'weight': '0.075'}

	Recorder: 0324d87abcf84f3487928db8261cabc5

		Model: {'id': '0324d87abcf84f3487928db8261cabc5', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.008, 'ICIR': 0.034, 'Rank IC': 0.02, 'Rank ICIR': 0.117}, 'data_train_vec': ['2022-10-04', '2025-10-03'], 'train_time_vec': ['2026-10-04', '2026-10-04'], 'rank_icir': '0.117', 'weight': '0.035'}

	Recorder: e7b3359384d544cca112ad3e096f1b7b

		Model: {'id': 'e7b3359384d544cca112ad3e096f1b7b', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.025, 'ICIR': 0.114, 'Rank IC': 0.009, 'Rank ICIR': 0.052}, 'data_train_vec': ['2024-10-04', '2026-04-03'], 'train_time_vec': ['2026-10-04', '2026-10-04'], 'rank_icir': '0.052', 'weight': '0.015'}

	Recorder: b16b9983100d4e53b9c259f377bc7bd8

		Model: {'id': 'b16b9983100d4e53b9c259f377bc7bd8', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.006, 'ICIR': 0.053, 'Rank IC': 0.01, 'Rank ICIR': 0.129}, 'data_train_vec': ['2025-10-04', '2026-07-03'], 'train_time_vec': ['2026-10-04', '2026-10-04'], 'rank_icir': '0.129', 'weight': '0.038'}
