# params 
 {'predict_dates': [{'start': '2026-08-28', 'end': '2026-08-28'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260829_00 100626871165236314 (Recorders: 2/5)

	Recorder: 5312fbb1fdbf48518c9b258c47d5a4de

		Model: {'id': '5312fbb1fdbf48518c9b258c47d5a4de', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.029, 'ICIR': 0.129, 'Rank IC': 0.035, 'Rank ICIR': 0.227}, 'data_train_vec': ['2022-08-29', '2025-08-28'], 'train_time_vec': ['2026-08-29', '2026-08-29'], 'rank_icir': '0.227', 'weight': '0.119'}

	Recorder: 15e2c94af68f4b56bd499704dc1080b4

		Model: {'id': '15e2c94af68f4b56bd499704dc1080b4', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.019, 'ICIR': 0.072, 'Rank IC': 0.009, 'Rank ICIR': 0.061}, 'data_train_vec': ['2023-08-29', '2025-11-28'], 'train_time_vec': ['2026-08-29', '2026-08-29'], 'rank_icir': '0.061', 'weight': '0.032'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260829_00 600851731447404879 (Recorders: 3/5)

	Recorder: dc32c0a7f06d4ecfb7d0f83263f5c99a

		Model: {'id': 'dc32c0a7f06d4ecfb7d0f83263f5c99a', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.011, 'ICIR': 0.073, 'Rank IC': 0.02, 'Rank ICIR': 0.154}, 'data_train_vec': ['2021-08-29', '2025-05-28'], 'train_time_vec': ['2026-08-29', '2026-08-29'], 'rank_icir': '0.154', 'weight': '0.081'}

	Recorder: 2dee2993d4c84eb79c2c65d035ffa523

		Model: {'id': '2dee2993d4c84eb79c2c65d035ffa523', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.01, 'ICIR': 0.088, 'Rank IC': 0.007, 'Rank ICIR': 0.065}, 'data_train_vec': ['2023-08-29', '2025-11-28'], 'train_time_vec': ['2026-08-29', '2026-08-29'], 'rank_icir': '0.065', 'weight': '0.034'}

	Recorder: c4150c48f43c4091b31b7965f4fc5d8f

		Model: {'id': 'c4150c48f43c4091b31b7965f4fc5d8f', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.001, 'ICIR': 0.01, 'Rank IC': 0.027, 'Rank ICIR': 0.159}, 'data_train_vec': ['2025-08-29', '2026-05-28'], 'train_time_vec': ['2026-08-29', '2026-08-29'], 'rank_icir': '0.159', 'weight': '0.083'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260828_22 252643967621401991 (Recorders: 3/5)

	Recorder: 16cc89972bd94f4dbe5cbca27999fc9c

		Model: {'id': '16cc89972bd94f4dbe5cbca27999fc9c', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.007, 'ICIR': 0.034, 'Rank IC': 0.018, 'Rank ICIR': 0.109}, 'data_train_vec': ['2021-08-28', '2025-05-27'], 'train_time_vec': ['2026-08-29', '2026-08-29'], 'rank_icir': '0.109', 'weight': '0.057'}

	Recorder: 27ef8645d8df4ed2bb53c19eaf90bdb7

		Model: {'id': '27ef8645d8df4ed2bb53c19eaf90bdb7', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.022, 'ICIR': 0.097, 'Rank IC': 0.03, 'Rank ICIR': 0.18}, 'data_train_vec': ['2022-08-28', '2025-08-27'], 'train_time_vec': ['2026-08-28', '2026-08-29'], 'rank_icir': '0.180', 'weight': '0.094'}

	Recorder: 8757efdcd99149cba26a44a657ea0f69

		Model: {'id': '8757efdcd99149cba26a44a657ea0f69', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.003, 'ICIR': 0.01, 'Rank IC': 0.007, 'Rank ICIR': 0.039}, 'data_train_vec': ['2023-08-28', '2025-11-27'], 'train_time_vec': ['2026-08-28', '2026-08-28'], 'rank_icir': '0.039', 'weight': '0.020'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260828_22 562276194446437215 (Recorders: 4/5)

	Recorder: 5f05681b2f6f465a9a4dcaa2a6644e70

		Model: {'id': '5f05681b2f6f465a9a4dcaa2a6644e70', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.012, 'ICIR': 0.055, 'Rank IC': 0.021, 'Rank ICIR': 0.129}, 'data_train_vec': ['2021-08-28', '2025-05-27'], 'train_time_vec': ['2026-08-28', '2026-08-28'], 'rank_icir': '0.129', 'weight': '0.068'}

	Recorder: 040913155cf640749adab157a7abfee0

		Model: {'id': '040913155cf640749adab157a7abfee0', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.029, 'ICIR': 0.153, 'Rank IC': 0.028, 'Rank ICIR': 0.182}, 'data_train_vec': ['2022-08-28', '2025-08-27'], 'train_time_vec': ['2026-08-28', '2026-08-28'], 'rank_icir': '0.182', 'weight': '0.095'}

	Recorder: 71835c1f4b1a4ee19192cfed35c642d5

		Model: {'id': '71835c1f4b1a4ee19192cfed35c642d5', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.033, 'ICIR': 0.1, 'Rank IC': 0.018, 'Rank ICIR': 0.069}, 'data_train_vec': ['2024-08-28', '2026-02-27'], 'train_time_vec': ['2026-08-28', '2026-08-28'], 'rank_icir': '0.069', 'weight': '0.036'}

	Recorder: 66d2ed44b9004821be11b8fe09f2d0c8

		Model: {'id': '66d2ed44b9004821be11b8fe09f2d0c8', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.067, 'ICIR': 0.297, 'Rank IC': 0.036, 'Rank ICIR': 0.198}, 'data_train_vec': ['2025-08-28', '2026-05-27'], 'train_time_vec': ['2026-08-28', '2026-08-28'], 'rank_icir': '0.198', 'weight': '0.104'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260828_22 632129132781085669 (Recorders: 3/5)

	Recorder: ad87c903ad204849b4aba2b50821cf88

		Model: {'id': 'ad87c903ad204849b4aba2b50821cf88', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.002, 'ICIR': 0.008, 'Rank IC': 0.016, 'Rank ICIR': 0.095}, 'data_train_vec': ['2021-08-28', '2025-05-27'], 'train_time_vec': ['2026-08-28', '2026-08-28'], 'rank_icir': '0.095', 'weight': '0.050'}

	Recorder: 6fe660fd542f42e1a8600dfffde12d97

		Model: {'id': '6fe660fd542f42e1a8600dfffde12d97', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.005, 'ICIR': 0.02, 'Rank IC': 0.026, 'Rank ICIR': 0.168}, 'data_train_vec': ['2022-08-28', '2025-08-27'], 'train_time_vec': ['2026-08-28', '2026-08-28'], 'rank_icir': '0.168', 'weight': '0.088'}

	Recorder: e5918d6cff534b66bf577eef6abdf891

		Model: {'id': 'e5918d6cff534b66bf577eef6abdf891', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.04, 'ICIR': 0.128, 'Rank IC': 0.016, 'Rank ICIR': 0.073}, 'data_train_vec': ['2025-08-28', '2026-05-27'], 'train_time_vec': ['2026-08-28', '2026-08-28'], 'rank_icir': '0.073', 'weight': '0.038'}
