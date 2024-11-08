# Python To-Do List CLI App 🐍

This simple command-line interface (CLI) to-do list application was created in Python. This app allows users to add items, mark them as done, view the list, and exit the program.


## Features

- Add a to-do item: Add a new task to the list.
- Mark an item as done: Remove completed tasks from the list.
- View all items: Display all current tasks in the list.
- Exit the application: End session.


## Installation

1. Clone this repository to your local machine:
   ```bash
   git clone https://github.com/pixelphvntom/python-todo-list.git
   cd python-todo-list

## How to Use the Python To-Do List CLI App

### 1. Start the App
   
Run the app by typing python to_do_list_app.py in the terminal.

### 2. Add an item.
   
Type 1 and press enter to add a new item. You’ll be prompted to enter the item's name. Once entered, the item is saved to your list.

   <img width="565" alt="Screenshot 2024-11-07 at 6 23 25 PM" src="https://github.com/user-attachments/assets/4a4017cf-8690-4e19-94b6-34f72978930b">

   <img width="564" alt="Screenshot 2024-11-07 at 6 24 11 PM" src="https://github.com/user-attachments/assets/5edfa3c0-d95c-4128-8871-fb9a185365ae">

   <img width="565" alt="Screenshot 2024-11-07 at 6 25 21 PM 1" src="https://github.com/user-attachments/assets/109c8dd4-2771-4bff-bbd8-782e8158deb0">

   <img width="565" alt="Screenshot 2024-11-07 at 6 26 20 PM" src="https://github.com/user-attachments/assets/93d77386-830f-4d6e-a857-110569fc279b">

   <img width="564" alt="Screenshot 2024-11-07 at 6 27 05 PM" src="https://github.com/user-attachments/assets/75390f36-263a-4a92-9906-c9b5bd1c360c">

   <img width="565" alt="Screenshot 2024-11-07 at 6 27 14 PM" src="https://github.com/user-attachments/assets/c7623e1a-84c1-4175-b410-8c06d239720c">
   
### 3. View items

Type 3 and press enter to view all items in the    list. The app will display the items with their respective position for easy reference.

<img width="563" alt="Screenshot 2024-11-07 at 6 29 04 PM" src="https://github.com/user-attachments/assets/c1fc58e0-5d4b-40d3-b345-2b6967060b96">

<img width="564" alt="Screenshot 2024-11-07 at 6 28 56 PM" src="https://github.com/user-attachments/assets/e5d8b94c-f446-4de9-91c5-46adc2242d60">

### 4. Mark a item as Complete

Type 2 and press enter to mark a item as completed and have it removed from list.

<img width="563" alt="Screenshot 2024-11-07 at 6 29 04 PM" src="https://github.com/user-attachments/assets/c1fc58e0-5d4b-40d3-b345-2b6967060b96">

<img width="564" alt="Screenshot 2024-11-07 at 6 29 31 PM" src="https://github.com/user-attachments/assets/41574e16-e8ea-4468-aee9-2974a89b14d8">

### 5. Recheck your List
   
Type 3 again and press eneter. This allows you to confirm that completed tasks have been marked and removed as intended.

<img width="563" alt="Screenshot 2024-11-07 at 6 29 04 PM" src="https://github.com/user-attachments/assets/c1fc58e0-5d4b-40d3-b345-2b6967060b96">

<img width="565" alt="Screenshot 2024-11-07 at 6 29 49 PM" src="https://github.com/user-attachments/assets/fe8a241c-20e5-4772-8f29-a61d799bc93a">

### 7. Exit the App

Type 4 and press enter. You’ll see a "All done, goodbye!" message and then exited out the app. 

<img width="563" alt="Screenshot 2024-11-07 at 6 29 04 PM" src="https://github.com/user-attachments/assets/c1fc58e0-5d4b-40d3-b345-2b6967060b96">

<img width="563" alt="Screenshot 2024-11-07 at 6 34 20 PM 1" src="https://github.com/user-attachments/assets/43ff823b-b638-4901-963f-43a74acab061">


## Additional Feature 

### 1. Attempt to mark a removed item as complete

If you type 2 and try to mark an item as complete that's already been removed, the app will respond with the message "Couldn't find item (...)," indicating that the item is no longer available in the list.

<img width="563" alt="Screenshot 2024-11-07 at 6 29 04 PM" src="https://github.com/user-attachments/assets/c1fc58e0-5d4b-40d3-b345-2b6967060b96">

<img width="567" alt="Screenshot 2024-11-07 at 6 33 01 PM" src="https://github.com/user-attachments/assets/eba7ac2e-9a71-488a-a0b8-35f01d5cd118">


### 2. Attempt to add a duplicate item

If you type 3 and try to add an item that's already on the list, the app will respond with the message "Couldn't add item (...) it is already on the list." indicating that the item you're trying to add is a duplicate. (WILL BE ADDED IN THE UPDATE!!!)

### 3. Reopen the app and you list will still presist 

If you type 3 to view the list. Your saved list should reappear exactly as it was before you exited, confirming that your data is successfully saved between sessions. (WILL BE ADDED IN THE UPDATE!!!)


## License

MIT. This project is open-source.
