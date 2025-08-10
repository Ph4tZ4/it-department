# 🎓 IT Department Website - Loei Technical College

A modern, responsive website for the IT Department of Loei Technical College, featuring bilingual support (Thai/English), interactive animations, and comprehensive information about the department's programs, curriculum, and facilities.

## ✨ Features

### 🌐 **Bilingual Support**
- **Thai (ภาษาไทย)** - Primary language with full localization
- **English** - Secondary language support
- Language switching with persistent preferences
- Complete content translation for all sections

### 🎨 **Modern Design & UX**
- **Dark theme** with gradient accents (pink/fuchsia)
- **Responsive design** - Mobile-first approach
- **Smooth animations** with reduced motion support
- **Interactive elements** with hover effects and transitions
- **Accessibility features** - Focus rings, ARIA labels, keyboard navigation

### 📱 **Responsive Layout**
- **Mobile-first design** with progressive enhancement
- **Collapsible navigation** for mobile devices
- **Touch-friendly** interface elements
- **Optimized typography** across all screen sizes

### 🚀 **Interactive Elements**
- **Animated background** with floating particles and glowing orbs
- **Scroll-triggered animations** using Intersection Observer
- **Parallax effects** for background elements
- **Smooth scrolling** navigation
- **Count-up animations** for statistics

### 📊 **Content Sections**
- **Hero section** with call-to-action buttons
- **Department overview** - Mission, vision, and values
- **Subject offerings** - Core and elective courses
- **Curriculum structure** - 3-year program breakdown
- **Student & instructor statistics**
- **Facilities and contact information**

## 🛠️ Technologies Used

### **Frontend**
- **HTML5** - Semantic markup structure
- **CSS3** - Modern styling with custom properties
- **Tailwind CSS** - Utility-first CSS framework (via CDN)
- **Vanilla JavaScript** - No external dependencies

### **Key Features**
- **CSS Grid & Flexbox** - Modern layout systems
- **CSS Animations** - Keyframes and transitions
- **CSS Custom Properties** - Dynamic theming
- **Intersection Observer API** - Scroll-based animations
- **Local Storage** - Language preference persistence

### **Performance & Accessibility**
- **Lazy loading** for components
- **Reduced motion** support for accessibility
- **Semantic HTML** structure
- **ARIA labels** and screen reader support
- **Keyboard navigation** support

## 📁 Project Structure

```
it-department/
├── index.html              # Main HTML file
├── components/             # Reusable component files
│   ├── navbar.html        # Navigation component
│   └── footer.html        # Footer component
└── README.md              # Project documentation
```

### **File Descriptions**

- **`index.html`** - Main application file containing all sections, styles, and JavaScript
- **`components/navbar.html`** - Responsive navigation with mobile menu and language switcher
- **`components/footer.html`** - Footer with contact information and quick links
- **`README.md`** - This documentation file

## 🚀 Getting Started

### **Prerequisites**
- Modern web browser (Chrome, Firefox, Safari, Edge)
- Local web server (optional, for development)

### **Quick Start**
1. **Clone or download** the project files
2. **Open `index.html`** in your web browser
3. **Navigate** through the different sections
4. **Switch languages** using the TH/EN buttons in the navigation

### **Local Development**
For development with live reloading:

```bash
# Using Python 3
python -m http.server 8000

# Using Node.js (if you have http-server installed)
npx http-server

# Using PHP
php -S localhost:8000
```

Then open `http://localhost:8000` in your browser.

## 🎯 Key Sections

### **1. Hero Section**
- Department introduction and mission statement
- Call-to-action buttons for exploration
- Animated background elements

### **2. Overview**
- Department mission, vision, and values
- Core competencies and focus areas
- Educational approach and methodology

### **3. Subjects Offered**
- **Core Subjects**: Programming, Networking, Cybersecurity, Databases
- **Elective Subjects**: Web & Mobile Development, Multimedia & IoT
- Detailed course descriptions and learning outcomes

### **4. Curriculum Structure**
- **Year 1**: Foundations and basics
- **Year 2**: Core tracks and specialization
- **Year 3**: Advanced electives and capstone project
- Semester-by-semester breakdown

### **5. Statistics**
- **320+ current students**
- **18 experienced instructors**
- Student clubs, projects, and activities
- Instructor certifications and experience

### **6. Additional Information**
- **Facilities**: Computer labs, networking equipment, project studios
- **Admissions**: Application process, scholarships, orientation
- **Contact**: Email, phone, office hours, address

## 🌍 Internationalization (i18n)

The website supports complete bilingual functionality:

- **Automatic language detection** based on user preference
- **Persistent language selection** stored in localStorage
- **Complete content translation** for all text elements
- **Dynamic language switching** without page reload
- **Accessibility support** for both languages

### **Language Support**
- **Thai (th)**: Primary language with full localization
- **English (en)**: Secondary language for international users

## 🎨 Customization

### **Colors & Themes**
The website uses a consistent color scheme:
- **Primary**: Pink (#ec4899) to Fuchsia (#a855f7) gradients
- **Background**: Dark neutral (#0a0a0a) with transparency
- **Text**: White and neutral grays for readability
- **Accents**: Pink and fuchsia for interactive elements

### **Styling**
- **Tailwind CSS classes** for rapid development
- **Custom CSS** for animations and special effects
- **CSS variables** for consistent theming
- **Responsive breakpoints** for all device sizes

## 📱 Responsive Design

### **Breakpoints**
- **Mobile**: 320px - 768px
- **Tablet**: 768px - 1024px
- **Desktop**: 1024px+

### **Mobile Features**
- **Collapsible navigation** menu
- **Touch-optimized** buttons and interactions
- **Optimized animations** for mobile performance
- **Reduced motion** support for accessibility

## ♿ Accessibility Features

- **Semantic HTML** structure
- **ARIA labels** and descriptions
- **Keyboard navigation** support
- **Focus management** with visible focus rings
- **Reduced motion** preferences support
- **Screen reader** compatibility
- **High contrast** color scheme

## 🚀 Performance Features

- **Optimized animations** with CSS transforms
- **Intersection Observer** for efficient scroll handling
- **Lazy loading** of components
- **Minimal JavaScript** footprint
- **Efficient CSS** with Tailwind utilities
- **Optimized images** and assets

## 🔧 Browser Support

- **Chrome** 90+
- **Firefox** 88+
- **Safari** 14+
- **Edge** 90+
- **Mobile browsers** (iOS Safari, Chrome Mobile)

## 📝 Development Notes

### **Component Architecture**
- **Modular design** with separate HTML components
- **Dynamic loading** of navbar and footer
- **Event-driven** language switching
- **Responsive component** behavior

### **JavaScript Features**
- **ES6+ syntax** with modern browser APIs
- **Intersection Observer** for scroll animations
- **Local Storage** for user preferences
- **Event delegation** for dynamic content
- **Smooth scrolling** and navigation

### **CSS Architecture**
- **Utility-first** approach with Tailwind CSS
- **Custom animations** and keyframes
- **CSS Grid** and Flexbox layouts
- **Responsive design** patterns
- **Dark theme** with gradient accents

## 🤝 Contributing

This is a static website project. To contribute:

1. **Fork** the repository
2. **Create** a feature branch
3. **Make** your changes
4. **Test** across different browsers and devices
5. **Submit** a pull request

### **Development Guidelines**
- Maintain **responsive design** principles
- Ensure **accessibility** compliance
- Test **language switching** functionality
- Verify **mobile navigation** behavior
- Check **animation performance** on various devices

## 📄 License

This project is created for educational purposes at Loei Technical College.

## 📞 Contact

**IT Department - Loei Technical College**
- **Email**: it@loeitech.ac.th
- **Phone**: +66 42 123 456
- **Address**: 123 Moo 5, Tambon Nong Bua, Amphoe Mueang, Loei 42000
- **Office Hours**: Monday-Friday 8:00-16:30, Saturday 8:00-12:00

---

**Built with ❤️ for the IT Department community at Loei Technical College**
