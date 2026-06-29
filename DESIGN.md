---
name: Verdo Vitality
colors:
  surface: '#fbf9f5'
  surface-dim: '#dbdad6'
  surface-bright: '#fbf9f5'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f5f3ef'
  surface-container: '#efeeea'
  surface-container-high: '#eae8e4'
  surface-container-highest: '#e4e2de'
  on-surface: '#1b1c1a'
  on-surface-variant: '#3f4a3c'
  inverse-surface: '#30312e'
  inverse-on-surface: '#f2f0ed'
  outline: '#6f7a6b'
  outline-variant: '#becab9'
  surface-tint: '#006e1c'
  primary: '#006e1c'
  on-primary: '#ffffff'
  primary-container: '#4caf50'
  on-primary-container: '#003c0b'
  inverse-primary: '#78dc77'
  secondary: '#4f625e'
  on-secondary: '#ffffff'
  secondary-container: '#d2e7e1'
  on-secondary-container: '#556864'
  tertiary: '#bc004b'
  on-tertiary: '#ffffff'
  tertiary-container: '#ff678a'
  on-tertiary-container: '#6b0027'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#94f990'
  primary-fixed-dim: '#78dc77'
  on-primary-fixed: '#002204'
  on-primary-fixed-variant: '#005313'
  secondary-fixed: '#d2e7e1'
  secondary-fixed-dim: '#b6cbc5'
  on-secondary-fixed: '#0c1f1b'
  on-secondary-fixed-variant: '#384a46'
  tertiary-fixed: '#ffd9de'
  tertiary-fixed-dim: '#ffb2be'
  on-tertiary-fixed: '#400014'
  on-tertiary-fixed-variant: '#900038'
  background: '#fbf9f5'
  on-background: '#1b1c1a'
  surface-variant: '#e4e2de'
typography:
  display-lg:
    fontFamily: Public Sans
    fontSize: 64px
    fontWeight: '800'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Public Sans
    fontSize: 40px
    fontWeight: '800'
    lineHeight: '1.15'
    letterSpacing: -0.01em
  headline-xl:
    fontFamily: Public Sans
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.01em
  headline-lg:
    fontFamily: Public Sans
    fontSize: 32px
    fontWeight: '700'
    lineHeight: '1.25'
  body-lg:
    fontFamily: Public Sans
    fontSize: 20px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Public Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-md:
    fontFamily: Public Sans
    fontSize: 14px
    fontWeight: '600'
    lineHeight: '1.4'
    letterSpacing: 0.05em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  unit: 8px
  section-gap: 120px
  container-max: 1280px
  gutter: 24px
  margin-mobile: 20px
  margin-desktop: 64px
---

## Brand & Style
The design system embodies a "High-End Farmers Market" aesthetic—merging the tactile freshness of organic produce with the precision of premium editorial design. The personality is optimistic and light, steering away from heavy agricultural grit or sterile corporate layouts. 

The visual style is **Soft Minimalism** with an **Editorial** edge. It prioritizes clarity through immense whitespace (breathing room), rhythmic typography, and organic layering. The interface should feel like a summer breeze: clean, natural, and inviting. Key visual drivers include fluid transitions, soft-focus photography of produce, and a rejection of pure black in favor of deep vegetal greens for text to maintain a natural warmth.

## Colors
This design system utilizes a palette inspired by a sun-drenched garden. 
- **Primary Canvas:** Use `Pure White` for the main background to ensure a crisp, clean feel. Use `Warm White` (#FDFBF7) for section blocks to create subtle, sophisticated contrast.
- **The Greens:** `Leaf Green` is the primary action color. `Cucumber Green` (#2E7D32) replaces traditional black for all primary text and headlines to keep the tone "organic."
- **Fresh Accents:** `Fresh Mint` and `Soft Sage` are used for secondary backgrounds and tonal UI elements.
- **Vibrancy:** `Cherry Red` is used sparingly for highlights, sales tags, or heart icons, mimicking the pop of a ripe tomato or radish. 
- **Soft Pastels:** `Lavender`, `Beige`, and `Sky Blue` serve as background tints for product categorization, ensuring a varied but cohesive snackable vegetable catalog.

## Typography
The system uses **Public Sans** to achieve a friendly, institutional-grade clarity that feels modern and accessible. 

- **Hierarchy:** Use extreme scale differences. Large `Display` sizes should be set with tight tracking to create a "magazine cover" feel.
- **Editorial Body:** Body text is generous in size (`20px` for primary reading) with an open line height to ensure a relaxed, premium reading experience.
- **Color Application:** Never use #000000. Headlines should use `Cucumber Green` (#2E7D32) and body text should use a slightly desaturated version of the same for better legibility and softness.

## Elevation & Depth
Depth in this design system is achieved through **Organic Layering** and **Ambient Shadows** rather than stark borders.

- **Soft Depth:** Use extremely diffused, low-opacity shadows (e.g., `box-shadow: 0 10px 40px rgba(46, 125, 50, 0.05)`) tinted with a hint of green. Shadows should look like natural light hitting a matte surface.
- **Tonal Stacking:** Use color to define depth. A `Warm White` card sitting on a `Pure White` background provides a subtle distinction without the need for heavy outlines.
- **Glassmorphism:** For navigation bars or floating "Add to Cart" buttons, use a high-blur backdrop filter (30px+) on a semi-transparent `Fresh Mint` or `White` base to maintain the airy summer vibe.

## Shapes
The shape language is **Warmly Rounded**. There are no sharp corners in the UI, mirroring the organic forms of fresh produce.

- **Base Radius:** Elements like buttons and input fields use a `0.5rem` (8px) radius.
- **Container Radius:** Product cards and editorial modules use `1.5rem` (24px) for a soft, friendly presence.
- **Media:** Product photography should either be isolated (no background) or clipped with large, soft-radius shapes.

## Components
- **Buttons:** Use "Pill" shapes for primary actions. The primary button is `Leaf Green` with white text. Secondary buttons use a `Fresh Mint` ghost style with `Cucumber Green` text.
- **Cards:** Use `Warm White` backgrounds with subtle ambient shadows. Avoid borders. Content within cards should have a minimum of 32px padding.
- **Chips:** Used for vegetable attributes (e.g., "Crunchy," "Organic," "Sweet"). These should be small, fully rounded, and use light pastel backgrounds matching the produce type (e.g., `Soft Lavender` for eggplant-related items).
- **Input Fields:** Soft beige backgrounds (`#F5F5DC`) with no border until focused. On focus, a soft `Leaf Green` glow is applied.
- **Iconography:** Use 2px stroke-width rounded icons. Icons should be "open" and never filled, maintaining the light, airy aesthetic of the brand.
- **Lists:** Use custom icons (like a small green leaf or dot) instead of standard bullets, with generous vertical spacing (16px) between items.