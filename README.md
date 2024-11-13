
# 📝 Task Manager React App

An easy-to-use Task Manager application built with React to help users manage tasks efficiently. This application features intuitive UI, customizable task management, and persistent data storage for seamless task tracking.



## 📋 Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Getting Started](#getting-started)
- [Installation](#installation)
- [Usage](#usage)
- [Project Structure](#project-structure)
- [Technologies Used](#technologies-used)
- [Roadmap & Future Enhancements](#roadmap--future-enhancements)
- [Contributing](#contributing)
- [License](#license)

## Overview
This Task Manager App empowers users to organize their tasks with customizable options for setting priorities, due dates, and more. With  automatic overdue tracking, and task persistence via local storage, it provides an optimal solution for personal task management.

## ✨ Features
- **🌟 Task Creation**: Add new tasks with a title, description, priority level, and due date.
- **🖊️ Task Editing**: Modify existing tasks’ details in-place.
- **🗑️ Task Deletion**: Easily remove tasks with a single click.
- **🔍 Task Filtering & Search**: Quickly filter tasks by priority or search by title.
- **📌 Task Categories**: Organize tasks into Upcoming, Completed, and Overdue categories for better task visibility.
- **💾 Persistent Storage**: Save tasks in local storage to retain data across browser sessions.
- **🌐 Responsive Design**: Optimized for all devices, ensuring usability on desktops, tablets, and mobile devices.

## 🚀 Getting Started
Follow these instructions to set up and run the app locally.

### Prerequisites
Ensure you have the following installed:
- **Node.js** (v12 or higher) - [Download](https://nodejs.org/)
- **npm** or **yarn** - [Download npm](https://www.npmjs.com/)

## 🔧 Installation

1. **Clone the repository**:
   ```bash
   
   git clone https://github.com/your-username/Task_manager.git
   cd Task_manager
   ```

2. **Install dependencies**:
   ```bash
   npm install
   # or
   yarn install
   ```

3. **Run the development server**:
   ```bash
   npm start
   # or
   yarn start
   ```

4. **Open the app**: Navigate to [http://localhost:3000](http://localhost:3000) in your web browser.

## 💻 Usage

1. **Add a New Task**: Use the form to add a task with specific details such as title, description, due date, and priority.
2. **Edit Tasks**: Update any task by clicking the edit button and making the desired changes.
3. **Delete Tasks**: Remove tasks easily by pressing the delete button.
4. **Filter & Search Tasks**: Use the priority filter or search bar to find tasks quickly.
5. **View Categorized Tasks**:
   - **Upcoming**: All tasks scheduled for the future.
   - **Completed**: Tasks marked as done.
   - **Overdue**: Tasks that have exceeded their due date.

## 📁 Project Structure

```
src/
├── components/               # Contains all reusable UI components
│   ├── TaskItem.js           # Single task item component
│   ├── TaskList.js           # Task list component displaying all tasks
│   └── AddTaskForm.js        # Form component for adding new tasks
├── hooks/
│   └── useLocalStorage.js    # Custom hook for local storage management
├── utils/
│   └── dateHelpers.js        # Helper functions for handling date logic
├── App.js                    # Main app component
├── index.js                  # Entry point for rendering the app
└── styles/                   # CSS files for styling
```

## 🛠️ Technologies Used
- **React** - for building the user interface
- **React-DND** - to implement drag-and-drop functionality
- **React-Hot-Toast** - to display notifications
- **Local Storage** - to persist task data across page reloads

## 🚧 Roadmap & Future Enhancements
- **Authentication**: Allow users to log in and save tasks to a personal account.
- **Task Reminders**: Send notifications for tasks nearing their due dates.
- **Categories & Tags**: Enable users to categorize and label tasks.
- **Dark Mode**: Add a dark mode option for better user experience at night.

