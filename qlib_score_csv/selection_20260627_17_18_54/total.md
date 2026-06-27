# params 
 {'predict_dates': [{'start': '2026-06-26', 'end': '2026-06-26'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260627_16 729376855330843357 (Recorders: 3/5)

	Recorder: 0e9dfa8d816f441c959961b12b908995

		Model: {'id': '0e9dfa8d816f441c959961b12b908995', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.012, 'ICIR': 0.099, 'Rank IC': 0.038, 'Rank ICIR': 0.222}, 'data_train_vec': ['2022-06-27', '2025-06-26'], 'train_time_vec': ['2026-06-27', '2026-06-27'], 'rank_icir': '0.222', 'weight': '0.071'}

	Recorder: 9f9293acdb6c45ca9a98fed59ef60f6a

		Model: {'id': '9f9293acdb6c45ca9a98fed59ef60f6a', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.038, 'ICIR': 0.329, 'Rank IC': 0.038, 'Rank ICIR': 0.307}, 'data_train_vec': ['2023-06-27', '2025-09-26'], 'train_time_vec': ['2026-06-27', '2026-06-27'], 'rank_icir': '0.307', 'weight': '0.099'}

	Recorder: 75e4136fc14c4e928d615aadbe01103c

		Model: {'id': '75e4136fc14c4e928d615aadbe01103c', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.051, 'ICIR': 0.405, 'Rank IC': 0.041, 'Rank ICIR': 0.387}, 'data_train_vec': ['2024-06-27', '2025-12-26'], 'train_time_vec': ['2026-06-27', '2026-06-27'], 'rank_icir': '0.387', 'weight': '0.124'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260627_16 330909143879851952 (Recorders: 5/5)

	Recorder: 61b1f04afa344edb9692200778c9b66c

		Model: {'id': '61b1f04afa344edb9692200778c9b66c', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.002, 'ICIR': 0.016, 'Rank IC': 0.025, 'Rank ICIR': 0.179}, 'data_train_vec': ['2021-06-27', '2025-03-26'], 'train_time_vec': ['2026-06-27', '2026-06-27'], 'rank_icir': '0.179', 'weight': '0.057'}

	Recorder: 3b875f2fecd041ff922ade0aeaeb2813

		Model: {'id': '3b875f2fecd041ff922ade0aeaeb2813', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.013, 'ICIR': 0.112, 'Rank IC': 0.032, 'Rank ICIR': 0.25}, 'data_train_vec': ['2022-06-27', '2025-06-26'], 'train_time_vec': ['2026-06-27', '2026-06-27'], 'rank_icir': '0.250', 'weight': '0.080'}

	Recorder: 4e48c9a7c64d46e0a8cecdcdc2eb0f33

		Model: {'id': '4e48c9a7c64d46e0a8cecdcdc2eb0f33', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.029, 'ICIR': 0.289, 'Rank IC': 0.037, 'Rank ICIR': 0.297}, 'data_train_vec': ['2023-06-27', '2025-09-26'], 'train_time_vec': ['2026-06-27', '2026-06-27'], 'rank_icir': '0.297', 'weight': '0.095'}

	Recorder: 21b97e8b4548418780f41dfa2aed8559

		Model: {'id': '21b97e8b4548418780f41dfa2aed8559', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.027, 'ICIR': 0.211, 'Rank IC': 0.023, 'Rank ICIR': 0.195}, 'data_train_vec': ['2024-06-27', '2025-12-26'], 'train_time_vec': ['2026-06-27', '2026-06-27'], 'rank_icir': '0.195', 'weight': '0.063'}

	Recorder: be089db8d37a45a9b6d472e336701bdc

		Model: {'id': 'be089db8d37a45a9b6d472e336701bdc', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.038, 'ICIR': 0.14, 'Rank IC': 0.006, 'Rank ICIR': 0.024}, 'data_train_vec': ['2025-06-27', '2026-03-26'], 'train_time_vec': ['2026-06-27', '2026-06-27'], 'rank_icir': '0.024', 'weight': '0.008'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260627_14 667733126875897399 (Recorders: 3/5)

	Recorder: 33be5b934b42488c9c582c81af120cba

		Model: {'id': '33be5b934b42488c9c582c81af120cba', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.013, 'ICIR': 0.077, 'Rank IC': 0.043, 'Rank ICIR': 0.257}, 'data_train_vec': ['2021-06-27', '2025-03-26'], 'train_time_vec': ['2026-06-27', '2026-06-27'], 'rank_icir': '0.257', 'weight': '0.083'}

	Recorder: 490c8dbc91b745b484b9c05f23dc4b1e

		Model: {'id': '490c8dbc91b745b484b9c05f23dc4b1e', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.011, 'ICIR': 0.069, 'Rank IC': 0.041, 'Rank ICIR': 0.251}, 'data_train_vec': ['2022-06-27', '2025-06-26'], 'train_time_vec': ['2026-06-27', '2026-06-27'], 'rank_icir': '0.251', 'weight': '0.081'}

	Recorder: 1ed3eb27bbb146d990ae60327c7d40b1

		Model: {'id': '1ed3eb27bbb146d990ae60327c7d40b1', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.029, 'ICIR': 0.23, 'Rank IC': 0.038, 'Rank ICIR': 0.302}, 'data_train_vec': ['2023-06-27', '2025-09-26'], 'train_time_vec': ['2026-06-27', '2026-06-27'], 'rank_icir': '0.302', 'weight': '0.097'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260627_14 660754301444892497 (Recorders: 1/5)

	Recorder: f860a22b595e4559b94c7fa5f319fadd

		Model: {'id': 'f860a22b595e4559b94c7fa5f319fadd', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.003, 'ICIR': 0.019, 'Rank IC': 0.019, 'Rank ICIR': 0.142}, 'data_train_vec': ['2023-06-27', '2025-09-26'], 'train_time_vec': ['2026-06-27', '2026-06-27'], 'rank_icir': '0.142', 'weight': '0.046'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260627_14 818119312407798444 (Recorders: 2/5)

	Recorder: 6fbf15553b0a4f13b708d85f001ff313

		Model: {'id': '6fbf15553b0a4f13b708d85f001ff313', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.023, 'ICIR': 0.167, 'Rank IC': 0.028, 'Rank ICIR': 0.203}, 'data_train_vec': ['2023-06-27', '2025-09-26'], 'train_time_vec': ['2026-06-27', '2026-06-27'], 'rank_icir': '0.203', 'weight': '0.065'}

	Recorder: f42a6c138c504082860b8da1d35a5118

		Model: {'id': 'f42a6c138c504082860b8da1d35a5118', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.017, 'ICIR': 0.134, 'Rank IC': 0.01, 'Rank ICIR': 0.098}, 'data_train_vec': ['2024-06-27', '2025-12-26'], 'train_time_vec': ['2026-06-27', '2026-06-27'], 'rank_icir': '0.098', 'weight': '0.031'}
