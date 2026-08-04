# params 
 {'predict_dates': [{'start': '2026-08-04', 'end': '2026-08-04'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260804_17 345555485119079096 (Recorders: 2/5)

	Recorder: dfc93d68e3ce485f8509c2134c44e113

		Model: {'id': 'dfc93d68e3ce485f8509c2134c44e113', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.007, 'ICIR': 0.045, 'Rank IC': 0.028, 'Rank ICIR': 0.177}, 'data_train_vec': ['2021-08-04', '2025-05-03'], 'train_time_vec': ['2026-08-04', '2026-08-04'], 'rank_icir': '0.177', 'weight': '0.325'}

	Recorder: a06372b158ce48fcb62707718ae3d7d4

		Model: {'id': 'a06372b158ce48fcb62707718ae3d7d4', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.02, 'ICIR': 0.111, 'Rank IC': 0.024, 'Rank ICIR': 0.173}, 'data_train_vec': ['2023-08-04', '2025-11-03'], 'train_time_vec': ['2026-08-04', '2026-08-04'], 'rank_icir': '0.173', 'weight': '0.317'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260804_14 278608065891377434 (Recorders: 1/5)

	Recorder: 69306323b38c424fa1c8ada7680c0425

		Model: {'id': '69306323b38c424fa1c8ada7680c0425', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.013, 'ICIR': 0.068, 'Rank IC': 0.033, 'Rank ICIR': 0.195}, 'data_train_vec': ['2021-08-04', '2025-05-03'], 'train_time_vec': ['2026-08-04', '2026-08-04'], 'rank_icir': '0.195', 'weight': '0.358'}
