Modern Todo List Application
A sleek and modern todo list application built with vanilla JavaScript. Features a minimalist design with a dark theme and smooth animations.
Features

Clean, modern dark theme interface
Add new tasks with a user-friendly input field
Custom-designed checkboxes with smooth animations
Delete tasks with a hover effect
Data persistence using localStorage
Fully responsive design (mobile and desktop compatible)
Maximum character limit of 50 for todo items
Custom SVG icons for checkmarks and delete buttons
Smooth transitions and hover effects

Technologies Used

HTML5
CSS3 (Custom Properties, Flexbox, Media Queries)
JavaScript (ES6+)
Local Storage API for data persistence

Project Structure
Copytodo-app/
│
├── index.html      # Main HTML structure
├── style.css       # Styling with custom properties
└── app.js         # JavaScript functionality
Implementation Details
CSS Features

Custom CSS properties (variables) for easy theme customization
Mobile-first responsive design
Flexbox layout system
Custom checkbox design with SVG icons
Smooth transitions and hover effects
Adaptive font sizing for different screen sizes

JavaScript Functionality

Form submission handling with preventDefault()
Local storage integration for data persistence
Dynamic DOM manipulation
Event delegation for todo items
Todo object structure with text and completion status
Filter implementation for todo deletion

Getting Started

Clone the repository

bashCopygit clone https://github.com/yourusername/todo-app.git

Open index.html in your web browser

No additional setup or dependencies required!
Usage

Type your todo item in the input field (max 50 characters)
Click "ADD" button or press Enter to add the item
Click the checkbox to mark a todo as complete
Click the trash icon to delete a todo
Your todos will be automatically saved and persist between sessions

Color Scheme
The application uses a custom dark theme with the following colors:
cssCopy--background: #101114
--primary-color: #1C1D20
--secondary-color: #4A4D57
--accent-color: #00FFC4
--text-color: #F9F9F9
Responsive Design

Desktop: Full width up to 700px
Mobile: Adaptive layout with:

Adjusted font sizes
Repositioned ADD button
Optimized spacing
Flexible input handling



Browser Support
Compatible with modern browsers that support:

CSS Custom Properties
Flexbox
LocalStorage API
ES6+ JavaScript features

License
This project is licensed under the MIT License - see the LICENSE file for details.
Contributing

Fork the project
Create your feature branch (git checkout -b feature/AmazingFeature)
Commit your changes (git commit -m 'Add some AmazingFeature')
Push to the branch (git push origin feature/AmazingFeature)
Open a Pull Request

Future Enhancements

Task categories/labels
Due dates
Priority levels
Search functionality
Dark/Light theme toggle
Task editing
Multiple todo lists