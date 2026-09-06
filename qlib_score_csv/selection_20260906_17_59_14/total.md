# params 
 {'predict_dates': [{'start': '2026-09-04', 'end': '2026-09-04'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260906_17 101319811841029970 (Recorders: 3/5)

	Recorder: cd52f2642f30433bb247f13cbfb01917

		Model: {'id': 'cd52f2642f30433bb247f13cbfb01917', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.004, 'ICIR': 0.025, 'Rank IC': 0.019, 'Rank ICIR': 0.108}, 'data_train_vec': ['2021-09-06', '2025-06-05'], 'train_time_vec': ['2026-09-06', '2026-09-06'], 'rank_icir': '0.108', 'weight': '0.045'}

	Recorder: b0db9e02cb73417b842eebee639234ab

		Model: {'id': 'b0db9e02cb73417b842eebee639234ab', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.004, 'ICIR': 0.024, 'Rank IC': 0.036, 'Rank ICIR': 0.28}, 'data_train_vec': ['2022-09-06', '2025-09-05'], 'train_time_vec': ['2026-09-06', '2026-09-06'], 'rank_icir': '0.280', 'weight': '0.118'}

	Recorder: 87a5385f7e8847758e154b5aa0dd4fed

		Model: {'id': '87a5385f7e8847758e154b5aa0dd4fed', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.012, 'ICIR': 0.043, 'Rank IC': 0.022, 'Rank ICIR': 0.138}, 'data_train_vec': ['2023-09-06', '2025-12-05'], 'train_time_vec': ['2026-09-06', '2026-09-06'], 'rank_icir': '0.138', 'weight': '0.058'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260906_17 178841581379971801 (Recorders: 3/5)

	Recorder: 356e91d0d3c64fad96309497f41e4965

		Model: {'id': '356e91d0d3c64fad96309497f41e4965', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.011, 'ICIR': 0.076, 'Rank IC': 0.018, 'Rank ICIR': 0.129}, 'data_train_vec': ['2021-09-06', '2025-06-05'], 'train_time_vec': ['2026-09-06', '2026-09-06'], 'rank_icir': '0.129', 'weight': '0.054'}

	Recorder: 2a2b86f98e64453f9bd1708bd1d90a68

		Model: {'id': '2a2b86f98e64453f9bd1708bd1d90a68', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.022, 'ICIR': 0.156, 'Rank IC': 0.033, 'Rank ICIR': 0.257}, 'data_train_vec': ['2022-09-06', '2025-09-05'], 'train_time_vec': ['2026-09-06', '2026-09-06'], 'rank_icir': '0.257', 'weight': '0.108'}

	Recorder: 55af503fbb7347c499497b0bf30c6d89

		Model: {'id': '55af503fbb7347c499497b0bf30c6d89', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.01, 'ICIR': 0.05, 'Rank IC': 0.011, 'Rank ICIR': 0.066}, 'data_train_vec': ['2023-09-06', '2025-12-05'], 'train_time_vec': ['2026-09-06', '2026-09-06'], 'rank_icir': '0.066', 'weight': '0.028'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260906_15 124800479231178077 (Recorders: 3/5)

	Recorder: 5ff00ebb9eac44d9a97ca298a15456a6

		Model: {'id': '5ff00ebb9eac44d9a97ca298a15456a6', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.019, 'ICIR': 0.098, 'Rank IC': 0.033, 'Rank ICIR': 0.198}, 'data_train_vec': ['2021-09-06', '2025-06-05'], 'train_time_vec': ['2026-09-06', '2026-09-06'], 'rank_icir': '0.198', 'weight': '0.083'}

	Recorder: 42cfb1f6b5744ea7b0e4fd393808e59b

		Model: {'id': '42cfb1f6b5744ea7b0e4fd393808e59b', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.033, 'ICIR': 0.164, 'Rank IC': 0.044, 'Rank ICIR': 0.281}, 'data_train_vec': ['2022-09-06', '2025-09-05'], 'train_time_vec': ['2026-09-06', '2026-09-06'], 'rank_icir': '0.281', 'weight': '0.118'}

	Recorder: 9b72c7334ca64d5bb6bce1388994ccbc

		Model: {'id': '9b72c7334ca64d5bb6bce1388994ccbc', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.005, 'ICIR': 0.02, 'Rank IC': 0.009, 'Rank ICIR': 0.046}, 'data_train_vec': ['2023-09-06', '2025-12-05'], 'train_time_vec': ['2026-09-06', '2026-09-06'], 'rank_icir': '0.046', 'weight': '0.019'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260906_15 560481026216337007 (Recorders: 3/5)

	Recorder: 71d2a84f40f0418d906ab6a44a284f31

		Model: {'id': '71d2a84f40f0418d906ab6a44a284f31', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.016, 'ICIR': 0.079, 'Rank IC': 0.026, 'Rank ICIR': 0.155}, 'data_train_vec': ['2021-09-06', '2025-06-05'], 'train_time_vec': ['2026-09-06', '2026-09-06'], 'rank_icir': '0.155', 'weight': '0.065'}

	Recorder: 61454ba6b1e9425d990eb8bc18a259db

		Model: {'id': '61454ba6b1e9425d990eb8bc18a259db', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.042, 'ICIR': 0.232, 'Rank IC': 0.04, 'Rank ICIR': 0.261}, 'data_train_vec': ['2022-09-06', '2025-09-05'], 'train_time_vec': ['2026-09-06', '2026-09-06'], 'rank_icir': '0.261', 'weight': '0.110'}

	Recorder: 8e24573f08c4489593b3599aba88c4fb

		Model: {'id': '8e24573f08c4489593b3599aba88c4fb', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.019, 'ICIR': 0.09, 'Rank IC': 0.013, 'Rank ICIR': 0.061}, 'data_train_vec': ['2025-09-06', '2026-06-05'], 'train_time_vec': ['2026-09-06', '2026-09-06'], 'rank_icir': '0.061', 'weight': '0.026'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260906_15 218519172044356778 (Recorders: 2/5)

	Recorder: 42a84ff4701444e09153e67b68e94456

		Model: {'id': '42a84ff4701444e09153e67b68e94456', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.006, 'ICIR': 0.028, 'Rank IC': 0.028, 'Rank ICIR': 0.165}, 'data_train_vec': ['2021-09-06', '2025-06-05'], 'train_time_vec': ['2026-09-06', '2026-09-06'], 'rank_icir': '0.165', 'weight': '0.069'}

	Recorder: 05670008d31b425485a394a1cffbed0d

		Model: {'id': '05670008d31b425485a394a1cffbed0d', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.014, 'ICIR': 0.064, 'Rank IC': 0.035, 'Rank ICIR': 0.231}, 'data_train_vec': ['2022-09-06', '2025-09-05'], 'train_time_vec': ['2026-09-06', '2026-09-06'], 'rank_icir': '0.231', 'weight': '0.097'}
