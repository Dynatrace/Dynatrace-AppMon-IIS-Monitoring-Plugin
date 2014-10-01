<html xmlns="http://www.w3.org/1999/xhtml">
<head>
    <title>IIS Monitoring Plugin</title>
    <meta http-equiv="Content-Type" content="text/html; charset=UTF-8"/>
    <meta http-equiv="X-UA-Compatible" content="IE=EmulateIE8" />
    <meta content="Scroll Wiki Publisher" name="generator"/>
    <link type="text/css" rel="stylesheet" href="css/blueprint/liquid.css" media="screen, projection"/>
    <link type="text/css" rel="stylesheet" href="css/blueprint/print.css" media="print"/>
    <link type="text/css" rel="stylesheet" href="css/content-style.css" media="screen, projection, print"/>
    <link type="text/css" rel="stylesheet" href="css/screen.css" media="screen, projection"/>
    <link type="text/css" rel="stylesheet" href="css/print.css" media="print"/>
</head>
<body>
                <h1>IIS Monitoring Plugin</h1>
    <div class="tablewrap">
        <table>
<thead class=" "></thead><tfoot class=" "></tfoot><tbody class=" ">    <tr>
            <td rowspan="1" colspan="1">
        <p>
Name    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
IIS (Internet Information Services) Monitoring Plugin for dynaTrace 3.2+, 4.x    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Description    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
The IIS Monitoring Plugin extends the Windows Performance Counter Monitor with <strong class=" ">pre-configured measures for Internet Information Services</strong>    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Plug-In Version    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
3.2    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Compatible with    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
dynaTrace Diagnostics 3.2+, 4.x    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Tested with:    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
IIS 6 &amp; 7    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Author    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Andreas Grabner (andreas.grabner@dynatrace.com)    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Download    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
<a href="attachments_23725272_1_dynaTrace_PerfMonIIS_v3.2.zip">IIS Monitoring Plugin</a>    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
License    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
<a href="attachments_5275722_2_dynaTraceBSD.txt">dynaTrace BSD</a>    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Support    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
<a href="https://community/display/DL/Support+Levels#SupportLevels-Community">Not Supported </a>    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Screenshots    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
<strong class=" ">Verify Installed Plugin in Server Preferences-&gt;Plugins</strong><br/>            <img src="images_community/download/attachments/23594447/import_monitor.PNG" alt="images_community/download/attachments/23594447/import_monitor.PNG" class="" />
        <br/><br/><strong class=" ">Create a new Windows Performance Monitor for your System Profile</strong><br/>            <img src="images_community/download/attachments/23594447/create_monitor.PNG" alt="images_community/download/attachments/23594447/create_monitor.PNG" class="" />
        <br/><br/><strong class=" ">Give it the name IIS Performance Monitor (name is important if you want to use the attached dashboard)</strong><br/>            <img src="images_community/download/attachments/23594447/create_monitor_1.PNG" alt="images_community/download/attachments/23594447/create_monitor_1.PNG" class="" />
        <br/><br/><strong class=" ">List of subscribed IIS specific performance counters</strong><br/>            <img src="images_community/download/attachments/23594447/create_monitor_2.PNG" alt="images_community/download/attachments/23594447/create_monitor_2.PNG" class="" />
        <br/><br/><strong class=" ">The package also includes the following dashboard.</strong><br/>            <img src="images_community/download/attachments/23594447/IIS_Dashboard.PNG" alt="images_community/download/attachments/23594447/IIS_Dashboard.PNG" class="" />
            </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Install Description    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
1) Extract the attached zip file to your file system<br/>2) Open the Server Preferences dialog and open the Plugins tab<br/>4) Choose &quot;Import JAR ...&quot; and select the extracted file &quot;com.dynatrace.diagnostics.plugin.PerfMonIIS_3.2.0.0.jar&quot;<br/>5) Verify that the plugin was correctly installed. Verify that the plugin &quot;IIS Performance Monitor&quot; shows up in the list of installed plugins<br/><br/>In order to subscribe to IIS Performance Measures you have to:<br/>1) Edit your System Profile<br/>2) Add a new Monitor<br/>3) Select &quot;Windows Performance Monitor&quot;<br/>4) Specify &quot;IIS Performance Monitor&quot; as the monitors name (This is important if you also want to use the IIS Monitoring Dashboard that is attached to this plugin)<br/>5) Specify the hostname of IIS in the monitor properties<br/>6) View a list of all Measures that you now have subscribed. You can view and modify the list on the Measures tab<br/><br/><strong class=" ">IIS Dashboard</strong><br/>1) Open the Dashboard (Internet Information Services.dashboard.xml) that is part of the download package.<br/>2) You will be prompted to specify the data source as the original datasource is not accessible. Select the System Profile that contains the Monitor with the name &quot;IIS Performance Monitor&quot;<br/>3) The dashboard is configured to refresh every 10 seconds    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Compatibility Matrix    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
        <p>
Disclaimer    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
    </p>
            </td>
        </tr>
</tbody>        </table>
            </div>
    <p>
    </p>
    <div class="tablewrap">
        <table>
<thead class=" ">    <tr>
            <td rowspan="1" colspan="1">
        <p>
&nbsp;    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
<a href="IIS_Monitoring_Plugin.html">File</a>    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
<a href="IIS_Monitoring_Plugin.html">Modified</a>    </p>
            </td>
        </tr>
</thead><tfoot class=" "></tfoot><tbody class=" ">    <tr>
            <td rowspan="1" colspan="1">
                </td>
                <td rowspan="1" colspan="1">
        <p>
PNG File                    <a href="https://community/download/attachments/23594447/create_monitor_2%5B1%5D.PNG?api=v2">create_monitor_2[1].PNG</a>    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Aug 30, 2014by<a href="    /community/display/~marcia.beierle@compuware.com ">Beierle Marcia</a>    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
                </td>
                <td rowspan="1" colspan="2">
        <p>
            <img src="images_community/download/attachments/23594447/create_monitor_2[1].PNG" alt="images_community/download/attachments/23594447/create_monitor_2[1].PNG" class="confluence-embedded-image" />
            </p>
    <p>
Labels    </p>
<ul class="label-list has-pen "><li class="no-labels-message ">    <p>
No labels    </p>
</li><li class="labels-edit-container ">    <p>
<a href="IIS_Monitoring_Plugin.html">Edit Labels</a>    </p>
</li></ul>    <p>
    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
                </td>
                <td rowspan="1" colspan="1">
        <p>
PNG File                    <a href="https://community/download/attachments/23594447/icon.png?api=v2">icon.png</a>    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Apr 02, 2012by<a href="    /community/display/~wolfgang.gottesheim@compuware.com ">Wolfgang Gottesheim</a>    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
                </td>
                <td rowspan="1" colspan="2">
        <p>
            <img src="images_community/download/attachments/23594447/icon.png" alt="images_community/download/attachments/23594447/icon.png" class="confluence-embedded-image" />
            </p>
    <p>
Labels    </p>
<ul class="label-list has-pen "><li class="no-labels-message ">    <p>
No labels    </p>
</li><li class="labels-edit-container ">    <p>
<a href="IIS_Monitoring_Plugin.html">Edit Labels</a>    </p>
</li></ul>    <p>
    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
                </td>
                <td rowspan="1" colspan="1">
        <p>
File                    <a href="https://community/download/attachments/23594447/import_monitor.PNG?api=v2">import_monitor.PNG</a>    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Mar 08, 2010by<a href="    /community/display/~andreas.grabner@compuware.com ">Andreas Grabner</a>    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
                </td>
                <td rowspan="1" colspan="2">
        <p>
            <img src="images_community/download/attachments/23594447/import_monitor0.PNG" alt="images_community/download/attachments/23594447/import_monitor0.PNG" class="confluence-embedded-image" />
            </p>
    <p>
Labels    </p>
<ul class="label-list has-pen "><li class="no-labels-message ">    <p>
No labels    </p>
</li><li class="labels-edit-container ">    <p>
<a href="IIS_Monitoring_Plugin.html">Edit Labels</a>    </p>
</li></ul>    <p>
    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
                </td>
                <td rowspan="1" colspan="1">
        <p>
File                    <a href="https://community/download/attachments/23594447/create_monitor.PNG?api=v2">create_monitor.PNG</a>    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Mar 08, 2010by<a href="    /community/display/~andreas.grabner@compuware.com ">Andreas Grabner</a>    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
                </td>
                <td rowspan="1" colspan="2">
        <p>
            <img src="images_community/download/attachments/23594447/create_monitor0.PNG" alt="images_community/download/attachments/23594447/create_monitor0.PNG" class="confluence-embedded-image" />
            </p>
    <p>
Labels    </p>
<ul class="label-list has-pen "><li class="no-labels-message ">    <p>
No labels    </p>
</li><li class="labels-edit-container ">    <p>
<a href="IIS_Monitoring_Plugin.html">Edit Labels</a>    </p>
</li></ul>    <p>
    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
                </td>
                <td rowspan="1" colspan="1">
        <p>
File                    <a href="https://community/download/attachments/23594447/create_monitor_1.PNG?api=v2">create_monitor_1.PNG</a>    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Mar 08, 2010by<a href="    /community/display/~andreas.grabner@compuware.com ">Andreas Grabner</a>    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
                </td>
                <td rowspan="1" colspan="2">
        <p>
            <img src="images_community/download/attachments/23594447/create_monitor_10.PNG" alt="images_community/download/attachments/23594447/create_monitor_10.PNG" class="confluence-embedded-image" />
            </p>
    <p>
Labels    </p>
<ul class="label-list has-pen "><li class="no-labels-message ">    <p>
No labels    </p>
</li><li class="labels-edit-container ">    <p>
<a href="IIS_Monitoring_Plugin.html">Edit Labels</a>    </p>
</li></ul>    <p>
    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
                </td>
                <td rowspan="1" colspan="1">
        <p>
File                    <a href="https://community/download/attachments/23594447/IIS_Dashboard.PNG?api=v2">IIS_Dashboard.PNG</a>    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Mar 08, 2010by<a href="    /community/display/~andreas.grabner@compuware.com ">Andreas Grabner</a>    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
                </td>
                <td rowspan="1" colspan="2">
        <p>
            <img src="images_community/download/attachments/23594447/IIS_Dashboard0.PNG" alt="images_community/download/attachments/23594447/IIS_Dashboard0.PNG" class="confluence-embedded-image" />
            </p>
    <p>
Labels    </p>
<ul class="label-list has-pen "><li class="no-labels-message ">    <p>
No labels    </p>
</li><li class="labels-edit-container ">    <p>
<a href="IIS_Monitoring_Plugin.html">Edit Labels</a>    </p>
</li></ul>    <p>
    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
                </td>
                <td rowspan="1" colspan="1">
        <p>
File                    <a href="https://community/download/attachments/23594447/create_monitor_2.PNG?api=v2">create_monitor_2.PNG</a>    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Mar 08, 2010by<a href="    /community/display/~andreas.grabner@compuware.com ">Andreas Grabner</a>    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
                </td>
                <td rowspan="1" colspan="2">
        <p>
            <img src="images_community/download/attachments/23594447/create_monitor_20.PNG" alt="images_community/download/attachments/23594447/create_monitor_20.PNG" class="confluence-embedded-image" />
            </p>
    <p>
Labels    </p>
<ul class="label-list has-pen "><li class="no-labels-message ">    <p>
No labels    </p>
</li><li class="labels-edit-container ">    <p>
<a href="IIS_Monitoring_Plugin.html">Edit Labels</a>    </p>
</li></ul>    <p>
    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
                </td>
                <td rowspan="1" colspan="1">
        <p>
ZIP Archive                    <a href="https://community/download/attachments/23594447/dynaTrace_PerfMonIIS_v3.2.zip?api=v2">dynaTrace_PerfMonIIS_v3.2.zip</a>IIS Monitoring Plugin for dynaTrace 3.2    </p>
            </td>
                <td rowspan="1" colspan="1">
        <p>
Mar 08, 2010by<a href="    /community/display/~andreas.grabner@compuware.com ">Andreas Grabner</a>    </p>
            </td>
        </tr>
    <tr>
            <td rowspan="1" colspan="1">
                </td>
                <td rowspan="1" colspan="2">
        <p>
    </p>
    <p>
Labels    </p>
<ul class="label-list has-pen "><li class="no-labels-message ">    <p>
No labels    </p>
</li><li class="labels-edit-container ">    <p>
<a href="IIS_Monitoring_Plugin.html">Edit Labels</a>    </p>
</li></ul>    <p>
    </p>
            </td>
        </tr>
</tbody>        </table>
            </div>
<ul class=" "><li class="drop-zone-text hidden ">    <p>
Drag and drop to upload or browse for files    </p>
            <img src="images_community/images/icons/wait.gif" alt="images_community/images/icons/wait.gif" class="plugin_attachments_dropzone_uploadwaiticon" />
        </li></ul>    <p>
Upload fileFile description<a href="https://community/pages/downloadallattachments.action?pageId=23594447">Download All</a>    </p>
            </div>
        </div>
        <div class="footer">
        </div>
    </div>
</body>
</html>
