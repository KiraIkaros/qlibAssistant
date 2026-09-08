# params 
 {'predict_dates': [{'start': '2026-09-04', 'end': '2026-09-04'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260908_19 990900598886659187 (Recorders: 2/5)

	Recorder: 72bd9cbf34d8475f9acada151a25aaa2

		Model: {'id': '72bd9cbf34d8475f9acada151a25aaa2', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.02, 'ICIR': 0.096, 'Rank IC': 0.037, 'Rank ICIR': 0.253}, 'data_train_vec': ['2022-09-08', '2025-09-07'], 'train_time_vec': ['2026-09-08', '2026-09-08'], 'rank_icir': '0.253', 'weight': '0.112'}

	Recorder: 3a9f41bf56334d279715b79845b9b3d3

		Model: {'id': '3a9f41bf56334d279715b79845b9b3d3', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.007, 'ICIR': 0.026, 'Rank IC': 0.011, 'Rank ICIR': 0.071}, 'data_train_vec': ['2023-09-08', '2025-12-07'], 'train_time_vec': ['2026-09-08', '2026-09-08'], 'rank_icir': '0.071', 'weight': '0.031'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260908_19 989757596131920411 (Recorders: 3/5)

	Recorder: c4734e2377cf4e01b97245c1874a1f3d

		Model: {'id': 'c4734e2377cf4e01b97245c1874a1f3d', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.01, 'ICIR': 0.067, 'Rank IC': 0.021, 'Rank ICIR': 0.155}, 'data_train_vec': ['2021-09-08', '2025-06-07'], 'train_time_vec': ['2026-09-08', '2026-09-08'], 'rank_icir': '0.155', 'weight': '0.068'}

	Recorder: 3cddd44b1e7945ee82354c261f53ac18

		Model: {'id': '3cddd44b1e7945ee82354c261f53ac18', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.017, 'ICIR': 0.139, 'Rank IC': 0.026, 'Rank ICIR': 0.22}, 'data_train_vec': ['2022-09-08', '2025-09-07'], 'train_time_vec': ['2026-09-08', '2026-09-08'], 'rank_icir': '0.220', 'weight': '0.097'}

	Recorder: a1c255c950e04c66a7956576fdb8b310

		Model: {'id': 'a1c255c950e04c66a7956576fdb8b310', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.009, 'ICIR': 0.049, 'Rank IC': 0.012, 'Rank ICIR': 0.075}, 'data_train_vec': ['2023-09-08', '2025-12-07'], 'train_time_vec': ['2026-09-08', '2026-09-08'], 'rank_icir': '0.075', 'weight': '0.033'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260908_16 713378218179945108 (Recorders: 3/5)

	Recorder: db3cb1a10d84479c8ed71304e62f56d7

		Model: {'id': 'db3cb1a10d84479c8ed71304e62f56d7', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.019, 'ICIR': 0.096, 'Rank IC': 0.031, 'Rank ICIR': 0.182}, 'data_train_vec': ['2021-09-08', '2025-06-07'], 'train_time_vec': ['2026-09-08', '2026-09-08'], 'rank_icir': '0.182', 'weight': '0.080'}

	Recorder: 1d992ddb3203456bb177ca6cfebc3ade

		Model: {'id': '1d992ddb3203456bb177ca6cfebc3ade', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.038, 'ICIR': 0.185, 'Rank IC': 0.047, 'Rank ICIR': 0.291}, 'data_train_vec': ['2022-09-08', '2025-09-07'], 'train_time_vec': ['2026-09-08', '2026-09-08'], 'rank_icir': '0.291', 'weight': '0.128'}

	Recorder: d72fe82f18694c4aa4e08ff929f91cab

		Model: {'id': 'd72fe82f18694c4aa4e08ff929f91cab', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.004, 'ICIR': 0.013, 'Rank IC': 0.009, 'Rank ICIR': 0.046}, 'data_train_vec': ['2023-09-08', '2025-12-07'], 'train_time_vec': ['2026-09-08', '2026-09-08'], 'rank_icir': '0.046', 'weight': '0.020'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260908_16 150226362923081513 (Recorders: 3/5)

	Recorder: b89d67b59beb4533b8967d9c20b533e3

		Model: {'id': 'b89d67b59beb4533b8967d9c20b533e3', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.018, 'ICIR': 0.089, 'Rank IC': 0.027, 'Rank ICIR': 0.166}, 'data_train_vec': ['2021-09-08', '2025-06-07'], 'train_time_vec': ['2026-09-08', '2026-09-08'], 'rank_icir': '0.166', 'weight': '0.073'}

	Recorder: e79e80f74c0a4a0ea58b979112cee9e6

		Model: {'id': 'e79e80f74c0a4a0ea58b979112cee9e6', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.043, 'ICIR': 0.23, 'Rank IC': 0.039, 'Rank ICIR': 0.249}, 'data_train_vec': ['2022-09-08', '2025-09-07'], 'train_time_vec': ['2026-09-08', '2026-09-08'], 'rank_icir': '0.249', 'weight': '0.110'}

	Recorder: d65cd8126bfc441884ade3c7c8ae8ab5

		Model: {'id': 'd65cd8126bfc441884ade3c7c8ae8ab5', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.033, 'ICIR': 0.157, 'Rank IC': 0.019, 'Rank ICIR': 0.09}, 'data_train_vec': ['2025-09-08', '2026-06-07'], 'train_time_vec': ['2026-09-08', '2026-09-08'], 'rank_icir': '0.090', 'weight': '0.040'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260908_16 712596927816448552 (Recorders: 2/5)

	Recorder: 5d90ecba4b904828b384eee99181cacd

		Model: {'id': '5d90ecba4b904828b384eee99181cacd', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.004, 'ICIR': 0.019, 'Rank IC': 0.029, 'Rank ICIR': 0.17}, 'data_train_vec': ['2021-09-08', '2025-06-07'], 'train_time_vec': ['2026-09-08', '2026-09-08'], 'rank_icir': '0.170', 'weight': '0.075'}

	Recorder: 7a309d068b834e1692b3473d200f4301

		Model: {'id': '7a309d068b834e1692b3473d200f4301', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.021, 'ICIR': 0.105, 'Rank IC': 0.044, 'Rank ICIR': 0.298}, 'data_train_vec': ['2022-09-08', '2025-09-07'], 'train_time_vec': ['2026-09-08', '2026-09-08'], 'rank_icir': '0.298', 'weight': '0.132'}
