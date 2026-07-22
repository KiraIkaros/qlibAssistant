# params 
 {'predict_dates': [{'start': '2026-07-20', 'end': '2026-07-20'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260722_17 341521130985386807 (Recorders: 2/5)

	Recorder: ed70b7e4fcf742f6a7363443aeab412c

		Model: {'id': 'ed70b7e4fcf742f6a7363443aeab412c', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.013, 'ICIR': 0.091, 'Rank IC': 0.035, 'Rank ICIR': 0.223}, 'data_train_vec': ['2021-07-22', '2025-04-21'], 'train_time_vec': ['2026-07-22', '2026-07-22'], 'rank_icir': '0.223', 'weight': '0.293'}

	Recorder: a9032782ec6e4203b5f921214a7690fd

		Model: {'id': 'a9032782ec6e4203b5f921214a7690fd', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.01, 'ICIR': 0.075, 'Rank IC': 0.021, 'Rank ICIR': 0.183}, 'data_train_vec': ['2023-07-22', '2025-10-21'], 'train_time_vec': ['2026-07-22', '2026-07-22'], 'rank_icir': '0.183', 'weight': '0.241'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260722_14 929057788342407684 (Recorders: 2/5)

	Recorder: 0309426addda455599784368dbb91c97

		Model: {'id': '0309426addda455599784368dbb91c97', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.007, 'ICIR': 0.045, 'Rank IC': 0.036, 'Rank ICIR': 0.218}, 'data_train_vec': ['2021-07-22', '2025-04-21'], 'train_time_vec': ['2026-07-22', '2026-07-22'], 'rank_icir': '0.218', 'weight': '0.287'}

	Recorder: b469303c2e3b4323b5017ffa4dfb8ee1

		Model: {'id': 'b469303c2e3b4323b5017ffa4dfb8ee1', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.002, 'ICIR': 0.017, 'Rank IC': 0.021, 'Rank ICIR': 0.136}, 'data_train_vec': ['2022-07-22', '2025-07-21'], 'train_time_vec': ['2026-07-22', '2026-07-22'], 'rank_icir': '0.136', 'weight': '0.179'}
