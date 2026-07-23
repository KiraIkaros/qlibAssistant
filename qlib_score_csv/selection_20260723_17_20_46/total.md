# params 
 {'predict_dates': [{'start': '2026-07-23', 'end': '2026-07-23'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260723_17 897183798970482942 (Recorders: 1/5)

	Recorder: 37a37d63164249989c413741d7d91870

		Model: {'id': '37a37d63164249989c413741d7d91870', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.007, 'ICIR': 0.038, 'Rank IC': 0.015, 'Rank ICIR': 0.123}, 'data_train_vec': ['2023-07-23', '2025-10-22'], 'train_time_vec': ['2026-07-23', '2026-07-23'], 'rank_icir': '0.123', 'weight': '0.153'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260723_16 151529532456637898 (Recorders: 3/5)

	Recorder: 2fe1ef0225344e03ab9e98b01f512c07

		Model: {'id': '2fe1ef0225344e03ab9e98b01f512c07', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.009, 'ICIR': 0.063, 'Rank IC': 0.026, 'Rank ICIR': 0.161}, 'data_train_vec': ['2021-07-23', '2025-04-22'], 'train_time_vec': ['2026-07-23', '2026-07-23'], 'rank_icir': '0.161', 'weight': '0.201'}

	Recorder: c655c784a6e349529122575305a3bc34

		Model: {'id': 'c655c784a6e349529122575305a3bc34', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.001, 'ICIR': 0.014, 'Rank IC': 0.009, 'Rank ICIR': 0.079}, 'data_train_vec': ['2022-07-23', '2025-07-22'], 'train_time_vec': ['2026-07-23', '2026-07-23'], 'rank_icir': '0.079', 'weight': '0.099'}

	Recorder: ea102a66ad134745a588db3ab5ecbd26

		Model: {'id': 'ea102a66ad134745a588db3ab5ecbd26', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.015, 'ICIR': 0.122, 'Rank IC': 0.025, 'Rank ICIR': 0.215}, 'data_train_vec': ['2023-07-23', '2025-10-22'], 'train_time_vec': ['2026-07-23', '2026-07-23'], 'rank_icir': '0.215', 'weight': '0.268'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260723_14 122259300407538956 (Recorders: 1/5)

	Recorder: 98a0635531e34f77a6f20a24210f1bd2

		Model: {'id': '98a0635531e34f77a6f20a24210f1bd2', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.009, 'ICIR': 0.052, 'Rank IC': 0.037, 'Rank ICIR': 0.224}, 'data_train_vec': ['2021-07-23', '2025-04-22'], 'train_time_vec': ['2026-07-23', '2026-07-23'], 'rank_icir': '0.224', 'weight': '0.279'}
