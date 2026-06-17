# params 
 {'predict_dates': [{'start': '2026-06-17', 'end': '2026-06-17'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260617_18 175881069236489656 (Recorders: 3/5)

	Recorder: 7752741d60a443d7b2eec104462dd911

		Model: {'id': '7752741d60a443d7b2eec104462dd911', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.007, 'ICIR': 0.056, 'Rank IC': 0.036, 'Rank ICIR': 0.223}, 'data_train_vec': ['2022-06-17', '2025-06-16'], 'train_time_vec': ['2026-06-17', '2026-06-17'], 'rank_icir': '0.223', 'weight': '0.044'}

	Recorder: 69dbf88cdbb546e5a0e2c2e1bae2ae50

		Model: {'id': '69dbf88cdbb546e5a0e2c2e1bae2ae50', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.012, 'ICIR': 0.1, 'Rank IC': 0.032, 'Rank ICIR': 0.214}, 'data_train_vec': ['2023-06-17', '2025-09-16'], 'train_time_vec': ['2026-06-17', '2026-06-17'], 'rank_icir': '0.214', 'weight': '0.043'}

	Recorder: 91e33d4b459c4dd7b2f3fbbf2f890945

		Model: {'id': '91e33d4b459c4dd7b2f3fbbf2f890945', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.041, 'ICIR': 0.352, 'Rank IC': 0.042, 'Rank ICIR': 0.423}, 'data_train_vec': ['2024-06-17', '2025-12-16'], 'train_time_vec': ['2026-06-17', '2026-06-17'], 'rank_icir': '0.423', 'weight': '0.084'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260617_18 273754194553862304 (Recorders: 4/5)

	Recorder: 487977a5d6a7401786d336e7f8beeb2c

		Model: {'id': '487977a5d6a7401786d336e7f8beeb2c', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.002, 'ICIR': 0.013, 'Rank IC': 0.019, 'Rank ICIR': 0.134}, 'data_train_vec': ['2021-06-17', '2025-03-16'], 'train_time_vec': ['2026-06-17', '2026-06-17'], 'rank_icir': '0.134', 'weight': '0.027'}

	Recorder: 0b325a1f2d254d5a9abfc12954e085ae

		Model: {'id': '0b325a1f2d254d5a9abfc12954e085ae', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.004, 'ICIR': 0.031, 'Rank IC': 0.038, 'Rank ICIR': 0.254}, 'data_train_vec': ['2022-06-17', '2025-06-16'], 'train_time_vec': ['2026-06-17', '2026-06-17'], 'rank_icir': '0.254', 'weight': '0.051'}

	Recorder: bdf356473d8b4919a0ad5802460e0bb2

		Model: {'id': 'bdf356473d8b4919a0ad5802460e0bb2', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.032, 'ICIR': 0.309, 'Rank IC': 0.042, 'Rank ICIR': 0.348}, 'data_train_vec': ['2023-06-17', '2025-09-16'], 'train_time_vec': ['2026-06-17', '2026-06-17'], 'rank_icir': '0.348', 'weight': '0.069'}

	Recorder: 1eca1b24a2a7466c8248fb642ac8a559

		Model: {'id': '1eca1b24a2a7466c8248fb642ac8a559', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.036, 'ICIR': 0.351, 'Rank IC': 0.037, 'Rank ICIR': 0.383}, 'data_train_vec': ['2024-06-17', '2025-12-16'], 'train_time_vec': ['2026-06-17', '2026-06-17'], 'rank_icir': '0.383', 'weight': '0.076'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260617_16 190108121599155665 (Recorders: 4/5)

	Recorder: 6f861c2dc0a84e63bd49fce6402be103

		Model: {'id': '6f861c2dc0a84e63bd49fce6402be103', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.014, 'ICIR': 0.088, 'Rank IC': 0.044, 'Rank ICIR': 0.286}, 'data_train_vec': ['2021-06-17', '2025-03-16'], 'train_time_vec': ['2026-06-17', '2026-06-17'], 'rank_icir': '0.286', 'weight': '0.057'}

	Recorder: d0850a2e8fc64412b0ba104f0ecf2c9e

		Model: {'id': 'd0850a2e8fc64412b0ba104f0ecf2c9e', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.026, 'ICIR': 0.173, 'Rank IC': 0.056, 'Rank ICIR': 0.34}, 'data_train_vec': ['2022-06-17', '2025-06-16'], 'train_time_vec': ['2026-06-17', '2026-06-17'], 'rank_icir': '0.340', 'weight': '0.068'}

	Recorder: 6fa7578a59924516b8f2864cda30385e

		Model: {'id': '6fa7578a59924516b8f2864cda30385e', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.026, 'ICIR': 0.194, 'Rank IC': 0.042, 'Rank ICIR': 0.286}, 'data_train_vec': ['2023-06-17', '2025-09-16'], 'train_time_vec': ['2026-06-17', '2026-06-17'], 'rank_icir': '0.286', 'weight': '0.057'}

	Recorder: 04f5d966c752475db3c42f7a401f5d3f

		Model: {'id': '04f5d966c752475db3c42f7a401f5d3f', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.025, 'ICIR': 0.199, 'Rank IC': 0.029, 'Rank ICIR': 0.256}, 'data_train_vec': ['2024-06-17', '2025-12-16'], 'train_time_vec': ['2026-06-17', '2026-06-17'], 'rank_icir': '0.256', 'weight': '0.051'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260617_16 616088662635976723 (Recorders: 4/5)

	Recorder: 5a4f1b1c37e9489e8a0d3f4c79a05011

		Model: {'id': '5a4f1b1c37e9489e8a0d3f4c79a05011', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.005, 'ICIR': 0.035, 'Rank IC': 0.036, 'Rank ICIR': 0.299}, 'data_train_vec': ['2021-06-17', '2025-03-16'], 'train_time_vec': ['2026-06-17', '2026-06-17'], 'rank_icir': '0.299', 'weight': '0.060'}

	Recorder: 95c44167e8ac482bb4cd7e0639f811da

		Model: {'id': '95c44167e8ac482bb4cd7e0639f811da', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.001, 'ICIR': 0.007, 'Rank IC': 0.038, 'Rank ICIR': 0.281}, 'data_train_vec': ['2022-06-17', '2025-06-16'], 'train_time_vec': ['2026-06-17', '2026-06-17'], 'rank_icir': '0.281', 'weight': '0.056'}

	Recorder: 7b13f41a1da44b079f861cc90cc69e89

		Model: {'id': '7b13f41a1da44b079f861cc90cc69e89', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.004, 'ICIR': 0.035, 'Rank IC': 0.029, 'Rank ICIR': 0.234}, 'data_train_vec': ['2023-06-17', '2025-09-16'], 'train_time_vec': ['2026-06-17', '2026-06-17'], 'rank_icir': '0.234', 'weight': '0.047'}

	Recorder: 09a4dac0614846c880a867fdd6b3ef30

		Model: {'id': '09a4dac0614846c880a867fdd6b3ef30', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.019, 'ICIR': 0.119, 'Rank IC': 0.021, 'Rank ICIR': 0.147}, 'data_train_vec': ['2024-06-17', '2025-12-16'], 'train_time_vec': ['2026-06-17', '2026-06-17'], 'rank_icir': '0.147', 'weight': '0.029'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260617_16 914432880922610246 (Recorders: 4/5)

	Recorder: 99943b45d54b4ccfaf82c349bc86b6ef

		Model: {'id': '99943b45d54b4ccfaf82c349bc86b6ef', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.008, 'ICIR': 0.051, 'Rank IC': 0.043, 'Rank ICIR': 0.258}, 'data_train_vec': ['2021-06-17', '2025-03-16'], 'train_time_vec': ['2026-06-17', '2026-06-17'], 'rank_icir': '0.258', 'weight': '0.051'}

	Recorder: 8b36d964d863493aa9932b4fbdd7701d

		Model: {'id': '8b36d964d863493aa9932b4fbdd7701d', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.008, 'ICIR': 0.053, 'Rank IC': 0.041, 'Rank ICIR': 0.233}, 'data_train_vec': ['2022-06-17', '2025-06-16'], 'train_time_vec': ['2026-06-17', '2026-06-17'], 'rank_icir': '0.233', 'weight': '0.046'}

	Recorder: 859b271477494ea69a4fea17f66994f4

		Model: {'id': '859b271477494ea69a4fea17f66994f4', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.003, 'ICIR': 0.027, 'Rank IC': 0.029, 'Rank ICIR': 0.183}, 'data_train_vec': ['2023-06-17', '2025-09-16'], 'train_time_vec': ['2026-06-17', '2026-06-17'], 'rank_icir': '0.183', 'weight': '0.036'}

	Recorder: ee8a4b7c31c2437385d74ee2c3c2f2c2

		Model: {'id': 'ee8a4b7c31c2437385d74ee2c3c2f2c2', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.005, 'ICIR': 0.043, 'Rank IC': 0.026, 'Rank ICIR': 0.242}, 'data_train_vec': ['2024-06-17', '2025-12-16'], 'train_time_vec': ['2026-06-17', '2026-06-17'], 'rank_icir': '0.242', 'weight': '0.048'}
