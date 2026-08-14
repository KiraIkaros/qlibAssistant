# params 
 {'predict_dates': [{'start': '2026-08-14', 'end': '2026-08-14'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260814_16 663641356525634014 (Recorders: 3/5)

	Recorder: 691b6a6514704d44b73060a986e1eb13

		Model: {'id': '691b6a6514704d44b73060a986e1eb13', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.008, 'ICIR': 0.049, 'Rank IC': 0.014, 'Rank ICIR': 0.073}, 'data_train_vec': ['2021-08-14', '2025-05-13'], 'train_time_vec': ['2026-08-14', '2026-08-14'], 'rank_icir': '0.073', 'weight': '0.060'}

	Recorder: 76b089b78fb44c01b80b8a6d590c78b9

		Model: {'id': '76b089b78fb44c01b80b8a6d590c78b9', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.006, 'ICIR': 0.029, 'Rank IC': 0.016, 'Rank ICIR': 0.092}, 'data_train_vec': ['2022-08-14', '2025-08-13'], 'train_time_vec': ['2026-08-14', '2026-08-14'], 'rank_icir': '0.092', 'weight': '0.076'}

	Recorder: 3e8e77ee0e914633aa002cf7b337f393

		Model: {'id': '3e8e77ee0e914633aa002cf7b337f393', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.009, 'ICIR': 0.047, 'Rank IC': 0.015, 'Rank ICIR': 0.111}, 'data_train_vec': ['2023-08-14', '2025-11-13'], 'train_time_vec': ['2026-08-14', '2026-08-14'], 'rank_icir': '0.111', 'weight': '0.091'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260814_16 705882421921085010 (Recorders: 2/5)

	Recorder: c2f9db0d2a2741bc8d97c3ddb23f4513

		Model: {'id': 'c2f9db0d2a2741bc8d97c3ddb23f4513', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.004, 'ICIR': 0.036, 'Rank IC': 0.013, 'Rank ICIR': 0.096}, 'data_train_vec': ['2022-08-14', '2025-08-13'], 'train_time_vec': ['2026-08-14', '2026-08-14'], 'rank_icir': '0.096', 'weight': '0.079'}

	Recorder: 9914ec8f036442d4bbd913620ff6cdb0

		Model: {'id': '9914ec8f036442d4bbd913620ff6cdb0', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.018, 'ICIR': 0.097, 'Rank IC': 0.024, 'Rank ICIR': 0.177}, 'data_train_vec': ['2023-08-14', '2025-11-13'], 'train_time_vec': ['2026-08-14', '2026-08-14'], 'rank_icir': '0.177', 'weight': '0.146'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260814_13 626886423296121972 (Recorders: 3/5)

	Recorder: a040cf87a78e4e00b10a5ab7be5c96f5

		Model: {'id': 'a040cf87a78e4e00b10a5ab7be5c96f5', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.013, 'ICIR': 0.067, 'Rank IC': 0.028, 'Rank ICIR': 0.162}, 'data_train_vec': ['2021-08-14', '2025-05-13'], 'train_time_vec': ['2026-08-14', '2026-08-14'], 'rank_icir': '0.162', 'weight': '0.133'}

	Recorder: 98a6752759384c6ca658df5e99d7da0f

		Model: {'id': '98a6752759384c6ca658df5e99d7da0f', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.012, 'ICIR': 0.056, 'Rank IC': 0.026, 'Rank ICIR': 0.147}, 'data_train_vec': ['2022-08-14', '2025-08-13'], 'train_time_vec': ['2026-08-14', '2026-08-14'], 'rank_icir': '0.147', 'weight': '0.121'}

	Recorder: a37c3b1e4be7493c9e275c119f31f43f

		Model: {'id': 'a37c3b1e4be7493c9e275c119f31f43f', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.001, 'ICIR': 0.005, 'Rank IC': 0.009, 'Rank ICIR': 0.051}, 'data_train_vec': ['2023-08-14', '2025-11-13'], 'train_time_vec': ['2026-08-14', '2026-08-14'], 'rank_icir': '0.051', 'weight': '0.042'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260814_13 951642168062077972 (Recorders: 2/5)

	Recorder: fbbc99b3fdca4349855d9a26c7088e6d

		Model: {'id': 'fbbc99b3fdca4349855d9a26c7088e6d', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.004, 'ICIR': 0.022, 'Rank IC': 0.022, 'Rank ICIR': 0.138}, 'data_train_vec': ['2021-08-14', '2025-05-13'], 'train_time_vec': ['2026-08-14', '2026-08-14'], 'rank_icir': '0.138', 'weight': '0.114'}

	Recorder: 362d8ff880c3451eb7b3fac590954722

		Model: {'id': '362d8ff880c3451eb7b3fac590954722', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.016, 'ICIR': 0.083, 'Rank IC': 0.027, 'Rank ICIR': 0.167}, 'data_train_vec': ['2022-08-14', '2025-08-13'], 'train_time_vec': ['2026-08-14', '2026-08-14'], 'rank_icir': '0.167', 'weight': '0.138'}
