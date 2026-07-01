# params 
 {'predict_dates': [{'start': '2026-07-01', 'end': '2026-07-01'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260701_17 559802846143223155 (Recorders: 4/5)

	Recorder: c8966d97603a4b048b84eb54ad98ee84

		Model: {'id': 'c8966d97603a4b048b84eb54ad98ee84', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.007, 'ICIR': 0.066, 'Rank IC': 0.015, 'Rank ICIR': 0.11}, 'data_train_vec': ['2022-07-01', '2025-06-30'], 'train_time_vec': ['2026-07-01', '2026-07-01'], 'rank_icir': '0.110', 'weight': '0.046'}

	Recorder: 29e2f6b776b74731aab540d43de59649

		Model: {'id': '29e2f6b776b74731aab540d43de59649', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.031, 'ICIR': 0.25, 'Rank IC': 0.028, 'Rank ICIR': 0.221}, 'data_train_vec': ['2023-07-01', '2025-09-30'], 'train_time_vec': ['2026-07-01', '2026-07-01'], 'rank_icir': '0.221', 'weight': '0.093'}

	Recorder: d606917376b5460e920dab2fd9d93639

		Model: {'id': 'd606917376b5460e920dab2fd9d93639', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.02, 'ICIR': 0.181, 'Rank IC': 0.025, 'Rank ICIR': 0.221}, 'data_train_vec': ['2024-07-01', '2025-12-31'], 'train_time_vec': ['2026-07-01', '2026-07-01'], 'rank_icir': '0.221', 'weight': '0.093'}

	Recorder: def895c8bad44950abad775c194cedd5

		Model: {'id': 'def895c8bad44950abad775c194cedd5', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.018, 'ICIR': 0.116, 'Rank IC': 0.008, 'Rank ICIR': 0.055}, 'data_train_vec': ['2025-07-01', '2026-03-31'], 'train_time_vec': ['2026-07-01', '2026-07-01'], 'rank_icir': '0.055', 'weight': '0.023'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260701_17 489698752669352033 (Recorders: 3/5)

	Recorder: 63bf1bb5286b433fb06422f2e8e0c08f

		Model: {'id': '63bf1bb5286b433fb06422f2e8e0c08f', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.021, 'ICIR': 0.195, 'Rank IC': 0.025, 'Rank ICIR': 0.191}, 'data_train_vec': ['2023-07-01', '2025-09-30'], 'train_time_vec': ['2026-07-01', '2026-07-01'], 'rank_icir': '0.191', 'weight': '0.081'}

	Recorder: 93bf865f4d5d448f8b8ae556d2e995c3

		Model: {'id': '93bf865f4d5d448f8b8ae556d2e995c3', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.031, 'ICIR': 0.222, 'Rank IC': 0.027, 'Rank ICIR': 0.209}, 'data_train_vec': ['2024-07-01', '2025-12-31'], 'train_time_vec': ['2026-07-01', '2026-07-01'], 'rank_icir': '0.209', 'weight': '0.088'}

	Recorder: 3d5d17b21c43433b840130f148a86459

		Model: {'id': '3d5d17b21c43433b840130f148a86459', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.059, 'ICIR': 0.245, 'Rank IC': 0.044, 'Rank ICIR': 0.208}, 'data_train_vec': ['2025-07-01', '2026-03-31'], 'train_time_vec': ['2026-07-01', '2026-07-01'], 'rank_icir': '0.208', 'weight': '0.088'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260701_15 613684738334010577 (Recorders: 3/5)

	Recorder: 261cecdc2f1941ed8374bc12280929ae

		Model: {'id': '261cecdc2f1941ed8374bc12280929ae', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.004, 'ICIR': 0.023, 'Rank IC': 0.038, 'Rank ICIR': 0.223}, 'data_train_vec': ['2021-07-01', '2025-03-31'], 'train_time_vec': ['2026-07-01', '2026-07-01'], 'rank_icir': '0.223', 'weight': '0.094'}

	Recorder: 8dd6058a915e4ab59ca0a18682c1ed07

		Model: {'id': '8dd6058a915e4ab59ca0a18682c1ed07', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.011, 'ICIR': 0.071, 'Rank IC': 0.037, 'Rank ICIR': 0.23}, 'data_train_vec': ['2022-07-01', '2025-06-30'], 'train_time_vec': ['2026-07-01', '2026-07-01'], 'rank_icir': '0.230', 'weight': '0.097'}

	Recorder: d539a256def844058ccf2bc2b5a094d3

		Model: {'id': 'd539a256def844058ccf2bc2b5a094d3', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.022, 'ICIR': 0.171, 'Rank IC': 0.033, 'Rank ICIR': 0.259}, 'data_train_vec': ['2023-07-01', '2025-09-30'], 'train_time_vec': ['2026-07-01', '2026-07-01'], 'rank_icir': '0.259', 'weight': '0.109'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260701_15 682287373112865821 (Recorders: 2/5)

	Recorder: 2e310b329e0149a588b62af00a881871

		Model: {'id': '2e310b329e0149a588b62af00a881871', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.005, 'ICIR': 0.039, 'Rank IC': 0.023, 'Rank ICIR': 0.172}, 'data_train_vec': ['2023-07-01', '2025-09-30'], 'train_time_vec': ['2026-07-01', '2026-07-01'], 'rank_icir': '0.172', 'weight': '0.073'}

	Recorder: 6051a7ee92974f8391d879e92049a0e3

		Model: {'id': '6051a7ee92974f8391d879e92049a0e3', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.02, 'ICIR': 0.078, 'Rank IC': 0.002, 'Rank ICIR': 0.007}, 'data_train_vec': ['2025-07-01', '2026-03-31'], 'train_time_vec': ['2026-07-01', '2026-07-01'], 'rank_icir': '0.007', 'weight': '0.003'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260701_14 231676536439163319 (Recorders: 2/5)

	Recorder: 6153b7ed85b9455ea23ed36fe4feb82f

		Model: {'id': '6153b7ed85b9455ea23ed36fe4feb82f', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.006, 'ICIR': 0.056, 'Rank IC': 0.012, 'Rank ICIR': 0.09}, 'data_train_vec': ['2023-07-01', '2025-09-30'], 'train_time_vec': ['2026-07-01', '2026-07-01'], 'rank_icir': '0.090', 'weight': '0.038'}

	Recorder: e3d1d173da2e4cee83c3dba837119d06

		Model: {'id': 'e3d1d173da2e4cee83c3dba837119d06', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.009, 'ICIR': 0.081, 'Rank IC': 0.018, 'Rank ICIR': 0.174}, 'data_train_vec': ['2024-07-01', '2025-12-31'], 'train_time_vec': ['2026-07-01', '2026-07-01'], 'rank_icir': '0.174', 'weight': '0.073'}
