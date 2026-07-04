# params 
 {'predict_dates': [{'start': '2026-07-03', 'end': '2026-07-03'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260704_16 927509734486261918 (Recorders: 3/5)

	Recorder: 8638d41f30f94bdf97f552694c87aa06

		Model: {'id': '8638d41f30f94bdf97f552694c87aa06', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.023, 'ICIR': 0.205, 'Rank IC': 0.028, 'Rank ICIR': 0.18}, 'data_train_vec': ['2022-07-04', '2025-07-03'], 'train_time_vec': ['2026-07-04', '2026-07-04'], 'rank_icir': '0.180', 'weight': '0.073'}

	Recorder: 8ca54a596dee4a53b9ec41be263d256f

		Model: {'id': '8ca54a596dee4a53b9ec41be263d256f', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.029, 'ICIR': 0.253, 'Rank IC': 0.033, 'Rank ICIR': 0.262}, 'data_train_vec': ['2023-07-04', '2025-10-03'], 'train_time_vec': ['2026-07-04', '2026-07-04'], 'rank_icir': '0.262', 'weight': '0.106'}

	Recorder: 331de4a7cad94473a20e11babba16f09

		Model: {'id': '331de4a7cad94473a20e11babba16f09', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.037, 'ICIR': 0.351, 'Rank IC': 0.026, 'Rank ICIR': 0.257}, 'data_train_vec': ['2024-07-04', '2026-01-03'], 'train_time_vec': ['2026-07-04', '2026-07-04'], 'rank_icir': '0.257', 'weight': '0.104'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260704_16 181050451469464557 (Recorders: 3/5)

	Recorder: 4f6c0d5d85c14c00a6ba9ea46c8193e4

		Model: {'id': '4f6c0d5d85c14c00a6ba9ea46c8193e4', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.02, 'ICIR': 0.195, 'Rank IC': 0.02, 'Rank ICIR': 0.17}, 'data_train_vec': ['2023-07-04', '2025-10-03'], 'train_time_vec': ['2026-07-04', '2026-07-04'], 'rank_icir': '0.170', 'weight': '0.069'}

	Recorder: c4b99f6d3a214337b327a1e275fd44c9

		Model: {'id': 'c4b99f6d3a214337b327a1e275fd44c9', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.034, 'ICIR': 0.262, 'Rank IC': 0.029, 'Rank ICIR': 0.238}, 'data_train_vec': ['2024-07-04', '2026-01-03'], 'train_time_vec': ['2026-07-04', '2026-07-04'], 'rank_icir': '0.238', 'weight': '0.096'}

	Recorder: c8e13ac106d6476fa76fcaab9ca4372f

		Model: {'id': 'c8e13ac106d6476fa76fcaab9ca4372f', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.036, 'ICIR': 0.146, 'Rank IC': 0.016, 'Rank ICIR': 0.067}, 'data_train_vec': ['2025-07-04', '2026-04-03'], 'train_time_vec': ['2026-07-04', '2026-07-04'], 'rank_icir': '0.067', 'weight': '0.027'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260704_14 608006185872948582 (Recorders: 3/5)

	Recorder: 3a7bcee9ecb1423c9bd589725e643e04

		Model: {'id': '3a7bcee9ecb1423c9bd589725e643e04', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.006, 'ICIR': 0.033, 'Rank IC': 0.038, 'Rank ICIR': 0.22}, 'data_train_vec': ['2021-07-04', '2025-04-03'], 'train_time_vec': ['2026-07-04', '2026-07-04'], 'rank_icir': '0.220', 'weight': '0.089'}

	Recorder: 5738c8685507497dab600658ba7f66c8

		Model: {'id': '5738c8685507497dab600658ba7f66c8', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.021, 'ICIR': 0.136, 'Rank IC': 0.046, 'Rank ICIR': 0.284}, 'data_train_vec': ['2022-07-04', '2025-07-03'], 'train_time_vec': ['2026-07-04', '2026-07-04'], 'rank_icir': '0.284', 'weight': '0.115'}

	Recorder: 4904cb452ed74e43baae7aec481f87bd

		Model: {'id': '4904cb452ed74e43baae7aec481f87bd', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.023, 'ICIR': 0.175, 'Rank IC': 0.033, 'Rank ICIR': 0.259}, 'data_train_vec': ['2023-07-04', '2025-10-03'], 'train_time_vec': ['2026-07-04', '2026-07-04'], 'rank_icir': '0.259', 'weight': '0.104'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260704_14 956816385440983133 (Recorders: 2/5)

	Recorder: e834f90719994c74a6be8f2ab66ee070

		Model: {'id': 'e834f90719994c74a6be8f2ab66ee070', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.008, 'ICIR': 0.054, 'Rank IC': 0.019, 'Rank ICIR': 0.142}, 'data_train_vec': ['2023-07-04', '2025-10-03'], 'train_time_vec': ['2026-07-04', '2026-07-04'], 'rank_icir': '0.142', 'weight': '0.057'}

	Recorder: abc67afd45984c49b757765f88d15351

		Model: {'id': 'abc67afd45984c49b757765f88d15351', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.031, 'ICIR': 0.133, 'Rank IC': 0.008, 'Rank ICIR': 0.04}, 'data_train_vec': ['2025-07-04', '2026-04-03'], 'train_time_vec': ['2026-07-04', '2026-07-04'], 'rank_icir': '0.040', 'weight': '0.016'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260704_13 241323031912230357 (Recorders: 2/5)

	Recorder: cc753568afac4e3c897336cfbe7ceeb7

		Model: {'id': 'cc753568afac4e3c897336cfbe7ceeb7', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.006, 'ICIR': 0.039, 'Rank IC': 0.036, 'Rank ICIR': 0.219}, 'data_train_vec': ['2022-07-04', '2025-07-03'], 'train_time_vec': ['2026-07-04', '2026-07-04'], 'rank_icir': '0.219', 'weight': '0.088'}

	Recorder: aff40279ea544887aa2ef4d05f85b06c

		Model: {'id': 'aff40279ea544887aa2ef4d05f85b06c', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.009, 'ICIR': 0.08, 'Rank IC': 0.019, 'Rank ICIR': 0.141}, 'data_train_vec': ['2023-07-04', '2025-10-03'], 'train_time_vec': ['2026-07-04', '2026-07-04'], 'rank_icir': '0.141', 'weight': '0.057'}
