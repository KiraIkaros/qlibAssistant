# params 
 {'predict_dates': [{'start': '2026-08-21', 'end': '2026-08-21'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260821_15 951510664013609457 (Recorders: 2/5)

	Recorder: 1a8dc9ca472e41bdb475e93a5e2cee3e

		Model: {'id': '1a8dc9ca472e41bdb475e93a5e2cee3e', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.014, 'ICIR': 0.08, 'Rank IC': 0.03, 'Rank ICIR': 0.231}, 'data_train_vec': ['2022-08-21', '2025-08-20'], 'train_time_vec': ['2026-08-21', '2026-08-21'], 'rank_icir': '0.231', 'weight': '0.130'}

	Recorder: 4278d1be89b94b51bbec19c06a49cda9

		Model: {'id': '4278d1be89b94b51bbec19c06a49cda9', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.011, 'ICIR': 0.047, 'Rank IC': 0.023, 'Rank ICIR': 0.158}, 'data_train_vec': ['2023-08-21', '2025-11-20'], 'train_time_vec': ['2026-08-21', '2026-08-21'], 'rank_icir': '0.158', 'weight': '0.089'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260821_15 623228315781924191 (Recorders: 1/5)

	Recorder: ef72dd58f27846ce97249d4fe2133a58

		Model: {'id': 'ef72dd58f27846ce97249d4fe2133a58', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.012, 'ICIR': 0.067, 'Rank IC': 0.022, 'Rank ICIR': 0.157}, 'data_train_vec': ['2023-08-21', '2025-11-20'], 'train_time_vec': ['2026-08-21', '2026-08-21'], 'rank_icir': '0.157', 'weight': '0.088'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260821_13 945250827712499160 (Recorders: 3/5)

	Recorder: 4fcd5d3f742245b6b5e3c30f2c54c907

		Model: {'id': '4fcd5d3f742245b6b5e3c30f2c54c907', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.017, 'ICIR': 0.087, 'Rank IC': 0.03, 'Rank ICIR': 0.173}, 'data_train_vec': ['2021-08-21', '2025-05-20'], 'train_time_vec': ['2026-08-21', '2026-08-21'], 'rank_icir': '0.173', 'weight': '0.097'}

	Recorder: 3701ba2f138647eab57512b2683280ab

		Model: {'id': '3701ba2f138647eab57512b2683280ab', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.021, 'ICIR': 0.095, 'Rank IC': 0.032, 'Rank ICIR': 0.188}, 'data_train_vec': ['2022-08-21', '2025-08-20'], 'train_time_vec': ['2026-08-21', '2026-08-21'], 'rank_icir': '0.188', 'weight': '0.106'}

	Recorder: 609710e8bd8641dc87fc8777ecdbfbb2

		Model: {'id': '609710e8bd8641dc87fc8777ecdbfbb2', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.003, 'ICIR': 0.014, 'Rank IC': 0.01, 'Rank ICIR': 0.058}, 'data_train_vec': ['2023-08-21', '2025-11-20'], 'train_time_vec': ['2026-08-21', '2026-08-21'], 'rank_icir': '0.058', 'weight': '0.033'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260821_13 412797089239833456 (Recorders: 3/5)

	Recorder: e07a47357e3e4f0ca28f945779136e54

		Model: {'id': 'e07a47357e3e4f0ca28f945779136e54', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.014, 'ICIR': 0.067, 'Rank IC': 0.026, 'Rank ICIR': 0.16}, 'data_train_vec': ['2021-08-21', '2025-05-20'], 'train_time_vec': ['2026-08-21', '2026-08-21'], 'rank_icir': '0.160', 'weight': '0.090'}

	Recorder: bdf05c322f7a4634aec492d81f956dc9

		Model: {'id': 'bdf05c322f7a4634aec492d81f956dc9', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.031, 'ICIR': 0.163, 'Rank IC': 0.036, 'Rank ICIR': 0.226}, 'data_train_vec': ['2022-08-21', '2025-08-20'], 'train_time_vec': ['2026-08-21', '2026-08-21'], 'rank_icir': '0.226', 'weight': '0.127'}

	Recorder: d4375793ad3e46b4914d537887702a9f

		Model: {'id': 'd4375793ad3e46b4914d537887702a9f', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.041, 'ICIR': 0.158, 'Rank IC': 0.012, 'Rank ICIR': 0.065}, 'data_train_vec': ['2025-08-21', '2026-05-20'], 'train_time_vec': ['2026-08-21', '2026-08-21'], 'rank_icir': '0.065', 'weight': '0.037'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260821_13 357219446895752394 (Recorders: 3/5)

	Recorder: 21c3872ccb124dbb816fc87be2513278

		Model: {'id': '21c3872ccb124dbb816fc87be2513278', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.007, 'ICIR': 0.031, 'Rank IC': 0.019, 'Rank ICIR': 0.107}, 'data_train_vec': ['2021-08-21', '2025-05-20'], 'train_time_vec': ['2026-08-21', '2026-08-21'], 'rank_icir': '0.107', 'weight': '0.060'}

	Recorder: 4f5a93fd9547426f82970e47b23ccd43

		Model: {'id': '4f5a93fd9547426f82970e47b23ccd43', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.004, 'ICIR': 0.019, 'Rank IC': 0.025, 'Rank ICIR': 0.161}, 'data_train_vec': ['2022-08-21', '2025-08-20'], 'train_time_vec': ['2026-08-21', '2026-08-21'], 'rank_icir': '0.161', 'weight': '0.091'}

	Recorder: 7589173805f841ddb820addc22b521c4

		Model: {'id': '7589173805f841ddb820addc22b521c4', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.029, 'ICIR': 0.083, 'Rank IC': 0.021, 'Rank ICIR': 0.091}, 'data_train_vec': ['2025-08-21', '2026-05-20'], 'train_time_vec': ['2026-08-21', '2026-08-21'], 'rank_icir': '0.091', 'weight': '0.051'}
