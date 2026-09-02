# params 
 {'predict_dates': [{'start': '2026-09-02', 'end': '2026-09-02'}], 'provider_uri': '~/.qlib/qlib_data/cn_data/', 'uri_folder': '~/.qlibAssistant/mlruns/', 'analysis_folder': '~/.qlibAssistant/analysis/', 'pfx_name': 'p', 'sfx_name': 's', 'model_name': 'Linear', 'dataset_name': 'Alpha158', 'stock_pool': 'csi300', 'step': 60, 'rolling_type': 'expanding', 'model_filter': ['.*'], 'rec_filter': [{'ic': 0.001}, {'icir': 0.001}, {'rankic': 0.001}, {'rankicir': 0.001}]}



 # model info 

Experiment: EXP_CatBoostModel_Alpha158_csi300_custom_step0_s_20260902_19 163072333442014494 (Recorders: 2/5)

	Recorder: 5344043a8442400b8931bad52f621b17

		Model: {'id': '5344043a8442400b8931bad52f621b17', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.016, 'ICIR': 0.082, 'Rank IC': 0.029, 'Rank ICIR': 0.19}, 'data_train_vec': ['2022-09-02', '2025-09-01'], 'train_time_vec': ['2026-09-02', '2026-09-02'], 'rank_icir': '0.190', 'weight': '0.083'}

	Recorder: b9873eae6f644822a6350da480a0e559

		Model: {'id': 'b9873eae6f644822a6350da480a0e559', 'model': 'CatBoostModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.016, 'ICIR': 0.063, 'Rank IC': 0.018, 'Rank ICIR': 0.114}, 'data_train_vec': ['2023-09-02', '2025-12-01'], 'train_time_vec': ['2026-09-02', '2026-09-02'], 'rank_icir': '0.114', 'weight': '0.050'}
Experiment: EXP_LGBModel_Alpha158_csi300_custom_step0_s_20260902_19 645589966962644843 (Recorders: 3/5)

	Recorder: e6d9c39ac94142578c4907c5b24ce3fe

		Model: {'id': 'e6d9c39ac94142578c4907c5b24ce3fe', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.005, 'ICIR': 0.034, 'Rank IC': 0.016, 'Rank ICIR': 0.117}, 'data_train_vec': ['2021-09-02', '2025-06-01'], 'train_time_vec': ['2026-09-02', '2026-09-02'], 'rank_icir': '0.117', 'weight': '0.051'}

	Recorder: 2cae519a269e4f8c9aa71b37afdad0ff

		Model: {'id': '2cae519a269e4f8c9aa71b37afdad0ff', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.021, 'ICIR': 0.114, 'Rank IC': 0.032, 'Rank ICIR': 0.215}, 'data_train_vec': ['2022-09-02', '2025-09-01'], 'train_time_vec': ['2026-09-02', '2026-09-02'], 'rank_icir': '0.215', 'weight': '0.094'}

	Recorder: 63c5de98082a47e69174909dc50c738b

		Model: {'id': '63c5de98082a47e69174909dc50c738b', 'model': 'LGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.01, 'ICIR': 0.057, 'Rank IC': 0.011, 'Rank ICIR': 0.072}, 'data_train_vec': ['2023-09-02', '2025-12-01'], 'train_time_vec': ['2026-09-02', '2026-09-02'], 'rank_icir': '0.072', 'weight': '0.032'}
Experiment: EXP_DEnsembleModel_Alpha158_csi300_custom_step0_s_20260902_16 611610971774401804 (Recorders: 3/5)

	Recorder: 670133620fe24f60984d786ab706f754

		Model: {'id': '670133620fe24f60984d786ab706f754', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.017, 'ICIR': 0.086, 'Rank IC': 0.028, 'Rank ICIR': 0.164}, 'data_train_vec': ['2021-09-02', '2025-06-01'], 'train_time_vec': ['2026-09-02', '2026-09-02'], 'rank_icir': '0.164', 'weight': '0.072'}

	Recorder: 7afb6f32584140dd9d1148d22395b03b

		Model: {'id': '7afb6f32584140dd9d1148d22395b03b', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.031, 'ICIR': 0.134, 'Rank IC': 0.042, 'Rank ICIR': 0.245}, 'data_train_vec': ['2022-09-02', '2025-09-01'], 'train_time_vec': ['2026-09-02', '2026-09-02'], 'rank_icir': '0.245', 'weight': '0.108'}

	Recorder: a3fccc85b4bf479a93ecde1a6a8f4e9c

		Model: {'id': 'a3fccc85b4bf479a93ecde1a6a8f4e9c', 'model': 'DEnsembleModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.004, 'ICIR': 0.014, 'Rank IC': 0.011, 'Rank ICIR': 0.058}, 'data_train_vec': ['2023-09-02', '2025-12-01'], 'train_time_vec': ['2026-09-02', '2026-09-02'], 'rank_icir': '0.058', 'weight': '0.025'}
Experiment: EXP_LinearModel_Alpha158_csi300_custom_step0_s_20260902_16 616618702643412214 (Recorders: 5/5)

	Recorder: 73b794f0b8374d6fb2ed6375843d25b7

		Model: {'id': '73b794f0b8374d6fb2ed6375843d25b7', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.021, 'ICIR': 0.102, 'Rank IC': 0.03, 'Rank ICIR': 0.178}, 'data_train_vec': ['2021-09-02', '2025-06-01'], 'train_time_vec': ['2026-09-02', '2026-09-02'], 'rank_icir': '0.178', 'weight': '0.078'}

	Recorder: 12b57c2df23d4af387793c019d04c910

		Model: {'id': '12b57c2df23d4af387793c019d04c910', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.039, 'ICIR': 0.202, 'Rank IC': 0.037, 'Rank ICIR': 0.233}, 'data_train_vec': ['2022-09-02', '2025-09-01'], 'train_time_vec': ['2026-09-02', '2026-09-02'], 'rank_icir': '0.233', 'weight': '0.102'}

	Recorder: 9d931606968b416c8595f6608410d86a

		Model: {'id': '9d931606968b416c8595f6608410d86a', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.006, 'ICIR': 0.024, 'Rank IC': 0.002, 'Rank ICIR': 0.009}, 'data_train_vec': ['2023-09-02', '2025-12-01'], 'train_time_vec': ['2026-09-02', '2026-09-02'], 'rank_icir': '0.009', 'weight': '0.004'}

	Recorder: ac5359c83f224bc29187973a36495019

		Model: {'id': 'ac5359c83f224bc29187973a36495019', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.008, 'ICIR': 0.025, 'Rank IC': 0.005, 'Rank ICIR': 0.018}, 'data_train_vec': ['2024-09-02', '2026-03-01'], 'train_time_vec': ['2026-09-02', '2026-09-02'], 'rank_icir': '0.018', 'weight': '0.008'}

	Recorder: 5884a5ed2f4b4aac88fed5ee3fe35edb

		Model: {'id': '5884a5ed2f4b4aac88fed5ee3fe35edb', 'model': 'LinearModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.071, 'ICIR': 0.343, 'Rank IC': 0.051, 'Rank ICIR': 0.27}, 'data_train_vec': ['2025-09-02', '2026-06-01'], 'train_time_vec': ['2026-09-02', '2026-09-02'], 'rank_icir': '0.270', 'weight': '0.119'}
Experiment: EXP_XGBModel_Alpha158_csi300_custom_step0_s_20260902_16 236182729608997734 (Recorders: 2/5)

	Recorder: 59c33deb82e0494cb8c0c1bb5d98d241

		Model: {'id': '59c33deb82e0494cb8c0c1bb5d98d241', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.007, 'ICIR': 0.033, 'Rank IC': 0.025, 'Rank ICIR': 0.148}, 'data_train_vec': ['2021-09-02', '2025-06-01'], 'train_time_vec': ['2026-09-02', '2026-09-02'], 'rank_icir': '0.148', 'weight': '0.065'}

	Recorder: fa68962651014ab8afddb8e4d5092935

		Model: {'id': 'fa68962651014ab8afddb8e4d5092935', 'model': 'XGBModel', 'dataset': 'Alpha158', 'ic_info': {'IC': 0.013, 'ICIR': 0.057, 'Rank IC': 0.04, 'Rank ICIR': 0.247}, 'data_train_vec': ['2022-09-02', '2025-09-01'], 'train_time_vec': ['2026-09-02', '2026-09-02'], 'rank_icir': '0.247', 'weight': '0.108'}
