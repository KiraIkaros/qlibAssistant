# params 
 {'predict_dates': [{'start': '2026-06-26', 'end': '2026-06-26'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260629_18 457680708710747117 (Recorders: 2/5)

	Recorder: 07553cf9736d4382b23cf165ae889d1d

		Model: {'id': '07553cf9736d4382b23cf165ae889d1d', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.031, 'ICIR': 0.258, 'Rank IC': 0.031, 'Rank ICIR': 0.251}, 'data_train_vec': ['2023-06-29', '2025-09-28'], 'train_time_vec': ['2026-06-29', '2026-06-29'], 'rank_icir': '0.251', 'weight': '0.108'}

	Recorder: 44cafb92aa984593967f0ea492704f73

		Model: {'id': '44cafb92aa984593967f0ea492704f73', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.028, 'ICIR': 0.275, 'Rank IC': 0.025, 'Rank ICIR': 0.268}, 'data_train_vec': ['2024-06-29', '2025-12-28'], 'train_time_vec': ['2026-06-29', '2026-06-29'], 'rank_icir': '0.268', 'weight': '0.115'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260629_18 908290969268152774 (Recorders: 3/5)

	Recorder: 3512f9be59d44777a8ff3cff6ce43c3a

		Model: {'id': '3512f9be59d44777a8ff3cff6ce43c3a', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.021, 'ICIR': 0.204, 'Rank IC': 0.025, 'Rank ICIR': 0.204}, 'data_train_vec': ['2023-06-29', '2025-09-28'], 'train_time_vec': ['2026-06-29', '2026-06-29'], 'rank_icir': '0.204', 'weight': '0.087'}

	Recorder: 39d5914fe93d4b11ad070688f6d99e61

		Model: {'id': '39d5914fe93d4b11ad070688f6d99e61', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.037, 'ICIR': 0.266, 'Rank IC': 0.029, 'Rank ICIR': 0.25}, 'data_train_vec': ['2024-06-29', '2025-12-28'], 'train_time_vec': ['2026-06-29', '2026-06-29'], 'rank_icir': '0.250', 'weight': '0.107'}

	Recorder: 083dc237f8524e219c2e6d04ec8a63d2

		Model: {'id': '083dc237f8524e219c2e6d04ec8a63d2', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.073, 'ICIR': 0.291, 'Rank IC': 0.039, 'Rank ICIR': 0.173}, 'data_train_vec': ['2025-06-29', '2026-03-28'], 'train_time_vec': ['2026-06-29', '2026-06-29'], 'rank_icir': '0.173', 'weight': '0.074'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260629_16 594495422920996162 (Recorders: 3/5)

	Recorder: 2d02d798bbb04328b3470e12e88ca3c5

		Model: {'id': '2d02d798bbb04328b3470e12e88ca3c5', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.008, 'ICIR': 0.045, 'Rank IC': 0.042, 'Rank ICIR': 0.24}, 'data_train_vec': ['2021-06-29', '2025-03-28'], 'train_time_vec': ['2026-06-29', '2026-06-29'], 'rank_icir': '0.240', 'weight': '0.103'}

	Recorder: 7b6a033a7ba64048abca2556e8bc1939

		Model: {'id': '7b6a033a7ba64048abca2556e8bc1939', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.013, 'ICIR': 0.084, 'Rank IC': 0.039, 'Rank ICIR': 0.242}, 'data_train_vec': ['2022-06-28', '2025-06-27'], 'train_time_vec': ['2026-06-29', '2026-06-29'], 'rank_icir': '0.242', 'weight': '0.104'}

	Recorder: a535c5201a0a4882bb48497428cde5eb

		Model: {'id': 'a535c5201a0a4882bb48497428cde5eb', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.015, 'ICIR': 0.112, 'Rank IC': 0.025, 'Rank ICIR': 0.194}, 'data_train_vec': ['2023-06-29', '2025-09-28'], 'train_time_vec': ['2026-06-29', '2026-06-29'], 'rank_icir': '0.194', 'weight': '0.083'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260629_16 899501673083006518 (Recorders: 1/5)

	Recorder: 7407e63116f4419a918d31079731777d

		Model: {'id': '7407e63116f4419a918d31079731777d', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.003, 'ICIR': 0.02, 'Rank IC': 0.02, 'Rank ICIR': 0.149}, 'data_train_vec': ['2023-06-29', '2025-09-28'], 'train_time_vec': ['2026-06-29', '2026-06-29'], 'rank_icir': '0.149', 'weight': '0.064'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260629_16 118268400896050203 (Recorders: 2/5)

	Recorder: 67a37d3ff54340c7a58ad39ef528fc14

		Model: {'id': '67a37d3ff54340c7a58ad39ef528fc14', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.003, 'ICIR': 0.023, 'Rank IC': 0.037, 'Rank ICIR': 0.217}, 'data_train_vec': ['2022-06-28', '2025-06-27'], 'train_time_vec': ['2026-06-29', '2026-06-29'], 'rank_icir': '0.217', 'weight': '0.093'}

	Recorder: 52572c06e13a459a8193092c4d9de457

		Model: {'id': '52572c06e13a459a8193092c4d9de457', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.014, 'ICIR': 0.116, 'Rank IC': 0.021, 'Rank ICIR': 0.145}, 'data_train_vec': ['2023-06-29', '2025-09-28'], 'train_time_vec': ['2026-06-29', '2026-06-29'], 'rank_icir': '0.145', 'weight': '0.062'}
