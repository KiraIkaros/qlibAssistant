# params 
 {'predict_dates': [{'start': '2026-09-03', 'end': '2026-09-03'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260903_18 106579192912153308 (Recorders: 3/5)

	Recorder: 0f2a89b25043409f82399b334300ed46

		Model: {'id': '0f2a89b25043409f82399b334300ed46', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.009, 'ICIR': 0.06, 'Rank IC': 0.025, 'Rank ICIR': 0.137}, 'data_train_vec': ['2021-09-03', '2025-06-02'], 'train_time_vec': ['2026-09-03', '2026-09-03'], 'rank_icir': '0.137', 'weight': '0.061'}

	Recorder: b2898ead8a4b4bdcbbe4fe4f7b850bb0

		Model: {'id': 'b2898ead8a4b4bdcbbe4fe4f7b850bb0', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.015, 'ICIR': 0.084, 'Rank IC': 0.025, 'Rank ICIR': 0.176}, 'data_train_vec': ['2022-09-03', '2025-09-02'], 'train_time_vec': ['2026-09-03', '2026-09-03'], 'rank_icir': '0.176', 'weight': '0.078'}

	Recorder: 27943a357cdf40b6877d0492396b0182

		Model: {'id': '27943a357cdf40b6877d0492396b0182', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.025, 'ICIR': 0.09, 'Rank IC': 0.018, 'Rank ICIR': 0.107}, 'data_train_vec': ['2023-09-03', '2025-12-02'], 'train_time_vec': ['2026-09-03', '2026-09-03'], 'rank_icir': '0.107', 'weight': '0.047'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260903_18 151039553956977172 (Recorders: 3/5)

	Recorder: f8fd554d9a38492ba8d59f949ff8a132

		Model: {'id': 'f8fd554d9a38492ba8d59f949ff8a132', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.009, 'ICIR': 0.064, 'Rank IC': 0.018, 'Rank ICIR': 0.121}, 'data_train_vec': ['2021-09-03', '2025-06-02'], 'train_time_vec': ['2026-09-03', '2026-09-03'], 'rank_icir': '0.121', 'weight': '0.054'}

	Recorder: 56c7f923dd564e8bae9e7032a6f41212

		Model: {'id': '56c7f923dd564e8bae9e7032a6f41212', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.016, 'ICIR': 0.138, 'Rank IC': 0.025, 'Rank ICIR': 0.229}, 'data_train_vec': ['2022-09-03', '2025-09-02'], 'train_time_vec': ['2026-09-03', '2026-09-03'], 'rank_icir': '0.229', 'weight': '0.101'}

	Recorder: 9decca58d50b405da268d76be7158e5c

		Model: {'id': '9decca58d50b405da268d76be7158e5c', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.01, 'ICIR': 0.052, 'Rank IC': 0.014, 'Rank ICIR': 0.083}, 'data_train_vec': ['2023-09-03', '2025-12-02'], 'train_time_vec': ['2026-09-03', '2026-09-03'], 'rank_icir': '0.083', 'weight': '0.037'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260903_16 131122921200012755 (Recorders: 4/5)

	Recorder: 6d293050268c4c3ebd07aaee74c1b4a7

		Model: {'id': '6d293050268c4c3ebd07aaee74c1b4a7', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.017, 'ICIR': 0.087, 'Rank IC': 0.027, 'Rank ICIR': 0.164}, 'data_train_vec': ['2021-09-03', '2025-06-02'], 'train_time_vec': ['2026-09-03', '2026-09-03'], 'rank_icir': '0.164', 'weight': '0.073'}

	Recorder: fe3462982b5f4fadb08d6c77a26d5e61

		Model: {'id': 'fe3462982b5f4fadb08d6c77a26d5e61', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.031, 'ICIR': 0.144, 'Rank IC': 0.042, 'Rank ICIR': 0.256}, 'data_train_vec': ['2022-09-03', '2025-09-02'], 'train_time_vec': ['2026-09-03', '2026-09-03'], 'rank_icir': '0.256', 'weight': '0.113'}

	Recorder: c0ae41295aad437f9d4f2e0892161294

		Model: {'id': 'c0ae41295aad437f9d4f2e0892161294', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.002, 'ICIR': 0.009, 'Rank IC': 0.008, 'Rank ICIR': 0.044}, 'data_train_vec': ['2023-09-03', '2025-12-02'], 'train_time_vec': ['2026-09-03', '2026-09-03'], 'rank_icir': '0.044', 'weight': '0.019'}

	Recorder: c51208b07462499ba8a1ebd1032704d0

		Model: {'id': 'c51208b07462499ba8a1ebd1032704d0', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.013, 'ICIR': 0.054, 'Rank IC': 0.001, 'Rank ICIR': 0.004}, 'data_train_vec': ['2025-09-03', '2026-06-02'], 'train_time_vec': ['2026-09-03', '2026-09-03'], 'rank_icir': '0.004', 'weight': '0.002'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260903_16 750002450499366563 (Recorders: 4/5)

	Recorder: 18055128241e4f97809a294bb0275935

		Model: {'id': '18055128241e4f97809a294bb0275935', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.021, 'ICIR': 0.101, 'Rank IC': 0.03, 'Rank ICIR': 0.179}, 'data_train_vec': ['2021-09-03', '2025-06-02'], 'train_time_vec': ['2026-09-03', '2026-09-03'], 'rank_icir': '0.179', 'weight': '0.079'}

	Recorder: cfbca044eb674131bcbde5d29da9bab3

		Model: {'id': 'cfbca044eb674131bcbde5d29da9bab3', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.04, 'ICIR': 0.21, 'Rank IC': 0.039, 'Rank ICIR': 0.242}, 'data_train_vec': ['2022-09-03', '2025-09-02'], 'train_time_vec': ['2026-09-03', '2026-09-03'], 'rank_icir': '0.242', 'weight': '0.107'}

	Recorder: 037c895fd687496699c258312baf3c1f

		Model: {'id': '037c895fd687496699c258312baf3c1f', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.009, 'ICIR': 0.027, 'Rank IC': 0.003, 'Rank ICIR': 0.01}, 'data_train_vec': ['2024-09-03', '2026-03-02'], 'train_time_vec': ['2026-09-03', '2026-09-03'], 'rank_icir': '0.010', 'weight': '0.004'}

	Recorder: 383ee2be448a4ede8218a102a85986a9

		Model: {'id': '383ee2be448a4ede8218a102a85986a9', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.072, 'ICIR': 0.358, 'Rank IC': 0.048, 'Rank ICIR': 0.263}, 'data_train_vec': ['2025-09-03', '2026-06-02'], 'train_time_vec': ['2026-09-03', '2026-09-03'], 'rank_icir': '0.263', 'weight': '0.116'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260903_16 646448731750569746 (Recorders: 1/5)

	Recorder: f03b06acfad24d9e981187312928295e

		Model: {'id': 'f03b06acfad24d9e981187312928295e', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.006, 'ICIR': 0.026, 'Rank IC': 0.037, 'Rank ICIR': 0.245}, 'data_train_vec': ['2022-09-03', '2025-09-02'], 'train_time_vec': ['2026-09-03', '2026-09-03'], 'rank_icir': '0.245', 'weight': '0.108'}
