# IIS Monitoring Plugin

## Overview

The IIS Monitoring Plugin extends the Windows Performance Counter Monitor with **pre-configured measures for Internet Information Services**

| Name | IIS (Internet Information Services) Monitoring Plugin
| :--- | :---
| Author | Andreas Grabner (andreas.grabner@dynatrace.com)
| Supported dynaTrace Version | >= 5.5
| Supported IIS Version | Tested with: IIS 6 & 7
| License | [dynaTrace BSD](dynaTraceBSD.txt) 
| Support | [Not Supported ](https://community.compuwareapm.com/community/display/DL/Support+Levels#SupportLevels-Community)
| Downloads | [IIS Monitoring Plugin](dynaTrace_PerfMonIIS_v3.2.zip)
| Release History | Version 3.2

## Screenshots

**Verify Installed Plugin in Server Preferences->Plugins**  
![images_community/download/attachments/23594447/import_monitor.PNG](images_community/download/attachments/23594447/import_monitor.PNG)  
  
**Create a new Windows Performance Monitor for your System Profile**  
![images_community/download/attachments/23594447/create_monitor.PNG](images_community/download/attachments/23594447/create_monitor.PNG)  
  
**Give it the name IIS Performance Monitor (name is important if you want to use the attached dashboard)**  
![images_community/download/attachments/23594447/create_monitor_1.PNG](images_community/download/attachments/23594447/create_monitor_1.PNG)  
  
**List of subscribed IIS specific performance counters**  
![images_community/download/attachments/23594447/create_monitor_2.PNG](images_community/download/attachments/23594447/create_monitor_2.PNG)  
  
**The package also includes the following dashboard.**  
![images_community/download/attachments/23594447/IIS_Dashboard.PNG](images_community/download/attachments/23594447/IIS_Dashboard.PNG)

## Install Description

1) Extract the attached zip file to your file system  
2) Open the Server Preferences dialog and open the Plugins tab  
4) Choose "Import JAR ..." and select the extracted file "com.dynatrace.diagnostics.plugin.PerfMonIIS_3.2.0.0.jar"  
5) Verify that the plugin was correctly installed. Verify that the plugin "IIS Performance Monitor" shows up in the list of installed plugins  
  
In order to subscribe to IIS Performance Measures you have to:  
1) Edit your System Profile  
2) Add a new Monitor  
3) Select "Windows Performance Monitor"  
4) Specify "IIS Performance Monitor" as the monitors name (This is important if you also want to use the IIS Monitoring Dashboard that is attached to this plugin)  
5) Specify the hostname of IIS in the monitor properties  
6) View a list of all Measures that you now have subscribed. You can view and modify the list on the Measures tab  
  
**IIS Dashboard**  
1) Open the Dashboard (Internet Information Services.dashboard.xml) that is part of the download package.  
2) You will be prompted to specify the data source as the original datasource is not accessible. Select the System Profile that contains the Monitor with the name "IIS Performance Monitor"  
3) The dashboard is configured to refresh every 10 seconds


