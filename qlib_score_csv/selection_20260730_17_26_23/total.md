# params 
 {'predict_dates': [{'start': '2026-07-30', 'end': '2026-07-30'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260730_17 577980927510300731 (Recorders: 2/5)

	Recorder: 521bf991ccaf4d1abd400eff906cd873

		Model: {'id': '521bf991ccaf4d1abd400eff906cd873', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.009, 'ICIR': 0.056, 'Rank IC': 0.027, 'Rank ICIR': 0.177}, 'data_train_vec': ['2021-07-28', '2025-04-27'], 'train_time_vec': ['2026-07-30', '2026-07-30'], 'rank_icir': '0.177', 'weight': '0.387'}

	Recorder: ac8e9ee1a9c548a492dec67351b2ed38

		Model: {'id': 'ac8e9ee1a9c548a492dec67351b2ed38', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.01, 'ICIR': 0.053, 'Rank IC': 0.018, 'Rank ICIR': 0.133}, 'data_train_vec': ['2023-07-30', '2025-10-29'], 'train_time_vec': ['2026-07-30', '2026-07-30'], 'rank_icir': '0.133', 'weight': '0.291'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260730_14 339679334253098128 (Recorders: 1/5)

	Recorder: 989b28e9719b4c879c6b1e6a25594660

		Model: {'id': '989b28e9719b4c879c6b1e6a25594660', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.005, 'ICIR': 0.024, 'Rank IC': 0.026, 'Rank ICIR': 0.147}, 'data_train_vec': ['2021-07-28', '2025-04-27'], 'train_time_vec': ['2026-07-30', '2026-07-30'], 'rank_icir': '0.147', 'weight': '0.322'}
