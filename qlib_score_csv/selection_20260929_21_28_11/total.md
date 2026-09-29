# params 
 {'predict_dates': [{'start': '2026-09-29', 'end': '2026-09-29'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260929_20 856234244434041532 (Recorders: 4/5)

	Recorder: e7983aa6b035494b951b1ecc5a081b35

		Model: {'id': 'e7983aa6b035494b951b1ecc5a081b35', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.016, 'ICIR': 0.099, 'Rank IC': 0.027, 'Rank ICIR': 0.154}, 'data_train_vec': ['2021-09-29', '2025-06-28'], 'train_time_vec': ['2026-09-29', '2026-09-29'], 'rank_icir': '0.154', 'weight': '0.057'}

	Recorder: c2bb01782a79490db8db9518c127317f

		Model: {'id': 'c2bb01782a79490db8db9518c127317f', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.027, 'ICIR': 0.103, 'Rank IC': 0.03, 'Rank ICIR': 0.149}, 'data_train_vec': ['2022-09-29', '2025-09-28'], 'train_time_vec': ['2026-09-29', '2026-09-29'], 'rank_icir': '0.149', 'weight': '0.055'}

	Recorder: 6554e8fb82204c4583b91670088cd7cc

		Model: {'id': '6554e8fb82204c4583b91670088cd7cc', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.006, 'ICIR': 0.021, 'Rank IC': 0.012, 'Rank ICIR': 0.06}, 'data_train_vec': ['2023-09-29', '2025-12-28'], 'train_time_vec': ['2026-09-29', '2026-09-29'], 'rank_icir': '0.060', 'weight': '0.022'}

	Recorder: a374f46286a741a6b5b71388e96e1faa

		Model: {'id': 'a374f46286a741a6b5b71388e96e1faa', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.046, 'ICIR': 0.292, 'Rank IC': 0.016, 'Rank ICIR': 0.127}, 'data_train_vec': ['2024-09-29', '2026-03-28'], 'train_time_vec': ['2026-09-29', '2026-09-29'], 'rank_icir': '0.127', 'weight': '0.047'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260929_20 192512109104678489 (Recorders: 4/5)

	Recorder: 77e81c0405034bd7b76f8e02d2903ca4

		Model: {'id': '77e81c0405034bd7b76f8e02d2903ca4', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.026, 'ICIR': 0.172, 'Rank IC': 0.03, 'Rank ICIR': 0.221}, 'data_train_vec': ['2021-09-29', '2025-06-28'], 'train_time_vec': ['2026-09-29', '2026-09-29'], 'rank_icir': '0.221', 'weight': '0.081'}

	Recorder: f87d29b28d3a49a5a969712379424616

		Model: {'id': 'f87d29b28d3a49a5a969712379424616', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.03, 'ICIR': 0.178, 'Rank IC': 0.033, 'Rank ICIR': 0.201}, 'data_train_vec': ['2022-09-29', '2025-09-28'], 'train_time_vec': ['2026-09-29', '2026-09-29'], 'rank_icir': '0.201', 'weight': '0.074'}

	Recorder: 3a625219e7904ec0ad92a28917d0340a

		Model: {'id': '3a625219e7904ec0ad92a28917d0340a', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.004, 'ICIR': 0.018, 'Rank IC': 0.009, 'Rank ICIR': 0.045}, 'data_train_vec': ['2023-09-29', '2025-12-28'], 'train_time_vec': ['2026-09-29', '2026-09-29'], 'rank_icir': '0.045', 'weight': '0.017'}

	Recorder: 02e0016167b540db8d19ddf11b8d1902

		Model: {'id': '02e0016167b540db8d19ddf11b8d1902', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.007, 'ICIR': 0.055, 'Rank IC': 0.008, 'Rank ICIR': 0.054}, 'data_train_vec': ['2024-09-29', '2026-03-28'], 'train_time_vec': ['2026-09-29', '2026-09-29'], 'rank_icir': '0.054', 'weight': '0.020'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260929_18 733114468644128604 (Recorders: 4/5)

	Recorder: 73840a4466c04be99322feb02964fb5b

		Model: {'id': '73840a4466c04be99322feb02964fb5b', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.034, 'ICIR': 0.172, 'Rank IC': 0.043, 'Rank ICIR': 0.251}, 'data_train_vec': ['2021-09-29', '2025-06-28'], 'train_time_vec': ['2026-09-29', '2026-09-29'], 'rank_icir': '0.251', 'weight': '0.092'}

	Recorder: a46d2998689542e1b3bec68dc8c95ea0

		Model: {'id': 'a46d2998689542e1b3bec68dc8c95ea0', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.025, 'ICIR': 0.104, 'Rank IC': 0.029, 'Rank ICIR': 0.155}, 'data_train_vec': ['2022-09-29', '2025-09-28'], 'train_time_vec': ['2026-09-29', '2026-09-29'], 'rank_icir': '0.155', 'weight': '0.057'}

	Recorder: c74cba1ccce24e298808f1ba970eb7c2

		Model: {'id': 'c74cba1ccce24e298808f1ba970eb7c2', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.004, 'ICIR': 0.015, 'Rank IC': 0.009, 'Rank ICIR': 0.04}, 'data_train_vec': ['2023-09-29', '2025-12-28'], 'train_time_vec': ['2026-09-29', '2026-09-29'], 'rank_icir': '0.040', 'weight': '0.015'}

	Recorder: 0ab1127399594ac6b8f6c63706294964

		Model: {'id': '0ab1127399594ac6b8f6c63706294964', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.036, 'ICIR': 0.182, 'Rank IC': 0.007, 'Rank ICIR': 0.043}, 'data_train_vec': ['2024-09-29', '2026-03-28'], 'train_time_vec': ['2026-09-29', '2026-09-29'], 'rank_icir': '0.043', 'weight': '0.016'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260929_18 480311155478370094 (Recorders: 5/5)

	Recorder: c34e94613e914afaba2dad805b5421f7

		Model: {'id': 'c34e94613e914afaba2dad805b5421f7', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.034, 'ICIR': 0.17, 'Rank IC': 0.038, 'Rank ICIR': 0.22}, 'data_train_vec': ['2021-09-29', '2025-06-28'], 'train_time_vec': ['2026-09-29', '2026-09-29'], 'rank_icir': '0.220', 'weight': '0.081'}

	Recorder: adbca05195244fca99cf34113e18e0de

		Model: {'id': 'adbca05195244fca99cf34113e18e0de', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.028, 'ICIR': 0.127, 'Rank IC': 0.019, 'Rank ICIR': 0.1}, 'data_train_vec': ['2022-09-29', '2025-09-28'], 'train_time_vec': ['2026-09-29', '2026-09-29'], 'rank_icir': '0.100', 'weight': '0.037'}

	Recorder: 9dc0f081245a4c03829a9283da578e10

		Model: {'id': '9dc0f081245a4c03829a9283da578e10', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.007, 'ICIR': 0.027, 'Rank IC': 0.001, 'Rank ICIR': 0.006}, 'data_train_vec': ['2023-09-29', '2025-12-28'], 'train_time_vec': ['2026-09-29', '2026-09-29'], 'rank_icir': '0.006', 'weight': '0.002'}

	Recorder: 1bdd0d0722e6405ca92321321da3fa05

		Model: {'id': '1bdd0d0722e6405ca92321321da3fa05', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.073, 'ICIR': 0.34, 'Rank IC': 0.045, 'Rank ICIR': 0.254}, 'data_train_vec': ['2024-09-29', '2026-03-28'], 'train_time_vec': ['2026-09-29', '2026-09-29'], 'rank_icir': '0.254', 'weight': '0.093'}

	Recorder: 6def2a83d9a4430f86832d5fd6791d4a

		Model: {'id': '6def2a83d9a4430f86832d5fd6791d4a', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.011, 'ICIR': 0.07, 'Rank IC': 0.005, 'Rank ICIR': 0.032}, 'data_train_vec': ['2025-09-29', '2026-06-28'], 'train_time_vec': ['2026-09-29', '2026-09-29'], 'rank_icir': '0.032', 'weight': '0.012'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260929_18 509970630386935592 (Recorders: 3/5)

	Recorder: 129f9e6ec2e946bdbf0bdec15b150571

		Model: {'id': '129f9e6ec2e946bdbf0bdec15b150571', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.005, 'ICIR': 0.021, 'Rank IC': 0.041, 'Rank ICIR': 0.236}, 'data_train_vec': ['2021-09-29', '2025-06-28'], 'train_time_vec': ['2026-09-29', '2026-09-29'], 'rank_icir': '0.236', 'weight': '0.087'}

	Recorder: 6f9099d80be14e99b9e8cdc9915eb9ea

		Model: {'id': '6f9099d80be14e99b9e8cdc9915eb9ea', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.009, 'ICIR': 0.04, 'Rank IC': 0.024, 'Rank ICIR': 0.14}, 'data_train_vec': ['2022-09-29', '2025-09-28'], 'train_time_vec': ['2026-09-29', '2026-09-29'], 'rank_icir': '0.140', 'weight': '0.051'}

	Recorder: bb169b5c1ecc46a8809f87f044e06358

		Model: {'id': 'bb169b5c1ecc46a8809f87f044e06358', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.06, 'ICIR': 0.291, 'Rank IC': 0.033, 'Rank ICIR': 0.233}, 'data_train_vec': ['2024-09-29', '2026-03-28'], 'train_time_vec': ['2026-09-29', '2026-09-29'], 'rank_icir': '0.233', 'weight': '0.086'}
