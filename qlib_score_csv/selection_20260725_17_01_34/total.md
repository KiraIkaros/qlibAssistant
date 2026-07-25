# params 
 {'predict_dates': [{'start': '2026-07-24', 'end': '2026-07-24'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260725_16 516688684789595737 (Recorders: 3/5)

	Recorder: 64ec671a4d5f44868cd60dbc219549d3

		Model: {'id': '64ec671a4d5f44868cd60dbc219549d3', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.005, 'ICIR': 0.03, 'Rank IC': 0.032, 'Rank ICIR': 0.17}, 'data_train_vec': ['2021-07-25', '2025-04-24'], 'train_time_vec': ['2026-07-25', '2026-07-25'], 'rank_icir': '0.170', 'weight': '0.146'}

	Recorder: 52bb009140c84cbfbeda611e9d548580

		Model: {'id': '52bb009140c84cbfbeda611e9d548580', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.02, 'ICIR': 0.151, 'Rank IC': 0.023, 'Rank ICIR': 0.158}, 'data_train_vec': ['2022-07-25', '2025-07-24'], 'train_time_vec': ['2026-07-25', '2026-07-25'], 'rank_icir': '0.158', 'weight': '0.136'}

	Recorder: 0de5ca22ebd840c7b440d37ed463fc73

		Model: {'id': '0de5ca22ebd840c7b440d37ed463fc73', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.011, 'ICIR': 0.05, 'Rank IC': 0.013, 'Rank ICIR': 0.087}, 'data_train_vec': ['2023-07-25', '2025-10-24'], 'train_time_vec': ['2026-07-25', '2026-07-25'], 'rank_icir': '0.087', 'weight': '0.075'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260725_16 815521695304725178 (Recorders: 2/5)

	Recorder: 852defbc808c48259d9310130e7844e6

		Model: {'id': '852defbc808c48259d9310130e7844e6', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.002, 'ICIR': 0.017, 'Rank IC': 0.023, 'Rank ICIR': 0.172}, 'data_train_vec': ['2021-07-25', '2025-04-24'], 'train_time_vec': ['2026-07-25', '2026-07-25'], 'rank_icir': '0.172', 'weight': '0.148'}

	Recorder: a72566d30a4243dfa86778caed33abe7

		Model: {'id': 'a72566d30a4243dfa86778caed33abe7', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.015, 'ICIR': 0.088, 'Rank IC': 0.016, 'Rank ICIR': 0.122}, 'data_train_vec': ['2023-07-25', '2025-10-24'], 'train_time_vec': ['2026-07-25', '2026-07-25'], 'rank_icir': '0.122', 'weight': '0.105'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260725_14 886020181794954524 (Recorders: 3/5)

	Recorder: 6cfc253783154dd2bae4c015eb1e7058

		Model: {'id': '6cfc253783154dd2bae4c015eb1e7058', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.013, 'ICIR': 0.075, 'Rank IC': 0.037, 'Rank ICIR': 0.215}, 'data_train_vec': ['2021-07-25', '2025-04-24'], 'train_time_vec': ['2026-07-25', '2026-07-25'], 'rank_icir': '0.215', 'weight': '0.185'}

	Recorder: a684f688cd2e4091929c5e5ec75eb1ae

		Model: {'id': 'a684f688cd2e4091929c5e5ec75eb1ae', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.008, 'ICIR': 0.046, 'Rank IC': 0.023, 'Rank ICIR': 0.143}, 'data_train_vec': ['2022-07-25', '2025-07-24'], 'train_time_vec': ['2026-07-25', '2026-07-25'], 'rank_icir': '0.143', 'weight': '0.123'}

	Recorder: 21b266ecfe404294bd32e80f9975626e

		Model: {'id': '21b266ecfe404294bd32e80f9975626e', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.003, 'ICIR': 0.015, 'Rank IC': 0.016, 'Rank ICIR': 0.094}, 'data_train_vec': ['2023-07-25', '2025-10-24'], 'train_time_vec': ['2026-07-25', '2026-07-25'], 'rank_icir': '0.094', 'weight': '0.081'}
