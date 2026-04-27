# ⚡ Patel Electrician - Professional Electrical Services Landing Page

A modern, premium, high-conversion landing page designed for an electrical service business. Built with clean HTML, CSS, and minimal JavaScript to deliver a professional agency-quality website.

![Electrician Services](https://images.unsplash.com/photo-1621905251918-48416bd8575a?q=80&w=1200&auto=format&fit=crop)

## 🌟 Features

### Design
- ✅ **Premium Light Theme** - Clean, minimal design with soft blue and elegant green color palette
- ✅ **Modern Typography** - Inter and Poppins fonts for professional appearance
- ✅ **Smooth Animations** - Scroll-based fade-up, slide-in effects, and parallax hero section
- ✅ **Responsive Design** - Fully mobile-optimized with hamburger menu
- ✅ **Custom Design** - Not a template, built from scratch for unique branding

### Sections
- 🏠 **Hero Section** - Eye-catching headline with parallax background and CTAs
- 💼 **Services Grid** - Modern card layout showcasing electrical services
- 🖼️ **Recent Works Gallery** - Portfolio with lightbox functionality
- 💰 **Pricing Cards** - Transparent pricing with feature lists
- ⭐ **Why Choose Us** - Trust-building section with key differentiators
- 📞 **Contact Section** - Split layout with info and Google Maps
- 📝 **Booking Form** - Modern form that submits to WhatsApp
- 💬 **Floating WhatsApp Button** - Smooth pulse animation for easy contact

### Interactive Features
- 🎯 Sticky navbar with smooth scroll
- 🖱️ Button hover micro-interactions
- 📸 Image lightbox for gallery
- 📱 Mobile hamburger menu
- 🔄 Scroll-triggered animations
- 📲 WhatsApp integration for bookings

## 🚀 Live Demo

**[View Live Website](https://landingpage-electrician.vercel.app)**

## 📂 Project Structure

```
main/
├── index.html          # Main landing page file
├── vercel.json         # Vercel deployment configuration
└── README.md           # Project documentation
```

## 🛠️ Technologies Used

- **HTML5** - Semantic markup
- **CSS3** - Modern styling with CSS Grid, Flexbox, Custom Properties
- **JavaScript** - Vanilla JS for interactivity
- **Font Awesome** - Professional icons
- **Google Fonts** - Inter and Poppins typography
- **Unsplash** - High-quality stock images

## 📦 Installation & Local Development

1. **Clone the repository**
   ```bash
   git clone https://github.com/4dithyan/landingpage_electrician.git
   ```

2. **Navigate to the main folder**
   ```bash
   cd landingpage_electrician/main
   ```

3. **Open in browser**
   - Simply open `index.html` in your preferred browser
   - Or use a local server:
     ```bash
     # Using Python
     python -m http.server 8000
     
     # Using Node.js (npx)
     npx serve
     ```

4. **View the website**
   - Open `http://localhost:8000` in your browser

## 🌐 Deployment to Vercel

### Method 1: Deploy via Vercel Dashboard (Recommended)

1. **Push your code to GitHub**
   ```bash
   cd landingpage_electrician
   git add .
   git commit -m "Initial commit: Premium electrician landing page"
   git push origin main
   ```

2. **Go to [Vercel](https://vercel.com)**
   - Sign in with your GitHub account

3. **Import Project**
   - Click "New Project"
   - Import the `landingpage_electrician` repository
   - Set Root Directory to `main`

4. **Deploy Settings**
   - Framework Preset: `Other`
   - Build Command: Leave blank
   - Output Directory: Leave blank
   - Install Command: Leave blank

5. **Click Deploy**
   - Your site will be live in seconds!

### Method 2: Deploy via Vercel CLI

1. **Install Vercel CLI**
   ```bash
   npm install -g vercel
   ```

2. **Login to Vercel**
   ```bash
   vercel login
   ```

3. **Deploy from main folder**
   ```bash
   cd main
   vercel
   ```

4. **Follow the prompts**
   - Set up and deploy? **Y**
   - Which scope? Choose your account
   - Link to existing project? **N**
   - Project name: `landingpage-electrician`
   - Directory: `./`
   - Want to override settings? **N**

5. **Production deployment**
   ```bash
   vercel --prod
   ```

## 🎨 Customization

### Update Business Information

Edit `index.html` and search for:
- **Phone numbers**: Replace `9356514611` and `9403668234`
- **Email**: Replace `skrhan735@gmail.com`
- **Business name**: Replace "Patel Electrician"
- **WhatsApp number**: Update in `wa.me/919356514611`

### Change Colors

Modify CSS custom properties in the `:root` section:
```css
:root {
  --primary: #2563eb;        /* Main blue color */
  --accent: #10b981;         /* Green accent */
  --primary-dark: #1d4ed8;   /* Darker blue */
  /* ... more colors */
}
```

### Update Images

**WhatsApp Images** (in test folder):
- Place your images in the `test` folder
- Update image paths in `index.html` using `../test/filename.jpeg`

**Unsplash Images**:
- Replace Unsplash URLs with your own images
- Recommended size: 1000x800px or larger

### Modify Pricing

Search for the pricing section and update:
- Service names
- Prices (₹ amounts)
- Feature lists

## 📱 Responsive Breakpoints

- **Desktop**: 993px and above
- **Tablet**: 769px - 992px
- **Mobile**: 768px and below
- **Small Mobile**: 480px and below

## ✨ Animations Included

1. **Hero Section**
   - Parallax background effect
   - Slide-in animations for text and image
   - Hover effects on buttons

2. **Scroll Animations**
   - Fade-up on scroll (Intersection Observer)
   - Staggered card reveals
   - Smooth section transitions

3. **Interactive Elements**
   - Button hover micro-interactions
   - Image zoom on hover
   - Card lift effects
   - Rotating feature icons
   - Gallery lightbox

## 🔧 Browser Support

- Chrome (latest)
- Firefox (latest)
- Safari (latest)
- Edge (latest)
- Mobile browsers (iOS Safari, Chrome Mobile)

## 📄 License

This project is created for demonstration purposes. Feel free to use and customize for your business needs.

## 👤 Author

**Patel Electrician**
- Phone: 9356514611 / 9403668234
- Email: skrhan735@gmail.com

## 🤝 Support

For questions or support:
- 📧 Email: skrhan735@gmail.com
- 📱 WhatsApp: [Chat Now](https://wa.me/919356514611)
- 📞 Call: 9356514611

---

**Made with ❤️ for professional electrical services**
