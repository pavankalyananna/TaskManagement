
# TaskManagement

A Java‑based Task Management application that helps users create, update, track, and complete tasks efficiently.

## 🚀 Overview

This project provides a basic task management system built with **Java** a backend framework like **Spring Boot**. Users can manage tasks through CRUD operations — create, read, update, and delete — and track the status of each task.

## 📦 Features

- ✅ Create new tasks  
- 📋 View all tasks  
- ✏️ Update existing tasks  
- 🗑️ Delete tasks  
- ⏱️ Mark tasks as completed/in-complete
- ⚙️ Configurable backend

(*Add more specific features once you know what your implementation includes.*)

## 🛠️ Technology Stack

| Component | Technology |
|-----------|------------|
| Language  | Java |
| Build Tool | Maven |
| Framework | Spring Boot |
| Persistence | H2 |

## 📁 Project Structure

```

TaskManagement/
├─ src/
│  ├─ main/
│  │  ├─ java/…
│  │  └─ resources/…
├─ pom.xml
├─ .gitignore

````

## 🚀 Getting Started

### Installation

1. **Clone the repository**
   ```bash
   git clone https://github.com/pavankalyananna/TaskManagement.git
   cd TaskManagement
````

2. **Build the project**

   ```bash
   mvn clean install
   ```

3. **Run the application**

   ```bash
   mvn spring-boot:run
   ```

 

## 📌 API Endpoints 

| Method | Endpoint                       | Description      |
| ------ | ------------------------------ | ---------------- |
| GET    | `/api/tasks`                   | Get all tasks    |
| GET    | `/api/tasks/{id}`              | Get task by ID   |
| POST   | `/api/tasks`                   | Create a task    |
| PUT    | `/api/tasks/{id}`              | Update a task    |
| DELETE | `/api/tasks/{id}`              | Delete a task    |
| PATCH  | `/api/tasks/{id}/complete`     | Mark Complete    |
| PATCH  | `/api/tasks/{id}/in-complete`  | Mark In-Complete |

