# params 
 {'predict_dates': [{'start': '2026-08-21', 'end': '2026-08-21'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260822_15 422060111900063497 (Recorders: 1/5)

	Recorder: bd954c55859c4fa891aac5583fc44879

		Model: {'id': 'bd954c55859c4fa891aac5583fc44879', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.021, 'ICIR': 0.083, 'Rank IC': 0.023, 'Rank ICIR': 0.15}, 'data_train_vec': ['2023-08-22', '2025-11-21'], 'train_time_vec': ['2026-08-22', '2026-08-22'], 'rank_icir': '0.150', 'weight': '0.081'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260822_15 786597298009885772 (Recorders: 3/5)

	Recorder: 9d695ebc40bc4c069ce542c1edfa9d15

		Model: {'id': '9d695ebc40bc4c069ce542c1edfa9d15', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.002, 'ICIR': 0.015, 'Rank IC': 0.014, 'Rank ICIR': 0.109}, 'data_train_vec': ['2021-08-22', '2025-05-21'], 'train_time_vec': ['2026-08-22', '2026-08-22'], 'rank_icir': '0.109', 'weight': '0.059'}

	Recorder: 4d6e987ded51444dba09a407d4a68302

		Model: {'id': '4d6e987ded51444dba09a407d4a68302', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.003, 'ICIR': 0.019, 'Rank IC': 0.011, 'Rank ICIR': 0.081}, 'data_train_vec': ['2022-08-22', '2025-08-21'], 'train_time_vec': ['2026-08-22', '2026-08-22'], 'rank_icir': '0.081', 'weight': '0.044'}

	Recorder: 37665e6b247346389f8e9880ea72c192

		Model: {'id': '37665e6b247346389f8e9880ea72c192', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.008, 'ICIR': 0.049, 'Rank IC': 0.016, 'Rank ICIR': 0.119}, 'data_train_vec': ['2023-08-22', '2025-11-21'], 'train_time_vec': ['2026-08-22', '2026-08-22'], 'rank_icir': '0.119', 'weight': '0.064'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260822_13 617973348523508166 (Recorders: 4/5)

	Recorder: 02075ba3278e44d0ae2110cf39fbcaa6

		Model: {'id': '02075ba3278e44d0ae2110cf39fbcaa6', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.017, 'ICIR': 0.085, 'Rank IC': 0.029, 'Rank ICIR': 0.171}, 'data_train_vec': ['2021-08-22', '2025-05-21'], 'train_time_vec': ['2026-08-22', '2026-08-22'], 'rank_icir': '0.171', 'weight': '0.092'}

	Recorder: c2335612226b480f8faca55cb003e6b9

		Model: {'id': 'c2335612226b480f8faca55cb003e6b9', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.027, 'ICIR': 0.124, 'Rank IC': 0.034, 'Rank ICIR': 0.203}, 'data_train_vec': ['2022-08-22', '2025-08-21'], 'train_time_vec': ['2026-08-22', '2026-08-22'], 'rank_icir': '0.203', 'weight': '0.109'}

	Recorder: 90355edc64964c0ca0acbcb03d107e61

		Model: {'id': '90355edc64964c0ca0acbcb03d107e61', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.007, 'ICIR': 0.03, 'Rank IC': 0.012, 'Rank ICIR': 0.066}, 'data_train_vec': ['2023-08-22', '2025-11-21'], 'train_time_vec': ['2026-08-22', '2026-08-22'], 'rank_icir': '0.066', 'weight': '0.036'}

	Recorder: 3569c0af2c1846cab2cb83de65ef3d94

		Model: {'id': '3569c0af2c1846cab2cb83de65ef3d94', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.015, 'ICIR': 0.053, 'Rank IC': 0.011, 'Rank ICIR': 0.052}, 'data_train_vec': ['2025-08-22', '2026-05-21'], 'train_time_vec': ['2026-08-22', '2026-08-22'], 'rank_icir': '0.052', 'weight': '0.028'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260822_13 122218873148613419 (Recorders: 4/5)

	Recorder: 51a7e0f1d3b847db9e5f0f12a7802c22

		Model: {'id': '51a7e0f1d3b847db9e5f0f12a7802c22', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.012, 'ICIR': 0.06, 'Rank IC': 0.025, 'Rank ICIR': 0.154}, 'data_train_vec': ['2021-08-22', '2025-05-21'], 'train_time_vec': ['2026-08-22', '2026-08-22'], 'rank_icir': '0.154', 'weight': '0.083'}

	Recorder: 0c2092bfa1db47a4881f4b4b3a9cd784

		Model: {'id': '0c2092bfa1db47a4881f4b4b3a9cd784', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.031, 'ICIR': 0.16, 'Rank IC': 0.035, 'Rank ICIR': 0.22}, 'data_train_vec': ['2022-08-22', '2025-08-21'], 'train_time_vec': ['2026-08-22', '2026-08-22'], 'rank_icir': '0.220', 'weight': '0.118'}

	Recorder: 7f4f88fde1324f36948ab34b27e43229

		Model: {'id': '7f4f88fde1324f36948ab34b27e43229', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.021, 'ICIR': 0.063, 'Rank IC': 0.012, 'Rank ICIR': 0.043}, 'data_train_vec': ['2024-08-22', '2026-02-21'], 'train_time_vec': ['2026-08-22', '2026-08-22'], 'rank_icir': '0.043', 'weight': '0.023'}

	Recorder: 7e8feb9d97924f1eb15d1cbd7ed4b80b

		Model: {'id': '7e8feb9d97924f1eb15d1cbd7ed4b80b', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.048, 'ICIR': 0.182, 'Rank IC': 0.018, 'Rank ICIR': 0.094}, 'data_train_vec': ['2025-08-22', '2026-05-21'], 'train_time_vec': ['2026-08-22', '2026-08-22'], 'rank_icir': '0.094', 'weight': '0.051'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260822_12 639395686144977601 (Recorders: 3/5)

	Recorder: 47cb6d4253ed471baa805a796bc5412f

		Model: {'id': '47cb6d4253ed471baa805a796bc5412f', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.004, 'ICIR': 0.02, 'Rank IC': 0.019, 'Rank ICIR': 0.11}, 'data_train_vec': ['2021-08-22', '2025-05-21'], 'train_time_vec': ['2026-08-22', '2026-08-22'], 'rank_icir': '0.110', 'weight': '0.059'}

	Recorder: fcb577ec0eef4a88a351af325aa00348

		Model: {'id': 'fcb577ec0eef4a88a351af325aa00348', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.007, 'ICIR': 0.03, 'Rank IC': 0.027, 'Rank ICIR': 0.163}, 'data_train_vec': ['2022-08-22', '2025-08-21'], 'train_time_vec': ['2026-08-22', '2026-08-22'], 'rank_icir': '0.163', 'weight': '0.088'}

	Recorder: 0628b1c417e9411190b0fa6873abc449

		Model: {'id': '0628b1c417e9411190b0fa6873abc449', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.04, 'ICIR': 0.108, 'Rank IC': 0.03, 'Rank ICIR': 0.124}, 'data_train_vec': ['2025-08-22', '2026-05-21'], 'train_time_vec': ['2026-08-22', '2026-08-22'], 'rank_icir': '0.124', 'weight': '0.067'}
