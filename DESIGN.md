---
name: Mediterranean Architectural Excellence
colors:
  surface: '#fbf9f8'
  surface-dim: '#dbd9d9'
  surface-bright: '#fbf9f8'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f5f3f3'
  surface-container: '#efeded'
  surface-container-high: '#eae8e7'
  surface-container-highest: '#e4e2e2'
  on-surface: '#1b1c1c'
  on-surface-variant: '#404751'
  inverse-surface: '#303030'
  inverse-on-surface: '#f2f0f0'
  outline: '#707882'
  outline-variant: '#c0c7d2'
  surface-tint: '#00629e'
  primary: '#005e97'
  on-primary: '#ffffff'
  primary-container: '#0077be'
  on-primary-container: '#f7f9ff'
  inverse-primary: '#9acbff'
  secondary: '#735a3a'
  on-secondary: '#ffffff'
  secondary-container: '#fddab2'
  on-secondary-container: '#785e3e'
  tertiary: '#595a57'
  on-tertiary: '#ffffff'
  tertiary-container: '#71736f'
  on-tertiary-container: '#f9f9f4'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#cfe5ff'
  primary-fixed-dim: '#9acbff'
  on-primary-fixed: '#001d34'
  on-primary-fixed-variant: '#004a79'
  secondary-fixed: '#ffddb6'
  secondary-fixed-dim: '#e2c19b'
  on-secondary-fixed: '#291801'
  on-secondary-fixed-variant: '#594325'
  tertiary-fixed: '#e3e3de'
  tertiary-fixed-dim: '#c6c7c2'
  on-tertiary-fixed: '#1a1c19'
  on-tertiary-fixed-variant: '#454744'
  background: '#fbf9f8'
  on-background: '#1b1c1c'
  surface-variant: '#e4e2e2'
typography:
  display-lg:
    fontFamily: Bodoni Moda
    fontSize: 64px
    fontWeight: '700'
    lineHeight: 72px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Bodoni Moda
    fontSize: 40px
    fontWeight: '700'
    lineHeight: 48px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Bodoni Moda
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
  headline-sm:
    fontFamily: Bodoni Moda
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  body-lg:
    fontFamily: Open Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Open Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-md:
    fontFamily: Open Sans
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.05em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  container-max: 1280px
  gutter: 24px
  margin-desktop: 80px
  margin-mobile: 20px
  stack-sm: 8px
  stack-md: 16px
  stack-lg: 32px
  section-gap: 120px
---

## Brand & Style

The design system is engineered to evoke "Modern Mediterranean Luxury"—a blend of high-end construction precision and the warm, inviting atmosphere of a Balearic estate. The target audience includes homeowners seeking premium renovations in Mallorca, valuing both professional reliability and aesthetic harmony.

The visual style is **Corporate / Modern** with a **Tactile** edge. It utilizes generous whitespace to signify premium service, while incorporating natural textures and soft shadows to prevent the UI from feeling sterile. The aesthetic balances the "hard" reality of construction with the "soft" dream of a Mediterranean home.

## Colors

The palette is anchored by **Mediterranean Blue (#0077BE)**, used strategically for trust-building elements and key navigation. The **Secondary Wood (#A68966)** acts as a sophisticated counter-point, bringing a warm, organic feel to the professional blue. 

- **Primary**: Used for branding, icons, and primary interaction states.
- **Secondary**: A warm, sand/wood-inspired tone for accents and secondary UI elements.
- **Success**: A deep, forest-inspired green specifically reserved for high-conversion Call to Actions (CTAs) to signify "Go" and "Completion."
- **Neutral/Surface**: Soft greys and off-whites (Warm White #F5F5F0) replace harsh pure whites to mimic the limestone and natural light of Mallorca.

## Typography

This design system uses a hierarchical scale that prioritizes clarity and a sense of architectural structure, now enhanced with an elegant serif for high-level headings.

- **Headings (Bodoni Moda)**: A sophisticated serif font that reflects high-end Mediterranean elegance and editorial polish. Set with tighter letter spacing in larger formats. Use Bold (700) for hero sections and Semi-Bold (600) for section titles.
- **Body (Open Sans)**: Chosen for its exceptional readability in long-form copy describing services and materials. 
- **Labels**: Always set in Open Sans with a slight tracking increase and uppercase styling to denote metadata or small category tags.

## Layout & Spacing

The layout follows a **Fixed Grid** philosophy on desktop to maintain a premium, editorial feel. 

- **Desktop**: 12-column grid with a 1280px max-width.
- **Sectioning**: Large vertical gaps (120px) are used between major content blocks to allow the high-quality photography of renovations to "breathe."
- **Padding**: Elements within cards or containers should use a standard 32px padding to maintain the "Generous Whitespace" requirement.
- **Reflow**: On mobile, the 12-column grid collapses to a single column with 20px side margins.

## Elevation & Depth

Depth is conveyed through **Ambient Shadows** and **Tonal Layers**. This system avoids heavy borders in favor of subtle elevation that suggests physical layers of materials.

- **Low Elevation**: Used for cards and input fields. A soft shadow with a 12px blur and 5% opacity using a blue-tinted neutral color to keep the shadows "cool" and clean.
- **High Elevation**: Reserved for floating navigation bars or modal pop-ups. 24px blur with 10% opacity.
- **Interactive Depth**: On hover, cards should transition from Low Elevation to a slightly more pronounced shadow with a subtle 2px upward shift to simulate "picking up" the element.

## Shapes

The shape language is consistently **Rounded**. 

- **Standard Radius**: 8px (0.5rem) is applied to all primary buttons, cards, and input fields.
- **Large Radius**: 16px (1rem) is used for large image containers or decorative background elements to soften the geometric nature of construction imagery.
- **Icons**: Should feature rounded terminals and joinery to match the UI's softness.

## Components

### Buttons
- **Primary**: Mediterranean Blue background, white text, 8px radius.
- **CTA (Success)**: Forest Green background, used only for "Request a Quote" or "Book Consultation."
- **Secondary**: Transparent background with a 2px Primary Blue or Secondary Wood border.

### Cards
- White surface, 8px radius, subtle shadow. 
- Use for "Service" descriptions and "Portfolio" highlights. 
- Images within cards should have their top corners rounded to 8px to match the container.

### Input Fields
- Soft Grey (#F5F5F0) fill with a 1px border that turns Primary Blue on focus.
- Labels sit above the field in Label-MD typography.

### Lists & Chips
- **Checklists**: Use the Mediterranean Blue for checkmark icons to denote completed projects or included services.
- **Tags**: Small, 4px rounded chips in Secondary Wood with white text for identifying renovation types (e.g., "Kitchen," "Pool," "Interior").

### Navigation
- A "sticky" top bar with a backdrop-blur (glassmorphism effect) to maintain a modern, high-end feel as the user scrolls through the portfolio.