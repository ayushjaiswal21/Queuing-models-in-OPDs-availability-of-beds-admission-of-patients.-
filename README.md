# 🏥 Health & Care - Hospital Management System

> A comprehensive digital healthcare platform designed to revolutionize hospital bed management, patient admissions, and healthcare service delivery.

[![Made with HTML5](https://img.shields.io/badge/Made%20with-HTML5-orange.svg)](https://developer.mozilla.org/en-US/docs/Web/Guide/HTML/HTML5)
[![CSS3](https://img.shields.io/badge/CSS3-1572B6?style=flat&logo=css3&logoColor=white)](https://www.w3.org/Style/CSS/)
[![TailwindCSS](https://img.shields.io/badge/Tailwind_CSS-38B2AC?style=flat&logo=tailwind-css&logoColor=white)](https://tailwindcss.com/)
[![JavaScript](https://img.shields.io/badge/JavaScript-F7DF1E?style=flat&logo=javascript&logoColor=black)](https://developer.mozilla.org/en-US/docs/Web/JavaScript)

## 📋 Table of Contents
- [Overview](#overview)
- [Key Features](#key-features)
- [Project Structure](#project-structure)
- [Getting Started](#getting-started)
- [Installation](#installation)
- [Usage](#usage)
- [Technologies Used](#technologies-used)
- [Screenshots](#screenshots)
- [Contributing](#contributing)
- [License](#license)

## 🎯 Overview

Health & Care is a modern web-based hospital management system that addresses critical challenges in healthcare delivery. Our platform implements advanced queuing models for OPDs, real-time bed availability tracking, and streamlined patient admission processes.

### 🚀 Mission
To enhance healthcare accessibility and efficiency through innovative digital solutions that reduce wait times, optimize resource allocation, and improve overall patient experience.

### 🎪 Vision
To become the leading platform for hospital management, enabling seamless integration of healthcare services across city-wide health modules.

## ✨ Key Features

### 🛏️ **Real-time Bed Management**
- Live tracking of bed availability across different wards
- Automated bed allocation system
- Multiple bed categories: General Ward, Semi Deluxe, Deluxe, Emergency

### 👥 **Patient Management**
- Streamlined patient registration process
- Digital admission forms with validation
- Patient history and medical record management

### 🏥 **Department Integration**
- Multi-specialty support (Cardiology, Neurology, Dermatology, etc.)
- Doctor consultation booking
- Department-wise resource allocation

### 📊 **Administrative Features**
- Admin dashboard for hospital management
- Real-time analytics and reporting
- Inventory management for medicines and consumables

### 💬 **User Support**
- Comprehensive FAQ section
- Multi-platform login (Admin/Patient)
- Responsive design for all devices

## 📁 Project Structure

```
Health-Care/
├── README.md
└── new final health&care/
    └── Health&care/
        ├── Hospital-Bed-Managment/
        │   ├── index.html              # Main dashboard
        │   ├── index2.html             # Doctor consultation
        │   ├── css/
        │   │   ├── input.css
        │   │   └── output.css
        │   ├── src/
        │   │   ├── Css/
        │   │   └── Images/
        │   ├── Images/
        │   ├── package.json            # Node.js dependencies
        │   └── tailwind.config.js     # Tailwind configuration
        ├── Registration form/
        │   ├── index.html              # Patient registration
        │   └── style.css
        ├── login page/
        │   ├── index.html              # User authentication
        │   ├── style.css
        │   └── script.js
        ├── About Us/
        │   ├── index.html              # Company information
        │   └── style.css
        └── FAQ-Section/
            ├── index.html              # Frequently asked questions
            ├── style.css
            └── script.js
```

## 🚀 Getting Started

### Prerequisites

Before running this project, make sure you have:

- A modern web browser (Chrome, Firefox, Safari, Edge)
- Node.js (v14 or higher) - for development
- Git for version control

### 📦 Installation

1. **Clone the repository**
   ```bash
   git clone git@github.com:ayushjaiswal21/Health-Care.git
   cd Health-Care
   ```

2. **Navigate to the project directory**
   ```bash
   cd "new final health&care/Health&care/Hospital-Bed-Managment"
   ```

3. **Install dependencies**
   ```bash
   npm install
   ```

4. **Build Tailwind CSS** (if making changes)
   ```bash
   npx tailwindcss -i ./css/input.css -o ./css/output.css --watch
   ```

## 🎮 Usage

### For Patients:
1. Visit the main landing page (`Hospital-Bed-Managment/index.html`)
2. Click "Book A Bed" to start the registration process
3. Fill out the registration form with your details
4. Select your preferred department and bed type
5. Complete the booking process

### For Administrators:
1. Click on the "Admin" button on the main page
2. Use admin credentials to access the dashboard
3. Monitor bed availability and patient registrations
4. Manage hospital resources and inventory

### Quick Start (Local Development):
```bash
# Open the main page in your browser
open "new final health&care/Health&care/Hospital-Bed-Managment/index.html"

# Or use a local server
python -m http.server 8000  # Python 3
# Then visit http://localhost:8000
```

## 🛠️ Technologies Used

| Technology | Purpose | Version |
|------------|---------|----------|
| **HTML5** | Structure and markup | Latest |
| **CSS3** | Styling and animations | Latest |
| **Tailwind CSS** | Utility-first CSS framework | ^3.4.10 |
| **JavaScript** | Interactive functionality | ES6+ |
| **Bootstrap** | Responsive components | 4.5.2 |
| **Font Awesome** | Icons and UI elements | 6.6.0 |

## 🌟 Key Highlights

- **Responsive Design**: Works seamlessly across all devices
- **Modern UI/UX**: Clean, intuitive interface design
- **Fast Performance**: Optimized for quick loading and smooth interactions
- **Accessibility**: Built with web accessibility standards in mind
- **Scalable Architecture**: Easy to extend and modify

## 🤝 Contributing

We welcome contributions from the community! Here's how you can help:

1. **Fork the repository**
2. **Create a feature branch**
   ```bash
   git checkout -b feature/amazing-feature
   ```
3. **Commit your changes**
   ```bash
   git commit -m 'Add some amazing feature'
   ```
4. **Push to the branch**
   ```bash
   git push origin feature/amazing-feature
   ```
5. **Open a Pull Request**

### 📋 Contribution Guidelines
- Follow existing code style and conventions
- Add comments for complex functionality
- Test your changes thoroughly
- Update documentation as needed

## 📝 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 👥 Authors

- **Ayush Jaiswal** - *Initial work* - [@ayushjaiswal21](https://github.com/ayushjaiswal21)

## 🙏 Acknowledgments

- Thanks to all healthcare professionals who inspired this project
- Bootstrap and Tailwind CSS communities for excellent frameworks
- Font Awesome for beautiful icons

## 📞 Support

If you have any questions or need help, please:
- Check our [FAQ section](new%20final%20health%26care/Health%26care/FAQ-Section/index.html)
- Open an issue on GitHub
- Contact the development team

---

<div align="center">
  <strong>Made with ❤️ for better healthcare</strong>
  <br>
  <sub>Health & Care - Enhancing Healthcare Access</sub>
</div>
