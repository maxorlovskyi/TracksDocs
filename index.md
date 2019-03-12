# **Table of Contents**
- [**Table of Contents**](#table-of-contents)
  - [**Expenses**](#expenses)
    - [**`Summary Page`**](#summary-page)
    - [**`Expense Status`**](#expense-status)
    - [**`New Expense`**](#new-expense)
    - [**`Post Selected`**](#post-selected)
  - [**Expense Details**](#expense-details)
    - [**`Expense Details Grid`**](#expense-details-grid)
    - [Expense Detail Account type](#expense-detail-account-type)
      - [**`Bus Meal`**](#bus-meal)
      - [**`Bus Mileage`**](#bus-mileage)
      - [**`Others`**](#others)

## **Expenses**

Expenses Module is for the Company Expenses.
There are two pages: 1st page - Summary Page and 2nd page - Detail page.

### **`Summary Page`**

1st page shows Summary Expenses Grid. Grid has columns:

| Column Name      | Type      |Description                                     |
| -----------------|-----------|----------------------------------------------- |
| Edit             |  button   | Navigates to expense details page              | 
| Context Menu     |  button   | Expense's parameters (Edit, Remove; if approved - Post)           | 
| Checkbox         |  checkbox | Select the checkbox to post expense (avaliable just for approved expenses)            | 
| Status           |  text     | Current [status](#expense-statuses) of expense  |
| Username         |  text     | Username of user who created expense                         |         |
| Fullname         |  text     | User's fullname 
| Employee Id      |  text     | Emloyee Id number                               
| Business Date    |  date     | Create's date                                              |
| Total            |  money    | Total spend for one expense
| Period           |  text     | Pay Period
| Mrg              |  text     | Manager's email
| Submitted By     |  text     | Username of user who submitted the expense
| Submitted Date   |  date     | Date when the expense was submitted
| Approved By      |  text     | Username of user who approved the expense
| Approved Date    |  date     | Date when the expense was approved
| Posted By        |  text     | Username of user who posted the expense
| Posted Date      |  date     | Date when the expense was posted

   
### **`Expense Status`**

Shows the Expenses' Status, can be 

- New - the new expense created by the user
- Submitted -  the expense sented from the user
- Approved - the expense accepted by the manager
- Posted - the approved expense 


The Expenses Module footer on 1st page has 3 buttons.

- **New Expense** - Create new expense
- **Post Selected** - If posted expense selected it can be posted from this button 
- **Expenses Filter** - can be Default or All , **Default** shows New, Subbmited and Approved Expenses. **All** - shows New, Submited, Approved and Posted Expenses.

### **`New Expense`**

To create new expense user has to choose Business Date and Period of expense and to click the button **Create**. 

![New Expense](/assets/expenses/newexpense.jpg "New Expense modal window")

### **`Post Selected`**

To Post multiple expenses user has to select them by checking checkbox inside expense grid.  

![New Expense](/assets/expenses/postselected.jpg "Post Selected Expenses")


## **Expense Details**

### **`Expense Details Grid`**

On the 1rst page can be choosen one expense and the 2nd page shows expense' details grid. Grid has columns:

| Column Name      | Type      |Description                                     |
| -----------------|-----------|----------------------------------------------- |
| Edit             |  button   | Shows expense details modal window             |
| Context Menu     |  button   | Expense's parameters (Attachment, Edit, Delete)|
| Account          |  text     | Account name and account type                  |
| Depertament      |  text     | 
| Information      |  text     | Expense information                            |
| Amount           |  Money    | Spent money for the each expense type          |
| Date             |  Date     | Date when the expense was created              |

### Expense Detail Account type

There are 3 account types of expense 

#### **`Bus Meal`**

**Expense Detail Meal Modal Window**

`Expense Info`

Account type - Employee Meal !!

- Expense Date - Date of expense
- Amount - How many money was spent
- Departament - User department!!!!!!
- People - People count!!!
- Location - Location of expense
- Attachment - The user can attach proof for an expense (for example check)!!!
- Notes - Add some notes

`Meal People`

- Add people - To click the button user can add people to the expense. In the text area, the user can type the name. !!

![New Expense](/assets/expenses/expensedetailmeal.jpg "Expense Detail Meal")

#### **`Bus Mileage`**

**Expense Detail Mileage Modal Window**

Account type - Gas (Mileage)

`Expense Info`

 - Expense Date - Date of expense
 - Amount - How many money was spent
 - Departament - User department!!!!!!
 - Miles - How many miles !!!!
 - Rate - !!!!!
 - Round Trip - Check box can be select if it was round trip
 - Attachment - The user can attach proof for an expense (for example gas receipt)
 - Notes - Add some notes

`Waypoints`

- Add Point - To click the button user can add location A (departure point) and location B (destination). User can type the address of location or to find point on the map or click to Search icon to find store address automaticly. 

![New Expense](/assets/expenses/expensedetailmillage.jpg "Expense Detail Mileage")

#### **`Others`**

Account type - Others!!!!!

`Expense Info`

 - Expense Date - Date of expense
 - Amount - How many money was spent
 - Departament - User department!!!!!!
 - Location - Location of expense
 - Attachment - The user can attach proof for an expense 
 - Notes - Add some notes

[New Expense](/assets/expenses/expensedetailothers.jpg "Expense Detail Others")

The Expenses Module footer on 2nd page has 4 buttons.

- **Expenses** - To go back to the 1st page
- **Add Detail** - 
- **Expense Info** -  Information about the expense. Shows 
   - Status
   - Total Amount
   - Prepared Date
   - Eployee Id
   - Mrg Email, Period
   - User Name. 
  
Also, user can submit new expense, approve submitted expense, and post approved expense!!!!  
  
Footer has 2 buttons - **Update** and **Cancel** 
- **Expense Report** - Expense's Report, can be printed




