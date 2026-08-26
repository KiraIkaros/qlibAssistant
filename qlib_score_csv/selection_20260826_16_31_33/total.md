# params 
 {'predict_dates': [{'start': '2026-08-26', 'end': '2026-08-26'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260826_15 638342998296308849 (Recorders: 2/5)

	Recorder: 93e2820f15df43fba8043c4da5477e71

		Model: {'id': '93e2820f15df43fba8043c4da5477e71', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.014, 'ICIR': 0.064, 'Rank IC': 0.033, 'Rank ICIR': 0.222}, 'data_train_vec': ['2022-08-26', '2025-08-25'], 'train_time_vec': ['2026-08-26', '2026-08-26'], 'rank_icir': '0.222', 'weight': '0.143'}

	Recorder: a185c3fc19764f84b5bfcbe7154daf02

		Model: {'id': 'a185c3fc19764f84b5bfcbe7154daf02', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.006, 'ICIR': 0.026, 'Rank IC': 0.01, 'Rank ICIR': 0.066}, 'data_train_vec': ['2023-08-26', '2025-11-25'], 'train_time_vec': ['2026-08-26', '2026-08-26'], 'rank_icir': '0.066', 'weight': '0.043'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260826_15 363633914712357669 (Recorders: 2/5)

	Recorder: 3e7b6a1979c24a899e24829472ceffdb

		Model: {'id': '3e7b6a1979c24a899e24829472ceffdb', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.004, 'ICIR': 0.025, 'Rank IC': 0.013, 'Rank ICIR': 0.089}, 'data_train_vec': ['2021-08-26', '2025-05-25'], 'train_time_vec': ['2026-08-26', '2026-08-26'], 'rank_icir': '0.089', 'weight': '0.057'}

	Recorder: 99892c3c4e13469a852756f8ca9b75ae

		Model: {'id': '99892c3c4e13469a852756f8ca9b75ae', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.014, 'ICIR': 0.083, 'Rank IC': 0.021, 'Rank ICIR': 0.145}, 'data_train_vec': ['2023-08-26', '2025-11-25'], 'train_time_vec': ['2026-08-26', '2026-08-26'], 'rank_icir': '0.145', 'weight': '0.093'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260826_13 368067982946795169 (Recorders: 3/5)

	Recorder: 784eaaed0b2c4587bb65b1f225116da8

		Model: {'id': '784eaaed0b2c4587bb65b1f225116da8', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.017, 'ICIR': 0.082, 'Rank IC': 0.028, 'Rank ICIR': 0.165}, 'data_train_vec': ['2021-08-26', '2025-05-25'], 'train_time_vec': ['2026-08-26', '2026-08-26'], 'rank_icir': '0.165', 'weight': '0.106'}

	Recorder: 153582ba12814bb3bf09d1954a5254c8

		Model: {'id': '153582ba12814bb3bf09d1954a5254c8', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.022, 'ICIR': 0.097, 'Rank IC': 0.031, 'Rank ICIR': 0.18}, 'data_train_vec': ['2022-08-26', '2025-08-25'], 'train_time_vec': ['2026-08-26', '2026-08-26'], 'rank_icir': '0.180', 'weight': '0.116'}

	Recorder: 76dc218e86ef4a2c8d628c90231e8261

		Model: {'id': '76dc218e86ef4a2c8d628c90231e8261', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.003, 'ICIR': 0.013, 'Rank IC': 0.01, 'Rank ICIR': 0.051}, 'data_train_vec': ['2023-08-26', '2025-11-25'], 'train_time_vec': ['2026-08-26', '2026-08-26'], 'rank_icir': '0.051', 'weight': '0.033'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260826_13 352685369726387571 (Recorders: 4/5)

	Recorder: 796fc163419f40928a51e61d756be735

		Model: {'id': '796fc163419f40928a51e61d756be735', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.012, 'ICIR': 0.056, 'Rank IC': 0.024, 'Rank ICIR': 0.146}, 'data_train_vec': ['2021-08-26', '2025-05-25'], 'train_time_vec': ['2026-08-26', '2026-08-26'], 'rank_icir': '0.146', 'weight': '0.094'}

	Recorder: fcef64330028485a8b920a5d231da2d5

		Model: {'id': 'fcef64330028485a8b920a5d231da2d5', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.029, 'ICIR': 0.152, 'Rank IC': 0.031, 'Rank ICIR': 0.198}, 'data_train_vec': ['2022-08-26', '2025-08-25'], 'train_time_vec': ['2026-08-26', '2026-08-26'], 'rank_icir': '0.198', 'weight': '0.128'}

	Recorder: 05b8f049beeb4963bf673546424423fd

		Model: {'id': '05b8f049beeb4963bf673546424423fd', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.032, 'ICIR': 0.096, 'Rank IC': 0.019, 'Rank ICIR': 0.068}, 'data_train_vec': ['2024-08-26', '2026-02-25'], 'train_time_vec': ['2026-08-26', '2026-08-26'], 'rank_icir': '0.068', 'weight': '0.044'}

	Recorder: 9c0181cabaa4444aa047a7846f228372

		Model: {'id': '9c0181cabaa4444aa047a7846f228372', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.056, 'ICIR': 0.266, 'Rank IC': 0.026, 'Rank ICIR': 0.166}, 'data_train_vec': ['2025-08-26', '2026-05-25'], 'train_time_vec': ['2026-08-26', '2026-08-26'], 'rank_icir': '0.166', 'weight': '0.107'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260826_13 313877307162740615 (Recorders: 1/5)

	Recorder: 14f1245719c14fcfa4fd5b8e01a77b3d

		Model: {'id': '14f1245719c14fcfa4fd5b8e01a77b3d', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.03, 'ICIR': 0.086, 'Rank IC': 0.013, 'Rank ICIR': 0.055}, 'data_train_vec': ['2025-08-26', '2026-05-25'], 'train_time_vec': ['2026-08-26', '2026-08-26'], 'rank_icir': '0.055', 'weight': '0.035'}
