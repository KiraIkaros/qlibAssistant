# params 
 {'predict_dates': [{'start': '2026-07-20', 'end': '2026-07-20'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260721_16 599824451459758057 (Recorders: 2/5)

	Recorder: 21c2d49125854e378585602312e8e151

		Model: {'id': '21c2d49125854e378585602312e8e151', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.005, 'ICIR': 0.036, 'Rank IC': 0.023, 'Rank ICIR': 0.148}, 'data_train_vec': ['2021-07-21', '2025-04-20'], 'train_time_vec': ['2026-07-21', '2026-07-21'], 'rank_icir': '0.148', 'weight': '0.174'}

	Recorder: b95da403be1345258740b59d67f7f28e

		Model: {'id': 'b95da403be1345258740b59d67f7f28e', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.015, 'ICIR': 0.103, 'Rank IC': 0.027, 'Rank ICIR': 0.233}, 'data_train_vec': ['2023-07-21', '2025-10-20'], 'train_time_vec': ['2026-07-21', '2026-07-21'], 'rank_icir': '0.233', 'weight': '0.273'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260721_14 294109517424810232 (Recorders: 3/5)

	Recorder: 9f90714561cb4d94bd8117968e8b7dfa

		Model: {'id': '9f90714561cb4d94bd8117968e8b7dfa', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.011, 'ICIR': 0.062, 'Rank IC': 0.039, 'Rank ICIR': 0.229}, 'data_train_vec': ['2021-07-21', '2025-04-20'], 'train_time_vec': ['2026-07-21', '2026-07-21'], 'rank_icir': '0.229', 'weight': '0.268'}

	Recorder: 422fd7fb6ec449c7a7df7bb510f5aa38

		Model: {'id': '422fd7fb6ec449c7a7df7bb510f5aa38', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.003, 'ICIR': 0.021, 'Rank IC': 0.02, 'Rank ICIR': 0.128}, 'data_train_vec': ['2022-07-21', '2025-07-20'], 'train_time_vec': ['2026-07-21', '2026-07-21'], 'rank_icir': '0.128', 'weight': '0.150'}

	Recorder: b5eca3021b854cdfbdaef684e588b990

		Model: {'id': 'b5eca3021b854cdfbdaef684e588b990', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.001, 'ICIR': 0.008, 'Rank IC': 0.016, 'Rank ICIR': 0.115}, 'data_train_vec': ['2023-07-21', '2025-10-20'], 'train_time_vec': ['2026-07-21', '2026-07-21'], 'rank_icir': '0.115', 'weight': '0.135'}
