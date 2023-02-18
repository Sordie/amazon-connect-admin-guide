# Set up contact transfers<a name="transfer"></a>

Amazon Connect enables you to set up different kinds of transfers:
+ [Agent\-to\-agent transfers](setup-agent-to-agent-transfers.md): For example, if you want agents to be able to transfer calls or tasks to other agents\. 
+ [Transfers to a specific agent](transfer-to-agent.md): For example, if you want to route contacts to the last agent the customer interacted with, or route contacts to agents who have specific responsibilities\.
+ [Transfers to queues](quick-connects.md): For example, if you want to transfer the contact to a sales, support, or escalation queue\. To do this, create a [queue quick connect](how-quick-connects-work.md#queue-quick-connects)\. This works with voice, chat, and task contacts\.
+ [Transfers to phone numbers](quick-connects.md): For example, if you want to transfer the contact to a phone number, such as an on\-call pager\. To do this, create an phone number quick connect\.

## Overview of steps<a name="transfer-overview"></a>

**To set up call transfers and quick connects**

1. Choose a flow type based on what you want to do: Transfer to agent or Transfer to queue\. Phone number transfers do not require a specific type of contact flow\.

1. Create and publish the flow\. 

1. Create a quick connect for the type of transfer to enable: **Agent**, **Queue**, or **Phone number**\.

   When you create the **Agent** or **Queue** quick connect, select a flow that matches the type of transfer to enable\. **Phone number** quick connects require only a phone number, and do not allow you to set a queue or flow\.

1. Add the quick connect that you created to any queue used in a flow for which to enable contact transfer, such as the queue used in the flow for incoming contacts\.

1. Make sure the queue is in a routing profile assigned to the agents who transfers contacts\. 