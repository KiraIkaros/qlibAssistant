# params 
 {'predict_dates': [{'start': '2026-08-18', 'end': '2026-08-18'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260818_15 508011967808477326 (Recorders: 2/5)

	Recorder: 4b962eb951cb4de68a3dacb03b8e058d

		Model: {'id': '4b962eb951cb4de68a3dacb03b8e058d', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.036, 'ICIR': 0.21, 'Rank IC': 0.031, 'Rank ICIR': 0.219}, 'data_train_vec': ['2022-08-18', '2025-08-17'], 'train_time_vec': ['2026-08-18', '2026-08-18'], 'rank_icir': '0.219', 'weight': '0.132'}

	Recorder: 3766cecc7a7747c3a3adb279deca10ef

		Model: {'id': '3766cecc7a7747c3a3adb279deca10ef', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.018, 'ICIR': 0.069, 'Rank IC': 0.014, 'Rank ICIR': 0.088}, 'data_train_vec': ['2023-08-18', '2025-11-17'], 'train_time_vec': ['2026-08-18', '2026-08-18'], 'rank_icir': '0.088', 'weight': '0.053'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260818_15 798339405756827463 (Recorders: 2/5)

	Recorder: 9b189aba02454f2b8e021165334768b0

		Model: {'id': '9b189aba02454f2b8e021165334768b0', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.003, 'ICIR': 0.018, 'Rank IC': 0.012, 'Rank ICIR': 0.087}, 'data_train_vec': ['2021-08-18', '2025-05-17'], 'train_time_vec': ['2026-08-18', '2026-08-18'], 'rank_icir': '0.087', 'weight': '0.052'}

	Recorder: f2d492c99bdf44ba85464056a50c143f

		Model: {'id': 'f2d492c99bdf44ba85464056a50c143f', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.013, 'ICIR': 0.065, 'Rank IC': 0.019, 'Rank ICIR': 0.124}, 'data_train_vec': ['2023-08-18', '2025-11-17'], 'train_time_vec': ['2026-08-18', '2026-08-18'], 'rank_icir': '0.124', 'weight': '0.075'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260818_13 683559449677840554 (Recorders: 2/5)

	Recorder: 80199ce35b454f7b867a29704d53ec5d

		Model: {'id': '80199ce35b454f7b867a29704d53ec5d', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.019, 'ICIR': 0.097, 'Rank IC': 0.031, 'Rank ICIR': 0.186}, 'data_train_vec': ['2021-08-18', '2025-05-17'], 'train_time_vec': ['2026-08-18', '2026-08-18'], 'rank_icir': '0.186', 'weight': '0.112'}

	Recorder: 91770274370e4e078621b7b5f7bef62b

		Model: {'id': '91770274370e4e078621b7b5f7bef62b', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.026, 'ICIR': 0.118, 'Rank IC': 0.03, 'Rank ICIR': 0.17}, 'data_train_vec': ['2022-08-18', '2025-08-17'], 'train_time_vec': ['2026-08-18', '2026-08-18'], 'rank_icir': '0.170', 'weight': '0.102'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260818_13 888226778611169238 (Recorders: 3/5)

	Recorder: ae338849254a497486e8f7b20705b35e

		Model: {'id': 'ae338849254a497486e8f7b20705b35e', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.009, 'ICIR': 0.043, 'Rank IC': 0.024, 'Rank ICIR': 0.15}, 'data_train_vec': ['2021-08-18', '2025-05-17'], 'train_time_vec': ['2026-08-18', '2026-08-18'], 'rank_icir': '0.150', 'weight': '0.090'}

	Recorder: e4123b3704ca400e94c62d6c832c5075

		Model: {'id': 'e4123b3704ca400e94c62d6c832c5075', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.028, 'ICIR': 0.143, 'Rank IC': 0.032, 'Rank ICIR': 0.202}, 'data_train_vec': ['2022-08-18', '2025-08-17'], 'train_time_vec': ['2026-08-18', '2026-08-18'], 'rank_icir': '0.202', 'weight': '0.121'}

	Recorder: c5528e62834c45259bb470d7efaea673

		Model: {'id': 'c5528e62834c45259bb470d7efaea673', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.034, 'ICIR': 0.123, 'Rank IC': 0.003, 'Rank ICIR': 0.018}, 'data_train_vec': ['2025-08-18', '2026-05-17'], 'train_time_vec': ['2026-08-18', '2026-08-18'], 'rank_icir': '0.018', 'weight': '0.011'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260818_13 232815232263282404 (Recorders: 4/5)

	Recorder: b65e7f47b1a34539a6f24fc2f4bfaadb

		Model: {'id': 'b65e7f47b1a34539a6f24fc2f4bfaadb', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.003, 'ICIR': 0.014, 'Rank IC': 0.027, 'Rank ICIR': 0.15}, 'data_train_vec': ['2021-08-18', '2025-05-17'], 'train_time_vec': ['2026-08-18', '2026-08-18'], 'rank_icir': '0.150', 'weight': '0.090'}

	Recorder: 147f90e919884ac2ad396c3331fa2873

		Model: {'id': '147f90e919884ac2ad396c3331fa2873', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.011, 'ICIR': 0.048, 'Rank IC': 0.028, 'Rank ICIR': 0.169}, 'data_train_vec': ['2022-08-18', '2025-08-17'], 'train_time_vec': ['2026-08-18', '2026-08-18'], 'rank_icir': '0.169', 'weight': '0.102'}

	Recorder: b4b5e8cb19a345b7b4686c0176132f88

		Model: {'id': 'b4b5e8cb19a345b7b4686c0176132f88', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.004, 'ICIR': 0.014, 'Rank IC': 0.003, 'Rank ICIR': 0.021}, 'data_train_vec': ['2023-08-18', '2025-11-17'], 'train_time_vec': ['2026-08-18', '2026-08-18'], 'rank_icir': '0.021', 'weight': '0.013'}

	Recorder: 13180c5d22a9450593498b32fe584e31

		Model: {'id': '13180c5d22a9450593498b32fe584e31', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.039, 'ICIR': 0.118, 'Rank IC': 0.016, 'Rank ICIR': 0.079}, 'data_train_vec': ['2025-08-18', '2026-05-17'], 'train_time_vec': ['2026-08-18', '2026-08-18'], 'rank_icir': '0.079', 'weight': '0.048'}
