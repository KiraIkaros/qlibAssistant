# params 
 {'predict_dates': [{'start': '2026-09-30', 'end': '2026-09-30'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20261007_21 564486955195428365 (Recorders: 5/5)

	Recorder: bdb4c9ef847b4b7ab4019e98079fc0c8

		Model: {'id': 'bdb4c9ef847b4b7ab4019e98079fc0c8', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.027, 'ICIR': 0.159, 'Rank IC': 0.036, 'Rank ICIR': 0.21}, 'data_train_vec': ['2021-10-07', '2025-07-06'], 'train_time_vec': ['2026-10-07', '2026-10-07'], 'rank_icir': '0.210', 'weight': '0.069'}

	Recorder: ec5bf8f84b594f098a50dcd171f965ff

		Model: {'id': 'ec5bf8f84b594f098a50dcd171f965ff', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.014, 'ICIR': 0.063, 'Rank IC': 0.025, 'Rank ICIR': 0.146}, 'data_train_vec': ['2022-10-07', '2025-10-06'], 'train_time_vec': ['2026-10-07', '2026-10-07'], 'rank_icir': '0.146', 'weight': '0.048'}

	Recorder: 1755b9ef81d74382901deb7532592e08

		Model: {'id': '1755b9ef81d74382901deb7532592e08', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.017, 'ICIR': 0.056, 'Rank IC': 0.019, 'Rank ICIR': 0.094}, 'data_train_vec': ['2023-10-07', '2026-01-06'], 'train_time_vec': ['2026-10-07', '2026-10-07'], 'rank_icir': '0.094', 'weight': '0.031'}

	Recorder: ab6a0a6a7cfe4b01bc158c0a0be9bb6d

		Model: {'id': 'ab6a0a6a7cfe4b01bc158c0a0be9bb6d', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.021, 'ICIR': 0.146, 'Rank IC': 0.009, 'Rank ICIR': 0.051}, 'data_train_vec': ['2024-10-07', '2026-04-06'], 'train_time_vec': ['2026-10-07', '2026-10-07'], 'rank_icir': '0.051', 'weight': '0.017'}

	Recorder: cf753ecbe0d34debbebb3c4ee2c940f0

		Model: {'id': 'cf753ecbe0d34debbebb3c4ee2c940f0', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.011, 'ICIR': 0.08, 'Rank IC': 0.033, 'Rank ICIR': 0.214}, 'data_train_vec': ['2025-10-07', '2026-07-06'], 'train_time_vec': ['2026-10-07', '2026-10-07'], 'rank_icir': '0.214', 'weight': '0.071'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20261007_21 445010026518185531 (Recorders: 4/5)

	Recorder: edbd109897a5447bacb2486e44e032f8

		Model: {'id': 'edbd109897a5447bacb2486e44e032f8', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.028, 'ICIR': 0.189, 'Rank IC': 0.037, 'Rank ICIR': 0.231}, 'data_train_vec': ['2021-10-07', '2025-07-06'], 'train_time_vec': ['2026-10-07', '2026-10-07'], 'rank_icir': '0.231', 'weight': '0.076'}

	Recorder: 47896e72888a499db470b0d8413d97ba

		Model: {'id': '47896e72888a499db470b0d8413d97ba', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.028, 'ICIR': 0.137, 'Rank IC': 0.028, 'Rank ICIR': 0.148}, 'data_train_vec': ['2022-10-07', '2025-10-06'], 'train_time_vec': ['2026-10-07', '2026-10-07'], 'rank_icir': '0.148', 'weight': '0.049'}

	Recorder: 47a11af2a010451089cbee2c78e5987e

		Model: {'id': '47a11af2a010451089cbee2c78e5987e', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.015, 'ICIR': 0.063, 'Rank IC': 0.019, 'Rank ICIR': 0.097}, 'data_train_vec': ['2023-10-07', '2026-01-06'], 'train_time_vec': ['2026-10-07', '2026-10-07'], 'rank_icir': '0.097', 'weight': '0.032'}

	Recorder: 6672641864a743dc918ea94713d66870

		Model: {'id': '6672641864a743dc918ea94713d66870', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.02, 'ICIR': 0.202, 'Rank IC': 0.025, 'Rank ICIR': 0.292}, 'data_train_vec': ['2025-10-07', '2026-07-06'], 'train_time_vec': ['2026-10-07', '2026-10-07'], 'rank_icir': '0.292', 'weight': '0.096'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20261007_19 975550116619557451 (Recorders: 3/5)

	Recorder: f74b9c4fb79142648c593d0b92c8fe25

		Model: {'id': 'f74b9c4fb79142648c593d0b92c8fe25', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.033, 'ICIR': 0.168, 'Rank IC': 0.045, 'Rank ICIR': 0.265}, 'data_train_vec': ['2021-10-07', '2025-07-06'], 'train_time_vec': ['2026-10-07', '2026-10-07'], 'rank_icir': '0.265', 'weight': '0.087'}

	Recorder: b1181fcf56b042d4aa42662a19a824d0

		Model: {'id': 'b1181fcf56b042d4aa42662a19a824d0', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.024, 'ICIR': 0.105, 'Rank IC': 0.025, 'Rank ICIR': 0.135}, 'data_train_vec': ['2022-10-07', '2025-10-06'], 'train_time_vec': ['2026-10-07', '2026-10-07'], 'rank_icir': '0.135', 'weight': '0.045'}

	Recorder: 221663c06cc1420185c9bafb0ae0ad0f

		Model: {'id': '221663c06cc1420185c9bafb0ae0ad0f', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.012, 'ICIR': 0.042, 'Rank IC': 0.012, 'Rank ICIR': 0.053}, 'data_train_vec': ['2023-10-07', '2026-01-06'], 'train_time_vec': ['2026-10-07', '2026-10-07'], 'rank_icir': '0.053', 'weight': '0.017'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20261007_19 651456434045810401 (Recorders: 5/5)

	Recorder: edef8dbebf944fc6a12f9d84776decae

		Model: {'id': 'edef8dbebf944fc6a12f9d84776decae', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.036, 'ICIR': 0.182, 'Rank IC': 0.04, 'Rank ICIR': 0.228}, 'data_train_vec': ['2021-10-07', '2025-07-06'], 'train_time_vec': ['2026-10-07', '2026-10-07'], 'rank_icir': '0.228', 'weight': '0.075'}

	Recorder: 900838f481df492b936fa7842569637e

		Model: {'id': '900838f481df492b936fa7842569637e', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.031, 'ICIR': 0.135, 'Rank IC': 0.018, 'Rank ICIR': 0.093}, 'data_train_vec': ['2022-10-07', '2025-10-06'], 'train_time_vec': ['2026-10-07', '2026-10-07'], 'rank_icir': '0.093', 'weight': '0.031'}

	Recorder: 81c7987822d84eccbf91bda62ee0d0d3

		Model: {'id': '81c7987822d84eccbf91bda62ee0d0d3', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.009, 'ICIR': 0.034, 'Rank IC': 0.005, 'Rank ICIR': 0.026}, 'data_train_vec': ['2023-10-07', '2026-01-06'], 'train_time_vec': ['2026-10-07', '2026-10-07'], 'rank_icir': '0.026', 'weight': '0.009'}

	Recorder: b89d0e8925334ef4842f5498067653fe

		Model: {'id': 'b89d0e8925334ef4842f5498067653fe', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.028, 'ICIR': 0.141, 'Rank IC': 0.013, 'Rank ICIR': 0.069}, 'data_train_vec': ['2024-10-07', '2026-04-06'], 'train_time_vec': ['2026-10-07', '2026-10-07'], 'rank_icir': '0.069', 'weight': '0.023'}

	Recorder: 185c3a3f2fed43dab8d1a2c467a5dc60

		Model: {'id': '185c3a3f2fed43dab8d1a2c467a5dc60', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.039, 'ICIR': 0.287, 'Rank IC': 0.045, 'Rank ICIR': 0.369}, 'data_train_vec': ['2025-10-07', '2026-07-06'], 'train_time_vec': ['2026-10-07', '2026-10-07'], 'rank_icir': '0.369', 'weight': '0.122'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20261007_18 560513915792915054 (Recorders: 2/5)

	Recorder: c9ab45ef5cf04270b5e6b87fa41717f8

		Model: {'id': 'c9ab45ef5cf04270b5e6b87fa41717f8', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.003, 'ICIR': 0.012, 'Rank IC': 0.035, 'Rank ICIR': 0.202}, 'data_train_vec': ['2021-10-07', '2025-07-06'], 'train_time_vec': ['2026-10-07', '2026-10-07'], 'rank_icir': '0.202', 'weight': '0.067'}

	Recorder: db458f9facbe49a0966266e9e09dd714

		Model: {'id': 'db458f9facbe49a0966266e9e09dd714', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.008, 'ICIR': 0.033, 'Rank IC': 0.019, 'Rank ICIR': 0.109}, 'data_train_vec': ['2022-10-07', '2025-10-06'], 'train_time_vec': ['2026-10-07', '2026-10-07'], 'rank_icir': '0.109', 'weight': '0.036'}
