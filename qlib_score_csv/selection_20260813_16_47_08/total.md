# params 
 {'predict_dates': [{'start': '2026-08-13', 'end': '2026-08-13'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260813_16 719980338456668507 (Recorders: 3/5)

	Recorder: f69b0432d12549ca985038fea215fbf5

		Model: {'id': 'f69b0432d12549ca985038fea215fbf5', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.005, 'ICIR': 0.032, 'Rank IC': 0.014, 'Rank ICIR': 0.095}, 'data_train_vec': ['2021-08-13', '2025-05-12'], 'train_time_vec': ['2026-08-13', '2026-08-13'], 'rank_icir': '0.095', 'weight': '0.086'}

	Recorder: 67b684e18a4b4a1187fddb6a0518ce08

		Model: {'id': '67b684e18a4b4a1187fddb6a0518ce08', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.004, 'ICIR': 0.038, 'Rank IC': 0.012, 'Rank ICIR': 0.094}, 'data_train_vec': ['2022-08-13', '2025-08-12'], 'train_time_vec': ['2026-08-13', '2026-08-13'], 'rank_icir': '0.094', 'weight': '0.085'}

	Recorder: 23c0a34107bd4d55a421ac6bec87036a

		Model: {'id': '23c0a34107bd4d55a421ac6bec87036a', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.016, 'ICIR': 0.094, 'Rank IC': 0.02, 'Rank ICIR': 0.156}, 'data_train_vec': ['2023-08-13', '2025-11-12'], 'train_time_vec': ['2026-08-13', '2026-08-13'], 'rank_icir': '0.156', 'weight': '0.141'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260813_13 706902067552422253 (Recorders: 2/5)

	Recorder: 071b434b5e4e421da2c5636d0651620d

		Model: {'id': '071b434b5e4e421da2c5636d0651620d', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.013, 'ICIR': 0.067, 'Rank IC': 0.028, 'Rank ICIR': 0.158}, 'data_train_vec': ['2021-08-13', '2025-05-12'], 'train_time_vec': ['2026-08-13', '2026-08-13'], 'rank_icir': '0.158', 'weight': '0.143'}

	Recorder: 9050b88eff2843a19b32d91d8e92cd38

		Model: {'id': '9050b88eff2843a19b32d91d8e92cd38', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.007, 'ICIR': 0.033, 'Rank IC': 0.022, 'Rank ICIR': 0.125}, 'data_train_vec': ['2022-08-13', '2025-08-12'], 'train_time_vec': ['2026-08-13', '2026-08-13'], 'rank_icir': '0.125', 'weight': '0.113'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260813_13 113904653492647794 (Recorders: 2/5)

	Recorder: 3402faaf162d4430a1a9adcf339e6966

		Model: {'id': '3402faaf162d4430a1a9adcf339e6966', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.006, 'ICIR': 0.031, 'Rank IC': 0.021, 'Rank ICIR': 0.131}, 'data_train_vec': ['2021-08-13', '2025-05-12'], 'train_time_vec': ['2026-08-13', '2026-08-13'], 'rank_icir': '0.131', 'weight': '0.119'}

	Recorder: b43aa256d02d4951b7922432ec7d0011

		Model: {'id': 'b43aa256d02d4951b7922432ec7d0011', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.018, 'ICIR': 0.09, 'Rank IC': 0.026, 'Rank ICIR': 0.162}, 'data_train_vec': ['2022-08-13', '2025-08-12'], 'train_time_vec': ['2026-08-13', '2026-08-13'], 'rank_icir': '0.162', 'weight': '0.147'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260813_13 785851711725758156 (Recorders: 1/5)

	Recorder: 55e4fcc483ff45d09bef42f56db3327a

		Model: {'id': '55e4fcc483ff45d09bef42f56db3327a', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.013, 'ICIR': 0.064, 'Rank IC': 0.033, 'Rank ICIR': 0.183}, 'data_train_vec': ['2021-08-13', '2025-05-12'], 'train_time_vec': ['2026-08-13', '2026-08-13'], 'rank_icir': '0.183', 'weight': '0.166'}
