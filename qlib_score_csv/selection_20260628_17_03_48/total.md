# params 
 {'predict_dates': [{'start': '2026-06-26', 'end': '2026-06-26'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260628_16 937732937880092736 (Recorders: 2/5)

	Recorder: 0da4cbd757ed4df194af8e5b05d30ce7

		Model: {'id': '0da4cbd757ed4df194af8e5b05d30ce7', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.031, 'ICIR': 0.236, 'Rank IC': 0.035, 'Rank ICIR': 0.25}, 'data_train_vec': ['2023-06-28', '2025-09-27'], 'train_time_vec': ['2026-06-28', '2026-06-28'], 'rank_icir': '0.250', 'weight': '0.110'}

	Recorder: ef8e50295ed7439aba239db4b319e328

		Model: {'id': 'ef8e50295ed7439aba239db4b319e328', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.029, 'ICIR': 0.281, 'Rank IC': 0.018, 'Rank ICIR': 0.204}, 'data_train_vec': ['2024-06-28', '2025-12-27'], 'train_time_vec': ['2026-06-28', '2026-06-28'], 'rank_icir': '0.204', 'weight': '0.090'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260628_16 103781612125211641 (Recorders: 3/5)

	Recorder: 0f902c853ebe486ea429f44a8497e547

		Model: {'id': '0f902c853ebe486ea429f44a8497e547', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.018, 'ICIR': 0.181, 'Rank IC': 0.025, 'Rank ICIR': 0.205}, 'data_train_vec': ['2023-06-28', '2025-09-27'], 'train_time_vec': ['2026-06-28', '2026-06-28'], 'rank_icir': '0.205', 'weight': '0.090'}

	Recorder: d633ca67e25949a2b96b8370b54f7662

		Model: {'id': 'd633ca67e25949a2b96b8370b54f7662', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.035, 'ICIR': 0.241, 'Rank IC': 0.032, 'Rank ICIR': 0.25}, 'data_train_vec': ['2024-06-28', '2025-12-27'], 'train_time_vec': ['2026-06-28', '2026-06-28'], 'rank_icir': '0.250', 'weight': '0.110'}

	Recorder: 58f8e47e710b44c7b1791e864c151876

		Model: {'id': '58f8e47e710b44c7b1791e864c151876', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.055, 'ICIR': 0.217, 'Rank IC': 0.028, 'Rank ICIR': 0.126}, 'data_train_vec': ['2025-06-28', '2026-03-27'], 'train_time_vec': ['2026-06-28', '2026-06-28'], 'rank_icir': '0.126', 'weight': '0.055'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260628_14 711009566927029547 (Recorders: 3/5)

	Recorder: f6c266e20f96446c818ef10fb30b1200

		Model: {'id': 'f6c266e20f96446c818ef10fb30b1200', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.009, 'ICIR': 0.055, 'Rank IC': 0.042, 'Rank ICIR': 0.245}, 'data_train_vec': ['2021-06-28', '2025-03-27'], 'train_time_vec': ['2026-06-28', '2026-06-28'], 'rank_icir': '0.245', 'weight': '0.108'}

	Recorder: 49b86274fea840348d41b65811bf3cf0

		Model: {'id': '49b86274fea840348d41b65811bf3cf0', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.016, 'ICIR': 0.101, 'Rank IC': 0.042, 'Rank ICIR': 0.255}, 'data_train_vec': ['2022-06-28', '2025-06-27'], 'train_time_vec': ['2026-06-28', '2026-06-28'], 'rank_icir': '0.255', 'weight': '0.112'}

	Recorder: fc49960721724b7da5707984bffb0fb1

		Model: {'id': 'fc49960721724b7da5707984bffb0fb1', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.023, 'ICIR': 0.175, 'Rank IC': 0.031, 'Rank ICIR': 0.247}, 'data_train_vec': ['2023-06-28', '2025-09-27'], 'train_time_vec': ['2026-06-28', '2026-06-28'], 'rank_icir': '0.247', 'weight': '0.108'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260628_14 404117063185316589 (Recorders: 1/5)

	Recorder: 61111c53633147f685393e2d379ccb52

		Model: {'id': '61111c53633147f685393e2d379ccb52', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.002, 'ICIR': 0.014, 'Rank IC': 0.019, 'Rank ICIR': 0.144}, 'data_train_vec': ['2023-06-28', '2025-09-27'], 'train_time_vec': ['2026-06-28', '2026-06-28'], 'rank_icir': '0.144', 'weight': '0.063'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260628_14 157880800238009317 (Recorders: 2/5)

	Recorder: 7dc9db18f1f8433e9cbf68ab13645795

		Model: {'id': '7dc9db18f1f8433e9cbf68ab13645795', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.003, 'ICIR': 0.023, 'Rank IC': 0.037, 'Rank ICIR': 0.217}, 'data_train_vec': ['2022-06-28', '2025-06-27'], 'train_time_vec': ['2026-06-28', '2026-06-28'], 'rank_icir': '0.217', 'weight': '0.095'}

	Recorder: b46d59e3adfb419aa4dbb531e78512bf

		Model: {'id': 'b46d59e3adfb419aa4dbb531e78512bf', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.005, 'ICIR': 0.044, 'Rank IC': 0.018, 'Rank ICIR': 0.135}, 'data_train_vec': ['2023-06-28', '2025-09-27'], 'train_time_vec': ['2026-06-28', '2026-06-28'], 'rank_icir': '0.135', 'weight': '0.059'}
