# Social Nexus - Digital Agency Website

**Where Brands Become Digital Powerhouses**

A modern, creative, colorful, and interactive website for Social Nexus—a digital media & branding agency powered by SGCA Technologies.

## 🚀 Features

- **Modern Design**: Energetic, creative, colorful, and premium UI
- **Fully Responsive**: Mobile-first design that works on all devices
- **Interactive Animations**: Smooth transitions, hover effects, and scroll animations
- **Component-Based**: Clean, reusable React components
- **SEO Optimized**: Proper meta tags and semantic HTML structure
- **Performance**: Optimized build with Vite

## 🛠️ Tech Stack

- **React JS** - UI framework
- **Tailwind CSS** - Utility-first styling
- **React Router** - Client-side routing
- **Vite** - Build tool and dev server

## 📁 Project Structure

src/
├── components/          # Reusable UI components
│   ├── Layout.jsx      # Main layout wrapper
│   ├── Navbar.jsx      # Navigation bar
│   ├── Footer.jsx      # Footer component
│   ├── Logo.jsx        # Brand logo
│   ├── ServiceCard.jsx # Service card component
│   └── BlogCard.jsx    # Blog post card
├── sections/           # Page sections
│   ├── Hero.jsx        # Hero section
│   ├── WhoWeAre.jsx    # About section
│   ├── CoreServices.jsx # Services grid
│   ├── WhyChoose.jsx   # Benefits section
│   ├── Industries.jsx   # Industries grid
│   ├── CTASection.jsx  # Call-to-action
│   ├── ServicesList.jsx # Detailed services
│   ├── ProcessTimeline.jsx # Process steps
│   ├── PortfolioGrid.jsx # Portfolio showcase
│   ├── TestimonialSlider.jsx # Testimonials carousel
│   ├── BlogGrid.jsx    # Blog posts grid
│   └── ContactSection.jsx # Contact form
├── pages/              # Page components
│   ├── Home.jsx        # Homepage
│   ├── About.jsx       # About page
│   ├── Services.jsx    # Services page
│   ├── Process.jsx     # Process page
│   ├── Portfolio.jsx   # Portfolio page
│   ├── Testimonials.jsx # Testimonials page
│   ├── Blog.jsx         # Blog page
│   └── Contact.jsx     # Contact page
├── App.jsx             # Main app component with routes
├── main.jsx            # Entry point
└── index.css           # Global styles & Tailwind directives
```

## 🎨 Color Theme

The website uses a custom color palette defined in `src/index.css`. **Important**: Replace the placeholder HSL values with the exact colors from your Social Nexus color palette PDF.

Current placeholder colors:
- Primary: Purple gradient
- Secondary: Blue gradient
- Accent: Orange gradient
- Background: Dark theme

## 🚦 Getting Started

### Install Dependencies

```bash
npm install
```

### Development Server

```bash
npm run dev
```

Visit `http://localhost:5173` to see the website.

### Build for Production

```bash
npm run build
```

The production build will be in the `dist/` directory.

### Preview Production Build

```bash
npm run preview
```

## 📝 Pages

1. **Home** (`/`) - Hero, Who We Are, Core Services, Why Choose, Industries, CTA
2. **About** (`/about`) - Vision, Mission, SGCA Technologies highlight
3. **Services** (`/services`) - Detailed service cards with expandable details
4. **Process** (`/process`) - Timeline of how we work
5. **Portfolio** (`/portfolio`) - Filterable portfolio grid
6. **Testimonials** (`/testimonials`) - Auto-scrolling testimonial carousel
7. **Blog** (`/blog`) - Blog posts grid
8. **Contact** (`/contact`) - Contact form and details

## 🎯 Key Features

- **Smooth Animations**: Intersection Observer for scroll-triggered animations
- **Hover Effects**: Interactive cards, buttons, and links
- **Responsive Design**: Mobile-first approach with breakpoints
- **Accessibility**: Semantic HTML, ARIA labels, keyboard navigation
- **Performance**: Optimized images, code splitting, lazy loading ready

## 🔧 Customization

### Update Colors

Edit `src/index.css` and replace the CSS variables in `:root` with your brand colors from the Social Nexus color palette PDF.

### Add Content

- Update service descriptions in `src/sections/CoreServices.jsx`
- Modify testimonials in `src/sections/TestimonialSlider.jsx`
- Add portfolio items in `src/sections/PortfolioGrid.jsx`
- Update blog posts in `src/sections/BlogGrid.jsx`

## 📄 License

© 2026 Social Nexus. All rights reserved.
