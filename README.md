# AdvertiserSimulationTool
Advertiser Simulation Tool

This solution automates the simulation process for spend and impressions.
At the beginning of the script, the user provides the required parameters.
The script then create the following tables in the database: 
prod_test.sababa_tool_production - the production figures of the defined case
prod_test.sababa_tool_simulation_factor - the desire factors based on the target anf production spend
prod_test.sababa_tool_thecube - Partial thecube table with the updated seen
prod_test.sababa_tool_impressions - Partial impressions table with the updated TOTAL_DAILY_OCCS
and EST_DAILY_OCC_IMPRESSIONS
prod_test.sababa_tool_simulation - the simulation figures based on prod_test.sababa_tool_thecube and prod_test.sababa_tool_impressions
Next, a line chart is displayed comparing the spend before and after the simulation.
At the end of the process, if the user agree for the simulation - the simulation tables name is presented, and the simulation csv file is exported to his desire folder.
