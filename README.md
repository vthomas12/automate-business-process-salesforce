# Automate Your Business Process (Salesforce)

## Overview
This project demonstrates Salesforce automation for managing support cases.  
I set up **queues, assignment rules, and escalation rules** to streamline how cases are routed and escalated.  

The work was completed as part of Salesforce Trailhead’s "Automate Your Business Process" module.

## Tools Used
- Salesforce CRM (Trailhead Playground)
- Case Assignment Rules
- Case Escalation Rules
- Queues

## Process
1. **Created a Billing Support Queue**
   - Added two users: Fumiko Suzuki and Aaron Hartzler.
   - Configured it to handle billing-related cases.  

2. **Built Case Assignment Rule**
   - Routed all *new billing cases* to the Billing Support Agents queue.  

3. **Created Escalation Rule**
   - Escalated any case with reason = *Performance* after 1 hour.  
   - Notification sent to manager using a preconfigured Salesforce email template.  

4. **Test Cases**
   - Billing case: *Renew Warranty* → successfully routed to Billing Support Agents.  
   - Product Support case: *Laptop not working* → correctly escalated as expected.  

## Results
- Cases routed automatically without manual reassignment.  
- Performance-related cases escalated promptly with manager notifications.  
- Demonstrated ability to configure Salesforce support workflows end-to-end.  

## Reflection
This project gave me hands-on experience with Salesforce case management automation.  
Key learning: how assignment and escalation rules can cut down resolution time and reduce errors in customer support workflows.  
