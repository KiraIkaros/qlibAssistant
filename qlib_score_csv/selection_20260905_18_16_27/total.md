# params 
 {'predict_dates': [{'start': '2026-09-04', 'end': '2026-09-04'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260905_17 382178670461522930 (Recorders: 2/5)

	Recorder: 5abb8fdee8e54d26967e46858d529893

		Model: {'id': '5abb8fdee8e54d26967e46858d529893', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.032, 'ICIR': 0.169, 'Rank IC': 0.043, 'Rank ICIR': 0.293}, 'data_train_vec': ['2022-09-05', '2025-09-04'], 'train_time_vec': ['2026-09-05', '2026-09-05'], 'rank_icir': '0.293', 'weight': '0.124'}

	Recorder: 4b0aacb8c7c04a51a1ade1fdebdc6b28

		Model: {'id': '4b0aacb8c7c04a51a1ade1fdebdc6b28', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.026, 'ICIR': 0.093, 'Rank IC': 0.013, 'Rank ICIR': 0.073}, 'data_train_vec': ['2023-09-05', '2025-12-04'], 'train_time_vec': ['2026-09-05', '2026-09-05'], 'rank_icir': '0.073', 'weight': '0.031'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260905_17 639820558421402195 (Recorders: 3/5)

	Recorder: 5e4e0a19f8de428eb3f53445555a87ba

		Model: {'id': '5e4e0a19f8de428eb3f53445555a87ba', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.009, 'ICIR': 0.06, 'Rank IC': 0.017, 'Rank ICIR': 0.118}, 'data_train_vec': ['2021-09-05', '2025-06-04'], 'train_time_vec': ['2026-09-05', '2026-09-05'], 'rank_icir': '0.118', 'weight': '0.050'}

	Recorder: 2811685dcb39404cbf5ae5ea6fb6d673

		Model: {'id': '2811685dcb39404cbf5ae5ea6fb6d673', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.027, 'ICIR': 0.163, 'Rank IC': 0.041, 'Rank ICIR': 0.294}, 'data_train_vec': ['2022-09-05', '2025-09-04'], 'train_time_vec': ['2026-09-05', '2026-09-05'], 'rank_icir': '0.294', 'weight': '0.124'}

	Recorder: 7a586acecd4345ce872bb34825d006f1

		Model: {'id': '7a586acecd4345ce872bb34825d006f1', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.017, 'ICIR': 0.112, 'Rank IC': 0.012, 'Rank ICIR': 0.101}, 'data_train_vec': ['2023-09-05', '2025-12-04'], 'train_time_vec': ['2026-09-05', '2026-09-05'], 'rank_icir': '0.101', 'weight': '0.043'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260905_15 906874538491557547 (Recorders: 3/5)

	Recorder: 2233258eb2fc4b43a3e9d0983c57f4f5

		Model: {'id': '2233258eb2fc4b43a3e9d0983c57f4f5', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.015, 'ICIR': 0.075, 'Rank IC': 0.03, 'Rank ICIR': 0.177}, 'data_train_vec': ['2021-09-05', '2025-06-04'], 'train_time_vec': ['2026-09-05', '2026-09-05'], 'rank_icir': '0.177', 'weight': '0.075'}

	Recorder: ba05f070a986403d83e71d812969f8b1

		Model: {'id': 'ba05f070a986403d83e71d812969f8b1', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.033, 'ICIR': 0.153, 'Rank IC': 0.045, 'Rank ICIR': 0.272}, 'data_train_vec': ['2022-09-05', '2025-09-04'], 'train_time_vec': ['2026-09-05', '2026-09-05'], 'rank_icir': '0.272', 'weight': '0.115'}

	Recorder: 4bb8bd0e428e4abd998ddf3696a66ff3

		Model: {'id': '4bb8bd0e428e4abd998ddf3696a66ff3', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.004, 'ICIR': 0.016, 'Rank IC': 0.009, 'Rank ICIR': 0.045}, 'data_train_vec': ['2023-09-05', '2025-12-04'], 'train_time_vec': ['2026-09-05', '2026-09-05'], 'rank_icir': '0.045', 'weight': '0.019'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260905_15 806044027572956322 (Recorders: 3/5)

	Recorder: 1b6747e9ef3f48b99f16e7f573eab080

		Model: {'id': '1b6747e9ef3f48b99f16e7f573eab080', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.017, 'ICIR': 0.081, 'Rank IC': 0.026, 'Rank ICIR': 0.156}, 'data_train_vec': ['2021-09-05', '2025-06-04'], 'train_time_vec': ['2026-09-05', '2026-09-05'], 'rank_icir': '0.156', 'weight': '0.066'}

	Recorder: 86ab19d5eb49475b8d43594adb13392b

		Model: {'id': '86ab19d5eb49475b8d43594adb13392b', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.039, 'ICIR': 0.211, 'Rank IC': 0.038, 'Rank ICIR': 0.241}, 'data_train_vec': ['2022-09-05', '2025-09-04'], 'train_time_vec': ['2026-09-05', '2026-09-05'], 'rank_icir': '0.241', 'weight': '0.102'}

	Recorder: ac31e704687242a4b30208b0700cf5d9

		Model: {'id': 'ac31e704687242a4b30208b0700cf5d9', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.039, 'ICIR': 0.18, 'Rank IC': 0.031, 'Rank ICIR': 0.15}, 'data_train_vec': ['2025-09-05', '2026-06-04'], 'train_time_vec': ['2026-09-05', '2026-09-05'], 'rank_icir': '0.150', 'weight': '0.063'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260905_15 455626629657522726 (Recorders: 2/5)

	Recorder: 07c5ddc919b8484ead6409fcf396f3f5

		Model: {'id': '07c5ddc919b8484ead6409fcf396f3f5', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.007, 'ICIR': 0.03, 'Rank IC': 0.032, 'Rank ICIR': 0.186}, 'data_train_vec': ['2021-09-05', '2025-06-04'], 'train_time_vec': ['2026-09-05', '2026-09-05'], 'rank_icir': '0.186', 'weight': '0.078'}

	Recorder: 2b6779c3c69d436d8c8acab47c96eeb4

		Model: {'id': '2b6779c3c69d436d8c8acab47c96eeb4', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.007, 'ICIR': 0.029, 'Rank IC': 0.04, 'Rank ICIR': 0.266}, 'data_train_vec': ['2022-09-05', '2025-09-04'], 'train_time_vec': ['2026-09-05', '2026-09-05'], 'rank_icir': '0.266', 'weight': '0.112'}
