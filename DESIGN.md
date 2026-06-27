---
name: Federation Modernism
colors:
  surface: '#fcf9f8'
  surface-dim: '#dcd9d9'
  surface-bright: '#fcf9f8'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f6f3f2'
  surface-container: '#f0edec'
  surface-container-high: '#ebe7e7'
  surface-container-highest: '#e5e2e1'
  on-surface: '#1c1b1b'
  on-surface-variant: '#424751'
  inverse-surface: '#313030'
  inverse-on-surface: '#f3f0ef'
  outline: '#727782'
  outline-variant: '#c2c6d3'
  surface-tint: '#1d5fa8'
  primary: '#003b72'
  on-primary: '#ffffff'
  primary-container: '#00529b'
  on-primary-container: '#a5c7ff'
  inverse-primary: '#a6c8ff'
  secondary: '#bb0014'
  on-secondary: '#ffffff'
  secondary-container: '#e51d24'
  on-secondary-container: '#fffbff'
  tertiary: '#642a00'
  on-tertiary: '#ffffff'
  tertiary-container: '#883b00'
  on-tertiary-container: '#ffb48b'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#d5e3ff'
  primary-fixed-dim: '#a6c8ff'
  on-primary-fixed: '#001c3b'
  on-primary-fixed-variant: '#004787'
  secondary-fixed: '#ffdad6'
  secondary-fixed-dim: '#ffb4ac'
  on-secondary-fixed: '#410002'
  on-secondary-fixed-variant: '#93000d'
  tertiary-fixed: '#ffdbca'
  tertiary-fixed-dim: '#ffb68e'
  on-tertiary-fixed: '#331200'
  on-tertiary-fixed-variant: '#773300'
  background: '#fcf9f8'
  on-background: '#1c1b1b'
  surface-variant: '#e5e2e1'
  surface-alt: '#F8F9FA'
  white: '#FFFFFF'
typography:
  headline-xl:
    fontFamily: Oswald
    fontSize: 64px
    fontWeight: '700'
    lineHeight: 72px
    letterSpacing: 0.02em
  headline-lg:
    fontFamily: Oswald
    fontSize: 40px
    fontWeight: '600'
    lineHeight: 48px
    letterSpacing: 0.01em
  headline-lg-mobile:
    fontFamily: Oswald
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 38px
  headline-md:
    fontFamily: Oswald
    fontSize: 24px
    fontWeight: '500'
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
  label-sm:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '600'
    lineHeight: 16px
    letterSpacing: 0.05em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  base: 8px
  container-max: 1280px
  gutter: 24px
  margin-mobile: 16px
  section-gap: 80px
---

## Brand & Style
The design system embodies the authority and prestige of a governing athletic body. The aesthetic, "Federation Modernism," moves away from the aggressive grit of commercial gyms toward a structured, institutional, and high-performance visual language. It balances patriotic traditionalism with modern sports science.

The target audience includes professional athletes, certified judges, and institutional partners. The UI evokes feelings of discipline, official certification, and national pride. The style utilizes a **Corporate / Modern** foundation with **High-Contrast** accents, ensuring every piece of information feels sanctioned and vital. Layouts are rigorous and aligned, reflecting the precision required in bodybuilding and fitness competition.

## Colors
The palette is rooted in institutional trust and athletic energy. 

- **Institutional Blue:** Used for primary actions, header backgrounds, and official stamps. It represents the "Patriotic Blue" of the association's heritage.
- **Athletic Red:** Reserved for high-impact accents, live event indicators, and urgent calls to action. It should be used sparingly to maintain its psychological "spike" in energy.
- **Deep Navy/Black:** Employed for footers and high-impact "Power Sections" (e.g., Hall of Fame or Championship announcements) to provide gravity and contrast.
- **Surface Grays:** Used to differentiate content blocks without the harshness of pure black borders, maintaining an organized, multi-layered information hierarchy.

## Typography
The typography strategy creates a sharp distinction between "Athletic Impact" and "Regulatory Clarity."

- **Headlines:** Oswald provides a condensed, vertical rhythm that echoes the strength and height of a physique on stage. All major headlines should be in uppercase to reinforce the institutional voice.
- **Body:** Inter is used for all functional text, ensuring that complex competition rules and federation bylaws remain highly legible.
- **Labels:** Small labels use Inter with increased letter spacing and uppercase styling to denote categories, dates, and metadata clearly.

## Layout & Spacing
The layout follows a **Fixed Grid** model for desktop to maintain a prestigious, editorial feel, transitioning to a fluid system for mobile.

- **Grid:** A 12-column grid is used for desktop (1280px max-width).
- **Rhythm:** Spacing is strictly based on 8px increments. Large "Section Gaps" (80px+) are used to separate major content areas, allowing high-quality photography to breathe.
- **Reflow:** On mobile, margins reduce to 16px. Cards and complex data tables should switch to a stacked vertical format or a horizontally scrollable container to preserve data integrity.

## Elevation & Depth
Depth is handled through **Tonal Layers** and **Low-contrast Outlines** rather than heavy shadows. This reinforces the "Official Document" feel.

- **Tiers:** Use `#F8F9FA` for secondary background sections. White cards sit on top of these gray backgrounds with a very soft, 10% opacity blue-tinted shadow.
- **Borders:** Use 1px solid borders in light gray (`#E5E7EB`) for UI elements like input fields and card boundaries.
- **High Impact:** Deep Navy (`#111111`) sections use pure white text to create a "Stage Light" effect, drawing immediate attention to featured athletes or upcoming championships.

## Shapes
The shape language is "Soft" yet disciplined. While 0px corners feel too aggressive/brutalist, overly rounded corners feel too "tech-consumer." 

A subtle **4px (0.25rem)** radius is applied to buttons, cards, and input fields. This provides a modern touch while maintaining the structural rigidity expected of a sports federation. Large-scale imagery should remain sharp-edged (0px) to feel like professional posters.

## Components
- **Buttons:** Primary buttons use the Institutional Blue with white text. Hover states should transition smoothly to a slightly darker shade of blue. Use "Athletic Red" only for the most critical action (e.g., "Inscribirse Ahora").
- **Cards:** White backgrounds with 1px light gray borders. Photography within cards should have a subtle zoom-in transition on hover.
- **Chips/Badges:** Used for competition categories (e.g., "Men's Physique," "Bikini Fitness"). These use a light gray fill with the Deep Navy text in the `label-sm` style.
- **Input Fields:** Clean, 1px bordered boxes. On focus, the border transitions to Institutional Blue.
- **Institutional Seal:** The A.PA.MU.FI logo should always be placed in a high-contrast area, ideally top-left in the navigation or centered in the footer.
- **Animations:** Transitions are strictly functional. Use `ease-in-out` 200ms for hover states. Page sections should utilize a subtle 20px translateY fade-in as the user scrolls to create a premium, choreographed feel.