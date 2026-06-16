---
name: Academic Excellence Portal
colors:
  surface: '#f8f9fa'
  surface-dim: '#d9dadb'
  surface-bright: '#f8f9fa'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f3f4f5'
  surface-container: '#edeeef'
  surface-container-high: '#e7e8e9'
  surface-container-highest: '#e1e3e4'
  on-surface: '#191c1d'
  on-surface-variant: '#5f3e39'
  inverse-surface: '#2e3132'
  inverse-on-surface: '#f0f1f2'
  outline: '#946e67'
  outline-variant: '#eabcb4'
  surface-tint: '#c00400'
  primary: '#bb0300'
  on-primary: '#ffffff'
  primary-container: '#ea0500'
  on-primary-container: '#fffbff'
  inverse-primary: '#ffb4a8'
  secondary: '#6b5f00'
  on-secondary: '#ffffff'
  secondary-container: '#fce010'
  on-secondary-container: '#706300'
  tertiary: '#5d5c5b'
  on-tertiary: '#ffffff'
  tertiary-container: '#757474'
  on-tertiary-container: '#f7feff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffdad4'
  primary-fixed-dim: '#ffb4a8'
  on-primary-fixed: '#410100'
  on-primary-fixed-variant: '#930200'
  secondary-fixed: '#ffe317'
  secondary-fixed-dim: '#e0c700'
  on-secondary-fixed: '#201c00'
  on-secondary-fixed-variant: '#514700'
  tertiary-fixed: '#e5e2e1'
  tertiary-fixed-dim: '#c8c6c5'
  on-tertiary-fixed: '#1c1b1b'
  on-tertiary-fixed-variant: '#474746'
  background: '#f8f9fa'
  on-background: '#191c1d'
  surface-variant: '#e1e3e4'
typography:
  display-lg:
    fontFamily: Montserrat
    fontSize: 48px
    fontWeight: '700'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  display-lg-mobile:
    fontFamily: Montserrat
    fontSize: 32px
    fontWeight: '700'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Montserrat
    fontSize: 24px
    fontWeight: '600'
    lineHeight: '1.3'
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: '1.6'
  body-md:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: '1.5'
  label-sm:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '600'
    lineHeight: '1'
    letterSpacing: 0.05em
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  container-max: 1200px
  gutter: 24px
  margin-desktop: 64px
  margin-mobile: 20px
  stack-sm: 8px
  stack-md: 16px
  stack-lg: 32px
---

## Brand & Style

The design system is engineered for the **Katalis BEM FH UI 2026 Announcement Landing Page**. The brand personality is rooted in **Academic Prestige, Authority, and Modernity**. It balances the weight of a historic institution with the energy of a student-led catalyst ("Katalis").

The visual style follows a **Modern Corporate** approach: clean, high-contrast, and highly structured. It utilizes a refined white-space strategy to ensure clarity and a sense of "Official Business." The emotional response should be one of gravity and importance, yet accessible and celebratory for those receiving their results.

- **Primary Style:** Modern Corporate / Minimalist.
- **Visual Tone:** Sharp, intentional, and trustworthy.
- **Target Audience:** Law students, faculty members, and student organization stakeholders.

## Colors

The palette is anchored by the heritage colors of Universitas Indonesia and the Faculty of Law. 

- **Primary (#F50E04):** Used for critical branding elements, primary calls to action, and headers to assert authority.
- **Secondary (#F6DB00):** Used as an accent for highlights, small decorative elements, and active states to provide warmth and visual interest without overpowering the primary red.
- **Neutral / Background:** A clean, paper-white (#FFFFFF) is the primary surface color to maintain an academic feel. Grays are used strictly for secondary text and subtle borders.
- **Semantic Colors:** 
    - **Success (Lolos):** A deep emerald green (#15803D) for status badges.
    - **Neutral/Failure (Tidak Lolos):** A muted charcoal (#374151) rather than a harsh red, to maintain a professional and empathetic tone.

## Typography

The typography strategy uses a pairing of **Montserrat** for impact and **Inter** for utility.

- **Montserrat** (Headlines): Chosen for its geometric stability and bold presence. Use this for the "Katalis" branding and major section headings to evoke a sense of modern prestige.
- **Inter** (Body & Interface): Used for all functional text. Its high legibility is crucial for search results, candidate lists, and official announcements.
- **Scale:** High contrast between display sizes and body text is encouraged to create a clear information hierarchy.

## Layout & Spacing

This design system utilizes a **Fixed Grid** model for desktop to maintain the "official document" look, transitioning to a fluid model for mobile devices.

- **Grid:** 12-column system for desktop (1200px max width).
- **Rhythm:** An 8px linear scale (8, 16, 24, 32, 48, 64) ensures consistent vertical rhythm.
- **Mobile:** Margins reduce to 20px. Content should reflow into a single column, with search bars becoming full-width for thumb-friendly interaction.
- **Safety:** Generous top and bottom padding (80px+) should be used between major sections (e.g., Hero to Search) to prevent visual clutter.

## Elevation & Depth

To maintain a "Modern Official" aesthetic, the design system avoids heavy shadows in favor of **Tonal Layers** and **Low-Contrast Outlines**.

- **Surfaces:** Most content sits on level 0 (pure white).
- **Elevation 1:** Used for search inputs and result cards. Defined by a subtle 1px border (#E5E7EB) and a soft, high-diffusion shadow (0px 4px 20px rgba(0,0,0,0.05)).
- **Overlays:** Modals for detailed status information use a backdrop blur (12px) with a semi-transparent white overlay to maintain focus on the announcement content.

## Shapes

The shape language is **Soft (0.25rem)**. This provides a professional edge that isn't as aggressive as sharp corners, but remains more serious and institutional than highly rounded or "bubbly" designs.

- **Standard Elements:** Buttons and Input fields use `rounded-sm` (4px).
- **Cards & Containers:** Status badges and result cards use `rounded-lg` (8px).
- **Badges:** Success/Status badges can utilize slightly more rounding to differentiate them as "stamps" of approval.

## Components

### Buttons
- **Primary:** Solid FH UI Red (#F50E04) with white Montserrat Bold text. No gradients.
- **Secondary:** Transparent with a 2px Red border.

### Search Bar
- A prominent, centered input field. Use a large magnifying glass icon. The border should thicken or change to UI Yellow (#F6DB00) on focus to guide user attention.

### Status Badges (The "Lolos" Moment)
- **Lolos (Accepted):** A green pill-shaped badge. When selected, the background can trigger a subtle "Celebratory Banner" effect (confetti or geometric patterns in UI Yellow).
- **Tidak Lolos (Not Accepted):** A neutral charcoal gray badge. Professional and quiet.

### Celebratory Banners
- Hero sections should use "Katalis" branding in a large display font. For candidates who pass, a temporary banner with a secondary yellow background and primary red text should be used to mark the achievement.

### Official Header
- A sticky navigation bar containing the FH UI and BEM logos. Background should be pure white with a subtle bottom border to distinguish it from the page content.

### Footer
- High-contrast (Dark background #1A1A1A) with "Copyright Nayla Monica" and official social links.