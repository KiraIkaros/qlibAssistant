# params 
 {'predict_dates': [{'start': '2026-07-30', 'end': '2026-07-30'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260731_17 407389155158408652 (Recorders: 2/5)

	Recorder: 9f1d9248eb5b4fa0afa09521e49bb70e

		Model: {'id': '9f1d9248eb5b4fa0afa09521e49bb70e', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.009, 'ICIR': 0.056, 'Rank IC': 0.027, 'Rank ICIR': 0.177}, 'data_train_vec': ['2021-07-28', '2025-04-27'], 'train_time_vec': ['2026-07-31', '2026-07-31'], 'rank_icir': '0.177', 'weight': '0.385'}

	Recorder: 7d02d9ac25ea4383b60a4952830f6daf

		Model: {'id': '7d02d9ac25ea4383b60a4952830f6daf', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.01, 'ICIR': 0.053, 'Rank IC': 0.018, 'Rank ICIR': 0.133}, 'data_train_vec': ['2023-07-30', '2025-10-29'], 'train_time_vec': ['2026-07-31', '2026-07-31'], 'rank_icir': '0.133', 'weight': '0.289'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260731_14 257916632999574193 (Recorders: 1/5)

	Recorder: 4cdb60808a9045e5849e64148bbf6a26

		Model: {'id': '4cdb60808a9045e5849e64148bbf6a26', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.007, 'ICIR': 0.037, 'Rank IC': 0.026, 'Rank ICIR': 0.15}, 'data_train_vec': ['2021-07-28', '2025-04-27'], 'train_time_vec': ['2026-07-31', '2026-07-31'], 'rank_icir': '0.150', 'weight': '0.326'}
