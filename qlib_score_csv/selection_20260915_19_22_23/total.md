# params 
 {'predict_dates': [{'start': '2026-09-15', 'end': '2026-09-15'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260915_18 886565807115217842 (Recorders: 2/5)

	Recorder: 9ec262c699bc4cafb14e508584f6db27

		Model: {'id': '9ec262c699bc4cafb14e508584f6db27', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.033, 'ICIR': 0.137, 'Rank IC': 0.045, 'Rank ICIR': 0.278}, 'data_train_vec': ['2022-09-15', '2025-09-14'], 'train_time_vec': ['2026-09-15', '2026-09-15'], 'rank_icir': '0.278', 'weight': '0.105'}

	Recorder: bdb56e436f484ea38d68de94c6424f2a

		Model: {'id': 'bdb56e436f484ea38d68de94c6424f2a', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.011, 'ICIR': 0.04, 'Rank IC': 0.021, 'Rank ICIR': 0.121}, 'data_train_vec': ['2023-09-15', '2025-12-14'], 'train_time_vec': ['2026-09-15', '2026-09-15'], 'rank_icir': '0.121', 'weight': '0.046'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260915_18 845447177976489071 (Recorders: 4/5)

	Recorder: 17d6b99a7d0649fea7ebac873bf423eb

		Model: {'id': '17d6b99a7d0649fea7ebac873bf423eb', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.019, 'ICIR': 0.118, 'Rank IC': 0.029, 'Rank ICIR': 0.195}, 'data_train_vec': ['2021-09-15', '2025-06-14'], 'train_time_vec': ['2026-09-15', '2026-09-15'], 'rank_icir': '0.195', 'weight': '0.073'}

	Recorder: 96a3c8415f8f4c93ad93e11bf20f369f

		Model: {'id': '96a3c8415f8f4c93ad93e11bf20f369f', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.028, 'ICIR': 0.16, 'Rank IC': 0.04, 'Rank ICIR': 0.273}, 'data_train_vec': ['2022-09-15', '2025-09-14'], 'train_time_vec': ['2026-09-15', '2026-09-15'], 'rank_icir': '0.273', 'weight': '0.103'}

	Recorder: 594e3b56371a4c2fb77c3ac627d482ae

		Model: {'id': '594e3b56371a4c2fb77c3ac627d482ae', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.005, 'ICIR': 0.029, 'Rank IC': 0.004, 'Rank ICIR': 0.028}, 'data_train_vec': ['2023-09-15', '2025-12-14'], 'train_time_vec': ['2026-09-15', '2026-09-15'], 'rank_icir': '0.028', 'weight': '0.011'}

	Recorder: 946bc8c8e6744646852c452598303147

		Model: {'id': '946bc8c8e6744646852c452598303147', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.022, 'ICIR': 0.08, 'Rank IC': 0.006, 'Rank ICIR': 0.03}, 'data_train_vec': ['2024-09-15', '2026-03-14'], 'train_time_vec': ['2026-09-15', '2026-09-15'], 'rank_icir': '0.030', 'weight': '0.011'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260915_17 946843876222023005 (Recorders: 4/5)

	Recorder: b873c97733b44815ab3c855a1d23a61a

		Model: {'id': 'b873c97733b44815ab3c855a1d23a61a', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.033, 'ICIR': 0.167, 'Rank IC': 0.044, 'Rank ICIR': 0.263}, 'data_train_vec': ['2021-09-15', '2025-06-14'], 'train_time_vec': ['2026-09-15', '2026-09-15'], 'rank_icir': '0.263', 'weight': '0.099'}

	Recorder: 6c46827673384a56a2233952fd3f5efc

		Model: {'id': '6c46827673384a56a2233952fd3f5efc', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.035, 'ICIR': 0.157, 'Rank IC': 0.044, 'Rank ICIR': 0.261}, 'data_train_vec': ['2022-09-15', '2025-09-14'], 'train_time_vec': ['2026-09-15', '2026-09-15'], 'rank_icir': '0.261', 'weight': '0.098'}

	Recorder: 85b3eb8b81fb47d58941ea2be6cf7bc8

		Model: {'id': '85b3eb8b81fb47d58941ea2be6cf7bc8', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.014, 'ICIR': 0.053, 'Rank IC': 0.019, 'Rank ICIR': 0.1}, 'data_train_vec': ['2023-09-15', '2025-12-14'], 'train_time_vec': ['2026-09-15', '2026-09-15'], 'rank_icir': '0.100', 'weight': '0.038'}

	Recorder: 482c4433851b4cfd860126a84e791065

		Model: {'id': '482c4433851b4cfd860126a84e791065', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.018, 'ICIR': 0.067, 'Rank IC': 0.002, 'Rank ICIR': 0.008}, 'data_train_vec': ['2024-09-15', '2026-03-14'], 'train_time_vec': ['2026-09-15', '2026-09-15'], 'rank_icir': '0.008', 'weight': '0.003'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260915_16 884478951429600330 (Recorders: 5/5)

	Recorder: f7aa059c495d4382a6b659c4a64a372d

		Model: {'id': 'f7aa059c495d4382a6b659c4a64a372d', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.03, 'ICIR': 0.149, 'Rank IC': 0.039, 'Rank ICIR': 0.236}, 'data_train_vec': ['2021-09-15', '2025-06-14'], 'train_time_vec': ['2026-09-15', '2026-09-15'], 'rank_icir': '0.236', 'weight': '0.089'}

	Recorder: b5804a2136e24355b8c0dcadc5cf6438

		Model: {'id': 'b5804a2136e24355b8c0dcadc5cf6438', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.034, 'ICIR': 0.168, 'Rank IC': 0.029, 'Rank ICIR': 0.171}, 'data_train_vec': ['2022-09-15', '2025-09-14'], 'train_time_vec': ['2026-09-15', '2026-09-15'], 'rank_icir': '0.171', 'weight': '0.064'}

	Recorder: 5cf115f192824c2b80760e95b2da8820

		Model: {'id': '5cf115f192824c2b80760e95b2da8820', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.005, 'ICIR': 0.019, 'Rank IC': 0.002, 'Rank ICIR': 0.011}, 'data_train_vec': ['2023-09-15', '2025-12-14'], 'train_time_vec': ['2026-09-15', '2026-09-15'], 'rank_icir': '0.011', 'weight': '0.004'}

	Recorder: c239f07e15384d7d8576f3d55e8f91b1

		Model: {'id': 'c239f07e15384d7d8576f3d55e8f91b1', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.046, 'ICIR': 0.159, 'Rank IC': 0.03, 'Rank ICIR': 0.121}, 'data_train_vec': ['2024-09-15', '2026-03-14'], 'train_time_vec': ['2026-09-15', '2026-09-15'], 'rank_icir': '0.121', 'weight': '0.046'}

	Recorder: f6982bfc1bb3477aafdb2cb9aa887dff

		Model: {'id': 'f6982bfc1bb3477aafdb2cb9aa887dff', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.027, 'ICIR': 0.138, 'Rank IC': 0.014, 'Rank ICIR': 0.073}, 'data_train_vec': ['2025-09-15', '2026-06-14'], 'train_time_vec': ['2026-09-15', '2026-09-15'], 'rank_icir': '0.073', 'weight': '0.027'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260915_16 756613876832955441 (Recorders: 2/5)

	Recorder: 1a720e645fc046f59c6ff9afed17bca7

		Model: {'id': '1a720e645fc046f59c6ff9afed17bca7', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.02, 'ICIR': 0.096, 'Rank IC': 0.047, 'Rank ICIR': 0.285}, 'data_train_vec': ['2021-09-15', '2025-06-14'], 'train_time_vec': ['2026-09-15', '2026-09-15'], 'rank_icir': '0.285', 'weight': '0.107'}

	Recorder: d82bc7e4e161493b9912d4d47f5ebb66

		Model: {'id': 'd82bc7e4e161493b9912d4d47f5ebb66', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.002, 'ICIR': 0.01, 'Rank IC': 0.033, 'Rank ICIR': 0.204}, 'data_train_vec': ['2022-09-15', '2025-09-14'], 'train_time_vec': ['2026-09-15', '2026-09-15'], 'rank_icir': '0.204', 'weight': '0.077'}
