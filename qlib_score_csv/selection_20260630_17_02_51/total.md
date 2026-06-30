# params 
 {'predict_dates': [{'start': '2026-06-30', 'end': '2026-06-30'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260630_16 211417435678453031 (Recorders: 2/5)

	Recorder: 8d61022cdba640d9952a3076b371d277

		Model: {'id': '8d61022cdba640d9952a3076b371d277', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.035, 'ICIR': 0.274, 'Rank IC': 0.032, 'Rank ICIR': 0.24}, 'data_train_vec': ['2023-06-30', '2025-09-29'], 'train_time_vec': ['2026-06-30', '2026-06-30'], 'rank_icir': '0.240', 'weight': '0.088'}

	Recorder: 25e7bea7a29a4dc6aaad6c9f61385eea

		Model: {'id': '25e7bea7a29a4dc6aaad6c9f61385eea', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.029, 'ICIR': 0.266, 'Rank IC': 0.034, 'Rank ICIR': 0.307}, 'data_train_vec': ['2024-06-30', '2025-12-29'], 'train_time_vec': ['2026-06-30', '2026-06-30'], 'rank_icir': '0.307', 'weight': '0.113'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260630_16 236628650028982644 (Recorders: 3/5)

	Recorder: 4760512309bc4eb5ace26407aec30aa6

		Model: {'id': '4760512309bc4eb5ace26407aec30aa6', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.033, 'ICIR': 0.258, 'Rank IC': 0.029, 'Rank ICIR': 0.219}, 'data_train_vec': ['2023-06-30', '2025-09-29'], 'train_time_vec': ['2026-06-30', '2026-06-30'], 'rank_icir': '0.219', 'weight': '0.081'}

	Recorder: c31f865d3e3540a4877ef280e2860218

		Model: {'id': 'c31f865d3e3540a4877ef280e2860218', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.039, 'ICIR': 0.29, 'Rank IC': 0.033, 'Rank ICIR': 0.286}, 'data_train_vec': ['2024-06-30', '2025-12-29'], 'train_time_vec': ['2026-06-30', '2026-06-30'], 'rank_icir': '0.286', 'weight': '0.105'}

	Recorder: 504c417185d640fab69172d8124637c0

		Model: {'id': '504c417185d640fab69172d8124637c0', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.075, 'ICIR': 0.287, 'Rank IC': 0.042, 'Rank ICIR': 0.179}, 'data_train_vec': ['2025-06-30', '2026-03-29'], 'train_time_vec': ['2026-06-30', '2026-06-30'], 'rank_icir': '0.179', 'weight': '0.066'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260630_14 922549896573423451 (Recorders: 3/5)

	Recorder: 69e7a027b5d74693ba29f8d28ac2fabf

		Model: {'id': '69e7a027b5d74693ba29f8d28ac2fabf', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.005, 'ICIR': 0.029, 'Rank IC': 0.04, 'Rank ICIR': 0.247}, 'data_train_vec': ['2021-06-30', '2025-03-29'], 'train_time_vec': ['2026-06-30', '2026-06-30'], 'rank_icir': '0.247', 'weight': '0.091'}

	Recorder: ca629862516a401f92c2e764be45fcaa

		Model: {'id': 'ca629862516a401f92c2e764be45fcaa', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.014, 'ICIR': 0.094, 'Rank IC': 0.04, 'Rank ICIR': 0.25}, 'data_train_vec': ['2022-06-28', '2025-06-27'], 'train_time_vec': ['2026-06-30', '2026-06-30'], 'rank_icir': '0.250', 'weight': '0.092'}

	Recorder: 7bc30016481f4d3b9f375e09ef89f46c

		Model: {'id': '7bc30016481f4d3b9f375e09ef89f46c', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.032, 'ICIR': 0.241, 'Rank IC': 0.038, 'Rank ICIR': 0.299}, 'data_train_vec': ['2023-06-30', '2025-09-29'], 'train_time_vec': ['2026-06-30', '2026-06-30'], 'rank_icir': '0.299', 'weight': '0.110'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260630_14 727018060098994249 (Recorders: 1/5)

	Recorder: 4971226c19f54870bba3c1ace25270a6

		Model: {'id': '4971226c19f54870bba3c1ace25270a6', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.005, 'ICIR': 0.038, 'Rank IC': 0.021, 'Rank ICIR': 0.155}, 'data_train_vec': ['2023-06-30', '2025-09-29'], 'train_time_vec': ['2026-06-30', '2026-06-30'], 'rank_icir': '0.155', 'weight': '0.057'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260630_14 627446017714042041 (Recorders: 3/5)

	Recorder: 3d9408af4a42416bbbc6d40c02dfab95

		Model: {'id': '3d9408af4a42416bbbc6d40c02dfab95', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.003, 'ICIR': 0.023, 'Rank IC': 0.037, 'Rank ICIR': 0.217}, 'data_train_vec': ['2022-06-28', '2025-06-27'], 'train_time_vec': ['2026-06-30', '2026-06-30'], 'rank_icir': '0.217', 'weight': '0.080'}

	Recorder: 5c0018623f8b4c78be259068a8404d79

		Model: {'id': '5c0018623f8b4c78be259068a8404d79', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.009, 'ICIR': 0.07, 'Rank IC': 0.025, 'Rank ICIR': 0.183}, 'data_train_vec': ['2023-06-30', '2025-09-29'], 'train_time_vec': ['2026-06-30', '2026-06-30'], 'rank_icir': '0.183', 'weight': '0.067'}

	Recorder: 926318f74d0745cf9aa05f8b20b79987

		Model: {'id': '926318f74d0745cf9aa05f8b20b79987', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.004, 'ICIR': 0.035, 'Rank IC': 0.014, 'Rank ICIR': 0.13}, 'data_train_vec': ['2024-06-30', '2025-12-29'], 'train_time_vec': ['2026-06-30', '2026-06-30'], 'rank_icir': '0.130', 'weight': '0.048'}
