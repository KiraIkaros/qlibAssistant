# params 
 {'predict_dates': [{'start': '2026-06-18', 'end': '2026-06-18'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260619_18 596438424595333866 (Recorders: 3/5)

	Recorder: 6f0919e9308c4b119f21642aab43eeb0

		Model: {'id': '6f0919e9308c4b119f21642aab43eeb0', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.008, 'ICIR': 0.072, 'Rank IC': 0.03, 'Rank ICIR': 0.222}, 'data_train_vec': ['2022-06-19', '2025-06-18'], 'train_time_vec': ['2026-06-19', '2026-06-19'], 'rank_icir': '0.222', 'weight': '0.053'}

	Recorder: a5b04107824c4e6caf744f5f2bc35cda

		Model: {'id': 'a5b04107824c4e6caf744f5f2bc35cda', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.038, 'ICIR': 0.381, 'Rank IC': 0.031, 'Rank ICIR': 0.233}, 'data_train_vec': ['2023-06-19', '2025-09-18'], 'train_time_vec': ['2026-06-19', '2026-06-19'], 'rank_icir': '0.233', 'weight': '0.056'}

	Recorder: 646d33d9433847d5bfeb09c282af6659

		Model: {'id': '646d33d9433847d5bfeb09c282af6659', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.021, 'ICIR': 0.188, 'Rank IC': 0.042, 'Rank ICIR': 0.457}, 'data_train_vec': ['2024-06-19', '2025-12-18'], 'train_time_vec': ['2026-06-19', '2026-06-19'], 'rank_icir': '0.457', 'weight': '0.109'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260619_18 514141505867553207 (Recorders: 3/5)

	Recorder: e8b3795ba2f94b2da4cd85bc9576ebbf

		Model: {'id': 'e8b3795ba2f94b2da4cd85bc9576ebbf', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.006, 'ICIR': 0.041, 'Rank IC': 0.035, 'Rank ICIR': 0.249}, 'data_train_vec': ['2022-06-19', '2025-06-18'], 'train_time_vec': ['2026-06-19', '2026-06-19'], 'rank_icir': '0.249', 'weight': '0.059'}

	Recorder: 5a256cd232024880949fd945e9e3cc0e

		Model: {'id': '5a256cd232024880949fd945e9e3cc0e', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.035, 'ICIR': 0.307, 'Rank IC': 0.041, 'Rank ICIR': 0.317}, 'data_train_vec': ['2023-06-19', '2025-09-18'], 'train_time_vec': ['2026-06-19', '2026-06-19'], 'rank_icir': '0.317', 'weight': '0.076'}

	Recorder: 62a51c8400b44099a06ed53861239b74

		Model: {'id': '62a51c8400b44099a06ed53861239b74', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.043, 'ICIR': 0.326, 'Rank IC': 0.049, 'Rank ICIR': 0.395}, 'data_train_vec': ['2024-06-19', '2025-12-18'], 'train_time_vec': ['2026-06-19', '2026-06-19'], 'rank_icir': '0.395', 'weight': '0.094'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260619_15 453939932971576585 (Recorders: 4/5)

	Recorder: 99fa7eb03e5d4d8594910108193939cd

		Model: {'id': '99fa7eb03e5d4d8594910108193939cd', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.014, 'ICIR': 0.085, 'Rank IC': 0.047, 'Rank ICIR': 0.282}, 'data_train_vec': ['2021-06-19', '2025-03-18'], 'train_time_vec': ['2026-06-19', '2026-06-19'], 'rank_icir': '0.282', 'weight': '0.067'}

	Recorder: 4b800419b46f4c9694b69f867a569896

		Model: {'id': '4b800419b46f4c9694b69f867a569896', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.026, 'ICIR': 0.167, 'Rank IC': 0.055, 'Rank ICIR': 0.323}, 'data_train_vec': ['2022-06-19', '2025-06-18'], 'train_time_vec': ['2026-06-19', '2026-06-19'], 'rank_icir': '0.323', 'weight': '0.077'}

	Recorder: 377c5e29bb6a46b1a78c972b24909e15

		Model: {'id': '377c5e29bb6a46b1a78c972b24909e15', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.022, 'ICIR': 0.161, 'Rank IC': 0.036, 'Rank ICIR': 0.243}, 'data_train_vec': ['2023-06-19', '2025-09-18'], 'train_time_vec': ['2026-06-19', '2026-06-19'], 'rank_icir': '0.243', 'weight': '0.058'}

	Recorder: 81170de5e7694d70a6c4b64b338822e6

		Model: {'id': '81170de5e7694d70a6c4b64b338822e6', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.026, 'ICIR': 0.194, 'Rank IC': 0.029, 'Rank ICIR': 0.245}, 'data_train_vec': ['2024-06-19', '2025-12-18'], 'train_time_vec': ['2026-06-19', '2026-06-19'], 'rank_icir': '0.245', 'weight': '0.058'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260619_15 657261960006796117 (Recorders: 3/5)

	Recorder: c8c4bc95d81446da92daf6bb4df3abd8

		Model: {'id': 'c8c4bc95d81446da92daf6bb4df3abd8', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.003, 'ICIR': 0.021, 'Rank IC': 0.036, 'Rank ICIR': 0.285}, 'data_train_vec': ['2021-06-19', '2025-03-18'], 'train_time_vec': ['2026-06-19', '2026-06-19'], 'rank_icir': '0.285', 'weight': '0.068'}

	Recorder: 12fe3e9225fb4dfe983fd66273be2023

		Model: {'id': '12fe3e9225fb4dfe983fd66273be2023', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.005, 'ICIR': 0.04, 'Rank IC': 0.024, 'Rank ICIR': 0.186}, 'data_train_vec': ['2023-06-19', '2025-09-18'], 'train_time_vec': ['2026-06-19', '2026-06-19'], 'rank_icir': '0.186', 'weight': '0.044'}

	Recorder: 25505efe09be49b8b4adf8b365e54ceb

		Model: {'id': '25505efe09be49b8b4adf8b365e54ceb', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.024, 'ICIR': 0.149, 'Rank IC': 0.021, 'Rank ICIR': 0.14}, 'data_train_vec': ['2024-06-19', '2025-12-18'], 'train_time_vec': ['2026-06-19', '2026-06-19'], 'rank_icir': '0.140', 'weight': '0.033'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260619_15 324169985122355424 (Recorders: 3/5)

	Recorder: 8958eb3754c7444c9cc08ccac9bb849a

		Model: {'id': '8958eb3754c7444c9cc08ccac9bb849a', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.003, 'ICIR': 0.022, 'Rank IC': 0.042, 'Rank ICIR': 0.247}, 'data_train_vec': ['2022-06-19', '2025-06-18'], 'train_time_vec': ['2026-06-19', '2026-06-19'], 'rank_icir': '0.247', 'weight': '0.059'}

	Recorder: 65be9a3ce0f24cb18e964b2b73d91749

		Model: {'id': '65be9a3ce0f24cb18e964b2b73d91749', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.002, 'ICIR': 0.014, 'Rank IC': 0.018, 'Rank ICIR': 0.115}, 'data_train_vec': ['2023-06-19', '2025-09-18'], 'train_time_vec': ['2026-06-19', '2026-06-19'], 'rank_icir': '0.115', 'weight': '0.027'}

	Recorder: 403b9af1af2b4fccb5c9bb1f07e130e8

		Model: {'id': '403b9af1af2b4fccb5c9bb1f07e130e8', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.01, 'ICIR': 0.08, 'Rank IC': 0.024, 'Rank ICIR': 0.25}, 'data_train_vec': ['2024-06-19', '2025-12-18'], 'train_time_vec': ['2026-06-19', '2026-06-19'], 'rank_icir': '0.250', 'weight': '0.060'}
