# params 
 {'predict_dates': [{'start': '2026-06-18', 'end': '2026-06-18'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260621_16 163852147593323941 (Recorders: 3/5)

	Recorder: d82dce52e2f44612a19999ee16e60bd5

		Model: {'id': 'd82dce52e2f44612a19999ee16e60bd5', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.007, 'ICIR': 0.063, 'Rank IC': 0.028, 'Rank ICIR': 0.207}, 'data_train_vec': ['2022-06-21', '2025-06-20'], 'train_time_vec': ['2026-06-21', '2026-06-21'], 'rank_icir': '0.207', 'weight': '0.047'}

	Recorder: 0139f78d011f4169826038472b7319e8

		Model: {'id': '0139f78d011f4169826038472b7319e8', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.029, 'ICIR': 0.231, 'Rank IC': 0.037, 'Rank ICIR': 0.263}, 'data_train_vec': ['2023-06-21', '2025-09-20'], 'train_time_vec': ['2026-06-21', '2026-06-21'], 'rank_icir': '0.263', 'weight': '0.060'}

	Recorder: 3c16af51b9ab43e6a3fa2b1a91d15b04

		Model: {'id': '3c16af51b9ab43e6a3fa2b1a91d15b04', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.052, 'ICIR': 0.525, 'Rank IC': 0.049, 'Rank ICIR': 0.53}, 'data_train_vec': ['2024-06-21', '2025-12-20'], 'train_time_vec': ['2026-06-21', '2026-06-21'], 'rank_icir': '0.530', 'weight': '0.120'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260621_16 274506494405118327 (Recorders: 5/5)

	Recorder: 575f6cd3af504f6daa3b87aba758c36e

		Model: {'id': '575f6cd3af504f6daa3b87aba758c36e', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.01, 'ICIR': 0.066, 'Rank IC': 0.031, 'Rank ICIR': 0.18}, 'data_train_vec': ['2021-06-21', '2025-03-20'], 'train_time_vec': ['2026-06-21', '2026-06-21'], 'rank_icir': '0.180', 'weight': '0.041'}

	Recorder: 01533a8a5981498ba567be7863959d2e

		Model: {'id': '01533a8a5981498ba567be7863959d2e', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.006, 'ICIR': 0.041, 'Rank IC': 0.034, 'Rank ICIR': 0.218}, 'data_train_vec': ['2022-06-21', '2025-06-20'], 'train_time_vec': ['2026-06-21', '2026-06-21'], 'rank_icir': '0.218', 'weight': '0.049'}

	Recorder: 4c54846024954a25b899309bbe7f649c

		Model: {'id': '4c54846024954a25b899309bbe7f649c', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.029, 'ICIR': 0.246, 'Rank IC': 0.039, 'Rank ICIR': 0.303}, 'data_train_vec': ['2023-06-21', '2025-09-20'], 'train_time_vec': ['2026-06-21', '2026-06-21'], 'rank_icir': '0.303', 'weight': '0.069'}

	Recorder: 1d71f51255e745218391a9743291fb20

		Model: {'id': '1d71f51255e745218391a9743291fb20', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.043, 'ICIR': 0.321, 'Rank IC': 0.03, 'Rank ICIR': 0.257}, 'data_train_vec': ['2024-06-21', '2025-12-20'], 'train_time_vec': ['2026-06-21', '2026-06-21'], 'rank_icir': '0.257', 'weight': '0.058'}

	Recorder: 2f2fa3841e474dea9dc5bebae51d5518

		Model: {'id': '2f2fa3841e474dea9dc5bebae51d5518', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.045, 'ICIR': 0.166, 'Rank IC': 0.012, 'Rank ICIR': 0.047}, 'data_train_vec': ['2025-06-21', '2026-03-20'], 'train_time_vec': ['2026-06-21', '2026-06-21'], 'rank_icir': '0.047', 'weight': '0.011'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260621_14 112691997024081596 (Recorders: 4/5)

	Recorder: ae70ef8b08bb4362b09d9be53a9d3ae4

		Model: {'id': 'ae70ef8b08bb4362b09d9be53a9d3ae4', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.018, 'ICIR': 0.108, 'Rank IC': 0.048, 'Rank ICIR': 0.295}, 'data_train_vec': ['2021-06-21', '2025-03-20'], 'train_time_vec': ['2026-06-21', '2026-06-21'], 'rank_icir': '0.295', 'weight': '0.067'}

	Recorder: d75b9d81407b4e32b6ab5b2a12794032

		Model: {'id': 'd75b9d81407b4e32b6ab5b2a12794032', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.016, 'ICIR': 0.099, 'Rank IC': 0.05, 'Rank ICIR': 0.292}, 'data_train_vec': ['2022-06-21', '2025-06-20'], 'train_time_vec': ['2026-06-21', '2026-06-21'], 'rank_icir': '0.292', 'weight': '0.066'}

	Recorder: 3f078818519348579473a3945070d41d

		Model: {'id': '3f078818519348579473a3945070d41d', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.029, 'ICIR': 0.208, 'Rank IC': 0.039, 'Rank ICIR': 0.272}, 'data_train_vec': ['2023-06-21', '2025-09-20'], 'train_time_vec': ['2026-06-21', '2026-06-21'], 'rank_icir': '0.272', 'weight': '0.062'}

	Recorder: 0afab97ea5004ce8870a8fbc5b8785ba

		Model: {'id': '0afab97ea5004ce8870a8fbc5b8785ba', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.026, 'ICIR': 0.188, 'Rank IC': 0.028, 'Rank ICIR': 0.224}, 'data_train_vec': ['2024-06-21', '2025-12-20'], 'train_time_vec': ['2026-06-21', '2026-06-21'], 'rank_icir': '0.224', 'weight': '0.051'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260621_14 474831336512613255 (Recorders: 3/5)

	Recorder: 7a24c379749342b18838558f342f55f4

		Model: {'id': '7a24c379749342b18838558f342f55f4', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.003, 'ICIR': 0.022, 'Rank IC': 0.036, 'Rank ICIR': 0.279}, 'data_train_vec': ['2021-06-21', '2025-03-20'], 'train_time_vec': ['2026-06-21', '2026-06-21'], 'rank_icir': '0.279', 'weight': '0.063'}

	Recorder: 01d987fe0cc746489048335dd071e1c8

		Model: {'id': '01d987fe0cc746489048335dd071e1c8', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.006, 'ICIR': 0.047, 'Rank IC': 0.023, 'Rank ICIR': 0.181}, 'data_train_vec': ['2023-06-21', '2025-09-20'], 'train_time_vec': ['2026-06-21', '2026-06-21'], 'rank_icir': '0.181', 'weight': '0.041'}

	Recorder: b281e16d47124b05b9b7155c3ba4750f

		Model: {'id': 'b281e16d47124b05b9b7155c3ba4750f', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.027, 'ICIR': 0.162, 'Rank IC': 0.022, 'Rank ICIR': 0.136}, 'data_train_vec': ['2024-06-21', '2025-12-20'], 'train_time_vec': ['2026-06-21', '2026-06-21'], 'rank_icir': '0.136', 'weight': '0.031'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260621_14 467056942662856326 (Recorders: 2/5)

	Recorder: 4f4bab676cad46d8b006b782feaa77cc

		Model: {'id': '4f4bab676cad46d8b006b782feaa77cc', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.003, 'ICIR': 0.02, 'Rank IC': 0.045, 'Rank ICIR': 0.268}, 'data_train_vec': ['2022-06-21', '2025-06-20'], 'train_time_vec': ['2026-06-21', '2026-06-21'], 'rank_icir': '0.268', 'weight': '0.061'}

	Recorder: 40172d5b76274ca8aa02b9300db18745

		Model: {'id': '40172d5b76274ca8aa02b9300db18745', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.032, 'ICIR': 0.301, 'Rank IC': 0.046, 'Rank ICIR': 0.465}, 'data_train_vec': ['2024-06-21', '2025-12-20'], 'train_time_vec': ['2026-06-21', '2026-06-21'], 'rank_icir': '0.465', 'weight': '0.105'}
