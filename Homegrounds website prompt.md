# Home Grounds Investments Website - v0.dev Prompt

## 🎯 Project Overview
Build a high-converting, professional dual-division business website for Home Grounds Investments Company in Zimbabwe. This is NOT a typical corporate site - it needs human-centric design that engages visitors emotionally while maintaining professional credibility.

---

## 🎨 Brand Identity & Design Direction

### Color Palette (from logo)
- **Primary Red**: #E31E24 (energy, action, trust)
- **Primary Green**: #8DC63F (growth, sustainability, freshness)
- **Neutral Dark**: #2D2D2D (text, headers)
- **Neutral Light**: #F5F5F5 (backgrounds)
- **White**: #FFFFFF
- **Accent Gray**: #6B7280

### Design Philosophy
**CRITICAL**: Avoid generic AI-generated aesthetics. This must feel:
- **Human & Approachable**: Like talking to a trusted local expert
- **Authentic Zimbabwean**: Use real imagery that reflects Zimbabwe's landscape, architecture, and people
- **Professionally Confident**: Without being cold or corporate
- **Action-Oriented**: Every section should guide toward conversion
- **Visually Rich**: High-quality photography, not stock AI images

---

## 📱 Website Structure & Pages

### 1. Homepage (/)
**Purpose**: Immediately clarify dual business model and build trust

#### Hero Section
- **Full-screen impactful hero** (not generic - think National Geographic style)
- Real photo: Zimbabwe property renovation or quality meat preparation
- **Headline**: "Building Better Homes. Feeding Better Lives."
- **Subheadline**: "Zimbabwe's trusted partner for quality renovations and premium farm-to-table meats across Harare, Bulawayo, and Masvingo"
- **Dual CTA buttons**:
  - "Plan Your Renovation" (Red)
  - "Order Premium Meats" (Green)
- Location indicator: "Serving Harare, Bulawayo, Masvingo & Waterfalls"

#### Two-Division Introduction (Critical Section)
**Layout**: Side-by-side cards with hover effects

**Left Card - Renovations Division**
- Icon/Badge: "Home Grounds Renovations & Improvements"
- Background: Subtle texture, real renovation photo overlay
- Key services listed (3-4 bullet points)
- "Transform Your Space →" CTA
- Visual: Before/after slider thumbnail

**Right Card - Meats Division**
- Icon/Badge: "Home Grounds Meats & Butcher"
- Background: Farm/butcher imagery
- Key products listed (3-4 bullet points)
- "Shop Quality Meats →" CTA
- Visual: Premium cuts display

#### Why Choose Home Grounds (Trust Section)
- **4 trust pillars** in icon + text format:
  1. "Local Expertise Since [Year]" - Zimbabwe flag icon
  2. "Quality Guaranteed" - Shield icon
  3. "Multi-City Service" - Location pins
  4. "Family-Owned Values" - Heart icon

#### Featured Services Carousel
- Rotating showcase of top services from both divisions
- Real project photos
- Pricing transparency where possible
- Quick-inquiry CTAs

#### Social Proof
- Customer testimonials (video testimonials if possible)
- Project gallery grid
- Certifications/partnerships
- "Join 500+ Happy Clients" counter

#### Location Coverage Map
- Interactive map showing Harare, Bulawayo, Masvingo, Waterfalls
- "We Come To You" messaging
- Service area details

#### Final CTA Section
- Dual-path conversion:
  - **Renovations**: "Get Free Consultation"
  - **Meats**: "View Our Products"
- Trust signals: phone number, WhatsApp, operating hours

---

### 2. Renovations Division Pages

#### /renovations (Main Division Page)
- Hero: Real Zimbabwe home renovation
- Service categories grid:
  - Residential Services
  - Commercial Services
  - Maintenance & Repairs
  - Modern Sustainable Solutions
- Portfolio gallery with filters
- Process timeline (5 steps)
- Pricing calculator or quote form
- FAQ accordion

#### /renovations/residential
- Detailed service breakdown
- Room-by-room renovation options
- Style gallery (modern, traditional, sustainable)
- Project case studies
- Material options showcase
- Timeline estimator

#### /renovations/commercial
- Office fit-outs portfolio
- Retail renovations
- Restaurant/hospitality
- Tenant installations
- Compliance expertise
- B2B testimonials

#### /renovations/maintenance
- Preventive maintenance plans
- Emergency services
- Waterproofing expertise
- Electrical & plumbing
- Subscription packages
- Service area map

#### /renovations/sustainable
- Solar installations
- Energy efficiency upgrades
- Smart home systems
- Water-wise solutions
- Green building materials
- ROI calculator

---

### 3. Meats Division Pages

#### /meats (Main Division Page)
- Hero: Farm landscape or premium cuts
- Farm-to-table story
- Product categories:
  - Premium Beef
  - Quality Pork
  - Fresh Poultry
  - Custom Butchery
- "How We Raise Our Animals" section
- Hygiene & quality standards
- Order options (retail/wholesale)

#### /meats/beef
- Beef cuts guide with diagrams
- Grass-fed vs grain-fed info
- Pricing per kg
- Vacuum packing options
- Bulk order calculator
- Recipe suggestions

#### /meats/pork
- Pork cuts guide
- Fresh & smoked products
- Sausage varieties
- Preparation tips
- Wholesale pricing

#### /meats/poultry
- Whole chickens & portions
- Free-range options
- Daily fresh guarantee
- Restaurant supply packages

#### /meats/butchery-services
- Custom cutting
- Deboning services
- Party packs
- Event catering
- Delivery options
- Subscription meat boxes

---

### 4. Essential Pages

#### /about
- Company story (human, authentic)
- Founder/team photos (real people)
- Our values & mission
- Timeline of growth
- Community involvement
- Dual-division synergy explanation

#### /contact
- Multi-location information:
  - **Head Office**: 14A, 6th Avenue Parktown Waterfalls, Zimbabwe
  - **Harare Branch**: [Address]
  - **Bulawayo Branch**: [Address]
  - **Masvingo Branch**: [Address]
- Contact form with division selector
- Phone: +263 78 028 9132
- WhatsApp button
- Email addresses
- Operating hours
- Map embeds for each location

#### /portfolio
- Filterable project gallery
- Before/after comparisons
- Client testimonials per project
- Project details (timeline, budget range, scope)
- Video walkthroughs

#### /blog
- Renovation tips
- Meat preparation guides
- Seasonal recipes
- Home maintenance advice
- Sustainability tips
- Local Zimbabwe content

#### /faq
- Categorized by division
- Searchable
- Video answers where helpful

#### /careers
- Current openings
- Company culture
- Application form

---

## 🛠️ Technical Specifications

### Framework & Technologies
- **Framework**: Next.js 14+ (App Router)
- **Styling**: Tailwind CSS
- **UI Components**: shadcn/ui
- **Forms**: React Hook Form + Zod validation
- **Animations**: Framer Motion (subtle, purposeful)
- **Images**: Next/Image with optimization
- **Icons**: Lucide React
- **Maps**: Google Maps API or Mapbox

### SEO Requirements

#### Meta & Structure
```javascript
// Example for homepage
export const metadata = {
  title: 'Home Grounds Investments | Property Renovations & Premium Meats Zimbabwe',
  description: 'Zimbabwe\'s trusted partner for quality home & commercial renovations, and farm-fresh premium meats. Serving Harare, Bulawayo, Masvingo.',
  keywords: 'zimbabwe renovations, harare home improvement, bulawayo construction, zimbabwe butcher, premium meats zimbabwe',
  openGraph: {
    title: 'Home Grounds Investments Zimbabwe',
    description: 'Quality Renovations & Premium Meats',
    images: ['/og-image.jpg'],
    locale: 'en_ZW',
  },
  alternates: {
    canonical: 'https://homegrounds.co.zw'
  }
}
```

#### URL Structure (Clean & SEO-Friendly)
```
homegrounds.co.zw/
homegrounds.co.zw/renovations
homegrounds.co.zw/renovations/residential
homegrounds.co.zw/renovations/commercial
homegrounds.co.zw/renovations/maintenance
homegrounds.co.zw/renovations/sustainable-solutions
homegrounds.co.zw/meats
homegrounds.co.zw/meats/beef
homegrounds.co.zw/meats/pork
homegrounds.co.zw/meats/poultry
homegrounds.co.zw/meats/butchery-services
homegrounds.co.zw/portfolio
homegrounds.co.zw/portfolio/[project-slug]
homegrounds.co.zw/about
homegrounds.co.zw/contact
homegrounds.co.zw/locations/harare
homegrounds.co.zw/locations/bulawayo
homegrounds.co.zw/locations/masvingo
homegrounds.co.zw/blog
homegrounds.co.zw/blog/[article-slug]
homegrounds.co.zw/quote
homegrounds.co.zw/order
```

#### Sitemap.xml Structure
```xml
<?xml version="1.0" encoding="UTF-8"?>
<urlset xmlns="http://www.sitemaps.org/schemas/sitemap/0.9">
  <url>
    <loc>https://homegrounds.co.zw/</loc>
    <lastmod>2026-01-30</lastmod>
    <changefreq>daily</changefreq>
    <priority>1.0</priority>
  </url>
  <url>
    <loc>https://homegrounds.co.zw/renovations</loc>
    <changefreq>weekly</changefreq>
    <priority>0.9</priority>
  </url>
  <url>
    <loc>https://homegrounds.co.zw/meats</loc>
    <changefreq>weekly</changefreq>
    <priority>0.9</priority>
  </url>
  <!-- Add all pages with appropriate priority -->
</urlset>
```

#### Robots.txt
```
User-agent: *
Allow: /
Disallow: /admin/
Disallow: /api/
Disallow: /_next/
Disallow: /private/

Sitemap: https://homegrounds.co.zw/sitemap.xml
Sitemap: https://homegrounds.co.zw/renovations-sitemap.xml
Sitemap: https://homegrounds.co.zw/meats-sitemap.xml
Sitemap: https://homegrounds.co.zw/blog-sitemap.xml
```

### Performance Requirements
- Lighthouse score: 90+ on all metrics
- First Contentful Paint: < 1.5s
- Largest Contentful Paint: < 2.5s
- Cumulative Layout Shift: < 0.1
- Mobile-first responsive design
- Image lazy loading
- Code splitting
- CDN delivery

### Schema Markup (JSON-LD)
```javascript
// Organization Schema
{
  "@context": "https://schema.org",
  "@type": "Organization",
  "name": "Home Grounds Investments Company",
  "url": "https://homegrounds.co.zw",
  "logo": "https://homegrounds.co.zw/logo.png",
  "description": "Diversified Investments in Construction, Renovations & Premium Meats",
  "address": {
    "@type": "PostalAddress",
    "streetAddress": "14A, 6th Avenue Parktown",
    "addressLocality": "Waterfalls",
    "addressCountry": "ZW"
  },
  "telephone": "+263780289132",
  "hasOfferCatalog": {
    "@type": "OfferCatalog",
    "name": "Renovation Services",
    "itemListElement": [...]
  }
}

// LocalBusiness Schema for each location
// Product Schema for meats
// Service Schema for renovations
```

---

## 🎯 Conversion Optimization

### CTA Strategy
**Primary CTAs** (Red buttons):
- "Get Free Quote"
- "Start Your Project"
- "Call Now: +263 78 028 9132"

**Secondary CTAs** (Green buttons):
- "View Products"
- "Order Meats"
- "Learn More"

**Tertiary CTAs** (Text links):
- "See Our Work"
- "Read More"
- "Browse Portfolio"

### Forms (React Hook Form + Zod)
1. **Quick Quote Form** (Homepage)
   - Division selector (Renovations/Meats)
   - Name, Phone, Location
   - Brief description
   - Preferred contact method

2. **Detailed Renovation Quote**
   - Project type
   - Property type
   - Budget range
   - Timeline
   - File upload (plans/photos)

3. **Meat Order Form**
   - Product selection
   - Quantity
   - Delivery details
   - Order type (one-time/subscription)

### WhatsApp Integration
- Floating WhatsApp button (green, bottom-right)
- Click-to-chat with pre-filled message
- Example: "Hi! I'm interested in [division] services..."

---

## 📸 Image Requirements

### CRITICAL: Authentic Zimbabwe Imagery
**DO NOT USE**:
- Generic stock photos
- AI-generated images
- Western/European architecture
- Generic corporate shots

**USE**:
- Real Zimbabwe properties (Harare suburbs, Bulawayo homes)
- Actual renovation projects
- Zimbabwe farm landscapes
- Local materials (brick, corrugated iron, etc.)
- Zimbabwean people (team, clients)
- Local cattle breeds
- Zimbabwe market scenes
- Genuine workshop/butchery photos

### Image Sources to Consider
- Commission local photographer
- Client project photos (with permission)
- Team captures during work
- Zimbabwe Tourism Authority (licensed)
- Local stock photo sites (Zimbabwe-specific)

### Image Specifications
- Format: WebP with JPEG fallback
- Responsive images: multiple sizes
- Lazy loading below fold
- Alt text: descriptive, keyword-rich
- Hero images: 1920x1080px minimum
- Thumbnails: 600x400px
- Maximum file size: 200KB (compressed)

---

## 🔧 Component Requirements

### Reusable Components
```typescript
// Division Selector Component
<DivisionToggle 
  onSelect={(division) => handleDivisionChange(division)}
  default="renovations"
/>

// Service Card Component
<ServiceCard
  icon={Icon}
  title="Kitchen Renovations"
  description="..."
  price="From $X"
  cta="Learn More"
  href="/renovations/residential#kitchens"
/>

// Before/After Slider
<BeforeAfter
  beforeImage="/project-1-before.jpg"
  afterImage="/project-1-after.jpg"
  alt="Kitchen renovation project"
/>

// Testimonial Component
<Testimonial
  quote="..."
  author="John Doe"
  location="Harare"
  project="Kitchen Renovation"
  rating={5}
  image="/testimonials/john.jpg"
/>

// Location Card
<LocationCard
  city="Harare"
  address="..."
  phone="+263 78 028 9132"
  hours="Mon-Fri: 8AM-5PM"
  mapLink="..."
/>

// Product Card (Meats)
<ProductCard
  name="Premium Beef Sirloin"
  price="$15/kg"
  image="/products/sirloin.jpg"
  availability="In Stock"
  cta="Order Now"
/>
```

### Navigation Structure
```typescript
// Main Navigation
const navigation = {
  main: [
    {
      name: 'Renovations',
      href: '/renovations',
      submenu: [
        { name: 'Residential', href: '/renovations/residential' },
        { name: 'Commercial', href: '/renovations/commercial' },
        { name: 'Maintenance', href: '/renovations/maintenance' },
        { name: 'Sustainable Solutions', href: '/renovations/sustainable-solutions' }
      ]
    },
    {
      name: 'Meats',
      href: '/meats',
      submenu: [
        { name: 'Beef', href: '/meats/beef' },
        { name: 'Pork', href: '/meats/pork' },
        { name: 'Poultry', href: '/meats/poultry' },
        { name: 'Butchery Services', href: '/meats/butchery-services' }
      ]
    },
    { name: 'Portfolio', href: '/portfolio' },
    { name: 'About', href: '/about' },
    { name: 'Blog', href: '/blog' },
    { name: 'Contact', href: '/contact' }
  ],
  cta: [
    { name: 'Get Quote', href: '/quote', style: 'red' },
    { name: 'Order Meats', href: '/order', style: 'green' }
  ]
}
```

---

## 🎨 Design System

### Typography
```css
/* Headings */
h1: font-size: 3.5rem (mobile: 2.5rem), font-weight: 800, line-height: 1.2
h2: font-size: 2.5rem (mobile: 2rem), font-weight: 700, line-height: 1.3
h3: font-size: 1.875rem (mobile: 1.5rem), font-weight: 600, line-height: 1.4

/* Body */
body: font-size: 1rem, font-weight: 400, line-height: 1.6
large: font-size: 1.125rem, font-weight: 400, line-height: 1.7

/* Font Family */
Primary: 'Inter', -apple-system, sans-serif
Display: 'Poppins', sans-serif (for headings)
```

### Spacing System (Tailwind)
```
xs: 0.25rem (4px)
sm: 0.5rem (8px)
md: 1rem (16px)
lg: 1.5rem (24px)
xl: 2rem (32px)
2xl: 3rem (48px)
3xl: 4rem (64px)
4xl: 6rem (96px)
```

### Button Styles
```typescript
// Primary Button (Red)
className="bg-red-600 hover:bg-red-700 text-white px-6 py-3 rounded-md font-semibold transition-all duration-200 shadow-lg hover:shadow-xl"

// Secondary Button (Green)
className="bg-green-500 hover:bg-green-600 text-white px-6 py-3 rounded-md font-semibold transition-all duration-200 shadow-lg hover:shadow-xl"

// Outline Button
className="border-2 border-gray-800 text-gray-800 hover:bg-gray-800 hover:text-white px-6 py-3 rounded-md font-semibold transition-all duration-200"
```

### Card Styles
```css
.card {
  @apply bg-white rounded-lg shadow-md hover:shadow-xl transition-shadow duration-300 overflow-hidden;
}

.card-image {
  @apply w-full h-64 object-cover;
}

.card-content {
  @apply p-6;
}
```

---

## 📱 Mobile Optimization

### Mobile-Specific Features
- Sticky CTA bar at bottom
- Click-to-call buttons
- WhatsApp integration
- Swipeable galleries
- Hamburger menu with smooth animation
- Touch-friendly tap targets (min 44x44px)
- Optimized forms (one column, large inputs)

### Breakpoints
```javascript
screens: {
  'xs': '475px',
  'sm': '640px',
  'md': '768px',
  'lg': '1024px',
  'xl': '1280px',
  '2xl': '1536px',
}
```

---

## 🔍 SEO Content Strategy

### Page-Specific Keywords

**Homepage**:
- Primary: "home renovations zimbabwe", "premium meats zimbabwe"
- Secondary: "harare construction", "bulawayo renovations", "zimbabwe butcher"
- Long-tail: "best renovation company harare", "farm fresh meat zimbabwe"

**Renovations Pages**:
- "kitchen renovation harare"
- "commercial fit outs bulawayo"
- "home maintenance zimbabwe"
- "sustainable building zimbabwe"

**Meats Pages**:
- "premium beef zimbabwe"
- "farm fresh poultry harare"
- "wholesale meat supplier zimbabwe"
- "custom butchery services"

### Content Guidelines
- 800-1200 words per main page
- Natural keyword integration (avoid stuffing)
- Include location-specific content
- Use headers (H2, H3) for structure
- Internal linking strategy
- Regular blog updates (weekly)

### Local SEO
- Google Business Profile optimization
- Location pages for each city
- Local schema markup
- Zimbabwe-specific content
- Local backlink building
- Customer reviews integration

---

## 🚀 Launch Checklist

### Pre-Launch
- [ ] All pages responsive (test on real devices)
- [ ] Forms working and submitting correctly
- [ ] SEO meta tags on all pages
- [ ] Sitemap generated and submitted
- [ ] Robots.txt configured
- [ ] Google Analytics integrated
- [ ] Google Search Console setup
- [ ] Social media OG tags tested
- [ ] Performance: Lighthouse score 90+
- [ ] All images optimized (WebP)
- [ ] Broken link check
- [ ] Browser compatibility (Chrome, Safari, Firefox, Edge)
- [ ] Contact forms email notifications working
- [ ] WhatsApp links functioning
- [ ] Phone click-to-call working
- [ ] Schema markup validated
- [ ] 404 page designed
- [ ] Loading states for all forms
- [ ] Error handling implemented

### Post-Launch
- [ ] Submit sitemap to Google Search Console
- [ ] Set up Google My Business for all locations
- [ ] Monitor Core Web Vitals
- [ ] Set up uptime monitoring
- [ ] Configure CDN
- [ ] SSL certificate active
- [ ] Set up email marketing integration
- [ ] Implement conversion tracking
- [ ] A/B testing setup

---

## 💬 Tone & Copywriting Guidelines

### Brand Voice
- **Professional but Warm**: Like a knowledgeable family friend
- **Confident without Arrogance**: "We deliver quality" not "We're the best"
- **Action-Oriented**: Use active verbs, create urgency
- **Locally Grounded**: Zimbabwe references, local context
- **Honest & Transparent**: Clear pricing, no hidden agendas

### Examples

**Good**:
- "Transform your Harare home with renovations that last"
- "Farm-fresh meats, delivered to your Bulawayo doorstep"
- "Quality workmanship, Zimbabwe values"

**Avoid**:
- "We're the #1 renovation company" (unsubstantiated claims)
- "Revolutionary solutions" (buzzwords)
- Generic corporate speak
- Over-promising

---

## 🎯 Final v0.dev Prompt

**Use this exact prompt in v0.dev:**

```
Create a modern, high-converting dual-division business website for Home Grounds Investments Company in Zimbabwe using Next.js 14, Tailwind CSS, and shadcn/ui.

BRAND COLORS (from logo):
- Primary Red: #E31E24
- Primary Green: #8DC63F
- Dark: #2D2D2D
- Light: #F5F5F5

CRITICAL DESIGN REQUIREMENTS:
- Avoid generic AI/stock aesthetics - design must feel human and authentic
- Use placeholder images that suggest Zimbabwe architecture, farms, and local context
- Professional but warm tone - not corporate or cold
- Mobile-first responsive design
- High conversion focus with clear dual CTAs throughout

HOMEPAGE STRUCTURE:

1. HERO SECTION:
- Full-screen impactful hero with real photography feel
- Headline: "Building Better Homes. Feeding Better Lives."
- Subheadline: "Zimbabwe's trusted partner for quality renovations and premium farm-to-table meats"
- Two prominent CTA buttons: "Plan Your Renovation" (red) and "Order Premium Meats" (green)
- Location badge: "Serving Harare, Bulawayo, Masvingo"

2. DUAL DIVISION CARDS:
- Side-by-side hover cards introducing:
  LEFT: "Home Grounds Renovations & Improvements" - residential/commercial services
  RIGHT: "Home Grounds Meats & Butcher" - beef, pork, poultry
- Each card: icon, 3-4 service highlights, CTA button, background imagery
- Use subtle animations on hover

3. TRUST SECTION:
- 4 trust pillars with icons:
  - "Local Expertise" | "Quality Guaranteed" | "Multi-City Service" | "Family Values"
- Clean grid layout

4. FEATURED SERVICES:
- Carousel showcasing top services from both divisions
- Service cards with: image, title, brief description, "Learn More" link

5. SOCIAL PROOF:
- Testimonial section with customer quotes
- Project gallery grid (6-8 images)
- Counter: "500+ Happy Clients"

6. LOCATION MAP:
- Visual representation showing service areas
- "We Come To You" messaging

7. FINAL CTA:
- Dual conversion section
- Contact info: +263 78 028 9132
- Operating hours display

NAVIGATION:
- Logo left, menu center, CTAs right
- Dropdown menus for Renovations and Meats divisions
- Mobile: hamburger menu
- Sticky header on scroll

FOOTER:
- 4 columns: About, Services, Quick Links, Contact
- Address: 14A, 6th Avenue Parktown Waterfalls, Zimbabwe
- Social media icons
- Newsletter signup
- Copyright info

TECHNICAL:
- Use Next.js App Router
- TypeScript
- Responsive breakpoints: mobile (< 768px), tablet (768-1024px), desktop (> 1024px)
- Framer Motion for subtle animations
- React Hook Form for contact forms
- Lucide React icons
- Accessibility compliant (WCAG 2.1 AA)
- SEO meta tags
- Performance optimized

Create the complete homepage with clean, professional code. Focus on conversion, authenticity, and user experience. No generic AI design patterns - make it feel human and trustworthy.
```

---

## 📋 Additional Implementation Notes

### Phase 1: Core Pages (Week 1-2)
- Homepage
- Renovations main page
- Meats main page
- Contact page
- About page

### Phase 2: Service Pages (Week 3-4)
- All renovation sub-pages
- All meats sub-pages
- Portfolio section
- Location pages

### Phase 3: Content & SEO (Week 5-6)
- Content population
- SEO optimization
- Schema markup
- Sitemap generation

### Phase 4: Testing & Launch (Week 7-8)
- Comprehensive testing
- Performance optimization
- Form testing
- Analytics setup
- Soft launch
- Full launch

---

## 🎬 Success Metrics

### Track These KPIs:
1. **Traffic**: Organic sessions, page views
2. **Engagement**: Bounce rate, time on site, pages per session
3. **Conversions**:
   - Quote form submissions
   - Order form submissions
   - Phone calls (click-to-call)
   - WhatsApp messages
4. **SEO**: Keyword rankings, organic visibility
5. **Technical**: Page speed, Core Web Vitals, uptime

### Goals (First 3 Months):
- 1,000+ monthly visitors
- 50+ quote requests
- 30+ meat orders
- 60-second average time on site
- <3% bounce rate on homepage

---

**END OF PROMPT DOCUMENT**
