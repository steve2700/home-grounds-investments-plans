# Home Grounds Investments - Website Structure

```
homegrounds.co.zw/
│
├── 🏠 HOME (/)
│   ├── Hero Section
│   ├── Division Cards (Renovations | Meats)
│   ├── Trust Pillars
│   ├── Featured Services
│   ├── Social Proof
│   ├── Locations Map
│   └── Final CTA
│
├── 🔨 RENOVATIONS (/renovations)
│   │
│   ├── Residential (/renovations/residential)
│   │   ├── Kitchen Renovations
│   │   ├── Bathroom Remodeling
│   │   ├── Full House Renovations
│   │   ├── Extensions & Additions
│   │   └── Interior Design
│   │
│   ├── Commercial (/renovations/commercial)
│   │   ├── Office Fit-Outs
│   │   ├── Retail Renovations
│   │   ├── Restaurant Renovations
│   │   ├── Tenant Installations
│   │   └── Warehouse Refurbishments
│   │
│   ├── Maintenance (/renovations/maintenance)
│   │   ├── General Property Maintenance
│   │   ├── Waterproofing & Damp Proofing
│   │   ├── Structural Repairs
│   │   ├── Electrical & Plumbing
│   │   └── Preventive Maintenance Plans
│   │
│   └── Sustainable Solutions (/renovations/sustainable-solutions)
│       ├── Solar Installations
│       ├── Energy Efficiency Upgrades
│       ├── Smart Home Systems
│       ├── Water-Wise Solutions
│       └── Green Building Materials
│
├── 🥩 MEATS (/meats)
│   │
│   ├── Beef (/meats/beef)
│   │   ├── Premium Cuts Guide
│   │   ├── Grass-Fed & Grain-Fed
│   │   ├── Bulk Orders
│   │   └── Pricing
│   │
│   ├── Pork (/meats/pork)
│   │   ├── Fresh Pork Cuts
│   │   ├── Sausages
│   │   ├── Smoked Products
│   │   └── Bulk Supply
│   │
│   ├── Poultry (/meats/poultry)
│   │   ├── Whole Chickens
│   │   ├── Chicken Portions
│   │   ├── Free-Range Options
│   │   └── Frozen Products
│   │
│   └── Butchery Services (/meats/butchery-services)
│       ├── Custom Cutting
│       ├── Deboning
│       ├── Party Packs
│       ├── Event Catering
│       └── Subscription Boxes
│
├── 📸 PORTFOLIO (/portfolio)
│   ├── All Projects Gallery
│   ├── Renovation Projects
│   ├── Commercial Projects
│   └── Individual Project Pages (/portfolio/[project-slug])
│
├── 📍 LOCATIONS
│   ├── Harare (/locations/harare)
│   ├── Bulawayo (/locations/bulawayo)
│   ├── Masvingo (/locations/masvingo)
│   └── Waterfalls - Head Office (/locations/waterfalls)
│
├── ℹ️ ABOUT (/about)
│   ├── Company Story
│   ├── Our Team
│   ├── Our Values
│   ├── Timeline
│   └── Community Involvement
│
├── 📝 BLOG (/blog)
│   ├── Renovation Tips
│   ├── Meat Preparation Guides
│   ├── Home Maintenance
│   ├── Recipes
│   └── Individual Articles (/blog/[article-slug])
│
├── 💬 CONTACT (/contact)
│   ├── Multi-Location Info
│   ├── Contact Forms
│   ├── Map Embeds
│   └── Operating Hours
│
├── 📋 QUOTE REQUEST (/quote)
│   └── Renovation Quote Form
│
├── 🛒 ORDER MEATS (/order)
│   └── Meat Order Form
│
├── ❓ FAQ (/faq)
│   ├── Renovation FAQs
│   └── Meats FAQs
│
├── 💼 CAREERS (/careers)
│
├── 🔒 PRIVACY POLICY (/privacy)
│
└── 📜 TERMS & CONDITIONS (/terms)
```

---

## URL Structure Examples

### Clean, SEO-Friendly URLs:

✅ **GOOD:**
```
homegrounds.co.zw/renovations
homegrounds.co.zw/renovations/residential
homegrounds.co.zw/renovations/kitchen-renovations
homegrounds.co.zw/meats/beef
homegrounds.co.zw/portfolio/sandton-kitchen-remodel
homegrounds.co.zw/blog/5-kitchen-trends-2026
homegrounds.co.zw/locations/harare
```

❌ **AVOID:**
```
homegrounds.co.zw/services?id=123
homegrounds.co.zw/page.php?cat=renovations
homegrounds.co.zw/index.html
homegrounds.co.zw/products.asp?type=meat
```

---

## Navigation Hierarchy

### Desktop Header:
```
[LOGO]  Renovations ▾ | Meats ▾ | Portfolio | About | Blog | Contact  [Get Quote] [Order Meats]
```

### Renovations Dropdown:
```
Residential
Commercial
Maintenance
Sustainable Solutions
─────────────
View All Services →
```

### Meats Dropdown:
```
Beef
Pork
Poultry
Butchery Services
─────────────
Order Now →
```

### Mobile Menu:
```
☰ [LOGO]                    [CALL] [WHATSAPP]

Expanded:
├─ Home
├─ Renovations
│  ├─ Residential
│  ├─ Commercial
│  ├─ Maintenance
│  └─ Sustainable
├─ Meats
│  ├─ Beef
│  ├─ Pork
│  ├─ Poultry
│  └─ Butchery
├─ Portfolio
├─ About
├─ Blog
├─ Contact
├─ [Get Quote Button]
└─ [Order Meats Button]
```

---

## Footer Structure

```
┌─────────────────────────────────────────────────────────┐
│                                                           │
│  [LOGO]                                                   │
│  Zimbabwe's trusted partner for quality renovations      │
│  and premium farm-to-table meats                         │
│                                                           │
├─────────────┬─────────────┬─────────────┬───────────────┤
│             │             │             │               │
│  RENOVATIONS│  MEATS      │  COMPANY    │  CONTACT      │
│  Residential│  Beef       │  About      │  Head Office  │
│  Commercial │  Pork       │  Portfolio  │  14A, 6th Ave │
│  Maintenance│  Poultry    │  Blog       │  Waterfalls   │
│  Sustainable│  Butchery   │  Careers    │               │
│             │             │  FAQ        │  +263 78 028  │
│             │             │             │  9132         │
│             │             │             │               │
│             │             │             │  📧 info@     │
│             │             │             │  homegrounds  │
│             │             │             │  .co.zw       │
│             │             │             │               │
├─────────────┴─────────────┴─────────────┴───────────────┤
│                                                           │
│  LOCATIONS:  Harare | Bulawayo | Masvingo | Waterfalls   │
│                                                           │
│  [Facebook] [Instagram] [LinkedIn] [YouTube]              │
│                                                           │
│  Newsletter: [email input] [Subscribe]                    │
│                                                           │
├───────────────────────────────────────────────────────────┤
│                                                           │
│  © 2026 Home Grounds Investments. All rights reserved.   │
│  Privacy Policy | Terms & Conditions | Sitemap            │
│                                                           │
└───────────────────────────────────────────────────────────┘
```

---

## Page Templates

### Template 1: Service Page (e.g., /renovations/residential)
```
Hero Image + Title
↓
Service Overview (2-3 paragraphs)
↓
Key Services Grid (4-6 cards)
↓
Process Timeline (4-5 steps)
↓
Portfolio Gallery (6-9 images)
↓
Pricing Information / Quote Calculator
↓
Testimonials (2-3)
↓
FAQ Accordion (5-8 questions)
↓
CTA Section (Get Quote)
```

### Template 2: Product Page (e.g., /meats/beef)
```
Hero Image + Title
↓
Product Description
↓
Product Categories (cuts guide with images)
↓
Pricing Table
↓
Quality Standards Section
↓
Preparation Tips / Recipes
↓
Bulk Order Information
↓
Testimonials
↓
CTA Section (Order Now)
```

### Template 3: Location Page (e.g., /locations/harare)
```
Location Hero
↓
Address & Contact Info
↓
Services Available in This Location
↓
Map Embed
↓
Operating Hours
↓
Local Projects Gallery
↓
Local Team Members
↓
CTA (Schedule Visit)
```
