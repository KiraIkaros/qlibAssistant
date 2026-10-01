# params 
 {'predict_dates': [{'start': '2026-09-30', 'end': '2026-09-30'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20261001_20 290970142553594568 (Recorders: 3/5)

	Recorder: f691f8295a2d48728df8c5d71adb788a

		Model: {'id': 'f691f8295a2d48728df8c5d71adb788a', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.018, 'ICIR': 0.132, 'Rank IC': 0.034, 'Rank ICIR': 0.194}, 'data_train_vec': ['2021-10-01', '2025-06-30'], 'train_time_vec': ['2026-10-01', '2026-10-01'], 'rank_icir': '0.194', 'weight': '0.075'}

	Recorder: 17cc074ba4f94596ac63c3bdeeeafa4f

		Model: {'id': '17cc074ba4f94596ac63c3bdeeeafa4f', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.016, 'ICIR': 0.073, 'Rank IC': 0.029, 'Rank ICIR': 0.173}, 'data_train_vec': ['2022-10-01', '2025-09-30'], 'train_time_vec': ['2026-10-01', '2026-10-01'], 'rank_icir': '0.173', 'weight': '0.067'}

	Recorder: d2c242947a384e0a9d8432a950534829

		Model: {'id': 'd2c242947a384e0a9d8432a950534829', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.013, 'ICIR': 0.045, 'Rank IC': 0.019, 'Rank ICIR': 0.091}, 'data_train_vec': ['2023-10-01', '2025-12-31'], 'train_time_vec': ['2026-10-01', '2026-10-01'], 'rank_icir': '0.091', 'weight': '0.035'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20261001_20 597714036141412375 (Recorders: 3/5)

	Recorder: 4efc3642ebeb4b989c5b9f1de51346b1

		Model: {'id': '4efc3642ebeb4b989c5b9f1de51346b1', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.035, 'ICIR': 0.224, 'Rank IC': 0.046, 'Rank ICIR': 0.293}, 'data_train_vec': ['2021-10-01', '2025-06-30'], 'train_time_vec': ['2026-10-01', '2026-10-01'], 'rank_icir': '0.293', 'weight': '0.113'}

	Recorder: 234de275c25240099ec14ad53312a960

		Model: {'id': '234de275c25240099ec14ad53312a960', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.032, 'ICIR': 0.171, 'Rank IC': 0.038, 'Rank ICIR': 0.213}, 'data_train_vec': ['2022-10-01', '2025-09-30'], 'train_time_vec': ['2026-10-01', '2026-10-01'], 'rank_icir': '0.213', 'weight': '0.082'}

	Recorder: 9d17af96d3fa4051ae9ce64b1b90cd83

		Model: {'id': '9d17af96d3fa4051ae9ce64b1b90cd83', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.01, 'ICIR': 0.041, 'Rank IC': 0.013, 'Rank ICIR': 0.062}, 'data_train_vec': ['2023-10-01', '2025-12-31'], 'train_time_vec': ['2026-10-01', '2026-10-01'], 'rank_icir': '0.062', 'weight': '0.024'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20261001_18 974202682329852896 (Recorders: 3/5)

	Recorder: ec6f51d61d9f48828d787190a2bb34d7

		Model: {'id': 'ec6f51d61d9f48828d787190a2bb34d7', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.037, 'ICIR': 0.182, 'Rank IC': 0.048, 'Rank ICIR': 0.275}, 'data_train_vec': ['2021-10-01', '2025-06-30'], 'train_time_vec': ['2026-10-01', '2026-10-01'], 'rank_icir': '0.275', 'weight': '0.106'}

	Recorder: bcfbc80e95d54994845bc976d31d741e

		Model: {'id': 'bcfbc80e95d54994845bc976d31d741e', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.031, 'ICIR': 0.137, 'Rank IC': 0.03, 'Rank ICIR': 0.158}, 'data_train_vec': ['2022-10-01', '2025-09-30'], 'train_time_vec': ['2026-10-01', '2026-10-01'], 'rank_icir': '0.158', 'weight': '0.061'}

	Recorder: 86a715a9d70d477ab3f17c9d51121c5f

		Model: {'id': '86a715a9d70d477ab3f17c9d51121c5f', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.006, 'ICIR': 0.021, 'Rank IC': 0.006, 'Rank ICIR': 0.027}, 'data_train_vec': ['2023-10-01', '2025-12-31'], 'train_time_vec': ['2026-10-01', '2026-10-01'], 'rank_icir': '0.027', 'weight': '0.010'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20261001_18 230527748354961097 (Recorders: 5/5)

	Recorder: 948d1ae38b0e47fbbf575abf7ec78efb

		Model: {'id': '948d1ae38b0e47fbbf575abf7ec78efb', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.037, 'ICIR': 0.186, 'Rank IC': 0.041, 'Rank ICIR': 0.233}, 'data_train_vec': ['2021-10-01', '2025-06-30'], 'train_time_vec': ['2026-10-01', '2026-10-01'], 'rank_icir': '0.233', 'weight': '0.090'}

	Recorder: 251c0cd7718a4cb4a1c6523897dc60fd

		Model: {'id': '251c0cd7718a4cb4a1c6523897dc60fd', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.033, 'ICIR': 0.148, 'Rank IC': 0.021, 'Rank ICIR': 0.11}, 'data_train_vec': ['2022-10-01', '2025-09-30'], 'train_time_vec': ['2026-10-01', '2026-10-01'], 'rank_icir': '0.110', 'weight': '0.042'}

	Recorder: d143054933f445be9f32b1fcd0de056d

		Model: {'id': 'd143054933f445be9f32b1fcd0de056d', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.006, 'ICIR': 0.022, 'Rank IC': 0.002, 'Rank ICIR': 0.007}, 'data_train_vec': ['2023-10-01', '2025-12-31'], 'train_time_vec': ['2026-10-01', '2026-10-01'], 'rank_icir': '0.007', 'weight': '0.003'}

	Recorder: fd2318935efd4829b2d56c98827a3be7

		Model: {'id': 'fd2318935efd4829b2d56c98827a3be7', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.05, 'ICIR': 0.242, 'Rank IC': 0.025, 'Rank ICIR': 0.142}, 'data_train_vec': ['2024-10-01', '2026-03-31'], 'train_time_vec': ['2026-10-01', '2026-10-01'], 'rank_icir': '0.142', 'weight': '0.055'}

	Recorder: 819ff4bdb88c40e596cd0000a38cb2fa

		Model: {'id': '819ff4bdb88c40e596cd0000a38cb2fa', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.019, 'ICIR': 0.118, 'Rank IC': 0.015, 'Rank ICIR': 0.108}, 'data_train_vec': ['2025-10-01', '2026-06-30'], 'train_time_vec': ['2026-10-01', '2026-10-01'], 'rank_icir': '0.108', 'weight': '0.042'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20261001_18 357159028057105630 (Recorders: 3/5)

	Recorder: eb47f2deaed44513b7186e073d375855

		Model: {'id': 'eb47f2deaed44513b7186e073d375855', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.014, 'ICIR': 0.064, 'Rank IC': 0.044, 'Rank ICIR': 0.266}, 'data_train_vec': ['2021-10-01', '2025-06-30'], 'train_time_vec': ['2026-10-01', '2026-10-01'], 'rank_icir': '0.266', 'weight': '0.103'}

	Recorder: b57ce80944b143588916c49367247eb8

		Model: {'id': 'b57ce80944b143588916c49367247eb8', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.013, 'ICIR': 0.052, 'Rank IC': 0.024, 'Rank ICIR': 0.137}, 'data_train_vec': ['2022-10-01', '2025-09-30'], 'train_time_vec': ['2026-10-01', '2026-10-01'], 'rank_icir': '0.137', 'weight': '0.053'}

	Recorder: 5f923dc500e14624b10031b17148fd0f

		Model: {'id': '5f923dc500e14624b10031b17148fd0f', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.035, 'ICIR': 0.174, 'Rank IC': 0.016, 'Rank ICIR': 0.104}, 'data_train_vec': ['2024-10-01', '2026-03-31'], 'train_time_vec': ['2026-10-01', '2026-10-01'], 'rank_icir': '0.104', 'weight': '0.040'}
