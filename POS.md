# POS Items

## Configuration Types 

There are two Configuration Types

- POS Item Type (lkpPOSItemType)
- POS Item Link Type (lkpPOSItemLinkType)

### POS Item Type (lkpPOSItemType)

POS Item Type (lkpPOSItemType) consist 

- POSItemType - Primary Key
- POSItemTypeName - Display Name (optional)
- IsPromptRequired  
> If true  - Prompt propertie will be required (located in Properties Tab)
- ShowComboOptions 
> If true  - user will be able to control combo options, such as - combo meal object number (datPOSItemComboObjNum)

POS Item Link Type (lkpPOSItemLinkType) consist 

- POSItemLinkType - Primary Key
- POSItemLinkTypeGroup - Ingredients Group used for generation grouping ingredients by type. Using inside Ingredient Tab.
- POSItemLinkTypeName - Display Name (optional) 
> Selected in Ingredient Grid - column `Type` or `Ingredient` - Tab Properties -   `drop down` link Type
- POSItemLinkDescription - using for describing the behavior for Ingredient Link Type
> Will shows when hover over the Grid - column `Type`, shows as `tooltip`
- ShowFeaturedItemOptions 
> If true - allow the user to configure additional ingredient link properties, such as - is featured item

> If `is featured item` true - allow the user to select Featured Modifier Selection 
- ShowMinMaxOptions
> If true - allow the user to select - `Min Items`,`Max Items`, `Min Items Only`, `Max Items Only`, `Min Items Total Qty`, `Max Items Total Qty`
- CanBeDefault - allow to choose default ingredient (location in Ingredients Tab - Ingredients Grid)
- ShowComboOptions - **`not used`**
- IsPromptRequired - Ingredient Tab - Properties
- ShowUseImage 
> If true - the user can change used images configuration via a checkbox at Ingredients Properties
- ShowUsePrice
> If true - the user can change used price configuration via a checkbox at Ingredients Properties
- ShowPriceLevels 
> If true - allow the user to control price levels for ingredient
- Icon - controls rendering icon inside Grid - column Name, before item name (optional). User can see link to website with icons https://fontawesome.com/v4.7.0/icons/
