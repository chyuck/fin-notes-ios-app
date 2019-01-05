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
- AutoCalculateAmount: Boolean (required) (default false)
- Archived: Boolean (required) (default false)
- Flagged: Boolean (required) (default false)
- Created: Date (required)
- Modified: Date (required)


### Features:
- "Amount" can be recalculated using "Amount Changes"
- "Amount" and "Amount Change" can be positive or negative
- Archived notes have light grey color and displayed at the end of the table
- "Created" and "Modified" are calculated automatically and cannot be changed by user
- Flagged notes have bold text color and displayed at the beginning of the table, right after notes with close due date
- Notes with close due date (1 week) have red text and displayed at very beginning of table
- Notes ordered in descending order by "Due Date" and then by "Modified" date by default
- Notes can be deleted


### Screens:
- **Notes Screen** (Start screen). A table of notes with add/edit/delete capabilities.
- **Note View/Edit Screen**. Screen is displayed when item is tapped in table of notes. All attributes must be displayed on screen along with a table of amount changes with add/edit/delete capabilities.
- **Note Amount Change Edit/View Popup Screen**. This popup screen is displayed when item is tapped in table of amount changes.


### Roadmap:
1. Implement Core Data Model
2. Implement Repository for Data Model
3. Implement **Notes Screen**
4. Implement **Note View/Edit Screen**
5. Implement **Note Amount Change Edit/View Popup Screen**
