# params 
 {'predict_dates': [{'start': '2026-07-14', 'end': '2026-07-14'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260714_16 176330506818201137 (Recorders: 2/5)

	Recorder: fd092019606c4376a26f8a1d09aefeb3

		Model: {'id': 'fd092019606c4376a26f8a1d09aefeb3', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.009, 'ICIR': 0.068, 'Rank IC': 0.029, 'Rank ICIR': 0.225}, 'data_train_vec': ['2021-07-14', '2025-04-13'], 'train_time_vec': ['2026-07-14', '2026-07-14'], 'rank_icir': '0.225', 'weight': '0.088'}

	Recorder: a401d0e3dbc14c0587de306d3183ff8e

		Model: {'id': 'a401d0e3dbc14c0587de306d3183ff8e', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.016, 'ICIR': 0.13, 'Rank IC': 0.021, 'Rank ICIR': 0.215}, 'data_train_vec': ['2023-07-14', '2025-10-13'], 'train_time_vec': ['2026-07-14', '2026-07-14'], 'rank_icir': '0.215', 'weight': '0.084'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260714_16 587859968996217210 (Recorders: 3/5)

	Recorder: 771121aa0a0e486e8c449f8e660e80c9

		Model: {'id': '771121aa0a0e486e8c449f8e660e80c9', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.013, 'ICIR': 0.083, 'Rank IC': 0.041, 'Rank ICIR': 0.275}, 'data_train_vec': ['2021-07-14', '2025-04-13'], 'train_time_vec': ['2026-07-14', '2026-07-14'], 'rank_icir': '0.275', 'weight': '0.107'}

	Recorder: 905b8645bd84446ebe3068e5fdd65977

		Model: {'id': '905b8645bd84446ebe3068e5fdd65977', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.034, 'ICIR': 0.304, 'Rank IC': 0.036, 'Rank ICIR': 0.321}, 'data_train_vec': ['2023-07-14', '2025-10-13'], 'train_time_vec': ['2026-07-14', '2026-07-14'], 'rank_icir': '0.321', 'weight': '0.125'}

	Recorder: b287aac7b6294e00885ea727c8165568

		Model: {'id': 'b287aac7b6294e00885ea727c8165568', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.01, 'ICIR': 0.065, 'Rank IC': 0.01, 'Rank ICIR': 0.073}, 'data_train_vec': ['2024-07-14', '2026-01-13'], 'train_time_vec': ['2026-07-14', '2026-07-14'], 'rank_icir': '0.073', 'weight': '0.028'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260714_14 853985001637112917 (Recorders: 3/5)

	Recorder: a733c880d4ea4222a1c63c8701ec1c0c

		Model: {'id': 'a733c880d4ea4222a1c63c8701ec1c0c', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.02, 'ICIR': 0.123, 'Rank IC': 0.048, 'Rank ICIR': 0.297}, 'data_train_vec': ['2021-07-14', '2025-04-13'], 'train_time_vec': ['2026-07-14', '2026-07-14'], 'rank_icir': '0.297', 'weight': '0.116'}

	Recorder: 1d73e437ced74a7481e947c412a151e2

		Model: {'id': '1d73e437ced74a7481e947c412a151e2', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.011, 'ICIR': 0.075, 'Rank IC': 0.033, 'Rank ICIR': 0.226}, 'data_train_vec': ['2022-07-14', '2025-07-13'], 'train_time_vec': ['2026-07-14', '2026-07-14'], 'rank_icir': '0.226', 'weight': '0.088'}

	Recorder: d03afdd83df1497b9aa9b61767fcb92a

		Model: {'id': 'd03afdd83df1497b9aa9b61767fcb92a', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.019, 'ICIR': 0.138, 'Rank IC': 0.034, 'Rank ICIR': 0.282}, 'data_train_vec': ['2023-07-14', '2025-10-13'], 'train_time_vec': ['2026-07-14', '2026-07-14'], 'rank_icir': '0.282', 'weight': '0.110'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260714_14 965384084167864625 (Recorders: 1/5)

	Recorder: bc7a7b0a8562486d982edcbe8cf8de02

		Model: {'id': 'bc7a7b0a8562486d982edcbe8cf8de02', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.005, 'ICIR': 0.028, 'Rank IC': 0.02, 'Rank ICIR': 0.135}, 'data_train_vec': ['2023-07-14', '2025-10-13'], 'train_time_vec': ['2026-07-14', '2026-07-14'], 'rank_icir': '0.135', 'weight': '0.053'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260714_14 154177857710900724 (Recorders: 2/5)

	Recorder: 6a655a29e3f2455585647ef89582abdd

		Model: {'id': '6a655a29e3f2455585647ef89582abdd', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.004, 'ICIR': 0.025, 'Rank IC': 0.036, 'Rank ICIR': 0.224}, 'data_train_vec': ['2021-07-14', '2025-04-13'], 'train_time_vec': ['2026-07-14', '2026-07-14'], 'rank_icir': '0.224', 'weight': '0.087'}

	Recorder: 26306f77292e4f90a903720d39627829

		Model: {'id': '26306f77292e4f90a903720d39627829', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.009, 'ICIR': 0.061, 'Rank IC': 0.035, 'Rank ICIR': 0.292}, 'data_train_vec': ['2023-07-14', '2025-10-13'], 'train_time_vec': ['2026-07-14', '2026-07-14'], 'rank_icir': '0.292', 'weight': '0.114'}
