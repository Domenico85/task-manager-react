# 📋 Task Manager - Productivity App

A modern, responsive task management application built with React and Tailwind CSS. Stay organized and boost your productivity with intuitive task creation, prioritization, and deadline tracking.

## ✨ Features

### 🎯 Core Functionality

- **Create & Edit Tasks** - Add detailed tasks with titles, descriptions, priorities, and deadlines
- **Smart Prioritization** - Organize tasks with High, Medium, and Low priority levels
- **Deadline Management** - Set and track task deadlines with overdue detection
- **Task Completion** - Mark tasks as complete with visual feedback

### 🔍 Advanced Features

- **Real-time Search** - Find tasks instantly by title or description
- **Multi-filter System** - Filter by priority level and completion status
- **Dashboard Analytics** - Track your productivity with task statistics
- **Overdue Detection** - Visual alerts for tasks past their deadline

### 🎨 User Experience

- **Responsive Design** - Works seamlessly on desktop, tablet, and mobile
- **Modern UI** - Clean, intuitive interface with smooth animations
- **Visual Indicators** - Color-coded priorities and status indicators
- **Accessibility** - Built with semantic HTML and keyboard navigation

## 🚀 Quick Start

### Prerequisites

- Node.js (v14 or higher)
- npm or yarn package manager

### Installation

1. **Clone the repository**

   ```bash
   git clone https://github.com/yourusername/task-manager.git
   cd task-manager
   ```

2. **Install dependencies**

   ```bash
   npm install
   # or
   yarn install
   ```

3. **Start the development server**

   ```bash
   npm start
   # or
   yarn start
   ```

4. **Open your browser**
   Navigate to `http://localhost:3000` to see the app in action!

## 🛠️ Built With

- **[React](https://reactjs.org/)** - Frontend library for building user interfaces
- **[Tailwind CSS](https://tailwindcss.com/)** - Utility-first CSS framework for styling
- **[Lucide React](https://lucide.dev/)** - Beautiful & consistent icon library
- **[Vite](https://vitejs.dev/)** - Fast build tool and development server

## 🎯 Usage Guide

### Creating Tasks

1. Click the "Add Task" button
2. Fill in the task details:
   - **Title** (required) - Brief description of the task
   - **Description** (optional) - Additional details
   - **Priority** - High, Medium, or Low
   - **Deadline** (optional) - Due date for the task
3. Click "Add Task" to save

### Managing Tasks

- **Complete Task** - Click the checkbox to mark as done
- **Edit Task** - Click the edit icon to modify task details
- **Delete Task** - Click the trash icon to remove permanently

### Finding Tasks

- **Search** - Use the search bar to find tasks by title or description
- **Filter by Priority** - Select High, Medium, Low, or All priorities
- **Filter by Status** - View All, Pending, or Completed tasks

## 🔧 Project Structure

```
task-manager/
├── public/
│   ├── index.html
│   └── favicon.gif
├── src/
│   ├── components/
│   │   └── TaskManager.jsx
│   ├── App.js
│   ├── index.js
│   └── index.css
├── package.json
├── tailwind.config.js
├── vite.config.js
└── README.md
```

## 🚦 Available Scripts

In the project directory, you can run:

- `npm start` - Runs the app in development mode
- `npm test` - Launches the test runner
- `npm run build` - Builds the app for production
- `npm run eject` - Ejects from Create React App (irreversible)

## 🎨 Customization

### Styling

The app uses Tailwind CSS for styling. You can customize the appearance by:

- Modifying the `tailwind.config.js` file
- Updating color schemes in the component classes
- Adding custom CSS in `src/index.css`

### Features

To add new features:

1. Update the task object structure in the state
2. Add new form fields in the task creation form
3. Update the task display and filtering logic

## 🤝 Contributing

Contributions are welcome! Here's how you can help:

1. **Fork the repository**
2. **Create a feature branch** (`git checkout -b feature/AmazingFeature`)
3. **Commit your changes** (`git commit -m 'Add some AmazingFeature'`)
4. **Push to the branch** (`git push origin feature/AmazingFeature`)
5. **Open a Pull Request**

### Development Guidelines

- Follow React best practices and hooks patterns
- Use Tailwind CSS utility classes for styling
- Ensure responsive design across all screen sizes
- Add comments for complex logic
- Test your changes thoroughly

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🌟 Acknowledgments

- Icons provided by [Lucide](https://lucide.dev/)
- Design inspiration from modern productivity apps
- Built with love for the developer community

## 📞 Support

If you have any questions or run into issues:

- Create an [Issue](https://github.com/yourusername/task-manager/issues)
- Check existing issues for solutions
- Contact the maintainer

---

<div align="center">
  <p>Made with ❤️ by DomDev</p>
  <p>
    <a href="https://github.com/Domenico85">GitHub</a> •
  </p>
</div>
