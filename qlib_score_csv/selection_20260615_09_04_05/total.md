# params 
 {'predict_dates': [{'start': '2026-06-12', 'end': '2026-06-12'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260615_08 512551058650919066 (Recorders: 3/5)

	Recorder: b6277c9f580c40c58d38944bc6589de0

		Model: {'id': 'b6277c9f580c40c58d38944bc6589de0', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.009, 'ICIR': 0.053, 'Rank IC': 0.031, 'Rank ICIR': 0.195}, 'data_train_vec': ['2021-06-15', '2025-03-14'], 'train_time_vec': ['2026-06-15', '2026-06-15'], 'rank_icir': '0.195', 'weight': '0.043'}

	Recorder: 557e441f6be4450bbc5a0b48aec1be5a

		Model: {'id': '557e441f6be4450bbc5a0b48aec1be5a', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.014, 'ICIR': 0.119, 'Rank IC': 0.037, 'Rank ICIR': 0.231}, 'data_train_vec': ['2023-06-15', '2025-09-14'], 'train_time_vec': ['2026-06-15', '2026-06-15'], 'rank_icir': '0.231', 'weight': '0.051'}

	Recorder: 4269878a17414846a6b82e3a1fba2664

		Model: {'id': '4269878a17414846a6b82e3a1fba2664', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.008, 'ICIR': 0.083, 'Rank IC': 0.037, 'Rank ICIR': 0.36}, 'data_train_vec': ['2024-06-15', '2025-12-14'], 'train_time_vec': ['2026-06-15', '2026-06-15'], 'rank_icir': '0.360', 'weight': '0.080'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260615_08 432100274965659790 (Recorders: 4/5)

	Recorder: c22bf29ecaa241fabdc286ec8d3894fd

		Model: {'id': 'c22bf29ecaa241fabdc286ec8d3894fd', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.004, 'ICIR': 0.034, 'Rank IC': 0.024, 'Rank ICIR': 0.169}, 'data_train_vec': ['2021-06-15', '2025-03-14'], 'train_time_vec': ['2026-06-15', '2026-06-15'], 'rank_icir': '0.169', 'weight': '0.037'}

	Recorder: 8ddc697e0bb848139ca7d72a91623697

		Model: {'id': '8ddc697e0bb848139ca7d72a91623697', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.007, 'ICIR': 0.051, 'Rank IC': 0.039, 'Rank ICIR': 0.303}, 'data_train_vec': ['2022-06-15', '2025-06-14'], 'train_time_vec': ['2026-06-15', '2026-06-15'], 'rank_icir': '0.303', 'weight': '0.067'}

	Recorder: 5b0972ef6a3a46a7b58d2cb4988b83cb

		Model: {'id': '5b0972ef6a3a46a7b58d2cb4988b83cb', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.017, 'ICIR': 0.161, 'Rank IC': 0.035, 'Rank ICIR': 0.271}, 'data_train_vec': ['2023-06-15', '2025-09-14'], 'train_time_vec': ['2026-06-15', '2026-06-15'], 'rank_icir': '0.271', 'weight': '0.060'}

	Recorder: 4d2bfec645e94bcebeac570364ba4a73

		Model: {'id': '4d2bfec645e94bcebeac570364ba4a73', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.012, 'ICIR': 0.116, 'Rank IC': 0.023, 'Rank ICIR': 0.236}, 'data_train_vec': ['2024-06-15', '2025-12-14'], 'train_time_vec': ['2026-06-15', '2026-06-15'], 'rank_icir': '0.236', 'weight': '0.052'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260615_06 512740433237102291 (Recorders: 4/5)

	Recorder: 0ba3988c121e412e999491e03c283e85

		Model: {'id': '0ba3988c121e412e999491e03c283e85', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.026, 'ICIR': 0.174, 'Rank IC': 0.053, 'Rank ICIR': 0.353}, 'data_train_vec': ['2021-06-15', '2025-03-14'], 'train_time_vec': ['2026-06-15', '2026-06-15'], 'rank_icir': '0.353', 'weight': '0.078'}

	Recorder: c4dd62fa2a334431af19cca3ad237abd

		Model: {'id': 'c4dd62fa2a334431af19cca3ad237abd', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.026, 'ICIR': 0.169, 'Rank IC': 0.055, 'Rank ICIR': 0.326}, 'data_train_vec': ['2022-06-15', '2025-06-14'], 'train_time_vec': ['2026-06-15', '2026-06-15'], 'rank_icir': '0.326', 'weight': '0.072'}

	Recorder: cfd8a583339d44c59527961dbb2b560f

		Model: {'id': 'cfd8a583339d44c59527961dbb2b560f', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.018, 'ICIR': 0.14, 'Rank IC': 0.037, 'Rank ICIR': 0.258}, 'data_train_vec': ['2023-06-15', '2025-09-14'], 'train_time_vec': ['2026-06-15', '2026-06-15'], 'rank_icir': '0.258', 'weight': '0.057'}

	Recorder: a330d9a067704735ac79a1b05e1e216c

		Model: {'id': 'a330d9a067704735ac79a1b05e1e216c', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.004, 'ICIR': 0.034, 'Rank IC': 0.015, 'Rank ICIR': 0.156}, 'data_train_vec': ['2024-06-15', '2025-12-14'], 'train_time_vec': ['2026-06-15', '2026-06-15'], 'rank_icir': '0.156', 'weight': '0.035'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260615_06 296307465000984587 (Recorders: 4/5)

	Recorder: 4baad6e765c04c82b09d721d19534f66

		Model: {'id': '4baad6e765c04c82b09d721d19534f66', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.017, 'ICIR': 0.127, 'Rank IC': 0.045, 'Rank ICIR': 0.379}, 'data_train_vec': ['2021-06-15', '2025-03-14'], 'train_time_vec': ['2026-06-15', '2026-06-15'], 'rank_icir': '0.379', 'weight': '0.084'}

	Recorder: ebbcbe1494a64344a30d7dbf923aee94

		Model: {'id': 'ebbcbe1494a64344a30d7dbf923aee94', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.008, 'ICIR': 0.053, 'Rank IC': 0.044, 'Rank ICIR': 0.33}, 'data_train_vec': ['2022-06-15', '2025-06-14'], 'train_time_vec': ['2026-06-15', '2026-06-15'], 'rank_icir': '0.330', 'weight': '0.073'}

	Recorder: 308b20795397477fa54a6fc359baf00f

		Model: {'id': '308b20795397477fa54a6fc359baf00f', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.008, 'ICIR': 0.065, 'Rank IC': 0.034, 'Rank ICIR': 0.285}, 'data_train_vec': ['2023-06-15', '2025-09-14'], 'train_time_vec': ['2026-06-15', '2026-06-15'], 'rank_icir': '0.285', 'weight': '0.063'}

	Recorder: 7ad3a684d9e14c2686b4923fb79bc9b6

		Model: {'id': '7ad3a684d9e14c2686b4923fb79bc9b6', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.006, 'ICIR': 0.042, 'Rank IC': 0.015, 'Rank ICIR': 0.11}, 'data_train_vec': ['2024-06-15', '2025-12-14'], 'train_time_vec': ['2026-06-15', '2026-06-15'], 'rank_icir': '0.110', 'weight': '0.024'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260615_06 420629530516131922 (Recorders: 2/5)

	Recorder: ee8b517355a24376961b92271901c938

		Model: {'id': 'ee8b517355a24376961b92271901c938', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.007, 'ICIR': 0.047, 'Rank IC': 0.041, 'Rank ICIR': 0.253}, 'data_train_vec': ['2021-06-15', '2025-03-14'], 'train_time_vec': ['2026-06-15', '2026-06-15'], 'rank_icir': '0.253', 'weight': '0.056'}

	Recorder: 6eb64bd0ffac4a3cb2d806301ddbd92c

		Model: {'id': '6eb64bd0ffac4a3cb2d806301ddbd92c', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.02, 'ICIR': 0.15, 'Rank IC': 0.05, 'Rank ICIR': 0.296}, 'data_train_vec': ['2022-06-15', '2025-06-14'], 'train_time_vec': ['2026-06-15', '2026-06-15'], 'rank_icir': '0.296', 'weight': '0.066'}
