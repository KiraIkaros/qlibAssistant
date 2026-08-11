# params 
 {'predict_dates': [{'start': '2026-08-11', 'end': '2026-08-11'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260811_15 380984875167197321 (Recorders: 3/5)

	Recorder: 6a845f35ea754d5eb6776970782f0d5b

		Model: {'id': '6a845f35ea754d5eb6776970782f0d5b', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.001, 'ICIR': 0.008, 'Rank IC': 0.018, 'Rank ICIR': 0.135}, 'data_train_vec': ['2021-08-11', '2025-05-10'], 'train_time_vec': ['2026-08-11', '2026-08-11'], 'rank_icir': '0.135', 'weight': '0.127'}

	Recorder: 8a3692c246c343e98e44dd1cbef2c9df

		Model: {'id': '8a3692c246c343e98e44dd1cbef2c9df', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.014, 'ICIR': 0.124, 'Rank IC': 0.018, 'Rank ICIR': 0.147}, 'data_train_vec': ['2022-08-11', '2025-08-10'], 'train_time_vec': ['2026-08-11', '2026-08-11'], 'rank_icir': '0.147', 'weight': '0.139'}

	Recorder: 2d7dd17b7da94cf2a5b06fbf7f4feb6c

		Model: {'id': '2d7dd17b7da94cf2a5b06fbf7f4feb6c', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.015, 'ICIR': 0.081, 'Rank IC': 0.019, 'Rank ICIR': 0.152}, 'data_train_vec': ['2023-08-11', '2025-11-10'], 'train_time_vec': ['2026-08-11', '2026-08-11'], 'rank_icir': '0.152', 'weight': '0.143'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260811_13 605822129785953274 (Recorders: 2/5)

	Recorder: 8bd6a6390fae40058881aa178b0f0fae

		Model: {'id': '8bd6a6390fae40058881aa178b0f0fae', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.016, 'ICIR': 0.084, 'Rank IC': 0.032, 'Rank ICIR': 0.183}, 'data_train_vec': ['2021-08-11', '2025-05-10'], 'train_time_vec': ['2026-08-11', '2026-08-11'], 'rank_icir': '0.183', 'weight': '0.172'}

	Recorder: 1aeb53da92304a53a89fccd40c0e155d

		Model: {'id': '1aeb53da92304a53a89fccd40c0e155d', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.015, 'ICIR': 0.075, 'Rank IC': 0.025, 'Rank ICIR': 0.14}, 'data_train_vec': ['2022-08-11', '2025-08-10'], 'train_time_vec': ['2026-08-11', '2026-08-11'], 'rank_icir': '0.140', 'weight': '0.132'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260811_13 463484125539177740 (Recorders: 2/5)

	Recorder: 0433c02c61ed49e1b797b51dfd0de749

		Model: {'id': '0433c02c61ed49e1b797b51dfd0de749', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.009, 'ICIR': 0.044, 'Rank IC': 0.024, 'Rank ICIR': 0.148}, 'data_train_vec': ['2021-08-11', '2025-05-10'], 'train_time_vec': ['2026-08-11', '2026-08-11'], 'rank_icir': '0.148', 'weight': '0.139'}

	Recorder: 55a14a40a3614f9e9ce3102e4ae52023

		Model: {'id': '55a14a40a3614f9e9ce3102e4ae52023', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.018, 'ICIR': 0.087, 'Rank IC': 0.026, 'Rank ICIR': 0.156}, 'data_train_vec': ['2022-08-11', '2025-08-10'], 'train_time_vec': ['2026-08-11', '2026-08-11'], 'rank_icir': '0.156', 'weight': '0.147'}
