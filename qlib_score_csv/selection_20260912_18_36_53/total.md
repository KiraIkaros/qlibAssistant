# params 
 {'predict_dates': [{'start': '2026-09-11', 'end': '2026-09-11'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260912_18 517468256903981011 (Recorders: 3/5)

	Recorder: 982dc4cf45d14c1dac59105ca2d515c8

		Model: {'id': '982dc4cf45d14c1dac59105ca2d515c8', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.009, 'ICIR': 0.056, 'Rank IC': 0.026, 'Rank ICIR': 0.158}, 'data_train_vec': ['2021-09-12', '2025-06-11'], 'train_time_vec': ['2026-09-12', '2026-09-12'], 'rank_icir': '0.158', 'weight': '0.056'}

	Recorder: b6743330914941238f02344484238701

		Model: {'id': 'b6743330914941238f02344484238701', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.033, 'ICIR': 0.169, 'Rank IC': 0.05, 'Rank ICIR': 0.338}, 'data_train_vec': ['2022-09-12', '2025-09-11'], 'train_time_vec': ['2026-09-12', '2026-09-12'], 'rank_icir': '0.338', 'weight': '0.120'}

	Recorder: 1ae75ca7091645bfb4079c6a4ca5a2b9

		Model: {'id': '1ae75ca7091645bfb4079c6a4ca5a2b9', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.011, 'ICIR': 0.039, 'Rank IC': 0.018, 'Rank ICIR': 0.102}, 'data_train_vec': ['2023-09-12', '2025-12-11'], 'train_time_vec': ['2026-09-12', '2026-09-12'], 'rank_icir': '0.102', 'weight': '0.036'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260912_18 853580985525289626 (Recorders: 3/5)

	Recorder: 9486eb7c36e94e7b8ca3c45ca5afe31a

		Model: {'id': '9486eb7c36e94e7b8ca3c45ca5afe31a', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.015, 'ICIR': 0.106, 'Rank IC': 0.024, 'Rank ICIR': 0.187}, 'data_train_vec': ['2021-09-12', '2025-06-11'], 'train_time_vec': ['2026-09-12', '2026-09-12'], 'rank_icir': '0.187', 'weight': '0.067'}

	Recorder: 0d2066039f634ff0a0846b8fe75c242e

		Model: {'id': '0d2066039f634ff0a0846b8fe75c242e', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.033, 'ICIR': 0.177, 'Rank IC': 0.047, 'Rank ICIR': 0.316}, 'data_train_vec': ['2022-09-12', '2025-09-11'], 'train_time_vec': ['2026-09-12', '2026-09-12'], 'rank_icir': '0.316', 'weight': '0.112'}

	Recorder: 8487740b046044499902173e5831073b

		Model: {'id': '8487740b046044499902173e5831073b', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.011, 'ICIR': 0.081, 'Rank IC': 0.009, 'Rank ICIR': 0.064}, 'data_train_vec': ['2023-09-12', '2025-12-11'], 'train_time_vec': ['2026-09-12', '2026-09-12'], 'rank_icir': '0.064', 'weight': '0.023'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260912_15 518859028184210209 (Recorders: 3/5)

	Recorder: ad422a65f9914d8d9d003fa058e2a1f8

		Model: {'id': 'ad422a65f9914d8d9d003fa058e2a1f8', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.033, 'ICIR': 0.16, 'Rank IC': 0.043, 'Rank ICIR': 0.251}, 'data_train_vec': ['2021-09-12', '2025-06-11'], 'train_time_vec': ['2026-09-12', '2026-09-12'], 'rank_icir': '0.251', 'weight': '0.089'}

	Recorder: 1d86b2bcc96c4d69b93b0921111c04dd

		Model: {'id': '1d86b2bcc96c4d69b93b0921111c04dd', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.035, 'ICIR': 0.16, 'Rank IC': 0.046, 'Rank ICIR': 0.275}, 'data_train_vec': ['2022-09-12', '2025-09-11'], 'train_time_vec': ['2026-09-12', '2026-09-12'], 'rank_icir': '0.275', 'weight': '0.098'}

	Recorder: 109a7a3e3d394f5a91fb228c578c1c61

		Model: {'id': '109a7a3e3d394f5a91fb228c578c1c61', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.007, 'ICIR': 0.026, 'Rank IC': 0.015, 'Rank ICIR': 0.074}, 'data_train_vec': ['2023-09-12', '2025-12-11'], 'train_time_vec': ['2026-09-12', '2026-09-12'], 'rank_icir': '0.074', 'weight': '0.026'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260912_15 669720912368526073 (Recorders: 5/5)

	Recorder: dd35c04dc21443da8f8d6d4bd48e24e0

		Model: {'id': 'dd35c04dc21443da8f8d6d4bd48e24e0', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.028, 'ICIR': 0.134, 'Rank IC': 0.035, 'Rank ICIR': 0.213}, 'data_train_vec': ['2021-09-12', '2025-06-11'], 'train_time_vec': ['2026-09-12', '2026-09-12'], 'rank_icir': '0.213', 'weight': '0.076'}

	Recorder: bbd45983836d45c6a9711c78da0d0fc5

		Model: {'id': 'bbd45983836d45c6a9711c78da0d0fc5', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.038, 'ICIR': 0.194, 'Rank IC': 0.035, 'Rank ICIR': 0.215}, 'data_train_vec': ['2022-09-12', '2025-09-11'], 'train_time_vec': ['2026-09-12', '2026-09-12'], 'rank_icir': '0.215', 'weight': '0.077'}

	Recorder: cd31c1b8fe8640f0897bef42e3759d81

		Model: {'id': 'cd31c1b8fe8640f0897bef42e3759d81', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.008, 'ICIR': 0.03, 'Rank IC': 0.004, 'Rank ICIR': 0.021}, 'data_train_vec': ['2023-09-12', '2025-12-11'], 'train_time_vec': ['2026-09-12', '2026-09-12'], 'rank_icir': '0.021', 'weight': '0.007'}

	Recorder: 7e5f5f5d4efe4e5fbc076f644e742d67

		Model: {'id': '7e5f5f5d4efe4e5fbc076f644e742d67', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.026, 'ICIR': 0.086, 'Rank IC': 0.016, 'Rank ICIR': 0.061}, 'data_train_vec': ['2024-09-12', '2026-03-11'], 'train_time_vec': ['2026-09-12', '2026-09-12'], 'rank_icir': '0.061', 'weight': '0.022'}

	Recorder: 53a4fa79841948e0abcc8068ebfcebe3

		Model: {'id': '53a4fa79841948e0abcc8068ebfcebe3', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.055, 'ICIR': 0.251, 'Rank IC': 0.038, 'Rank ICIR': 0.179}, 'data_train_vec': ['2025-09-12', '2026-06-11'], 'train_time_vec': ['2026-09-12', '2026-09-12'], 'rank_icir': '0.179', 'weight': '0.064'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260912_15 219748772042329787 (Recorders: 2/5)

	Recorder: 20fb7c252a0e4790876cbd14bd7c07f0

		Model: {'id': '20fb7c252a0e4790876cbd14bd7c07f0', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.019, 'ICIR': 0.086, 'Rank IC': 0.044, 'Rank ICIR': 0.284}, 'data_train_vec': ['2022-09-12', '2025-09-11'], 'train_time_vec': ['2026-09-12', '2026-09-12'], 'rank_icir': '0.284', 'weight': '0.101'}

	Recorder: f10bc8625f214af7a24d689674970e10

		Model: {'id': 'f10bc8625f214af7a24d689674970e10', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.002, 'ICIR': 0.008, 'Rank IC': 0.013, 'Rank ICIR': 0.072}, 'data_train_vec': ['2023-09-12', '2025-12-11'], 'train_time_vec': ['2026-09-12', '2026-09-12'], 'rank_icir': '0.072', 'weight': '0.026'}
