# params 
 {'predict_dates': [{'start': '2026-08-14', 'end': '2026-08-14'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260816_14 633515144648484817 (Recorders: 3/5)

	Recorder: f976ad989bfb4a51b1ba85d9ee927404

		Model: {'id': 'f976ad989bfb4a51b1ba85d9ee927404', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.009, 'ICIR': 0.06, 'Rank IC': 0.02, 'Rank ICIR': 0.109}, 'data_train_vec': ['2021-08-16', '2025-05-15'], 'train_time_vec': ['2026-08-16', '2026-08-16'], 'rank_icir': '0.109', 'weight': '0.057'}

	Recorder: 963c1991161c433f82687fb9807a5863

		Model: {'id': '963c1991161c433f82687fb9807a5863', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.01, 'ICIR': 0.063, 'Rank IC': 0.017, 'Rank ICIR': 0.121}, 'data_train_vec': ['2022-08-16', '2025-08-15'], 'train_time_vec': ['2026-08-16', '2026-08-16'], 'rank_icir': '0.121', 'weight': '0.064'}

	Recorder: 1bb9ec8253b1480eb992d4084ece3f37

		Model: {'id': '1bb9ec8253b1480eb992d4084ece3f37', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.01, 'ICIR': 0.039, 'Rank IC': 0.014, 'Rank ICIR': 0.089}, 'data_train_vec': ['2023-08-16', '2025-11-15'], 'train_time_vec': ['2026-08-16', '2026-08-16'], 'rank_icir': '0.089', 'weight': '0.047'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260816_14 988199170669218452 (Recorders: 2/5)

	Recorder: 1acabdcb33c94d8ca8efed68051e6cd0

		Model: {'id': '1acabdcb33c94d8ca8efed68051e6cd0', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.005, 'ICIR': 0.036, 'Rank IC': 0.017, 'Rank ICIR': 0.118}, 'data_train_vec': ['2021-08-16', '2025-05-15'], 'train_time_vec': ['2026-08-16', '2026-08-16'], 'rank_icir': '0.118', 'weight': '0.062'}

	Recorder: 7c61dee20ff6435ebd3c89d605666cbc

		Model: {'id': '7c61dee20ff6435ebd3c89d605666cbc', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.016, 'ICIR': 0.101, 'Rank IC': 0.023, 'Rank ICIR': 0.183}, 'data_train_vec': ['2023-08-16', '2025-11-15'], 'train_time_vec': ['2026-08-16', '2026-08-16'], 'rank_icir': '0.183', 'weight': '0.096'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260816_13 251884279302864556 (Recorders: 3/5)

	Recorder: 9b40bf5a1eb449f7b229321372c9dc4f

		Model: {'id': '9b40bf5a1eb449f7b229321372c9dc4f', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.018, 'ICIR': 0.093, 'Rank IC': 0.032, 'Rank ICIR': 0.181}, 'data_train_vec': ['2021-08-16', '2025-05-15'], 'train_time_vec': ['2026-08-16', '2026-08-16'], 'rank_icir': '0.181', 'weight': '0.095'}

	Recorder: 2efff2aa7c134970913c0748a6332890

		Model: {'id': '2efff2aa7c134970913c0748a6332890', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.026, 'ICIR': 0.127, 'Rank IC': 0.035, 'Rank ICIR': 0.207}, 'data_train_vec': ['2022-08-16', '2025-08-15'], 'train_time_vec': ['2026-08-16', '2026-08-16'], 'rank_icir': '0.207', 'weight': '0.109'}

	Recorder: 7dfc0831921a4452b6936bc376bf3ec0

		Model: {'id': '7dfc0831921a4452b6936bc376bf3ec0', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.004, 'ICIR': 0.018, 'Rank IC': 0.009, 'Rank ICIR': 0.053}, 'data_train_vec': ['2023-08-16', '2025-11-15'], 'train_time_vec': ['2026-08-16', '2026-08-16'], 'rank_icir': '0.053', 'weight': '0.028'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260816_13 456779211743848999 (Recorders: 3/5)

	Recorder: 5e59df588be54342876da95d326c5c8f

		Model: {'id': '5e59df588be54342876da95d326c5c8f', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.004, 'ICIR': 0.022, 'Rank IC': 0.022, 'Rank ICIR': 0.139}, 'data_train_vec': ['2021-08-16', '2025-05-15'], 'train_time_vec': ['2026-08-16', '2026-08-16'], 'rank_icir': '0.139', 'weight': '0.073'}

	Recorder: c9d8837246614f4b960f4145ea3c0473

		Model: {'id': 'c9d8837246614f4b960f4145ea3c0473', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.028, 'ICIR': 0.147, 'Rank IC': 0.034, 'Rank ICIR': 0.217}, 'data_train_vec': ['2022-08-16', '2025-08-15'], 'train_time_vec': ['2026-08-16', '2026-08-16'], 'rank_icir': '0.217', 'weight': '0.114'}

	Recorder: dd1e59857be04ca3946c3ee091eb976b

		Model: {'id': 'dd1e59857be04ca3946c3ee091eb976b', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.05, 'ICIR': 0.154, 'Rank IC': 0.026, 'Rank ICIR': 0.113}, 'data_train_vec': ['2025-08-16', '2026-05-15'], 'train_time_vec': ['2026-08-16', '2026-08-16'], 'rank_icir': '0.113', 'weight': '0.060'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260816_12 949064489810687503 (Recorders: 3/5)

	Recorder: 13407a7dab024004bd2417df622e1984

		Model: {'id': '13407a7dab024004bd2417df622e1984', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.008, 'ICIR': 0.043, 'Rank IC': 0.031, 'Rank ICIR': 0.182}, 'data_train_vec': ['2021-08-16', '2025-05-15'], 'train_time_vec': ['2026-08-16', '2026-08-16'], 'rank_icir': '0.182', 'weight': '0.096'}

	Recorder: 4c7dfb9cbac147a8b43b0300abacdc54

		Model: {'id': '4c7dfb9cbac147a8b43b0300abacdc54', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.003, 'ICIR': 0.013, 'Rank IC': 0.023, 'Rank ICIR': 0.134}, 'data_train_vec': ['2022-08-16', '2025-08-15'], 'train_time_vec': ['2026-08-16', '2026-08-16'], 'rank_icir': '0.134', 'weight': '0.071'}

	Recorder: 9779713c978a4353a085ae23005f051d

		Model: {'id': '9779713c978a4353a085ae23005f051d', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.031, 'ICIR': 0.084, 'Rank IC': 0.012, 'Rank ICIR': 0.053}, 'data_train_vec': ['2025-08-16', '2026-05-15'], 'train_time_vec': ['2026-08-16', '2026-08-16'], 'rank_icir': '0.053', 'weight': '0.028'}
