---
name: Colliers Chile Institutional Excellence
colors:
  surface: '#121414'
  surface-dim: '#121414'
  surface-bright: '#38393a'
  surface-container-lowest: '#0c0f0f'
  surface-container-low: '#1a1c1c'
  surface-container: '#1e2020'
  surface-container-high: '#282a2b'
  surface-container-highest: '#333535'
  on-surface: '#e2e2e2'
  on-surface-variant: '#c3c5d9'
  inverse-surface: '#e2e2e2'
  inverse-on-surface: '#2f3131'
  outline: '#8d90a2'
  outline-variant: '#434656'
  surface-tint: '#b7c4ff'
  primary: '#b7c4ff'
  on-primary: '#002584'
  primary-container: '#1c54f4'
  on-primary-container: '#dfe2ff'
  inverse-primary: '#084ced'
  secondary: '#e6c364'
  on-secondary: '#3d2e00'
  secondary-container: '#785d00'
  on-secondary-container: '#fdd977'
  tertiary: '#bac8dc'
  on-tertiary: '#243141'
  tertiary-container: '#596779'
  on-tertiary-container: '#d7e5fb'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#dde1ff'
  primary-fixed-dim: '#b7c4ff'
  on-primary-fixed: '#001453'
  on-primary-fixed-variant: '#0037b8'
  secondary-fixed: '#ffe08f'
  secondary-fixed-dim: '#e6c364'
  on-secondary-fixed: '#241a00'
  on-secondary-fixed-variant: '#584400'
  tertiary-fixed: '#d6e4f9'
  tertiary-fixed-dim: '#bac8dc'
  on-tertiary-fixed: '#0f1c2c'
  on-tertiary-fixed-variant: '#3a4859'
  background: '#121414'
  on-background: '#e2e2e2'
  surface-variant: '#333535'
typography:
  display-xl:
    fontFamily: Inter
    fontSize: 64px
    fontWeight: '700'
    lineHeight: 72px
    letterSpacing: -0.02em
  display-lg:
    fontFamily: Inter
    fontSize: 48px
    fontWeight: '700'
    lineHeight: 56px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Inter
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
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
    fontWeight: '400'
    lineHeight: 16px
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

This design system establishes a visual language of institutional authority and high-stakes investment confidence. It is tailored for high-net-worth individuals and corporate entities, evoking the atmosphere of an exclusive private wealth management firm. 

The aesthetic is **Sophisticated Dark Mode**, characterized by deep, cinematic backgrounds and precise, razor-sharp UI elements. By blending **Minimalism** with subtle **Glassmorphism**, the system maintains a clean functional core while adding layers of depth that suggest technological sophistication. Visual interest is driven by high-quality architectural photography treated with dark gradients, ensuring that legibility and lead conversion remain the primary focus. The inclusion of metallic gold accents reinforces a sense of "prestige and prosperity," while the electric blue provides a modern, energetic pulse that signals market agility.

## Colors

The palette is anchored in **Deep Black (#0A0A0A)** to provide a canvas of absolute stability. The brand’s heritage is preserved through the use of **Electric Blue (#1C54F4)** as the primary action color, used sparingly for high-impact CTAs and navigational highlights. 

**Gold (#C9A84C)** serves as a secondary accent color, reserved for high-value indicators, premium tier labeling, and subtle border flourishes that denote luxury. **Navy Blue (#0D1B2A)** is utilized for container backgrounds and surface layering to prevent the UI from feeling flat. Text is rendered in **Off-White (#F5F5F5)** to maintain high contrast without the eye strain of pure white, ensuring a comfortable reading experience for complex investment reports.

## Typography

This design system utilizes **Inter** across all levels to project a modern, utilitarian, and global institutional feel. 

Headlines use **Bold (700)** and **SemiBold (600)** weights with tight letter spacing to create a commanding presence. Large display type is intended for property titles and market headlines. Body text is set in **Regular (400)** weight with generous line height to facilitate the digestion of long-form market analysis. Labels and utility text use uppercase styling with increased letter spacing to provide a structural, "blueprint-like" aesthetic to data-heavy interfaces.

## Layout & Spacing

The layout follows a **Fixed Grid** philosophy for desktop resolutions to maintain a controlled, editorial feel. A 12-column grid is used with 24px gutters and wide 80px margins to ensure content remains focused and prestigious. 

The vertical rhythm is based on an **8px baseline grid**. Heavy whitespace (Level XL) is used between sections to allow the high-end imagery and data visualizations to breathe. Components should use generous internal padding (Level MD) to reinforce the premium, uncrowded nature of the brand. Lead conversion forms are always centered or right-aligned to command attention within the grid.

## Elevation & Depth

Depth is achieved through **Glassmorphism** and **Tonal Layers** rather than traditional shadows. 

1.  **Base Layer:** Deep Black (#0A0A0A) for the primary background.
2.  **Surface Layer:** Navy Blue (#0D1B2A) for primary cards and sections.
3.  **Glass Layer:** Background blur (20px) with a 10% white tint for modal overlays and sticky navigation bars.
4.  **Accents:** 1px solid borders in Gold or Electric Blue (at 30% opacity) are used to define the edges of containers, giving them a "technical" and precise look.

Shadows, when used, are extremely soft, large, and tinted with the Navy Blue background color to avoid looking "dirty" on the dark canvas.

## Shapes

The design system employs **Soft (0.25rem)** roundedness to maintain a professional, architectural edge. This subtle rounding prevents the interface from feeling aggressive while remaining significantly more formal than consumer-grade "bubbly" apps.

Buttons and input fields use the standard 4px radius. High-impact image containers may occasionally use **Sharp (0px)** corners to emphasize a "monolithic" and structural architectural style. Decorative elements, such as gold divider lines, should remain sharp and 1px in thickness.

## Components

### Buttons
Primary buttons are solid **Electric Blue** with white text, using a subtle gold hover state. Secondary buttons are "ghost" style with a 1px **Gold** or **White** border and no fill, transitioning to a solid fill on hover.

### Inputs
Form fields are semi-transparent with a bottom-only border in **Navy Blue**. On focus, the border transitions to **Electric Blue** or **Gold**. Error states must be clearly defined in a high-contrast red that does not clash with the primary blue.

### Cards
Real estate listing cards utilize **dark overlays** on hero images. Property details are displayed in **Inter SemiBold**. A subtle 1px border surrounds the card, glowing slightly with the primary color when hovered.

### Imagery
All imagery must be professional architectural photography. A **20-40% Black overlay** is applied to images used as backgrounds to ensure the Off-White typography remains legible and the "Dark Mode" aesthetic is preserved.

### Conversion Elements
Lead capture forms are housed in **Glassmorphic** containers. The "Submit" or "Inquire" action is always the highest-contrast element on the page, typically using the solid Electric Blue button.