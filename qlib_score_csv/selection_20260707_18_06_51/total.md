# params 
 {'predict_dates': [{'start': '2026-07-03', 'end': '2026-07-03'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260707_17 793884872066201403 (Recorders: 3/5)

	Recorder: 0ea1f0f9f1804a74b1b6439a0befdfc6

		Model: {'id': '0ea1f0f9f1804a74b1b6439a0befdfc6', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.011, 'ICIR': 0.092, 'Rank IC': 0.025, 'Rank ICIR': 0.171}, 'data_train_vec': ['2022-07-07', '2025-07-06'], 'train_time_vec': ['2026-07-07', '2026-07-07'], 'rank_icir': '0.171', 'weight': '0.069'}

	Recorder: 179c10a2390a442a9963d61355046312

		Model: {'id': '179c10a2390a442a9963d61355046312', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.043, 'ICIR': 0.337, 'Rank IC': 0.037, 'Rank ICIR': 0.295}, 'data_train_vec': ['2023-07-07', '2025-10-06'], 'train_time_vec': ['2026-07-07', '2026-07-07'], 'rank_icir': '0.295', 'weight': '0.118'}

	Recorder: 44bbf3d6342f4f118c78235561c2a8ee

		Model: {'id': '44bbf3d6342f4f118c78235561c2a8ee', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.03, 'ICIR': 0.278, 'Rank IC': 0.012, 'Rank ICIR': 0.114}, 'data_train_vec': ['2024-07-07', '2026-01-06'], 'train_time_vec': ['2026-07-07', '2026-07-07'], 'rank_icir': '0.114', 'weight': '0.046'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260707_17 531374161617403934 (Recorders: 3/5)

	Recorder: 319b3059fe80490dbaada6320a271204

		Model: {'id': '319b3059fe80490dbaada6320a271204', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.034, 'ICIR': 0.262, 'Rank IC': 0.034, 'Rank ICIR': 0.265}, 'data_train_vec': ['2023-07-07', '2025-10-06'], 'train_time_vec': ['2026-07-07', '2026-07-07'], 'rank_icir': '0.265', 'weight': '0.106'}

	Recorder: ee21c742d7694ad2b5019d2165e2117c

		Model: {'id': 'ee21c742d7694ad2b5019d2165e2117c', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.026, 'ICIR': 0.195, 'Rank IC': 0.026, 'Rank ICIR': 0.206}, 'data_train_vec': ['2024-07-07', '2026-01-06'], 'train_time_vec': ['2026-07-07', '2026-07-07'], 'rank_icir': '0.206', 'weight': '0.083'}

	Recorder: d039386698634960a21451778411842a

		Model: {'id': 'd039386698634960a21451778411842a', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.039, 'ICIR': 0.155, 'Rank IC': 0.022, 'Rank ICIR': 0.088}, 'data_train_vec': ['2025-07-07', '2026-04-06'], 'train_time_vec': ['2026-07-07', '2026-07-07'], 'rank_icir': '0.088', 'weight': '0.035'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260707_15 736421554281235109 (Recorders: 4/5)

	Recorder: 2e0b19604ff34641b4749232894c8768

		Model: {'id': '2e0b19604ff34641b4749232894c8768', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.01, 'ICIR': 0.055, 'Rank IC': 0.043, 'Rank ICIR': 0.248}, 'data_train_vec': ['2021-07-07', '2025-04-06'], 'train_time_vec': ['2026-07-07', '2026-07-07'], 'rank_icir': '0.248', 'weight': '0.100'}

	Recorder: 32196086869f4c4ca6aecf3290501cb6

		Model: {'id': '32196086869f4c4ca6aecf3290501cb6', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.025, 'ICIR': 0.162, 'Rank IC': 0.05, 'Rank ICIR': 0.312}, 'data_train_vec': ['2022-07-07', '2025-07-06'], 'train_time_vec': ['2026-07-07', '2026-07-07'], 'rank_icir': '0.312', 'weight': '0.125'}

	Recorder: 6e4e7bfe62d5425a9100e1eaadbf38ea

		Model: {'id': '6e4e7bfe62d5425a9100e1eaadbf38ea', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.022, 'ICIR': 0.166, 'Rank IC': 0.031, 'Rank ICIR': 0.244}, 'data_train_vec': ['2023-07-07', '2025-10-06'], 'train_time_vec': ['2026-07-07', '2026-07-07'], 'rank_icir': '0.244', 'weight': '0.098'}

	Recorder: 887b14c397ca41b8828c061bf8edc6b7

		Model: {'id': '887b14c397ca41b8828c061bf8edc6b7', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.013, 'ICIR': 0.064, 'Rank IC': 0.001, 'Rank ICIR': 0.006}, 'data_train_vec': ['2025-07-07', '2026-04-06'], 'train_time_vec': ['2026-07-07', '2026-07-07'], 'rank_icir': '0.006', 'weight': '0.002'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260707_15 166107169899636159 (Recorders: 2/5)

	Recorder: 55c46eb06db64740bc212dc1914ab576

		Model: {'id': '55c46eb06db64740bc212dc1914ab576', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.008, 'ICIR': 0.058, 'Rank IC': 0.019, 'Rank ICIR': 0.14}, 'data_train_vec': ['2023-07-07', '2025-10-06'], 'train_time_vec': ['2026-07-07', '2026-07-07'], 'rank_icir': '0.140', 'weight': '0.056'}

	Recorder: a5b0ed403e21435abd7fd4f9598c4a28

		Model: {'id': 'a5b0ed403e21435abd7fd4f9598c4a28', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.017, 'ICIR': 0.08, 'Rank IC': 0.002, 'Rank ICIR': 0.008}, 'data_train_vec': ['2025-07-07', '2026-04-06'], 'train_time_vec': ['2026-07-07', '2026-07-07'], 'rank_icir': '0.008', 'weight': '0.003'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260707_15 398456654794312653 (Recorders: 2/5)

	Recorder: 389e74bbea4d4a9bad01ff2beda533ad

		Model: {'id': '389e74bbea4d4a9bad01ff2beda533ad', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.005, 'ICIR': 0.032, 'Rank IC': 0.04, 'Rank ICIR': 0.238}, 'data_train_vec': ['2022-07-07', '2025-07-06'], 'train_time_vec': ['2026-07-07', '2026-07-07'], 'rank_icir': '0.238', 'weight': '0.096'}

	Recorder: db119569a4bd4f5e9d907cbd0ffd8421

		Model: {'id': 'db119569a4bd4f5e9d907cbd0ffd8421', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.001, 'ICIR': 0.01, 'Rank IC': 0.019, 'Rank ICIR': 0.156}, 'data_train_vec': ['2023-07-07', '2025-10-06'], 'train_time_vec': ['2026-07-07', '2026-07-07'], 'rank_icir': '0.156', 'weight': '0.063'}
