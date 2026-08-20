# params 
 {'predict_dates': [{'start': '2026-08-20', 'end': '2026-08-20'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260820_15 979729446942914513 (Recorders: 3/5)

	Recorder: 6aad9634524540e4aa72d8d28bdbc858

		Model: {'id': '6aad9634524540e4aa72d8d28bdbc858', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.001, 'ICIR': 0.006, 'Rank IC': 0.011, 'Rank ICIR': 0.055}, 'data_train_vec': ['2021-08-20', '2025-05-19'], 'train_time_vec': ['2026-08-20', '2026-08-20'], 'rank_icir': '0.055', 'weight': '0.040'}

	Recorder: 64659ff220964e7d857e74a3c5531227

		Model: {'id': '64659ff220964e7d857e74a3c5531227', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.004, 'ICIR': 0.021, 'Rank IC': 0.024, 'Rank ICIR': 0.148}, 'data_train_vec': ['2022-08-20', '2025-08-19'], 'train_time_vec': ['2026-08-20', '2026-08-20'], 'rank_icir': '0.148', 'weight': '0.108'}

	Recorder: bad3b1e100d64e8aa679ca22c803cda3

		Model: {'id': 'bad3b1e100d64e8aa679ca22c803cda3', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.011, 'ICIR': 0.043, 'Rank IC': 0.016, 'Rank ICIR': 0.108}, 'data_train_vec': ['2023-08-20', '2025-11-19'], 'train_time_vec': ['2026-08-20', '2026-08-20'], 'rank_icir': '0.108', 'weight': '0.079'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260820_14 899542436491110598 (Recorders: 2/5)

	Recorder: 6949c630a2d64a5c837be97996103ae5

		Model: {'id': '6949c630a2d64a5c837be97996103ae5', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.006, 'ICIR': 0.041, 'Rank IC': 0.013, 'Rank ICIR': 0.091}, 'data_train_vec': ['2021-08-20', '2025-05-19'], 'train_time_vec': ['2026-08-20', '2026-08-20'], 'rank_icir': '0.091', 'weight': '0.066'}

	Recorder: bc6f2b8c826c4177a67affe65abd933f

		Model: {'id': 'bc6f2b8c826c4177a67affe65abd933f', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.013, 'ICIR': 0.112, 'Rank IC': 0.015, 'Rank ICIR': 0.147}, 'data_train_vec': ['2023-08-20', '2025-11-19'], 'train_time_vec': ['2026-08-20', '2026-08-20'], 'rank_icir': '0.147', 'weight': '0.107'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260820_13 924049541776936699 (Recorders: 2/5)

	Recorder: 428e966ab78641fb90f7527ee89fd385

		Model: {'id': '428e966ab78641fb90f7527ee89fd385', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.016, 'ICIR': 0.083, 'Rank IC': 0.03, 'Rank ICIR': 0.179}, 'data_train_vec': ['2021-08-20', '2025-05-19'], 'train_time_vec': ['2026-08-20', '2026-08-20'], 'rank_icir': '0.179', 'weight': '0.130'}

	Recorder: e67f897c48aa4bfeae5deec4f7db3f62

		Model: {'id': 'e67f897c48aa4bfeae5deec4f7db3f62', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.019, 'ICIR': 0.085, 'Rank IC': 0.03, 'Rank ICIR': 0.171}, 'data_train_vec': ['2022-08-20', '2025-08-19'], 'train_time_vec': ['2026-08-20', '2026-08-20'], 'rank_icir': '0.171', 'weight': '0.125'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260820_13 235440613422512318 (Recorders: 3/5)

	Recorder: 5b6df74aa70549f39409f1c363abc845

		Model: {'id': '5b6df74aa70549f39409f1c363abc845', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.014, 'ICIR': 0.069, 'Rank IC': 0.027, 'Rank ICIR': 0.167}, 'data_train_vec': ['2021-08-20', '2025-05-19'], 'train_time_vec': ['2026-08-20', '2026-08-20'], 'rank_icir': '0.167', 'weight': '0.122'}

	Recorder: 01ee47a916f94fa6aa14278e1c517c7f

		Model: {'id': '01ee47a916f94fa6aa14278e1c517c7f', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.031, 'ICIR': 0.162, 'Rank IC': 0.036, 'Rank ICIR': 0.228}, 'data_train_vec': ['2022-08-20', '2025-08-19'], 'train_time_vec': ['2026-08-20', '2026-08-20'], 'rank_icir': '0.228', 'weight': '0.166'}

	Recorder: 35a0cbc33afe4fb6a30f6d27f9554f37

		Model: {'id': '35a0cbc33afe4fb6a30f6d27f9554f37', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.042, 'ICIR': 0.156, 'Rank IC': 0.014, 'Rank ICIR': 0.079}, 'data_train_vec': ['2025-08-20', '2026-05-19'], 'train_time_vec': ['2026-08-20', '2026-08-20'], 'rank_icir': '0.079', 'weight': '0.058'}
