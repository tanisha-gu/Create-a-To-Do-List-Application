# Create-a-To-Do-List-Application


#### To-Do List Application
A command-line application for managing tasks with add, view, and remove functionality.

#### Features
- Add new tasks
- View all tasks with numbered list
- Remove tasks by index
- Persistent task storage using JSON
- Input validation and error handling
- Simple menu-driven interface

#### Requirements
- Python 3.x
- No external dependencies

#### Installation
1. Save the code to `todo_app.py`
2. Run in terminal:
```bash
python todo_app.py
```

#### Usage
1. **Main Menu**:
```
To-Do List Application
1. Add Task
2. View Tasks
3. Remove Task
4. Exit
Enter your choice: 
```

2. **Adding Tasks**:
```
Enter your choice: 1
Enter task description: Buy groceries
Task added successfully!
```

3. **Viewing Tasks**:
```
Enter your choice: 2
Your Tasks:
1. Buy groceries
2. Walk the dog
```

4. **Removing Tasks**:
```
Enter your choice: 3
Current Tasks:
1. Buy groceries
2. Walk the dog
Enter task number to remove: 1
Task removed successfully!
```
#### Key Features Explained
1. **Persistent Storage**:
   - Tasks are saved to `tasks.json` automatically
   - Tasks load automatically when application starts

2. **Error Handling**:
   - Empty task input prevention
   - Invalid task number handling
   - Non-numeric input detection
   - File operation safety

3. **User Experience**:
   - Clear menu navigation
   - Numbered task display
   - Confirmation messages
   - Intuitive task removal process

#### Example Workflow
```bash
$ python todo_app.py

To-Do List Application
1. Add Task
2. View Tasks
3. Remove Task
4. Exit
Enter your choice: 1
Enter task description: Finish project
Task added successfully!

To-Do List Application
1. Add Task
2. View Tasks
3. Remove Task
4. Exit
Enter your choice: 2

Your Tasks:
1. Finish project

To-Do List Application
1. Add Task
2. View Tasks
3. Remove Task
4. Exit
Enter your choice: 4
Exiting application. Goodbye!
```
_________________----------------------------------------------------------------------------------------------------------------------_____________________________________
#### Future Enhancements
- Task editing functionality
- Task prioritization
- Due dates and reminders
- Task categories/tags
- Search/filter functionality
- Web-based interface
- User authentication
- Cloud synchronization
