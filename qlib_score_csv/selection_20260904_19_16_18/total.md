# params 
 {'predict_dates': [{'start': '2026-09-04', 'end': '2026-09-04'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260904_18 958197021460725975 (Recorders: 3/5)

	Recorder: ba056bc712364e549b61d3e76ea38506

		Model: {'id': 'ba056bc712364e549b61d3e76ea38506', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.017, 'ICIR': 0.116, 'Rank IC': 0.033, 'Rank ICIR': 0.238}, 'data_train_vec': ['2021-09-04', '2025-06-03'], 'train_time_vec': ['2026-09-04', '2026-09-04'], 'rank_icir': '0.238', 'weight': '0.102'}

	Recorder: f14b3a546730469c9ef958e7f0e42b54

		Model: {'id': 'f14b3a546730469c9ef958e7f0e42b54', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.008, 'ICIR': 0.041, 'Rank IC': 0.027, 'Rank ICIR': 0.196}, 'data_train_vec': ['2022-09-04', '2025-09-03'], 'train_time_vec': ['2026-09-04', '2026-09-04'], 'rank_icir': '0.196', 'weight': '0.084'}

	Recorder: d942cd6b81104d49a1848002ca63d140

		Model: {'id': 'd942cd6b81104d49a1848002ca63d140', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.022, 'ICIR': 0.083, 'Rank IC': 0.015, 'Rank ICIR': 0.093}, 'data_train_vec': ['2023-09-04', '2025-12-03'], 'train_time_vec': ['2026-09-04', '2026-09-04'], 'rank_icir': '0.093', 'weight': '0.040'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260904_18 117380897650216944 (Recorders: 3/5)

	Recorder: d0da4aafa29547b48e9405d422c1d495

		Model: {'id': 'd0da4aafa29547b48e9405d422c1d495', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.012, 'ICIR': 0.082, 'Rank IC': 0.016, 'Rank ICIR': 0.109}, 'data_train_vec': ['2021-09-04', '2025-06-03'], 'train_time_vec': ['2026-09-04', '2026-09-04'], 'rank_icir': '0.109', 'weight': '0.047'}

	Recorder: e2edb0f889224c6899d0e5766963039a

		Model: {'id': 'e2edb0f889224c6899d0e5766963039a', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.023, 'ICIR': 0.238, 'Rank IC': 0.03, 'Rank ICIR': 0.303}, 'data_train_vec': ['2022-09-04', '2025-09-03'], 'train_time_vec': ['2026-09-04', '2026-09-04'], 'rank_icir': '0.303', 'weight': '0.129'}

	Recorder: b414b1611ab54fca9df3673c48a46830

		Model: {'id': 'b414b1611ab54fca9df3673c48a46830', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.018, 'ICIR': 0.097, 'Rank IC': 0.017, 'Rank ICIR': 0.107}, 'data_train_vec': ['2023-09-04', '2025-12-03'], 'train_time_vec': ['2026-09-04', '2026-09-04'], 'rank_icir': '0.107', 'weight': '0.046'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260904_16 509235475322077772 (Recorders: 3/5)

	Recorder: 6dcd95bbe94d4d3194a51d77f49f1cef

		Model: {'id': '6dcd95bbe94d4d3194a51d77f49f1cef', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.018, 'ICIR': 0.089, 'Rank IC': 0.03, 'Rank ICIR': 0.179}, 'data_train_vec': ['2021-09-04', '2025-06-03'], 'train_time_vec': ['2026-09-04', '2026-09-04'], 'rank_icir': '0.179', 'weight': '0.076'}

	Recorder: a11ac279507d44a6963238394bd57dc6

		Model: {'id': 'a11ac279507d44a6963238394bd57dc6', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.033, 'ICIR': 0.157, 'Rank IC': 0.043, 'Rank ICIR': 0.26}, 'data_train_vec': ['2022-09-04', '2025-09-03'], 'train_time_vec': ['2026-09-04', '2026-09-04'], 'rank_icir': '0.260', 'weight': '0.111'}

	Recorder: c6b3242315b94058ab729f374b909914

		Model: {'id': 'c6b3242315b94058ab729f374b909914', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.006, 'ICIR': 0.022, 'Rank IC': 0.009, 'Rank ICIR': 0.048}, 'data_train_vec': ['2023-09-04', '2025-12-03'], 'train_time_vec': ['2026-09-04', '2026-09-04'], 'rank_icir': '0.048', 'weight': '0.020'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260904_16 879608642958514285 (Recorders: 3/5)

	Recorder: 9ecefa36015c453183a3f97c512bcd27

		Model: {'id': '9ecefa36015c453183a3f97c512bcd27', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.017, 'ICIR': 0.082, 'Rank IC': 0.026, 'Rank ICIR': 0.156}, 'data_train_vec': ['2021-09-04', '2025-06-03'], 'train_time_vec': ['2026-09-04', '2026-09-04'], 'rank_icir': '0.156', 'weight': '0.067'}

	Recorder: 29e7ab4104b84a3baa106572d77f86eb

		Model: {'id': '29e7ab4104b84a3baa106572d77f86eb', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.04, 'ICIR': 0.213, 'Rank IC': 0.038, 'Rank ICIR': 0.242}, 'data_train_vec': ['2022-09-04', '2025-09-03'], 'train_time_vec': ['2026-09-04', '2026-09-04'], 'rank_icir': '0.242', 'weight': '0.103'}

	Recorder: d4c9b46d907b4b159ff8f2a5832e1343

		Model: {'id': 'd4c9b46d907b4b159ff8f2a5832e1343', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.049, 'ICIR': 0.224, 'Rank IC': 0.035, 'Rank ICIR': 0.175}, 'data_train_vec': ['2025-09-04', '2026-06-03'], 'train_time_vec': ['2026-09-04', '2026-09-04'], 'rank_icir': '0.175', 'weight': '0.075'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260904_16 845343247927383808 (Recorders: 1/5)

	Recorder: 84f10bc05b4341ceb78367a5e7cbdb88

		Model: {'id': '84f10bc05b4341ceb78367a5e7cbdb88', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.013, 'ICIR': 0.055, 'Rank IC': 0.036, 'Rank ICIR': 0.237}, 'data_train_vec': ['2022-09-04', '2025-09-03'], 'train_time_vec': ['2026-09-04', '2026-09-04'], 'rank_icir': '0.237', 'weight': '0.101'}
