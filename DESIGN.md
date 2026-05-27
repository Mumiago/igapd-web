---
name: Industrial Precision
colors:
  surface: '#f9f9f9'
  surface-dim: '#dadada'
  surface-bright: '#f9f9f9'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f3f3f3'
  surface-container: '#eeeeee'
  surface-container-high: '#e8e8e8'
  surface-container-highest: '#e2e2e2'
  on-surface: '#1a1c1c'
  on-surface-variant: '#5e3f3c'
  inverse-surface: '#2f3131'
  inverse-on-surface: '#f1f1f1'
  outline: '#936e6a'
  outline-variant: '#e8bcb7'
  surface-tint: '#c00014'
  primary: '#bb0013'
  on-primary: '#ffffff'
  primary-container: '#e71520'
  on-primary-container: '#fffbff'
  inverse-primary: '#ffb4ab'
  secondary: '#5e5e5e'
  on-secondary: '#ffffff'
  secondary-container: '#e2e2e2'
  on-secondary-container: '#646464'
  tertiary: '#5c5c5c'
  on-tertiary: '#ffffff'
  tertiary-container: '#747474'
  on-tertiary-container: '#fefcfc'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdad6'
  primary-fixed-dim: '#ffb4ab'
  on-primary-fixed: '#410002'
  on-primary-fixed-variant: '#93000d'
  secondary-fixed: '#e2e2e2'
  secondary-fixed-dim: '#c6c6c6'
  on-secondary-fixed: '#1b1b1b'
  on-secondary-fixed-variant: '#474747'
  tertiary-fixed: '#e4e2e2'
  tertiary-fixed-dim: '#c7c6c6'
  on-tertiary-fixed: '#1b1c1c'
  on-tertiary-fixed-variant: '#464747'
  background: '#f9f9f9'
  on-background: '#1a1c1c'
  surface-variant: '#e2e2e2'
typography:
  h1:
    fontFamily: Inter
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.2'
    letterSpacing: -0.02em
  h2:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '700'
    lineHeight: '1.3'
    letterSpacing: -0.01em
  h3:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.4'
    letterSpacing: '0'
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
    letterSpacing: '0'
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
    letterSpacing: '0'
  body-sm:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: '1.5'
    letterSpacing: '0'
  label-caps:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '700'
    lineHeight: '1'
    letterSpacing: 0.05em
  data-mono:
    fontFamily: monospace
    fontSize: 14px
    fontWeight: '500'
    lineHeight: '1.4'
    letterSpacing: '0'
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  base: 8px
  xs: 4px
  sm: 12px
  md: 24px
  lg: 48px
  xl: 80px
  container-max: 1280px
  gutter: 24px
---

## Brand & Style

This design system is built to project the core values of 3M: innovation, protection, and uncompromising quality. The brand personality is authoritative and technical, designed for professionals who rely on their equipment in hazardous environments. The visual language balances industrial toughness with corporate sophistication, avoiding unnecessary decoration in favor of functional clarity.

The chosen style is **Corporate / Modern** with a lean toward structural minimalism. It utilizes rigid layouts and high-contrast elements to evoke a sense of safety and precision. Every interface element is designed to feel like a precision tool—engineered rather than decorated—giving the user confidence in the technical data and product performance being presented.

## Colors

The palette is anchored by the iconic 3M Red, used strictly for primary actions and brand emphasis. Black and a hierarchy of industrial greys form the structural backbone of the UI, ensuring that the interface remains neutral and allows product photography and safety warnings to stand out.

Industrial greys are used to create "material" depth, distinguishing between technical specs, background surfaces, and interactive components. High-contrast white backgrounds are preferred for documentation and specification tables to maximize legibility in various lighting conditions typical of industrial workplaces.

## Typography

This design system utilizes **Inter** for its exceptional legibility and systematic, utilitarian feel. The typographic hierarchy is strictly organized to handle complex technical information without overwhelming the user. 

Headlines are bold and tight to convey strength. Body text is optimized for readability with generous line heights. A specific "Data-Mono" style (using a system monospace fallback) is reserved for technical specifications, serial numbers, and measurements to ensure character distinction—critical for safety-related data. All labels for specifications should use the "label-caps" style to provide a clear anchor for the eye when scanning data sheets.

## Layout & Spacing

The layout philosophy follows a **Fixed Grid** model on a strictly enforced 8px baseline. This mathematical rigidity mirrors the engineering standards of 3M products. 

The primary container is centered with a max-width of 1280px, utilizing a 12-column grid. For technical specification tables and product grids, spacing is condensed (using the 'sm' and 'xs' units) to allow for high information density. For marketing and landing pages, the 'lg' and 'xl' units are used to create breathable, premium sections that highlight product quality through large-scale imagery.

## Elevation & Depth

This design system avoids soft, organic shadows in favor of **low-contrast outlines** and **tonal layers**. Depth is communicated through structural stacking rather than lighting effects.

1.  **Level 0 (Base):** The primary background color.
2.  **Level 1 (Sub-surface):** Used for table headers or secondary content blocks. Slightly darker or lighter than the base.
3.  **Level 2 (Cards/Raised):** Uses a 1px solid border (#E0E0E0) to define boundaries. Shadows are only used on hover to indicate interactivity, and they should be sharp with low blur (e.g., 0px 4px 8px rgba(0,0,0,0.1)).
4.  **Level 3 (Overlay):** Modals and dropdowns use a sharp, 1px border and a distinct, dark shadow to separate them from the work surface.

## Shapes

The shape language is primarily linear and rectangular to maintain an industrial aesthetic. A "Soft" roundedness (0.25rem) is applied to buttons and input fields to provide a touch of ergonomic refinement, suggesting the user-centric design of 3M equipment. Large product cards or image containers may use `rounded-lg` (0.5rem) to soften the overall presentation, but the core identity remains focused on precise, right-angled architecture.

## Components

### Buttons
- **Primary:** Solid 3M Red with white text. Bold, uppercase labels. High-contrast and immediately visible.
- **Secondary:** Solid Black or Ghost (transparent with 2px black border).
- **Technical:** Small, grey buttons for "View Specs" or "Download PDF" actions.

### Product Cards
Cards feature a clean white background with a 1px industrial grey border. The product image should be centered on a light grey (#F9F9F9) square. Key technical specs (e.g., "Protection Level: N95") are displayed as small grey chips.

### Technical Specification Tables
Tables are high-density with a horizontal-only border style. Headers are dark grey with white "label-caps" text. Alternate rows use a subtle zebra-stripe (#F4F4F4) for tracking accuracy across wide data sets.

### Chips & Badges
Used for status indicators (e.g., "In Stock", "Certified"). These should be rectangular with the smallest possible corner radius and high-contrast color coding based on the functional palette.

### Input Fields
Strictly rectangular with a 1px border. Focus states use a 2px 3M Red outline to ensure the user’s location in a form is never in doubt. Labels are always positioned above the field for maximum legibility.