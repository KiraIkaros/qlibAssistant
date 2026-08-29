# params 
 {'predict_dates': [{'start': '2026-08-28', 'end': '2026-08-28'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260829_19 870033080461302883 (Recorders: 2/5)

	Recorder: 7a9b069dd7204c4fa29296d0a887dfac

		Model: {'id': '7a9b069dd7204c4fa29296d0a887dfac', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.029, 'ICIR': 0.129, 'Rank IC': 0.035, 'Rank ICIR': 0.227}, 'data_train_vec': ['2022-08-29', '2025-08-28'], 'train_time_vec': ['2026-08-29', '2026-08-29'], 'rank_icir': '0.227', 'weight': '0.113'}

	Recorder: 83ec2da8d39348fbbf49aad16baa4c9a

		Model: {'id': '83ec2da8d39348fbbf49aad16baa4c9a', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.019, 'ICIR': 0.072, 'Rank IC': 0.009, 'Rank ICIR': 0.061}, 'data_train_vec': ['2023-08-29', '2025-11-28'], 'train_time_vec': ['2026-08-29', '2026-08-29'], 'rank_icir': '0.061', 'weight': '0.030'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260829_19 368708772259961752 (Recorders: 3/5)

	Recorder: ad193a50ea5e4f5ca0917155f9a13c03

		Model: {'id': 'ad193a50ea5e4f5ca0917155f9a13c03', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.011, 'ICIR': 0.073, 'Rank IC': 0.02, 'Rank ICIR': 0.154}, 'data_train_vec': ['2021-08-29', '2025-05-28'], 'train_time_vec': ['2026-08-29', '2026-08-29'], 'rank_icir': '0.154', 'weight': '0.077'}

	Recorder: 706ccec7f12649c3ad11597b44aed58b

		Model: {'id': '706ccec7f12649c3ad11597b44aed58b', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.01, 'ICIR': 0.088, 'Rank IC': 0.007, 'Rank ICIR': 0.065}, 'data_train_vec': ['2023-08-29', '2025-11-28'], 'train_time_vec': ['2026-08-29', '2026-08-29'], 'rank_icir': '0.065', 'weight': '0.032'}

	Recorder: 5878af4e22634e5b89e04e2668453456

		Model: {'id': '5878af4e22634e5b89e04e2668453456', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.001, 'ICIR': 0.01, 'Rank IC': 0.027, 'Rank ICIR': 0.159}, 'data_train_vec': ['2025-08-29', '2026-05-28'], 'train_time_vec': ['2026-08-29', '2026-08-29'], 'rank_icir': '0.159', 'weight': '0.079'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260829_16 104117255922708538 (Recorders: 4/5)

	Recorder: b4bf9b120fbf404ab49bf196b4e95179

		Model: {'id': 'b4bf9b120fbf404ab49bf196b4e95179', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.012, 'ICIR': 0.059, 'Rank IC': 0.023, 'Rank ICIR': 0.138}, 'data_train_vec': ['2021-08-29', '2025-05-28'], 'train_time_vec': ['2026-08-29', '2026-08-29'], 'rank_icir': '0.138', 'weight': '0.069'}

	Recorder: 54e006e8325a49d78b1166d511c71172

		Model: {'id': '54e006e8325a49d78b1166d511c71172', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.026, 'ICIR': 0.117, 'Rank IC': 0.032, 'Rank ICIR': 0.192}, 'data_train_vec': ['2022-08-29', '2025-08-28'], 'train_time_vec': ['2026-08-29', '2026-08-29'], 'rank_icir': '0.192', 'weight': '0.096'}

	Recorder: 27c5cc6388d34516a6017f9248e8574a

		Model: {'id': '27c5cc6388d34516a6017f9248e8574a', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.004, 'ICIR': 0.017, 'Rank IC': 0.011, 'Rank ICIR': 0.06}, 'data_train_vec': ['2023-08-29', '2025-11-28'], 'train_time_vec': ['2026-08-29', '2026-08-29'], 'rank_icir': '0.060', 'weight': '0.030'}

	Recorder: 4dd341bc22484e139d56863d22617a15

		Model: {'id': '4dd341bc22484e139d56863d22617a15', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.019, 'ICIR': 0.088, 'Rank IC': 0.003, 'Rank ICIR': 0.015}, 'data_train_vec': ['2025-08-29', '2026-05-28'], 'train_time_vec': ['2026-08-29', '2026-08-29'], 'rank_icir': '0.015', 'weight': '0.007'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260829_16 258088833755392753 (Recorders: 5/5)

	Recorder: 484fa49d35ae4dd18b430a40259f8e6e

		Model: {'id': '484fa49d35ae4dd18b430a40259f8e6e', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.012, 'ICIR': 0.058, 'Rank IC': 0.022, 'Rank ICIR': 0.132}, 'data_train_vec': ['2021-08-29', '2025-05-28'], 'train_time_vec': ['2026-08-29', '2026-08-29'], 'rank_icir': '0.132', 'weight': '0.066'}

	Recorder: 46a938c14d4340609d15a32b05f415d5

		Model: {'id': '46a938c14d4340609d15a32b05f415d5', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.031, 'ICIR': 0.163, 'Rank IC': 0.029, 'Rank ICIR': 0.187}, 'data_train_vec': ['2022-08-29', '2025-08-28'], 'train_time_vec': ['2026-08-29', '2026-08-29'], 'rank_icir': '0.187', 'weight': '0.093'}

	Recorder: 0800bb6edaf54f978a82697173a62964

		Model: {'id': '0800bb6edaf54f978a82697173a62964', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.007, 'ICIR': 0.027, 'Rank IC': 0.002, 'Rank ICIR': 0.011}, 'data_train_vec': ['2023-08-29', '2025-11-28'], 'train_time_vec': ['2026-08-29', '2026-08-29'], 'rank_icir': '0.011', 'weight': '0.005'}

	Recorder: 6f930ad9f05e49bdbdb1a700365fdea0

		Model: {'id': '6f930ad9f05e49bdbdb1a700365fdea0', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.033, 'ICIR': 0.1, 'Rank IC': 0.018, 'Rank ICIR': 0.069}, 'data_train_vec': ['2024-08-28', '2026-02-27'], 'train_time_vec': ['2026-08-29', '2026-08-29'], 'rank_icir': '0.069', 'weight': '0.034'}

	Recorder: 9b95e00806bb4916a1ffb24782b8a054

		Model: {'id': '9b95e00806bb4916a1ffb24782b8a054', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.084, 'ICIR': 0.423, 'Rank IC': 0.045, 'Rank ICIR': 0.245}, 'data_train_vec': ['2025-08-29', '2026-05-28'], 'train_time_vec': ['2026-08-29', '2026-08-29'], 'rank_icir': '0.245', 'weight': '0.122'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260829_16 914828733620302283 (Recorders: 2/5)

	Recorder: 75eb91b31cae42f7b089e0eef90568f9

		Model: {'id': '75eb91b31cae42f7b089e0eef90568f9', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.004, 'ICIR': 0.015, 'Rank IC': 0.023, 'Rank ICIR': 0.139}, 'data_train_vec': ['2022-08-29', '2025-08-28'], 'train_time_vec': ['2026-08-29', '2026-08-29'], 'rank_icir': '0.139', 'weight': '0.069'}

	Recorder: 642705319b9743ab9987c901a6c08bad

		Model: {'id': '642705319b9743ab9987c901a6c08bad', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.081, 'ICIR': 0.268, 'Rank IC': 0.034, 'Rank ICIR': 0.156}, 'data_train_vec': ['2025-08-29', '2026-05-28'], 'train_time_vec': ['2026-08-29', '2026-08-29'], 'rank_icir': '0.156', 'weight': '0.078'}
