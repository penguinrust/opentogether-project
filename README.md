# Open Together

## 📌 Quick Links

-   [Live Site](https://codeinstitute.penguincode.tech/)
-   [Features](#-features)
-   [Testing](#-testing)
-   [Deployment](#-deployment)

## 🎯 Project Overview

Open Together is a comprehensive diversity and inclusion website dedicated to building inclusive workplaces and fostering understanding across all communities. The platform provides educational resources, powerful TED talks, and actionable insights to help individuals and organizations create more equitable environments for everyone.

### Mission Statement

"Embracing Diversity & Inclusion - Building a Better Workplace for Everybody"

Our mission is to empower diversity and foster inclusion in every community through education, awareness, and practical resources. We believe that small steps toward a more inclusive world can create lasting change.

### User Experience (UX)

#### User Stories

1. **First Time Visitor Goals**

    - As a first-time visitor, I want to understand the importance of diversity and uniqueness.
    - As a first-time visitor, I want to find resources that support diversity and inclusion.
    - As a first-time visitor, I want to see stories or examples promoting acceptance.

2. **Returning Visitor Goals**

    - As a returning visitor, I want to explore additional resources and tools.
    - As a returning visitor, I want to engage with community content or courses.
    - As a returning visitor, I want clear navigation to find relevant information quickly.

3. **Frequent User Goals**
    - As a frequent user, I want to receive updates on new content.
    - As a frequent user, I want interactive features to engage with uniqueness topics.
    - As a frequent user, I want to connect with like-minded individuals.

### 🎨 Features

#### 🏠 Home Page

-   **Compelling Title**: Large, impactful typography showcasing the diversity and inclusion message
-   **Call-to-Action Button**: Prominent "Learn More" button guiding users to resources
-   **Responsive Design**: Fully optimized for desktop, tablet, and mobile devices
-   **Decorative Elements**: SVG blob graphics for visual appeal (hidden on mobile for clean UX)

#### 📚 Resources Section

-   **Educational Cards**: Three core topics explaining diversity fundamentals:
    -   Understanding Diversity
    -   Inclusive Leadership
    -   Unconscious Bias
-   **Video Library**: Curated TED talks and educational content including:
    -   "The Danger of a Single Story" by Chimamanda Ngozi Adichie
    -   "How Diversity Makes Teams More Innovative"
    -   "Building Inclusive Workplaces"
-   **Interactive Elements**: Hover effects and smooth transitions for engaging user experience

#### 🌐 Navigation & Footer

-   **Modern Navbar**: Fixed, semi-transparent navigation with smooth scrolling
-   **Active States**: Dynamic navigation highlighting based on scroll position
-   **Newsletter Signup**: Email subscription form for staying connected
-   **Quick Links**: Easy access to all major sections
-   **Contact Information**: Direct communication channels

## 🎨 Design Philosophy

### Visual Design

-   **Modern Typography**: Inter font family for clean, professional appearance
-   **Color Scheme**:
    -   Primary: Dark blue (`#2c2c54`) and light blue (`#20d0ec`)
    -   Accent: Purple gradients (`#8b5cf6`) for highlights
    -   Background: Discord-gray (`#212121`) for content sections
-   **Responsive Layout**: Mobile-first approach with Bootstrap 3.3.7 grid system
-   **Gradient Effects**: Linear gradients for buttons and interactive elements
-   **Card-Based Design**: Consistent card layouts for content organization

### Technical Implementation

-   **CSS Variables**: Centralized color management for consistency
-   **Flexbox Layout**: Modern CSS layout for proper alignment
-   **Smooth Animations**: CSS transitions and transform effects
-   **Bootstrap Integration**: Custom styles built on Bootstrap foundation

### Accessibility Features

-   **Responsive Typography**: Scalable text sizes across all devices
-   **High Contrast**: Carefully chosen color combinations for readability
-   **Semantic HTML**: Proper heading hierarchy and ARIA labels
-   **Touch-Friendly**: Large tap targets for mobile interaction
-   **Screen Reader Support**: Alt text and descriptive labels throughout

## 🧪 Testing

### Responsive Design Testing

-   **Desktop**: Tested on Chrome, Firefox, Safari, and Edge
-   **Tablet**: iPad Pro (landscape/portrait), Surface Pro
-   **Mobile**: iPhone 14, Samsung Galaxy S23, various Android devices
-   **Small Screens**: iPhone SE and similar compact devices

### Feature Testing

1. **Navigation**

    - ✅ Smooth scrolling between sections
    - ✅ Active navigation states update on scroll
    - ✅ Mobile hamburger menu functionality
    - ✅ Right-aligned mobile menu positioning

2. **Interactive Elements**

    - ✅ Button hover effects and animations
    - ✅ Card hover transformations
    - ✅ Video embed functionality
    - ✅ Newsletter form submission

3. **Responsive Behavior**
    - ✅ Text scaling across all breakpoints
    - ✅ Image and video responsiveness
    - ✅ Mobile-optimized navigation
    - ✅ Blob graphics hidden on mobile

### Accessibility Testing

-   **Color Contrast**: WCAG AA compliant ratios
-   **Keyboard Navigation**: Full site navigation without mouse
-   **Screen Reader**: Tested with NVDA and VoiceOver
-   **Alt Text**: All images include descriptive alt attributes

## 🔧 Technical Stack

-   **HTML5**: Semantic markup structure
-   **CSS3**: Advanced styling with variables and flexbox
-   **Bootstrap 3.3.7**: Responsive grid framework
-   **JavaScript/jQuery**: Interactive functionality
-   **Font Awesome 5.15.4**: Icon library
-   **Google Fonts**: Inter typography system

## 🚀 Deployment

### Live Site

Visit the deployed website: [Open Together](https://codeinstitute.penguincode.tech/)

### Local Development

To run the project locally:

1. **Clone the repository**

    ```bash
    git clone https://github.com/penguinrust/opentogether-project.git
    cd opentogether-project
    ```

2. **Start a local server**

    ```bash
    # Using Python 3
    python -m http.server 8000

    # Using Python 2
    python -m SimpleHTTPServer 8000

    # Using Node.js
    npx http-server
    ```

3. **Open in browser**
   Navigate to `http://localhost:8000`

### File Structure

```
opentogether-project/
├── index.html              # Main homepage
├── contact.html            # Contact page
├── resources.html          # Resources page
├── README.md              # Project documentation
├── CNAME                  # Domain configuration
└── assets/
    ├── css/
    │   └── style.css      # Main stylesheet
    └── images/
        ├── favicon.ico    # Site icon
        ├── logo.png       # Brand logo
        ├── background.png # Header background
        └── blobs/         # Decorative SVG elements
            ├── blob.svg
            ├── blob2.svg
            └── blob3.svg
```

## ✨ Credits

### Content

-   **TED Talks**: Embedded educational videos from YouTube
-   **Diversity Resources**: Curated content focusing on workplace inclusion
-   **Copy**: Original content promoting diversity and inclusion values

### Media

-   **Icons**: Font Awesome icon library
-   **Typography**: Google Fonts (Inter family)
-   **Graphics**: Custom SVG blob decorations
-   **Videos**: Educational content from TED and diversity experts

### Technical

-   **Framework**: Bootstrap 3.3.7 for responsive design
-   **JavaScript**: jQuery for interactive functionality
-   **CSS**: Modern CSS3 with variables and flexbox
-   **Development**: Built with semantic HTML5 practices

## 🎯 Future Enhancements

### Planned Features

1. **Content Management**: Admin panel for easy content updates
2. **Interactive Elements**: Comment sections and user engagement
3. **Advanced Accessibility**: Voice navigation and screen reader enhancements
4. **Performance**: Image optimization and lazy loading
5. **Analytics**: User behavior tracking and insights

### Technical Improvements

1. **Framework Upgrade**: Migration to Bootstrap 5 or modern CSS Grid
2. **Performance**: Implement service workers for offline functionality
3. **SEO**: Enhanced meta tags and structured data
4. **Security**: Content Security Policy and HTTPS enforcement

---

Made with ❤️ by Scott
