---
name: Portal Humano
colors:
  surface: '#fff7fc'
  surface-dim: '#e1d7e2'
  surface-bright: '#fff7fc'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#fbf0fb'
  surface-container: '#f6eaf6'
  surface-container-high: '#f0e5f0'
  surface-container-highest: '#eadfea'
  on-surface: '#1f1a21'
  on-surface-variant: '#4d4351'
  inverse-surface: '#342e37'
  inverse-on-surface: '#f9edf9'
  outline: '#7f7383'
  outline-variant: '#d0c2d3'
  surface-tint: '#843ab4'
  primary: '#4e0078'
  on-primary: '#ffffff'
  primary-container: '#6a1b9a'
  on-primary-container: '#da9cff'
  inverse-primary: '#e4b5ff'
  secondary: '#a900a7'
  on-secondary: '#ffffff'
  secondary-container: '#fe53f7'
  on-secondary-container: '#630062'
  tertiary: '#725c00'
  on-tertiary: '#ffffff'
  tertiary-container: '#cba820'
  on-tertiary-container: '#4d3e00'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#f4d9ff'
  primary-fixed-dim: '#e4b5ff'
  on-primary-fixed: '#2f004b'
  on-primary-fixed-variant: '#6a1b9a'
  secondary-fixed: '#ffd7f5'
  secondary-fixed-dim: '#ffabf2'
  on-secondary-fixed: '#380037'
  on-secondary-fixed-variant: '#810080'
  tertiary-fixed: '#ffe07e'
  tertiary-fixed-dim: '#e8c33c'
  on-tertiary-fixed: '#231b00'
  on-tertiary-fixed-variant: '#564500'
  background: '#fff7fc'
  on-background: '#1f1a21'
  surface-variant: '#eadfea'
  surface-soft: '#F8F7FA'
  text-main: '#212121'
  text-muted: '#616161'
  border-light: '#E0E0E0'
  primary-light: '#9C4DCC'
  secondary-light: '#FF70FD'
typography:
  display-lg:
    fontFamily: Montserrat
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Montserrat
    fontSize: 36px
    fontWeight: '700'
    lineHeight: 42px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Montserrat
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
  headline-md:
    fontFamily: Montserrat
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 32px
  body-lg:
    fontFamily: Open Sans
    fontSize: 20px
    fontWeight: '400'
    lineHeight: 30px
  body-md:
    fontFamily: Open Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-sm:
    fontFamily: Open Sans
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  accent-quote:
    fontFamily: Caveat
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 34px
  label-bold:
    fontFamily: Open Sans
    fontSize: 14px
    fontWeight: '700'
    lineHeight: 16px
    letterSpacing: 0.05em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  base: 8px
  container-max: 1200px
  gutter: 24px
  margin-mobile: 16px
  section-gap-desktop: 80px
  section-gap-mobile: 48px
---

## Brand & Style

The design system is built upon a **Modern Institutional** style with a deeply **Human and Welcoming** heart. It departs from the rigid, cold aesthetics of traditional political platforms in favor of a **Clean Editorial** approach that emphasizes participation and proximity. 

The visual narrative is "Participatory and Organic," utilizing generous whitespace to allow content to breathe and emotional connections to form. By mixing structured corporate reliability with soft, approachable elements, the interface invites the citizen not just to observe, but to belong. The aesthetic is sophisticated yet accessible, avoiding artificial corporate polish in favor of authentic, community-focused storytelling.

## Colors

The palette is anchored by a deep **Primary Purple**, signifying institutional wisdom and stability. This is balanced by a vibrant **Secondary Magenta** used to inject energy into "participation" elements and emotional highlights. The **Accent Gold** serves as a symbolic high-contrast tool for special calls to action and key accomplishments.

Neutrality is essential for the editorial feel; backgrounds should remain predominantly white or use the very soft `surface-soft` lavender-tinted gray to define content sections without creating hard visual breaks. Text hierarchy relies on high-contrast dark grays rather than pure black to maintain a softer, more modern reading experience.

## Typography

This design system uses a tri-font pairing to manage different psychological layers of the content:
- **Montserrat (Headings):** Provides a geometric, confident, and modern institutional foundation. Use for all primary navigation and titles.
- **Open Sans (Body):** Selected for its high legibility and friendly, neutral tone. It handles all long-form reading and functional labels.
- **Caveat (Emotional Accents):** A distinctive handwritten font used sparingly for slogans, signatures, or "hand-annotated" emotional notes to emphasize the human touch.

**Implementation Note:** Always use Brazilian Portuguese (PT-BR) for UI strings. Maintain generous line-heights for body text to support an editorial, easy-to-read flow.

## Layout & Spacing

The layout follows a **Fluid Grid** model with a maximum container width of 1200px for desktop to maintain optimal line lengths for editorial content. 

### Rhythm
- Use a base-8 spacing scale. 
- **Desktop:** 12-column grid with 24px gutters.
- **Mobile:** Single column with 16px side margins.

### Philosophy
Generous vertical whitespace (section-gaps) is mandatory to prevent the "cluttered" feel common in political sites. Content should feel modular, with distinct sections separated by clear breathing room rather than heavy dividers.

## Elevation & Depth

Hierarchy is achieved through **Tonal Layers** and **Soft Ambient Shadows**. 

- **Surfaces:** Use subtle shifts between white backgrounds and `surface-soft` (light gray/lavender) to group related content.
- **Shadows:** Cards and primary buttons use extremely diffused, low-opacity shadows (e.g., `box-shadow: 0 10px 30px rgba(106, 27, 154, 0.08)`) to create a "lifted" effect without looking heavy.
- **Outlines:** Use low-contrast `border-light` (#E0E0E0) for secondary elements like input fields or secondary cards to maintain the clean, editorial aesthetic.

## Shapes

The shape language is **Organic and Soft**, designed to feel approachable and safe. 

- **Cards:** Use a 20px radius to emphasize the "Welcoming" brand trait.
- **Buttons:** Use a 12px radius for a modern, tactile feel that sits between a standard rectangle and a full pill-shape.
- **Images:** Apply a 16px radius to all photography to align with the soft-component language. 

Avoid sharp 90-degree corners in all primary UI elements to maintain the "Human" personality.

## Components

### Buttons
- **Primary:** Purple background, white text, 12px radius. High contrast.
- **Secondary:** Magenta or Ghost style with Purple border.
- **Interactive:** Subtle 2px lift on hover. Always use clear Portuguese CTAs like "Quero participar" or "Conheça as propostas."

### Cards
- **News & Proposals:** 20px radius, subtle ambient shadow, white background. Use "Image-top" layouts to prioritize the documentary-style photography.
- **Agenda:** Utilize a left-accent border in Magenta to highlight upcoming events.

### Input Fields
- Soft 8px radius, 1px light border. Focus state should use a soft Purple glow.

### Interactive Elements
- **Chips:** Used for "Axes of Care" or categories. Rounded-full (pill) with light Purple/Magenta tints.
- **Navigation:** Clean, centered or right-aligned top bar. Use Montserrat Medium for links to ensure institutional clarity.

### Feedback & Participation
- **Call-to-Action Blocks:** Full-width sections using a Primary Purple gradient to Magenta, featuring "Meta a Colher" (Participatory) messaging.