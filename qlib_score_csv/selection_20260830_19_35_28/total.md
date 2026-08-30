# params 
 {'predict_dates': [{'start': '2026-08-28', 'end': '2026-08-28'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260830_19 907980699811563006 (Recorders: 3/5)

	Recorder: 9096a3a8a34346fb8e4f5f588bf26af6

		Model: {'id': '9096a3a8a34346fb8e4f5f588bf26af6', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.014, 'ICIR': 0.082, 'Rank IC': 0.003, 'Rank ICIR': 0.014}, 'data_train_vec': ['2021-08-30', '2025-05-29'], 'train_time_vec': ['2026-08-30', '2026-08-30'], 'rank_icir': '0.014', 'weight': '0.008'}

	Recorder: 40ceb27c2b7146df8038a9670ab316d5

		Model: {'id': '40ceb27c2b7146df8038a9670ab316d5', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.023, 'ICIR': 0.137, 'Rank IC': 0.03, 'Rank ICIR': 0.24}, 'data_train_vec': ['2022-08-30', '2025-08-29'], 'train_time_vec': ['2026-08-30', '2026-08-30'], 'rank_icir': '0.240', 'weight': '0.130'}

	Recorder: dee95aaedf184ccd8e26c80c0d6ec8d2

		Model: {'id': 'dee95aaedf184ccd8e26c80c0d6ec8d2', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.009, 'ICIR': 0.041, 'Rank IC': 0.01, 'Rank ICIR': 0.078}, 'data_train_vec': ['2023-08-30', '2025-11-29'], 'train_time_vec': ['2026-08-30', '2026-08-30'], 'rank_icir': '0.078', 'weight': '0.042'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260830_19 886583826817322388 (Recorders: 3/5)

	Recorder: 0961dae3124f44f798c46096d89bc448

		Model: {'id': '0961dae3124f44f798c46096d89bc448', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.011, 'ICIR': 0.07, 'Rank IC': 0.019, 'Rank ICIR': 0.144}, 'data_train_vec': ['2021-08-30', '2025-05-29'], 'train_time_vec': ['2026-08-30', '2026-08-30'], 'rank_icir': '0.144', 'weight': '0.078'}

	Recorder: db993a4dd6044e6cbc111641ee74e6ff

		Model: {'id': 'db993a4dd6044e6cbc111641ee74e6ff', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.015, 'ICIR': 0.158, 'Rank IC': 0.018, 'Rank ICIR': 0.167}, 'data_train_vec': ['2022-08-30', '2025-08-29'], 'train_time_vec': ['2026-08-30', '2026-08-30'], 'rank_icir': '0.167', 'weight': '0.091'}

	Recorder: 0586e1ff311c48139c4b74f433fcfa15

		Model: {'id': '0586e1ff311c48139c4b74f433fcfa15', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.008, 'ICIR': 0.045, 'Rank IC': 0.007, 'Rank ICIR': 0.048}, 'data_train_vec': ['2023-08-30', '2025-11-29'], 'train_time_vec': ['2026-08-30', '2026-08-30'], 'rank_icir': '0.048', 'weight': '0.026'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260830_16 261507081307183131 (Recorders: 4/5)

	Recorder: 23d2d9e9bc3147ffae52d44c8b9ac579

		Model: {'id': '23d2d9e9bc3147ffae52d44c8b9ac579', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.009, 'ICIR': 0.045, 'Rank IC': 0.018, 'Rank ICIR': 0.107}, 'data_train_vec': ['2021-08-30', '2025-05-29'], 'train_time_vec': ['2026-08-30', '2026-08-30'], 'rank_icir': '0.107', 'weight': '0.058'}

	Recorder: 3220c308b13f44f29a9d46be8c884b8c

		Model: {'id': '3220c308b13f44f29a9d46be8c884b8c', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.027, 'ICIR': 0.12, 'Rank IC': 0.033, 'Rank ICIR': 0.2}, 'data_train_vec': ['2022-08-30', '2025-08-29'], 'train_time_vec': ['2026-08-30', '2026-08-30'], 'rank_icir': '0.200', 'weight': '0.109'}

	Recorder: dc5c8d08bcab4d719d74d0142657a06d

		Model: {'id': 'dc5c8d08bcab4d719d74d0142657a06d', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.006, 'ICIR': 0.023, 'Rank IC': 0.009, 'Rank ICIR': 0.047}, 'data_train_vec': ['2023-08-30', '2025-11-29'], 'train_time_vec': ['2026-08-30', '2026-08-30'], 'rank_icir': '0.047', 'weight': '0.026'}

	Recorder: 0372e978af624ebaafd24cfa1027ea3a

		Model: {'id': '0372e978af624ebaafd24cfa1027ea3a', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.022, 'ICIR': 0.092, 'Rank IC': 0.01, 'Rank ICIR': 0.047}, 'data_train_vec': ['2025-08-30', '2026-05-29'], 'train_time_vec': ['2026-08-30', '2026-08-30'], 'rank_icir': '0.047', 'weight': '0.026'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260830_16 557028982089328130 (Recorders: 5/5)

	Recorder: 2d7725e4747643ac97b43472eee0f43a

		Model: {'id': '2d7725e4747643ac97b43472eee0f43a', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.012, 'ICIR': 0.058, 'Rank IC': 0.022, 'Rank ICIR': 0.133}, 'data_train_vec': ['2021-08-30', '2025-05-29'], 'train_time_vec': ['2026-08-30', '2026-08-30'], 'rank_icir': '0.133', 'weight': '0.072'}

	Recorder: bf5c9b209a4d473ea85752cc9895256d

		Model: {'id': 'bf5c9b209a4d473ea85752cc9895256d', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.03, 'ICIR': 0.158, 'Rank IC': 0.029, 'Rank ICIR': 0.18}, 'data_train_vec': ['2022-08-30', '2025-08-29'], 'train_time_vec': ['2026-08-30', '2026-08-30'], 'rank_icir': '0.180', 'weight': '0.098'}

	Recorder: c3b867b667aa440aa1c7f96f7fe31cc7

		Model: {'id': 'c3b867b667aa440aa1c7f96f7fe31cc7', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.009, 'ICIR': 0.033, 'Rank IC': 0.002, 'Rank ICIR': 0.011}, 'data_train_vec': ['2023-08-30', '2025-11-29'], 'train_time_vec': ['2026-08-30', '2026-08-30'], 'rank_icir': '0.011', 'weight': '0.006'}

	Recorder: cf5a40cebfd74f9aa8ddb45ab1db8cfc

		Model: {'id': 'cf5a40cebfd74f9aa8ddb45ab1db8cfc', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.03, 'ICIR': 0.091, 'Rank IC': 0.017, 'Rank ICIR': 0.061}, 'data_train_vec': ['2024-08-28', '2026-02-27'], 'train_time_vec': ['2026-08-30', '2026-08-30'], 'rank_icir': '0.061', 'weight': '0.033'}

	Recorder: 321f582631624f3fa10a74d88a1a3d93

		Model: {'id': '321f582631624f3fa10a74d88a1a3d93', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.095, 'ICIR': 0.446, 'Rank IC': 0.052, 'Rank ICIR': 0.289}, 'data_train_vec': ['2025-08-30', '2026-05-29'], 'train_time_vec': ['2026-08-30', '2026-08-30'], 'rank_icir': '0.289', 'weight': '0.157'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260830_16 407505364542978446 (Recorders: 1/5)

	Recorder: e09cb8b525ea4492aa2ac3b9a54eb1bd

		Model: {'id': 'e09cb8b525ea4492aa2ac3b9a54eb1bd', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.053, 'ICIR': 0.161, 'Rank IC': 0.017, 'Rank ICIR': 0.075}, 'data_train_vec': ['2025-08-30', '2026-05-29'], 'train_time_vec': ['2026-08-30', '2026-08-30'], 'rank_icir': '0.075', 'weight': '0.041'}
