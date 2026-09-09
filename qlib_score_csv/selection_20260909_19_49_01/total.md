# params 
 {'predict_dates': [{'start': '2026-09-09', 'end': '2026-09-09'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260909_19 303030469570103196 (Recorders: 2/5)

	Recorder: aa0a81966d684b9eb81cd9f0d9caf8cd

		Model: {'id': 'aa0a81966d684b9eb81cd9f0d9caf8cd', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.021, 'ICIR': 0.093, 'Rank IC': 0.038, 'Rank ICIR': 0.239}, 'data_train_vec': ['2022-09-09', '2025-09-08'], 'train_time_vec': ['2026-09-09', '2026-09-09'], 'rank_icir': '0.239', 'weight': '0.106'}

	Recorder: 7d8b2653b130452eab557f998925b87b

		Model: {'id': '7d8b2653b130452eab557f998925b87b', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.016, 'ICIR': 0.056, 'Rank IC': 0.014, 'Rank ICIR': 0.08}, 'data_train_vec': ['2023-09-09', '2025-12-08'], 'train_time_vec': ['2026-09-09', '2026-09-09'], 'rank_icir': '0.080', 'weight': '0.035'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260909_19 163217118878587499 (Recorders: 3/5)

	Recorder: 48f8b6eb62ee4320ab0f9efe17b2837a

		Model: {'id': '48f8b6eb62ee4320ab0f9efe17b2837a', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.014, 'ICIR': 0.099, 'Rank IC': 0.027, 'Rank ICIR': 0.175}, 'data_train_vec': ['2021-09-09', '2025-06-08'], 'train_time_vec': ['2026-09-09', '2026-09-09'], 'rank_icir': '0.175', 'weight': '0.077'}

	Recorder: a73a564080d04aac82e7db2061eb8a8b

		Model: {'id': 'a73a564080d04aac82e7db2061eb8a8b', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.022, 'ICIR': 0.156, 'Rank IC': 0.033, 'Rank ICIR': 0.259}, 'data_train_vec': ['2022-09-09', '2025-09-08'], 'train_time_vec': ['2026-09-09', '2026-09-09'], 'rank_icir': '0.259', 'weight': '0.115'}

	Recorder: 42b43b8fc6a547ce9d34276d152aa5b7

		Model: {'id': '42b43b8fc6a547ce9d34276d152aa5b7', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.006, 'ICIR': 0.039, 'Rank IC': 0.007, 'Rank ICIR': 0.044}, 'data_train_vec': ['2023-09-09', '2025-12-08'], 'train_time_vec': ['2026-09-09', '2026-09-09'], 'rank_icir': '0.044', 'weight': '0.019'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260909_16 959843828438504604 (Recorders: 3/5)

	Recorder: 3dc8855e88e5490fa2021d1f1848e9d6

		Model: {'id': '3dc8855e88e5490fa2021d1f1848e9d6', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.018, 'ICIR': 0.091, 'Rank IC': 0.033, 'Rank ICIR': 0.194}, 'data_train_vec': ['2021-09-09', '2025-06-08'], 'train_time_vec': ['2026-09-09', '2026-09-09'], 'rank_icir': '0.194', 'weight': '0.086'}

	Recorder: 2b83175416d44fc681e4244773882493

		Model: {'id': '2b83175416d44fc681e4244773882493', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.026, 'ICIR': 0.125, 'Rank IC': 0.036, 'Rank ICIR': 0.223}, 'data_train_vec': ['2022-09-09', '2025-09-08'], 'train_time_vec': ['2026-09-09', '2026-09-09'], 'rank_icir': '0.223', 'weight': '0.099'}

	Recorder: 8efa34e3ac23469d95298ada901b9b30

		Model: {'id': '8efa34e3ac23469d95298ada901b9b30', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.004, 'ICIR': 0.017, 'Rank IC': 0.005, 'Rank ICIR': 0.027}, 'data_train_vec': ['2023-09-09', '2025-12-08'], 'train_time_vec': ['2026-09-09', '2026-09-09'], 'rank_icir': '0.027', 'weight': '0.012'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260909_16 969097811433455539 (Recorders: 4/5)

	Recorder: ddf55fac8af64c088bbe397ce168359f

		Model: {'id': 'ddf55fac8af64c088bbe397ce168359f', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.022, 'ICIR': 0.106, 'Rank IC': 0.028, 'Rank ICIR': 0.173}, 'data_train_vec': ['2021-09-09', '2025-06-08'], 'train_time_vec': ['2026-09-09', '2026-09-09'], 'rank_icir': '0.173', 'weight': '0.077'}

	Recorder: 0f6fd869af2b4ab6b135086a7035b672

		Model: {'id': '0f6fd869af2b4ab6b135086a7035b672', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.039, 'ICIR': 0.205, 'Rank IC': 0.034, 'Rank ICIR': 0.216}, 'data_train_vec': ['2022-09-09', '2025-09-08'], 'train_time_vec': ['2026-09-09', '2026-09-09'], 'rank_icir': '0.216', 'weight': '0.096'}

	Recorder: f335acb8e3f147cea4f154f84ab62140

		Model: {'id': 'f335acb8e3f147cea4f154f84ab62140', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.013, 'ICIR': 0.041, 'Rank IC': 0.002, 'Rank ICIR': 0.008}, 'data_train_vec': ['2024-09-09', '2026-03-08'], 'train_time_vec': ['2026-09-09', '2026-09-09'], 'rank_icir': '0.008', 'weight': '0.004'}

	Recorder: 839a04ba8ea743ed92dfb794377a2817

		Model: {'id': '839a04ba8ea743ed92dfb794377a2817', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.044, 'ICIR': 0.21, 'Rank IC': 0.03, 'Rank ICIR': 0.15}, 'data_train_vec': ['2025-09-09', '2026-06-08'], 'train_time_vec': ['2026-09-09', '2026-09-09'], 'rank_icir': '0.150', 'weight': '0.066'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260909_16 540520532234571259 (Recorders: 2/5)

	Recorder: 7e5e817575824c0790acf464a8dc2ebc

		Model: {'id': '7e5e817575824c0790acf464a8dc2ebc', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.004, 'ICIR': 0.019, 'Rank IC': 0.031, 'Rank ICIR': 0.185}, 'data_train_vec': ['2021-09-09', '2025-06-08'], 'train_time_vec': ['2026-09-09', '2026-09-09'], 'rank_icir': '0.185', 'weight': '0.082'}

	Recorder: 0bf95fbaea0d42c28858cbd28583d182

		Model: {'id': '0bf95fbaea0d42c28858cbd28583d182', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.013, 'ICIR': 0.059, 'Rank IC': 0.044, 'Rank ICIR': 0.286}, 'data_train_vec': ['2022-09-09', '2025-09-08'], 'train_time_vec': ['2026-09-09', '2026-09-09'], 'rank_icir': '0.286', 'weight': '0.127'}
