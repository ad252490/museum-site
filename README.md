# Community Science Museum

A responsive website for a community science museum featuring exhibitions, events, and educational programs.

## 📋 Project Overview

This is a static website built for a Community Science Museum. The site provides information about the museum's programs, exhibitions, events, and visitor information. It features a clean, modern design with responsive layouts that work across desktop, tablet, and mobile devices.

## ✨ Features

- **Responsive Design**: Fully responsive layout that adapts to different screen sizes
- **Navigation Menu**: 
  - Desktop navigation bar
  - Mobile hamburger menu for smaller screens
- **Search Functionality**: Search bar for finding museum content
- **User Account**: Login and registration options
- **Shopping Cart**: Cart functionality for museum tickets or merchandise
- **Social Media Integration**: Links to museum's social media profiles
- **Educational Content**: Information about various science topics including:
  - Cosmology
  - Museum exhibitions
  - Educational programs
  - Special events

## 📁 File Structure

```
museum-site/
├── index.html              # Main homepage
├── css/
│   ├── home..css          # Homepage-specific styles
│   └── general_style.css  # General/shared styles
├── images/
│   ├── homeimagetop.jpg   # Hero image
│   └── kid-touches-robot.jpg  # Content image
└── README.md              # This file
```

## 🚀 Getting Started

### Prerequisites

- A modern web browser (Chrome, Firefox, Safari, Edge)
- A text editor (VS Code, Sublime Text, etc.) if you want to modify the code

### Installation & Usage

1. Clone this repository:
   ```bash
   git clone https://github.com/ad252490/museum-site.git
   ```

2. Navigate to the project directory:
   ```bash
   cd museum-site
   ```

3. Open `index.html` in your web browser:
   - Double-click the file, or
   - Right-click and select "Open with" your preferred browser, or
   - Use a local development server (optional)

### Using a Local Development Server (Optional)

For a better development experience, you can use a local server:

**Using Python:**
```bash
# Python 3
python -m http.server 8000

# Python 2
python -m SimpleHTTPServer 8000
```

**Using Node.js (with http-server):**
```bash
npx http-server
```

Then visit `http://localhost:8000` in your browser.

## 🛠️ Technologies Used

- **HTML5**: Structure and content
- **CSS3**: Styling and layout
- **Font Awesome 6.3.0**: Icons for UI elements
- **Responsive Design**: Media queries for mobile compatibility

## 🎨 Key Sections

1. **Header**: Contains museum branding, search functionality, and user account options
2. **Navigation**: Main menu with links to:
   - Home
   - Museum Programs
   - Explore
   - Events
   - Exhibitions
   - Visit Us
3. **Hero Section**: Large banner image showcasing the museum
4. **Content Areas**: Educational content about science and cosmology
5. **Quick Links**: Button grid for easy navigation
6. **Footer**: Social media links, payment options, and contact information

## 📱 Responsive Features

- **Desktop**: Full navigation bar with all menu items visible
- **Tablet/Mobile**: Hamburger menu that expands on click
- **Flexible Images**: Images scale appropriately for different screen sizes
- **Mobile-Optimized Layout**: Content reflows for optimal viewing on smaller screens

## 📞 Contact Information

- **Phone**: +256757886712
- **Social Media**: 
  - Facebook
  - Instagram
  - TikTok
  - Twitter

## 🔧 Customization

To customize the website:

1. **Colors**: Edit the color schemes in `css/general_style.css`
2. **Content**: Modify the text in `index.html`
3. **Images**: Replace images in the `images/` folder (keep the same filenames or update references in HTML)
4. **Styling**: Adjust layouts and styles in the CSS files

## 📄 License

This project is available for educational and community purposes.

## 🤝 Contributing

Contributions are welcome! Feel free to:
- Report bugs
- Suggest new features
- Submit pull requests

## 📝 Notes

- The website uses Font Awesome for icons. Make sure the Font Awesome library is properly linked.
- Some navigation links are currently placeholders and point to relative paths (e.g., `/museum_programs`, `/explore`).
- The payment system and shopping cart are UI elements only and don't have backend functionality implemented.
- Note: The HTML references `visa.png` in the footer, but this image file is not currently included in the repository.

---

**Built with ❤️ for the Community Science Museum**
