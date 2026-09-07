# params 
 {'predict_dates': [{'start': '2026-09-04', 'end': '2026-09-04'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260907_20 375016824592227224 (Recorders: 2/5)

	Recorder: 0b9b626ceb204091ab3b227c21268902

		Model: {'id': '0b9b626ceb204091ab3b227c21268902', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.005, 'ICIR': 0.022, 'Rank IC': 0.036, 'Rank ICIR': 0.245}, 'data_train_vec': ['2022-09-07', '2025-09-06'], 'train_time_vec': ['2026-09-07', '2026-09-07'], 'rank_icir': '0.245', 'weight': '0.127'}

	Recorder: fb2757ff53bf453f863f2cde530f8e60

		Model: {'id': 'fb2757ff53bf453f863f2cde530f8e60', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.003, 'ICIR': 0.012, 'Rank IC': 0.007, 'Rank ICIR': 0.039}, 'data_train_vec': ['2023-09-07', '2025-12-06'], 'train_time_vec': ['2026-09-07', '2026-09-07'], 'rank_icir': '0.039', 'weight': '0.020'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260907_19 404396166749836041 (Recorders: 3/5)

	Recorder: 4290257aac454db1866b328ff1a69c43

		Model: {'id': '4290257aac454db1866b328ff1a69c43', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.009, 'ICIR': 0.06, 'Rank IC': 0.016, 'Rank ICIR': 0.118}, 'data_train_vec': ['2021-09-07', '2025-06-06'], 'train_time_vec': ['2026-09-07', '2026-09-07'], 'rank_icir': '0.118', 'weight': '0.061'}

	Recorder: e6610da94e84471997d39ecacdab9173

		Model: {'id': 'e6610da94e84471997d39ecacdab9173', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.017, 'ICIR': 0.115, 'Rank IC': 0.028, 'Rank ICIR': 0.222}, 'data_train_vec': ['2022-09-07', '2025-09-06'], 'train_time_vec': ['2026-09-07', '2026-09-07'], 'rank_icir': '0.222', 'weight': '0.115'}

	Recorder: c6a7d4255216490fa0409d6921d85a86

		Model: {'id': 'c6a7d4255216490fa0409d6921d85a86', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.011, 'ICIR': 0.054, 'Rank IC': 0.013, 'Rank ICIR': 0.078}, 'data_train_vec': ['2023-09-07', '2025-12-06'], 'train_time_vec': ['2026-09-07', '2026-09-07'], 'rank_icir': '0.078', 'weight': '0.040'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260907_17 803382509704750679 (Recorders: 2/5)

	Recorder: 0e25499d8187498dabdb4a9c5e7cf19b

		Model: {'id': '0e25499d8187498dabdb4a9c5e7cf19b', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.016, 'ICIR': 0.082, 'Rank IC': 0.029, 'Rank ICIR': 0.177}, 'data_train_vec': ['2021-09-07', '2025-06-06'], 'train_time_vec': ['2026-09-07', '2026-09-07'], 'rank_icir': '0.177', 'weight': '0.092'}

	Recorder: bef9f51745064a338626ae41148c3cba

		Model: {'id': 'bef9f51745064a338626ae41148c3cba', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.034, 'ICIR': 0.165, 'Rank IC': 0.043, 'Rank ICIR': 0.273}, 'data_train_vec': ['2022-09-07', '2025-09-06'], 'train_time_vec': ['2026-09-07', '2026-09-07'], 'rank_icir': '0.273', 'weight': '0.142'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260907_17 479245401248543239 (Recorders: 3/5)

	Recorder: 206ea5524af247c4a3edcc2a60b9b471

		Model: {'id': '206ea5524af247c4a3edcc2a60b9b471', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.016, 'ICIR': 0.079, 'Rank IC': 0.025, 'Rank ICIR': 0.153}, 'data_train_vec': ['2021-09-07', '2025-06-06'], 'train_time_vec': ['2026-09-07', '2026-09-07'], 'rank_icir': '0.153', 'weight': '0.079'}

	Recorder: 0265175537dc495394bfc7b79dc23e93

		Model: {'id': '0265175537dc495394bfc7b79dc23e93', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.04, 'ICIR': 0.217, 'Rank IC': 0.038, 'Rank ICIR': 0.245}, 'data_train_vec': ['2022-09-07', '2025-09-06'], 'train_time_vec': ['2026-09-07', '2026-09-07'], 'rank_icir': '0.245', 'weight': '0.127'}

	Recorder: 793d54f3d81c4b578c6df229c1089136

		Model: {'id': '793d54f3d81c4b578c6df229c1089136', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.032, 'ICIR': 0.152, 'Rank IC': 0.021, 'Rank ICIR': 0.1}, 'data_train_vec': ['2025-09-07', '2026-06-06'], 'train_time_vec': ['2026-09-07', '2026-09-07'], 'rank_icir': '0.100', 'weight': '0.052'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260907_17 211451658920289383 (Recorders: 1/5)

	Recorder: b8f46d533053460193ceb619d36351c2

		Model: {'id': 'b8f46d533053460193ceb619d36351c2', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.017, 'ICIR': 0.081, 'Rank IC': 0.042, 'Rank ICIR': 0.276}, 'data_train_vec': ['2022-09-07', '2025-09-06'], 'train_time_vec': ['2026-09-07', '2026-09-07'], 'rank_icir': '0.276', 'weight': '0.143'}
