# Data

 This repo features the benchmarked data for the master's thesis `Evaluating Intra-Application Communication and Data Access in Serverless Application`

 The data under [statistics](./statistics/) contains the main benchmarks.

 The data under [statistics_24_hours](./statistics_24_hours/) contains the benchmarks of hourly runs across 24 hours in order to measure variance occurring on inter-process communication latency measurements performed on a Google Cloud Platform VM.

 The data under [statistics_checkout_without_calcs](./statistics_checkout_without_calcs/) contains the benchmarks performed to establish the effect on measured inter-process communication latencies when removing background computational tasks from a service.

Each run is in a folder tagged `<environment>_<application>_<ipc>_yyyy_mm_dd_hh_mm_ss`.

 The raw data is found in the respective folder under `raw_data.csv`. It has been preprocessed to only keep the relevant fields under `clean.csv`.