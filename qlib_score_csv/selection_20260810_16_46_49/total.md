# params 
 {'predict_dates': [{'start': '2026-08-10', 'end': '2026-08-10'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260810_16 447398827977257941 (Recorders: 1/5)

	Recorder: 33bfee9a8972426d861620f2a2ea24e1

		Model: {'id': '33bfee9a8972426d861620f2a2ea24e1', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.007, 'ICIR': 0.032, 'Rank IC': 0.017, 'Rank ICIR': 0.086}, 'data_train_vec': ['2023-08-10', '2025-11-09'], 'train_time_vec': ['2026-08-10', '2026-08-10'], 'rank_icir': '0.086', 'weight': '0.070'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260810_16 846635521907374040 (Recorders: 3/5)

	Recorder: c99423c9944f4acf9567ad39b098909a

		Model: {'id': 'c99423c9944f4acf9567ad39b098909a', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.005, 'ICIR': 0.027, 'Rank IC': 0.015, 'Rank ICIR': 0.093}, 'data_train_vec': ['2021-08-10', '2025-05-09'], 'train_time_vec': ['2026-08-10', '2026-08-10'], 'rank_icir': '0.093', 'weight': '0.076'}

	Recorder: 9fd1d0c64deb4ff980fe64716a9e6b95

		Model: {'id': '9fd1d0c64deb4ff980fe64716a9e6b95', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.004, 'ICIR': 0.029, 'Rank IC': 0.014, 'Rank ICIR': 0.092}, 'data_train_vec': ['2022-08-10', '2025-08-09'], 'train_time_vec': ['2026-08-10', '2026-08-10'], 'rank_icir': '0.092', 'weight': '0.075'}

	Recorder: 4e037f08bae644428b94d4c3f0de7510

		Model: {'id': '4e037f08bae644428b94d4c3f0de7510', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.022, 'ICIR': 0.115, 'Rank IC': 0.023, 'Rank ICIR': 0.166}, 'data_train_vec': ['2023-08-10', '2025-11-09'], 'train_time_vec': ['2026-08-10', '2026-08-10'], 'rank_icir': '0.166', 'weight': '0.135'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260810_13 769014425592972791 (Recorders: 2/5)

	Recorder: 5317bf6b492b4e6e98e01ff8162a785a

		Model: {'id': '5317bf6b492b4e6e98e01ff8162a785a', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.015, 'ICIR': 0.079, 'Rank IC': 0.033, 'Rank ICIR': 0.189}, 'data_train_vec': ['2021-08-10', '2025-05-09'], 'train_time_vec': ['2026-08-10', '2026-08-10'], 'rank_icir': '0.189', 'weight': '0.154'}

	Recorder: c0abc3e70e534b979267351888feae87

		Model: {'id': 'c0abc3e70e534b979267351888feae87', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.01, 'ICIR': 0.048, 'Rank IC': 0.022, 'Rank ICIR': 0.129}, 'data_train_vec': ['2022-08-10', '2025-08-09'], 'train_time_vec': ['2026-08-10', '2026-08-10'], 'rank_icir': '0.129', 'weight': '0.105'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260810_13 120461889674128828 (Recorders: 2/5)

	Recorder: e2f94e1af1ae4025b5945f822cd24352

		Model: {'id': 'e2f94e1af1ae4025b5945f822cd24352', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.007, 'ICIR': 0.036, 'Rank IC': 0.023, 'Rank ICIR': 0.143}, 'data_train_vec': ['2021-08-10', '2025-05-09'], 'train_time_vec': ['2026-08-10', '2026-08-10'], 'rank_icir': '0.143', 'weight': '0.116'}

	Recorder: 74c630dc201849368d4d50e07550cd22

		Model: {'id': '74c630dc201849368d4d50e07550cd22', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.013, 'ICIR': 0.064, 'Rank IC': 0.02, 'Rank ICIR': 0.126}, 'data_train_vec': ['2022-08-10', '2025-08-09'], 'train_time_vec': ['2026-08-10', '2026-08-10'], 'rank_icir': '0.126', 'weight': '0.103'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260810_13 569744093615711788 (Recorders: 2/5)

	Recorder: 540c2541370c400791bd6483e4cd798f

		Model: {'id': '540c2541370c400791bd6483e4cd798f', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.002, 'ICIR': 0.011, 'Rank IC': 0.028, 'Rank ICIR': 0.157}, 'data_train_vec': ['2021-08-10', '2025-05-09'], 'train_time_vec': ['2026-08-10', '2026-08-10'], 'rank_icir': '0.157', 'weight': '0.128'}

	Recorder: 7c147982d08141d38e23258d1319e444

		Model: {'id': '7c147982d08141d38e23258d1319e444', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.026, 'ICIR': 0.073, 'Rank IC': 0.011, 'Rank ICIR': 0.048}, 'data_train_vec': ['2025-08-10', '2026-05-09'], 'train_time_vec': ['2026-08-10', '2026-08-10'], 'rank_icir': '0.048', 'weight': '0.039'}
