Salesforce Flows is an automation tool which helps us to Automate buissness process eaisly using Point and Click or declrative approach without writing a single line of a code

Flow types:

Screen flows  --> Quick action, Lightning page, Experience cloud site and more (UI
Autolaunched flows --> Another Flow, Apex, REST API   (no UI and no trigger runs at background)
Triggered flows --> Time, Date Change, Platform event (run by a trigger you specify and runs in background)


A triggered flow consist of atleast one creation and one action.

criteria defines when flow will trigger 
action define what will the flow does.

Trigger type
Schedule
Platform Event
Record


Record Trigger Flow:

Options:
Fast Field Updates   
Related Records and Actions
Run Asynchronously
Scheduled Path





When to use Fast Field Updates and when to use Action and Related records.


Field: WhatId
The WhatId field can refer to the ID of any related non-human object. It represents something other than a person, such as an account, opportunity, campaign, case, or custom object. To refer to a person object, such as contact, use WhoId.
Value: $Record > Id
Remember, data from the record that triggered the flow is stored in the $Record variable. To reference the record itself, drill down from $Record to the Id field.



Schedule Path and Schedule Flow:

Schedule Path runs based on record change, 
Schedule-Triggered Flow does all its work at a specific time and at specific Frequency

use a schedule-triggered flow when you want the flow to:

	Run at a specific time.
	Run independent of a record change.
	Run through many records at one time.
	Run daily or weekly.
