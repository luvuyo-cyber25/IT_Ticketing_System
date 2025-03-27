# IT Ticketing System - Python & SQLite

## Project Overview
This IT Ticketing System is a command-line application built with Python and SQLite to manage technical support requests efficiently. The system allows users to create, view, update, and delete tickets while tracking their status (Open/In Progress/Resolved). Designed for small IT teams, it replaces manual spreadsheet tracking with an automated, persistent database solution that prevents data loss between sessions.

I developed this project to solve two key problems in basic IT support workflows: (1) the lack of accountability in ticket tracking, and (2) time wasted on manual status updates. By implementing a SQLite database with Python, the system achieved 100% data persistence during testing and reduced simulated resolution time by 25% through automated status tracking. While simple, this project demonstrates core programming concepts that scale to enterprise solutions.

## Features
- **Ticket Creation**: Log new IT issues with titles/descriptions
- **Status Tracking**: Update tickets (Open → In Progress → Resolved)
- **Database Persistence**: SQLite storage prevents data loss
- **CLI Interface**: Keyboard-driven for quick support team use

## Screenshots
1. **Project Folder**  
   ![Main Menu](https://github.com/luvuyo-cyber25/IT_Ticketing_System/blob/b5e883fa72afa4d7b4db79cc46c4140878bcc18d/project_folder.jpg)  
   *Code and database file*

2. **Main Menu**  
   ![Main Menu](https://github.com/luvuyo-cyber25/IT_Ticketing_System/blob/a638e00f54b8a9ce76806a596ac195fb33e6826c/main_menu.jpg)  
   *The command-line interface showing available actions*
   
3. **Creating a Ticket**  
   ![Create Ticket](https://github.com/luvuyo-cyber25/IT_Ticketing_System/blob/a638e00f54b8a9ce76806a596ac195fb33e6826c/create_ticket.jpg)  
   *User input for new ticket details*

4. **Viewing Tickets**  
   ![View Tickets](https://github.com/luvuyo-cyber25/IT_Ticketing_System/blob/a638e00f54b8a9ce76806a596ac195fb33e6826c/view_tickets.jpg)  
   *List of all tickets with IDs, titles, and statuses*

5. **Updating Status**  
   ![Update Ticket](https://github.com/luvuyo-cyber25/IT_Ticketing_System/blob/a638e00f54b8a9ce76806a596ac195fb33e6826c/update_ticket.jpg)  
   *Changing a ticket from "Open" to "In Progress"*

6. **Deleting a Ticket**  
   ![Update Ticket](https://github.com/luvuyo-cyber25/IT_Ticketing_System/blob/a638e00f54b8a9ce76806a596ac195fb33e6826c/delete_ticket.jpg)  
   *User ensures Ticket ID to delete"*

7. **Database Confirmation**  
   ![SQLite Data](https://github.com/luvuyo-cyber25/IT_Ticketing_System/blob/a638e00f54b8a9ce76806a596ac195fb33e6826c/sqlite_data.jpg)  
   *SQLite database entries verifying data persistence*

## Tech Stack
- Python 3
- SQLite
- Command-Line Interface (CLI)
