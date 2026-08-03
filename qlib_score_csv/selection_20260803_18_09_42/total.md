# params 
 {'predict_dates': [{'start': '2026-08-03', 'end': '2026-08-03'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260803_17 420706864970950744 (Recorders: 1/5)

	Recorder: 9b87035ef4e946bcb68fc991198a3df0

		Model: {'id': '9b87035ef4e946bcb68fc991198a3df0', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.013, 'ICIR': 0.076, 'Rank IC': 0.02, 'Rank ICIR': 0.154}, 'data_train_vec': ['2023-08-03', '2025-11-02'], 'train_time_vec': ['2026-08-03', '2026-08-03'], 'rank_icir': '0.154', 'weight': '0.484'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260803_15 424866432505587309 (Recorders: 1/5)

	Recorder: 0188e53fa9d0418d81ad52ee281638cb

		Model: {'id': '0188e53fa9d0418d81ad52ee281638cb', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.008, 'ICIR': 0.04, 'Rank IC': 0.028, 'Rank ICIR': 0.164}, 'data_train_vec': ['2021-08-03', '2025-05-02'], 'train_time_vec': ['2026-08-03', '2026-08-03'], 'rank_icir': '0.164', 'weight': '0.516'}
