# Changelog
All notable changes to this project will be documented in this file.

## [15.03.22.19]

### Added
#### Habit Tracks Design
- Added Habit theme for Login screen;
- Added TracksStyle config value;
#### Reports Native
- Created module with new report rendering engine;
### Changed
##### Workflow
- Modified Mark As Completed process, added ability to validate workflow item start date, extend parent workflow start date;
- Fixed stored procedure for Reset nested workflows;
- Fixed sorting for Rule Engine items;
#### AboveStores Actual Vs Theo
- Added feature for update Theo Usage by selected value in Qty;
#### My Workflows
- Added same permissions as for Evaluation Workflows;
#### Global Styles
- Fix for tables scroll issue after Chrome updates;
### DB Changes
#### Modified Stored Procedures
- usp_WorkflowItem_Reset;
- usp_WorkflowItem_ExtensionRequest_ChangeStatus;
- usp_Workflow_Mark_As_Completed;
- usp_WorkflowItem_Mark_As_Completed;
- usp_WorkflowItem_ExtensionRequest_Get;
#### Added Stored Procedures
- usp_WorkflowItem_ResetRuleEngine;
- usp_Workflow_UpdateStartEndDate;
- usp_WorkflowItem_UpdateStartEndDate;


## [15.03.15.19]

### Added
##### TracksHelp
- Added Tracks Help to main screen header. Added Tracks documentation.
### Changed
##### Payroll
- Added checking of permission 'CanEditOwnRecords' on create new record for signed employee [TrelloCard #1101](https://trello.com/c/rxafNmgl/1101-payroll-can-you-add-a-request-to-not-allow-signed-in-employee-the-ability-to-add-a-record-for-themselves)
##### Login
- Fixed styles of inputs, fixed visiblity on mobile devices of forms for password reset/recovery [TrelloCard #1086](https://trello.com/c/JnqOCp8T/1086-tracks-90-day-password-experation-text-fields-not-allowing-user-to-type-in-the-field)
##### Workflow
- Fixed issue with navigation to nested workflows from Extension Requests Modal [TrelloCard #1104](https://trello.com/c/OgjXChrH/1104-extension-request-cant-navigate-to-nested-workflows)

## [15.03.14.19]

### Changed
##### Workflow
- Created simple workflow creator for Incident Forms. Changed Incident Form template. [TrelloCard #1099](https://trello.com/c/2EJYYsVR/1099-workflow-incident-forms-simple-wf-creation)
##### Org Structure
- Fixed an issue with saving stores sorting [TrelloCard #1100](https://trello.com/c/sZWELcBM/1100-org-structure-fix-sorting-for-stores)

## [15.03.06.19]

### Changed
##### Chromecast
- Fixed an issue with borders around the Chromecast Content. [TrelloCard #1090](https://trello.com/c/fqZyiN7Q/1090-chromecast-content-size-issue)
##### Expenses
- Fixed an issue with auto-filling address for mileage [TrelloCard #1082](https://trello.com/c/2SRWZK5x/1082-address-for-mileage-is-auto-filling-a-random-address-when-manual-typing-in-the-address-field)
##### Clock Entry
- Prevented Terminated Employees from signin into the TimeClock app.[TrelloCard #1083](https://trello.com/c/CLTtQJAM/1083-prevent-term-employees-from-clocking-in-out-of-tracks-time-clock)
##### Workflow Extenstion Request
- Extended fiels "Reason" and "Notes" up to 500 characters
