# Monitor metrics and run reports<a name="amazon-connect-metrics"></a>

In Amazon Connect, data about contacts are captured in contact records\. This data can include the amount of time a contact spends in each state: customer on hold, customer in queue, agent interaction time\. 

The basis for most historical and real\-time metrics in Amazon Connect is the data in the contact record\. When you create metrics reports, the values displayed for **most** \(not all\) metrics in the report are calculated using the data in the contact records\. 

Contact records are available within your instance for 24 months from the time when the associated contact was initiated\. You can also stream contact records to Amazon Kinesis to retain the data longer, and perform advanced analysis on it\.

**Tip**  
For detailed information about the activity of agents in your contact center, use [Amazon Connect agent event streams](agent-event-streams.md)\.

**Topics**
+ [What's new in metrics](upcoming-changes.md)
+ [Real\-time metrics reports](real-time-metrics-reports.md)
+ [Historical metrics reports](historical-metrics.md)
+ [Login/Logout reports](login-logout-reports.md)
+ [Amazon Connect agent event streams](agent-event-streams.md)
+ [Amazon Connect contact events](contact-events.md)
+ [Contact records data model](ctr-data-model.md)
+ [View a contact record in the UI](sample-ctr.md)
+ [About agent status](metrics-agent-status.md)
+ [About contact states](about-contact-states.md)
+ [About queued callbacks in metrics](about-queued-callbacks.md)
+ [Save custom reports](save-reports.md)
+ [Share custom reports](share-reports.md)
+ [View a shared report](view-a-shared-report.md)
+ [Publish reports](publish-reports.md)
+ [Manage saved reports \(admin\)](manage-saved-reports-admin.md)
+ [Monitoring your instance using CloudWatch](monitoring-cloudwatch.md)
+ [Logging Amazon Connect API calls with AWS CloudTrail](logging-using-cloudtrail.md)
+ [EventBridge events emitted by Amazon Connect](connect-eventbridge-events.md)