Python Homework Compiler

A web-based platform for teachers and students to manage Python programming assignments efficiently. Designed specifically for Atomic Energy Central School No. 3, Tarapur.
🎯 Overview
The Python Homework Compiler is a comprehensive web application that allows teachers to assign Python programming questions to students and enables students to write, test, and submit their code solutions online. The platform features separate dashboards for teachers and students with role-based access control.
✨ Features
👩‍🏫 Teacher Features

Secure Login System - Username/password authentication
Question Management - Add and remove questions for specific classes
Class-wise Organization - Assign questions to classes (9A, 9B, 10A, 10B, 11A, 11B, 12A, 12B)
Submission Review - View all student submissions organized by question
Code Compilation - Test and compile student code submissions
Real-time Feedback - Provide instant feedback on code quality

👨‍🎓 Student Features

Simple Registration - Enter name, class, and roll number
Question Viewing - Access questions assigned to their specific class
Built-in Code Editor - Write Python code with syntax highlighting
Code Testing - Run code before submission to check for errors
Code Submission - Submit solutions directly to teachers
Instant Feedback - Get immediate results when running code

🚀 Technology Stack

Frontend: HTML5, CSS3, JavaScript (ES6+)
Styling: Modern CSS with Glassmorphism design
Code Execution: JavaScript-based Python interpreter
Storage: In-memory data storage (browser session)
Deployment: Static hosting compatible (Netlify, GitHub Pages, etc.)

📁 Project Structure
python-homework-compiler/
├── index.html          # Main application file
├── README.md          # This documentation

🛠️ Installation & Setup
Method 1: Direct Deployment

Download the index.html file
Upload to any web hosting service (Netlify)
Access via the provided URL

Method 2: Local Development

Clone or download the repository
Open index.html in any modern web browser
No additional setup required!

📖 Usage Guide
For Teachers

Login

Username: teacher
Password: password


Adding Questions

Navigate to "Manage Questions" tab
Select target class
Enter question title and description
Click "Add Question"


Managing Submissions

Go to "Review Submissions" tab
View all student submissions
Click "Compile & Test" to run student code
Provide feedback based on results



For Students

Login

Enter your full name
Select your class from dropdown
Enter your roll number


Solving Problems

View questions assigned to your class
Write Python code in the editor
Click "Run Code" to test your solution
Click "Submit Code" to send to teacher



🔧 Configuration
Supported Classes

9A, 9B
10A, 10B
11A, 11B
12A, 12B

Default Credentials

Teacher Login: teacher / password
Student Login: No password required, just name/class/roll

🎨 Design Features

Responsive Design - Works on desktop, tablet, and mobile
Modern UI - Glassmorphism design with gradient backgrounds
Accessible - Proper contrast ratios and semantic HTML
User-friendly - Intuitive navigation and clear feedback

🧪 Code Execution Engine
The platform includes a simplified Python interpreter that supports:

Basic print statements
Variable assignments
Simple arithmetic operations
Basic control structures
Function definitions (simplified)

Note: This is a learning-focused interpreter and may not support all Python features.
📱 Browser Compatibility

✅ Chrome (recommended)
✅ Firefox
✅ Safari
✅ Edge
✅ Mobile browsers

🔒 Security Features

Role-based access control
Input validation
XSS protection
Safe code execution environment

🚀 Deployment Options
Netlify (Recommended)

Visit app.netlify.com
Drag and drop index.html
Get instant deployment URL

📊 Sample Data
The application comes with sample data for demonstration:

Pre-loaded sample questions
Example student submissions
Test teacher account

🤝 Contributing

Fork the repository
Create a feature branch
Make your changes
Test thoroughly
Submit a pull request
