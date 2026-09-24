# params 
 {'predict_dates': [{'start': '2026-09-24', 'end': '2026-09-24'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260924_19 304519468158205493 (Recorders: 3/5)

	Recorder: 3615f1be771f472082d450618d0873f4

		Model: {'id': '3615f1be771f472082d450618d0873f4', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.009, 'ICIR': 0.049, 'Rank IC': 0.026, 'Rank ICIR': 0.15}, 'data_train_vec': ['2021-09-24', '2025-06-23'], 'train_time_vec': ['2026-09-24', '2026-09-24'], 'rank_icir': '0.150', 'weight': '0.065'}

	Recorder: ba2c56bb2cb342dc96b3fd2a8db03615

		Model: {'id': 'ba2c56bb2cb342dc96b3fd2a8db03615', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.022, 'ICIR': 0.091, 'Rank IC': 0.036, 'Rank ICIR': 0.199}, 'data_train_vec': ['2022-09-24', '2025-09-23'], 'train_time_vec': ['2026-09-24', '2026-09-24'], 'rank_icir': '0.199', 'weight': '0.086'}

	Recorder: cfc3f0fd506f4762902e504d0cbefa8d

		Model: {'id': 'cfc3f0fd506f4762902e504d0cbefa8d', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.022, 'ICIR': 0.093, 'Rank IC': 0.02, 'Rank ICIR': 0.121}, 'data_train_vec': ['2023-09-24', '2025-12-23'], 'train_time_vec': ['2026-09-24', '2026-09-24'], 'rank_icir': '0.121', 'weight': '0.052'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260924_19 537767389156637372 (Recorders: 3/5)

	Recorder: b64d1c812908437f929b4830c7179380

		Model: {'id': 'b64d1c812908437f929b4830c7179380', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.022, 'ICIR': 0.153, 'Rank IC': 0.031, 'Rank ICIR': 0.228}, 'data_train_vec': ['2021-09-24', '2025-06-23'], 'train_time_vec': ['2026-09-24', '2026-09-24'], 'rank_icir': '0.228', 'weight': '0.098'}

	Recorder: 24ba041d9e314a789e9b1f159ddba065

		Model: {'id': '24ba041d9e314a789e9b1f159ddba065', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.024, 'ICIR': 0.121, 'Rank IC': 0.034, 'Rank ICIR': 0.193}, 'data_train_vec': ['2022-09-24', '2025-09-23'], 'train_time_vec': ['2026-09-24', '2026-09-24'], 'rank_icir': '0.193', 'weight': '0.083'}

	Recorder: 96156a8eed674dd7938d5e7aec5a0852

		Model: {'id': '96156a8eed674dd7938d5e7aec5a0852', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.006, 'ICIR': 0.027, 'Rank IC': 0.009, 'Rank ICIR': 0.05}, 'data_train_vec': ['2023-09-24', '2025-12-23'], 'train_time_vec': ['2026-09-24', '2026-09-24'], 'rank_icir': '0.050', 'weight': '0.022'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260924_17 532694850647229438 (Recorders: 4/5)

	Recorder: e0246b201fae488f890eaad73d6df09a

		Model: {'id': 'e0246b201fae488f890eaad73d6df09a', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.036, 'ICIR': 0.181, 'Rank IC': 0.046, 'Rank ICIR': 0.264}, 'data_train_vec': ['2021-09-24', '2025-06-23'], 'train_time_vec': ['2026-09-24', '2026-09-24'], 'rank_icir': '0.264', 'weight': '0.114'}

	Recorder: fa55f95bb2344f719a3e5b22563c504b

		Model: {'id': 'fa55f95bb2344f719a3e5b22563c504b', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.025, 'ICIR': 0.107, 'Rank IC': 0.03, 'Rank ICIR': 0.163}, 'data_train_vec': ['2022-09-24', '2025-09-23'], 'train_time_vec': ['2026-09-24', '2026-09-24'], 'rank_icir': '0.163', 'weight': '0.070'}

	Recorder: c7a22e08846747039f395c761ecfa0f5

		Model: {'id': 'c7a22e08846747039f395c761ecfa0f5', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.008, 'ICIR': 0.031, 'Rank IC': 0.008, 'Rank ICIR': 0.038}, 'data_train_vec': ['2023-09-24', '2025-12-23'], 'train_time_vec': ['2026-09-24', '2026-09-24'], 'rank_icir': '0.038', 'weight': '0.016'}

	Recorder: 3277dfbdd5394729b64e6639ee0415fb

		Model: {'id': '3277dfbdd5394729b64e6639ee0415fb', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.026, 'ICIR': 0.103, 'Rank IC': 0.007, 'Rank ICIR': 0.034}, 'data_train_vec': ['2024-09-24', '2026-03-23'], 'train_time_vec': ['2026-09-24', '2026-09-24'], 'rank_icir': '0.034', 'weight': '0.015'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260924_17 667254749496480185 (Recorders: 3/5)

	Recorder: 0d23c98a0c834ae9b201c994cd23b3b7

		Model: {'id': '0d23c98a0c834ae9b201c994cd23b3b7', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.032, 'ICIR': 0.158, 'Rank IC': 0.037, 'Rank ICIR': 0.211}, 'data_train_vec': ['2021-09-24', '2025-06-23'], 'train_time_vec': ['2026-09-24', '2026-09-24'], 'rank_icir': '0.211', 'weight': '0.091'}

	Recorder: a99de3435da742aaaacedc0eb2de4951

		Model: {'id': 'a99de3435da742aaaacedc0eb2de4951', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.027, 'ICIR': 0.13, 'Rank IC': 0.018, 'Rank ICIR': 0.102}, 'data_train_vec': ['2022-09-24', '2025-09-23'], 'train_time_vec': ['2026-09-24', '2026-09-24'], 'rank_icir': '0.102', 'weight': '0.044'}

	Recorder: 2e42ae1bf76049eb92c2cc6bf1e60d4f

		Model: {'id': '2e42ae1bf76049eb92c2cc6bf1e60d4f', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.047, 'ICIR': 0.19, 'Rank IC': 0.02, 'Rank ICIR': 0.096}, 'data_train_vec': ['2024-09-24', '2026-03-23'], 'train_time_vec': ['2026-09-24', '2026-09-24'], 'rank_icir': '0.096', 'weight': '0.041'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260924_17 674085822107799175 (Recorders: 3/5)

	Recorder: e65c319a937d49d1a29b8c242ba5c5dc

		Model: {'id': 'e65c319a937d49d1a29b8c242ba5c5dc', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.009, 'ICIR': 0.043, 'Rank IC': 0.035, 'Rank ICIR': 0.204}, 'data_train_vec': ['2021-09-24', '2025-06-23'], 'train_time_vec': ['2026-09-24', '2026-09-24'], 'rank_icir': '0.204', 'weight': '0.088'}

	Recorder: 08d04175e4cb43edb1eb1e440f67ff59

		Model: {'id': '08d04175e4cb43edb1eb1e440f67ff59', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.007, 'ICIR': 0.028, 'Rank IC': 0.025, 'Rank ICIR': 0.148}, 'data_train_vec': ['2022-09-24', '2025-09-23'], 'train_time_vec': ['2026-09-24', '2026-09-24'], 'rank_icir': '0.148', 'weight': '0.064'}

	Recorder: 5fa7cbf0ea8a4d38ab10cf4da1e197b3

		Model: {'id': '5fa7cbf0ea8a4d38ab10cf4da1e197b3', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.029, 'ICIR': 0.125, 'Rank IC': 0.018, 'Rank ICIR': 0.114}, 'data_train_vec': ['2024-09-24', '2026-03-23'], 'train_time_vec': ['2026-09-24', '2026-09-24'], 'rank_icir': '0.114', 'weight': '0.049'}
