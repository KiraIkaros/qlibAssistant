# params 
 {'predict_dates': [{'start': '2026-09-17', 'end': '2026-09-17'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260917_19 635934245074838755 (Recorders: 3/5)

	Recorder: 38337cf3f7af49b1925726f595966f47

		Model: {'id': '38337cf3f7af49b1925726f595966f47', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.008, 'ICIR': 0.048, 'Rank IC': 0.027, 'Rank ICIR': 0.18}, 'data_train_vec': ['2021-09-17', '2025-06-16'], 'train_time_vec': ['2026-09-17', '2026-09-17'], 'rank_icir': '0.180', 'weight': '0.077'}

	Recorder: 9acddca0425a4a26bcc7d637e9a0c7d2

		Model: {'id': '9acddca0425a4a26bcc7d637e9a0c7d2', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.017, 'ICIR': 0.074, 'Rank IC': 0.033, 'Rank ICIR': 0.198}, 'data_train_vec': ['2022-09-17', '2025-09-16'], 'train_time_vec': ['2026-09-17', '2026-09-17'], 'rank_icir': '0.198', 'weight': '0.085'}

	Recorder: 402b4e82810b43f591370303e2b5e1a7

		Model: {'id': '402b4e82810b43f591370303e2b5e1a7', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.003, 'ICIR': 0.009, 'Rank IC': 0.005, 'Rank ICIR': 0.024}, 'data_train_vec': ['2023-09-17', '2025-12-16'], 'train_time_vec': ['2026-09-17', '2026-09-17'], 'rank_icir': '0.024', 'weight': '0.010'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260917_19 362544409951237282 (Recorders: 3/5)

	Recorder: 8b060c41af0447cc8a08b4a5547dfdcb

		Model: {'id': '8b060c41af0447cc8a08b4a5547dfdcb', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.024, 'ICIR': 0.148, 'Rank IC': 0.036, 'Rank ICIR': 0.241}, 'data_train_vec': ['2021-09-17', '2025-06-16'], 'train_time_vec': ['2026-09-17', '2026-09-17'], 'rank_icir': '0.241', 'weight': '0.104'}

	Recorder: 0b35c670ad18429bb61c66bcd1258af1

		Model: {'id': '0b35c670ad18429bb61c66bcd1258af1', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.028, 'ICIR': 0.144, 'Rank IC': 0.038, 'Rank ICIR': 0.247}, 'data_train_vec': ['2022-09-17', '2025-09-16'], 'train_time_vec': ['2026-09-17', '2026-09-17'], 'rank_icir': '0.247', 'weight': '0.106'}

	Recorder: f7ca9abbdd8846a1ba3a3fa226b02c39

		Model: {'id': 'f7ca9abbdd8846a1ba3a3fa226b02c39', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.04, 'ICIR': 0.167, 'Rank IC': 0.021, 'Rank ICIR': 0.121}, 'data_train_vec': ['2024-09-17', '2026-03-16'], 'train_time_vec': ['2026-09-17', '2026-09-17'], 'rank_icir': '0.121', 'weight': '0.052'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260917_17 370058882433278251 (Recorders: 4/5)

	Recorder: 87bd431442ab4ea89e66f1d3c051e353

		Model: {'id': '87bd431442ab4ea89e66f1d3c051e353', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.031, 'ICIR': 0.158, 'Rank IC': 0.044, 'Rank ICIR': 0.264}, 'data_train_vec': ['2021-09-17', '2025-06-16'], 'train_time_vec': ['2026-09-17', '2026-09-17'], 'rank_icir': '0.264', 'weight': '0.114'}

	Recorder: 1ca90974c41345ecb8f9f9914f79a949

		Model: {'id': '1ca90974c41345ecb8f9f9914f79a949', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.03, 'ICIR': 0.136, 'Rank IC': 0.038, 'Rank ICIR': 0.227}, 'data_train_vec': ['2022-09-17', '2025-09-16'], 'train_time_vec': ['2026-09-17', '2026-09-17'], 'rank_icir': '0.227', 'weight': '0.098'}

	Recorder: 0eaf88c1e1cc450e95cefbe655baa1c0

		Model: {'id': '0eaf88c1e1cc450e95cefbe655baa1c0', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.007, 'ICIR': 0.028, 'Rank IC': 0.012, 'Rank ICIR': 0.06}, 'data_train_vec': ['2023-09-17', '2025-12-16'], 'train_time_vec': ['2026-09-17', '2026-09-17'], 'rank_icir': '0.060', 'weight': '0.026'}

	Recorder: 62950624849a4852a2901398ebb8076f

		Model: {'id': '62950624849a4852a2901398ebb8076f', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.033, 'ICIR': 0.12, 'Rank IC': 0.018, 'Rank ICIR': 0.08}, 'data_train_vec': ['2024-09-17', '2026-03-16'], 'train_time_vec': ['2026-09-17', '2026-09-17'], 'rank_icir': '0.080', 'weight': '0.034'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260917_17 738510639313901805 (Recorders: 4/5)

	Recorder: 9485e4ecc2674b3298bffdd81059776f

		Model: {'id': '9485e4ecc2674b3298bffdd81059776f', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.031, 'ICIR': 0.156, 'Rank IC': 0.038, 'Rank ICIR': 0.229}, 'data_train_vec': ['2021-09-17', '2025-06-16'], 'train_time_vec': ['2026-09-17', '2026-09-17'], 'rank_icir': '0.229', 'weight': '0.099'}

	Recorder: c8d34a525fad4fea9e80630fd36ee3c6

		Model: {'id': 'c8d34a525fad4fea9e80630fd36ee3c6', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.027, 'ICIR': 0.138, 'Rank IC': 0.022, 'Rank ICIR': 0.132}, 'data_train_vec': ['2022-09-17', '2025-09-16'], 'train_time_vec': ['2026-09-17', '2026-09-17'], 'rank_icir': '0.132', 'weight': '0.057'}

	Recorder: 99c700bea4ef4001b7ee8441731b33c7

		Model: {'id': '99c700bea4ef4001b7ee8441731b33c7', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.007, 'ICIR': 0.029, 'Rank IC': 0.003, 'Rank ICIR': 0.017}, 'data_train_vec': ['2023-09-17', '2025-12-16'], 'train_time_vec': ['2026-09-17', '2026-09-17'], 'rank_icir': '0.017', 'weight': '0.007'}

	Recorder: b0751b57163840258f77189546b18a41

		Model: {'id': 'b0751b57163840258f77189546b18a41', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.076, 'ICIR': 0.281, 'Rank IC': 0.05, 'Rank ICIR': 0.217}, 'data_train_vec': ['2024-09-17', '2026-03-16'], 'train_time_vec': ['2026-09-17', '2026-09-17'], 'rank_icir': '0.217', 'weight': '0.093'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260917_16 845214722666107823 (Recorders: 1/5)

	Recorder: 73225e85df744c89aabd25ad4a4e0808

		Model: {'id': '73225e85df744c89aabd25ad4a4e0808', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.036, 'ICIR': 0.133, 'Rank IC': 0.017, 'Rank ICIR': 0.087}, 'data_train_vec': ['2024-09-17', '2026-03-16'], 'train_time_vec': ['2026-09-17', '2026-09-17'], 'rank_icir': '0.087', 'weight': '0.037'}
