# Onboarding Portal - Personalized Checklist Generator

## Project Overview
The Onboarding Portal is a comprehensive web application designed to streamline the employee onboarding process by generating personalized checklists based on an employee's role, department, and experience level. The application provides a user-friendly interface that guides new hires through a customized onboarding journey, ensuring they complete all necessary tasks relevant to their specific position.

## 🚀 Features
- **Role-Based Checklists**: Automatically generates personalized onboarding tasks based on employee profile
- **Multi-Department Support**: Covers Tech, HR, and Operations departments
- **Experience Level Customization**: Tailored tasks for Junior, Mid, and Senior level employees
- **Interactive Task Management**: Add, edit, delete, and mark tasks as complete
- **Progress Tracking**: Real-time progress monitoring and save functionality
- **Responsive Design**: Beautiful glassmorphism UI with mobile-friendly design
- **User Authentication**: Secure login system with remember me functionality
- **Profile Setup**: Comprehensive profile creation for accurate checklist generation

## 🛠️ Tech Stack
- **Frontend**: HTML5, CSS3, JavaScript (ES6+)
- **Styling**: Tailwind CSS
- **Icons**: Font Awesome 6.5.1
- **Design**: Glassmorphism UI with backdrop blur effects
- **Background**: Unsplash API for dynamic backgrounds

## 👥 Supported Roles & Departments

### Roles:
- **Developer**: Technical roles focused on coding and development
- **Designer**: Creative roles focused on UI/UX and visual design
- **Product Manager**: Strategic roles focused on product development and management

### Departments:
- **Tech**: Technology and engineering department
- **HR**: Human resources and people operations
- **Operations**: Business operations and logistics

### Experience Levels:
- **Junior**: Entry-level positions with foundational tasks
- **Mid**: Mid-level positions with intermediate responsibilities
- **Senior**: Senior-level positions with leadership and strategic tasks

## 📋 Prerequisites
- Modern web browser (Chrome, Firefox, Safari, Edge)
- Internet connection for external CDN resources
- No server setup required - runs entirely in the browser

## 🔧 Installation

### **Clone the Repository**
```bash
git clone https://github.com/yourusername/onboarding-portal.git
cd onboarding-portal
```

### **Option 1: Direct Browser Access**
Simply open the `Onboarding Portal.html` file in your web browser:
```bash
open "Onboarding Portal.html"
```

### **Option 2: Local Server (Recommended)**
For better development experience, use a local server:

**Using Python:**
```bash
python -m http.server 8000
```
Then navigate to `http://localhost:8000`

**Using Node.js (http-server):**
```bash
npx http-server
```

**Using Live Server (VS Code Extension):**
1. Install Live Server extension in VS Code
2. Right-click on the HTML file
3. Select "Open with Live Server"

## 🖼️ Screenshots
<img width="1919" height="928" alt="image" src="https://github.com/user-attachments/assets/9dab261c-5ff1-40d0-a8ea-4c3a95a5892c" />
<img width="1912" height="930" alt="image" src="https://github.com/user-attachments/assets/5710cd85-c3dd-4a5e-a0b1-bbfe3352d51d" />
<img width="1894" height="928" alt="image" src="https://github.com/user-attachments/assets/dcc35487-9621-464c-ae94-4ee6fa71344b" />
<img width="1896" height="312" alt="image" src="https://github.com/user-attachments/assets/7ed3206e-2e63-41bb-975a-55347ba0dc79" />

## 🎯 Usage

### Step 1: Login
- Enter your credentials on the login page
- Optional: Check "Remember me" for future visits
- Click "Login" to proceed

### Step 2: Profile Setup
- **Full Name**: Enter your complete name
- **Role**: Select from Developer, Designer, or Product Manager
- **Department**: Choose between Tech, HR, or Operations
- **Level**: Select Junior, Mid, or Senior experience level
- Click "Save and Continue"

### Step 3: Personalized Checklist
- View your automatically generated checklist
- **Mark Complete**: Check off completed tasks
- **Edit Tasks**: Click the pencil icon to modify task descriptions
- **Delete Tasks**: Click the trash icon to remove tasks
- **Add Tasks**: Click "Add Task" to include custom tasks
- **Save Progress**: Click "Save" to preserve your progress
- **Complete Onboarding**: Click "Next" when finished

## 📁 Project Structure
```
onboarding-portal/
├── Onboarding Portal.html     # Main application file
├── README.md                  # Project documentation
└── assets/                    # (Optional) Local assets folder
    ├── images/
    └── icons/
```

## 🎨 Design Features
- **Glassmorphism UI**: Modern glass-like design with backdrop blur
- **Responsive Layout**: Adapts to all screen sizes
- **Beautiful Background**: Dynamic Unsplash imagery
- **Smooth Animations**: Hover effects and transitions
- **Intuitive Icons**: Font Awesome icons for better UX
- **Professional Typography**: Clean, readable fonts

## 🔧 Customization

### Adding New Roles
To add a new role, update the `checklistTemplates` object in the JavaScript section:

```javascript
checklistTemplates.NewRole = {
  Tech: {
    Junior: ["Task 1", "Task 2", ...],
    Mid: ["Task 1", "Task 2", ...],
    Senior: ["Task 1", "Task 2", ...]
  },
  // ... other departments
};
```

### Adding New Departments
Add new departments to existing roles:

```javascript
checklistTemplates.Developer.NewDepartment = {
  Junior: ["Task 1", "Task 2", ...],
  Mid: ["Task 1", "Task 2", ...],
  Senior: ["Task 1", "Task 2", ...]
};
```

### Customizing Styling
- Modify Tailwind classes in the HTML
- Add custom CSS in the `<style>` section
- Change background image by updating the `background-image` URL

## 📊 Checklist Examples

### Developer - Tech - Junior
- Set up GitHub
- Clone starter project
- Install VS Code
- Read engineering wiki
- Configure dev environment
- Join tech Slack channel
- And more...

### Designer - HR - Mid
- Design onboarding posters
- Update internal decks
- Define icon pack
- Improve layout templates
- Conduct HR asset audit
- And more...

### Product Manager - Operations - Senior
- Plan automation workflows
- Lead supply strategy meet
- Review team metrics
- Define ops roadmap
- Lead OKR planning
- And more...

## 🤝 Contributing
1. Fork the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add some amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 🐛 Issues & Support
If you encounter any issues or have suggestions:
1. Check existing issues on GitHub
2. Create a new issue with detailed description
3. Include browser information and steps to reproduce

## 📝 License
This project is licensed under the MIT License - see the [LICENSE.md](LICENSE.md) file for details.

## 🌟 Future Enhancements
- [ ] User data persistence with local storage
- [ ] Email notifications for task reminders
- [ ] Analytics dashboard for HR teams
- [ ] Integration with HR management systems
- [ ] Mobile app version
- [ ] Multi-language support
- [ ] Calendar integration
- [ ] Progress reporting

## 📧 Contact
For questions or support, please reach out:
- Email: [r.keer2005@gmail.com]
- GitHub: [RasuriKEERTHANA]

---

**Happy Onboarding! 🎉**

*Making employee onboarding smooth, personalized, and efficient.*
