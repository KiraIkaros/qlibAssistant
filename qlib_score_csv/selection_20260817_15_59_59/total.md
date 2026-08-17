# params 
 {'predict_dates': [{'start': '2026-08-17', 'end': '2026-08-17'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260817_15 802745498682592558 (Recorders: 1/5)

	Recorder: 840529cf05a94c6f880cf2fe95eb04ad

		Model: {'id': '840529cf05a94c6f880cf2fe95eb04ad', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.019, 'ICIR': 0.075, 'Rank IC': 0.024, 'Rank ICIR': 0.164}, 'data_train_vec': ['2023-08-17', '2025-11-16'], 'train_time_vec': ['2026-08-17', '2026-08-17'], 'rank_icir': '0.164', 'weight': '0.092'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260817_15 875101383874854007 (Recorders: 2/5)

	Recorder: 18e582c50b7241d3b0e33827c5c8603e

		Model: {'id': '18e582c50b7241d3b0e33827c5c8603e', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.009, 'ICIR': 0.059, 'Rank IC': 0.02, 'Rank ICIR': 0.144}, 'data_train_vec': ['2021-08-17', '2025-05-16'], 'train_time_vec': ['2026-08-17', '2026-08-17'], 'rank_icir': '0.144', 'weight': '0.081'}

	Recorder: 99395fe97a9c4c2b8b0ff08c7f732591

		Model: {'id': '99395fe97a9c4c2b8b0ff08c7f732591', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.021, 'ICIR': 0.123, 'Rank IC': 0.024, 'Rank ICIR': 0.174}, 'data_train_vec': ['2023-08-17', '2025-11-16'], 'train_time_vec': ['2026-08-17', '2026-08-17'], 'rank_icir': '0.174', 'weight': '0.098'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260817_13 506057435660925768 (Recorders: 4/5)

	Recorder: cdce2975b8b94bb68a5c1b7c53622add

		Model: {'id': 'cdce2975b8b94bb68a5c1b7c53622add', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.016, 'ICIR': 0.082, 'Rank IC': 0.029, 'Rank ICIR': 0.171}, 'data_train_vec': ['2021-08-17', '2025-05-16'], 'train_time_vec': ['2026-08-17', '2026-08-17'], 'rank_icir': '0.171', 'weight': '0.096'}

	Recorder: 635d09801d2e4c0cb815745b6bc60646

		Model: {'id': '635d09801d2e4c0cb815745b6bc60646', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.023, 'ICIR': 0.109, 'Rank IC': 0.032, 'Rank ICIR': 0.187}, 'data_train_vec': ['2022-08-17', '2025-08-16'], 'train_time_vec': ['2026-08-17', '2026-08-17'], 'rank_icir': '0.187', 'weight': '0.105'}

	Recorder: 5f569e8106f844aeb1c95223933488ba

		Model: {'id': '5f569e8106f844aeb1c95223933488ba', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.004, 'ICIR': 0.016, 'Rank IC': 0.009, 'Rank ICIR': 0.049}, 'data_train_vec': ['2023-08-17', '2025-11-16'], 'train_time_vec': ['2026-08-17', '2026-08-17'], 'rank_icir': '0.049', 'weight': '0.028'}

	Recorder: 6cfc505a242f46a9ba06c9f2a0561468

		Model: {'id': '6cfc505a242f46a9ba06c9f2a0561468', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.019, 'ICIR': 0.068, 'Rank IC': 0.006, 'Rank ICIR': 0.028}, 'data_train_vec': ['2025-08-17', '2026-05-16'], 'train_time_vec': ['2026-08-17', '2026-08-17'], 'rank_icir': '0.028', 'weight': '0.016'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260817_13 550777830133662686 (Recorders: 3/5)

	Recorder: a1563808b4f24563852aec0f58a5c4ca

		Model: {'id': 'a1563808b4f24563852aec0f58a5c4ca', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.007, 'ICIR': 0.033, 'Rank IC': 0.022, 'Rank ICIR': 0.138}, 'data_train_vec': ['2021-08-17', '2025-05-16'], 'train_time_vec': ['2026-08-17', '2026-08-17'], 'rank_icir': '0.138', 'weight': '0.078'}

	Recorder: 922eead1409741efa3da2a5ce72af3fc

		Model: {'id': '922eead1409741efa3da2a5ce72af3fc', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.028, 'ICIR': 0.147, 'Rank IC': 0.034, 'Rank ICIR': 0.215}, 'data_train_vec': ['2022-08-17', '2025-08-16'], 'train_time_vec': ['2026-08-17', '2026-08-17'], 'rank_icir': '0.215', 'weight': '0.121'}

	Recorder: 8712cef35ceb494e90fc040d0f4e2bdd

		Model: {'id': '8712cef35ceb494e90fc040d0f4e2bdd', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.075, 'ICIR': 0.245, 'Rank IC': 0.039, 'Rank ICIR': 0.171}, 'data_train_vec': ['2025-08-17', '2026-05-16'], 'train_time_vec': ['2026-08-17', '2026-08-17'], 'rank_icir': '0.171', 'weight': '0.096'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260817_13 672960053138586509 (Recorders: 3/5)

	Recorder: fb708ea8390644a2a3751489d0f9828c

		Model: {'id': 'fb708ea8390644a2a3751489d0f9828c', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.005, 'ICIR': 0.025, 'Rank IC': 0.033, 'Rank ICIR': 0.185}, 'data_train_vec': ['2021-08-17', '2025-05-16'], 'train_time_vec': ['2026-08-17', '2026-08-17'], 'rank_icir': '0.185', 'weight': '0.104'}

	Recorder: 4868f6dd4b444268999b8173479bbe1d

		Model: {'id': '4868f6dd4b444268999b8173479bbe1d', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.002, 'ICIR': 0.008, 'Rank IC': 0.005, 'Rank ICIR': 0.029}, 'data_train_vec': ['2023-08-17', '2025-11-16'], 'train_time_vec': ['2026-08-17', '2026-08-17'], 'rank_icir': '0.029', 'weight': '0.016'}

	Recorder: d2793169ed3d4a39b9b266196554cdf2

		Model: {'id': 'd2793169ed3d4a39b9b266196554cdf2', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.059, 'ICIR': 0.166, 'Rank IC': 0.026, 'Rank ICIR': 0.124}, 'data_train_vec': ['2025-08-17', '2026-05-16'], 'train_time_vec': ['2026-08-17', '2026-08-17'], 'rank_icir': '0.124', 'weight': '0.070'}
