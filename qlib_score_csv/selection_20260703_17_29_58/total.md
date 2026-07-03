# params 
 {'predict_dates': [{'start': '2026-07-03', 'end': '2026-07-03'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260703_17 666756542039639025 (Recorders: 3/5)

	Recorder: 89cc1b02558a420c842b7538d19a7667

		Model: {'id': '89cc1b02558a420c842b7538d19a7667', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.018, 'ICIR': 0.146, 'Rank IC': 0.024, 'Rank ICIR': 0.152}, 'data_train_vec': ['2022-07-03', '2025-07-02'], 'train_time_vec': ['2026-07-03', '2026-07-03'], 'rank_icir': '0.152', 'weight': '0.058'}

	Recorder: edf8224f5cb740288d21395bdcea7bbc

		Model: {'id': 'edf8224f5cb740288d21395bdcea7bbc', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.03, 'ICIR': 0.237, 'Rank IC': 0.025, 'Rank ICIR': 0.2}, 'data_train_vec': ['2023-07-03', '2025-10-02'], 'train_time_vec': ['2026-07-03', '2026-07-03'], 'rank_icir': '0.200', 'weight': '0.076'}

	Recorder: 1ad42fa9e35847ef9c2eae9a2260001e

		Model: {'id': '1ad42fa9e35847ef9c2eae9a2260001e', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.031, 'ICIR': 0.294, 'Rank IC': 0.037, 'Rank ICIR': 0.368}, 'data_train_vec': ['2024-07-03', '2026-01-02'], 'train_time_vec': ['2026-07-03', '2026-07-03'], 'rank_icir': '0.368', 'weight': '0.141'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260703_16 456350886136377584 (Recorders: 3/5)

	Recorder: 804dc190e6d8466a970005a105fd34b0

		Model: {'id': '804dc190e6d8466a970005a105fd34b0', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.022, 'ICIR': 0.207, 'Rank IC': 0.027, 'Rank ICIR': 0.214}, 'data_train_vec': ['2023-07-03', '2025-10-02'], 'train_time_vec': ['2026-07-03', '2026-07-03'], 'rank_icir': '0.214', 'weight': '0.082'}

	Recorder: 4cabc06500184af895ebce298c5b9f0d

		Model: {'id': '4cabc06500184af895ebce298c5b9f0d', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.021, 'ICIR': 0.168, 'Rank IC': 0.02, 'Rank ICIR': 0.154}, 'data_train_vec': ['2024-07-03', '2026-01-02'], 'train_time_vec': ['2026-07-03', '2026-07-03'], 'rank_icir': '0.154', 'weight': '0.059'}

	Recorder: 742e855b94684d13a3c1f976690092a2

		Model: {'id': '742e855b94684d13a3c1f976690092a2', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.018, 'ICIR': 0.067, 'Rank IC': 0.015, 'Rank ICIR': 0.066}, 'data_train_vec': ['2025-07-03', '2026-04-02'], 'train_time_vec': ['2026-07-03', '2026-07-03'], 'rank_icir': '0.066', 'weight': '0.025'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260703_14 593250387315906152 (Recorders: 3/5)

	Recorder: a3446e5a60d74304a3a77a83badff51e

		Model: {'id': 'a3446e5a60d74304a3a77a83badff51e', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.011, 'ICIR': 0.065, 'Rank IC': 0.042, 'Rank ICIR': 0.256}, 'data_train_vec': ['2021-07-03', '2025-04-02'], 'train_time_vec': ['2026-07-03', '2026-07-03'], 'rank_icir': '0.256', 'weight': '0.098'}

	Recorder: ee5e6e44b8f9480698ef0efbde7c777f

		Model: {'id': 'ee5e6e44b8f9480698ef0efbde7c777f', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.02, 'ICIR': 0.132, 'Rank IC': 0.044, 'Rank ICIR': 0.275}, 'data_train_vec': ['2022-07-03', '2025-07-02'], 'train_time_vec': ['2026-07-03', '2026-07-03'], 'rank_icir': '0.275', 'weight': '0.105'}

	Recorder: cece5563cc6e4463bf173a2a8d333189

		Model: {'id': 'cece5563cc6e4463bf173a2a8d333189', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.019, 'ICIR': 0.145, 'Rank IC': 0.032, 'Rank ICIR': 0.248}, 'data_train_vec': ['2023-07-03', '2025-10-02'], 'train_time_vec': ['2026-07-03', '2026-07-03'], 'rank_icir': '0.248', 'weight': '0.095'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260703_14 705279710496821397 (Recorders: 1/5)

	Recorder: 0b2abfd9b8ae4564b4b75f836e8ca0fd

		Model: {'id': '0b2abfd9b8ae4564b4b75f836e8ca0fd', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.009, 'ICIR': 0.063, 'Rank IC': 0.021, 'Rank ICIR': 0.154}, 'data_train_vec': ['2023-07-03', '2025-10-02'], 'train_time_vec': ['2026-07-03', '2026-07-03'], 'rank_icir': '0.154', 'weight': '0.059'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260703_14 585476089437664933 (Recorders: 3/5)

	Recorder: 9fca99e6325045d793b89ff27e2ab0a9

		Model: {'id': '9fca99e6325045d793b89ff27e2ab0a9', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.004, 'ICIR': 0.029, 'Rank IC': 0.038, 'Rank ICIR': 0.212}, 'data_train_vec': ['2021-07-03', '2025-04-02'], 'train_time_vec': ['2026-07-03', '2026-07-03'], 'rank_icir': '0.212', 'weight': '0.081'}

	Recorder: aa7530acb0a94b5e913773107913b204

		Model: {'id': 'aa7530acb0a94b5e913773107913b204', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.005, 'ICIR': 0.034, 'Rank IC': 0.033, 'Rank ICIR': 0.206}, 'data_train_vec': ['2022-07-03', '2025-07-02'], 'train_time_vec': ['2026-07-03', '2026-07-03'], 'rank_icir': '0.206', 'weight': '0.079'}

	Recorder: ccbc9c266ed44dab8248deeb62319676

		Model: {'id': 'ccbc9c266ed44dab8248deeb62319676', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.009, 'ICIR': 0.08, 'Rank IC': 0.016, 'Rank ICIR': 0.113}, 'data_train_vec': ['2023-07-03', '2025-10-02'], 'train_time_vec': ['2026-07-03', '2026-07-03'], 'rank_icir': '0.113', 'weight': '0.043'}
