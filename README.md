# Cat intracranial data

EEGLAB datasets from local and roving paradigms. Each dataset is a paired `.set` metadata file and `.fdt` float32 signal file; `_dvt` denotes deviant trials and `_std` denotes standard trials.

Associated paper: [Thalamic and cortical signals synergistically represent auditory prediction errors](https://doi.org/10.64898/2026.08.06.743264)

- Sampling rate: 1,024 Hz
- Epoch length: 512 samples
- Epoch window: -99.609375 to 399.4140625 ms

| Paradigm | Cat | Dataset | Channels | Trials |
| --- | --- | --- | ---: | ---: |
| Local | MichiLE | `MichiLE_W_dvt` | 12 | 1,820 |
| Local | MichiLE | `MichiLE_W_std` | 12 | 1,897 |
| Local | NegriLE | `NegriLE_W_dvt` | 13 | 1,076 |
| Local | NegriLE | `NegriLE_W_std` | 13 | 1,964 |
| Local | NimbLE | `NimbLE_W_dvt` | 12 | 2,848 |
| Local | NimbLE | `NimbLE_W_std` | 12 | 2,927 |
| Roving | Michi | `Michi_W_dvt` | 11 | 2,237 |
| Roving | Michi | `Michi_W_std` | 11 | 2,192 |
| Roving | Negri | `Negri_W_dvt` | 13 | 2,132 |
| Roving | Negri | `Negri_W_std` | 13 | 2,134 |
| Roving | Nimb | `Nimb_W_dvt` | 13 | 1,833 |
| Roving | Nimb | `Nimb_W_std` | 13 | 1,833 |
