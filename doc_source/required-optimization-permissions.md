# Security profile permissions for Forecasting, capacity planning, and scheduling<a name="required-optimization-permissions"></a>

The following images show you the security profile permissions that apply to forecasting, capacity planning, and scheduling\.

![\[Image NOT FOUND\]](http://docs.aws.amazon.com/connect/latest/adminguide/images/wfm-security-profiles-analytics.png)

![\[Image NOT FOUND\]](http://docs.aws.amazon.com/connect/latest/adminguide/images/wfm-security-profiles-scheduling.png)

 Assign the following permissions as needed to use Amazon Connect forecasting, capacity planning, and scheduling features: 
+ **Forecasting**: This permission allows you to view and edit in forecasting pages\. For example, you can create, view, publish, and delete forecast groups and forecasts, import historical data from external applications, and more\.
+ **Capacity planning**: This permission allows you to view and edit in capacity planning pages, including scenario and capacity plans\. It also allows users to import future estimated shrinkage and available FTEs\.
+ **Schedule manager**: This permission allows you to view and edit generated schedules from the schedule manager\. The view permission also enables you to view historical schedule adherence metrics\. \(Note: You still need the View Metrics Permission in addition to this permission\) 
+ **Team schedule calendar**: After a schedule is published, this permission enables you to view or edit the published schedule\. You can see the schedule calendar, but agents cannot\. The view permission also enables you to view historical schedule adherence metrics\. \(Note: You still need the View Metrics Permission in addition to this permission\)
+ **Individual schedule calendar**: This permission allows agents to view their schedule in their agent application\. 

For information about how add more permissions to an existing security profile, see [Update security profiles](update-security-profiles.md)\.

By default, the **Admin** security profile already has permissions to perform all forecasting, capacity planning, and scheduling activities\.