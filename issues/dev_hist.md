As a data engineer, i need to demonstrate efficient ways to process IEX HIST, pcap data

Functional notes
- integrate IEX_hist_parser into messages. 
- Host landing bucket where repo points to raw, process. 
- Cron tab automation
- test dask workload memory overflow (r5-xlarge)
- tbd spark streaming 

Acceptance
- IEX HIST - pcap TOPS and DEEP processed to parquet... might need spark.
- Basic pivots of hist data in notebooks with required libraries (pyarrow, dask, sfs3, etc.) shown. 

