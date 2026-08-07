# params 
 {'predict_dates': [{'start': '2026-08-07', 'end': '2026-08-07'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260807_16 500206259638649848 (Recorders: 1/5)

	Recorder: 59452fc5c0894084a4621fb15978abad

		Model: {'id': '59452fc5c0894084a4621fb15978abad', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.005, 'ICIR': 0.022, 'Rank IC': 0.03, 'Rank ICIR': 0.2}, 'data_train_vec': ['2023-08-07', '2025-11-06'], 'train_time_vec': ['2026-08-07', '2026-08-07'], 'rank_icir': '0.200', 'weight': '0.121'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260807_16 949193207735538303 (Recorders: 3/5)

	Recorder: 054a4403c2b04af9b00a271830d4aa15

		Model: {'id': '054a4403c2b04af9b00a271830d4aa15', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.007, 'ICIR': 0.048, 'Rank IC': 0.021, 'Rank ICIR': 0.137}, 'data_train_vec': ['2021-08-07', '2025-05-06'], 'train_time_vec': ['2026-08-07', '2026-08-07'], 'rank_icir': '0.137', 'weight': '0.083'}

	Recorder: 2a04c75e27ad4ea49c09c99ea7050db3

		Model: {'id': '2a04c75e27ad4ea49c09c99ea7050db3', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.006, 'ICIR': 0.051, 'Rank IC': 0.009, 'Rank ICIR': 0.066}, 'data_train_vec': ['2022-08-07', '2025-08-06'], 'train_time_vec': ['2026-08-07', '2026-08-07'], 'rank_icir': '0.066', 'weight': '0.040'}

	Recorder: 26d09af0026140a9adb88de8883bf37e

		Model: {'id': '26d09af0026140a9adb88de8883bf37e', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.03, 'ICIR': 0.16, 'Rank IC': 0.033, 'Rank ICIR': 0.244}, 'data_train_vec': ['2023-08-07', '2025-11-06'], 'train_time_vec': ['2026-08-07', '2026-08-07'], 'rank_icir': '0.244', 'weight': '0.148'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260807_13 710263614858975712 (Recorders: 3/5)

	Recorder: c8dcd3c5d4b241d78ba649807aa2f7d6

		Model: {'id': 'c8dcd3c5d4b241d78ba649807aa2f7d6', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.019, 'ICIR': 0.098, 'Rank IC': 0.037, 'Rank ICIR': 0.211}, 'data_train_vec': ['2021-08-07', '2025-05-06'], 'train_time_vec': ['2026-08-07', '2026-08-07'], 'rank_icir': '0.211', 'weight': '0.128'}

	Recorder: 6420deccc67c4269864ea9882ab6fa7d

		Model: {'id': '6420deccc67c4269864ea9882ab6fa7d', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.01, 'ICIR': 0.052, 'Rank IC': 0.023, 'Rank ICIR': 0.135}, 'data_train_vec': ['2022-08-07', '2025-08-06'], 'train_time_vec': ['2026-08-07', '2026-08-07'], 'rank_icir': '0.135', 'weight': '0.082'}

	Recorder: 1c8cb267c204405db36a315fc02fd729

		Model: {'id': '1c8cb267c204405db36a315fc02fd729', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.002, 'ICIR': 0.006, 'Rank IC': 0.014, 'Rank ICIR': 0.078}, 'data_train_vec': ['2023-08-07', '2025-11-06'], 'train_time_vec': ['2026-08-07', '2026-08-07'], 'rank_icir': '0.078', 'weight': '0.047'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260807_13 661664984247940114 (Recorders: 2/5)

	Recorder: 0c5bfd790a8942a7921f87e8992efb2f

		Model: {'id': '0c5bfd790a8942a7921f87e8992efb2f', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.009, 'ICIR': 0.044, 'Rank IC': 0.025, 'Rank ICIR': 0.158}, 'data_train_vec': ['2021-08-07', '2025-05-06'], 'train_time_vec': ['2026-08-07', '2026-08-07'], 'rank_icir': '0.158', 'weight': '0.096'}

	Recorder: 737772285ec54d6b8dd3b6ed594183a2

		Model: {'id': '737772285ec54d6b8dd3b6ed594183a2', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.009, 'ICIR': 0.044, 'Rank IC': 0.019, 'Rank ICIR': 0.12}, 'data_train_vec': ['2022-08-07', '2025-08-06'], 'train_time_vec': ['2026-08-07', '2026-08-07'], 'rank_icir': '0.120', 'weight': '0.073'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260807_13 143669305332789695 (Recorders: 2/5)

	Recorder: 67d888746f334aed93f14043a5114092

		Model: {'id': '67d888746f334aed93f14043a5114092', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.015, 'ICIR': 0.07, 'Rank IC': 0.039, 'Rank ICIR': 0.214}, 'data_train_vec': ['2021-08-07', '2025-05-06'], 'train_time_vec': ['2026-08-07', '2026-08-07'], 'rank_icir': '0.214', 'weight': '0.130'}

	Recorder: 11e446601c11469ca766a58e3f4def5a

		Model: {'id': '11e446601c11469ca766a58e3f4def5a', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.003, 'ICIR': 0.011, 'Rank IC': 0.014, 'Rank ICIR': 0.086}, 'data_train_vec': ['2023-08-07', '2025-11-06'], 'train_time_vec': ['2026-08-07', '2026-08-07'], 'rank_icir': '0.086', 'weight': '0.052'}
