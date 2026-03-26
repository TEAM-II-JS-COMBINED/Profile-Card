# ClassGlass - Student Profile Cards

A modern, dark-themed student directory showcasing the Class of 2025 with beautiful glass-morphism design and interactive profile cards.

## 🎓 Overview

ClassGlass is an elegant student profile directory featuring:
- **6 Student Profiles** across 4 different disciplines
- **Glass-morphism Design** with dark theme and vibrant accents
- **Responsive Layout** that works seamlessly on all devices
- **Interactive Cards** with hover effects and smooth animations
- **Modern Tech Stack** built with Tailwind CSS v4

## 🚀 Features

- **Responsive Grid Layout** - Adapts from 1 to 3 columns based on screen size
- **Glass-morphism Effects** - Beautiful frosted glass appearance with backdrop blur
- **Interactive Hover States** - Dynamic glow effects and smooth transitions
- **Color-coded Disciplines** - Each student has a unique color theme
- **Mobile Navigation** - Hamburger menu for mobile devices
- **Smooth Scrolling** - Navigation between sections
- **Modern Typography** - Custom font displays and readable body text

## 🛠️ Tech Stack

- **HTML5** - Semantic markup and structure
- **Tailwind CSS v4** - Utility-first styling framework
- **Vanilla JavaScript** - Interactive features and animations
- **CSS Variables** - Dynamic theming and color management

## 📁 Project Structure

```
Profile-Card/
├── index.html              # Main directory page
├── src/
│   ├── input.css          # Tailwind CSS imports
│   └── output.css         # Compiled Tailwind styles
├── package.json           # Dependencies and scripts
├── package-lock.json      # Dependency lock file
├── .gitignore            # Git ignore rules
└── README.md             # This file
```

## 🎨 Design System

### Color Palette
- **Cyan** (#2dd4dc) - Primary accent color
- **Purple** (#8a5fff) - Secondary accent
- **Orange** (#ff8040) - Tertiary accent
- **Green** (#40e67a) - Success/accent
- **Yellow** (#ffd93d) - Highlight color
- **Pink** (#e84da0) - Additional accent

### Typography
- **Display Font** - Bold, modern sans-serif for headings
- **Body Font** - Clean, readable sans-serif for content

## 👥 Student Profiles

The directory features 6 students from various disciplines:

1. **Amara Osei** - Frontend Developer (React, CSS, UX)
2. **Zara Ahmed** - UI Designer (Figma, Tailwind, SVG)
3. **Kofi Mensah** - Backend Developer (Node.js, Python, SQL)
4. **Lila Torres** - Data Analyst (Python, Excel, Data Viz)
5. **Emeka Nwosu** - Mobile Developer (Flutter, Dart, APIs)
6. **Priya Sharma** - Cybersecurity (Linux, Kali, Networking)

## 🚀 Getting Started

### Prerequisites
- Node.js (v14 or higher)
- npm or yarn

### Installation

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd Profile-Card
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Build the CSS**
   ```bash
   npm run build
   ```

4. **Start development server**
   ```bash
   npm run dev
   ```

5. **Open in browser**
   Navigate to `http://localhost:3000` or open `index.html` directly

## 📜 Available Scripts

- `npm run build` - Compile Tailwind CSS
- `npm run dev` - Start development server with watch mode
- `npm run start` - Start production server

## 🎯 Customization

### Adding New Students

1. Copy an existing card structure in `index.html`
2. Update the student information:
   - Name and role
   - Avatar initial and color
   - Skills list
   - Profile link
3. Adjust the color variables for unique theming

### Modifying Colors

Update the CSS variables in the styles section:
```css
:root {
  --cyan: #2dd4dc;
  --purple: #8a5fff;
  /* ... other colors */
}
```

### Adding New Sections

1. Create new HTML sections following the existing pattern
2. Use the established CSS classes for consistency
3. Add navigation links if needed

## 🔧 Development

### CSS Architecture
- **Tailwind CSS** for utility classes
- **Custom CSS** for specific glass-morphism effects
- **CSS Variables** for consistent theming
- **Responsive Design** with mobile-first approach

### JavaScript Features
- **Smooth scrolling** navigation
- **Interactive hover effects**
- **Mobile menu toggle**
- **Dynamic shadow effects**

## 📱 Browser Support

- Chrome/Chromium (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 🤝 Contributing

1. clon the repository
2. Create a feature branch (`git checkout -b feature/amazing-feature`)
3. Commit your changes (`git commit -m 'Add amazing feature'`)
4. Push to the branch (`git push origin feature/amazing-feature`)
5. Open a Pull Request

## 🙏 Acknowledgments

- **Tailwind CSS** for the amazing utility framework
- **Glass-morphism design** inspiration from modern UI trends
- **Class of 2025** - the brilliant students featured in this directory

---

Built with 💙 by the development team
