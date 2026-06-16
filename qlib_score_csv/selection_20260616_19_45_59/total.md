# params 
 {'predict_dates': [{'start': '2026-06-16', 'end': '2026-06-16'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260616_19 785379768430192543 (Recorders: 2/5)

	Recorder: 65a13aeb1fc6484594070cfd38a0a270

		Model: {'id': '65a13aeb1fc6484594070cfd38a0a270', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.016, 'ICIR': 0.139, 'Rank IC': 0.032, 'Rank ICIR': 0.22}, 'data_train_vec': ['2023-06-16', '2025-09-15'], 'train_time_vec': ['2026-06-16', '2026-06-16'], 'rank_icir': '0.220', 'weight': '0.049'}

	Recorder: 3a061e5d1e72424fb7671f0b1cec6c65

		Model: {'id': '3a061e5d1e72424fb7671f0b1cec6c65', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.012, 'ICIR': 0.107, 'Rank IC': 0.042, 'Rank ICIR': 0.335}, 'data_train_vec': ['2024-06-16', '2025-12-15'], 'train_time_vec': ['2026-06-16', '2026-06-16'], 'rank_icir': '0.335', 'weight': '0.075'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260616_19 126930729208546748 (Recorders: 4/5)

	Recorder: 54999cfbccf54233b4490b78fc0823fe

		Model: {'id': '54999cfbccf54233b4490b78fc0823fe', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.005, 'ICIR': 0.04, 'Rank IC': 0.023, 'Rank ICIR': 0.161}, 'data_train_vec': ['2021-06-16', '2025-03-15'], 'train_time_vec': ['2026-06-16', '2026-06-16'], 'rank_icir': '0.161', 'weight': '0.036'}

	Recorder: b5ffff8e57bf4667b489d52510ba1c8f

		Model: {'id': 'b5ffff8e57bf4667b489d52510ba1c8f', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.005, 'ICIR': 0.032, 'Rank IC': 0.037, 'Rank ICIR': 0.28}, 'data_train_vec': ['2022-06-16', '2025-06-15'], 'train_time_vec': ['2026-06-16', '2026-06-16'], 'rank_icir': '0.280', 'weight': '0.062'}

	Recorder: aa94691452cd4572a5e1ddae0527775f

		Model: {'id': 'aa94691452cd4572a5e1ddae0527775f', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.025, 'ICIR': 0.226, 'Rank IC': 0.036, 'Rank ICIR': 0.279}, 'data_train_vec': ['2023-06-16', '2025-09-15'], 'train_time_vec': ['2026-06-16', '2026-06-16'], 'rank_icir': '0.279', 'weight': '0.062'}

	Recorder: 2b961bec6ffa466e80f54815af01bdea

		Model: {'id': '2b961bec6ffa466e80f54815af01bdea', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.031, 'ICIR': 0.373, 'Rank IC': 0.034, 'Rank ICIR': 0.364}, 'data_train_vec': ['2024-06-16', '2025-12-15'], 'train_time_vec': ['2026-06-16', '2026-06-16'], 'rank_icir': '0.364', 'weight': '0.081'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260616_17 280668191928551240 (Recorders: 4/5)

	Recorder: 440013c380a3440a8c3dc69df91fb9d0

		Model: {'id': '440013c380a3440a8c3dc69df91fb9d0', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.021, 'ICIR': 0.138, 'Rank IC': 0.048, 'Rank ICIR': 0.312}, 'data_train_vec': ['2021-06-16', '2025-03-15'], 'train_time_vec': ['2026-06-16', '2026-06-16'], 'rank_icir': '0.312', 'weight': '0.070'}

	Recorder: 4193440980c84e948ccffe08c9e03025

		Model: {'id': '4193440980c84e948ccffe08c9e03025', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.027, 'ICIR': 0.177, 'Rank IC': 0.056, 'Rank ICIR': 0.323}, 'data_train_vec': ['2022-06-16', '2025-06-15'], 'train_time_vec': ['2026-06-16', '2026-06-16'], 'rank_icir': '0.323', 'weight': '0.072'}

	Recorder: bc081e8dbaf8460b877b61c72b2b6ede

		Model: {'id': 'bc081e8dbaf8460b877b61c72b2b6ede', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.02, 'ICIR': 0.154, 'Rank IC': 0.036, 'Rank ICIR': 0.25}, 'data_train_vec': ['2023-06-16', '2025-09-15'], 'train_time_vec': ['2026-06-16', '2026-06-16'], 'rank_icir': '0.250', 'weight': '0.056'}

	Recorder: 3a5e739b72d74d93a187014f99796d29

		Model: {'id': '3a5e739b72d74d93a187014f99796d29', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.029, 'ICIR': 0.235, 'Rank IC': 0.033, 'Rank ICIR': 0.287}, 'data_train_vec': ['2024-06-16', '2025-12-15'], 'train_time_vec': ['2026-06-16', '2026-06-16'], 'rank_icir': '0.287', 'weight': '0.064'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260616_17 869972903205597110 (Recorders: 4/5)

	Recorder: 4c15195be7204ae492923094710c0f38

		Model: {'id': '4c15195be7204ae492923094710c0f38', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.012, 'ICIR': 0.085, 'Rank IC': 0.04, 'Rank ICIR': 0.344}, 'data_train_vec': ['2021-06-16', '2025-03-15'], 'train_time_vec': ['2026-06-16', '2026-06-16'], 'rank_icir': '0.344', 'weight': '0.077'}

	Recorder: 8220ce7dab034c509784a8c12527b415

		Model: {'id': '8220ce7dab034c509784a8c12527b415', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.004, 'ICIR': 0.024, 'Rank IC': 0.041, 'Rank ICIR': 0.305}, 'data_train_vec': ['2022-06-16', '2025-06-15'], 'train_time_vec': ['2026-06-16', '2026-06-16'], 'rank_icir': '0.305', 'weight': '0.068'}

	Recorder: 268c1b3c22394d818afab0973ae8db50

		Model: {'id': '268c1b3c22394d818afab0973ae8db50', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.009, 'ICIR': 0.075, 'Rank IC': 0.033, 'Rank ICIR': 0.286}, 'data_train_vec': ['2023-06-16', '2025-09-15'], 'train_time_vec': ['2026-06-16', '2026-06-16'], 'rank_icir': '0.286', 'weight': '0.064'}

	Recorder: 869814bfd17c4199aec8f92eec305cac

		Model: {'id': '869814bfd17c4199aec8f92eec305cac', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.029, 'ICIR': 0.185, 'Rank IC': 0.029, 'Rank ICIR': 0.2}, 'data_train_vec': ['2024-06-16', '2025-12-15'], 'train_time_vec': ['2026-06-16', '2026-06-16'], 'rank_icir': '0.200', 'weight': '0.045'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260616_17 244134221386341880 (Recorders: 2/5)

	Recorder: 3135e0ac40da484d8d263b090c2124f0

		Model: {'id': '3135e0ac40da484d8d263b090c2124f0', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.005, 'ICIR': 0.035, 'Rank IC': 0.039, 'Rank ICIR': 0.239}, 'data_train_vec': ['2021-06-16', '2025-03-15'], 'train_time_vec': ['2026-06-16', '2026-06-16'], 'rank_icir': '0.239', 'weight': '0.053'}

	Recorder: 0e74f82f40c5490e8a08a21a60904ef8

		Model: {'id': '0e74f82f40c5490e8a08a21a60904ef8', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.013, 'ICIR': 0.11, 'Rank IC': 0.024, 'Rank ICIR': 0.297}, 'data_train_vec': ['2024-06-16', '2025-12-15'], 'train_time_vec': ['2026-06-16', '2026-06-16'], 'rank_icir': '0.297', 'weight': '0.066'}
