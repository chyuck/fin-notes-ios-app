# Personal Financial Notes
iOS app for managing personal financial notes.


### Note attributes:
- Name: Text (required)
- Description: Text (optional)
- Currency: Text (optional)
- Due Date: Date (optional)
- Amount: Number (optional)
- Amount Changes: collection of objects (optional)
  - Amount Change: Number (required)
  - Description: Text (optional)
- Archived: Boolean (required) (default false)
- Flagged: Boolean (required) (default false)
- Created: Date (required)
- Modified: Date (required)


### Features:
- "Amount" can be recalculated using "Amount Changes"
- "Amount" and "Amount Change" can be positive or negative
- Archived notes have light grey color and displayed at the end of the table
- "Created" and "Modified" are calculated automaicaly and cannot be changed by user
- Flagged notes have bold text color and  displayed at the beginning of the table, right after notes with close due date
- Notes with close due date (1 week) have read text and displayed at very beginning of table 
- Notes ordered in descending order by "Due Date" and then by "Modified" date by default
- Notes can be deleted
