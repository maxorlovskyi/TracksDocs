# Expenses Module User Guide

> Expenses Module is for the Company Expenses.
There are two pages: 1st - Summary Page and 2nd - Expenses Details page.

Expenses Permissions

- Can Change Emrg Email
- Can Create
- Can Delete
- Can Edit
- Can Post
- Can Re-Approve
- Can See expenses By Org Id
- Can Show

Table of Content

- [Expenses Module User Guide](#expenses-module-user-guide)
  - [Summary Page](#summary-page)
    - [Expense Status](#expense-status)
    - [New Expense](#new-expense)
    - [Post Selected](#post-selected)
  - [Expense Details](#expense-details)
    - [Expense Details Grid](#expense-details-grid)
    - [Expense Detail Account type](#expense-detail-account-type)
      - [Expense Detail Bus Meal Modal Window](#expense-detail-bus-meal-modal-window)
      - [Expense Detail Mileage Modal Window](#expense-detail-mileage-modal-window)
      - [Expense Detail Others Modal Window](#expense-detail-others-modal-window)

## Summary Page

1st page shows Summary Expenses Grid. Grid has columns:

| Column Name    |   Type   | Description                                                                |
| -------------- | :------: | -------------------------------------------------------------------------- |
| Edit           |  button  | Navigates to expense details page                                          |
| Context Menu   |  button  | Expense's parameters (Edit, Remove; if approved - Post)                    |
| Checkbox       | checkbox | Select the checkbox to post expense (avaliable just for approved expenses) |
| Status         |   text   | Current [status](#expense-statuses) of expense                             |
| Username       |   text   | Username of user who created expense                                       |
| Fullname       |   text   | User who is log in                                                         |
| Employee Id    |   text   | Corp Emloyee Id number                                                     |
| Business Date  |   date   | Create's date                                                              |
| Total          |  money   | Total spend for one expense                                                |
| Period         |   text   | Pay Period                                                                 |
| Mrg            |   text   | Manager's email                                                            |
| Submitted By   |   text   | Username of user who submitted the expense                                 |
| Submitted Date |   date   | Date when the expense was submitted                                        |
| Approved By    |   text   | Username of user who approved the expense                                  |
| Approved Date  |   date   | Date when the expense was approved                                         |
| Posted By      |   text   | Username of user who posted the expense                                    |
| Posted Date    |   date   | Date when the expense was posted                                           |

### Expense Status

Shows the Expenses' Status, can be

- New - the  expense is new and not ready to review by manager
- Submitted -  the expense is submitted and ready to review/approve
  > Now expense can be approved or unsubmitted based on manager decision
- Approved - the expense approved by the manager
  > Now expense can be approved or unapproved based on manager decision
- Posted - the approved expense
  >manager email is set in in the User Account. If user email is the same as manager email this user can approve the expense

The Expenses Module footer on Summary Page has 3 buttons.

- New Expense - Create new expense
- Post Selected - By default this button is non active. If posted expense selected it can be posted from this button
- Expenses Filter - can be Default or All , **Default** shows New, Subbmited and Approved Expenses. **All** - shows New, Submited, Approved and Posted Expenses

### New Expense

To create new expense user has to choose Business Date and Period of expense and to click the button **`Create`**. Click a button **`Cancel`** for the cancelation.

- Business Date (`required`) - by default, today's date, but can be chosen a date when an expense was
- Employee Id - by default, user number is set in the User Account (User Module)
- Full name - by default, user full name is set in the User Account (User Module)
- Period - by default

![New Expense](/assets/expenses/NewExpense.jpg)

### Post Selected

To Post one/multiple expenses user has to select them by checking checkbox inside expense grid.  

![New Expense](/assets/expenses/PostSelected.jpg)

## Expense Details

### Expense Details Grid

On the Summary Page click to **`Edit`** button for one expense and watch expenses details on the Expenses Details Page. Expenses Details Grid has columns:

| Column Name  |  Type  | Description                                     |
| ------------ | :----: | ----------------------------------------------- |
| Edit         | button | Shows expense details modal window              |
| Context Menu | button | Expense's parameters (Attachment, Edit, Delete) |
| Account      |  text  | Account name and account type                   |
| Depertament  |  text  | By default from User Module                     |
| Information  |  text  | Expense information                             |
| Amount       | Money  | Spent money for the each expense type           |
| Date         |  Date  | Date when the expense was created               |

>Information - Shows some expenses details depend on Account Expense Type

![New Expense](/assets/expenses/Types.jpg)

>If expense has attachment (proof for an expense), go to the Context Menu - Click **`Attachment`** and watch expence detail attachment

![New Expense](/assets/expenses/Attachment.jpg)

>Attachment could be edit. If Attachment was PDF or DOC document it is can be opened in new Tab.!!!! Can be printed.

### Expense Detail Account type

- Bus Meal
- Bus Mileage
- Others

#### Expense Detail Bus Meal Modal Window

**`Expense Info`**

- Expense Date (`required`) - by default, today's date, but can be chosen a date when an expense was
- Amount - How many money was spent for the expense detail
- Departament - by default, set in the User Account (User Module)
- People - People count for the expense detail
- Location (`non required`)- Location of expense
- Attachment (`required`) - The user can attach proof for an expense (for example check)
- Notes (`non required`)- Could be added some notes

**`Meal People`**

People count for the expense detail, can be added or removed

> `Add people` - To click the button user can add people to the expense. Insude the text area, the user can type the name.

![New Expense](/assets/expenses/ExpensedetailMeal.jpg)

#### Expense Detail Mileage Modal Window

**`Expense Info`**

- Expense Date (`required`) - by default, today's date, but can be chosen a date when an expense was
- Amount - How many money was spent for the expense detail
- Departament - by default, set in the User Account (User Module)
- Period - by default
- Miles - How many miles have been traveled????
- Rate - by default, set in the User Account (User Module)
- Round Trip - Check box can be select if it was a round trip and can be selected automatically if 1st Waypoint the same as last Waypoint
- Attachment (`required`) - The user can attach proof for an expense (for example gas receipt)
- Notes (`non required`) - Could be added some notes

**`Waypoints`**

Destination points for the expense details.

>Add Point - To click the button user can add 2 or more locations (destinations). User can type the address or find point on the Google Map or click to **`Search`** icon to find store address automaticly (from Organization Structure).

![New Expense](/assets/expenses/ExpensedetailMillage.jpg)

#### Expense Detail Others Modal Window

**`Expense Info`**

- Expense Date - (`required`) - by default, today's date, but can be chosen a date when an expense was
- Amount - How many money was spent for the expense detail
- Departament - by default, set in the User Account (User Module)
- Location (`non required`) - Location of expense
- Attachment (`required`) - The user can attach proof for an expense
- Notes (`non required`) - Could be added some notes

![New Expense](/assets/expenses/ExpensedetailOthers.jpg)

The Expenses Details Module footer has 4 buttons.

- Expenses - To go back to the Summary Page
- Add Detail - Add Expense Detail Account type
- Expense Info -  Information about the expense. Shows
  - Status
  - Total Amount
  - Prepared Date
  - Eployee Id
  - Mrg Email
  - Period
  - User Name

>If some information was change it is can be updeted
  
Also, user can submit new expense, approve submitted expense, and post approved expense!!!!  
  
- Expense Report - Expense's Report, can be printed
