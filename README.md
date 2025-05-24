# AltoPay - The Future of Digital Banking

<div align="center">
  <img src="https://img.shields.io/badge/HTML5-E34F26?style=for-the-badge&logo=html5&logoColor=white" alt="HTML5">
  <img src="https://img.shields.io/badge/CSS3-1572B6?style=for-the-badge&logo=css3&logoColor=white" alt="CSS3">
  <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=for-the-badge&logo=javascript&logoColor=black" alt="JavaScript">
  <img src="https://img.shields.io/badge/Vercel-000000?style=for-the-badge&logo=vercel&logoColor=white" alt="Vercel">
</div>

## 🌟 Overview

AltoPay is a modern, innovative digital banking platform designed for the future of financial services. This landing page showcases our cutting-edge fintech solutions including digital wallets, cryptocurrency trading, investment platforms, and comprehensive business banking services.

## ✨ Features

- **🎨 Modern Design**: Beautiful, responsive UI with smooth animations
- **🔒 Security Focus**: Bank-grade security features and encryption
- **📱 Mobile First**: Optimized for all devices and screen sizes
- **⚡ Performance**: Lightning-fast loading with optimized assets
- **🎯 Interactive Elements**: Engaging animations powered by Vanta.js
- **♿ Accessibility**: WCAG compliant and screen reader friendly

## 🚀 Live Demo

Visit our live demo: [AltoPay Landing Page](https://your-vercel-url.vercel.app)

## 🛠️ Tech Stack

- **Frontend**: HTML5, CSS3, JavaScript (ES6+)
- **Styling**: Custom CSS with CSS Variables and Grid/Flexbox
- **Fonts**: Inter & Montserrat from Google Fonts
- **Icons**: Font Awesome 6
- **Animations**: Vanta.js for 3D background effects
- **Deployment**: Vercel with optimized configuration

## 📁 Project Structure

```
altopay-landing/
├── index.html              # Main HTML file
├── css/
│   ├── altopay.webflow.css # Custom styles
│   ├── normalize.css       # CSS reset
│   └── webflow.css        # Webflow framework styles
├── js/
│   └── webflow.js         # Interactive functionality
├── images/
│   ├── favicon.ico        # Site favicon
│   └── webclip.png       # Apple touch icon
├── vercel.json            # Vercel deployment configuration
└── README.md             # Project documentation
```

## 🚀 Quick Start

### Local Development

1. Clone the repository:
```bash
git clone https://github.com/yourusername/altopay-landing.git
cd altopay-landing
```

2. Open `index.html` in your browser or use a local server:
```bash
# Using Python
python -m http.server 8000

# Using Node.js
npx serve .

# Using PHP
php -S localhost:8000
```

3. Visit `http://localhost:8000` to view the site

### Deploy to Vercel

#### Option 1: Deploy via Vercel CLI

1. Install Vercel CLI:
```bash
npm i -g vercel
```

2. Login to Vercel:
```bash
vercel login
```

3. Deploy:
```bash
vercel --prod
```

#### Option 2: Deploy via GitHub Integration

1. Push your code to GitHub
2. Visit [Vercel Dashboard](https://vercel.com/dashboard)
3. Click "New Project"
4. Import your GitHub repository
5. Vercel will automatically detect and deploy your static site

#### Option 3: Deploy via Drag & Drop

1. Visit [Vercel Deploy](https://vercel.com/new)
2. Drag and drop your project folder
3. Vercel will automatically deploy your site

## 🔧 Configuration

### Vercel Configuration

The `vercel.json` file includes:
- Static file optimization
- Security headers
- Cache control for assets
- Single Page Application routing

### Performance Optimizations

- **Image Optimization**: WebP format support
- **CSS Minification**: Optimized stylesheets
- **Font Loading**: Preconnect to Google Fonts
- **Cache Headers**: Long-term caching for static assets

## 🎨 Customization

### Colors

Update the CSS variables in `css/altopay.webflow.css`:

```css
:root {
  --primary: #ff6a6a;        /* Primary brand color */
  --secondary: #ff5a00;      /* Secondary accent color */
  --black: #0a0a0a;          /* Dark background */
  --white: #ffffff;          /* Light text */
}
```

### Content

Modify the content in `index.html` to match your brand:
- Update company name and branding
- Modify service descriptions
- Change contact information
- Update social media links

### Animations

Customize the Vanta.js background in the script section of `index.html`:

```javascript
VANTA.BIRDS({
  el: "#hero",
  backgroundColor: 0x0a0a0a,  // Background color
  color1: 0xff6a6a,          // Primary bird color
  color2: 0xff5a00,          // Secondary bird color
  birdSize: 0.60,            // Size of birds
  wingSpan: 25.00,           // Wing span
  speedLimit: 3.00,          // Movement speed
});
```

## 📱 Responsive Design

The landing page is fully responsive with breakpoints:
- **Desktop**: 1200px and above
- **Tablet**: 768px - 1199px
- **Mobile**: 320px - 767px

## 🔒 Security Features

- **Content Security Policy**: XSS protection
- **Frame Options**: Clickjacking prevention
- **HTTPS Only**: Secure connection enforcement
- **Referrer Policy**: Privacy protection

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch: `git checkout -b feature/amazing-feature`
3. Commit your changes: `git commit -m 'Add amazing feature'`
4. Push to the branch: `git push origin feature/amazing-feature`
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 📞 Support

For support and questions:
- **Email**: support@altopay.com
- **Website**: [altopay.com](https://altopay.com)
- **Issues**: [GitHub Issues](https://github.com/yourusername/altopay-landing/issues)

## 🙏 Acknowledgments

- Design inspiration from modern fintech platforms
- Vanta.js for beautiful background animations
- Font Awesome for icons
- Google Fonts for typography

---

<div align="center">
  <p>Made with ❤️ for the future of digital banking</p>
  <p>© 2024 AltoPay. All rights reserved.</p>
</div> 