# params 
 {'predict_dates': [{'start': '2026-09-16', 'end': '2026-09-16'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260916_19 318299826464518614 (Recorders: 3/5)

	Recorder: 3f427545e6684713a4428ac4c626952f

		Model: {'id': '3f427545e6684713a4428ac4c626952f', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.011, 'ICIR': 0.076, 'Rank IC': 0.018, 'Rank ICIR': 0.111}, 'data_train_vec': ['2021-09-16', '2025-06-15'], 'train_time_vec': ['2026-09-16', '2026-09-16'], 'rank_icir': '0.111', 'weight': '0.044'}

	Recorder: d8b94fe757c34f38a369ea49eba6dc4d

		Model: {'id': 'd8b94fe757c34f38a369ea49eba6dc4d', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.024, 'ICIR': 0.112, 'Rank IC': 0.026, 'Rank ICIR': 0.154}, 'data_train_vec': ['2022-09-16', '2025-09-15'], 'train_time_vec': ['2026-09-16', '2026-09-16'], 'rank_icir': '0.154', 'weight': '0.061'}

	Recorder: 2c95adddde9d480c81d369e2c04c3412

		Model: {'id': '2c95adddde9d480c81d369e2c04c3412', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.003, 'ICIR': 0.013, 'Rank IC': 0.007, 'Rank ICIR': 0.045}, 'data_train_vec': ['2023-09-16', '2025-12-15'], 'train_time_vec': ['2026-09-16', '2026-09-16'], 'rank_icir': '0.045', 'weight': '0.018'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260916_19 992638256668637372 (Recorders: 4/5)

	Recorder: 7046a6f05042410483b354279b398f9d

		Model: {'id': '7046a6f05042410483b354279b398f9d', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.018, 'ICIR': 0.114, 'Rank IC': 0.027, 'Rank ICIR': 0.181}, 'data_train_vec': ['2021-09-16', '2025-06-15'], 'train_time_vec': ['2026-09-16', '2026-09-16'], 'rank_icir': '0.181', 'weight': '0.072'}

	Recorder: 2d9d6ba5cefe4257af7ab83743d857f2

		Model: {'id': '2d9d6ba5cefe4257af7ab83743d857f2', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.025, 'ICIR': 0.155, 'Rank IC': 0.037, 'Rank ICIR': 0.247}, 'data_train_vec': ['2022-09-16', '2025-09-15'], 'train_time_vec': ['2026-09-16', '2026-09-16'], 'rank_icir': '0.247', 'weight': '0.098'}

	Recorder: 1a8a455c7b7f49f582a9e491253e83ae

		Model: {'id': '1a8a455c7b7f49f582a9e491253e83ae', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.004, 'ICIR': 0.02, 'Rank IC': 0.002, 'Rank ICIR': 0.014}, 'data_train_vec': ['2023-09-16', '2025-12-15'], 'train_time_vec': ['2026-09-16', '2026-09-16'], 'rank_icir': '0.014', 'weight': '0.006'}

	Recorder: 6508f99ea3604f8e842c2a0ce4ee50c4

		Model: {'id': '6508f99ea3604f8e842c2a0ce4ee50c4', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.031, 'ICIR': 0.116, 'Rank IC': 0.014, 'Rank ICIR': 0.067}, 'data_train_vec': ['2024-09-16', '2026-03-15'], 'train_time_vec': ['2026-09-16', '2026-09-16'], 'rank_icir': '0.067', 'weight': '0.027'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260916_17 927303055797530458 (Recorders: 4/5)

	Recorder: f6bb961dd2024d2bb9bd86422e4fd2f5

		Model: {'id': 'f6bb961dd2024d2bb9bd86422e4fd2f5', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.032, 'ICIR': 0.166, 'Rank IC': 0.042, 'Rank ICIR': 0.255}, 'data_train_vec': ['2021-09-16', '2025-06-15'], 'train_time_vec': ['2026-09-16', '2026-09-16'], 'rank_icir': '0.255', 'weight': '0.101'}

	Recorder: 3b5ab4d73f874fc286cf37596b2c0174

		Model: {'id': '3b5ab4d73f874fc286cf37596b2c0174', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.032, 'ICIR': 0.142, 'Rank IC': 0.04, 'Rank ICIR': 0.236}, 'data_train_vec': ['2022-09-16', '2025-09-15'], 'train_time_vec': ['2026-09-16', '2026-09-16'], 'rank_icir': '0.236', 'weight': '0.093'}

	Recorder: 066416175d374364b9a2248fe50a2603

		Model: {'id': '066416175d374364b9a2248fe50a2603', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.012, 'ICIR': 0.047, 'Rank IC': 0.013, 'Rank ICIR': 0.067}, 'data_train_vec': ['2023-09-16', '2025-12-15'], 'train_time_vec': ['2026-09-16', '2026-09-16'], 'rank_icir': '0.067', 'weight': '0.027'}

	Recorder: aa21c49c97684574bdc944a006555629

		Model: {'id': 'aa21c49c97684574bdc944a006555629', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.036, 'ICIR': 0.124, 'Rank IC': 0.021, 'Rank ICIR': 0.095}, 'data_train_vec': ['2024-09-16', '2026-03-15'], 'train_time_vec': ['2026-09-16', '2026-09-16'], 'rank_icir': '0.095', 'weight': '0.038'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260916_16 808636652082265753 (Recorders: 4/5)

	Recorder: ea929dbd1ec84e0fac3846f91a04d5d5

		Model: {'id': 'ea929dbd1ec84e0fac3846f91a04d5d5', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.032, 'ICIR': 0.159, 'Rank IC': 0.038, 'Rank ICIR': 0.229}, 'data_train_vec': ['2021-09-16', '2025-06-15'], 'train_time_vec': ['2026-09-16', '2026-09-16'], 'rank_icir': '0.229', 'weight': '0.091'}

	Recorder: 4dc9a1ab8b274513be86734f9e05aae3

		Model: {'id': '4dc9a1ab8b274513be86734f9e05aae3', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.029, 'ICIR': 0.145, 'Rank IC': 0.023, 'Rank ICIR': 0.138}, 'data_train_vec': ['2022-09-16', '2025-09-15'], 'train_time_vec': ['2026-09-16', '2026-09-16'], 'rank_icir': '0.138', 'weight': '0.055'}

	Recorder: 2ee6501d0180457493aa7d6eef35c68a

		Model: {'id': '2ee6501d0180457493aa7d6eef35c68a', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.006, 'ICIR': 0.024, 'Rank IC': 0.002, 'Rank ICIR': 0.008}, 'data_train_vec': ['2023-09-16', '2025-12-15'], 'train_time_vec': ['2026-09-16', '2026-09-16'], 'rank_icir': '0.008', 'weight': '0.003'}

	Recorder: 2124459ab62f41bc916377b300cd6dc1

		Model: {'id': '2124459ab62f41bc916377b300cd6dc1', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.064, 'ICIR': 0.226, 'Rank IC': 0.046, 'Rank ICIR': 0.195}, 'data_train_vec': ['2024-09-16', '2026-03-15'], 'train_time_vec': ['2026-09-16', '2026-09-16'], 'rank_icir': '0.195', 'weight': '0.077'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260916_16 528043967430050537 (Recorders: 3/5)

	Recorder: baa970ee9eb24a6a82bcc761cb2d36fe

		Model: {'id': 'baa970ee9eb24a6a82bcc761cb2d36fe', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.003, 'ICIR': 0.012, 'Rank IC': 0.035, 'Rank ICIR': 0.2}, 'data_train_vec': ['2021-09-16', '2025-06-15'], 'train_time_vec': ['2026-09-16', '2026-09-16'], 'rank_icir': '0.200', 'weight': '0.079'}

	Recorder: 2172838c83e24e91962216b1252a3396

		Model: {'id': '2172838c83e24e91962216b1252a3396', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.004, 'ICIR': 0.019, 'Rank IC': 0.038, 'Rank ICIR': 0.254}, 'data_train_vec': ['2022-09-16', '2025-09-15'], 'train_time_vec': ['2026-09-16', '2026-09-16'], 'rank_icir': '0.254', 'weight': '0.101'}

	Recorder: d53886d7c0d345dfb4d75b3a9ae18b1f

		Model: {'id': 'd53886d7c0d345dfb4d75b3a9ae18b1f', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.023, 'ICIR': 0.087, 'Rank IC': 0.005, 'Rank ICIR': 0.029}, 'data_train_vec': ['2024-09-16', '2026-03-15'], 'train_time_vec': ['2026-09-16', '2026-09-16'], 'rank_icir': '0.029', 'weight': '0.011'}
