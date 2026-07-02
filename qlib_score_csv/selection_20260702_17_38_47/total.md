# params 
 {'predict_dates': [{'start': '2026-07-02', 'end': '2026-07-02'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260702_17 762617386637982172 (Recorders: 3/5)

	Recorder: b5b3d9e885b94b2b87fe02e8fd6848cf

		Model: {'id': 'b5b3d9e885b94b2b87fe02e8fd6848cf', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.015, 'ICIR': 0.138, 'Rank IC': 0.019, 'Rank ICIR': 0.126}, 'data_train_vec': ['2022-07-02', '2025-07-01'], 'train_time_vec': ['2026-07-02', '2026-07-02'], 'rank_icir': '0.126', 'weight': '0.059'}

	Recorder: ee6fb3a4119e46708f3db6560f31683e

		Model: {'id': 'ee6fb3a4119e46708f3db6560f31683e', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.03, 'ICIR': 0.233, 'Rank IC': 0.025, 'Rank ICIR': 0.196}, 'data_train_vec': ['2023-07-02', '2025-10-01'], 'train_time_vec': ['2026-07-02', '2026-07-02'], 'rank_icir': '0.196', 'weight': '0.092'}

	Recorder: 513614c36415456791439e2529d47969

		Model: {'id': '513614c36415456791439e2529d47969', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.02, 'ICIR': 0.204, 'Rank IC': 0.014, 'Rank ICIR': 0.17}, 'data_train_vec': ['2024-07-02', '2026-01-01'], 'train_time_vec': ['2026-07-02', '2026-07-02'], 'rank_icir': '0.170', 'weight': '0.080'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260702_17 910041680894598671 (Recorders: 3/5)

	Recorder: e66f4ad34b2c4456a1e08c6391630022

		Model: {'id': 'e66f4ad34b2c4456a1e08c6391630022', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.021, 'ICIR': 0.198, 'Rank IC': 0.025, 'Rank ICIR': 0.195}, 'data_train_vec': ['2023-07-02', '2025-10-01'], 'train_time_vec': ['2026-07-02', '2026-07-02'], 'rank_icir': '0.195', 'weight': '0.091'}

	Recorder: b94d7c8399ac47b5976a4a65ea3cb462

		Model: {'id': 'b94d7c8399ac47b5976a4a65ea3cb462', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.023, 'ICIR': 0.178, 'Rank IC': 0.022, 'Rank ICIR': 0.175}, 'data_train_vec': ['2024-07-02', '2026-01-01'], 'train_time_vec': ['2026-07-02', '2026-07-02'], 'rank_icir': '0.175', 'weight': '0.082'}

	Recorder: 390260c0a850432399e8924ec86af97d

		Model: {'id': '390260c0a850432399e8924ec86af97d', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.041, 'ICIR': 0.152, 'Rank IC': 0.022, 'Rank ICIR': 0.092}, 'data_train_vec': ['2025-07-02', '2026-04-01'], 'train_time_vec': ['2026-07-02', '2026-07-02'], 'rank_icir': '0.092', 'weight': '0.043'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260702_14 856099203794270641 (Recorders: 3/5)

	Recorder: d45131e6cc624ee3ad7c710f9a3a5ea9

		Model: {'id': 'd45131e6cc624ee3ad7c710f9a3a5ea9', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.006, 'ICIR': 0.037, 'Rank IC': 0.038, 'Rank ICIR': 0.228}, 'data_train_vec': ['2021-07-02', '2025-04-01'], 'train_time_vec': ['2026-07-02', '2026-07-02'], 'rank_icir': '0.228', 'weight': '0.107'}

	Recorder: dbbf6bd31138411e8ec0e37f29c20d42

		Model: {'id': 'dbbf6bd31138411e8ec0e37f29c20d42', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.016, 'ICIR': 0.103, 'Rank IC': 0.042, 'Rank ICIR': 0.257}, 'data_train_vec': ['2022-07-02', '2025-07-01'], 'train_time_vec': ['2026-07-02', '2026-07-02'], 'rank_icir': '0.257', 'weight': '0.120'}

	Recorder: 8df5008086f74c09a1b5c2b3d98696dc

		Model: {'id': '8df5008086f74c09a1b5c2b3d98696dc', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.017, 'ICIR': 0.132, 'Rank IC': 0.028, 'Rank ICIR': 0.217}, 'data_train_vec': ['2023-07-02', '2025-10-01'], 'train_time_vec': ['2026-07-02', '2026-07-02'], 'rank_icir': '0.217', 'weight': '0.102'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260702_14 282828764653916688 (Recorders: 1/5)

	Recorder: 8cdefe0eac754bc89b01ca104d6bee88

		Model: {'id': '8cdefe0eac754bc89b01ca104d6bee88', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.007, 'ICIR': 0.053, 'Rank IC': 0.022, 'Rank ICIR': 0.162}, 'data_train_vec': ['2023-07-02', '2025-10-01'], 'train_time_vec': ['2026-07-02', '2026-07-02'], 'rank_icir': '0.162', 'weight': '0.076'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260702_14 447266059652937062 (Recorders: 2/5)

	Recorder: 1cc68a53381c499e9230174844b0f26d

		Model: {'id': '1cc68a53381c499e9230174844b0f26d', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.004, 'ICIR': 0.032, 'Rank IC': 0.035, 'Rank ICIR': 0.216}, 'data_train_vec': ['2022-07-02', '2025-07-01'], 'train_time_vec': ['2026-07-02', '2026-07-02'], 'rank_icir': '0.216', 'weight': '0.101'}

	Recorder: a484bbc338b249fe926440682b49937c

		Model: {'id': 'a484bbc338b249fe926440682b49937c', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.008, 'ICIR': 0.068, 'Rank IC': 0.014, 'Rank ICIR': 0.101}, 'data_train_vec': ['2023-07-02', '2025-10-01'], 'train_time_vec': ['2026-07-02', '2026-07-02'], 'rank_icir': '0.101', 'weight': '0.047'}
