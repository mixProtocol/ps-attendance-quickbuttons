Attendance Entry Quick Buttons Plugin for PowerSchool Admin Portal

Description
This plugin adds "Current Time" and Start/End of Day buttons to the "New/Edit Daily Attendance Time" page and the Daily Attendance dashboard's time entry dialogs.  The "Current Time" button populates the associated input box with the current time of the user's computer.  The "Start/End of Day" buttons rely of the "Default Time In/Out" values of the Bell Schedule Item for which the "Use For Daily Attendance" checkbox is checked.

Notes:
The "Start/End of Day" buttons will be disabled if the Bell Schedule for the current day isn't defined or doesn't contain a Bell Schedule Item set as "Use For Daily Attendance" (with the associated "Default Time In/Out" fields set).
The stock example text, ie: "(Example entry: 08:00 AM)", is removed from the page in order to make room for the buttons.

Release History
1.11 / 20220216.01 - Fix to disable dashboard dialog buttons if no Start/End times are found in the bell schedule
1.10 / 20220215.01 - Added support for the Daily Attendance dashboard's time entry dialogs
1.00 / 20220205.01 - Initial Release

Links:
PowerSource: https://support.powerschool.com/exchange/view.action?download.id=1157
GitHub: https://github.com/mixProtocol/ps-attendance-quickbuttons

Installation
Install in System > System Settings > Plugin Management Configuration  

Do not unzip the plugin. Install the entire zip file. Be sure to enable the plugin once it's installed.  

If you are updating, you can now click on the Plugin name and then use the Update button, and then browse to the new file and click Submit.  PowerSchool will then load the update and then ask you to enable it.