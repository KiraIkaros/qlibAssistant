# params 
 {'predict_dates': [{'start': '2026-09-18', 'end': '2026-09-18'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260918_18 590513045937855878 (Recorders: 3/5)

	Recorder: 2e87c9d720924ab7a0d82012292748e9

		Model: {'id': '2e87c9d720924ab7a0d82012292748e9', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.01, 'ICIR': 0.06, 'Rank IC': 0.034, 'Rank ICIR': 0.208}, 'data_train_vec': ['2021-09-18', '2025-06-17'], 'train_time_vec': ['2026-09-18', '2026-09-18'], 'rank_icir': '0.208', 'weight': '0.096'}

	Recorder: d841c244d0af4ba3ad0c84d58e69485b

		Model: {'id': 'd841c244d0af4ba3ad0c84d58e69485b', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.017, 'ICIR': 0.077, 'Rank IC': 0.031, 'Rank ICIR': 0.195}, 'data_train_vec': ['2022-09-18', '2025-09-17'], 'train_time_vec': ['2026-09-18', '2026-09-18'], 'rank_icir': '0.195', 'weight': '0.090'}

	Recorder: f2e2a59a1b574dc3b181339352e659b1

		Model: {'id': 'f2e2a59a1b574dc3b181339352e659b1', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.01, 'ICIR': 0.037, 'Rank IC': 0.009, 'Rank ICIR': 0.053}, 'data_train_vec': ['2023-09-18', '2025-12-17'], 'train_time_vec': ['2026-09-18', '2026-09-18'], 'rank_icir': '0.053', 'weight': '0.024'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260918_18 235199208681660652 (Recorders: 3/5)

	Recorder: d1c591d1299841f5a93468f2845a5fe2

		Model: {'id': 'd1c591d1299841f5a93468f2845a5fe2', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.015, 'ICIR': 0.094, 'Rank IC': 0.025, 'Rank ICIR': 0.163}, 'data_train_vec': ['2021-09-18', '2025-06-17'], 'train_time_vec': ['2026-09-18', '2026-09-18'], 'rank_icir': '0.163', 'weight': '0.075'}

	Recorder: 57572ab9db674f799b7aeaa25df8f965

		Model: {'id': '57572ab9db674f799b7aeaa25df8f965', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.022, 'ICIR': 0.12, 'Rank IC': 0.034, 'Rank ICIR': 0.214}, 'data_train_vec': ['2022-09-18', '2025-09-17'], 'train_time_vec': ['2026-09-18', '2026-09-18'], 'rank_icir': '0.214', 'weight': '0.099'}

	Recorder: 817424c0771a42b097b918357d1a1a2a

		Model: {'id': '817424c0771a42b097b918357d1a1a2a', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.023, 'ICIR': 0.096, 'Rank IC': 0.007, 'Rank ICIR': 0.042}, 'data_train_vec': ['2024-09-18', '2026-03-17'], 'train_time_vec': ['2026-09-18', '2026-09-18'], 'rank_icir': '0.042', 'weight': '0.019'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260918_16 321893422548354065 (Recorders: 4/5)

	Recorder: 4d7f2e42661d498991e806c71a598063

		Model: {'id': '4d7f2e42661d498991e806c71a598063', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.027, 'ICIR': 0.14, 'Rank IC': 0.038, 'Rank ICIR': 0.218}, 'data_train_vec': ['2021-09-18', '2025-06-17'], 'train_time_vec': ['2026-09-18', '2026-09-18'], 'rank_icir': '0.218', 'weight': '0.100'}

	Recorder: e5d9c23967a34361aacbea1c36056848

		Model: {'id': 'e5d9c23967a34361aacbea1c36056848', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.029, 'ICIR': 0.127, 'Rank IC': 0.035, 'Rank ICIR': 0.198}, 'data_train_vec': ['2022-09-18', '2025-09-17'], 'train_time_vec': ['2026-09-18', '2026-09-18'], 'rank_icir': '0.198', 'weight': '0.091'}

	Recorder: b487fa729d3e49528091d9c2469cfa79

		Model: {'id': 'b487fa729d3e49528091d9c2469cfa79', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.003, 'ICIR': 0.011, 'Rank IC': 0.005, 'Rank ICIR': 0.025}, 'data_train_vec': ['2023-09-18', '2025-12-17'], 'train_time_vec': ['2026-09-18', '2026-09-18'], 'rank_icir': '0.025', 'weight': '0.012'}

	Recorder: ec325e6f909f4191a397cf9c20f4913d

		Model: {'id': 'ec325e6f909f4191a397cf9c20f4913d', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.024, 'ICIR': 0.097, 'Rank IC': 0.004, 'Rank ICIR': 0.021}, 'data_train_vec': ['2024-09-18', '2026-03-17'], 'train_time_vec': ['2026-09-18', '2026-09-18'], 'rank_icir': '0.021', 'weight': '0.010'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260918_16 509845620859238045 (Recorders: 3/5)

	Recorder: 96ac4445d6284b2b996be0bb35512801

		Model: {'id': '96ac4445d6284b2b996be0bb35512801', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.029, 'ICIR': 0.142, 'Rank IC': 0.034, 'Rank ICIR': 0.2}, 'data_train_vec': ['2021-09-18', '2025-06-17'], 'train_time_vec': ['2026-09-18', '2026-09-18'], 'rank_icir': '0.200', 'weight': '0.092'}

	Recorder: a9224c3b72e7458d95f17dc118027e54

		Model: {'id': 'a9224c3b72e7458d95f17dc118027e54', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.024, 'ICIR': 0.118, 'Rank IC': 0.017, 'Rank ICIR': 0.101}, 'data_train_vec': ['2022-09-18', '2025-09-17'], 'train_time_vec': ['2026-09-18', '2026-09-18'], 'rank_icir': '0.101', 'weight': '0.047'}

	Recorder: db7393ecead04f6d934b099e89ef5d60

		Model: {'id': 'db7393ecead04f6d934b099e89ef5d60', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.061, 'ICIR': 0.255, 'Rank IC': 0.037, 'Rank ICIR': 0.181}, 'data_train_vec': ['2024-09-18', '2026-03-17'], 'train_time_vec': ['2026-09-18', '2026-09-18'], 'rank_icir': '0.181', 'weight': '0.083'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260918_16 435579531235039609 (Recorders: 3/5)

	Recorder: a3a2c6b25085480eaf7093ddc9f3fedc

		Model: {'id': 'a3a2c6b25085480eaf7093ddc9f3fedc', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.001, 'ICIR': 0.007, 'Rank IC': 0.029, 'Rank ICIR': 0.168}, 'data_train_vec': ['2021-09-18', '2025-06-17'], 'train_time_vec': ['2026-09-18', '2026-09-18'], 'rank_icir': '0.168', 'weight': '0.077'}

	Recorder: d429e70567324bfb87bac8917b3738f4

		Model: {'id': 'd429e70567324bfb87bac8917b3738f4', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.002, 'ICIR': 0.008, 'Rank IC': 0.012, 'Rank ICIR': 0.071}, 'data_train_vec': ['2023-09-18', '2025-12-17'], 'train_time_vec': ['2026-09-18', '2026-09-18'], 'rank_icir': '0.071', 'weight': '0.033'}

	Recorder: d237d30481544c0d94b68253841f0424

		Model: {'id': 'd237d30481544c0d94b68253841f0424', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.033, 'ICIR': 0.121, 'Rank IC': 0.02, 'Rank ICIR': 0.113}, 'data_train_vec': ['2024-09-18', '2026-03-17'], 'train_time_vec': ['2026-09-18', '2026-09-18'], 'rank_icir': '0.113', 'weight': '0.052'}
