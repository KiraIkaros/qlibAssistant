# params 
 {'predict_dates': [{'start': '2026-07-27', 'end': '2026-07-27'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260727_17 760372207963978506 (Recorders: 1/5)

	Recorder: 0271c0dae558411abb2f5d9936cc1b34

		Model: {'id': '0271c0dae558411abb2f5d9936cc1b34', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.008, 'ICIR': 0.045, 'Rank IC': 0.034, 'Rank ICIR': 0.185}, 'data_train_vec': ['2021-07-27', '2025-04-26'], 'train_time_vec': ['2026-07-27', '2026-07-27'], 'rank_icir': '0.185', 'weight': '0.157'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260727_17 729341976540428799 (Recorders: 3/5)

	Recorder: fc76b5e84e4f4b069e2047f6ac7f28f6

		Model: {'id': 'fc76b5e84e4f4b069e2047f6ac7f28f6', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.011, 'ICIR': 0.089, 'Rank IC': 0.032, 'Rank ICIR': 0.233}, 'data_train_vec': ['2021-07-27', '2025-04-26'], 'train_time_vec': ['2026-07-27', '2026-07-27'], 'rank_icir': '0.233', 'weight': '0.198'}

	Recorder: 1cce4c0228b8436ab89e90673168f927

		Model: {'id': '1cce4c0228b8436ab89e90673168f927', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.002, 'ICIR': 0.015, 'Rank IC': 0.019, 'Rank ICIR': 0.128}, 'data_train_vec': ['2022-07-27', '2025-07-26'], 'train_time_vec': ['2026-07-27', '2026-07-27'], 'rank_icir': '0.128', 'weight': '0.109'}

	Recorder: c80bd7d5b35442a8901845ab6f49f2b5

		Model: {'id': 'c80bd7d5b35442a8901845ab6f49f2b5', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.02, 'ICIR': 0.125, 'Rank IC': 0.022, 'Rank ICIR': 0.164}, 'data_train_vec': ['2023-07-27', '2025-10-26'], 'train_time_vec': ['2026-07-27', '2026-07-27'], 'rank_icir': '0.164', 'weight': '0.139'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260727_15 498991905203926680 (Recorders: 3/5)

	Recorder: 7569dc8fece34dbea2dac5e0cd9d9580

		Model: {'id': '7569dc8fece34dbea2dac5e0cd9d9580', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.019, 'ICIR': 0.106, 'Rank IC': 0.039, 'Rank ICIR': 0.229}, 'data_train_vec': ['2021-07-27', '2025-04-26'], 'train_time_vec': ['2026-07-27', '2026-07-27'], 'rank_icir': '0.229', 'weight': '0.194'}

	Recorder: 1394c8ac8b1245669690a8ff05009169

		Model: {'id': '1394c8ac8b1245669690a8ff05009169', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.009, 'ICIR': 0.053, 'Rank IC': 0.025, 'Rank ICIR': 0.159}, 'data_train_vec': ['2022-07-27', '2025-07-26'], 'train_time_vec': ['2026-07-27', '2026-07-27'], 'rank_icir': '0.159', 'weight': '0.135'}

	Recorder: 26d639a3be5847e29a05b87b6b82d5d2

		Model: {'id': '26d639a3be5847e29a05b87b6b82d5d2', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.004, 'ICIR': 0.019, 'Rank IC': 0.013, 'Rank ICIR': 0.081}, 'data_train_vec': ['2023-07-27', '2025-10-26'], 'train_time_vec': ['2026-07-27', '2026-07-27'], 'rank_icir': '0.081', 'weight': '0.069'}
