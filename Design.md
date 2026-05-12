---
name: Public Service Design System
colors:
  surface: '#fbf8fd'
  surface-dim: '#dbd9dd'
  surface-bright: '#fbf8fd'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f5f3f7'
  surface-container: '#efedf1'
  surface-container-high: '#e9e7ec'
  surface-container-highest: '#e4e2e6'
  on-surface: '#1b1b1f'
  on-surface-variant: '#44464f'
  inverse-surface: '#303034'
  inverse-on-surface: '#f2f0f4'
  outline: '#757780'
  outline-variant: '#c5c6d0'
  surface-tint: '#4c5d8a'
  primary: '#00153f'
  on-primary: '#ffffff'
  primary-container: '#182b55'
  on-primary-container: '#8293c3'
  inverse-primary: '#b4c6f9'
  secondary: '#645d58'
  on-secondary: '#ffffff'
  secondary-container: '#eae1da'
  on-secondary-container: '#6a635e'
  tertiary: '#3a0002'
  on-tertiary: '#ffffff'
  tertiary-container: '#610006'
  on-tertiary-container: '#ff5c52'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dae2ff'
  primary-fixed-dim: '#b4c6f9'
  on-primary-fixed: '#031943'
  on-primary-fixed-variant: '#344671'
  secondary-fixed: '#eae1da'
  secondary-fixed-dim: '#cec5bf'
  on-secondary-fixed: '#1f1b17'
  on-secondary-fixed-variant: '#4b4641'
  tertiary-fixed: '#ffdad6'
  tertiary-fixed-dim: '#ffb4ac'
  on-tertiary-fixed: '#410002'
  on-tertiary-fixed-variant: '#93000e'
  background: '#fbf8fd'
  on-background: '#1b1b1f'
  surface-variant: '#e4e2e6'
typography:
  display-lg:
    fontFamily: publicSans
    fontSize: 56px
    fontWeight: '700'
    lineHeight: 64px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: publicSans
    fontSize: 32px
    fontWeight: '600'
    lineHeight: 40px
    letterSpacing: -0.01em
  headline-lg-mobile:
    fontFamily: publicSans
    fontSize: 28px
    fontWeight: '600'
    lineHeight: 36px
  headline-md:
    fontFamily: publicSans
    fontSize: 24px
    fontWeight: '600'
    lineHeight: 32px
  title-lg:
    fontFamily: publicSans
    fontSize: 20px
    fontWeight: '500'
    lineHeight: 28px
  body-lg:
    fontFamily: publicSans
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: publicSans
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  label-md:
    fontFamily: publicSans
    fontSize: 14px
    fontWeight: '500'
    lineHeight: 20px
    letterSpacing: 0.01em
  label-sm:
    fontFamily: publicSans
    fontSize: 12px
    fontWeight: '600'
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
  container-max: 1280px
  gutter: 24px
  margin-desktop: 64px
  margin-mobile: 20px
---

## Brand & Style

The design system is defined by an ethos of civic trust and editorial clarity. It bridges the gap between institutional authority and human accessibility. The aesthetic direction is **Modern Corporate with an Editorial lean**, prioritizing legibility and a sense of "quiet importance." 

The visual language avoids the coldness of pure white and heavy blacks, instead utilizing a warm, paper-like surface and a deep, intellectual navy. The RTA Red is used sparingly as a "call to action" and a signal of critical information, ensuring the interface remains professional and calm while highlighting essential user pathways.

## Colors

The palette is anchored by a sophisticated **Primary Blue (#182B55)**, which conveys stability and tradition. This is balanced by a **Secondary Stone (#78716c)** that handles supporting UI elements and metadata. 

The **Tertiary Red (#EC2027)** serves as the high-visibility accent, reserved for primary actions, alerts, and branding moments. The foundation of the system is the **Warm Surface (#fff8f5)**, which reduces eye strain and provides a premium, "stationery" feel compared to default digital whites.

- **Primary:** Deep Navy for headers, primary buttons, and iconography.
- **Secondary:** Warm Grey for borders, secondary text, and inactive states.
- **Accent:** RTA Red for critical buttons, active indicators, and notifications.
- **Surface:** Warm Off-white for page backgrounds and container fills.

## Typography

This design system utilizes **Public Sans** (as a high-accessibility proxy for Google Sans) to maintain a clean, geometric, and neutral tone. The typography follows an editorial scale, with generous line heights and tight letter spacing for large display titles.

- **Headlines:** Use Semi-Bold (600) or Bold (700) weights to establish clear hierarchy against the warm background.
- **Body Text:** Set in 16px or 18px to ensure high readability for long-form content.
- **Labels:** Use Medium (500) or Semi-Bold (600) weights. Small labels may use all-caps with light tracking to denote categories or metadata.
- **Color Application:** Headings should primarily use the Primary Blue (#182B55), while body text utilizes a darkened version of the Secondary Stone for optimal contrast.

## Layout & Spacing

The system employs a **Fixed Grid** philosophy for desktop to maintain editorial integrity, transitioning to a fluid model for mobile devices. 

- **Grid:** A 12-column grid is standard for desktop (1280px max-width).
- **Rhythm:** An 8px base unit drives all padding and margin increments.
- **Vertical Rhythm:** Generous whitespace between sections (e.g., 80px or 120px) is encouraged to reinforce the premium, "uncluttered" public service feel.
- **Alignment:** Content is typically centered in the viewport with large side margins on wide screens to keep line lengths readable.

## Elevation & Depth

Depth in this design system is achieved through **Tonal Layering** and **Low-Contrast Outlines** rather than aggressive shadows. This preserves the "flat" editorial aesthetic while providing necessary visual cues.

- **Surfaces:** Use subtle shifts in value. The main background is `#fff8f5`; cards and elevated containers may use absolute white `#ffffff` to "pop" forward.
- **Borders:** Use 1px solid strokes in the Secondary Stone (#78716c) at low opacity (15-20%) to define containers.
- **Shadows:** When necessary for functional elevation (like dropdowns), use "Ambient Shadows"—diffused, low-opacity (10%) blurs with a slight tint of the Primary Blue to maintain color harmony.

## Shapes

The shape language is **Soft (0.25rem / 4px)**. This choice strikes a balance between the rigid formality of sharp corners (0px) and the overly casual nature of fully rounded elements (8px+). 

- **Small Components:** Buttons, input fields, and tags use a 4px corner radius.
- **Large Components:** Cards and modals may scale up to a "Large" radius (8px) to soften their presence on the page.
- **Icons:** Should follow a similar soft-cornered aesthetic, avoiding perfectly sharp or circular terminals.

## Components

### Buttons
- **Primary:** Solid #EC2027 (RTA Red) with white text. High contrast for main actions.
- **Secondary:** Outlined with #182B55 (Primary Blue) or solid #182B55 with white text for institutional actions.
- **Ghost:** Text-only in Secondary Stone for low-priority navigation.

### Input Fields
- **Background:** Pure white (#ffffff) to contrast against the warm surface.
- **Border:** 1px stroke in Secondary Stone. On focus, the border thickens or changes to Primary Blue.
- **Labels:** Always visible, placed above the field in Label-MD typography.

### Cards
- Flat design with a 1px #78716c (20% opacity) border. 
- Editorial style: Use Primary Blue for card titles and generous internal padding (24px or 32px).

### Chips & Tags
- Used for categorization. Subtle warm fills (a slightly darker tint of the surface color) with #182B55 text.

### Navigation
- Global navigation utilizes the Primary Blue for the background with white text, or a clean white background with Primary Blue typography for a lighter, more modern feel.
