# params 
 {'predict_dates': [{'start': '2026-08-07', 'end': '2026-08-07'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260808_15 516397208754135716 (Recorders: 2/5)

	Recorder: 29861ba1b00c411bb7e4f2625c707de7

		Model: {'id': '29861ba1b00c411bb7e4f2625c707de7', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.007, 'ICIR': 0.04, 'Rank IC': 0.024, 'Rank ICIR': 0.118}, 'data_train_vec': ['2021-08-08', '2025-05-07'], 'train_time_vec': ['2026-08-08', '2026-08-08'], 'rank_icir': '0.118', 'weight': '0.082'}

	Recorder: ddaa58a5714240d2881018b2a3fbabca

		Model: {'id': 'ddaa58a5714240d2881018b2a3fbabca', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.017, 'ICIR': 0.069, 'Rank IC': 0.035, 'Rank ICIR': 0.232}, 'data_train_vec': ['2023-08-08', '2025-11-07'], 'train_time_vec': ['2026-08-08', '2026-08-08'], 'rank_icir': '0.232', 'weight': '0.161'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260808_14 748372408296547006 (Recorders: 2/5)

	Recorder: 7f1866eb1cb64046aef890ac6897c6b4

		Model: {'id': '7f1866eb1cb64046aef890ac6897c6b4', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.01, 'ICIR': 0.059, 'Rank IC': 0.021, 'Rank ICIR': 0.129}, 'data_train_vec': ['2021-08-08', '2025-05-07'], 'train_time_vec': ['2026-08-08', '2026-08-08'], 'rank_icir': '0.129', 'weight': '0.089'}

	Recorder: 60e65baeeac045d49538dc55b66568f6

		Model: {'id': '60e65baeeac045d49538dc55b66568f6', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.031, 'ICIR': 0.157, 'Rank IC': 0.033, 'Rank ICIR': 0.231}, 'data_train_vec': ['2023-08-08', '2025-11-07'], 'train_time_vec': ['2026-08-08', '2026-08-08'], 'rank_icir': '0.231', 'weight': '0.160'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260808_13 728174088514751280 (Recorders: 3/5)

	Recorder: 0b4bd5e028884aeb9893767e8443a1ac

		Model: {'id': '0b4bd5e028884aeb9893767e8443a1ac', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.019, 'ICIR': 0.098, 'Rank IC': 0.036, 'Rank ICIR': 0.205}, 'data_train_vec': ['2021-08-08', '2025-05-07'], 'train_time_vec': ['2026-08-08', '2026-08-08'], 'rank_icir': '0.205', 'weight': '0.142'}

	Recorder: 817c547fac504d9cbcc2c169b9677fdd

		Model: {'id': '817c547fac504d9cbcc2c169b9677fdd', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.011, 'ICIR': 0.051, 'Rank IC': 0.024, 'Rank ICIR': 0.139}, 'data_train_vec': ['2022-08-08', '2025-08-07'], 'train_time_vec': ['2026-08-08', '2026-08-08'], 'rank_icir': '0.139', 'weight': '0.096'}

	Recorder: df2d3d3c1ed342c999e430f5ae964c46

		Model: {'id': 'df2d3d3c1ed342c999e430f5ae964c46', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.004, 'ICIR': 0.017, 'Rank IC': 0.016, 'Rank ICIR': 0.09}, 'data_train_vec': ['2023-08-08', '2025-11-07'], 'train_time_vec': ['2026-08-08', '2026-08-08'], 'rank_icir': '0.090', 'weight': '0.062'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260808_13 281342471352972091 (Recorders: 2/5)

	Recorder: ead5c6db497f4b1c8c1b56500001d5b1

		Model: {'id': 'ead5c6db497f4b1c8c1b56500001d5b1', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.009, 'ICIR': 0.043, 'Rank IC': 0.026, 'Rank ICIR': 0.16}, 'data_train_vec': ['2021-08-08', '2025-05-07'], 'train_time_vec': ['2026-08-08', '2026-08-08'], 'rank_icir': '0.160', 'weight': '0.111'}

	Recorder: 36db44d3712c466296cbac8a8913ec55

		Model: {'id': '36db44d3712c466296cbac8a8913ec55', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.012, 'ICIR': 0.058, 'Rank IC': 0.022, 'Rank ICIR': 0.138}, 'data_train_vec': ['2022-08-08', '2025-08-07'], 'train_time_vec': ['2026-08-08', '2026-08-08'], 'rank_icir': '0.138', 'weight': '0.096'}
