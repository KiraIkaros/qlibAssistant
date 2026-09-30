# params 
 {'predict_dates': [{'start': '2026-09-30', 'end': '2026-09-30'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260930_20 267575908586205608 (Recorders: 5/5)

	Recorder: 18fa191df26940d5a957e323ea9a1dd8

		Model: {'id': '18fa191df26940d5a957e323ea9a1dd8', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.015, 'ICIR': 0.105, 'Rank IC': 0.03, 'Rank ICIR': 0.196}, 'data_train_vec': ['2021-09-30', '2025-06-29'], 'train_time_vec': ['2026-09-30', '2026-09-30'], 'rank_icir': '0.196', 'weight': '0.070'}

	Recorder: 90702860a69f435894c9ea460cfde38b

		Model: {'id': '90702860a69f435894c9ea460cfde38b', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.025, 'ICIR': 0.095, 'Rank IC': 0.034, 'Rank ICIR': 0.163}, 'data_train_vec': ['2022-09-30', '2025-09-29'], 'train_time_vec': ['2026-09-30', '2026-09-30'], 'rank_icir': '0.163', 'weight': '0.059'}

	Recorder: 8cb3e29fc3134190bb00a27fae019ddb

		Model: {'id': '8cb3e29fc3134190bb00a27fae019ddb', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.011, 'ICIR': 0.035, 'Rank IC': 0.014, 'Rank ICIR': 0.07}, 'data_train_vec': ['2023-09-30', '2025-12-29'], 'train_time_vec': ['2026-09-30', '2026-09-30'], 'rank_icir': '0.070', 'weight': '0.025'}

	Recorder: c38892adf3f949f18f3dc072a5a13240

		Model: {'id': 'c38892adf3f949f18f3dc072a5a13240', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.038, 'ICIR': 0.254, 'Rank IC': 0.014, 'Rank ICIR': 0.114}, 'data_train_vec': ['2024-09-30', '2026-03-29'], 'train_time_vec': ['2026-09-30', '2026-09-30'], 'rank_icir': '0.114', 'weight': '0.041'}

	Recorder: 9a4d01022dc94ff6a25a0c7d4ab965b6

		Model: {'id': '9a4d01022dc94ff6a25a0c7d4ab965b6', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.017, 'ICIR': 0.194, 'Rank IC': 0.012, 'Rank ICIR': 0.117}, 'data_train_vec': ['2025-09-30', '2026-06-29'], 'train_time_vec': ['2026-09-30', '2026-09-30'], 'rank_icir': '0.117', 'weight': '0.042'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260930_20 349370758386976719 (Recorders: 5/5)

	Recorder: 91dd412b6770417c8a53ee85a24dd022

		Model: {'id': '91dd412b6770417c8a53ee85a24dd022', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.035, 'ICIR': 0.225, 'Rank IC': 0.042, 'Rank ICIR': 0.245}, 'data_train_vec': ['2021-09-30', '2025-06-29'], 'train_time_vec': ['2026-09-30', '2026-09-30'], 'rank_icir': '0.245', 'weight': '0.088'}

	Recorder: 26a32a1ac03e45889fec82ae66d368f4

		Model: {'id': '26a32a1ac03e45889fec82ae66d368f4', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.032, 'ICIR': 0.165, 'Rank IC': 0.035, 'Rank ICIR': 0.2}, 'data_train_vec': ['2022-09-30', '2025-09-29'], 'train_time_vec': ['2026-09-30', '2026-09-30'], 'rank_icir': '0.200', 'weight': '0.072'}

	Recorder: c0527dbe343c45298d45c989c573a61d

		Model: {'id': 'c0527dbe343c45298d45c989c573a61d', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.013, 'ICIR': 0.057, 'Rank IC': 0.017, 'Rank ICIR': 0.084}, 'data_train_vec': ['2023-09-30', '2025-12-29'], 'train_time_vec': ['2026-09-30', '2026-09-30'], 'rank_icir': '0.084', 'weight': '0.030'}

	Recorder: 1aab3e5f3445480b980166cf334ac560

		Model: {'id': '1aab3e5f3445480b980166cf334ac560', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.005, 'ICIR': 0.04, 'Rank IC': 0.008, 'Rank ICIR': 0.054}, 'data_train_vec': ['2024-09-30', '2026-03-29'], 'train_time_vec': ['2026-09-30', '2026-09-30'], 'rank_icir': '0.054', 'weight': '0.019'}

	Recorder: b9319120577740a19a66e9ec6fc09edb

		Model: {'id': 'b9319120577740a19a66e9ec6fc09edb', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.005, 'ICIR': 0.043, 'Rank IC': 0.005, 'Rank ICIR': 0.049}, 'data_train_vec': ['2025-09-30', '2026-06-29'], 'train_time_vec': ['2026-09-30', '2026-09-30'], 'rank_icir': '0.049', 'weight': '0.018'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260930_18 132608678865580827 (Recorders: 3/5)

	Recorder: a41ed2a0321441b2a51e7de0846d8bee

		Model: {'id': 'a41ed2a0321441b2a51e7de0846d8bee', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.036, 'ICIR': 0.179, 'Rank IC': 0.048, 'Rank ICIR': 0.279}, 'data_train_vec': ['2021-09-30', '2025-06-29'], 'train_time_vec': ['2026-09-30', '2026-09-30'], 'rank_icir': '0.279', 'weight': '0.100'}

	Recorder: 1da7f43bf52542cc8d55822ddd611faa

		Model: {'id': '1da7f43bf52542cc8d55822ddd611faa', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.026, 'ICIR': 0.112, 'Rank IC': 0.03, 'Rank ICIR': 0.157}, 'data_train_vec': ['2022-09-30', '2025-09-29'], 'train_time_vec': ['2026-09-30', '2026-09-30'], 'rank_icir': '0.157', 'weight': '0.056'}

	Recorder: 68d7059d333b4aeca5176f25d4f37bb1

		Model: {'id': '68d7059d333b4aeca5176f25d4f37bb1', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.008, 'ICIR': 0.03, 'Rank IC': 0.01, 'Rank ICIR': 0.044}, 'data_train_vec': ['2023-09-30', '2025-12-29'], 'train_time_vec': ['2026-09-30', '2026-09-30'], 'rank_icir': '0.044', 'weight': '0.016'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260930_18 277489418431114736 (Recorders: 5/5)

	Recorder: 92d249f1f8384b32a4b76c30d5dc9c20

		Model: {'id': '92d249f1f8384b32a4b76c30d5dc9c20', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.037, 'ICIR': 0.182, 'Rank IC': 0.04, 'Rank ICIR': 0.227}, 'data_train_vec': ['2021-09-30', '2025-06-29'], 'train_time_vec': ['2026-09-30', '2026-09-30'], 'rank_icir': '0.227', 'weight': '0.082'}

	Recorder: 0404538829f545ceaa09658100775164

		Model: {'id': '0404538829f545ceaa09658100775164', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.032, 'ICIR': 0.144, 'Rank IC': 0.02, 'Rank ICIR': 0.108}, 'data_train_vec': ['2022-09-30', '2025-09-29'], 'train_time_vec': ['2026-09-30', '2026-09-30'], 'rank_icir': '0.108', 'weight': '0.039'}

	Recorder: 7ec5a9b2dd414282ad0cfc058080493e

		Model: {'id': '7ec5a9b2dd414282ad0cfc058080493e', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.008, 'ICIR': 0.031, 'Rank IC': 0.003, 'Rank ICIR': 0.014}, 'data_train_vec': ['2023-09-30', '2025-12-29'], 'train_time_vec': ['2026-09-30', '2026-09-30'], 'rank_icir': '0.014', 'weight': '0.005'}

	Recorder: 53c4915e6c5741a390779162abfb5910

		Model: {'id': '53c4915e6c5741a390779162abfb5910', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.054, 'ICIR': 0.244, 'Rank IC': 0.029, 'Rank ICIR': 0.159}, 'data_train_vec': ['2024-09-30', '2026-03-29'], 'train_time_vec': ['2026-09-30', '2026-09-30'], 'rank_icir': '0.159', 'weight': '0.057'}

	Recorder: d982616fc7c94ebaba6d86288339fe41

		Model: {'id': 'd982616fc7c94ebaba6d86288339fe41', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.014, 'ICIR': 0.09, 'Rank IC': 0.01, 'Rank ICIR': 0.07}, 'data_train_vec': ['2025-09-30', '2026-06-29'], 'train_time_vec': ['2026-09-30', '2026-09-30'], 'rank_icir': '0.070', 'weight': '0.025'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260930_17 504937861369371108 (Recorders: 2/5)

	Recorder: 8b54156704fa4aafb263fa21f07ad524

		Model: {'id': '8b54156704fa4aafb263fa21f07ad524', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.005, 'ICIR': 0.023, 'Rank IC': 0.043, 'Rank ICIR': 0.26}, 'data_train_vec': ['2021-09-30', '2025-06-29'], 'train_time_vec': ['2026-09-30', '2026-09-30'], 'rank_icir': '0.260', 'weight': '0.093'}

	Recorder: 645058b7bac647d7886c4c471bb05f8e

		Model: {'id': '645058b7bac647d7886c4c471bb05f8e', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.046, 'ICIR': 0.225, 'Rank IC': 0.025, 'Rank ICIR': 0.175}, 'data_train_vec': ['2024-09-30', '2026-03-29'], 'train_time_vec': ['2026-09-30', '2026-09-30'], 'rank_icir': '0.175', 'weight': '0.063'}
