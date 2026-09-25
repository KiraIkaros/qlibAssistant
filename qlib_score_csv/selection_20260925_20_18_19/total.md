# params 
 {'predict_dates': [{'start': '2026-09-24', 'end': '2026-09-24'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260925_19 490797920967552006 (Recorders: 4/5)

	Recorder: 2a228ce1e6e74ebba2fc6125541b62d6

		Model: {'id': '2a228ce1e6e74ebba2fc6125541b62d6', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.003, 'ICIR': 0.022, 'Rank IC': 0.023, 'Rank ICIR': 0.153}, 'data_train_vec': ['2021-09-25', '2025-06-24'], 'train_time_vec': ['2026-09-25', '2026-09-25'], 'rank_icir': '0.153', 'weight': '0.069'}

	Recorder: 4dc9d946d95f45dd9687465a4c5e1cb9

		Model: {'id': '4dc9d946d95f45dd9687465a4c5e1cb9', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.023, 'ICIR': 0.097, 'Rank IC': 0.03, 'Rank ICIR': 0.163}, 'data_train_vec': ['2022-09-25', '2025-09-24'], 'train_time_vec': ['2026-09-25', '2026-09-25'], 'rank_icir': '0.163', 'weight': '0.073'}

	Recorder: ca8259e63e924806921ba69bad5dc41f

		Model: {'id': 'ca8259e63e924806921ba69bad5dc41f', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.006, 'ICIR': 0.023, 'Rank IC': 0.009, 'Rank ICIR': 0.047}, 'data_train_vec': ['2023-09-25', '2025-12-24'], 'train_time_vec': ['2026-09-25', '2026-09-25'], 'rank_icir': '0.047', 'weight': '0.021'}

	Recorder: c9fdde27a58546859ea4d10fb92f7a46

		Model: {'id': 'c9fdde27a58546859ea4d10fb92f7a46', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.002, 'ICIR': 0.02, 'Rank IC': 0.01, 'Rank ICIR': 0.06}, 'data_train_vec': ['2025-09-25', '2026-06-24'], 'train_time_vec': ['2026-09-25', '2026-09-25'], 'rank_icir': '0.060', 'weight': '0.027'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260925_19 761947956548385668 (Recorders: 3/5)

	Recorder: 414762ffc0504be887b3bc39a38a55bd

		Model: {'id': '414762ffc0504be887b3bc39a38a55bd', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.021, 'ICIR': 0.126, 'Rank IC': 0.031, 'Rank ICIR': 0.199}, 'data_train_vec': ['2021-09-25', '2025-06-24'], 'train_time_vec': ['2026-09-25', '2026-09-25'], 'rank_icir': '0.199', 'weight': '0.090'}

	Recorder: 6751da68668446ff907552e648c01b71

		Model: {'id': '6751da68668446ff907552e648c01b71', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.025, 'ICIR': 0.125, 'Rank IC': 0.035, 'Rank ICIR': 0.197}, 'data_train_vec': ['2022-09-25', '2025-09-24'], 'train_time_vec': ['2026-09-25', '2026-09-25'], 'rank_icir': '0.197', 'weight': '0.089'}

	Recorder: 872ae53142b24dfeb386448dc9aeff00

		Model: {'id': '872ae53142b24dfeb386448dc9aeff00', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.004, 'ICIR': 0.019, 'Rank IC': 0.005, 'Rank ICIR': 0.026}, 'data_train_vec': ['2023-09-25', '2025-12-24'], 'train_time_vec': ['2026-09-25', '2026-09-25'], 'rank_icir': '0.026', 'weight': '0.012'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260925_17 178531480039835573 (Recorders: 4/5)

	Recorder: 2881b0f29f354be38b7153f696ab638f

		Model: {'id': '2881b0f29f354be38b7153f696ab638f', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.033, 'ICIR': 0.167, 'Rank IC': 0.041, 'Rank ICIR': 0.236}, 'data_train_vec': ['2021-09-25', '2025-06-24'], 'train_time_vec': ['2026-09-25', '2026-09-25'], 'rank_icir': '0.236', 'weight': '0.106'}

	Recorder: f6512b6395d1494cad77a601e3aa7dfe

		Model: {'id': 'f6512b6395d1494cad77a601e3aa7dfe', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.031, 'ICIR': 0.142, 'Rank IC': 0.036, 'Rank ICIR': 0.199}, 'data_train_vec': ['2022-09-25', '2025-09-24'], 'train_time_vec': ['2026-09-25', '2026-09-25'], 'rank_icir': '0.199', 'weight': '0.090'}

	Recorder: 09ad9859f4fe443eafa38c4d8584b590

		Model: {'id': '09ad9859f4fe443eafa38c4d8584b590', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.006, 'ICIR': 0.024, 'Rank IC': 0.007, 'Rank ICIR': 0.036}, 'data_train_vec': ['2023-09-25', '2025-12-24'], 'train_time_vec': ['2026-09-25', '2026-09-25'], 'rank_icir': '0.036', 'weight': '0.016'}

	Recorder: a1049ad1cfef4611bc14287ca44416c2

		Model: {'id': 'a1049ad1cfef4611bc14287ca44416c2', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.032, 'ICIR': 0.144, 'Rank IC': 0.009, 'Rank ICIR': 0.053}, 'data_train_vec': ['2024-09-25', '2026-03-24'], 'train_time_vec': ['2026-09-25', '2026-09-25'], 'rank_icir': '0.053', 'weight': '0.024'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260925_17 613410172043957460 (Recorders: 4/5)

	Recorder: 99ea294222484aeca130860782c64aec

		Model: {'id': '99ea294222484aeca130860782c64aec', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.03, 'ICIR': 0.15, 'Rank IC': 0.035, 'Rank ICIR': 0.2}, 'data_train_vec': ['2021-09-25', '2025-06-24'], 'train_time_vec': ['2026-09-25', '2026-09-25'], 'rank_icir': '0.200', 'weight': '0.090'}

	Recorder: 1a81f9f2ff2944ce8b1a3d99caeb9d32

		Model: {'id': '1a81f9f2ff2944ce8b1a3d99caeb9d32', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.028, 'ICIR': 0.133, 'Rank IC': 0.019, 'Rank ICIR': 0.108}, 'data_train_vec': ['2022-09-25', '2025-09-24'], 'train_time_vec': ['2026-09-25', '2026-09-25'], 'rank_icir': '0.108', 'weight': '0.049'}

	Recorder: 0f9dccc8901f4e73839a955525b08799

		Model: {'id': '0f9dccc8901f4e73839a955525b08799', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.009, 'ICIR': 0.036, 'Rank IC': 0.001, 'Rank ICIR': 0.006}, 'data_train_vec': ['2023-09-25', '2025-12-24'], 'train_time_vec': ['2026-09-25', '2026-09-25'], 'rank_icir': '0.006', 'weight': '0.003'}

	Recorder: 2b4057b6bb4f49a38ea81b70e9886d36

		Model: {'id': '2b4057b6bb4f49a38ea81b70e9886d36', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.058, 'ICIR': 0.241, 'Rank IC': 0.03, 'Rank ICIR': 0.148}, 'data_train_vec': ['2024-09-25', '2026-03-24'], 'train_time_vec': ['2026-09-25', '2026-09-25'], 'rank_icir': '0.148', 'weight': '0.067'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260925_17 862499582528695150 (Recorders: 2/5)

	Recorder: 00eac58efc9b449881bb65e9249afeef

		Model: {'id': '00eac58efc9b449881bb65e9249afeef', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.012, 'ICIR': 0.057, 'Rank IC': 0.036, 'Rank ICIR': 0.216}, 'data_train_vec': ['2021-09-25', '2025-06-24'], 'train_time_vec': ['2026-09-25', '2026-09-25'], 'rank_icir': '0.216', 'weight': '0.097'}

	Recorder: e184dedac55f4cbdabc4b3369346d272

		Model: {'id': 'e184dedac55f4cbdabc4b3369346d272', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.049, 'ICIR': 0.214, 'Rank IC': 0.027, 'Rank ICIR': 0.173}, 'data_train_vec': ['2024-09-25', '2026-03-24'], 'train_time_vec': ['2026-09-25', '2026-09-25'], 'rank_icir': '0.173', 'weight': '0.078'}
