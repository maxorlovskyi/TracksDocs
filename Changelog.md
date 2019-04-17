# Changelog

    All notable changes to this project will be documented in this file.

`[15.04.17.19]`
- **Core**
    - Introduced to concept of ScreenApiControllers
- **Expenses**
    - Updated Controller fo ScreenController
- **Habit Tracks Design**
    - Fixed Issue Org Structure Footer button-View [TrelloCard #1130](https://trello.com/c/uPKxuQUm/1130-view-button-in-org-structure-module-has-issue-in-pre-tracks)
- **POS Item**
    - Added Prompt and Description fields
    - Added minor updates [TrelloCard #1096](https://trello.com/c/16ODmLrD/1096-cms)

`[15.04.16.19]`
- **Dashboard**
    - Added navigation to Incident Form module from Days Since Last Incident widget [TrelloCard #1126](https://trello.com/c/HgGdOEVr/1126-incident-form-issues-from-email)
- **Habit Tracks Design**
    - Updated CSS For Habit
- **Incident Forms**
    - Added tab notes, hidden unnecessary tabs from viewer,
    added attachments tab to viewer (for incident forms) [TrelloCard #1126](https://trello.com/c/HgGdOEVr/1126-incident-form-issues-from-email)
- **Organization Structure**
    - Fix for DMA tiers sorting, added fix for DMA view
    - Added feature for copy tiers from immediate parent to child DMA on create [TrelloCard #1127](https://trello.com/c/hPkwfu2J/1127-orgstructure-dma-fixes)
- **POS Item**
    - Updated CMS
    - Changes log, Validation, Save [TrelloCard #1096](https://trello.com/c/16ODmLrD/1096-cms)
- **Purchase Order**
    - Added permission CanDrillToPODetailItem [TrelloCard #1102](https://trello.com/c/BieiadrG/1102-create-functionality-to-allow-user-with-permissions-to-drill-to-the-item-the-po-is-tied-to)
- **User Admin**
    - Refactored User Admin module [TrelloCard #1103](https://trello.com/c/P48D3x3r/1103-retest-branch-usersadminupdated-and-merge-into-develop-if-everything-is-okay)
- **Workflow**
    - Updated workflow item start (passed username)

`[15.04.03.19]`
- **Habit Tracks Design**
    - Fixed habit styles
- **POS Item**
    - Added minor fixes to CMS [TrelloCard #1096](https://trello.com/c/16ODmLrD/1096-cms)
- **Purchase Order**
    - Added ability to drill to FAB Items from PO constructor [TrelloCard #1102](https://trello.com/c/BieiadrG/1102-create-functionality-to-allow-user-with-permissions-to-drill-to-the-item-the-po-is-tied-to)

`[15.04.02.19]`
- **POS Item**
    - Navigation from ingredients tab [TrelloCard #1096](https://trello.com/c/16ODmLrD/1096-cms)
- **Workflow**
    - Added UI for running fix scripts [TrelloCard #1124](https://trello.com/c/toOwD97F/1124-incorrect-due-date-on-extension-request-screen-because-of-mixed-up-rules-engine-associate-with-card-343-342-318)

`[15.04.01.19]`
- **Habit Tracks Design**
    - Updated Dashboard styles
- **POS Item**
    - Created module POS Items: template, DMA, Tiers, OrderingType Manager, Properties tab [TrelloCard #1096](https://trello.com/c/16ODmLrD/1096-cms)
- **Workflow**
    - Added 'Fix Rule Engine' Button to Workflow Dates Admin [TrelloCard #1125](https://trello.com/c/IzIiI4op/1125-workflow-admin-check-logic-for-fix-script)

`[15.03.28.19]`

- **Habit Tracks Design**
    - Habit CSS updates
    - Redesigned Icons for Habit [TrelloCard #1107](https://trello.com/c/mNEaMpim/1107-habit-login-design)
- **Workflow**
    - Created permission based feature for managing workflow, tasks, rule engine statuses dates [TrelloCard #1106](https://trello.com/c/CQHCiyxr/1106-discuss-concept-for-worklfow-dates-adming)

`[15.03.25.19]`

- **Reports Native**
  - Fixed Issue with Auth for SSRS. Added domain
- **Workflow**
  - Added ability to get to the Extension Request Report from the extension request page [TrelloCard #1089](https://trello.com/c/SZtAQDWA/1089-ability-to-get-to-the-extension-request-report-from-the-extension-request-page-link-directly-to-the-store-specific-report-for-ea)
- **Workflow Admin**
  - Changes to Workflow Admin grid [TrelloCard #1123](https://trello.com/c/YWvNIcfJ/1123-changes-to-workflow-admin-grid)

`[15.03.22.19]`

- **Habit Tracks Design**
  - Added Habit theme for Login screen
  - Added TracksStyle config value [TrelloCard #1107](https://trello.com/c/mNEaMpim/1107-habit-login-design)
- **Reports Native**
  - Created module with new report rendering engine
  - Fixed styles
- **Workflow**
  - Added validation for start date and end date
  - Modified Mark As Completed process, added ability to validate workflow item start date, extend parent workflow start date [TrelloCard #1105](https://trello.com/c/UEC2C5fs/1105-end-date-prior-to-start-date)
  - Fixed stored procedure for Reset nested workflows
  - Fixed sorting for Rule Engine items [TrelloCard #1088](https://trello.com/c/l7JmDrSV/1088-incorrect-due-date-on-extension-request-screen-because-of-mixed-up-rules-engine)
- **AboveStores Actual Vs Theo**
  - Added feature for update Theo Usage by selected value in Qty [TrelloCard #1108](https://trello.com/c/G3G4PcQq/1108-avt-load-usage-grid-same-as-po-adjustment)
- **My Workflows**
  - Added same permissions as for Evaluation Workflows
- **Global Styles**
  - Fix for tables scroll issue after Chrome updates

`[15.03.15.19]`

- **TracksHelp**
  - Added Tracks Help to main screen header. Added Tracks documentation.
- **Chromecast**
  - Fixed an issue with borders around the Chromecast Content. [TrelloCard #1090](https://trello.com/c/fqZyiN7Q/1090-chromecast-content-size-issue)
- **Expenses**
  - Fixed an issue with auto-filling address for mileage [TrelloCard #1082](https://trello.com/c/2SRWZK5x/1082-address-for-mileage-is-auto-filling-a-random-address-when-manual-typing-in-the-address-field)
- **Clock Entry**
  - Prevented Terminated Employees from signin into the TimeClock app.[TrelloCard #1083](https://trello.com/c/CLTtQJAM/1083-prevent-term-employees-from-clocking-in-out-of-tracks-time-clock)
- **Workflow Extenstion Request**
  - Extended fiels "Reason" and "Notes" up to 500 characters
- **Payroll**
  - Added checking of permission 'CanEditOwnRecords' on create new record for signed employee [TrelloCard #1101](https://trello.com/c/rxafNmgl/1101-payroll-can-you-add-a-request-to-not-allow-signed-in-employee-the-ability-to-add-a-record-for-themselves)
- **Login**
  - Fixed styles of inputs, fixed visiblity on mobile devices of forms for password reset/recovery [TrelloCard #1086](https://trello.com/c/JnqOCp8T/1086-tracks-90-day-password-experation-text-fields-not-allowing-user-to-type-in-the-field)
- **Workflow**
  - Fixed issue with navigation to nested workflows from Extension Requests Modal [TrelloCard #1104](https://trello.com/c/OgjXChrH/1104-extension-request-cant-navigate-to-nested-workflows)
  - Created simple workflow creator for Incident Forms. Changed Incident Form template. [TrelloCard #1099](https://trello.com/c/2EJYYsVR/1099-workflow-incident-forms-simple-wf-creation)
- **Org Structure**
  - Fixed an issue with saving stores sorting [TrelloCard #1100](https://trello.com/c/sZWELcBM/1100-org-structure-fix-sorting-for-stores)

`[15.03.06.19]`

- **Chromecast**
  - Fixed an issue with borders around the Chromecast Content. [TrelloCard #1090](https://trello.com/c/fqZyiN7Q/1090-chromecast-content-size-issue)
- **Expenses**
  - Fixed an issue with auto-filling address for mileage [TrelloCard #1082](https://trello.com/c/2SRWZK5x/1082-address-for-mileage-is-auto-filling-a-random-address-when-manual-typing-in-the-address-field)
- **Clock Entry**
  - Prevented Terminated Employees from signin into the TimeClock app.[TrelloCard #1083](https://trello.com/c/CLTtQJAM/1083-prevent-term-employees-from-clocking-in-out-of-tracks-time-clock)
- **Workflow Extenstion Request**
  - Extended fiels "Reason" and "Notes" up to 500 characters
