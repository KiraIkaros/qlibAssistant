# params 
 {'predict_dates': [{'start': '2026-09-30', 'end': '2026-09-30'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20261006_21 411275748510443328 (Recorders: 5/5)

	Recorder: 032932312d964a15988982c3c54039fe

		Model: {'id': '032932312d964a15988982c3c54039fe', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.028, 'ICIR': 0.163, 'Rank IC': 0.037, 'Rank ICIR': 0.215}, 'data_train_vec': ['2021-10-06', '2025-07-05'], 'train_time_vec': ['2026-10-06', '2026-10-06'], 'rank_icir': '0.215', 'weight': '0.072'}

	Recorder: d19a1ed90d1b4646bf93195330ecd138

		Model: {'id': 'd19a1ed90d1b4646bf93195330ecd138', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.014, 'ICIR': 0.063, 'Rank IC': 0.025, 'Rank ICIR': 0.146}, 'data_train_vec': ['2022-10-06', '2025-10-05'], 'train_time_vec': ['2026-10-06', '2026-10-06'], 'rank_icir': '0.146', 'weight': '0.049'}

	Recorder: 84cce9c4d22543acadfbc3812424d5d2

		Model: {'id': '84cce9c4d22543acadfbc3812424d5d2', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.011, 'ICIR': 0.035, 'Rank IC': 0.015, 'Rank ICIR': 0.077}, 'data_train_vec': ['2023-10-06', '2026-01-05'], 'train_time_vec': ['2026-10-06', '2026-10-06'], 'rank_icir': '0.077', 'weight': '0.026'}

	Recorder: e61e5c52125543029670295f4759ebb3

		Model: {'id': 'e61e5c52125543029670295f4759ebb3', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.015, 'ICIR': 0.105, 'Rank IC': 0.003, 'Rank ICIR': 0.019}, 'data_train_vec': ['2024-10-06', '2026-04-05'], 'train_time_vec': ['2026-10-06', '2026-10-06'], 'rank_icir': '0.019', 'weight': '0.006'}

	Recorder: 20b642dc2c0e41b481e4f0e05209b487

		Model: {'id': '20b642dc2c0e41b481e4f0e05209b487', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.023, 'ICIR': 0.217, 'Rank IC': 0.016, 'Rank ICIR': 0.146}, 'data_train_vec': ['2025-10-06', '2026-07-05'], 'train_time_vec': ['2026-10-06', '2026-10-06'], 'rank_icir': '0.146', 'weight': '0.049'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20261006_20 163673894553920774 (Recorders: 5/5)

	Recorder: 0473a48bd8c44d5ea200da565afca557

		Model: {'id': '0473a48bd8c44d5ea200da565afca557', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.029, 'ICIR': 0.195, 'Rank IC': 0.037, 'Rank ICIR': 0.237}, 'data_train_vec': ['2021-10-06', '2025-07-05'], 'train_time_vec': ['2026-10-06', '2026-10-06'], 'rank_icir': '0.237', 'weight': '0.079'}

	Recorder: f72f613fb6a147bcaac58ed02fa2ef9d

		Model: {'id': 'f72f613fb6a147bcaac58ed02fa2ef9d', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.028, 'ICIR': 0.137, 'Rank IC': 0.028, 'Rank ICIR': 0.148}, 'data_train_vec': ['2022-10-06', '2025-10-05'], 'train_time_vec': ['2026-10-06', '2026-10-06'], 'rank_icir': '0.148', 'weight': '0.049'}

	Recorder: 4535550dd73c430fa1df1d1b51504d3e

		Model: {'id': '4535550dd73c430fa1df1d1b51504d3e', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.013, 'ICIR': 0.057, 'Rank IC': 0.02, 'Rank ICIR': 0.101}, 'data_train_vec': ['2023-10-06', '2026-01-05'], 'train_time_vec': ['2026-10-06', '2026-10-06'], 'rank_icir': '0.101', 'weight': '0.034'}

	Recorder: d6a6a86aeee64c19947d9ee8ad8660c4

		Model: {'id': 'd6a6a86aeee64c19947d9ee8ad8660c4', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.013, 'ICIR': 0.084, 'Rank IC': 0.001, 'Rank ICIR': 0.009}, 'data_train_vec': ['2024-10-06', '2026-04-05'], 'train_time_vec': ['2026-10-06', '2026-10-06'], 'rank_icir': '0.009', 'weight': '0.003'}

	Recorder: 9e9d8934b399465a873eaa17997cc094

		Model: {'id': '9e9d8934b399465a873eaa17997cc094', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.01, 'ICIR': 0.103, 'Rank IC': 0.019, 'Rank ICIR': 0.255}, 'data_train_vec': ['2025-10-06', '2026-07-05'], 'train_time_vec': ['2026-10-06', '2026-10-06'], 'rank_icir': '0.255', 'weight': '0.085'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20261006_18 144974527520007253 (Recorders: 3/5)

	Recorder: a21a994dcb6d459aaa2a40c281a7a80e

		Model: {'id': 'a21a994dcb6d459aaa2a40c281a7a80e', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.033, 'ICIR': 0.171, 'Rank IC': 0.042, 'Rank ICIR': 0.252}, 'data_train_vec': ['2021-10-06', '2025-07-05'], 'train_time_vec': ['2026-10-06', '2026-10-06'], 'rank_icir': '0.252', 'weight': '0.084'}

	Recorder: e3209160ffd647e7a1a8b87876375876

		Model: {'id': 'e3209160ffd647e7a1a8b87876375876', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.023, 'ICIR': 0.101, 'Rank IC': 0.023, 'Rank ICIR': 0.123}, 'data_train_vec': ['2022-10-06', '2025-10-05'], 'train_time_vec': ['2026-10-06', '2026-10-06'], 'rank_icir': '0.123', 'weight': '0.041'}

	Recorder: 574ee156eeff43aeb810b29c5855f162

		Model: {'id': '574ee156eeff43aeb810b29c5855f162', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.008, 'ICIR': 0.027, 'Rank IC': 0.007, 'Rank ICIR': 0.031}, 'data_train_vec': ['2023-10-06', '2026-01-05'], 'train_time_vec': ['2026-10-06', '2026-10-06'], 'rank_icir': '0.031', 'weight': '0.010'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20261006_18 354304842296284789 (Recorders: 5/5)

	Recorder: 0edb66ffc9cb4afc888e5bce6f397389

		Model: {'id': '0edb66ffc9cb4afc888e5bce6f397389', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.038, 'ICIR': 0.191, 'Rank IC': 0.041, 'Rank ICIR': 0.235}, 'data_train_vec': ['2021-10-06', '2025-07-05'], 'train_time_vec': ['2026-10-06', '2026-10-06'], 'rank_icir': '0.235', 'weight': '0.079'}

	Recorder: 0ab5127258d04da391d93a7a7131db28

		Model: {'id': '0ab5127258d04da391d93a7a7131db28', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.031, 'ICIR': 0.135, 'Rank IC': 0.018, 'Rank ICIR': 0.093}, 'data_train_vec': ['2022-10-06', '2025-10-05'], 'train_time_vec': ['2026-10-06', '2026-10-06'], 'rank_icir': '0.093', 'weight': '0.031'}

	Recorder: 2d8801a9aa7940ee82d1e4f3713e0f60

		Model: {'id': '2d8801a9aa7940ee82d1e4f3713e0f60', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.006, 'ICIR': 0.021, 'Rank IC': 0.002, 'Rank ICIR': 0.012}, 'data_train_vec': ['2023-10-06', '2026-01-05'], 'train_time_vec': ['2026-10-06', '2026-10-06'], 'rank_icir': '0.012', 'weight': '0.004'}

	Recorder: a544a122d3144ae1b5fbab51222becc2

		Model: {'id': 'a544a122d3144ae1b5fbab51222becc2', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.025, 'ICIR': 0.127, 'Rank IC': 0.011, 'Rank ICIR': 0.06}, 'data_train_vec': ['2024-10-06', '2026-04-05'], 'train_time_vec': ['2026-10-06', '2026-10-06'], 'rank_icir': '0.060', 'weight': '0.020'}

	Recorder: 73387a56db2d440cb5357f1be7f41527

		Model: {'id': '73387a56db2d440cb5357f1be7f41527', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.038, 'ICIR': 0.283, 'Rank IC': 0.044, 'Rank ICIR': 0.368}, 'data_train_vec': ['2025-10-06', '2026-07-05'], 'train_time_vec': ['2026-10-06', '2026-10-06'], 'rank_icir': '0.368', 'weight': '0.123'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20261006_18 892707184220814556 (Recorders: 4/5)

	Recorder: b25edaf2442547f891ba3af134acdc25

		Model: {'id': 'b25edaf2442547f891ba3af134acdc25', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.005, 'ICIR': 0.022, 'Rank IC': 0.036, 'Rank ICIR': 0.208}, 'data_train_vec': ['2021-10-06', '2025-07-05'], 'train_time_vec': ['2026-10-06', '2026-10-06'], 'rank_icir': '0.208', 'weight': '0.070'}

	Recorder: 0e4f4a8505be4772a286a7bae28cc62c

		Model: {'id': '0e4f4a8505be4772a286a7bae28cc62c', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.008, 'ICIR': 0.033, 'Rank IC': 0.019, 'Rank ICIR': 0.109}, 'data_train_vec': ['2022-10-06', '2025-10-05'], 'train_time_vec': ['2026-10-06', '2026-10-06'], 'rank_icir': '0.109', 'weight': '0.036'}

	Recorder: 97a335450b7a4250aa9cc8ba2a16d817

		Model: {'id': '97a335450b7a4250aa9cc8ba2a16d817', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.009, 'ICIR': 0.041, 'Rank IC': 0.001, 'Rank ICIR': 0.008}, 'data_train_vec': ['2024-10-06', '2026-04-05'], 'train_time_vec': ['2026-10-06', '2026-10-06'], 'rank_icir': '0.008', 'weight': '0.003'}

	Recorder: c5cef8127dbf4851ae40ecc3d5fe6ace

		Model: {'id': 'c5cef8127dbf4851ae40ecc3d5fe6ace', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.01, 'ICIR': 0.097, 'Rank IC': 0.011, 'Rank ICIR': 0.138}, 'data_train_vec': ['2025-10-06', '2026-07-05'], 'train_time_vec': ['2026-10-06', '2026-10-06'], 'rank_icir': '0.138', 'weight': '0.046'}
