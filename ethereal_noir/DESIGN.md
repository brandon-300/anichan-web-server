---
name: Ethereal Noir
colors:
  surface: '#131315'
  surface-dim: '#131315'
  surface-bright: '#39393b'
  surface-container-lowest: '#0e0e10'
  surface-container-low: '#1c1b1d'
  surface-container: '#201f21'
  surface-container-high: '#2a2a2c'
  surface-container-highest: '#353437'
  on-surface: '#e5e1e4'
  on-surface-variant: '#cfc2d6'
  inverse-surface: '#e5e1e4'
  inverse-on-surface: '#313032'
  outline: '#988d9f'
  outline-variant: '#4d4354'
  surface-tint: '#ddb7ff'
  primary: '#ddb7ff'
  on-primary: '#490080'
  primary-container: '#b76dff'
  on-primary-container: '#400071'
  inverse-primary: '#842bd2'
  secondary: '#5de6ff'
  on-secondary: '#00363e'
  secondary-container: '#00cbe6'
  on-secondary-container: '#00515d'
  tertiary: '#c8c5cb'
  on-tertiary: '#303034'
  tertiary-container: '#929095'
  on-tertiary-container: '#2a292e'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#f0dbff'
  primary-fixed-dim: '#ddb7ff'
  on-primary-fixed: '#2c0051'
  on-primary-fixed-variant: '#6900b3'
  secondary-fixed: '#a2eeff'
  secondary-fixed-dim: '#2fd9f4'
  on-secondary-fixed: '#001f25'
  on-secondary-fixed-variant: '#004e5a'
  tertiary-fixed: '#e4e1e7'
  tertiary-fixed-dim: '#c8c5cb'
  on-tertiary-fixed: '#1b1b1f'
  on-tertiary-fixed-variant: '#47464b'
  background: '#131315'
  on-background: '#e5e1e4'
  surface-variant: '#353437'
typography:
  headline-xl:
    fontFamily: Lexend
    fontSize: 48px
    fontWeight: '800'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Lexend
    fontSize: 32px
    fontWeight: '700'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: Lexend
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 32px
  headline-md:
    fontFamily: Lexend
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: 20px
    letterSpacing: 0.05em
  caption:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '500'
    lineHeight: 16px
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  base: 8px
  container-max: 1280px
  gutter: 24px
  margin-mobile: 16px
  margin-desktop: 40px
---

## Brand & Style
The design system is a premium, high-fidelity framework tailored for a sophisticated anime social ecosystem. It balances the depth of a dark-mode interface with the high-energy vibrancy of cyber-anime aesthetics. The personality is "Nocturnal & Electric"—merging the mystery of midnight tones with the sharp, neon clarity of electric purple and cyan.

The style is a refined **Glassmorphic-Modern** hybrid. It utilizes translucent layers to create a sense of verticality and immersion, while maintaining a clean, minimalist structure that prevents the "otaku" aesthetic from feeling cluttered. The goal is to evoke a premium, exclusive atmosphere that feels like a high-end digital lounge for creators and enthusiasts.

## Colors
The palette is built on a "Deep Space" foundation. The primary surfaces use a custom charcoal (#0a0a0c) and midnight navy (#121216) to ensure true black levels on OLED screens while maintaining enough gray-scale for depth.

- **Primary (Electric Purple):** Used for primary actions, active states, and brand-critical highlights.
- **Secondary (Neon Cyan):** Reserved for technical accents, status indicators, and secondary call-to-actions.
- **Accent Glows:** Both primary and secondary colors should be used as low-opacity glows (10-15%) behind glass containers to simulate environmental lighting.
- **Surface Tiers:** Background is #0a0a0c. Cards and navigation bars use #121216 with varying levels of transparency (80-90%) when positioned over background elements.

## Typography
This design system utilizes **Lexend** for headlines to provide a modern, wide, and slightly futuristic character that feels grounded yet distinct. **Inter** is used for all body text and UI labels to ensure maximum legibility within the dark interface, where light-on-dark text can often suffer from "haloing."

Headlines should be set with tight letter-spacing to emphasize the bold, geometric nature of the font. For labels, a slight increase in letter-spacing and uppercase styling is recommended to differentiate interactive elements from static content.

## Layout & Spacing
The design system follows a **Fluid-Fixed hybrid** layout. On mobile, the system relies on a single-column layout with 16px margins. On desktop, content is centered within a 1280px container using a 12-column grid.

Spacing follows an 8px rhythmic scale. Generous whitespace is a core requirement to maintain the "premium" feel. Use "Airy" padding (32px+) for card containers and section headers to allow the glassmorphic effects and background glows room to breathe. Components should be grouped using 8px or 16px gaps, while major sections should be separated by 64px or 80px.

## Elevation & Depth
Depth is achieved through **Glassmorphism and Tonal Layering**. 

1.  **Base Layer:** Solid #0a0a0c.
2.  **Mid Layer (Cards/Panels):** #121216 at 85% opacity with a `backdrop-filter: blur(12px)`. These elements feature a subtle 1px border using a semi-transparent white (10% opacity) or a faint purple gradient.
3.  **Top Layer (Modals/Dropdowns):** Increased transparency (70%) with a stronger blur (24px) and a subtle outer glow using the primary color at 5% opacity.

Avoid traditional drop shadows. Instead, use "Environmental Glows"—soft, diffused box-shadows that match the hue of the element (e.g., a purple button has a soft purple glow) to simulate neon light reflecting off a dark surface.

## Shapes
The shape language is characterized by **Generous Rounding**. A base radius of 16px (`0.5rem` based on the internal scale) is applied to standard cards and containers. This softness offsets the aggressive "dark/neon" color palette, making the app feel more approachable and modern.

Interactive elements like buttons and search bars should utilize a higher degree of roundedness (32px or full pill-shape) to distinguish them from structural layout components.

## Components

### Buttons
Primary buttons use a linear gradient from Electric Purple to a slightly deeper violet. They feature a `15px` blur glow on hover. Text is white and bold. Secondary buttons use a ghost style with a Neon Cyan border and 0% fill, transitioning to 10% fill on hover.

### Cards
Cards are the centerpiece of the experience. They must have a 1px border that is top-weighted (brighter at the top, fading at the bottom) to simulate overhead lighting. Content within cards should follow a 24px internal padding rule.

### Input Fields
Inputs are dark-filled (#0a0a0c) with a subtle 1px border. Upon focus, the border glows Neon Cyan and the label shifts upward. The cursor should be styled as a Neon Cyan block to enhance the "technical" anime feel.

### Navigation
The navigation bar is a floating glass element with a `backdrop-filter`. It should occupy the bottom on mobile (thumb-friendly) and the top on desktop. Active links are indicated by a small Neon Cyan dot underneath the icon rather than a full background change.

### Chips & Tags
Used for genre tags or status. These are small, pill-shaped elements with a semi-transparent purple background and high-contrast white text.
