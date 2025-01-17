# Simple Journal

A simple Bullet Journal. Try it out [here](https://soggybag.github.io/simple-journal/).

In a nut shell the Simple Journal consists of a series of bullet point lists. Items in a list are marked with a status. 

- `X` (completed)
- `>` (for tomorrow) 
- `<` (save for later)
- and a few others 

When making a new entry items from the list marked `>` (for later) are moved to the next entry list. 

Imagine an entry as a list of daily todos and reminders. And items being items in an entry list. 

The app uses React for View managment and Redux for state management. The app persists data using local storage. All of the data will be saved on the device where they were created and will reappear each time you open the app. 

## Todo

- Contributions
  - Add Contribution guidelines
  - Move todos to issues and tag
- List items can be arranged
  - Drag to arrange? 
  - Arrow to move up/down?
- Add editable title to each entry
  - Generate default Entry title with short date - `09/19/19`
- Ideas for possible features
  - Add timer to items to get time spent
  - Badge shows number of times an item has been passed along to a new entry
- Save for later 
  - Move `<` items to saved for later list
  - Add a reducer for saved for later
- Add New Journal
  - Group entires under journals
- Add styles 
  - Basic font styles 
    - Use the framework?
  - Layout
    - Move list of Entries to left column
    - Mockup layouts
  - Status Selector styles
    - Web Component?
    - CSS Drop Down?s
    - Existing React component?
- Add notifications 
  - Reminder to add events at the beginning of the day
  - Reminder at the end of the day
- ~~Should automatically navigate to the new entry after clicking new entry~~ 
  - Prevents confusion as users wonder if a new entry was created.
- ~~Post to Github Pages~~
- ~~Adding an entry should grab the Items with status `>`~~
- ~~New Entry button functional~~
- ~~Remove Add Entry section at top~~
- ~~Use Local Storage~~

## Contributions 

Coming soon...
