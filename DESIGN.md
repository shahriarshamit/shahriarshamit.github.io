---
name: Midnight Engineering
colors:
  surface: '#051424'
  surface-dim: '#051424'
  surface-bright: '#2c3a4c'
  surface-container-lowest: '#010f1f'
  surface-container-low: '#0d1c2d'
  surface-container: '#122131'
  surface-container-high: '#1c2b3c'
  surface-container-highest: '#273647'
  on-surface: '#d4e4fa'
  on-surface-variant: '#c6c6cd'
  inverse-surface: '#d4e4fa'
  inverse-on-surface: '#233143'
  outline: '#909097'
  outline-variant: '#45464d'
  surface-tint: '#bec6e0'
  primary: '#bec6e0'
  on-primary: '#283044'
  primary-container: '#0f172a'
  on-primary-container: '#798098'
  inverse-primary: '#565e74'
  secondary: '#4edea3'
  on-secondary: '#003824'
  secondary-container: '#00a572'
  on-secondary-container: '#00311f'
  tertiary: '#adc6ff'
  on-tertiary: '#002e6a'
  tertiary-container: '#00163a'
  on-tertiary-container: '#357df1'
  error: '#ffb4ab'
  on-error: '#690005'
  error-container: '#93000a'
  on-error-container: '#ffdad6'
  primary-fixed: '#dae2fd'
  primary-fixed-dim: '#bec6e0'
  on-primary-fixed: '#131b2e'
  on-primary-fixed-variant: '#3f465c'
  secondary-fixed: '#6ffbbe'
  secondary-fixed-dim: '#4edea3'
  on-secondary-fixed: '#002113'
  on-secondary-fixed-variant: '#005236'
  tertiary-fixed: '#d8e2ff'
  tertiary-fixed-dim: '#adc6ff'
  on-tertiary-fixed: '#001a42'
  on-tertiary-fixed-variant: '#004395'
  background: '#051424'
  on-background: '#d4e4fa'
  surface-variant: '#273647'
  terminal-bg: '#020617'
  success-emerald: '#10B981'
  electric-blue: '#60A5FA'
  surface-border: '#1E293B'
  text-vibrant: '#F8FAFC'
typography:
  headline-lg:
    fontFamily: Hanken Grotesk
    fontSize: 48px
    fontWeight: '800'
    lineHeight: '1.1'
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Hanken Grotesk
    fontSize: 32px
    fontWeight: '800'
    lineHeight: '1.2'
  headline-md:
    fontFamily: Hanken Grotesk
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
  label-code:
    fontFamily: JetBrains Mono
    fontSize: 14px
    fontWeight: '500'
    lineHeight: '1.4'
    letterSpacing: 0.05em
  stats-number:
    fontFamily: Hanken Grotesk
    fontSize: 40px
    fontWeight: '700'
    lineHeight: '1'
rounded:
  sm: 0.125rem
  DEFAULT: 0.25rem
  md: 0.375rem
  lg: 0.5rem
  xl: 0.75rem
  full: 9999px
spacing:
  base: 8px
  gutter: 24px
  section-padding: 80px
  container-max: 1200px
  stack-gap: 16px
---

## Brand & Style

The design system is crafted for a Senior Full Stack Developer, emphasizing high-trust, technical mastery, and long-term reliability. The brand personality is **Authoritative, Precise, and Sophisticated**, reflecting over 14 years of engineering experience and a proven track record of high-value delivery.

The visual style is a **Modern Corporate & Technical** hybrid. It draws from the "Clean Code" movement—prioritizing legibility and structural integrity over decorative flourish. The aesthetic mimics high-end developer tools and command-line environments but is refined for a premium client audience. It uses deep, dark surfaces to minimize eye strain and neon-inspired technical accents to highlight "code-level" excellence. 

Every element should feel "engineered"—calculated, intentional, and robust—evoking the same confidence as a well-architected system.

## Colors

The "Midnight & Tech" palette is designed to convey professional maturity.

- **Primary (Midnight):** A deep, saturated navy-charcoal used for the foundational background. It provides a more sophisticated depth than pure black.
- **Secondary (Emerald):** Used specifically for "success indicators" such as Upwork milestones, 100% success rates, and "Active" project status.
- **Tertiary (Electric Blue):** The primary interactive accent. Used for links, code syntax highlighting, and primary calls to action.
- **Neutral (Slate):** A range of cool grays used for secondary text and structural borders to maintain a low-contrast, easy-to-read hierarchy.

The default mode is **Dark**. Surfaces should use subtle gradients or tonal shifts to distinguish between sections rather than varying lightness significantly.

## Typography

The typography system balances modern accessibility with technical precision. 

- **Headlines:** Use **Hanken Grotesk** for a sharp, contemporary, and authoritative feel. High-level headers should be tightly tracked and bold to command attention.
- **Body:** Use **Inter** for its exceptional readability at small sizes and its neutral, systematic aesthetic. It ensures that long technical descriptions remain approachable.
- **Data & Labels:** Use **JetBrains Mono** for technical labels, skill tags, and snippets. This monospaced font reinforces the developer persona and helps differentiate "technical data" from "narrative content."

Scale typography purposefully: use large, impactful numbers for achievements (e.g., "14+ Years") and clear, structured headings for skill categorization.

## Layout & Spacing

The layout philosophy follows a **Fixed-Width Grid** on desktop to maintain a "dashboard" feel, transitioning to a fluid stack on mobile.

- **Grid:** Use a 12-column grid for desktop with 24px gutters. Content should be centered within a 1200px container to ensure readability on ultrawide monitors.
- **Rhythm:** An 8px base unit governs all spacing. Section vertical padding is generous (80px+) to allow the "Midnight" background to provide breathing room, signifying high-end quality.
- **Information Density:** While the overall layout is airy, specific "Technical Blocks" (like skill lists or project details) should use tighter spacing (16px stack gap) to reflect the density of a code editor.
- **Responsive:** On tablet (under 1024px), move to an 8-column grid with 32px side margins. On mobile (under 640px), collapse to a 1-column stack with 20px margins.

## Elevation & Depth

This design system eschews traditional shadows in favor of **Tonal Layers and Technical Outlines**.

- **Surfaces:** Depth is created by "lifting" elements with slightly lighter fill colors. For example, a card might use a background of `#1E293B` against the site background of `#0F172A`.
- **Borders:** Use 1px solid borders for all containers. These should be subtle (`#1E293B`) for standard cards and more vibrant (`#3B82F6`) for active or highlighted elements.
- **Glassmorphism:** Apply a subtle backdrop blur (12px) to the navigation bar and modal overlays to maintain a sense of context and modern "engineered" layering.
- **Shadows:** If used, shadows should be extremely sharp and low-opacity, acting more as a "glow" from the electric blue accent than a physical shadow.

## Shapes

The shape language is **Soft (0.25rem)**, leaning toward the "Sharp" end of the spectrum. This reinforces a professional, disciplined, and technical aesthetic.

- **Standard Elements:** Buttons, input fields, and tags use a `rounded-sm` (4px) radius. 
- **Containers:** Larger cards and image containers use a `rounded-md` (8px) radius. 
- **Pills:** Only used for status indicators (e.g., "Top Rated" badge) to make them stand out from the rigid technical grid.

The interaction of sharp lines and subtle rounding creates a UI that feels modern but structured.

## Components

- **Buttons:** Primary buttons use the Electric Blue background with white text, no icons (or a simple right-arrow). Secondary buttons use a transparent background with a 1px Slate border.
- **Chips / Tags:** Use the monospaced font for tech tags. Backgrounds should be a very dark tint of the accent color (e.g., deep emerald green) with a high-contrast label.
- **Cards:** Cards should have a distinct 1px border. For project cards, include a "header" area that mimics a code editor tab or a terminal window header.
- **Input Fields:** Use a dark, recessed background with a 1px border that turns Electric Blue on focus. Labels should be small, monospaced, and positioned above the field.
- **Code Snippets:** Use a specialized component with a "terminal-bg" background and a "traffic light" window control icon set in the corner. Syntax highlighting must match the Emerald and Electric Blue palette.
- **Success Indicators:** Specialized badges for Upwork metrics. Use a subtle Emerald glow effect to signify high performance and trustworthiness.