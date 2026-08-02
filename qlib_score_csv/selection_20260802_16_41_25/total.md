# params 
 {'predict_dates': [{'start': '2026-07-31', 'end': '2026-07-31'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260802_16 517277393586639223 (Recorders: 1/5)

	Recorder: ff5acd9722734f8e974b37909ef3fa08

		Model: {'id': 'ff5acd9722734f8e974b37909ef3fa08', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.005, 'ICIR': 0.032, 'Rank IC': 0.028, 'Rank ICIR': 0.139}, 'data_train_vec': ['2021-08-02', '2025-05-01'], 'train_time_vec': ['2026-08-02', '2026-08-02'], 'rank_icir': '0.139', 'weight': '0.227'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260802_16 370707708167327086 (Recorders: 2/5)

	Recorder: 5641a5f68bbc4954ad99773113a998c2

		Model: {'id': '5641a5f68bbc4954ad99773113a998c2', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.01, 'ICIR': 0.062, 'Rank IC': 0.029, 'Rank ICIR': 0.176}, 'data_train_vec': ['2021-08-02', '2025-05-01'], 'train_time_vec': ['2026-08-02', '2026-08-02'], 'rank_icir': '0.176', 'weight': '0.287'}

	Recorder: 62cbcd9f68e54196ac5f192f054b63c8

		Model: {'id': '62cbcd9f68e54196ac5f192f054b63c8', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.013, 'ICIR': 0.069, 'Rank IC': 0.018, 'Rank ICIR': 0.13}, 'data_train_vec': ['2023-08-02', '2025-11-01'], 'train_time_vec': ['2026-08-02', '2026-08-02'], 'rank_icir': '0.130', 'weight': '0.212'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260802_14 917944437780348766 (Recorders: 1/5)

	Recorder: 20de9f7658644f9399cba37fffea2453

		Model: {'id': '20de9f7658644f9399cba37fffea2453', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.009, 'ICIR': 0.049, 'Rank IC': 0.029, 'Rank ICIR': 0.168}, 'data_train_vec': ['2021-08-02', '2025-05-01'], 'train_time_vec': ['2026-08-02', '2026-08-02'], 'rank_icir': '0.168', 'weight': '0.274'}
