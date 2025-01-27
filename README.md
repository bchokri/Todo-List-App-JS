# Todo List App ✓
[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://opensource.org/licenses/MIT)
[![HTML](https://img.shields.io/badge/HTML5-E34F26?style=flat&logo=html5&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/HTML)
[![CSS](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)](https://developer.mozilla.org/en-US/docs/Web/CSS)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

> A modern, minimalist todo list application with a beautiful dark theme and smooth animations.

## 🚀 Demo

Check out the live demo: [Todo List App Demo](https://yourusername.github.io/todo-list-app)

## ✨ Features

- 🎨 Sleek dark theme interface
- ✏️ Easy task management
- 🔄 Real-time updates
- 💾 Local storage persistence
- 📱 Fully responsive design
- ⚡ No dependencies required

## 📋 Prerequisites

- Any modern web browser (Chrome, Firefox, Safari, or Edge)

## 🛠️ Installation

1. Clone the repository
   ```sh
   git clone git@github.com:bchokri/Todo-List-App-JS.git
   ```

2. Navigate to project directory
   ```sh
   cd Todo-List-App-JS.git
   ```

3. Open `index.html` in your browser

## 💻 Usage

1. Enter your task in the input field
2. Press 'ADD' button or hit Enter
3. Click the checkbox to mark tasks as complete
4. Click the trash icon to delete tasks

## 🎯 Code Structure

```
todo-list-app/
├── index.html          # Main HTML file
├── style.css          # Styles and animations
└── app.js            # Core functionality
```

## 🎨 Color Reference

| Color             | Hex                                    |
| ----------------- | -------------------------------------- |
| Background        | #101114                                |
| Primary          | #1C1D20                                |
| Secondary        | #4A4D57                                |
| Accent           | #00FFC4                                |
| Text             | #F9F9F9                                |

## ⚙️ Core Functions

### Task Management
```javascript
// Add new todo
function addTodo() {
    const todoText = todoInput.value.trim();
    if(todoText.length > 0) {
        const todoObject = {
            text: todoText,
            complited: false
        }
        allTodos.push(todoObject);
        updateTodoList();
        saveTodos();
        todoInput.value = "";
    }
}
```

### Local Storage
```javascript
// Save todos to localStorage
function saveTodos() {
    const todosJson = JSON.stringify(allTodos);
    localStorage.setItem("todos", todosJson);
}
```

## 🤝 Contributing

1. Fork the Project
2. Create your Feature Branch (`git checkout -b feature/AmazingFeature`)
3. Commit your Changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the Branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📝 License

Distributed under the MIT License. See `LICENSE` for more information.

## 📧 Contact

Your Name - [@yourusername](https://twitter.com/yourusername)

Project Link: [https://github.com/yourusername/todo-list-app](https://github.com/yourusername/todo-list-app)

## 🙏 Acknowledgments

- [Google Fonts](https://fonts.google.com/)
- [Material Icons](https://material.io/icons/)
- [GitHub Pages](https://pages.github.com)

## 🚀 Upcoming Features

- [ ] Task categories
- [ ] Due dates
- [ ] Priority levels
- [ ] Search functionality
- [ ] Dark/Light theme toggle
- [ ] Task editing
- [ ] Multiple lists
