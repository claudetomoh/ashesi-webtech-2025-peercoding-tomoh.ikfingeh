# SmartRegister - Faculty Intern Dashboard

A modern, responsive web dashboard for managing course attendance and allowing faculty interns to oversee their assigned courses. This dashboard provides an intuitive interface for both managing attendance and joining courses as observers.

## 🎯 Project Overview

SmartRegister is designed specifically for faculty interns who need to:
- View their assigned courses at a glance
- Manage attendance for multiple sessions
- Allow staff and students to join as observers/auditors
- Access course information in a user-friendly format

## 🚀 Features

- **Dynamic Course Display**: Courses are loaded dynamically using JavaScript
- **Dual Action Buttons**: Each course card includes both "Manage Attendance" and "Join as Observer" functionality
- **Responsive Design**: Optimized for desktop and mobile devices
- **Modern UI**: Clean, professional interface with gradient navigation and hover effects
- **Accessibility**: Includes ARIA labels for better screen reader support

## 🛠️ Technologies Used

- **HTML5**: Semantic markup structure
- **CSS3**: 
  - Flexbox and Grid layouts
  - CSS gradients and transitions
  - Responsive design with media queries
  - Modern card-based UI components
- **JavaScript (ES6+)**:
  - Dynamic DOM manipulation
  - Template literals
  - Arrow functions
  - Array methods (forEach)

## 📁 Project Structure

```
activity_02/
├── dashboard.html      # Main HTML structure
├── style.css          # Styling and responsive design
├── script.js          # JavaScript functionality
└── README.md          # Project documentation
```

## 🎨 Design Features

### Navigation Bar
- Gradient background (red to pink theme)
- Responsive navigation that stacks vertically on mobile
- Hover effects for better user interaction

### Course Cards
- Grid-based layout that adapts to screen size
- Hover animations with subtle lift effect
- Clean typography using Poppins font family
- Dual-button interface for different user roles

### Responsive Design
- Mobile-first approach
- Breakpoint at 600px for mobile optimization
- Flexible navigation and content layout

## 💻 Sample Data

The dashboard currently displays four sample courses:

1. **Introduction to Web Tech** - Dr. Osafo-Maafo (2 sessions)
2. **Database Systems** - Prof. Stephane Nwolley (1 session)
3. **WOC** - Ms. Theodora Aryee (8 sessions)
4. **Systems Analysis and Design** - Dr. Dennis Owusu (4 sessions)

## 🚀 Getting Started

1. **Clone the repository**:
   ```bash
   git clone [repository-url]
   cd activity_02
   ```

2. **Open the project**:
   - Simply open `dashboard.html` in your web browser
   - No additional setup or dependencies required

3. **For development**:
   - Use a local server (like Live Server in VS Code) for the best experience
   - Modify the `courses` array in `script.js` to add/edit course data

## 🔧 Customization

### Adding New Courses
Edit the `courses` array in `script.js`:
```javascript
const courses = [
  { title: "Your Course Title", instructor: "Instructor Name", sessions: 5 },
  // Add more courses here
];
```

### Styling Modifications
- Main colors can be changed in the CSS custom properties
- Grid layout can be adjusted in the `.course-grid` class
- Responsive breakpoints can be modified in the media queries

## 🎯 Future Enhancements

- **Database Integration**: Connect to a real backend API
- **User Authentication**: Add login/logout functionality
- **Session Management**: Detailed attendance tracking
- **Reporting**: Generate attendance reports
- **Real-time Updates**: Live course data synchronization

## 📱 Browser Compatibility

- Chrome (recommended)
- Firefox
- Safari
- Edge
- Mobile browsers (iOS Safari, Chrome Mobile)

## 👥 User Roles

### Faculty Interns
- Primary users who manage course attendance
- Can view all assigned courses
- Access to attendance management tools

### Observers/Auditors
- Staff and students who want to audit courses
- Can join courses without management privileges
- Read-only access to course content

## 📄 License

This project is part of an educational assignment and is available for learning purposes.

---

**Built with ❤️ for faculty interns**

*Note: This dashboard represents a learning project demonstrating modern web development practices including responsive design, dynamic content generation, and user-centered interface design.*