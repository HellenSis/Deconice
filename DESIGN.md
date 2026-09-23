---
name: Deco Nice Boutique
colors:
  surface: '#fff8f7'
  surface-dim: '#ffcece'
  surface-bright: '#fff8f7'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#fff0f0'
  surface-container: '#ffe9e8'
  surface-container-high: '#ffe1e1'
  surface-container-highest: '#ffdad9'
  on-surface: '#301314'
  on-surface-variant: '#514344'
  inverse-surface: '#492728'
  inverse-on-surface: '#ffedec'
  outline: '#837374'
  outline-variant: '#d5c2c2'
  surface-tint: '#7f5257'
  primary: '#7f5257'
  on-primary: '#ffffff'
  primary-container: '#c58f95'
  on-primary-container: '#50292f'
  inverse-primary: '#f2b8be'
  secondary: '#72585a'
  on-secondary: '#ffffff'
  secondary-container: '#fedadc'
  on-secondary-container: '#785e60'
  tertiary: '#615e59'
  on-tertiary: '#ffffff'
  tertiary-container: '#a29d97'
  on-tertiary-container: '#373530'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffd9dc'
  primary-fixed-dim: '#f2b8be'
  on-primary-fixed: '#321116'
  on-primary-fixed-variant: '#653b40'
  secondary-fixed: '#fedadc'
  secondary-fixed-dim: '#e0bec0'
  on-secondary-fixed: '#291618'
  on-secondary-fixed-variant: '#594142'
  tertiary-fixed: '#e7e2db'
  tertiary-fixed-dim: '#cbc6bf'
  on-tertiary-fixed: '#1d1b17'
  on-tertiary-fixed-variant: '#494641'
  background: '#fff8f7'
  on-background: '#301314'
  surface-variant: '#ffdad9'
typography:
  display-lg:
    fontFamily: Bodoni Moda
    fontSize: 64px
    fontWeight: '600'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Bodoni Moda
    fontSize: 48px
    fontWeight: '500'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Bodoni Moda
    fontSize: 32px
    fontWeight: '500'
    lineHeight: '1.3'
  headline-sm:
    fontFamily: Bodoni Moda
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.4'
  body-lg:
    fontFamily: Libre Franklin
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Libre Franklin
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-caps:
    fontFamily: Metrophobic
    fontSize: 12px
    fontWeight: '400'
    lineHeight: '1.2'
    letterSpacing: 0.15em
  nav-item:
    fontFamily: Metrophobic
    fontSize: 14px
    fontWeight: '500'
    lineHeight: '1.2'
    letterSpacing: 0.1em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  margin-edge: 2rem
  gutter-grid: 1.5rem
  stack-xl: 5rem
  stack-lg: 3rem
  stack-md: 1.5rem
  stack-sm: 0.75rem
---

## Brand & Style

The design system is rooted in **Maximalist Elegance**, a style that marries the eccentric, pattern-heavy heritage of high-end interior design with a refined, modern digital sensibility. It evokes the feeling of a sun-drenched atelier, where residential luxury meets editorial precision.

The visual language is defined by a "Residential Premium" aesthetic: warm, tactile, and deeply inviting. We avoid the clinical coldness of standard e-commerce by using rich textures, layered compositions, and a palette that feels organic rather than synthetic. The goal is to evoke an emotional response of comfort and aspiration, positioning the brand as a curator of sophisticated living spaces.

## Colors

This design system utilizes a sophisticated, content-focused palette that emphasizes airy lightness and soft, romantic tones, now grounded by warmer neutral foundations.

- **Primary (Blush Silk):** A slightly more saturated and warm pink (#efb5bb) that serves as the system's core highlight. It provides a cohesive, floral energy that feels both premium and approachable.
- **Secondary (Dusty Mauve):** A muted, mid-tone rose-grey (#c2a2a4) that provides structural contrast and depth to the lighter primary elements.
- **Tertiary (Champagne Linen):** An extremely light, warm off-white (#ebe5de) used for subtle backgrounds and high-end surface layering.
- **Neutral (Warm Clay):** A custom-defined soft pinkish-grey (#f2bdbd) that replaces standard greys. This ensures that even the most "neutral" surfaces carry a hint of the brand's warmth, maintaining a cohesive, warm-tinted environment across all surface and text variations.

## Typography

The typography strategy relies on the tension between high-contrast Serifs and minimalist Sans-Serifs.

- **Headlines:** Use **Bodoni Moda**. The high stroke contrast mirrors the precision of textile weaving and luxury editorial design. For mobile, headline sizes should scale down by 20% to maintain balance.
- **Body Text:** Use **Libre Franklin**. It provides a neutral, highly readable foundation that doesn't compete with the expressive headlines.
- **Navigation & Labels:** Use **Metrophobic**. To achieve the "tracked-out" look, apply a generous letter-spacing (0.1em to 0.15em). These elements should almost always be in uppercase to act as structural anchors within the layout.

## Layout & Spacing

The layout follows a **Fixed Grid** philosophy on desktop (max-width 1440px) and a fluid model on smaller devices.

- **The Editorial Grid:** Elements often break the standard column alignment to create a dynamic, magazine-style flow. Use "safe margins" of 2rem on desktop to let the content breathe.
- **Rhythm:** Vertical spacing is intentionally generous (stack-xl) between major sections to emphasize the luxury of space.
- **Mobile Adaptivity:** On mobile, margins reduce to 1rem. Complex multi-column grid layouts reflow into a single-column stack, prioritizing large-scale imagery that spans the full width of the viewport.

## Elevation & Depth

In this design system, depth is achieved through **Tonal Layers** and **Subtle Materiality** rather than aggressive shadows.

- **Surfaces:** Use subtle shifts between the primary surface and container tones (derived from the Neutral and Secondary hexes) to define hierarchy.
- **Borders:** Instead of shadows, use extremely thin (1px) borders in **Dusty Mauve** or the new **Warm Clay** neutral to define edges.
- **Shadows:** When necessary for functional depth (like a dropdown menu), use a "Sun-Drenched Shadow"—highly diffused, low-opacity (5-8%), with a slight warm tint to avoid a gray, "dirty" look.

## Shapes

The shape language is **Soft and Architectural**. The interface uses a "Rounded" aesthetic that complements the lighter, romantic color palette.

- **Primary Radius:** A 0.5rem (Rounded) radius is used for buttons and input fields, creating a friendlier, more contemporary feel.
- **Container Radius:** Larger containers like cards use up to 1rem (lg) to emphasize the "Residential" comfort of the brand.
- **Iconography:** Icons should be thin-stroke (1px to 1.5px) and use rounded terminals to match the corner radii of the UI components.

## Components

- **Buttons:** Primary buttons use a solid **Blush Silk** background with dark text for high legibility. On hover, they transition smoothly to a more saturated variation. Secondary buttons use an outline style with 1px **Dusty Mauve** borders.
- **Input Fields:** Bottom-border only or very light four-sided borders in **Dusty Mauve**. Focus state transitions the border and label to **Blush Silk**.
- **Cards:** No shadows; use a subtle **Champagne Linen** background fill and a generous 1rem corner radius.
- **Navigation:** Top-level navigation items use the Nav-Item typography (tracked-out Sans-Serif). Use a simple 1px underline in **Blush Silk** for the active state.
- **Chips/Tags:** Small, pill-shaped tags in a light tint of **Dusty Mauve** or **Warm Clay** with dark text for categorization.