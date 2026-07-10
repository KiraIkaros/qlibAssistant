# params 
 {'predict_dates': [{'start': '2026-07-03', 'end': '2026-07-03'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260710_17 652049745330591298 (Recorders: 5/5)

	Recorder: 4c4dfa603edf4abcb5baaddb649d1ba4

		Model: {'id': '4c4dfa603edf4abcb5baaddb649d1ba4', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.009, 'ICIR': 0.062, 'Rank IC': 0.027, 'Rank ICIR': 0.152}, 'data_train_vec': ['2021-07-10', '2025-04-09'], 'train_time_vec': ['2026-07-10', '2026-07-10'], 'rank_icir': '0.152', 'weight': '0.038'}

	Recorder: f3c221b716f0435bbbc778b19179c0ad

		Model: {'id': 'f3c221b716f0435bbbc778b19179c0ad', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.008, 'ICIR': 0.064, 'Rank IC': 0.029, 'Rank ICIR': 0.16}, 'data_train_vec': ['2022-07-10', '2025-07-09'], 'train_time_vec': ['2026-07-10', '2026-07-10'], 'rank_icir': '0.160', 'weight': '0.040'}

	Recorder: 71fcc1d920d941d3bca9275261645a9d

		Model: {'id': '71fcc1d920d941d3bca9275261645a9d', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.043, 'ICIR': 0.372, 'Rank IC': 0.047, 'Rank ICIR': 0.374}, 'data_train_vec': ['2023-07-10', '2025-10-09'], 'train_time_vec': ['2026-07-10', '2026-07-10'], 'rank_icir': '0.374', 'weight': '0.093'}

	Recorder: 7d79f098817947dca2aa4383e8615627

		Model: {'id': '7d79f098817947dca2aa4383e8615627', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.03, 'ICIR': 0.247, 'Rank IC': 0.028, 'Rank ICIR': 0.266}, 'data_train_vec': ['2024-07-10', '2026-01-09'], 'train_time_vec': ['2026-07-10', '2026-07-10'], 'rank_icir': '0.266', 'weight': '0.066'}

	Recorder: e1cce4c5756c4c19be72bb449fb382a3

		Model: {'id': 'e1cce4c5756c4c19be72bb449fb382a3', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.056, 'ICIR': 0.272, 'Rank IC': 0.042, 'Rank ICIR': 0.201}, 'data_train_vec': ['2025-07-10', '2026-04-09'], 'train_time_vec': ['2026-07-10', '2026-07-10'], 'rank_icir': '0.201', 'weight': '0.050'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260710_17 427057209348926802 (Recorders: 5/5)

	Recorder: 84226d42d9f445bba96a77e6f4b0162f

		Model: {'id': '84226d42d9f445bba96a77e6f4b0162f', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.003, 'ICIR': 0.02, 'Rank IC': 0.021, 'Rank ICIR': 0.112}, 'data_train_vec': ['2021-07-10', '2025-04-09'], 'train_time_vec': ['2026-07-10', '2026-07-10'], 'rank_icir': '0.112', 'weight': '0.028'}

	Recorder: 836e8c64f5764e93843f911f311b261f

		Model: {'id': '836e8c64f5764e93843f911f311b261f', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.008, 'ICIR': 0.056, 'Rank IC': 0.03, 'Rank ICIR': 0.196}, 'data_train_vec': ['2022-07-10', '2025-07-09'], 'train_time_vec': ['2026-07-10', '2026-07-10'], 'rank_icir': '0.196', 'weight': '0.049'}

	Recorder: 1b0425ff9b2343e38f46b25db711b00f

		Model: {'id': '1b0425ff9b2343e38f46b25db711b00f', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.037, 'ICIR': 0.332, 'Rank IC': 0.031, 'Rank ICIR': 0.314}, 'data_train_vec': ['2023-07-10', '2025-10-09'], 'train_time_vec': ['2026-07-10', '2026-07-10'], 'rank_icir': '0.314', 'weight': '0.078'}

	Recorder: 2bad00d54be84a3c917b803104ac6a62

		Model: {'id': '2bad00d54be84a3c917b803104ac6a62', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.015, 'ICIR': 0.114, 'Rank IC': 0.013, 'Rank ICIR': 0.097}, 'data_train_vec': ['2024-07-10', '2026-01-09'], 'train_time_vec': ['2026-07-10', '2026-07-10'], 'rank_icir': '0.097', 'weight': '0.024'}

	Recorder: 8c941a8be404489abd74093225ce90b8

		Model: {'id': '8c941a8be404489abd74093225ce90b8', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.069, 'ICIR': 0.267, 'Rank IC': 0.056, 'Rank ICIR': 0.226}, 'data_train_vec': ['2025-07-10', '2026-04-09'], 'train_time_vec': ['2026-07-10', '2026-07-10'], 'rank_icir': '0.226', 'weight': '0.056'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260710_15 901797203521797592 (Recorders: 4/5)

	Recorder: 094a72f471f2442586a8ffc9dfd8f5b2

		Model: {'id': '094a72f471f2442586a8ffc9dfd8f5b2', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.011, 'ICIR': 0.062, 'Rank IC': 0.042, 'Rank ICIR': 0.247}, 'data_train_vec': ['2021-07-10', '2025-04-09'], 'train_time_vec': ['2026-07-10', '2026-07-10'], 'rank_icir': '0.247', 'weight': '0.061'}

	Recorder: 60916d28292348f6a3599caea796faa0

		Model: {'id': '60916d28292348f6a3599caea796faa0', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.023, 'ICIR': 0.152, 'Rank IC': 0.046, 'Rank ICIR': 0.294}, 'data_train_vec': ['2022-07-10', '2025-07-09'], 'train_time_vec': ['2026-07-10', '2026-07-10'], 'rank_icir': '0.294', 'weight': '0.073'}

	Recorder: 50d5381c92784c1695311e59ea71b30f

		Model: {'id': '50d5381c92784c1695311e59ea71b30f', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.036, 'ICIR': 0.272, 'Rank IC': 0.043, 'Rank ICIR': 0.333}, 'data_train_vec': ['2023-07-10', '2025-10-09'], 'train_time_vec': ['2026-07-10', '2026-07-10'], 'rank_icir': '0.333', 'weight': '0.083'}

	Recorder: 97bb88a9f64441b983e09da9a841b901

		Model: {'id': '97bb88a9f64441b983e09da9a841b901', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.035, 'ICIR': 0.158, 'Rank IC': 0.03, 'Rank ICIR': 0.141}, 'data_train_vec': ['2025-07-10', '2026-04-09'], 'train_time_vec': ['2026-07-10', '2026-07-10'], 'rank_icir': '0.141', 'weight': '0.035'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260710_14 152403534860963617 (Recorders: 2/5)

	Recorder: 2813f65ef50c439da2a32e4b54d4919c

		Model: {'id': '2813f65ef50c439da2a32e4b54d4919c', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.015, 'ICIR': 0.106, 'Rank IC': 0.026, 'Rank ICIR': 0.189}, 'data_train_vec': ['2023-07-10', '2025-10-09'], 'train_time_vec': ['2026-07-10', '2026-07-10'], 'rank_icir': '0.189', 'weight': '0.047'}

	Recorder: c95ed2f57b424b4bad1c56eda07994cb

		Model: {'id': 'c95ed2f57b424b4bad1c56eda07994cb', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.065, 'ICIR': 0.332, 'Rank IC': 0.046, 'Rank ICIR': 0.27}, 'data_train_vec': ['2025-07-10', '2026-04-09'], 'train_time_vec': ['2026-07-10', '2026-07-10'], 'rank_icir': '0.270', 'weight': '0.067'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260710_14 516050229956493796 (Recorders: 2/5)

	Recorder: 4b7f4f4d397d419aabc68541afa0376d

		Model: {'id': '4b7f4f4d397d419aabc68541afa0376d', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.009, 'ICIR': 0.062, 'Rank IC': 0.043, 'Rank ICIR': 0.269}, 'data_train_vec': ['2022-07-10', '2025-07-09'], 'train_time_vec': ['2026-07-10', '2026-07-10'], 'rank_icir': '0.269', 'weight': '0.067'}

	Recorder: a158cd113b35414d8ae73ab2ae655888

		Model: {'id': 'a158cd113b35414d8ae73ab2ae655888', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.019, 'ICIR': 0.157, 'Rank IC': 0.024, 'Rank ICIR': 0.195}, 'data_train_vec': ['2023-07-10', '2025-10-09'], 'train_time_vec': ['2026-07-10', '2026-07-10'], 'rank_icir': '0.195', 'weight': '0.048'}
