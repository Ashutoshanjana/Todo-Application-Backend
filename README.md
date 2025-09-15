## 📌Todo Application Backend
A sacalable backend application built with **Node.js**, **Express.js** and **MongoDB(Mongoose)** to manage todos.
This project provides REST APIs to perform CRUD operations on todos with validations, filtering, and date formating.

---

## 🚀Features 
- Connects to MongoDB using **Mongoose**
- CRUD operation on todos
- Query-based filtering (status, priority, category, search text, due date)
- Validations for status, priority, category, and due date
- Proper error handling with descriptive messages
- Authentication routes (Bonus)
- Scalable project structure

---

## 🗄️Database Schema (Todo Collection)

| Column       | Type        | Description                              |
|--------------|-------------|------------------------------------------|
| `id`         |  Number     | Unique identifier for the todo           |
| `todo`       |  String     | The actual task description              | 
| `category`   |  String     | Category (`WORK`, `HOME`, `LEARNING`)    |
| `priority`   |  String     | Priority (`HIGH`, `MEDIUM`, `LOW`)       |
| `status`     |  String     | Status (`TO DO`, `IN PROGRESS`, `DONE`)  |
| `dueDate`    |  Date       | Due date (formatted as `yyyy-MM-dd`)     |

---

## 🧑‍💻Author
**Ashutosh Anjana**

*Passionate about web development & fintech solutions.*
