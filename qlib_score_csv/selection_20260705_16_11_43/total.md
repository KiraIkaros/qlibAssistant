# params 
 {'predict_dates': [{'start': '2026-07-03', 'end': '2026-07-03'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260705_15 747256245741621733 (Recorders: 3/5)

	Recorder: 86eff2fe496e4db998e6bf68b86eb953

		Model: {'id': '86eff2fe496e4db998e6bf68b86eb953', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.003, 'ICIR': 0.031, 'Rank IC': 0.024, 'Rank ICIR': 0.178}, 'data_train_vec': ['2022-07-05', '2025-07-04'], 'train_time_vec': ['2026-07-05', '2026-07-05'], 'rank_icir': '0.178', 'weight': '0.066'}

	Recorder: a9d534edc0be4fc99d45c0f49c00c523

		Model: {'id': 'a9d534edc0be4fc99d45c0f49c00c523', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.024, 'ICIR': 0.196, 'Rank IC': 0.022, 'Rank ICIR': 0.198}, 'data_train_vec': ['2023-07-05', '2025-10-04'], 'train_time_vec': ['2026-07-05', '2026-07-05'], 'rank_icir': '0.198', 'weight': '0.073'}

	Recorder: 1c086218e56b4133bf419c2b7b2e1181

		Model: {'id': '1c086218e56b4133bf419c2b7b2e1181', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.025, 'ICIR': 0.191, 'Rank IC': 0.011, 'Rank ICIR': 0.098}, 'data_train_vec': ['2024-07-05', '2026-01-04'], 'train_time_vec': ['2026-07-05', '2026-07-05'], 'rank_icir': '0.098', 'weight': '0.036'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260705_15 801816017860396588 (Recorders: 4/5)

	Recorder: 8e634bcd6734435ab362f7bde5d8c4dd

		Model: {'id': '8e634bcd6734435ab362f7bde5d8c4dd', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.002, 'ICIR': 0.012, 'Rank IC': 0.03, 'Rank ICIR': 0.22}, 'data_train_vec': ['2022-07-05', '2025-07-04'], 'train_time_vec': ['2026-07-05', '2026-07-05'], 'rank_icir': '0.220', 'weight': '0.082'}

	Recorder: 1ca7f6a52ecd4f55bb142564c32ff8e7

		Model: {'id': '1ca7f6a52ecd4f55bb142564c32ff8e7', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.024, 'ICIR': 0.219, 'Rank IC': 0.03, 'Rank ICIR': 0.243}, 'data_train_vec': ['2023-07-05', '2025-10-04'], 'train_time_vec': ['2026-07-05', '2026-07-05'], 'rank_icir': '0.243', 'weight': '0.090'}

	Recorder: 8a757699892a4345a04518375a06b35d

		Model: {'id': '8a757699892a4345a04518375a06b35d', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.031, 'ICIR': 0.231, 'Rank IC': 0.027, 'Rank ICIR': 0.211}, 'data_train_vec': ['2024-07-05', '2026-01-04'], 'train_time_vec': ['2026-07-05', '2026-07-05'], 'rank_icir': '0.211', 'weight': '0.078'}

	Recorder: 884bb146971f43ed81f6506e476a8852

		Model: {'id': '884bb146971f43ed81f6506e476a8852', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.055, 'ICIR': 0.218, 'Rank IC': 0.034, 'Rank ICIR': 0.14}, 'data_train_vec': ['2025-07-05', '2026-04-04'], 'train_time_vec': ['2026-07-05', '2026-07-05'], 'rank_icir': '0.140', 'weight': '0.052'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260705_14 646023172482735075 (Recorders: 4/5)

	Recorder: 0ab49960c880412b8387cc7115659dcf

		Model: {'id': '0ab49960c880412b8387cc7115659dcf', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.008, 'ICIR': 0.05, 'Rank IC': 0.041, 'Rank ICIR': 0.242}, 'data_train_vec': ['2021-07-05', '2025-04-04'], 'train_time_vec': ['2026-07-05', '2026-07-05'], 'rank_icir': '0.242', 'weight': '0.090'}

	Recorder: 3cfb5554f73347c29f4bc66a0699ffe8

		Model: {'id': '3cfb5554f73347c29f4bc66a0699ffe8', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.023, 'ICIR': 0.149, 'Rank IC': 0.045, 'Rank ICIR': 0.273}, 'data_train_vec': ['2022-07-05', '2025-07-04'], 'train_time_vec': ['2026-07-05', '2026-07-05'], 'rank_icir': '0.273', 'weight': '0.101'}

	Recorder: 20b81a9ba43f43b0b6e54c7d53e9fff6

		Model: {'id': '20b81a9ba43f43b0b6e54c7d53e9fff6', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.021, 'ICIR': 0.162, 'Rank IC': 0.031, 'Rank ICIR': 0.247}, 'data_train_vec': ['2023-07-05', '2025-10-04'], 'train_time_vec': ['2026-07-05', '2026-07-05'], 'rank_icir': '0.247', 'weight': '0.092'}

	Recorder: 5d80b73135c24cc495050cc60f59fa43

		Model: {'id': '5d80b73135c24cc495050cc60f59fa43', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.033, 'ICIR': 0.166, 'Rank IC': 0.018, 'Rank ICIR': 0.092}, 'data_train_vec': ['2025-07-05', '2026-04-04'], 'train_time_vec': ['2026-07-05', '2026-07-05'], 'rank_icir': '0.092', 'weight': '0.034'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260705_14 367124975371901871 (Recorders: 2/5)

	Recorder: 3455180d80224c8f83486bc852612299

		Model: {'id': '3455180d80224c8f83486bc852612299', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.006, 'ICIR': 0.045, 'Rank IC': 0.018, 'Rank ICIR': 0.131}, 'data_train_vec': ['2023-07-05', '2025-10-04'], 'train_time_vec': ['2026-07-05', '2026-07-05'], 'rank_icir': '0.131', 'weight': '0.049'}

	Recorder: d5eb33b16460469885a079b2e538573d

		Model: {'id': 'd5eb33b16460469885a079b2e538573d', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.04, 'ICIR': 0.175, 'Rank IC': 0.016, 'Rank ICIR': 0.081}, 'data_train_vec': ['2025-07-05', '2026-04-04'], 'train_time_vec': ['2026-07-05', '2026-07-05'], 'rank_icir': '0.081', 'weight': '0.030'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260705_14 249979907400488545 (Recorders: 2/5)

	Recorder: 65af4c871a1a4767b1047aaecbb9fa1e

		Model: {'id': '65af4c871a1a4767b1047aaecbb9fa1e', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.007, 'ICIR': 0.056, 'Rank IC': 0.035, 'Rank ICIR': 0.224}, 'data_train_vec': ['2022-07-05', '2025-07-04'], 'train_time_vec': ['2026-07-05', '2026-07-05'], 'rank_icir': '0.224', 'weight': '0.083'}

	Recorder: 91043e88c4384bd5b7dab8a910cf22e8

		Model: {'id': '91043e88c4384bd5b7dab8a910cf22e8', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.008, 'ICIR': 0.064, 'Rank IC': 0.014, 'Rank ICIR': 0.12}, 'data_train_vec': ['2024-07-05', '2026-01-04'], 'train_time_vec': ['2026-07-05', '2026-07-05'], 'rank_icir': '0.120', 'weight': '0.044'}
