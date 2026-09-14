# params 
 {'predict_dates': [{'start': '2026-09-14', 'end': '2026-09-14'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260914_20 750174292592083679 (Recorders: 3/5)

	Recorder: e5e3c80a49ce42e9b32e0d0cc15419b7

		Model: {'id': 'e5e3c80a49ce42e9b32e0d0cc15419b7', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.003, 'ICIR': 0.018, 'Rank IC': 0.018, 'Rank ICIR': 0.11}, 'data_train_vec': ['2021-09-14', '2025-06-13'], 'train_time_vec': ['2026-09-14', '2026-09-14'], 'rank_icir': '0.110', 'weight': '0.041'}

	Recorder: 611a5a71a78c45c2a42089694d1c6253

		Model: {'id': '611a5a71a78c45c2a42089694d1c6253', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.014, 'ICIR': 0.075, 'Rank IC': 0.034, 'Rank ICIR': 0.236}, 'data_train_vec': ['2022-09-14', '2025-09-13'], 'train_time_vec': ['2026-09-14', '2026-09-14'], 'rank_icir': '0.236', 'weight': '0.088'}

	Recorder: 2dd1cac8f9ba47a88172b550f6b3d203

		Model: {'id': '2dd1cac8f9ba47a88172b550f6b3d203', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.01, 'ICIR': 0.035, 'Rank IC': 0.008, 'Rank ICIR': 0.045}, 'data_train_vec': ['2023-09-14', '2025-12-13'], 'train_time_vec': ['2026-09-14', '2026-09-14'], 'rank_icir': '0.045', 'weight': '0.017'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260914_20 641618737520619677 (Recorders: 3/5)

	Recorder: 0575f6d1133a47a5aecd4733c087a236

		Model: {'id': '0575f6d1133a47a5aecd4733c087a236', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.023, 'ICIR': 0.161, 'Rank IC': 0.031, 'Rank ICIR': 0.245}, 'data_train_vec': ['2021-09-14', '2025-06-13'], 'train_time_vec': ['2026-09-14', '2026-09-14'], 'rank_icir': '0.245', 'weight': '0.091'}

	Recorder: ef0e5db4c07e48c5bdfd2bad3797a4cf

		Model: {'id': 'ef0e5db4c07e48c5bdfd2bad3797a4cf', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.035, 'ICIR': 0.188, 'Rank IC': 0.049, 'Rank ICIR': 0.329}, 'data_train_vec': ['2022-09-14', '2025-09-13'], 'train_time_vec': ['2026-09-14', '2026-09-14'], 'rank_icir': '0.329', 'weight': '0.122'}

	Recorder: 7fdafdbbcadc455b8b09c54e8a550090

		Model: {'id': '7fdafdbbcadc455b8b09c54e8a550090', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.012, 'ICIR': 0.07, 'Rank IC': 0.011, 'Rank ICIR': 0.072}, 'data_train_vec': ['2023-09-14', '2025-12-13'], 'train_time_vec': ['2026-09-14', '2026-09-14'], 'rank_icir': '0.072', 'weight': '0.027'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260914_18 783280616004171572 (Recorders: 3/5)

	Recorder: 0e4f7c25605d44918c9420df386334e5

		Model: {'id': '0e4f7c25605d44918c9420df386334e5', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.029, 'ICIR': 0.15, 'Rank IC': 0.041, 'Rank ICIR': 0.242}, 'data_train_vec': ['2021-09-14', '2025-06-13'], 'train_time_vec': ['2026-09-14', '2026-09-14'], 'rank_icir': '0.242', 'weight': '0.090'}

	Recorder: ac42bc73ab024c2589773ee77850a3f4

		Model: {'id': 'ac42bc73ab024c2589773ee77850a3f4', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.032, 'ICIR': 0.141, 'Rank IC': 0.04, 'Rank ICIR': 0.233}, 'data_train_vec': ['2022-09-14', '2025-09-13'], 'train_time_vec': ['2026-09-14', '2026-09-14'], 'rank_icir': '0.233', 'weight': '0.086'}

	Recorder: 1ddd6083d44449b484035668930a5a03

		Model: {'id': '1ddd6083d44449b484035668930a5a03', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.009, 'ICIR': 0.037, 'Rank IC': 0.015, 'Rank ICIR': 0.082}, 'data_train_vec': ['2023-09-14', '2025-12-13'], 'train_time_vec': ['2026-09-14', '2026-09-14'], 'rank_icir': '0.082', 'weight': '0.030'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260914_18 238162986077637405 (Recorders: 5/5)

	Recorder: 01ee3996031d4473bf2926795cffc9d2

		Model: {'id': '01ee3996031d4473bf2926795cffc9d2', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.028, 'ICIR': 0.137, 'Rank IC': 0.037, 'Rank ICIR': 0.219}, 'data_train_vec': ['2021-09-14', '2025-06-13'], 'train_time_vec': ['2026-09-14', '2026-09-14'], 'rank_icir': '0.219', 'weight': '0.081'}

	Recorder: 9a39263961e64509984465c43f94fead

		Model: {'id': '9a39263961e64509984465c43f94fead', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.038, 'ICIR': 0.188, 'Rank IC': 0.032, 'Rank ICIR': 0.192}, 'data_train_vec': ['2022-09-14', '2025-09-13'], 'train_time_vec': ['2026-09-14', '2026-09-14'], 'rank_icir': '0.192', 'weight': '0.071'}

	Recorder: 16daadf482eb4e64a09343ae772ecb24

		Model: {'id': '16daadf482eb4e64a09343ae772ecb24', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.009, 'ICIR': 0.037, 'Rank IC': 0.005, 'Rank ICIR': 0.025}, 'data_train_vec': ['2023-09-14', '2025-12-13'], 'train_time_vec': ['2026-09-14', '2026-09-14'], 'rank_icir': '0.025', 'weight': '0.009'}

	Recorder: a20c82de1d74454db62aa75eca472715

		Model: {'id': 'a20c82de1d74454db62aa75eca472715', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.031, 'ICIR': 0.102, 'Rank IC': 0.018, 'Rank ICIR': 0.072}, 'data_train_vec': ['2024-09-14', '2026-03-13'], 'train_time_vec': ['2026-09-14', '2026-09-14'], 'rank_icir': '0.072', 'weight': '0.027'}

	Recorder: 7def5a517b744ae7bfbfd566c12ffd84

		Model: {'id': '7def5a517b744ae7bfbfd566c12ffd84', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.02, 'ICIR': 0.103, 'Rank IC': 0.016, 'Rank ICIR': 0.086}, 'data_train_vec': ['2025-09-14', '2026-06-13'], 'train_time_vec': ['2026-09-14', '2026-09-14'], 'rank_icir': '0.086', 'weight': '0.032'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260914_18 924183399158231093 (Recorders: 2/5)

	Recorder: 0387230ea6774ac39fc859d345d71c8e

		Model: {'id': '0387230ea6774ac39fc859d345d71c8e', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.005, 'ICIR': 0.022, 'Rank IC': 0.032, 'Rank ICIR': 0.19}, 'data_train_vec': ['2021-09-14', '2025-06-13'], 'train_time_vec': ['2026-09-14', '2026-09-14'], 'rank_icir': '0.190', 'weight': '0.070'}

	Recorder: 4ba473eac64b460b8a93f60e29d37cd1

		Model: {'id': '4ba473eac64b460b8a93f60e29d37cd1', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.017, 'ICIR': 0.075, 'Rank IC': 0.05, 'Rank ICIR': 0.319}, 'data_train_vec': ['2022-09-14', '2025-09-13'], 'train_time_vec': ['2026-09-14', '2026-09-14'], 'rank_icir': '0.319', 'weight': '0.118'}
