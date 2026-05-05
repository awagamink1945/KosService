---
name: Modern Service Utility
colors:
  surface: '#f9f9ff'
  surface-dim: '#d3daea'
  surface-bright: '#f9f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f0f3ff'
  surface-container: '#e7eefe'
  surface-container-high: '#e2e8f8'
  surface-container-highest: '#dce2f3'
  on-surface: '#151c27'
  on-surface-variant: '#434655'
  inverse-surface: '#2a313d'
  inverse-on-surface: '#ebf1ff'
  outline: '#737686'
  outline-variant: '#c3c6d7'
  surface-tint: '#0053db'
  primary: '#004ac6'
  on-primary: '#ffffff'
  primary-container: '#2563eb'
  on-primary-container: '#eeefff'
  inverse-primary: '#b4c5ff'
  secondary: '#006c49'
  on-secondary: '#ffffff'
  secondary-container: '#6cf8bb'
  on-secondary-container: '#00714d'
  tertiary: '#943700'
  on-tertiary: '#ffffff'
  tertiary-container: '#bc4800'
  on-tertiary-container: '#ffede6'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#dbe1ff'
  primary-fixed-dim: '#b4c5ff'
  on-primary-fixed: '#00174b'
  on-primary-fixed-variant: '#003ea8'
  secondary-fixed: '#6ffbbe'
  secondary-fixed-dim: '#4edea3'
  on-secondary-fixed: '#002113'
  on-secondary-fixed-variant: '#005236'
  tertiary-fixed: '#ffdbcd'
  tertiary-fixed-dim: '#ffb596'
  on-tertiary-fixed: '#360f00'
  on-tertiary-fixed-variant: '#7d2d00'
  background: '#f9f9ff'
  on-background: '#151c27'
  surface-variant: '#dce2f3'
typography:
  h1:
    fontFamily: Inter
    fontSize: 24px
    fontWeight: '700'
    lineHeight: 32px
  h2:
    fontFamily: Inter
    fontSize: 20px
    fontWeight: '600'
    lineHeight: 28px
  body-lg:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '400'
    lineHeight: 24px
  body-md:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '400'
    lineHeight: 20px
  button:
    fontFamily: Inter
    fontSize: 16px
    fontWeight: '600'
    lineHeight: 24px
  label-sm:
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
  base: 4px
  xs: 4px
  sm: 8px
  md: 16px
  lg: 24px
  xl: 32px
  container-padding: 20px
  gutter: 12px
---

## Brand & Style

The design system is built for the "KosService" ecosystem, focusing on the unique needs of boarding house residents who prioritize efficiency, reliability, and ease of use. The brand personality is **Practical, Clean, and Helpful**, positioning the app as a reliable digital assistant for daily living. 

The visual style follows a **Corporate Modern** aesthetic with **Minimalist** influences. It avoids unnecessary decoration in favor of clarity and high-speed task completion. By utilizing ample whitespace and a systematic hierarchy, the design system ensures that service requests—from laundry to maintenance—feel manageable and stress-free. The emotional response is one of "ordered simplicity," giving users confidence that their living environment is well-managed.

## Colors

The palette is anchored by a **Vibrant Blue**, chosen to evoke trust and technological reliability. This is the primary driver for all core actions and navigation elements.

- **Primary (#2563EB):** Used for primary buttons, active states in the bottom navigation, and key progress indicators.
- **Secondary (#10B981):** A "Success Green" reserved for positive outcomes, confirmation messages, and high-priority contact actions like the "Chat Kurir" feature.
- **Danger (#EF4444):** A high-visibility red for destructive actions, error states, and logout prompts to prevent accidental user errors.
- **Neutral Scale:** Utilizes a range of grays to establish hierarchy in text and subtle borders. The background is a very soft off-white to reduce eye strain during evening use.

## Typography

This design system utilizes **Inter**, a highly legible sans-serif designed for screens. The typography focuses on a strict vertical rhythm and clear weight differentiation to guide the user through service forms and status updates.

- **Headlines:** Bold and concise to define screen context immediately.
- **Body Text:** Uses a standard 16px size for primary information to ensure accessibility for all users.
- **Labels:** Medium weights are used for form headers and micro-copy to maintain clarity at smaller scales.
- **Hierarchy:** Contrast is achieved through weight (Regular vs. Semi-Bold) rather than excessive size variations, maintaining the "Practical" tone.

## Layout & Spacing

The design system employs a **Fluid Grid** model optimized for mobile devices. It uses a 4-column structure with a standard 20px outer margin to ensure content doesn't feel cramped against the screen edges.

The spacing philosophy follows a **4px baseline grid**, ensuring that all elements—from icons to text blocks—align mathematically. 
- **Vertical Spacing:** 16px (md) is the standard gap between related elements, while 24px (lg) separates distinct sections.
- **Horizontal Scroll:** Horizontal scrollable banners should use a "peek" effect, showing 10-15% of the next card to signal interactivity.

## Elevation & Depth

To maintain a modern and clean look, depth is communicated through **Ambient Shadows** rather than heavy outlines. Shadows are used sparingly to elevate "floating" elements like cards and the bottom navigation bar.

- **Low Elevation:** Used for cards and input fields. A soft blur (Y: 2, Blur: 4, Opacity: 0.05) creates a subtle lift from the background.
- **High Elevation:** Reserved for the persistent bottom navigation and any floating action buttons. This uses a wider spread (Y: -4, Blur: 12, Opacity: 0.08) to indicate it sits above the scrollable content layer.
- **Tonal Layering:** Different shades of neutral gray are used for "surface-container" areas to group information without needing a shadow.

## Shapes

The shape language is defined by a consistent **12px border radius**, striking a balance between a friendly, approachable feel and a structured, professional appearance.

- **Input Fields & Cards:** Strictly 12px radius. This consistency reinforces the "Systematic" nature of the design.
- **Buttons:** While primary buttons can follow the 12px rule, secondary "pill" buttons or chips may use a full-round radius for better visual distinction.
- **Banners:** Large promotional banners also adhere to the 12px radius to ensure they feel integrated into the layout.

## Components

The components in this design system are engineered for high-frequency interaction and clarity.

- **Buttons:** 
  - Primary buttons are full-width with a minimum height of 52px to ensure a comfortable tap target. 
  - The "Chat Kurir" button uses the secondary green with a prominent message icon.
- **Input Fields:** 
  - Must include leading icons (e.g., a magnifying glass for search, a lock for passwords) to provide visual cues.
  - 12px border radius with a light gray border that transitions to the primary blue on focus.
- **Horizontal Banners:** 
  - Used for announcements or promotions. These should support image backgrounds with text overlays on a 40% black gradient for legibility.
- **Bottom Navigation:** 
  - Persistent at the bottom of the screen with a blur effect (backdrop-filter) and subtle top shadow.
  - Icons are accompanied by text labels for maximum clarity.
- **Cards:** 
  - Use 12px radius and a soft shadow. Cards should group related service info (e.g., "Laundry Status" or "Billing").
- **Chips/Badges:** 
  - Small, high-contrast labels used for status indicators like "Pending," "Completed," or "In Progress."