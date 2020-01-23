# Changelog

    All notable changes to this project will be documented in this file.

`[15.01.23.20]`

- **Global**
    - CCS changes jicon (coaliance theme)
    - CSS updates (wizard, tooltip, MIT tracker)
    - Fix for durandalAjax

- **Time Clock**
    - CSS Clock Entry (active employees window) [TrelloCard #1340](https://trello.com/c/uscLJ4F4/1340-add-colors-to-clocked-out-for-break-and-clocked-in-joaquin-has-given-his-approval-that-it-would-be-useful)

- **Organization Structure**
    - Fix for displaying effective tax rate
    - Updated effective tax rate logic for store by Ownership [TrelloCard #1342](https://trello.com/c/rmVhnIiF/1342-remove-ability-to-change-tax-on-store-summary-screen-force-them-to-use-effective-tax-screen)
    - Moved sq feet fields to Rankings tab [TrelloCard #1344](https://trello.com/c/5rdpJSGO/1344-real-estate-request-add-new-feild-on-rankings-tab)

- **Adjustments**
    - Validation for details
    - Updated adj details validation [TrelloCard #1343](https://trello.com/c/O357PT1I/1343-not-allowing-zero-dollar-blank-adjustments-in-tracks)

- **Order Manager**
    - Added ability to refund orders

- **Order Call Center**
    - Order Call Center Fix [TrelloCard #1](https://trello.com/c/CYxfC65T/1-order-call-center)

- **MIT Tracker**
    - Reverted binding to WF's logic, added weeks with alert, added stores list to create wizard summary, fixed issues about moving over locked weeks
    - Added filtering by orgUnitId, by trainee name
    - Used orgUnits as lookup for vacation organization [TrelloCard #1349](https://trello.com/c/qvUhl56d/1349-mit-tracker-feedback-1-16-20)
 
- **Tracks Mobile**
    - Updated CSS for tracks mobile

- **Purchase Orders**
    - Added ability to move batch to store
    - Validation fixes for moving POs/batches to other stores [TrelloCard #1332](https://trello.com/c/tykBC6Pi/1332-po-move-to-another-store)

`[15.01.15.20]`

- **Purchase Orders**
    - Reverted multiple selection for invoice
    - Added confirm pop-up on batches removing

- **POS Item**
    - Fixed issue about tooltip provider

- **MIT Tracker**
    - Create wizard
    - Create wizard steps
    - Create wizard validation, completed steps
    - Create wizard - progress bar, step header, code refactoring
    - Added summary employees grid to create wizard
    - Minor fixes for create wizard, create contract mapper
    - Modified api models, saving process updates
    - Added api client method to obtain schedule data from db
    - Modified training loading, added update after moving, added deleting
    - Added vacations feature: create, delete, display
    - Edit training modal
    - MIT Tracker CSS
    - Added tab view, added alerts tab
    - Ability to lock weeks
    - Locked weeks save, get, validate before add
    - Locked weeks handlers, fixed issues, re-made UI
    - Changed create wizard to use single store for training type, fixed timeline issues about scale and DLT [TrelloCard #1328](https://trello.com/c/ldgjENaP/1328-mit)
    - Breaking of shift on locked week, schedule issue view on create 
    - Binding of MIT trainings to WF's [TrelloCard #1349](https://trello.com/c/qvUhl56d/1349-mit-tracker-feedback-1-16-20)

- **Order Call Center**
    -  Order Call Center Admin [TrelloCard #1](https://trello.com/c/CYxfC65T/1-order-call-center)

- **Tracks Mobile**
    - Change password from mobile version
    - CSS mobile  fix for change password
    - Fixed bugs and code refactoring [TrelloCard #1208]()
    - Fixed bug (create new expense)
    - fix bugs [TrelloCard #1336]()

- **Labor Management**
    - CSS fix Labor Management (legend, job info) [TrelloCard #1350](https://trello.com/c/4egLKvwC/1350-labor-management-css-updates)

`[15.12.31.19]`

- **Global**
    - Extracted timeline and sortable table to react-ui
    - Sortable grid without tracks redux

- **Sales Count**
    - Fixed issue about external totals, fixed cashiers, drawers update issue
    - Fixed issue with broken cashier or drawer for sales count
    - Fixed issue with denomination updates on sales count type changed [TrelloCard #1251](https://trello.com/c/TcCJXMsS/1251-setup-sales-count-denominations-for-pretracks)

- **Tracks Mobile**
    - Fixed CSS issues on the iPhone in task [TrelloCard #1279](https://trello.com/c/kA1nWcRi/1279-mobile-dropdown-update)
    - CSS mobile app update for KPI

- **Call Order Center**
    - Call order center
    - Reducers
    - CSS Order Call Center
    - Fixing issues. Updated JIcons
    - Fixing issues, Redesigned to Call CorporateApi for Process/Cancel order [TrelloCard #1](https://trello.com/c/CYxfC65T/1-order-call-center)

- **Order Manager**
    - Autoload fix based on timeout
    - Fixed issue about source type refreshing [TrelloCard #1327](https://trello.com/c/y5AshxVV/1327-order-manager-changes)

- **JIcons**
    - New icons: clone, email, n/a, phone-on-call, user-add
    - Menu, profile, email, clock, mobile, house

- **Purchase Orders**
    - Added ability to transfer PO between stores/batches
    - Applied transfer feature when batchMode is off, added permission
    - Added POs cleanup on batches load
    - Moved "Edit" to the grid [TrelloCard #1333](https://trello.com/c/Gdu86z19/1333-discuss-purchase-orders-module)

- **POS Item**
    - Added view selector to 86 tab and ability to remove availability [TrelloCard #1334](https://trello.com/c/ScSdDsGf/1334-add-ability-to-remove-86-items)

- **Workflow Admin**
    - Added sortable for grid
    - Used sortable.table from POS Item and fixed bug
    - Added ability to save sort order
    - Fixes for saving order [TrelloCard #1182](https://trello.com/c/f0D4Ceg2/1182-workflow-admin)

- **MIT Tracker**
    - Timeline by weeks
    - Reverted position calculation by month
    - Added context menu on timeline item, used new development standart for MIT module
    - Completed mit module context infrastructure [TrelloCard #1328](https://trello.com/c/ldgjENaP/1328-mit)

- **Timeline**
    - Added dragging, resizing by basic interval
    - Basic interval resizing for timeline map [TrelloCard #1328](https://trello.com/c/ldgjENaP/1328-mit)

- **Job Codes**
    - Added ask: "do you want to save changes" and had changed validation process
    - Added validation for Min Rate and Max Rate [TrelloCard #1311](https://trello.com/c/37Ia7Bry/1311-job-codes-module)

`[15.12.04.19]`

- **Global**
    - Api Client fix

- **Login**
    - Added service for old password validation
    - Minor fix for old password validation
    - CSS fix login for login screen
    - Added checking old password before reset [TrelloCard #291](https://trello.com/c/732k8izv/291-user-password-db-validation)

- **MIT Tracker**
    - Drag and drop fixes, timeline refactoring, saving new point process
    - Automation: Applied new approach for back-end [TrelloCard #1328](https://trello.com/c/ldgjENaP/1328-mit)

- **Timeline**
    - Fixes for draggable element positions, fixes for highlights positions, code refactoring
    - Timeline map fix (Invalid focus date range issue)
    - Fixed daylight saving time issue [TrelloCard #1328](https://trello.com/c/ldgjENaP/1328-mit)

- **Call Order Center**
    - Module development [TrelloCard #1](https://trello.com/c/CYxfC65T/1-order-call-center)

- **Order manager**
    - Made tabs and source types visible by permissions [TrelloCard #1327](https://trello.com/c/y5AshxVV/1327-order-manager-changes)

`[15.12.02.19]`

- **Call Order Center**
    - Reverted update for Newtonsoft
    - Module development [TrelloCard #1](https://trello.com/c/CYxfC65T/1-order-call-center)

- **Reset Password**
    - Changed process validation
    - Changed bugs [TrelloCard #1129](https://trello.com/c/Du1WAyZC/1129-tracks-password-expires-reset-window-has-bug)

- **Login**
    - Modified pwd recovery/reset validation api, client models
    - Changed process validation password for "recovery password"
    - Fixed bugs in task and changed UI [TrelloCard #1129](https://trello.com/c/Du1WAyZC/1129-tracks-password-expires-reset-window-has-bug)
    - Changed process pasword validation in "password expired" and "pasword recovery" if forgot your password

- **POS Item**
    - 86 updates, changed storeId to orgUnitId [TrelloCard #1334](https://trello.com/c/ScSdDsGf/1334-add-ability-to-remove-86-items)

- **Sales Count**
    - Dynamic groups api
    - Added dynamic groups to UI
    - Replaced total group inputs by dynamic values from json, added username, updatedDate [TrelloCard #1326](https://trello.com/c/SvSpYUGn/1326-till-counts-changes)

- **Organization Structure**
    - Fixed drawers map issue on create new store

`[15.11.25.19]`

- **Global**
    - Deleted ignored files

- **JIcons**
    - Updated Tracks Menu to use JIcons
    - Added new icons to JIcons Library


- **Employee Messaging**
    - Addedd property Delivery Method
    - Changed UI "Recipient" setting using delivery method [TrelloCard #1321](https://trello.com/c/AFtFxyjx/1321-empoyeemessaging-delivery-method)
    - Validation fix

- **Tracks Mobile**
    - Changed UI
    - Fixed references

- **Time Clock**
    - CSS Clock Entry Updates
    - CSS fix (mobile view) and small mobile fix

- **Login**
    - Added api action to validate user password [TrelloCard #291](https://trello.com/c/732k8izv/291-user-password-db-validation)

- **Query Constructor**
    - Implemented drop-down for multi-selecting values
    - Implemented simple Query
    - Implemented update for value item text from loaded options
    - Fixed issue clear operation [TrelloCard #1181](https://trello.com/c/kQThrOHU/1181-query-ctor)

- **Order Call Center**
    - Module development [TrelloCard #1](https://trello.com/c/CYxfC65T/1-order-call-center)

- **MIT Tracker**
    - Resize mode [TrelloCard #1328](https://trello.com/c/ldgjENaP/1328-mit)

`[15.11.14.19]`

- **Global**
    - Fixed csproj
    - CSS fix Tracks (mini footer botton)

- **Employee Messagign**
    - Added validate button and message name in current folder
    - Changed position for button settings
    - Fixed UI issue on Message Details
    - Fixed bug with section "Buttons setting"

- **Expenses Mobile**
    - Fixed details account issue [TrelloCard #1030](https://trello.com/c/AR4YsJHZ/1030-tracks-mobile-expenses)

- **Query Constructor**
    - Fixed issue on show query results
    - CSS fix for Query Constructor Module [TrelloCard #1316](https://trello.com/c/ED9hl26x/1316-query-constructor)

- **Inventories**
    - Fix for selected inventories on shell reducer changes

- **My Messages**
    - Message List view, List Item template
    - Added My Messages mobile module
    - Added SendDate to get messages result
    - Fixed bugs in task [TrelloCard #1310](https://trello.com/c/z43Snm7J/1310-my-message-module)
    - Fix for select message when quiz was answered

- **My Messages Mobile**
    - Added messageDetail and procces button
    - Fixed bugs with buttonFunc and UI
    - Added Toasts for Quiz [trelloCard #1309](https://trello.com/c/PeXRPAKm/1309-design-fo-my-messages-mobile-ver-employee-portal)

- **MIT Tracker**
    - Created module
    - Added test data, customized items, added tooltip
    - Added ability to move timeline items
    - Handled data update after item was moved
    - Fixed issues on focus change, fixed drag issues, added styles, added highlights
    - Created basic API, added manager vacation shifts [TrelloCard #1326](https://trello.com/c/ldgjENaP/1328-mit)

- **Users**
    - Added flag IgnoreClockInRequirement, remove old permission
    - Added message on sending alert Change Password [TrelloCard #1209](https://trello.com/c/TN0PY27t/1209-employee-user-passowords)

- **Order Call Center**
    - Created Order Call Center [TrelloCard #1](https://trello.com/c/CYxfC65T/1-order-call-center)

- **Order Manager**
    - Added uber
    - React-Hooks [TrelloCard #1195](https://trello.com/c/FiIB38mx/1195-order-manager-module)

- **Sales Counts**
    - Added Till Count type
    - Added Drawers to Org structure
    - Add flags to SalesCountTypes
    - Manage fields visibility by flags
    - Fixed lookup loading
    - Fixed Drawers validation [TrelloCard #1305](https://trello.com/c/nZRAzHAy/1305-till-counts-sales-counts-enhancments-in-tracks)

- **Store API**
    - MaskedCard number after token processing

- **Taxes**
    - Fixed bug in task [TrelloCard #1180](https://trello.com/c/b66mlvYg/1180-theme-updates)

- **Tracks Mobile**
    - Redesign [TrelloCard #1323](https://trello.com/c/reMWfriJ/1323-track-mobile-design)

- **Time Clock**
    - Fix for job codes list [TrelloCard #1306](https://trello.com/c/9Ex0mQP2/1306-clock-entry)
    - Added client checking of app version to fix caching issue
    - CSS update for footer icons
    - Fix for TracksVersionCheckAttribute [TrelloCard #1314](https://trello.com/c/aB1LRGi7/1314-clock-entry-check-is-version-updated-on-auth)
    - Fix for select default job
    - Added logic to confirm entered mileage
    - Added needAskForMileage and needAskForTips to employee data result (job codes), used in clockIn wizard. fixed issue with tips
    - Minor fixes for mileage entering
    - CSS updates for ClockEntry and Login
    - Fix for clock in user out of store [TrelloCard #1303](https://trello.com/c/HMREJLZj/1303-timeclock-check-manager-corp-id-for-entering-mileage)
    - Fix for mileage confirm from different store

- **Workflow**
    - Added ClockIn validation on Sign By Employee
    - Fixes for async tasks controllers, fixed validation sign by emp sp name [TrelloCard #1312](https://trello.com/c/0XGBtXZ8/1312-workflow-employee-sign-allow-sign-workflow-as-employee-only-if-employee-is-clocked-in)
    - Added message after create by query [TrelloCard #1317](https://trello.com/c/pdUcyk1A/1317-workflow-add-message-after-creating-workflows-by-query)

- **Workflow Admin**
    - Fixes for validation
    - Added validation for fild Target
    - Created class with border for dependency block

- **Workflow Form Admin**
    - Validation fixes [TrelloCard #1122](https://trello.com/c/t3QcMmFq/1122-workflow-form-admin)

- **Workflow Form**
    - Added validation page name
    - Fix bug with process "add new page" task [TrelloCard #1122](https://trello.com/c/t3QcMmFq/1122-workflow-form-admin)
    - Fixed email validation

`[15.10.25.19]`

- **Employee Messaging**
    - Changed in multiselect job codes
    - Added JobGroups lookup api, updated server models for jobLink
    - Extended JobLink model on Get
    - Changed save message method to use json
    - UI Job Codes and Job Groups
    - Update job liks method
    - Changed the selection process Job Codes
    - Changed way for select target locations [TrelloCard #1198](https://trello.com/c/aqwsCKjn/1198-employee-messaging)

- **Global**
    - Using Typescript 3.5 as default typescript version
    - Updated csproj

- **Job Codes**
    - Added job groups lookup, added job group id to contract [TrelloCard #1307](https://trello.com/c/opcTYVhf/1307-job-codes-add-job-groups-selector)

- **POSMenu**
    - Fix for uber eats calories [TrelloCard #1297](https://trello.com/c/wYQt409m/1297-uber-menus)

- **ROR User**
    - Added new unit manager for ROR (only stores and DMAs) [TrelloCard #1300](https://trello.com/c/vNynAHPL/1300-ror-orgunits)

- **Time Clock**
    - CSS Clock Entry Updates

- **Workflow Form**
    - Fix for wf form validation
    - Added same form name validation on server side [TrelloCard #1133](https://trello.com/c/6TvflvBD/1133-workflow-forms)
    - Fixed server side validation
    - Fixed bugs for admin [TrelloCard #1122](https://trello.com/c/t3QcMmFq/1122-workflow-form-admin)

`[15.10.21.19]`

- **Global**
    - Added my messages icons
    - Added feature that allows work on workflows (configurable from system) when employee on clock

- **Time Clock**
    - CSS Updates for Clock Entry (buttons)
    - Closing language switcher after language selected [TrelloCard #1288](https://trello.com/c/vhXW07gq/1288-clockentry-changes)

- **User Admin**
    - Fix for remove permission

`[15.10.17.19]`

- **Employee Messaging**
    - Added displayingTimeout property
    - Added displaying timeout to API

- **My Message**
    - Added rendering plain HTML as message text

- **Time Clock**
    - Hide employee message after 5 - 20 seconds interval
    - Added feature for rendering plain HTML as message text [TrelloCard #423](https://trello.com/c/7H8o6JnW/423-employee-messaging-enhancement-testing-feedback)

- **Workflow**
    - Added folder prop OrgUnitType, added payroll org units and payroll store button to workflow layout
    - Extended payroll unit initialization, used for workflow folders [TrelloCard #1304](https://trello.com/c/jilDYsCJ/1304-workflow-folder-change-to-select-which-store-list-need-to-use-on-workflow-module)

`[15.10.11.19]`

- **Adjustments**
    - Added logging for create, post, receive, reject [TrelloCard #1296](https://trello.com/c/k3W6bA1I/1296-add-aditional-avt-logging)

- **Inventory**
    - Changes in log modal, changed parameters for log [TrelloCard #1296](https://trello.com/c/k3W6bA1I/1296-add-aditional-avt-logging)

- **Workflow Form**
    - Fixed bugs (section QA Test) [TrelloCard #1122](https://trello.com/c/t3QcMmFq/1122-workflow-form-admin)

`[15.10.10.19]`

- **Employee Messaging**
    - Changed labels in message details [TrelloCard #1198](https://trello.com/c/aqwsCKjn/1198-employee-messaging)

- **Inventory**
    - Logging for post, pre-post [TrelloCard #1296](https://trello.com/c/k3W6bA1I/1296-add-aditional-avt-logging)

`[15.10.09.19]`

- **Employee Messagign**
    - UI updates
    - Add button - cancel - in add new message
    - Fixed minor UI issues [TrelloCard #1198](https://trello.com/c/aqwsCKjn/1198-employee-messaging)

- **FAB Items**
    - Added ability to change AVG Cost per week in Items Module [TrelloCard #1277](https://trello.com/c/eHowFsfJ/1277-ability-to-change-avg-cost-per-week-in-items-module)

- **My Messages**
    - Code refactoring

- **Payroll**
    - Fix for onchange unit subscription, fix for org unit update

`[15.10.04.19]`

- **Employee Messaging**
    - Fix for org units list (filtered dups)

- **Time Clock**
    - Fix for using jobCode for get message on clock out
    - Fixed clock in to another store, added filter by store on get messages

`[15.10.03.19]`

- **POSItem**
    - POSFile

- **Time Clock**
    - Fix for checking IsMileageEntered
    - Get message by current Job Code [TrelloCard #1303](https://trello.com/c/HMREJLZj/1303-timeclock-check-manager-corp-id-for-entering-mileage)

`[15.10.02.19]`

- **Adjustments**
    - Data format fix [TrelloCard #1285](1285-adjustment-bulk-reject)

- **Employee Messaging Admin**
    - Fix for buttons update
    - DMA organizations support, activities view
    - Fixes minor issues found by QA
    - Added max length to buttons label [TrelloCard #1299](https://trello.com/c/fBJzDQjF/1299-employee-messaging-enhancement-testing-feedback)
    - Fixes minor issues

- **Payroll**
    - Fix for payroll unit manager [TrelloCard #1293](https://trello.com/c/gUBPJnz7/1293-payroll)

- **POSItem**
    - Menu mapping update
    - Added Search to Menu [TrelloCard #1292](https://trello.com/c/pBhsfLk5/1292-menu-search)
    - Map Postmates and UberEats menus
    - Change uber menu to V2 [TrelloCard #1280](https://trello.com/c/Nfn9pWY5/1280-ubereats-menu)

- **My Messages**
    - Created my messages screen, API for it
    - UI for screen, added list of messages and message details view
    - Modified model for get messages
    - Added get attachment controller, added attachment viewer component
    - Process button controller
    - Added badge section to list selection template
    - Added response to process button, modified list view template
    - Added messageDetails, process buttons
    - Process button and optimization code [TrelloCard #1310](https://trello.com/c/z43Snm7J/1310-my-message-module)

- **Time Clock**
    - Fix for clock out issue
    - Double clock out prevention. Disabled session buttons
    - Limited the Truck Employee to enter mileage only once per day
    - Extendet clock out model with session records [TrelloCard #1288](https://trello.com/c/vhXW07gq/1288-clockentry-changes)
    - Fix for language switcher
    - Button label update, fixes around language change (placeholder, lang button name) [TrelloCard #1287](https://trello.com/c/6itcbM9M/1287-spanish-tracks-clock-in-button-update)
    - Fix for clock entry error handling, add store name to registration
    - Modified server error handler for auth employee
    - CSS Update for Clock Entry (Browser Registration)

- **Workflow**
    - Warning Pop Up for Previous Dates on Extension Request [TrelloCard #1281](https://trello.com/c/S1Z1w16T/1281-warning-pop-up-for-previous-dates-on-extension-request)
    - Process checkbox validation in training list [TrelloCard #1283](https://trello.com/c/TwII06Vx/1283-add-setting-to-disallow-users-from-signing-off-their-own-checkboxes)
    - Added field IsVisibleOnlyByOwner to workflow template 
    - Used IsVisibleOnlyByOwner for workflow grid [TrelloCard #1294](https://trello.com/c/HKiWtjoM/1294-annual-review-users-currently-can-see-all-other-users-reviews-should-only-be-able-to-see-own-reviews-supervisors-correctly-only)

`[15.09.18.19]`

- **POSItem**
    - Replaced calories by min calories and max calories
    - Image Viewer: Added item size [TrelloCard #1286](1286-change-calories-to-mincalories-add-maxcalories-display-on-positem-ui-add-to-mobile-json)

- **Adjustments**
    - Added ability to bulk reject [TrelloCard #1285](1285-adjustment-bulk-reject)

- **Mobile KPI**
    - Fixed businessDate parameter format

`[15.09.17.19]`

- **POSItem**
    - Item Image

- **POSItem/OrgStructure**
    - fixed issue with build POS Items
    - navigation between modules

- **Employee Messaging Admin**
    - Fixes for messaging admin by QA notes
    - Added message body type, validation updates
    - Ability to move to folder
    - Fix for quiz answers update
    - Server side validation for quiz
    - Validation for buttons
    - Fix for delete functional button
    - Add default ok button for message
    - Fix for saving, message text and attachment validation
    - Added button properties
    - Button settings, buttons settings saving [TrelloCard #1198](https://trello.com/c/aqwsCKjn/1198-employee-messaging)

- **Tracks Mobile**
    - Mobile Expenses: fixed bus meal
    - Fixed issue with Mobile Expense store selector
    - Mobile UI Component update
    - Minor css fix
    - KPI Grid Mobile [TrelloCard #1254](https://trello.com/c/qZYCzHJh/1254-kpi-mobile-dashboard)
    - CSS updates for Tracks Mobile (KPI coaliance theme) [TrelloCard #1254](https://trello.com/c/qZYCzHJh/1254-kpi-mobile-dashboard)

- **Time Clock**
    - Minor icon fix
    - Fixes for employee messaging buttons, added predefined note if emp, message answer is not correct [TrelloCard #1198](https://trello.com/c/aqwsCKjn/1198-employee-messaging)

- **Organization Structure**
    - Added maxOrderSizeInDollars validation, fix for default values [TrelloCard #1270](https://trello.com/c/lHloUm8s/1270-add-new-fields-to-store-lkpstoremaster-tracks-organizationstructure-corporateapi-json)

`[15.09.10.19]`

- **Tracks Mobile**
    - KPI Grid Mobile [TrelloCard #1254](https://trello.com/c/qZYCzHJh/1254-kpi-mobile-dashboard)

`[15.09.09.19]`

- **Scorm Admin**
    - Locked ability to create/edit courses in recycle bin #1267 [TrelloCard #1267](https://trello.com/c/W8Q6LI4v/1267-workflow-scorm-admin)
- **Workflow Admin**
    - Removed autosave feature, added notification on save not posted template #1262 [TrelloCard #1262](https://trello.com/c/ItlCNdlA/1262-when-cheryl-was-testing-scorm-she-edited-the-workflow-admin-for-scorm-cloud-and-all-the-users-were-deleted-because-the-workflow)
- **Jicon**
    - Added checkbox icons 
    - Added checkbox icons (two styles)
- **Tracks Mobile**
    - Mobile KPI Dashboard [TrelloCard #1254](https://trello.com/c/qZYCzHJh/1254-kpi-mobile-dashboard)
    - ApiServices, KPI Grid Mobile [TrelloCard #1254](https://trello.com/c/qZYCzHJh/1254-kpi-mobile-dashboard)
- **Employee Messaging Admin**
    - Added DAL service [TrelloCard #1198](https://trello.com/c/aqwsCKjn/1198-employee-messaging)
    - UI structure [TrelloCard #1198](https://trello.com/c/aqwsCKjn/1198-employee-messaging)
    - Employee messaging api service [TrelloCard #1198](https://trello.com/c/aqwsCKjn/1198-employee-messaging)
    - Employee messaging admin [TrelloCard #1198](https://trello.com/c/aqwsCKjn/1198-employee-messaging)
    - Validation and send messages button [TrelloCard #1198](https://trello.com/c/aqwsCKjn/1198-employee-messaging)

`[15.09.05.19]`

- **Organization Structure**
    - Changed type for IncludeNearMiles to int, added field AvgOrderTime [TrelloCard #1270](https://trello.com/c/lHloUm8s/1270-add-new-fields-to-store-lkpstoremaster-tracks-organizationstructure-corporateapi-json)
- **SalesCount**
    - Sales Count Changes #1275 [TrelloCard #1275](https://trello.com/c/thgpXiBo/1275-make-deposit-times-match-the-business-date-times-400am-to-359am-to-prevent-stores-from-having-to-change-the-business-date-after)
- **Adjustments**
    - Adjustment Changes #1274 [TrelloCard #1274](https://trello.com/c/APPQZYkY/1274-adjustment-enhancement-permission)
- **POSItems**
    - Added calories field, used in Global JSON  #1270 [TrelloCard #1270](https://trello.com/c/lHloUm8s/1270-add-new-fields-to-store-lkpstoremaster-tracks-organizationstructure-corporateapi-json)
- **Workflow**
    - Added warning for completed item on extension request #1272 [TrelloCard #1272](https://trello.com/c/z1AIK5th/1272-warning-to-pop-up-when-requesting-an-extension-on-a-completed-course-within-a-flame-workflow)
    - Showing scorm course status only if item started #1268 [TrelloCard #1268](https://trello.com/c/pcyapz82/1268-add-scorm-course-status-to-ui)


`[15.09.04.19]`

- **Organization Structure**
    - Added new fields to store model IncludeNearMiles, MaxOrderSizeInDollars, MaxOrderSizeInEntrees [TrelloCard #1270](https://trello.com/c/lHloUm8s/1270-add-new-fields-to-store-lkpstoremaster-tracks-organizationstructure-corporateapi-json)
- **Order Manager**
    - Implemented features from task [TrelloCard #1269](https://trello.com/c/M1SoWvyA/1269-order-manager)

`[15.09.03.19]`

- **Workflow**
    - Added Scorm Course result, menu icons [TrelloCard #1268](https://trello.com/c/pcyapz82/1268-add-scorm-course-status-to-ui)
- **Jicons**
    - Added search icon
- **Scorm Admin**
    - Created scorm admin screen [TrelloCard #1267](https://trello.com/c/W8Q6LI4v/1267-workflow-scorm-admin)
    - Versions view, actions, version modal [TrelloCard #1267](https://trello.com/c/W8Q6LI4v/1267-workflow-scorm-admin)
    - Saving process, validation, versions creation [TrelloCard #1267](https://trello.com/c/W8Q6LI4v/1267-workflow-scorm-admin)
    - Fix for move to folder, naming validation, selection fix [TrelloCard #1267](https://trello.com/c/W8Q6LI4v/1267-workflow-scorm-admin)
    - Fixed save on course select [TrelloCard #1267](https://trello.com/c/W8Q6LI4v/1267-workflow-scorm-admin)
    - Disabled from moving courses in recycle bin [TrelloCard #1267](https://trello.com/c/W8Q6LI4v/1267-workflow-scorm-admin)

`[15.08.29.19]`

- **Workflow**
    - Added scorm identifier [TrelloCard #1266](https://trello.com/c/aHbWERmP/1266-workflow-scorm-few-courses-for-one-registration-create-two-courses-fe-english-spanish-and-choose-one-of-them-on-workflow-create)
- **Login**
    - Fix for reset expired password

`[15.08.26.19]`

- **ClockEntry**
    - Clock in alert icon replaced by button [TrelloCard #1261](https://trello.com/c/7JDadimP/1261-timeclock-design-update)
- **ClockEntry Style**
    - CSS Clock Entry icons [TrelloCard #1261](https://trello.com/c/7JDadimP/1261-timeclock-design-update)
    - CSS Clock Entry Updates [TrelloCard #1261](https://trello.com/c/7JDadimP/1261-timeclock-design-update)
    - CSS Clock Entry - buttons updates [TrelloCard #1261](https://trello.com/c/7JDadimP/1261-timeclock-design-update)
- **POSItem**
    - Fixed issue with MenuVersions [TrelloCard #1230](https://trello.com/c/DrBlR4Ht/1230-update-cms-menu-creating)
- **Workflow**
    - Select scorm course version feature [TrelloCard #1266](https://trello.com/c/aHbWERmP/1266-workflow-scorm-few-courses-for-one-registration-create-two-courses-fe-english-spanish-and-choose-one-of-them-on-workflow-create)
    - Modified scorm config, refactored API [TrelloCard #1266](https://trello.com/c/aHbWERmP/1266-workflow-scorm-few-courses-for-one-registration-create-two-courses-fe-english-spanish-and-choose-one-of-them-on-workflow-create)
    - Updated scorm flow for versions using [TrelloCard #1266](https://trello.com/c/aHbWERmP/1266-workflow-scorm-few-courses-for-one-registration-create-two-courses-fe-english-spanish-and-choose-one-of-them-on-workflow-create)

`[15.08.20.19]`

- **POSItems**
    - UI for 86. Refactored 86 structure [TrelloCard #1249](https://trello.com/c/3Wjv1SOG/1249-positems-86)
- **POSMenu**
    - Updated Menu JSON [TrelloCard #1258](https://trello.com/c/QbSQOPHc/1258-split-global-and-storemenu-for-mobile-pos-menus)
- **Workflow Form**
    - Enabled save progress regardless of required fields status [TrelloCard #1259](https://trello.com/c/nufN9nxF/1259-workflow-form-the-save-progress-button-only-enables-after-the-required-fields-are-completed-was-wondering-if-we-could-have-it-sa)
- **Clock Entry**
    - Added feature of Employee Messaging [TrelloCard #1198](https://trello.com/c/aqwsCKjn/1198-employee-messaging)
    - Updated break issue alert [TrelloCard #1264](https://trello.com/c/tAOSJY5m/1264-time-clock-updates-show-employee-message-for-clock-in-clock-out-add-break-issue-message)
    - Added JIcons [TrelloCard #1264](https://trello.com/c/tAOSJY5m/1264-time-clock-updates-show-employee-message-for-clock-in-clock-out-add-break-issue-message)
- **Store Control Panel**
    - Added StoreApiClient, StoreControlPanel [TrelloCard #1246](https://trello.com/c/YCZc7FT7/1246-storeapi-kiosk-online-status)
- **JIcons**
    - Fixed build for JIcons
- **CSS for Habit**
    - CSS Reports Module button fix

`[15.08.07.19]`

- **Org. Structure**
    - Added maxOrderValue [TrelloCard #1257](https://trello.com/c/Mhu0xpZH/1257-org-structure-add-maxordervalue)
- **POSItems**
    - Created 86 feature. Server logic [TrelloCard #1249](https://trello.com/c/3Wjv1SOG/1249-positems-86)

`[15.08.05.19]`

- **Coaliance Theme**
    - CSS Updates for Tracks mobile
- **Org. Structure**
    - Fixed validation message in org structure page for "Set Online" feature [TrelloCard #1220](https://trello.com/c/4V7oAjpt/1220-organization-structure-do-not-allow-setup-store-as-online-if-store-missing-mid-tid-gid-ip-address-lon-lan)
    - Change StoreMasterId to StoreId in Error message when set stores online [TrelloCard #1220](https://trello.com/c/4V7oAjpt/1220-organization-structure-do-not-allow-setup-store-as-online-if-store-missing-mid-tid-gid-ip-address-lon-lan)
- **POSItems**
    - Added new flag and category description [TrelloCard #1247](https://trello.com/c/TYUEGTfm/1247-positem-add-to-item-new-flag-isentree-add-to-categories-new-column-description-update-bhw-menu-payload)
    - Modified models for menu reprocess [TrelloCard #1247](https://trello.com/c/TYUEGTfm/1247-positem-add-to-item-new-flag-isentree-add-to-categories-new-column-description-update-bhw-menu-payload)
    - Fixed Ip Address validation in OrgStructure Set Online feature [TrelloCard #1247](https://trello.com/c/TYUEGTfm/1247-positem-add-to-item-new-flag-isentree-add-to-categories-new-column-description-update-bhw-menu-payload)

`[15.08.05.19]`

- **TracksMobile**
    - Fixed issue with mobile styles
- **Workflow**
    - Fixed scorm create registration logic, added ability to open scorm item in new tab by setting [TrelloCard #1235](https://trello.com/c/znb2eLXX/1235-new-workflow-item-type-scorm-course)
    - Obtained and deserialized registration result [TrelloCard #1235](https://trello.com/c/znb2eLXX/1235-new-workflow-item-type-scorm-course)
- **Coaliance Theme**
    - CSS Updates for Tracks mobile. Coaliance Theme

`[15.07.31.19]`

- **POSMenu**
    - Added Store Mapping Item Menu push Fixed Login issue [TrelloCard #1260](https://trello.com/c/VGuyaeYm/1260-add-ability-to-pos-menus-for-mobile-for-db)
    - updated contract for storeApi [TrelloCard #1230](https://trello.com/c/DrBlR4Ht/1230-update-cms-menu-creating)
- **Workflow**
    - Added Scorm result getting [TrelloCard #1235](https://trello.com/c/znb2eLXX/1235-new-workflow-item-type-scorm-course)
    - Obtained and deserialized registration result [TrelloCard #1235](https://trello.com/c/znb2eLXX/1235-new-workflow-item-type-scorm-course)
    - Refactored API for getting scorm registration report [TrelloCard #1235](https://trello.com/c/znb2eLXX/1235-new-workflow-item-type-scorm-course)
- **Workflow Schedule**
    - Added reset status to 0 feature [TrelloCard #1244](https://trello.com/c/hcFBPJbz/1244-workflow-schedule-reset-status-to-0-feature)
- **JIcons**
    - Created SVG icons with color
- **TracksMobile**
    - Removed AwesomeIcons from TracksMobile 
    - Made CSS Updates for Tracks mobile. Added new Icons

`[15.07.25.19]`

- **Dashboard**
    - Added refund reason options in Check reproduction widget [TrelloCard #1213](https://trello.com/c/h8OvYhTg/1213-update-refund-process)
- **Mobile Expenses**
    - Fixed loading of attachments [TrelloCard #1193](https://trello.com/c/RjpvHrwc/1193-tracks-mobile-version-iphone)
- **Users**
    - Minor UI fixes
- **Tracks Mobile**
    - Fixed components/layouts/scrolls [TrelloCard #1030](https://trello.com/c/AR4YsJHZ/1030-tracks-mobile-expenses)
- **Login**
    - Fixed recovery password fields 
- **Order Manager**
    - Added filter parameters to URL [TrelloCard #1195](https://trello.com/c/FiIB38mx/1195-order-manager-module)
    - Fixed Source filter [TrelloCard #1195](https://trello.com/c/FiIB38mx/1195-order-manager-module)
    - Added order manager menu items [TrelloCard #1195](https://trello.com/c/FiIB38mx/1195-order-manager-module)
    - Changes for local parameters [TrelloCard #1195](https://trello.com/c/FiIB38mx/1195-order-manager-module)
    - Fixed prop name for BHW contract [TrelloCard #1195](https://trello.com/c/FiIB38mx/1195-order-manager-module)
- **CSS For Habit**
    - Created CSS styles for Login and TracksMobile [TrelloCard #1107](https://trello.com/c/mNEaMpim/1107-habit-login-design)
- **Org. Structure**
    - Added filtering by Store Id and Store Name in DMA Organizations [TrelloCard #1219](https://trello.com/c/j9v75CVs/1219-dma-add-easy-way-to-find-store-cross-dmas)
    - Added selected org unit title in DMA Tab [TrelloCard #1219](https://trello.com/c/j9v75CVs/1219-dma-add-easy-way-to-find-store-cross-dmas)
    - Added validation before setting stores online [TrelloCard #1219](https://trello.com/c/j9v75CVs/1219-dma-add-easy-way-to-find-store-cross-dmas)
- **JIcons**
    - Added JIcons, used in Tracks Mobile
- **Workflow**
    - Created tables, api services for scorm courses and registration for scorm courses [TrelloCard #1235](https://trello.com/c/znb2eLXX/1235-new-workflow-item-type-scorm-course)
    - Scorm courses item start and opening process [TrelloCard #1235](https://trello.com/c/znb2eLXX/1235-new-workflow-item-type-scorm-course)
    - Open scorm course in iframe [TrelloCard #1235](https://trello.com/c/znb2eLXX/1235-new-workflow-item-type-scorm-course)
    - Check scorm course progress [TrelloCard #1235](https://trello.com/c/znb2eLXX/1235-new-workflow-item-type-scorm-course)

`[15.07.10.19]`

- **StoreStatusUI**
  - Updated UI, added additional info [TrelloCard #1231](https://trello.com/c/JoOizERr/1231-update-storestatus-ui-add-ipaddress)
- **Org.Structure**
  - Fixed issue [TrelloCard #1194](https://trello.com/c/MPIPky3F/1194-dma-stores-with-dash)
  - Added additional validation for StoreHours [TrelloCard #1214](https://trello.com/c/r4IrQLzp/1214-org-structure-fix-issue-with-hours)
- **Workflow**
  - Tasks based on Training Group request [TrelloCard #1184](https://trello.com/c/FFwapujD/1184-workflow)
- **Reports**
  - Updated Native report view to support drill functionality [TrelloCard #1217](https://trello.com/c/0NKkoUcu/1217-report-native-create-same-drill-flow-as-on-reports-pdf)
- **Labor Management**
  - New flag for Above Guide [TrelloCard #1203](https://trello.com/c/UWLk8F0q/1203-above-guide-new-flag-isfixed)
- **Org.Structure**
  - Added GID input [TrelloCard #1186](https://trello.com/c/BVErL770/1186-add-groupid-to-same-areas-as-tid-and-mid-for-store-maintenance)
  - Added IP Added input
- **User**
  - Update modal window for check password requirements
  
`[15.07.03.19]`

- **Workflow**
  - Fixed workflow styles issues [TrelloCard #1171](https://trello.com/c/eYMOVahv/1171-workflow-pending-tasks-fix-css)
  - Fix script for rule engine (add logic for due date extension ) [TrelloCard #1174](https://trello.com/c/vHxsTBGg/1174-workflow-fix-script-for-rule-engine-add-logic-for-due-date-extension)
  - Overdue [TrelloCard #1196](https://trello.com/c/LO2P0dlU/1196-workflow-overdue-date)
- **Workflow Forms**
  - Changes based on feedback[TrelloCard #1202](https://trello.com/c/pMVgFPdn/1202-incident-form-changes)
  - Added security group permissions
- **Adjustments**
  - Open adjustment by moving from above stores [TrelloCard #1173](https://trello.com/c/5iVuWigl/1173-adjustments-open-adjustment-by-moving-from-above-stores)
  - Added new settings for business date validation [TrelloCard #1175](https://trello.com/c/Wlf2Vxyc/1175-adjustments-new-settings-create-new-for-current-business-date-max-days-for-business-date)
- **Employee**
  - Updated Rate History [TrelloCard #1176](https://trello.com/c/Eg5Uxrdi/1176-employee-module-changes)
- **Labor Management**
  - Fixed issue with updating above guides [TrelloCard #1177](https://trello.com/c/SWm86trv/1177-locked-schedule-cante-above-guide-hours)
- **Dashboard**
  - Fixed parameters issue for KPI grid [TrelloCard #1178](https://trello.com/c/SUB4bzE7/1178-params-for-kpi-cogs)
- **Payroll**
  - Added new Premium Pay icon [TrelloCard #1179](https://trello.com/c/N6diREKk/1179-premium-pay-icon)
- **Org.Structure**
  - Fixed issue [TrelloCard #1194](https://trello.com/c/MPIPky3F/1194-dma-stores-with-dash)
  - Updated Validation for StoreHours [TrelloCard #1197](https://trello.com/c/1vsmPZDg/1197-orgstructure-add-validation-to-stores-open-close-time)
- **CMS**
  - Updated Price Timeline. Added ability to edit prices. Fixed issues.
  - Update flow for generating menus
  - Added ability to publish menu to DoorDash
  - Added JSON viewer
- **Tracks Mobile**
  - Updated UI styles [TrelloCard #1191](https://trello.com/c/1YHMLyt3/1191-design-changes-tracks-mobile)
  - Create new custom icons library
- **Mobile Expenses**
  - Added missed functionality from Desktop version  [TrelloCard #1185](https://trello.com/c/cvG5rnVC/1185-tracks-mobile)
- **Order Manager**
  - New module based on BHW order api

`[15.05.28.19]`

- **Adjustments**
  - Fixes after testing [TrelloCard #1170](https://trello.com/c/sNpycwCy/1170-adjustments-changes)
  - Added settings, restricted business date edit
  - Removed toggle button in adjustment options modal
  - Fixes for adjustments modal after testing [TrelloCard #1175](https://trello.com/c/Wlf2Vxyc/1175-adjustments-new-settings-create-new-for-current-business-date-max-days-for-business-date)
- **CSS For Habit**
  - Updated CSS [TrelloCard #1130](https://trello.com/c/uPKxuQUm/1130-view-button-in-org-structure-module-has-issue-in-pre-tracks)
- **CMS**
  - Fixing Issues [TrelloCard #1141](https://trello.com/c/hk2bbZMM/1141-cms-testing)
  - Added new ingredient prop: POSItemLinkPriority
  - Added disabled row style
  - Tags, Meal Periods, Views Refactoring [TrelloCard #1096](https://trello.com/c/16ODmLrD/1096-cms)
- **Form Admin**
  - Preview form feature [TrelloCard #1122](https://trello.com/c/t3QcMmFq/1122-workflow-form-admin)
- **Incident Form**
  - Changed to Form [Trello Card #1145](https://trello.com/c/h3d7elQP/1145-remove-old-incident-forms)
- **Organization Structure**
  - DMA: Store rule for DMA items on the root level [TrelloCard #1136](https://trello.com/c/fdAofKHx/1136-dma-updates)
- **Workflow**
  - Fixed extension request button visibility, changes to extension modal labels [TrelloCard #1169](https://trello.com/c/3nzfwWnX/1169-extension-request-changes)
  - Workflow Admin Dates: Fix for rule engine steps sorting [TrelloCard #1174](https://trello.com/c/vHxsTBGg/1174-workflow-fix-script-for-rule-engine-add-logic-for-due-date-extension)

`[15.05.17.19]`

- **Adjustments**
  - Change business date only by permission
  - Default business date to yesterday [TrelloCard #1170](https://trello.com/c/sNpycwCy/1170-adjustments-changes)
- **CMS**
  - Where Used, Remove View All, Removed Save sort mode
  - Default Link id [TrelloCard #1096](https://trello.com/c/16ODmLrD/1096-cms)
- **Form Admin**
  - Preview modal [TrelloCard #1122](https://trello.com/c/t3QcMmFq/1122-workflow-form-admin)
- **Workflow**
  - Fix for pending tasks css [TrelloCard #1171](https://trello.com/c/eYMOVahv/1171-workflow-pending-tasks-fix-css)

`[15.05.16.19]`

- **CMS**
  - Added section Item Settings, added validation for manage ingredients
  - Item Prices
  - Fixing Issues [TrelloCard #1096](https://trello.com/c/16ODmLrD/1096-cms)
- **Employee**
  - Trim corpEmpId on change [TrelloCard #1158](https://trello.com/c/Wr2U4xxI/1158-employee-issues)
- **Expenses**
  - Fix for amount field [TrelloCard #1143](https://trello.com/c/ezosxfJy/1143-expense)
- **Form Admin**
  - Check for changes on folder change
  - Check if some form items has been updated [TrelloCard #1122](https://trello.com/c/t3QcMmFq/1122-workflow-form-admin)
- **Workflow**
  - Cleaned up extension requests code
  - Fix for server validation [TrelloCard #1169](https://trello.com/c/3nzfwWnX/1169-extension-request-changes)

`[15.05.14.19]`

- **CMS**
  - Fixing issues
- **Form Admin**
  - Added row name [TrelloCard #1122](https://trello.com/c/t3QcMmFq/1122-workflow-form-admin)
- **Organization Structure**
  - Updated style for list without levels, clone dma only for default view, modified naming method on clone dma [TrelloCard #1136](https://trello.com/c/fdAofKHx/1136-dma-updates)
- **Workflow**
  - Added approved by, approved date columns to extension requests grid [TrelloCard #1169](https://trello.com/c/3nzfwWnX/1169-extension-request-changes)

`[15.05.13.19]`

- **Above Stores**
  - Added additional fields for grouping
  - Rows visibility
  - Added new view to AvT UI, added new grid to AvT module [TrelloCard #970](https://trello.com/c/qKHSViGL/970-add-new-view-to-avt-ui)
- **CMS**
  - Fixing issues
  - Categories with Tiers. Scope Selector
  - Fixes [TrelloCard #1146](https://trello.com/c/JTlSFW6E/1146-cms-changes-050819)
  - Sorting
  - Sorting Table View [TrelloCard #1096](https://trello.com/c/16ODmLrD/1096-cms)
- **Form Admin**
  - Hide row list fix
  - Fixed issues after testing [TrelloCard #1122](https://trello.com/c/t3QcMmFq/1122-workflow-form-admin)
- **Organization Structure**
  - Updated dma stores grid, validation for tiers, DMA name, email
  - Updated DMA stores and tiers, lists replaced by grids, fixed minor issues
  - DMA updates: fix for stores sorting, hidden parent effective dates, added tab view for stores, tiers [TrelloCard #1136](https://trello.com/c/fdAofKHx/1136-dma-updates)
- **Workflow**
  - Extension Request validation updates [TrelloCard #1169](https://trello.com/c/3nzfwWnX/1169-extension-request-changes)

`[15.05.06.19]`

- **CMS**
  - Added validation to ComboObjNum [TrelloCard #1096](https://trello.com/c/16ODmLrD/1096-cms)
- **Form Admin**
  - Fixed save issue, form validation
  - Modified models after data base changes,  saving pre populate bindings
  - Api fixes
  - Saving process, versioning
  - Form save selector
  - Save form service
  - Refactored rich text control, fixes for selectors, view updates
  - Options, dependencies
  - Pages actions, page modal, lookups, rows list
  - Row properties, rich text editor
  - Folder actions, forms list, pages list
  - Created form admin module, folder structure, forms list [TrelloCard #1122](https://trello.com/c/t3QcMmFq/1122-workflow-form-admin)
- **Incident Form**
  - Modified form result process, added feature for saving last page
  - Fixed issues from email
- **Libs**
  - Updated React and Typescript for Tracks CMS
- **Organization Structure**
  - Fixed move modal issue, css of tree view issue [TrelloCard #1136](https://trello.com/c/fdAofKHx/1136-dma-updates)

`[15.04.30.19]`

- **CMS**
  - Enhanced PriceLevels Validations [TrelloCard #1096](https://trello.com/c/16ODmLrD/1096-cms)
- **Organization Structure**
  - Fixed DMA  issues after testing [TrelloCard #1136](https://trello.com/c/fdAofKHx/1136-dma-updates)
- **Incident Form**
  - Fixes by email reports

`[15.04.26.19]`

- **CMS**
  - Fixed issues from feedback [TrelloCard #1139](https://trello.com/c/4EoMoq7P/1139-cms-feedback-042619)
- **Organization Structure**
  - DMA fixes after testing [TrelloCard #1136](https://trello.com/c/fdAofKHx/1136-dma-updates)

`[15.04.25.19]`

- **CSS For Habit**
  - Updated CSS For Habit [TrelloCard #1130](https://trello.com/c/uPKxuQUm/1130-view-button-in-org-structure-module-has-issue-in-pre-tracks)
- **CMS**
  - Added validation for Prompt
  - Fixed issues from feedback [TrelloCard #1096](https://trello.com/c/16ODmLrD/1096-cms)

`[15.04.24.19]`

- **CSS For Habit**
  - Updated CSS For Habit [TrelloCard #1130](https://trello.com/c/uPKxuQUm/1130-view-button-in-org-structure-module-has-issue-in-pre-tracks)
- **CMS**
  - Ingredient Sorting
  - Saving Names [TrelloCard #1096](https://trello.com/c/16ODmLrD/1096-cms)
- **Organization Structure**
  - Added DMA views, removed tier views
  - DMA fixes [TrelloCard #1136](https://trello.com/c/fdAofKHx/1136-dma-updates)

`[15.04.23.19]`

- **CSS For Habit**
  - Fixed issue with Workflow Folders
  - Updated CSS For Habit [TrelloCard #1130](https://trello.com/c/uPKxuQUm/1130-view-button-in-org-structure-module-has-issue-in-pre-tracks)
- **CMS**
  - Added new columns to ingredient grid
  - Default OrderType, Insert/Delete ingredients
  - Loading sub ingredients, saving ingredient changes [TrelloCard #1096](https://trello.com/c/16ODmLrD/1096-cms)
- **Organization Structure**
  - Added DMA sorting, leveled list component, tiers types [TrelloCard #1136](https://trello.com/c/fdAofKHx/1136-dma-updates)

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
