# params 
 {'predict_dates': [{'start': '2026-09-28', 'end': '2026-09-28'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260928_21 801054716884538383 (Recorders: 4/5)

	Recorder: 645a257422a64814a35bf3a3946d8518

		Model: {'id': '645a257422a64814a35bf3a3946d8518', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.021, 'ICIR': 0.126, 'Rank IC': 0.038, 'Rank ICIR': 0.282}, 'data_train_vec': ['2021-09-28', '2025-06-27'], 'train_time_vec': ['2026-09-28', '2026-09-28'], 'rank_icir': '0.282', 'weight': '0.110'}

	Recorder: bf55e467c9584c989e1115d8e397b2a6

		Model: {'id': 'bf55e467c9584c989e1115d8e397b2a6', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.021, 'ICIR': 0.089, 'Rank IC': 0.027, 'Rank ICIR': 0.149}, 'data_train_vec': ['2022-09-28', '2025-09-27'], 'train_time_vec': ['2026-09-28', '2026-09-28'], 'rank_icir': '0.149', 'weight': '0.058'}

	Recorder: bba631a26f2c4704ac62a10e9fb6855d

		Model: {'id': 'bba631a26f2c4704ac62a10e9fb6855d', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.005, 'ICIR': 0.016, 'Rank IC': 0.014, 'Rank ICIR': 0.071}, 'data_train_vec': ['2023-09-28', '2025-12-27'], 'train_time_vec': ['2026-09-28', '2026-09-28'], 'rank_icir': '0.071', 'weight': '0.028'}

	Recorder: fc1864b36c5549419c4f4fbb1233e5be

		Model: {'id': 'fc1864b36c5549419c4f4fbb1233e5be', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.04, 'ICIR': 0.24, 'Rank IC': 0.015, 'Rank ICIR': 0.125}, 'data_train_vec': ['2024-09-28', '2026-03-27'], 'train_time_vec': ['2026-09-28', '2026-09-28'], 'rank_icir': '0.125', 'weight': '0.049'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260928_21 123928328472694469 (Recorders: 3/5)

	Recorder: b8f7f33072cb4d8c9ee99ef6b1e702f5

		Model: {'id': 'b8f7f33072cb4d8c9ee99ef6b1e702f5', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.027, 'ICIR': 0.168, 'Rank IC': 0.041, 'Rank ICIR': 0.244}, 'data_train_vec': ['2021-09-28', '2025-06-27'], 'train_time_vec': ['2026-09-28', '2026-09-28'], 'rank_icir': '0.244', 'weight': '0.095'}

	Recorder: 8fffd40725fc43c3aa89e42805e3080b

		Model: {'id': '8fffd40725fc43c3aa89e42805e3080b', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.027, 'ICIR': 0.134, 'Rank IC': 0.033, 'Rank ICIR': 0.188}, 'data_train_vec': ['2022-09-28', '2025-09-27'], 'train_time_vec': ['2026-09-28', '2026-09-28'], 'rank_icir': '0.188', 'weight': '0.073'}

	Recorder: fd8ae32b583a4af2b0caed3aebe3c7d3

		Model: {'id': 'fd8ae32b583a4af2b0caed3aebe3c7d3', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.009, 'ICIR': 0.043, 'Rank IC': 0.015, 'Rank ICIR': 0.076}, 'data_train_vec': ['2023-09-28', '2025-12-27'], 'train_time_vec': ['2026-09-28', '2026-09-28'], 'rank_icir': '0.076', 'weight': '0.030'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260928_19 266355473927933961 (Recorders: 3/5)

	Recorder: 68271875995c4a81895ffa3ab1c48462

		Model: {'id': '68271875995c4a81895ffa3ab1c48462', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.035, 'ICIR': 0.177, 'Rank IC': 0.046, 'Rank ICIR': 0.267}, 'data_train_vec': ['2021-09-28', '2025-06-27'], 'train_time_vec': ['2026-09-28', '2026-09-28'], 'rank_icir': '0.267', 'weight': '0.104'}

	Recorder: 74fc4d41cc06471d96a1c48134eec223

		Model: {'id': '74fc4d41cc06471d96a1c48134eec223', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.03, 'ICIR': 0.131, 'Rank IC': 0.034, 'Rank ICIR': 0.186}, 'data_train_vec': ['2022-09-28', '2025-09-27'], 'train_time_vec': ['2026-09-28', '2026-09-28'], 'rank_icir': '0.186', 'weight': '0.072'}

	Recorder: d031d4c8e0304096a577239cdadef33d

		Model: {'id': 'd031d4c8e0304096a577239cdadef33d', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.012, 'ICIR': 0.041, 'Rank IC': 0.014, 'Rank ICIR': 0.065}, 'data_train_vec': ['2023-09-28', '2025-12-27'], 'train_time_vec': ['2026-09-28', '2026-09-28'], 'rank_icir': '0.065', 'weight': '0.025'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260928_19 643382819991760306 (Recorders: 4/5)

	Recorder: c551f28e9d3940778718261790d4a36e

		Model: {'id': 'c551f28e9d3940778718261790d4a36e', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.033, 'ICIR': 0.166, 'Rank IC': 0.037, 'Rank ICIR': 0.212}, 'data_train_vec': ['2021-09-28', '2025-06-27'], 'train_time_vec': ['2026-09-28', '2026-09-28'], 'rank_icir': '0.212', 'weight': '0.083'}

	Recorder: 68b3c90f56c24621842454ff04a1fbb9

		Model: {'id': '68b3c90f56c24621842454ff04a1fbb9', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.03, 'ICIR': 0.136, 'Rank IC': 0.02, 'Rank ICIR': 0.108}, 'data_train_vec': ['2022-09-28', '2025-09-27'], 'train_time_vec': ['2026-09-28', '2026-09-28'], 'rank_icir': '0.108', 'weight': '0.042'}

	Recorder: b2b9c2b5ab344c51b756851568624330

		Model: {'id': 'b2b9c2b5ab344c51b756851568624330', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.01, 'ICIR': 0.037, 'Rank IC': 0.002, 'Rank ICIR': 0.01}, 'data_train_vec': ['2023-09-28', '2025-12-27'], 'train_time_vec': ['2026-09-28', '2026-09-28'], 'rank_icir': '0.010', 'weight': '0.004'}

	Recorder: 2941e2eaa33d417e9ee1063d063c816c

		Model: {'id': '2941e2eaa33d417e9ee1063d063c816c', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.059, 'ICIR': 0.25, 'Rank IC': 0.033, 'Rank ICIR': 0.174}, 'data_train_vec': ['2024-09-28', '2026-03-27'], 'train_time_vec': ['2026-09-28', '2026-09-28'], 'rank_icir': '0.174', 'weight': '0.068'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260928_19 358902300661377177 (Recorders: 2/5)

	Recorder: 440707005f6c47189ebe02650db676f4

		Model: {'id': '440707005f6c47189ebe02650db676f4', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.007, 'ICIR': 0.033, 'Rank IC': 0.035, 'Rank ICIR': 0.208}, 'data_train_vec': ['2021-09-28', '2025-06-27'], 'train_time_vec': ['2026-09-28', '2026-09-28'], 'rank_icir': '0.208', 'weight': '0.081'}

	Recorder: b12e3c1dd7f24f3f809881101037583c

		Model: {'id': 'b12e3c1dd7f24f3f809881101037583c', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.048, 'ICIR': 0.213, 'Rank IC': 0.03, 'Rank ICIR': 0.204}, 'data_train_vec': ['2024-09-28', '2026-03-27'], 'train_time_vec': ['2026-09-28', '2026-09-28'], 'rank_icir': '0.204', 'weight': '0.079'}
