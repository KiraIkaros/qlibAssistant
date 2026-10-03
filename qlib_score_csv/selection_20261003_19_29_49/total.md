# params 
 {'predict_dates': [{'start': '2026-09-30', 'end': '2026-09-30'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20261003_19 861389437918715495 (Recorders: 4/5)

	Recorder: 2d389f843dc549158b62cf09a733530f

		Model: {'id': '2d389f843dc549158b62cf09a733530f', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.035, 'ICIR': 0.214, 'Rank IC': 0.041, 'Rank ICIR': 0.208}, 'data_train_vec': ['2021-10-03', '2025-07-02'], 'train_time_vec': ['2026-10-03', '2026-10-03'], 'rank_icir': '0.208', 'weight': '0.072'}

	Recorder: 46f9467479fb4228a3e01685aecb5d17

		Model: {'id': '46f9467479fb4228a3e01685aecb5d17', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.013, 'ICIR': 0.059, 'Rank IC': 0.027, 'Rank ICIR': 0.157}, 'data_train_vec': ['2022-10-03', '2025-10-02'], 'train_time_vec': ['2026-10-03', '2026-10-03'], 'rank_icir': '0.157', 'weight': '0.054'}

	Recorder: 29089b91db18488490cf6fe33e1ea7ed

		Model: {'id': '29089b91db18488490cf6fe33e1ea7ed', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.013, 'ICIR': 0.043, 'Rank IC': 0.019, 'Rank ICIR': 0.093}, 'data_train_vec': ['2023-10-03', '2026-01-02'], 'train_time_vec': ['2026-10-03', '2026-10-03'], 'rank_icir': '0.093', 'weight': '0.032'}

	Recorder: 414a8bf2667e4e78bf4bcffb3950a472

		Model: {'id': '414a8bf2667e4e78bf4bcffb3950a472', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.03, 'ICIR': 0.198, 'Rank IC': 0.025, 'Rank ICIR': 0.166}, 'data_train_vec': ['2024-10-03', '2026-04-02'], 'train_time_vec': ['2026-10-03', '2026-10-03'], 'rank_icir': '0.166', 'weight': '0.057'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20261003_18 386261707533165874 (Recorders: 3/5)

	Recorder: 9770c312a52241fdab79980a999b2de9

		Model: {'id': '9770c312a52241fdab79980a999b2de9', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.027, 'ICIR': 0.18, 'Rank IC': 0.035, 'Rank ICIR': 0.216}, 'data_train_vec': ['2021-10-03', '2025-07-02'], 'train_time_vec': ['2026-10-03', '2026-10-03'], 'rank_icir': '0.216', 'weight': '0.074'}

	Recorder: ed23b594b1894379b913f77a6a0a6c9e

		Model: {'id': 'ed23b594b1894379b913f77a6a0a6c9e', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.029, 'ICIR': 0.155, 'Rank IC': 0.035, 'Rank ICIR': 0.195}, 'data_train_vec': ['2022-10-03', '2025-10-02'], 'train_time_vec': ['2026-10-03', '2026-10-03'], 'rank_icir': '0.195', 'weight': '0.067'}

	Recorder: db65d873e900453eb304e63730c44c5d

		Model: {'id': 'db65d873e900453eb304e63730c44c5d', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.009, 'ICIR': 0.038, 'Rank IC': 0.013, 'Rank ICIR': 0.061}, 'data_train_vec': ['2023-10-03', '2026-01-02'], 'train_time_vec': ['2026-10-03', '2026-10-03'], 'rank_icir': '0.061', 'weight': '0.021'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20261003_16 118611722403430076 (Recorders: 3/5)

	Recorder: 85a4db340d1b451fa37aaafa02ccc62f

		Model: {'id': '85a4db340d1b451fa37aaafa02ccc62f', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.038, 'ICIR': 0.184, 'Rank IC': 0.049, 'Rank ICIR': 0.282}, 'data_train_vec': ['2021-10-03', '2025-07-02'], 'train_time_vec': ['2026-10-03', '2026-10-03'], 'rank_icir': '0.282', 'weight': '0.097'}

	Recorder: e4d19a7f4d3a464bbace2af08d6335ff

		Model: {'id': 'e4d19a7f4d3a464bbace2af08d6335ff', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.025, 'ICIR': 0.107, 'Rank IC': 0.027, 'Rank ICIR': 0.141}, 'data_train_vec': ['2022-10-03', '2025-10-02'], 'train_time_vec': ['2026-10-03', '2026-10-03'], 'rank_icir': '0.141', 'weight': '0.049'}

	Recorder: 689d3c34b2264d138ee7bec45abddf22

		Model: {'id': '689d3c34b2264d138ee7bec45abddf22', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.013, 'ICIR': 0.045, 'Rank IC': 0.013, 'Rank ICIR': 0.058}, 'data_train_vec': ['2023-10-03', '2026-01-02'], 'train_time_vec': ['2026-10-03', '2026-10-03'], 'rank_icir': '0.058', 'weight': '0.020'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20261003_16 284985278343483726 (Recorders: 5/5)

	Recorder: 7b51acbfc9044e3bbd650dee089901ee

		Model: {'id': '7b51acbfc9044e3bbd650dee089901ee', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.038, 'ICIR': 0.188, 'Rank IC': 0.04, 'Rank ICIR': 0.233}, 'data_train_vec': ['2021-10-03', '2025-07-02'], 'train_time_vec': ['2026-10-03', '2026-10-03'], 'rank_icir': '0.233', 'weight': '0.080'}

	Recorder: 00b86262e8db442786e0ab0305df3514

		Model: {'id': '00b86262e8db442786e0ab0305df3514', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.031, 'ICIR': 0.136, 'Rank IC': 0.018, 'Rank ICIR': 0.094}, 'data_train_vec': ['2022-10-03', '2025-10-02'], 'train_time_vec': ['2026-10-03', '2026-10-03'], 'rank_icir': '0.094', 'weight': '0.032'}

	Recorder: 2d7f33870f154d3fad279cde182bd434

		Model: {'id': '2d7f33870f154d3fad279cde182bd434', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.01, 'ICIR': 0.037, 'Rank IC': 0.005, 'Rank ICIR': 0.025}, 'data_train_vec': ['2023-10-03', '2026-01-02'], 'train_time_vec': ['2026-10-03', '2026-10-03'], 'rank_icir': '0.025', 'weight': '0.009'}

	Recorder: 0730b86c626f41459da17e8936f72017

		Model: {'id': '0730b86c626f41459da17e8936f72017', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.052, 'ICIR': 0.255, 'Rank IC': 0.028, 'Rank ICIR': 0.159}, 'data_train_vec': ['2024-10-03', '2026-04-02'], 'train_time_vec': ['2026-10-03', '2026-10-03'], 'rank_icir': '0.159', 'weight': '0.055'}

	Recorder: 6be02f24ec9a4f0292399493b2ca42f5

		Model: {'id': '6be02f24ec9a4f0292399493b2ca42f5', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.051, 'ICIR': 0.354, 'Rank IC': 0.048, 'Rank ICIR': 0.411}, 'data_train_vec': ['2025-10-03', '2026-07-02'], 'train_time_vec': ['2026-10-03', '2026-10-03'], 'rank_icir': '0.411', 'weight': '0.141'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20261003_16 235318751202262864 (Recorders: 3/5)

	Recorder: 4929cba1ae254eafbbfa9f79f633b887

		Model: {'id': '4929cba1ae254eafbbfa9f79f633b887', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.001, 'ICIR': 0.005, 'Rank IC': 0.035, 'Rank ICIR': 0.215}, 'data_train_vec': ['2021-10-03', '2025-07-02'], 'train_time_vec': ['2026-10-03', '2026-10-03'], 'rank_icir': '0.215', 'weight': '0.074'}

	Recorder: 0857aa379f6e425989575ee83577cd88

		Model: {'id': '0857aa379f6e425989575ee83577cd88', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.009, 'ICIR': 0.035, 'Rank IC': 0.021, 'Rank ICIR': 0.123}, 'data_train_vec': ['2022-10-03', '2025-10-02'], 'train_time_vec': ['2026-10-03', '2026-10-03'], 'rank_icir': '0.123', 'weight': '0.042'}

	Recorder: f07c2d8ca65547a695b810ad3dfa37c7

		Model: {'id': 'f07c2d8ca65547a695b810ad3dfa37c7', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.025, 'ICIR': 0.118, 'Rank IC': 0.01, 'Rank ICIR': 0.068}, 'data_train_vec': ['2024-10-03', '2026-04-02'], 'train_time_vec': ['2026-10-03', '2026-10-03'], 'rank_icir': '0.068', 'weight': '0.023'}
