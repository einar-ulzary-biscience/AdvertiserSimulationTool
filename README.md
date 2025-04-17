# AdvertiserSimulationTool
Advertiser Simulation Tool

This solution automates the simulation process for spend and impressions.
At the beginning of the script, the user provides the required parameters.
The script then retrieves two datasets from the database: adc2_ops.thecube and adc2_dwh.pub_daily_impressions.
Next, the simulation begins — factoring the seen, TOTAL_DAILY_OCCS, and EST_DAILY_OCC_IMPRESSIONS based on the user's target parameter.
At the end of the process, a line chart is displayed comparing the spend before and after the simulation.

next step: export the data sets into CSV files ready for deployment.
