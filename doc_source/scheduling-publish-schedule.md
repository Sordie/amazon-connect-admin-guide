# Generate, review, and publish a schedule by using Schedule Manager<a name="scheduling-publish-schedule"></a>

Amazon Connect is designed to generate the least number of shifts for agents based on the forecasted demand pattern and configured constraints to hit the optimization goal\.

After you create shift activities, shift profiles, staffing groups and staffing group rules, you can generate a schedule\. 

1. Log in to the Amazon Connect console with an account that has security profile permissions for **Scheduling**, **Schedule manager \- Edit**\. 

   For more information, see [Security profile permissions for Forecasting, capacity planning, and scheduling](required-optimization-permissions.md)\. 

1. On the Amazon Connect navigation menu, select **Analytics and optimization**, **Scheduling**\.

1. Choose the **Schedule Manager** tab, and then choose **Generate schedule**\. 

1. Enter a name and description for the schedule\.

1. In the **Schedule input** section, select the forecast group from the dropdown menu\.

   Currently you cannot schedule for multiple forecast groups\.

1. Specify the duration of the schedule \- the start and end dates\. You can schedule up to 18 weeks out\.

1. Under **Optimize schedule for**, choose **Service level** or **Average speed of answer**\.

1. Average speed of answer \(ASA\) is an alternative to using service level percentage targets\. For example, if an ASA is set to 30 seconds, the capacity planning and scheduling system will optimize headcount / schedules to ensure that the goal is met\.  
![\[Image NOT FOUND\]](http://docs.aws.amazon.com/connect/latest/adminguide/images/asa-gen-schedule.png)

1. Choose **Generate schedule**\.
**Note**  
Amazon Connect generates a draft schedule\. It will not be visible to agents or supervisors until you publish it\.

1. In the list of schedules, the schedule you created shows a status of **In progress**\. It takes 5\-30 minutes to generate, depending on the number of agents, number of configured rules, schedule duration, and more\. After the schedule is generated, it's status is **Complete** or **Failed**\.

1. To view any warnings and breaches of rules or constraints breaches, choose the warnings icon to learn more\.   
![\[Image NOT FOUND\]](http://docs.aws.amazon.com/connect/latest/adminguide/images/wfm-scheduling-warnings.png)

1. When the status is **Complete**, choose the draft schedule to view it\. The following image shows a sample schedule:  
![\[Image NOT FOUND\]](http://docs.aws.amazon.com/connect/latest/adminguide/images/wfm-scheduling-supervisors-schedule.png)

   Schedulers can:
   + View schedules for all agents\.
   + Pick a date to view a specific shift\.
   + Navigate back to today's date\.
   + View failed rules and goals\.

1. When you're satisfied with the schedule, choose **Publish**\. You'll get a confirmation page\. Choose **Proceed** to make the schedule official\!   
![\[Image NOT FOUND\]](http://docs.aws.amazon.com/connect/latest/adminguide/images/wfm-scheduling-publish-confirmation.png)

   Staff \(agents\) and supervisors specified in the staffing groups can now view the schedule\. See the following topics to learn about their experience: 
   + [How supervisors view published schedules](scheduling-view-schedule-supervisors.md)
   + [How agents view their schedule](scheduling-view-schedule-agents.md)

## Edit a schedule<a name="scheduling-edit-schedule"></a>

Before publishing a schedule, you might want to edit it\. For example, if you notice that all the agents are scheduled to be on break at the same time and no one is scheduled to take contacts\.

You can: 
+ Change agent shift start and/or end time, duration\.
+ Change activity shift start and/or end time, duration\.
+ Add an activity to one or more agents shift\.
+ Remove or replace activity from an agent shift\.
+ Copy an entire shift from one agent to another\.
+ Recompute metrics to ensure schedule adjustments result in better service level \(SL%\) or occupancy\.

![\[Image NOT FOUND\]](http://docs.aws.amazon.com/connect/latest/adminguide/images/wfm-scheduling-edit-schedule.png)