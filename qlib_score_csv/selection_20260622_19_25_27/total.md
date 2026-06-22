# params 
 {'predict_dates': [{'start': '2026-06-22', 'end': '2026-06-22'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260622_18 960323843998253369 (Recorders: 3/5)

	Recorder: cce51be86e094951b708c6c373d4cd37

		Model: {'id': 'cce51be86e094951b708c6c373d4cd37', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.006, 'ICIR': 0.051, 'Rank IC': 0.02, 'Rank ICIR': 0.138}, 'data_train_vec': ['2022-06-22', '2025-06-21'], 'train_time_vec': ['2026-06-22', '2026-06-22'], 'rank_icir': '0.138', 'weight': '0.035'}

	Recorder: ae72ff92b4bb4116a6e14d0ab1ed4170

		Model: {'id': 'ae72ff92b4bb4116a6e14d0ab1ed4170', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.002, 'ICIR': 0.014, 'Rank IC': 0.029, 'Rank ICIR': 0.192}, 'data_train_vec': ['2023-06-22', '2025-09-21'], 'train_time_vec': ['2026-06-22', '2026-06-22'], 'rank_icir': '0.192', 'weight': '0.049'}

	Recorder: b921655fa94240a3baddf1629d943b55

		Model: {'id': 'b921655fa94240a3baddf1629d943b55', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.044, 'ICIR': 0.409, 'Rank IC': 0.035, 'Rank ICIR': 0.404}, 'data_train_vec': ['2024-06-22', '2025-12-21'], 'train_time_vec': ['2026-06-22', '2026-06-22'], 'rank_icir': '0.404', 'weight': '0.104'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260622_18 569899798994076337 (Recorders: 4/5)

	Recorder: 282e5752c7344cf6a751660c5bdb57e3

		Model: {'id': '282e5752c7344cf6a751660c5bdb57e3', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.004, 'ICIR': 0.029, 'Rank IC': 0.033, 'Rank ICIR': 0.221}, 'data_train_vec': ['2022-06-22', '2025-06-21'], 'train_time_vec': ['2026-06-22', '2026-06-22'], 'rank_icir': '0.221', 'weight': '0.057'}

	Recorder: 47be64aa6a994abe9d6d1536a27bb42e

		Model: {'id': '47be64aa6a994abe9d6d1536a27bb42e', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.036, 'ICIR': 0.312, 'Rank IC': 0.04, 'Rank ICIR': 0.316}, 'data_train_vec': ['2023-06-22', '2025-09-21'], 'train_time_vec': ['2026-06-22', '2026-06-22'], 'rank_icir': '0.316', 'weight': '0.081'}

	Recorder: 13d96ccbeba04523a2de2f611313f359

		Model: {'id': '13d96ccbeba04523a2de2f611313f359', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.032, 'ICIR': 0.244, 'Rank IC': 0.03, 'Rank ICIR': 0.231}, 'data_train_vec': ['2024-06-22', '2025-12-21'], 'train_time_vec': ['2026-06-22', '2026-06-22'], 'rank_icir': '0.231', 'weight': '0.059'}

	Recorder: c7c7994f3c2b4cb1b1807ff748394ba7

		Model: {'id': 'c7c7994f3c2b4cb1b1807ff748394ba7', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.043, 'ICIR': 0.162, 'Rank IC': 0.007, 'Rank ICIR': 0.028}, 'data_train_vec': ['2025-06-22', '2026-03-21'], 'train_time_vec': ['2026-06-22', '2026-06-22'], 'rank_icir': '0.028', 'weight': '0.007'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260622_17 699390880748678723 (Recorders: 4/5)

	Recorder: 39ff4c7156d84f67a7f4c7d386579197

		Model: {'id': '39ff4c7156d84f67a7f4c7d386579197', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.019, 'ICIR': 0.117, 'Rank IC': 0.053, 'Rank ICIR': 0.318}, 'data_train_vec': ['2021-06-22', '2025-03-21'], 'train_time_vec': ['2026-06-22', '2026-06-22'], 'rank_icir': '0.318', 'weight': '0.082'}

	Recorder: c32225cdc0384a088319cb9212851d4b

		Model: {'id': 'c32225cdc0384a088319cb9212851d4b', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.016, 'ICIR': 0.1, 'Rank IC': 0.049, 'Rank ICIR': 0.296}, 'data_train_vec': ['2022-06-22', '2025-06-21'], 'train_time_vec': ['2026-06-22', '2026-06-22'], 'rank_icir': '0.296', 'weight': '0.076'}

	Recorder: 44b7b52387b244caa242b6232d210543

		Model: {'id': '44b7b52387b244caa242b6232d210543', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.026, 'ICIR': 0.195, 'Rank IC': 0.038, 'Rank ICIR': 0.265}, 'data_train_vec': ['2023-06-22', '2025-09-21'], 'train_time_vec': ['2026-06-22', '2026-06-22'], 'rank_icir': '0.265', 'weight': '0.068'}

	Recorder: 7cd280fdc6da4959a78caeb81ead232b

		Model: {'id': '7cd280fdc6da4959a78caeb81ead232b', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.02, 'ICIR': 0.143, 'Rank IC': 0.021, 'Rank ICIR': 0.164}, 'data_train_vec': ['2024-06-22', '2025-12-21'], 'train_time_vec': ['2026-06-22', '2026-06-22'], 'rank_icir': '0.164', 'weight': '0.042'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260622_17 904108353468944282 (Recorders: 3/5)

	Recorder: a12d540d53a44680a68add4e25927de0

		Model: {'id': 'a12d540d53a44680a68add4e25927de0', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.001, 'ICIR': 0.008, 'Rank IC': 0.035, 'Rank ICIR': 0.267}, 'data_train_vec': ['2021-06-22', '2025-03-21'], 'train_time_vec': ['2026-06-22', '2026-06-22'], 'rank_icir': '0.267', 'weight': '0.069'}

	Recorder: d231dd8839364e3fa0f756e7e93127ab

		Model: {'id': 'd231dd8839364e3fa0f756e7e93127ab', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.004, 'ICIR': 0.034, 'Rank IC': 0.022, 'Rank ICIR': 0.176}, 'data_train_vec': ['2023-06-22', '2025-09-21'], 'train_time_vec': ['2026-06-22', '2026-06-22'], 'rank_icir': '0.176', 'weight': '0.045'}

	Recorder: 514bd505815e46809d8053fad36c32b6

		Model: {'id': '514bd505815e46809d8053fad36c32b6', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.023, 'ICIR': 0.137, 'Rank IC': 0.019, 'Rank ICIR': 0.114}, 'data_train_vec': ['2024-06-22', '2025-12-21'], 'train_time_vec': ['2026-06-22', '2026-06-22'], 'rank_icir': '0.114', 'weight': '0.029'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260622_17 811303358210762867 (Recorders: 3/5)

	Recorder: e56a506bd5cf4d599554a6ffb5a60dcd

		Model: {'id': 'e56a506bd5cf4d599554a6ffb5a60dcd', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.007, 'ICIR': 0.053, 'Rank IC': 0.048, 'Rank ICIR': 0.279}, 'data_train_vec': ['2022-06-22', '2025-06-21'], 'train_time_vec': ['2026-06-22', '2026-06-22'], 'rank_icir': '0.279', 'weight': '0.072'}

	Recorder: c2821881787b42ada2686613fd3ec3b7

		Model: {'id': 'c2821881787b42ada2686613fd3ec3b7', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.008, 'ICIR': 0.066, 'Rank IC': 0.025, 'Rank ICIR': 0.168}, 'data_train_vec': ['2023-06-22', '2025-09-21'], 'train_time_vec': ['2026-06-22', '2026-06-22'], 'rank_icir': '0.168', 'weight': '0.043'}

	Recorder: 8241e156ed7c451bb02e5c75cd37352a

		Model: {'id': '8241e156ed7c451bb02e5c75cd37352a', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.012, 'ICIR': 0.103, 'Rank IC': 0.028, 'Rank ICIR': 0.32}, 'data_train_vec': ['2024-06-22', '2025-12-21'], 'train_time_vec': ['2026-06-22', '2026-06-22'], 'rank_icir': '0.320', 'weight': '0.082'}
