# params 
 {'predict_dates': [{'start': '2026-09-23', 'end': '2026-09-23'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260923_18 300986362354160389 (Recorders: 3/5)

	Recorder: 09b1e98af9fa47bd995f38dc809001c4

		Model: {'id': '09b1e98af9fa47bd995f38dc809001c4', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.027, 'ICIR': 0.195, 'Rank IC': 0.033, 'Rank ICIR': 0.22}, 'data_train_vec': ['2021-09-23', '2025-06-22'], 'train_time_vec': ['2026-09-23', '2026-09-23'], 'rank_icir': '0.220', 'weight': '0.118'}

	Recorder: dda19e568eaf44dc9a8c95bea54d4cfc

		Model: {'id': 'dda19e568eaf44dc9a8c95bea54d4cfc', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.024, 'ICIR': 0.097, 'Rank IC': 0.03, 'Rank ICIR': 0.173}, 'data_train_vec': ['2022-09-23', '2025-09-22'], 'train_time_vec': ['2026-09-23', '2026-09-23'], 'rank_icir': '0.173', 'weight': '0.093'}

	Recorder: 733b4d82a91841d0b18dc91a05c12375

		Model: {'id': '733b4d82a91841d0b18dc91a05c12375', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.011, 'ICIR': 0.04, 'Rank IC': 0.012, 'Rank ICIR': 0.061}, 'data_train_vec': ['2023-09-23', '2025-12-22'], 'train_time_vec': ['2026-09-23', '2026-09-23'], 'rank_icir': '0.061', 'weight': '0.033'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260923_18 483091080562889525 (Recorders: 2/5)

	Recorder: 1f0e89a133f94d149f726fee0cb9393f

		Model: {'id': '1f0e89a133f94d149f726fee0cb9393f', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.008, 'ICIR': 0.051, 'Rank IC': 0.018, 'Rank ICIR': 0.105}, 'data_train_vec': ['2021-09-23', '2025-06-22'], 'train_time_vec': ['2026-09-23', '2026-09-23'], 'rank_icir': '0.105', 'weight': '0.056'}

	Recorder: 575f61cc8b524763adb6bbc336e123fe

		Model: {'id': '575f61cc8b524763adb6bbc336e123fe', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.025, 'ICIR': 0.149, 'Rank IC': 0.033, 'Rank ICIR': 0.211}, 'data_train_vec': ['2022-09-23', '2025-09-22'], 'train_time_vec': ['2026-09-23', '2026-09-23'], 'rank_icir': '0.211', 'weight': '0.113'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260923_16 175682218810747882 (Recorders: 3/5)

	Recorder: 78eefdf761c44cff8c956d4c73c66b1e

		Model: {'id': '78eefdf761c44cff8c956d4c73c66b1e', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.027, 'ICIR': 0.14, 'Rank IC': 0.036, 'Rank ICIR': 0.214}, 'data_train_vec': ['2021-09-23', '2025-06-22'], 'train_time_vec': ['2026-09-23', '2026-09-23'], 'rank_icir': '0.214', 'weight': '0.114'}

	Recorder: 673fc29d22824dfe878aa962d8726c10

		Model: {'id': '673fc29d22824dfe878aa962d8726c10', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.023, 'ICIR': 0.104, 'Rank IC': 0.029, 'Rank ICIR': 0.166}, 'data_train_vec': ['2022-09-23', '2025-09-22'], 'train_time_vec': ['2026-09-23', '2026-09-23'], 'rank_icir': '0.166', 'weight': '0.089'}

	Recorder: 0b9a5383a9224ca2b487d62c59126643

		Model: {'id': '0b9a5383a9224ca2b487d62c59126643', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.031, 'ICIR': 0.128, 'Rank IC': 0.006, 'Rank ICIR': 0.033}, 'data_train_vec': ['2024-09-23', '2026-03-22'], 'train_time_vec': ['2026-09-23', '2026-09-23'], 'rank_icir': '0.033', 'weight': '0.018'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260923_16 557243268016535256 (Recorders: 3/5)

	Recorder: 3069477a4dbb40f18aa7791c2fda9be9

		Model: {'id': '3069477a4dbb40f18aa7791c2fda9be9', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.028, 'ICIR': 0.137, 'Rank IC': 0.033, 'Rank ICIR': 0.193}, 'data_train_vec': ['2021-09-23', '2025-06-22'], 'train_time_vec': ['2026-09-23', '2026-09-23'], 'rank_icir': '0.193', 'weight': '0.103'}

	Recorder: 609ac1e8f118477eb992c4f65f1eee3e

		Model: {'id': '609ac1e8f118477eb992c4f65f1eee3e', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.026, 'ICIR': 0.124, 'Rank IC': 0.016, 'Rank ICIR': 0.092}, 'data_train_vec': ['2022-09-23', '2025-09-22'], 'train_time_vec': ['2026-09-23', '2026-09-23'], 'rank_icir': '0.092', 'weight': '0.049'}

	Recorder: c452784c7fa74100a9b8c7a8e4740730

		Model: {'id': 'c452784c7fa74100a9b8c7a8e4740730', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.061, 'ICIR': 0.259, 'Rank IC': 0.032, 'Rank ICIR': 0.162}, 'data_train_vec': ['2024-09-23', '2026-03-22'], 'train_time_vec': ['2026-09-23', '2026-09-23'], 'rank_icir': '0.162', 'weight': '0.087'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260923_16 931701733692720156 (Recorders: 2/5)

	Recorder: 6c82ea538d9644d586f956d799e7fa86

		Model: {'id': '6c82ea538d9644d586f956d799e7fa86', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.012, 'ICIR': 0.056, 'Rank IC': 0.035, 'Rank ICIR': 0.211}, 'data_train_vec': ['2021-09-23', '2025-06-22'], 'train_time_vec': ['2026-09-23', '2026-09-23'], 'rank_icir': '0.211', 'weight': '0.113'}

	Recorder: 520f866e4680444e87b82ccaaf0a4fc7

		Model: {'id': '520f866e4680444e87b82ccaaf0a4fc7', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.04, 'ICIR': 0.164, 'Rank IC': 0.004, 'Rank ICIR': 0.028}, 'data_train_vec': ['2024-09-23', '2026-03-22'], 'train_time_vec': ['2026-09-23', '2026-09-23'], 'rank_icir': '0.028', 'weight': '0.015'}
