# Simple Command-Line Diary

Create a simple command-line diary application where users can add, view, and search for diary entries.

## Focus on

- Object Oriented Programming
- String manipulation
- Date formatting
- Signaling / Keyboard interrupts
- Terminal **COLORS** (optional but very nice)

### Language

This exercise is intended to be done using Python or JavaScript (Node.js), but you're free to use whatever you like.


## Requirements

1. **Add Entry:** Users should be able to add a new diary entry. Each entry should have a date (automatically generated) and a text content.
2. **View Entries:** Users should be able to view all diary entries.
3. **Search Entries:** Users should be able to search for a specific word or phrase in the diary entries.
4. **Exit:** Users should be able to exit the application. If they press `Ctrl-C`, the application should also exit gracefully with a message "Thank you for using the diary app!"

## Instructions

1. **Setup:**
   - If using Python, start a new Python script.
   - If using JavaScript, initialize a new Node.js project using `npm init`.

2. **Main Menu:**
   - Display a menu with options: `1. Add Entry`, `2. View Entries`, `3. Search Entries`, and `4. Exit`.

3. **Add Entry:**
   - Prompt the user for the diary entry content.
   - Store the entry with the current date.

4. **View Entries:**
   - Display all the diary entries with their respective dates (in `%d-%m-%Y %H:%M:%S` format).

5. **Search Entries:**
   - Prompt the user for a search term.
   - Display all entries that contain the search term.

6. **Exit:**
   - If the user selects the exit option or presses `Ctrl-C`, display a goodbye message and terminate the application.

**Tips:**

- Use an OOP approach.
- Use a list or an array to store the diary entries.
- For date generation in Python, you can use the `datetime` module. In JavaScript, you can use the `Date` object.
- To capture `Ctrl-C` in Python, you can use the `try` and `except` blocks for the `KeyboardInterrupt` exception. In Node.js, you can use the `process` object and listen for the `SIGINT` event.

**Bonus:**

- Add colors to your command-line interface. In Python, you can use the `termcolor` module. In Node.js, you can use the `chalk` library.
- Implement a way to edit or delete diary entries.

### Example Output

```
------------------ DIARY ENTRIES ------------------

05-09-2023 14:30:45
Today I Went To The Park And Enjoyed A Lovely Picnic With Friends. The Weather Was Perfect, And We Played Frisbee For Hours.

06-09-2023 09:15:32
Had An Amazing Breakfast At The New Cafe Downtown. Their Blueberry Pancakes Are To Die For!

06-09-2023 21:50:10
Finished Reading "The Great Gatsby" Tonight. What A Captivating Story! Makes Me Wonder About The Roaring Twenties.

07-09-2023 18:20:55
Attended A Workshop On Digital Art. Learned So Much About Different Techniques And Tools. Can't Wait To Start My Own Project.

---------------------------------------------------
```
