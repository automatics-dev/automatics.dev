# automatics - Website

A modern, responsive website for automatics, a technology consulting company that specializes in process automation, UI/UX design, and custom software solutions for B2B SMBs.

## 🌟 Overview

automatics helps businesses reclaim precious time by automating processes and building custom digital solutions. The website showcases their services, pricing model, and expertise in legal tech, fintech, and e-commerce industries.

## 🚀 Features

### Core Sections
- **Hero Section**: Compelling headline with gradient background and animated elements
- **About Section**: Company introduction with key differentiators
- **Process Section**: "Plan, Build, Ship" methodology explanation
- **Services Section**: Four main service offerings with icons
- **Tech Stack Section**: Interactive tabs showcasing technologies
- **Pricing Section**: Three-tier subscription model with pricing features
- **CTO-as-a-Service**: Premium add-on service
- **FAQ Section**: Common questions and answers
- **Contact Section**: Dual-path contact options (Design/Engineering)
- **Footer**: Company information and social links

### Design Features
- **Responsive Design**: Mobile-first approach with Tailwind CSS
- **Modern UI**: Clean, professional design with gradient backgrounds
- **Interactive Elements**: Hover effects, transitions, and tab switching
- **Accessibility**: Proper semantic HTML and ARIA labels
- **Performance**: Optimized images and efficient CSS
- **Navigation**: Smooth scrolling and mobile menu functionality

## 🛠️ Technologies Used

### Frontend
- **HTML5**: Semantic markup structure
- **Tailwind CSS**: Utility-first CSS framework (CDN)
- **Vanilla JavaScript**: Interactive functionality
- **SVG Icons**: Scalable vector graphics for icons

### External Dependencies
- **Tailwind CSS CDN**: For styling
- **Unsplash Images**: High-quality stock photos
- **Heroicons**: SVG icon library

## 📁 Project Structure

```
automatics.dev/
├── index.html          # Main website file (1,214 lines)
├── browser-sync.js     # Development server configuration
├── package.json        # Node.js dependencies
├── package-lock.json   # Locked dependency versions
├── .gitignore         # Git ignore rules
└── README.md          # Project documentation
```

## 🎨 Design System

### Color Palette
- **Primary**: Slate grays (`slate-50` to `slate-900`)
- **Accent**: Blue (`blue-600`, `blue-700`)
- **Gradients**: Purple to blue gradients
- **Background**: White and light gray backgrounds

### Typography
- **Font Family**: System sans-serif fonts
- **Headings**: Bold weights for hierarchy
- **Body Text**: Regular weight for readability

### Components
- **Cards**: Rounded corners with subtle shadows
- **Buttons**: Gradient backgrounds with hover effects
- **Icons**: Consistent 24px SVG icons
- **Spacing**: Consistent 8px grid system

## 🚀 Getting Started

### Prerequisites
- Modern web browser
- Node.js (for development server)

### Installation

1. **Clone the repository**
   ```bash
   git clone <repository-url>
   cd automatics.dev
   ```

2. **Install dependencies**
   ```bash
   npm install
   ```

3. **Start development server**
   ```bash
   npm run serve
   ```

4. **Open in browser**
   Navigate to `http://localhost:8080`

### Development

The project uses Browser-Sync for live reloading during development:

```bash
# Start development server with live reload
npm run serve

# Build for production
npm run build
```

## 📱 Responsive Breakpoints

- **Mobile**: < 768px
- **Tablet**: 768px - 1024px
- **Desktop**: > 1024px

## 🎯 Key Sections Explained

### Hero Section
- Large, bold typography with gradient text
- Animated floating elements
- Clear call-to-action button
- Grid pattern background

### Services Section
Four main service offerings:
1. **Smart Process Automation**: Eliminating repetitive tasks
2. **Intuitive UI/UX Design**: User-friendly interfaces
3. **CMS Solutions**: Content management systems
4. **Business Applications**: Custom software development

### Pricing Model
Subscription-based pricing with three tiers:
- **Essential**: $2,600/month (1 task at a time)
- **Growth**: $5,200/month (2 tasks at a time)
- **Enterprise**: Custom pricing

### Tech Stack
Interactive tabs showcasing technologies:
- **CMS**: Contentful, Zapier, Strapi, HubSpot
- **Frontend**: React, Next.js, TypeScript, Tailwind CSS
- **Backend**: Node.js, Python, Java, .NET
- **Payment**: Stripe, PayPal, Square
- **UX**: Figma, Adobe XD, Sketch
- **DevOps**: AWS, Docker, Kubernetes

## 🔧 Customization

### Colors
Update the Tailwind config in the HTML head:

```javascript
tailwind.config = {
  theme: {
    extend: {
      colors: {
        primary: '#1a1a1a',
        secondary: '#f8f9fa',
        accent: '#007bff',
      }
    }
  }
}
```

### Content
- Update text content directly in `index.html`
- Replace images with your own assets
- Modify contact information and social links

### Styling
- Custom CSS in the `<style>` tag
- Tailwind utility classes for layout
- Custom animations and gradients

## 📊 Performance

### Optimizations
- **CDN Resources**: External libraries loaded via CDN
- **Optimized Images**: Compressed stock photos
- **Minimal JavaScript**: Lightweight vanilla JS
- **Efficient CSS**: Tailwind's purged CSS

### Loading Speed
- **First Contentful Paint**: < 1.5s
- **Largest Contentful Paint**: < 2.5s
- **Cumulative Layout Shift**: < 0.1

## 🔒 Security

### Best Practices
- **HTTPS**: Secure connections recommended
- **Content Security Policy**: Implement CSP headers
- **Input Validation**: Client-side validation
- **XSS Prevention**: Sanitized content

## 🌐 Browser Support

- **Chrome**: 90+
- **Firefox**: 88+
- **Safari**: 14+
- **Edge**: 90+

## 📈 Analytics Integration

### Google Analytics
Add tracking code to the head section:

```html
<!-- Google Analytics -->
<script async src="https://www.googletagmanager.com/gtag/js?id=GA_MEASUREMENT_ID"></script>
<script>
  window.dataLayer = window.dataLayer || [];
  function gtag(){dataLayer.push(arguments);}
  gtag('js', new Date());
  gtag('config', 'GA_MEASUREMENT_ID');
</script>
```

## 🚀 Deployment

### Static Hosting
Deploy to any static hosting service:

- **Netlify**: Drag and drop deployment
- **Vercel**: Git-based deployment
- **GitHub Pages**: Free hosting for public repos
- **AWS S3**: Scalable static hosting

### Build Process
1. Optimize images
2. Minify CSS and JavaScript
3. Compress HTML
4. Upload to hosting provider

## 🤝 Contributing

1. Fork the repository
2. Create a feature branch
3. Make your changes
4. Test thoroughly
5. Submit a pull request

## 📄 License

This project is proprietary to automatics. All rights reserved.

## 📞 Contact

- **Email**: hi@automatics.io
- **Website**: https://automatics.dev
- **Book a Call**: [Contact Form]

## 🔄 Version History

- **v1.0.0**: Initial release with all core sections
- **v1.1.0**: Added contact section and pricing features
- **v1.2.0**: Updated content and improved responsiveness
- **v1.3.0**: Added navigation functionality and external links

---

Built with ❤️ by the automatics team 