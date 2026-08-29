---
name: Ethereal Luminescence
colors:
  surface: '#fff8f8'
  surface-dim: '#f2d1de'
  surface-bright: '#fff8f8'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#fff0f4'
  surface-container: '#ffe8f0'
  surface-container-high: '#ffe0ec'
  surface-container-highest: '#fbdae7'
  on-surface: '#28161f'
  on-surface-variant: '#4c444b'
  inverse-surface: '#3f2a34'
  inverse-on-surface: '#ffecf2'
  outline: '#7e747b'
  outline-variant: '#cfc3cb'
  surface-tint: '#745474'
  primary: '#745474'
  on-primary: '#ffffff'
  primary-container: '#ffdbfc'
  on-primary-container: '#7c5c7d'
  inverse-primary: '#e1bae0'
  secondary: '#5d5f5f'
  on-secondary: '#ffffff'
  secondary-container: '#dfe0e0'
  on-secondary-container: '#616363'
  tertiary: '#675e41'
  on-tertiary: '#ffffff'
  tertiary-container: '#f3e5c0'
  on-tertiary-container: '#706648'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffd6fd'
  primary-fixed-dim: '#e1bae0'
  on-primary-fixed: '#2b112e'
  on-primary-fixed-variant: '#5a3c5c'
  secondary-fixed: '#e2e2e2'
  secondary-fixed-dim: '#c6c6c7'
  on-secondary-fixed: '#1a1c1c'
  on-secondary-fixed-variant: '#454747'
  tertiary-fixed: '#f0e2bd'
  tertiary-fixed-dim: '#d3c6a2'
  on-tertiary-fixed: '#221b05'
  on-tertiary-fixed-variant: '#4f462b'
  background: '#fff8f8'
  on-background: '#28161f'
  surface-variant: '#fbdae7'
typography:
  display-lg:
    fontFamily: Playfair Display
    fontSize: 48px
    fontWeight: '600'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Playfair Display
    fontSize: 36px
    fontWeight: '600'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Playfair Display
    fontSize: 32px
    fontWeight: '500'
    lineHeight: '1.3'
  headline-sm:
    fontFamily: Playfair Display
    fontSize: 24px
    fontWeight: '500'
    lineHeight: '1.4'
  body-lg:
    fontFamily: DM Sans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: DM Sans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.6'
  label-sm:
    fontFamily: DM Sans
    fontSize: 12px
    fontWeight: '700'
    lineHeight: '1'
    letterSpacing: 0.1em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  unit: 8px
  container-max: 1280px
  gutter: 24px
  margin-mobile: 20px
  stack-lg: 80px
  stack-md: 48px
  stack-sm: 24px
---

## Brand & Style

The design system is anchored in the concept of **"Ethereal Luminescence."** It bridges the gap between clinical professionalism and a high-end digital sanctuary. The visual language is quiet, intentional, and spacious, utilizing a light-mode foundation to create a refreshing, expansive environment.

The style is **Minimalist Glassmorphism**. It avoids the sterility of pure modernism by utilizing translucent layers, soft background blurs, and subtle orchid accents. Every element is designed to feel as though it is floating in a bright, calm space, emphasizing quality and peace. The emotional goal is to evoke a sense of "Natural Radiance"—clean, rejuvenating, and deeply calm.

## Colors

The palette is derived from the soft glow of morning light and modern luxury, now grounded by refined neutral tones.

*   **Primary (Luminous Orchid):** A slightly more saturated orchid (#ffd6fd) used for brand expression, active states, and primary calls to action. It represents soft vitality and modern elegance.
*   **Background (Pure Alabaster):** A bright, off-white base that provides a fresh and premium canvas, maximizing the sense of space.
*   **Accents (Champagne Gold):** Used sparingly for interactive highlights, premium tags, and decorative borders.
*   **Secondary (Bright White):** Reserved for elevated surface elements and grounding UI components to create subtle contrast.
*   **Neutral (Dusty Mauve):** A sophisticated neutral (#ad909c) used for grounding text, subtle borders, and providing a modern, polished contrast.
*   **Surface (Translucent):** Used for elevated cards and containers, employing backdrop blurs to create a glass-like depth within the bright background.

## Typography

This design system uses a high-contrast typographic pairing to establish a hierarchy of "Authority and Approachability."

**Playfair Display** handles all editorial and structural headings. Its high-contrast strokes evoke the feel of luxury publishing. In this light theme, it maintains elegance in deep charcoal or orchid tones, ensuring legibility against bright backgrounds.

**DM Sans** provides a functional, low-contrast counterpoint for long-form reading and interface labels. Its geometric clarity ensures that services and pricing remain easy to digest.

**Formatting Note:** Use generous paragraph spacing (1.5x body font size) to maintain the "breathable" quality of the layout.

## Layout & Spacing

The layout philosophy follows a **Fixed Grid with Fluid Internal Spacing**. 

*   **Desktop:** A 12-column grid with a maximum width of 1280px. Content is centered with significant outer margins to prevent the UI from feeling "crowded."
*   **Mobile:** A 4-column grid with a minimum 20px side margin.
*   **Rhythm:** This design system utilizes a "Step-Down" spacing model. Section-to-section spacing (stack-lg) is intentionally oversized to create "visual pauses," mimicking the pacing of a physical spa experience.

Whitespace is treated as a functional element, not a void. No primary content should be within 48px of a neighboring section on desktop.

## Elevation & Depth

Hierarchy is achieved through **Glassmorphism and Internal Glows** rather than aggressive outlines or heavy shadows.

1.  **Base Layer:** The Alabaster background serves as the infinite, bright canvas.
2.  **Elevated Surface:** Translucent white containers with backdrop-blurs are used for interactive content blocks. These should feature a very subtle soft shadow or a faint Orchid stroke to maintain color harmony and visual lift.
3.  **Depth Accents:** Elegant line dividers (0.5px thickness) in Champagne Gold or Neutral Mauve at low opacity are used to separate content without adding visual bulk.

## Shapes

The shape language is **Rounded and Organic**. 

Sharp corners are avoided to maintain the "calm and welcoming" brand promise. Standard UI components (buttons, input fields) use a 0.5rem radius (roundedness level 2). Larger containers, such as feature cards and imagery, should utilize the `rounded-xl` (1.5rem) setting to mimic soft, natural curves.

Interactive elements like "Book Now" buttons may occasionally use the "Pill-shaped" treatment if they are standalone floating actions.

## Components

*   **Buttons:** Primary buttons use the Luminous Orchid background with white or deep-toned text. Secondary buttons use a Champagne Gold or Neutral Mauve outline with a transparent, blurred background.
*   **Cards:** Translucent white backgrounds with a 1.5rem corner radius and backdrop filtering. Use high-quality photography with soft, ethereal lighting as headers.
*   **Input Fields:** Minimalist design with a bottom-border only in Champagne Gold or Neutral Mauve. Labels should use the `label-sm` typographic role.
*   **Chips/Tags:** Used for "Treatment Types." Small, pill-shaped, with a semi-transparent orchid background and dark neutral text.
*   **Dividers:** Use 1px horizontal lines in Champagne Gold (#F0E2BD) or Neutral Mauve (#AD909C) with 25% opacity to separate menu items or service details.
*   **Photography:** Images should feature "Bright Exposure," "Natural Highlights," and "Macro Textures" (linen, glass, water). Avoid high-contrast, dark, or gritty imagery.