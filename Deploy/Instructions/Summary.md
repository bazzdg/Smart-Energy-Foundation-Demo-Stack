## Success! Your solution has been successfully deployed and real-time Carbon Emissions data is now flowing in. 

**Power BI dashboard**

* You can download a sample Power BI desktop **.pbix** file [**here**]({PatternAssetBaseUrl}/SmartEnergyDashboardDirectQuery.pbix). (*Edge might change the extension to .zip*)
* Instructions on how to connect to data source in Power BI desktop is available [**here**](https://github.com/Azure/Azure-CloudIntelligence-SolutionAuthoringWorkspace/blob/master/docs/powerbi-configurations.md).

The AzureFunction that mines emissions and weather data is scheduled to run every 30 minutes, so it may take up to 30 minutes for the data to appear in the dashboard.


**You can connect to your Azure SQL Database with the following:**

* ***Server***: _{Outputs.sqlServer}.database.windows.net_
* ***Database***: _{Outputs.sqlDatabase}_
* ***Username***: _{Outputs.sqlServerUsername}_
* ***Password***: _\<Password provided at provision time\>_

Feel free to customise and extend the solution (for example, automate your devices to run at times of low Emissions) with the code from **https://github.com/Microsoft/Smart-Energy-Foundation-Demo-Stack**