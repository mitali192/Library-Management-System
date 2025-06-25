# Library-Management-System
 A Python desktop application to manage books in a library. Users can add books, issue and return them, calculate late fees, and track inventory. Data is stored using SQLite and the interface is built with Tkinter.
Key Features:
- Add books with title and author.
- View list of all available and issued books.
- Issue books to users with automatic status update.
- Return books and calculate late fees after 14-day grace period.
- Search books by title.
- Delete unissued books from the inventory.

Technologies Used:
- Python 3.12
- Tkinter (GUI Framework)
- SQLite (Embedded Database)

File Structure:
- main.py        → Launches the GUI application.
- ui.py          → Contains all GUI components and user interaction logic.
- database.py    → Handles all database-related operations such as insert, update, delete.
- utils.py       → Contains late fee calculation logic.
- library.db     → Auto-created database storing books and issue records.

How to Run:
1. Install Python 3.12.
2. Open the project in PyCharm or any IDE.
3. Run `main.py` to start the app.
4. Use the GUI to add books and manage inventory.

Future Enhancements:
- Add authentication system for staff and students.
- Enable barcode scanning for quick check-in/out.
- Generate reports and export data to Excel/PDF.
- Add category/tags for books and advanced filtering.
