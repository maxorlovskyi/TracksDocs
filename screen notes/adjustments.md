## Adjustments types

1. Waste Log
1. Inv Transfer (IRT)

## Adjustments statuses

1. New
1. Recieved
1. Rejected
1. Posted

### New
This is an initial status of created adjusment

### Recieved
Adjustment status can be changed to **Received** when:
1. Current status is **New**
1. User has permission **Can Receive** (or User is an Admin)
1. Selected store equals receive store (***only for Inv Transfer***)

### Rejected

Adjustment status can be changed to **Rejected** when:
1. Current Adjustment status is **New**
1. User has permission **Can Reject** ***or*** selected store equals store Id or recieve store Id of Adjustment

### Posted

Adjustment can be change to **Posted** when:
1. Current status is **Recieved**
1. User has permission **Can Post**

## Tracks Adjustment Features

### Change Adjustment Status

User can change status from:
1. From Main Adjustment Grid  ***context menu***
1. From Edit Adjustment modal window via footer buttons
1. By selecting target status at main grid footer, then selecting adjustments via grid (column with checkbox) and then clicking on **Recieve Selected**, **Rejected Selected**,  **Post Selected** at main grid footer. 

Bulk change status to **Recieved**, **Rejected**, **Posted**  available when:
1. user if he has permission **Can Post**
2. Adjustment has all requirements described above for specific status.

### Create Adjustment

User can create new adjusment by clicking on **New Inv Transfer** or **New Waste Log**. 

Feature available when:
1. Current selected org unit is type of **Store**
2. User has permission **Can Create** (or User is ad Admin)