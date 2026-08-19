# params 
 {'predict_dates': [{'start': '2026-08-19', 'end': '2026-08-19'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260819_15 225812213755479018 (Recorders: 1/5)

	Recorder: 6d0e954148d148b694d60bb0d415b580

		Model: {'id': '6d0e954148d148b694d60bb0d415b580', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.007, 'ICIR': 0.03, 'Rank IC': 0.025, 'Rank ICIR': 0.175}, 'data_train_vec': ['2023-08-19', '2025-11-18'], 'train_time_vec': ['2026-08-19', '2026-08-19'], 'rank_icir': '0.175', 'weight': '0.103'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260819_15 292824319586880307 (Recorders: 3/5)

	Recorder: fa75b0966c424d97a483b86325d1987c

		Model: {'id': 'fa75b0966c424d97a483b86325d1987c', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.005, 'ICIR': 0.032, 'Rank IC': 0.016, 'Rank ICIR': 0.106}, 'data_train_vec': ['2021-08-19', '2025-05-18'], 'train_time_vec': ['2026-08-19', '2026-08-19'], 'rank_icir': '0.106', 'weight': '0.063'}

	Recorder: 24bdfad5dc9b4ca8878d1c3668df5aa0

		Model: {'id': '24bdfad5dc9b4ca8878d1c3668df5aa0', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.003, 'ICIR': 0.023, 'Rank IC': 0.01, 'Rank ICIR': 0.073}, 'data_train_vec': ['2022-08-19', '2025-08-18'], 'train_time_vec': ['2026-08-19', '2026-08-19'], 'rank_icir': '0.073', 'weight': '0.043'}

	Recorder: 6165063c8d9d44bc8917679dea32c90c

		Model: {'id': '6165063c8d9d44bc8917679dea32c90c', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.016, 'ICIR': 0.097, 'Rank IC': 0.018, 'Rank ICIR': 0.156}, 'data_train_vec': ['2023-08-19', '2025-11-18'], 'train_time_vec': ['2026-08-19', '2026-08-19'], 'rank_icir': '0.156', 'weight': '0.092'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260819_13 820226015437528924 (Recorders: 4/5)

	Recorder: eac25d83987e4ef9ae1e2e6e88f17d49

		Model: {'id': 'eac25d83987e4ef9ae1e2e6e88f17d49', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.017, 'ICIR': 0.09, 'Rank IC': 0.026, 'Rank ICIR': 0.159}, 'data_train_vec': ['2021-08-19', '2025-05-18'], 'train_time_vec': ['2026-08-19', '2026-08-19'], 'rank_icir': '0.159', 'weight': '0.094'}

	Recorder: a6331a0c13114740bf6597d51b4de929

		Model: {'id': 'a6331a0c13114740bf6597d51b4de929', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.027, 'ICIR': 0.126, 'Rank IC': 0.033, 'Rank ICIR': 0.194}, 'data_train_vec': ['2022-08-19', '2025-08-18'], 'train_time_vec': ['2026-08-19', '2026-08-19'], 'rank_icir': '0.194', 'weight': '0.115'}

	Recorder: 346349104c2d478cab35e2e4dbc2f8d5

		Model: {'id': '346349104c2d478cab35e2e4dbc2f8d5', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.004, 'ICIR': 0.014, 'Rank IC': 0.009, 'Rank ICIR': 0.049}, 'data_train_vec': ['2023-08-19', '2025-11-18'], 'train_time_vec': ['2026-08-19', '2026-08-19'], 'rank_icir': '0.049', 'weight': '0.029'}

	Recorder: 60ff773f1e614544983c1cfb9d6edfa6

		Model: {'id': '60ff773f1e614544983c1cfb9d6edfa6', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.012, 'ICIR': 0.046, 'Rank IC': 0.007, 'Rank ICIR': 0.033}, 'data_train_vec': ['2025-08-19', '2026-05-18'], 'train_time_vec': ['2026-08-19', '2026-08-19'], 'rank_icir': '0.033', 'weight': '0.020'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260819_13 777196763294655551 (Recorders: 3/5)

	Recorder: fed4c1eba47a4882a030c45a1b0203cb

		Model: {'id': 'fed4c1eba47a4882a030c45a1b0203cb', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.01, 'ICIR': 0.052, 'Rank IC': 0.024, 'Rank ICIR': 0.151}, 'data_train_vec': ['2021-08-19', '2025-05-18'], 'train_time_vec': ['2026-08-19', '2026-08-19'], 'rank_icir': '0.151', 'weight': '0.089'}

	Recorder: 956fbdad1ca84262ad9f4ce746e8361a

		Model: {'id': '956fbdad1ca84262ad9f4ce746e8361a', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.029, 'ICIR': 0.148, 'Rank IC': 0.033, 'Rank ICIR': 0.207}, 'data_train_vec': ['2022-08-19', '2025-08-18'], 'train_time_vec': ['2026-08-19', '2026-08-19'], 'rank_icir': '0.207', 'weight': '0.122'}

	Recorder: 2554f89670fc4d89909c5c219ef1e4d5

		Model: {'id': '2554f89670fc4d89909c5c219ef1e4d5', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.033, 'ICIR': 0.117, 'Rank IC': 0.008, 'Rank ICIR': 0.041}, 'data_train_vec': ['2025-08-19', '2026-05-18'], 'train_time_vec': ['2026-08-19', '2026-08-19'], 'rank_icir': '0.041', 'weight': '0.024'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260819_13 554531945941786933 (Recorders: 3/5)

	Recorder: 63e34d098520442eb5f8aeee144eb7c7

		Model: {'id': '63e34d098520442eb5f8aeee144eb7c7', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.009, 'ICIR': 0.042, 'Rank IC': 0.02, 'Rank ICIR': 0.115}, 'data_train_vec': ['2021-08-19', '2025-05-18'], 'train_time_vec': ['2026-08-19', '2026-08-19'], 'rank_icir': '0.115', 'weight': '0.068'}

	Recorder: f8ab3f3e9d7349a99e93951e62cf3018

		Model: {'id': 'f8ab3f3e9d7349a99e93951e62cf3018', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.008, 'ICIR': 0.029, 'Rank IC': 0.014, 'Rank ICIR': 0.087}, 'data_train_vec': ['2023-08-19', '2025-11-18'], 'train_time_vec': ['2026-08-19', '2026-08-19'], 'rank_icir': '0.087', 'weight': '0.051'}

	Recorder: a80ee352cca24545aec0ce98ee05ae2c

		Model: {'id': 'a80ee352cca24545aec0ce98ee05ae2c', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.045, 'ICIR': 0.131, 'Rank IC': 0.031, 'Rank ICIR': 0.145}, 'data_train_vec': ['2025-08-19', '2026-05-18'], 'train_time_vec': ['2026-08-19', '2026-08-19'], 'rank_icir': '0.145', 'weight': '0.086'}
