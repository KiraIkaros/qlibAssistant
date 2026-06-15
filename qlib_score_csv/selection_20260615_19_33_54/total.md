# params 
 {'predict_dates': [{'start': '2026-06-15', 'end': '2026-06-15'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260615_19 897873922278319272 (Recorders: 3/5)

	Recorder: 063c7b80bfb144c093a733c6c21659f5

		Model: {'id': '063c7b80bfb144c093a733c6c21659f5', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.006, 'ICIR': 0.037, 'Rank IC': 0.028, 'Rank ICIR': 0.179}, 'data_train_vec': ['2021-06-15', '2025-03-14'], 'train_time_vec': ['2026-06-15', '2026-06-15'], 'rank_icir': '0.179', 'weight': '0.040'}

	Recorder: b7ea61087f5842ac8f6957895597c7c4

		Model: {'id': 'b7ea61087f5842ac8f6957895597c7c4', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.016, 'ICIR': 0.139, 'Rank IC': 0.035, 'Rank ICIR': 0.218}, 'data_train_vec': ['2023-06-15', '2025-09-14'], 'train_time_vec': ['2026-06-15', '2026-06-15'], 'rank_icir': '0.218', 'weight': '0.049'}

	Recorder: 8eb7c1ae2bcb43dfb426a6ecf3462774

		Model: {'id': '8eb7c1ae2bcb43dfb426a6ecf3462774', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.013, 'ICIR': 0.127, 'Rank IC': 0.035, 'Rank ICIR': 0.333}, 'data_train_vec': ['2024-06-15', '2025-12-14'], 'train_time_vec': ['2026-06-15', '2026-06-15'], 'rank_icir': '0.333', 'weight': '0.075'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260615_19 798556879805029037 (Recorders: 4/5)

	Recorder: e3fcef8c166a4c3cab9fd53dab2e1700

		Model: {'id': 'e3fcef8c166a4c3cab9fd53dab2e1700', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.002, 'ICIR': 0.019, 'Rank IC': 0.022, 'Rank ICIR': 0.151}, 'data_train_vec': ['2021-06-15', '2025-03-14'], 'train_time_vec': ['2026-06-15', '2026-06-15'], 'rank_icir': '0.151', 'weight': '0.034'}

	Recorder: fb69a152a16e4017acf396df92137ff6

		Model: {'id': 'fb69a152a16e4017acf396df92137ff6', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.005, 'ICIR': 0.033, 'Rank IC': 0.036, 'Rank ICIR': 0.278}, 'data_train_vec': ['2022-06-15', '2025-06-14'], 'train_time_vec': ['2026-06-15', '2026-06-15'], 'rank_icir': '0.278', 'weight': '0.063'}

	Recorder: e316a79e0d724424a6058ce4aa8e5d28

		Model: {'id': 'e316a79e0d724424a6058ce4aa8e5d28', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.016, 'ICIR': 0.155, 'Rank IC': 0.032, 'Rank ICIR': 0.253}, 'data_train_vec': ['2023-06-15', '2025-09-14'], 'train_time_vec': ['2026-06-15', '2026-06-15'], 'rank_icir': '0.253', 'weight': '0.057'}

	Recorder: c1a43e7be9b946f5ac9ffe1a5b9c8ea0

		Model: {'id': 'c1a43e7be9b946f5ac9ffe1a5b9c8ea0', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.017, 'ICIR': 0.159, 'Rank IC': 0.025, 'Rank ICIR': 0.257}, 'data_train_vec': ['2024-06-15', '2025-12-14'], 'train_time_vec': ['2026-06-15', '2026-06-15'], 'rank_icir': '0.257', 'weight': '0.058'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260615_17 727998908937693197 (Recorders: 4/5)

	Recorder: 447f06480fc94b0ba6f1cd4eb9dd1b20

		Model: {'id': '447f06480fc94b0ba6f1cd4eb9dd1b20', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.023, 'ICIR': 0.154, 'Rank IC': 0.05, 'Rank ICIR': 0.338}, 'data_train_vec': ['2021-06-15', '2025-03-14'], 'train_time_vec': ['2026-06-15', '2026-06-15'], 'rank_icir': '0.338', 'weight': '0.076'}

	Recorder: 7fbdebcf58164247b0d0857b9fd71311

		Model: {'id': '7fbdebcf58164247b0d0857b9fd71311', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.026, 'ICIR': 0.165, 'Rank IC': 0.052, 'Rank ICIR': 0.306}, 'data_train_vec': ['2022-06-15', '2025-06-14'], 'train_time_vec': ['2026-06-15', '2026-06-15'], 'rank_icir': '0.306', 'weight': '0.069'}

	Recorder: 25681d9ecd3d4017a57500d39b160c7d

		Model: {'id': '25681d9ecd3d4017a57500d39b160c7d', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.021, 'ICIR': 0.16, 'Rank IC': 0.037, 'Rank ICIR': 0.257}, 'data_train_vec': ['2023-06-15', '2025-09-14'], 'train_time_vec': ['2026-06-15', '2026-06-15'], 'rank_icir': '0.257', 'weight': '0.058'}

	Recorder: 988d52bcf3f0494d86a3f096230db30e

		Model: {'id': '988d52bcf3f0494d86a3f096230db30e', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.011, 'ICIR': 0.091, 'Rank IC': 0.022, 'Rank ICIR': 0.201}, 'data_train_vec': ['2024-06-15', '2025-12-14'], 'train_time_vec': ['2026-06-15', '2026-06-15'], 'rank_icir': '0.201', 'weight': '0.045'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260615_17 358971104687191197 (Recorders: 4/5)

	Recorder: ce392166356a4aeda5ac83dbc31de280

		Model: {'id': 'ce392166356a4aeda5ac83dbc31de280', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.016, 'ICIR': 0.115, 'Rank IC': 0.043, 'Rank ICIR': 0.363}, 'data_train_vec': ['2021-06-15', '2025-03-14'], 'train_time_vec': ['2026-06-15', '2026-06-15'], 'rank_icir': '0.363', 'weight': '0.082'}

	Recorder: 64723b671b1446a2865b17982151e0a7

		Model: {'id': '64723b671b1446a2865b17982151e0a7', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.007, 'ICIR': 0.044, 'Rank IC': 0.043, 'Rank ICIR': 0.317}, 'data_train_vec': ['2022-06-15', '2025-06-14'], 'train_time_vec': ['2026-06-15', '2026-06-15'], 'rank_icir': '0.317', 'weight': '0.072'}

	Recorder: 910e1144c4464e0499c509eede14c6b1

		Model: {'id': '910e1144c4464e0499c509eede14c6b1', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.009, 'ICIR': 0.081, 'Rank IC': 0.034, 'Rank ICIR': 0.291}, 'data_train_vec': ['2023-06-15', '2025-09-14'], 'train_time_vec': ['2026-06-15', '2026-06-15'], 'rank_icir': '0.291', 'weight': '0.066'}

	Recorder: a5dad8189b344ce49c67e053854c5ffe

		Model: {'id': 'a5dad8189b344ce49c67e053854c5ffe', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.016, 'ICIR': 0.102, 'Rank IC': 0.022, 'Rank ICIR': 0.158}, 'data_train_vec': ['2024-06-15', '2025-12-14'], 'train_time_vec': ['2026-06-15', '2026-06-15'], 'rank_icir': '0.158', 'weight': '0.036'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260615_17 936258299855629911 (Recorders: 2/5)

	Recorder: 6b76109344254f49961f4b9cebd0d42c

		Model: {'id': '6b76109344254f49961f4b9cebd0d42c', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.005, 'ICIR': 0.034, 'Rank IC': 0.039, 'Rank ICIR': 0.239}, 'data_train_vec': ['2021-06-15', '2025-03-14'], 'train_time_vec': ['2026-06-15', '2026-06-15'], 'rank_icir': '0.239', 'weight': '0.054'}

	Recorder: 15a61671d4724891ba2a43e135c235f1

		Model: {'id': '15a61671d4724891ba2a43e135c235f1', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.019, 'ICIR': 0.143, 'Rank IC': 0.048, 'Rank ICIR': 0.284}, 'data_train_vec': ['2022-06-15', '2025-06-14'], 'train_time_vec': ['2026-06-15', '2026-06-15'], 'rank_icir': '0.284', 'weight': '0.064'}
