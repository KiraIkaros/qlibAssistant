# params 
 {'predict_dates': [{'start': '2026-08-28', 'end': '2026-08-28'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260831_21 107296598083643409 (Recorders: 2/5)

	Recorder: 51cfa163bd5643d7b386a026f8e91ac8

		Model: {'id': '51cfa163bd5643d7b386a026f8e91ac8', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.023, 'ICIR': 0.137, 'Rank IC': 0.03, 'Rank ICIR': 0.24}, 'data_train_vec': ['2022-08-30', '2025-08-29'], 'train_time_vec': ['2026-08-31', '2026-08-31'], 'rank_icir': '0.240', 'weight': '0.119'}

	Recorder: 0dba8488af624396b8f963677ea4581e

		Model: {'id': '0dba8488af624396b8f963677ea4581e', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.009, 'ICIR': 0.041, 'Rank IC': 0.01, 'Rank ICIR': 0.078}, 'data_train_vec': ['2023-08-30', '2025-11-29'], 'train_time_vec': ['2026-08-31', '2026-08-31'], 'rank_icir': '0.078', 'weight': '0.039'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260831_21 355611685374431150 (Recorders: 3/5)

	Recorder: 51ae220b3a8e41d9b5b5527020c0c217

		Model: {'id': '51ae220b3a8e41d9b5b5527020c0c217', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.005, 'ICIR': 0.038, 'Rank IC': 0.018, 'Rank ICIR': 0.125}, 'data_train_vec': ['2021-08-31', '2025-05-30'], 'train_time_vec': ['2026-08-31', '2026-08-31'], 'rank_icir': '0.125', 'weight': '0.062'}

	Recorder: 83752ffe1a43459da57bf1e95ffc5e71

		Model: {'id': '83752ffe1a43459da57bf1e95ffc5e71', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.015, 'ICIR': 0.158, 'Rank IC': 0.018, 'Rank ICIR': 0.167}, 'data_train_vec': ['2022-08-30', '2025-08-29'], 'train_time_vec': ['2026-08-31', '2026-08-31'], 'rank_icir': '0.167', 'weight': '0.083'}

	Recorder: ce1575bef17b44969664bfe640e68eb5

		Model: {'id': 'ce1575bef17b44969664bfe640e68eb5', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.008, 'ICIR': 0.045, 'Rank IC': 0.007, 'Rank ICIR': 0.048}, 'data_train_vec': ['2023-08-30', '2025-11-29'], 'train_time_vec': ['2026-08-31', '2026-08-31'], 'rank_icir': '0.048', 'weight': '0.024'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260831_19 944572315540342225 (Recorders: 3/5)

	Recorder: 619edc5987e1400ca8857def91b93051

		Model: {'id': '619edc5987e1400ca8857def91b93051', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.013, 'ICIR': 0.068, 'Rank IC': 0.024, 'Rank ICIR': 0.145}, 'data_train_vec': ['2021-08-31', '2025-05-30'], 'train_time_vec': ['2026-08-31', '2026-08-31'], 'rank_icir': '0.145', 'weight': '0.072'}

	Recorder: c725f34a146645cf9b77576d274cd0f7

		Model: {'id': 'c725f34a146645cf9b77576d274cd0f7', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.029, 'ICIR': 0.127, 'Rank IC': 0.034, 'Rank ICIR': 0.198}, 'data_train_vec': ['2022-08-30', '2025-08-29'], 'train_time_vec': ['2026-08-31', '2026-08-31'], 'rank_icir': '0.198', 'weight': '0.098'}

	Recorder: cd2d40bc79d74dfaa3489d8941db6b02

		Model: {'id': 'cd2d40bc79d74dfaa3489d8941db6b02', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.038, 'ICIR': 0.168, 'Rank IC': 0.026, 'Rank ICIR': 0.12}, 'data_train_vec': ['2025-08-31', '2026-05-30'], 'train_time_vec': ['2026-08-31', '2026-08-31'], 'rank_icir': '0.120', 'weight': '0.059'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260831_19 549913393867549379 (Recorders: 5/5)

	Recorder: e4199eaafcce4f0eb2f4af1b67ad01ff

		Model: {'id': 'e4199eaafcce4f0eb2f4af1b67ad01ff', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.015, 'ICIR': 0.072, 'Rank IC': 0.024, 'Rank ICIR': 0.148}, 'data_train_vec': ['2021-08-31', '2025-05-30'], 'train_time_vec': ['2026-08-31', '2026-08-31'], 'rank_icir': '0.148', 'weight': '0.073'}

	Recorder: 6258d1a46b924432847c2bd09b595cc7

		Model: {'id': '6258d1a46b924432847c2bd09b595cc7', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.03, 'ICIR': 0.158, 'Rank IC': 0.029, 'Rank ICIR': 0.18}, 'data_train_vec': ['2022-08-30', '2025-08-29'], 'train_time_vec': ['2026-08-31', '2026-08-31'], 'rank_icir': '0.180', 'weight': '0.089'}

	Recorder: 674a527e5fb748a8b8447ca711531615

		Model: {'id': '674a527e5fb748a8b8447ca711531615', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.009, 'ICIR': 0.033, 'Rank IC': 0.002, 'Rank ICIR': 0.011}, 'data_train_vec': ['2023-08-30', '2025-11-29'], 'train_time_vec': ['2026-08-31', '2026-08-31'], 'rank_icir': '0.011', 'weight': '0.005'}

	Recorder: a545f5f00c8c44b58e3ccfe75996eccd

		Model: {'id': 'a545f5f00c8c44b58e3ccfe75996eccd', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.03, 'ICIR': 0.091, 'Rank IC': 0.017, 'Rank ICIR': 0.061}, 'data_train_vec': ['2024-08-28', '2026-02-27'], 'train_time_vec': ['2026-08-31', '2026-08-31'], 'rank_icir': '0.061', 'weight': '0.030'}

	Recorder: 805ff5af1da6463a815c7a002e6ffab3

		Model: {'id': '805ff5af1da6463a815c7a002e6ffab3', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.104, 'ICIR': 0.475, 'Rank IC': 0.064, 'Rank ICIR': 0.358}, 'data_train_vec': ['2025-08-31', '2026-05-30'], 'train_time_vec': ['2026-08-31', '2026-08-31'], 'rank_icir': '0.358', 'weight': '0.177'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260831_19 182162152641680486 (Recorders: 1/5)

	Recorder: 6349085f66b94c87ade438d2d42aa1db

		Model: {'id': '6349085f66b94c87ade438d2d42aa1db', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.076, 'ICIR': 0.239, 'Rank IC': 0.031, 'Rank ICIR': 0.14}, 'data_train_vec': ['2025-08-31', '2026-05-30'], 'train_time_vec': ['2026-08-31', '2026-08-31'], 'rank_icir': '0.140', 'weight': '0.069'}
