# 🚀 Kanban Board – JavaScript + SCSS Task Manager

### 🔗 **Live Demo:**  
https://niraj-verma07.github.io/Kanban-Board/

A clean and interactive **Kanban Board** built using **JavaScript** and **SCSS**, allowing users to add, delete, and drag tasks across different workflow stages — **Todo**, **In Progress**, and **Completed**.  
The app also uses **LocalStorage** to save all tasks so nothing gets lost on page refresh.

---

## ✨ Features

- ➕ **Add Tasks:** Create tasks with a title and description  
- 🗑️ **Delete Tasks:** Remove tasks instantly  
- 🔄 **Drag & Drop:** Smoothly move tasks between columns  
- 🔢 **Dynamic Task Counter:** Each column shows the number of tasks  
- 💾 **LocalStorage Support:** Tasks stay even after refreshing the page  
- 🎨 **SCSS-Powered UI:** Clean layout with hover & drag feedback  

---

## 🛠️ Tech Stack

- **HTML**
- **SCSS**
- **JavaScript (Vanilla)**

---

## 📌 How It Works

### ✔ Adding a Task
Tasks are created using a modal input and automatically added to the **Todo** column.

### ✔ Drag & Drop Functionality
Each task is draggable, and columns listen for drag events to move the task into the correct section.

### ✔ Task Persistence
All tasks are saved in `localStorage`, including their:  
- Title  
- Description  
- Current column (todo / progress / done)

### ✔ Task Count
Each column displays how many tasks it currently contains, updating live on every action.

---

## 📂 Project Structure
Kanban-Board/ <br>
│ <br>
├── index.html       <br>
│ <br>
├── script.js        <br>
│ <br>
├── style.scss  
