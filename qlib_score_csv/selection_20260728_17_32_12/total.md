# params 
 {'predict_dates': [{'start': '2026-07-28', 'end': '2026-07-28'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260728_17 681565773560344754 (Recorders: 1/5)

	Recorder: b795779d70b0493d990bd6b9e404e52c

		Model: {'id': 'b795779d70b0493d990bd6b9e404e52c', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.015, 'ICIR': 0.107, 'Rank IC': 0.019, 'Rank ICIR': 0.163}, 'data_train_vec': ['2023-07-28', '2025-10-27'], 'train_time_vec': ['2026-07-28', '2026-07-28'], 'rank_icir': '0.163', 'weight': '0.207'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260728_17 259392526982291473 (Recorders: 2/5)

	Recorder: ba646347bc0f48899dddd6afeca3a052

		Model: {'id': 'ba646347bc0f48899dddd6afeca3a052', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.012, 'ICIR': 0.075, 'Rank IC': 0.031, 'Rank ICIR': 0.2}, 'data_train_vec': ['2021-07-28', '2025-04-27'], 'train_time_vec': ['2026-07-28', '2026-07-28'], 'rank_icir': '0.200', 'weight': '0.254'}

	Recorder: 63f76fe01ad446fab065a06638a34c6b

		Model: {'id': '63f76fe01ad446fab065a06638a34c6b', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.024, 'ICIR': 0.164, 'Rank IC': 0.027, 'Rank ICIR': 0.236}, 'data_train_vec': ['2023-07-28', '2025-10-27'], 'train_time_vec': ['2026-07-28', '2026-07-28'], 'rank_icir': '0.236', 'weight': '0.299'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260728_14 413812461025663506 (Recorders: 1/5)

	Recorder: 9a0d4a3a9a5b45e59d2979f37dfb033f

		Model: {'id': '9a0d4a3a9a5b45e59d2979f37dfb033f', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.01, 'ICIR': 0.055, 'Rank IC': 0.032, 'Rank ICIR': 0.189}, 'data_train_vec': ['2021-07-28', '2025-04-27'], 'train_time_vec': ['2026-07-28', '2026-07-28'], 'rank_icir': '0.189', 'weight': '0.240'}
