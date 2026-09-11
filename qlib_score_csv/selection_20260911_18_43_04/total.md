# params 
 {'predict_dates': [{'start': '2026-09-11', 'end': '2026-09-11'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260911_18 566388444327520961 (Recorders: 2/5)

	Recorder: 6c9d478d9c7743e18a211f23b6d61d0c

		Model: {'id': '6c9d478d9c7743e18a211f23b6d61d0c', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.011, 'ICIR': 0.054, 'Rank IC': 0.029, 'Rank ICIR': 0.188}, 'data_train_vec': ['2022-09-11', '2025-09-10'], 'train_time_vec': ['2026-09-11', '2026-09-11'], 'rank_icir': '0.188', 'weight': '0.074'}

	Recorder: ab5b59f67f9e44068d1e30b501f01ee2

		Model: {'id': 'ab5b59f67f9e44068d1e30b501f01ee2', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.012, 'ICIR': 0.047, 'Rank IC': 0.017, 'Rank ICIR': 0.108}, 'data_train_vec': ['2023-09-11', '2025-12-10'], 'train_time_vec': ['2026-09-11', '2026-09-11'], 'rank_icir': '0.108', 'weight': '0.043'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260911_18 299707104626182421 (Recorders: 3/5)

	Recorder: 4afe5f98d310468bad9e5af4ed2e30e1

		Model: {'id': '4afe5f98d310468bad9e5af4ed2e30e1', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.016, 'ICIR': 0.107, 'Rank IC': 0.026, 'Rank ICIR': 0.204}, 'data_train_vec': ['2021-09-11', '2025-06-10'], 'train_time_vec': ['2026-09-11', '2026-09-11'], 'rank_icir': '0.204', 'weight': '0.080'}

	Recorder: 34e027e641654c049ce3913bee51c767

		Model: {'id': '34e027e641654c049ce3913bee51c767', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.032, 'ICIR': 0.178, 'Rank IC': 0.046, 'Rank ICIR': 0.32}, 'data_train_vec': ['2022-09-11', '2025-09-10'], 'train_time_vec': ['2026-09-11', '2026-09-11'], 'rank_icir': '0.320', 'weight': '0.126'}

	Recorder: ca7e84e01842403192efd94e245990ca

		Model: {'id': 'ca7e84e01842403192efd94e245990ca', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.018, 'ICIR': 0.105, 'Rank IC': 0.017, 'Rank ICIR': 0.108}, 'data_train_vec': ['2023-09-11', '2025-12-10'], 'train_time_vec': ['2026-09-11', '2026-09-11'], 'rank_icir': '0.108', 'weight': '0.043'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260911_16 749541404778331083 (Recorders: 3/5)

	Recorder: 9aaff0ddaf834c63b809193ee2f5241d

		Model: {'id': '9aaff0ddaf834c63b809193ee2f5241d', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.03, 'ICIR': 0.153, 'Rank IC': 0.041, 'Rank ICIR': 0.248}, 'data_train_vec': ['2021-09-11', '2025-06-10'], 'train_time_vec': ['2026-09-11', '2026-09-11'], 'rank_icir': '0.248', 'weight': '0.098'}

	Recorder: 2198b0213c7b418395e348f6f2f9434d

		Model: {'id': '2198b0213c7b418395e348f6f2f9434d', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.03, 'ICIR': 0.131, 'Rank IC': 0.043, 'Rank ICIR': 0.261}, 'data_train_vec': ['2022-09-11', '2025-09-10'], 'train_time_vec': ['2026-09-11', '2026-09-11'], 'rank_icir': '0.261', 'weight': '0.103'}

	Recorder: 450ed30494444ad98855dac200611002

		Model: {'id': '450ed30494444ad98855dac200611002', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.018, 'ICIR': 0.067, 'Rank IC': 0.021, 'Rank ICIR': 0.106}, 'data_train_vec': ['2023-09-11', '2025-12-10'], 'train_time_vec': ['2026-09-11', '2026-09-11'], 'rank_icir': '0.106', 'weight': '0.042'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260911_16 458770691830583043 (Recorders: 5/5)

	Recorder: 27ccb000f0be475da367ac2c23195d2d

		Model: {'id': '27ccb000f0be475da367ac2c23195d2d', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.028, 'ICIR': 0.133, 'Rank IC': 0.035, 'Rank ICIR': 0.212}, 'data_train_vec': ['2021-09-11', '2025-06-10'], 'train_time_vec': ['2026-09-11', '2026-09-11'], 'rank_icir': '0.212', 'weight': '0.083'}

	Recorder: 18f2bb3d49db4d08ba3139e12711a212

		Model: {'id': '18f2bb3d49db4d08ba3139e12711a212', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.038, 'ICIR': 0.194, 'Rank IC': 0.035, 'Rank ICIR': 0.215}, 'data_train_vec': ['2022-09-11', '2025-09-10'], 'train_time_vec': ['2026-09-11', '2026-09-11'], 'rank_icir': '0.215', 'weight': '0.085'}

	Recorder: 03111eafe93f4f8b9e88edbf92a13a2b

		Model: {'id': '03111eafe93f4f8b9e88edbf92a13a2b', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.011, 'ICIR': 0.044, 'Rank IC': 0.006, 'Rank ICIR': 0.029}, 'data_train_vec': ['2023-09-11', '2025-12-10'], 'train_time_vec': ['2026-09-11', '2026-09-11'], 'rank_icir': '0.029', 'weight': '0.011'}

	Recorder: 032cde2d5ba84159ada71ce4f5a86290

		Model: {'id': '032cde2d5ba84159ada71ce4f5a86290', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.022, 'ICIR': 0.07, 'Rank IC': 0.011, 'Rank ICIR': 0.04}, 'data_train_vec': ['2024-09-11', '2026-03-10'], 'train_time_vec': ['2026-09-11', '2026-09-11'], 'rank_icir': '0.040', 'weight': '0.016'}

	Recorder: 1697a3064a34446bad819e384a790caf

		Model: {'id': '1697a3064a34446bad819e384a790caf', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.049, 'ICIR': 0.224, 'Rank IC': 0.038, 'Rank ICIR': 0.185}, 'data_train_vec': ['2025-09-11', '2026-06-10'], 'train_time_vec': ['2026-09-11', '2026-09-11'], 'rank_icir': '0.185', 'weight': '0.073'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260911_16 608782064970237668 (Recorders: 2/5)

	Recorder: a30dad086f084ac7b3dcf08497cc173e

		Model: {'id': 'a30dad086f084ac7b3dcf08497cc173e', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.012, 'ICIR': 0.054, 'Rank IC': 0.038, 'Rank ICIR': 0.235}, 'data_train_vec': ['2022-09-11', '2025-09-10'], 'train_time_vec': ['2026-09-11', '2026-09-11'], 'rank_icir': '0.235', 'weight': '0.093'}

	Recorder: b9b526c7d1da4197a3d3f40f3cedf248

		Model: {'id': 'b9b526c7d1da4197a3d3f40f3cedf248', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.003, 'ICIR': 0.01, 'Rank IC': 0.014, 'Rank ICIR': 0.08}, 'data_train_vec': ['2023-09-11', '2025-12-10'], 'train_time_vec': ['2026-09-11', '2026-09-11'], 'rank_icir': '0.080', 'weight': '0.032'}
