# params 
 {'predict_dates': [{'start': '2026-08-12', 'end': '2026-08-12'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260812_16 628598479453739088 (Recorders: 1/5)

	Recorder: 627f052841004af7b34bcc2d74991a3b

		Model: {'id': '627f052841004af7b34bcc2d74991a3b', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.003, 'ICIR': 0.011, 'Rank IC': 0.026, 'Rank ICIR': 0.175}, 'data_train_vec': ['2023-08-12', '2025-11-11'], 'train_time_vec': ['2026-08-12', '2026-08-12'], 'rank_icir': '0.175', 'weight': '0.177'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260812_15 278780931770942441 (Recorders: 1/5)

	Recorder: ec164e3af15345c5823cab077203f4ef

		Model: {'id': 'ec164e3af15345c5823cab077203f4ef', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.02, 'ICIR': 0.136, 'Rank IC': 0.025, 'Rank ICIR': 0.216}, 'data_train_vec': ['2023-08-12', '2025-11-11'], 'train_time_vec': ['2026-08-12', '2026-08-12'], 'rank_icir': '0.216', 'weight': '0.219'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260812_13 584828567704580469 (Recorders: 2/5)

	Recorder: 695c8646114f44838f45af5b0183cb40

		Model: {'id': '695c8646114f44838f45af5b0183cb40', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.015, 'ICIR': 0.073, 'Rank IC': 0.031, 'Rank ICIR': 0.175}, 'data_train_vec': ['2021-08-12', '2025-05-11'], 'train_time_vec': ['2026-08-12', '2026-08-12'], 'rank_icir': '0.175', 'weight': '0.177'}

	Recorder: 4ec7ff71e918437da51c02c9ff262fce

		Model: {'id': '4ec7ff71e918437da51c02c9ff262fce', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.01, 'ICIR': 0.046, 'Rank IC': 0.021, 'Rank ICIR': 0.121}, 'data_train_vec': ['2022-08-12', '2025-08-11'], 'train_time_vec': ['2026-08-12', '2026-08-12'], 'rank_icir': '0.121', 'weight': '0.122'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260812_13 726246463003092483 (Recorders: 2/5)

	Recorder: 6b930252b2ad4447868632453fb333c9

		Model: {'id': '6b930252b2ad4447868632453fb333c9', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.007, 'ICIR': 0.036, 'Rank IC': 0.022, 'Rank ICIR': 0.139}, 'data_train_vec': ['2021-08-12', '2025-05-11'], 'train_time_vec': ['2026-08-12', '2026-08-12'], 'rank_icir': '0.139', 'weight': '0.141'}

	Recorder: 70592b913c3040759c536a7c068ccf91

		Model: {'id': '70592b913c3040759c536a7c068ccf91', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.018, 'ICIR': 0.089, 'Rank IC': 0.026, 'Rank ICIR': 0.162}, 'data_train_vec': ['2022-08-12', '2025-08-11'], 'train_time_vec': ['2026-08-12', '2026-08-12'], 'rank_icir': '0.162', 'weight': '0.164'}
