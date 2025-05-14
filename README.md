# Note-maker-
A simple command-line interface (CLI) based Note Management System with user authentication, built using Python. Users can register, log in, manage their notes, and even upload files securely. Admins can view user statistics.
.










├── users.csv            # Stores usernames and passwords
├── user_notes/          # Stores user notes (auto-created)
└── note_app.py          # Main application code

👨‍💻 Usage Flow
Main Menu:

Login

Sign up

Admin: Show user details

Quit

User Dashboard Options:

Create a new note file

Write to an existing file

View all your notes

Upload an external file

Exit dashboard

🔐 Admin Access
Admins can log in and see:

Total registered users

Number of note files per user

Admin credentials must be registered as a normal user first.

📌 Notes
All user files are stored under user_notes/ with a prefix of the username.

Password input is hidden using the getpass module for security.

Files are timestamped when written to, using datetime.

📄 License
This project is open-source and free to use under the MIT License.
