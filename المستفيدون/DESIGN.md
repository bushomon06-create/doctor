---
name: Sanad Care
colors:
  surface: '#f8f9ff'
  surface-dim: '#ccdbf3'
  surface-bright: '#f8f9ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#eff4ff'
  surface-container: '#e6eeff'
  surface-container-high: '#dce9ff'
  surface-container-highest: '#d5e3fc'
  on-surface: '#0d1c2e'
  on-surface-variant: '#40474f'
  inverse-surface: '#233144'
  inverse-on-surface: '#eaf1ff'
  outline: '#707881'
  outline-variant: '#c0c7d1'
  surface-tint: '#006399'
  primary: '#00507d'
  on-primary: '#ffffff'
  primary-container: '#0369a1'
  on-primary-container: '#cbe4ff'
  inverse-primary: '#94ccff'
  secondary: '#006a61'
  on-secondary: '#ffffff'
  secondary-container: '#86f2e4'
  on-secondary-container: '#006f66'
  tertiary: '#6003d1'
  on-tertiary: '#ffffff'
  tertiary-container: '#7936ea'
  on-tertiary-container: '#e9dbff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#cde5ff'
  primary-fixed-dim: '#94ccff'
  on-primary-fixed: '#001d32'
  on-primary-fixed-variant: '#004b74'
  secondary-fixed: '#89f5e7'
  secondary-fixed-dim: '#6bd8cb'
  on-secondary-fixed: '#00201d'
  on-secondary-fixed-variant: '#005049'
  tertiary-fixed: '#eaddff'
  tertiary-fixed-dim: '#d2bbff'
  on-tertiary-fixed: '#25005a'
  on-tertiary-fixed-variant: '#5a00c6'
  background: '#f8f9ff'
  on-background: '#0d1c2e'
  surface-variant: '#d5e3fc'
typography:
  display:
    fontFamily: IBM Plex Sans
    fontSize: 3rem
    fontWeight: '700'
    lineHeight: 3.75rem
    letterSpacing: '0'
  headline-lg:
    fontFamily: IBM Plex Sans
    fontSize: 2.25rem
    fontWeight: '700'
    lineHeight: 3rem
    letterSpacing: '0'
  headline-lg-mobile:
    fontFamily: IBM Plex Sans
    fontSize: 1.75rem
    fontWeight: '700'
    lineHeight: 2.375rem
    letterSpacing: '0'
  headline-md:
    fontFamily: IBM Plex Sans
    fontSize: 1.5rem
    fontWeight: '600'
    lineHeight: 2.125rem
    letterSpacing: '0'
  headline-sm:
    fontFamily: IBM Plex Sans
    fontSize: 1.25rem
    fontWeight: '600'
    lineHeight: 1.875rem
    letterSpacing: '0'
  body-lg:
    fontFamily: IBM Plex Sans
    fontSize: 1.125rem
    fontWeight: '400'
    lineHeight: 1.875rem
    letterSpacing: '0'
  body-md:
    fontFamily: IBM Plex Sans
    fontSize: 1rem
    fontWeight: '400'
    lineHeight: 1.75rem
    letterSpacing: '0'
  body-sm:
    fontFamily: IBM Plex Sans
    fontSize: 0.875rem
    fontWeight: '400'
    lineHeight: 1.5rem
    letterSpacing: '0'
  label-lg:
    fontFamily: IBM Plex Sans
    fontSize: 1.125rem
    fontWeight: '600'
    lineHeight: 1.5rem
    letterSpacing: '0'
  label-md:
    fontFamily: IBM Plex Sans
    fontSize: 0.9375rem
    fontWeight: '600'
    lineHeight: 1.375rem
    letterSpacing: '0'
  label-sm:
    fontFamily: IBM Plex Sans
    fontSize: 0.8125rem
    fontWeight: '600'
    lineHeight: 1.25rem
    letterSpacing: '0'
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-mobile: 1rem
  margin: 2.5rem
  margin-mobile: 1.25rem
  space-xs: 0.5rem
  space-sm: 0.75rem
  space-md: 1.25rem
  space-lg: 1.75rem
  space-xl: 2.5rem
---

## Brand & Style

The design system is tailored for an accessible, humane, and empathetic digital telehealth and rehabilitation ecosystem dedicated to people with determination, individuals with disabilities, and their families. 

The emotional tone balances clinical reassurance with domestic warmth. It rejects cold, clinical sterility in favor of quiet confidence, radical clarity, and stress-reducing harmony. Interactions feel forgiving, tactile, and legible, offering reassurance to families coping with complex therapy schedules while providing accessible agency for individuals navigating motor, cognitive, or sensory differences.

The design movement combines **Accessible Humanism** with **Modern Soft Functionalism**:
- Directionality is natively Right-to-Left (RTL), where visual flows, iconography, and spatial orientation naturally follow Arabic reading mechanics.
- Generous touch targets and ample negative space eliminate fine-motor precision barriers.
- Sensory-friendly design principles: low-stimulation palettes, zero disorienting layout shifts, gentle ambient depth, and explicit tactile feedback.

## Colors

The color palette is engineered to achieve strict WCAG AAA contrast compliance across core reading contexts while emitting calm, restorative energy.

- **Primary (`#0369A1` / Sky 700):** Deep medical blue representing guidance, scientific rigor, and trust. Supported by `#0284C7` (Sky 600) for active UI states and `#E0F2FE` (Sky 100) for high-contrast container fills.
- **Secondary (`#0D9488` / Teal 600):** Restorative therapeutic turquoise denoting rehabilitation, physical healing, and holistic growth. Used for progress indicators, success markers, and therapy session milestones.
- **Tertiary (`#7C3AED` / Soft Violet-Lavender):** A cognitive-support accent that introduces neuro-friendly sensory softness. Used sparingly for supportive notes, companion/caregiver highlights, and specialized developmental programs, backed by `#EDE9FE` for soothing alert panels.
- **Neutrals (`#475569` base slate):** Grounding typography in `#0F172A` (Slate 900) on ultra-soft canvas layers (`#F8FAFC` and `#F1F5F9`). Pure stark white (`#FFFFFF`) is reserved exclusively for elevated interactive cards to minimize glare and sensory eye fatigue.

All text combinations against their adjacent surfaces exceed 7:1 contrast ratios for body copy and 4.5:1 for interactive graphics.

## Typography

The design system implements **IBM Plex Sans** (with explicit native fallback to IBM Plex Sans Arabic) across all hierarchical tiers. Its open counters, distinct glyph differentiation, structural geometric balance, and clean baseline rhythm make it exceptionally legible for Arabic text at any reading distance or zoom scale.

- **Baseline & Line Height:** Line heights are calibrated wider (1.6 to 1.75x) to accommodate Arabic ascenders, descenders, and optional tashkeel/diacritics without clipping or cognitive overcrowding.
- **Letter Spacing:** Fixed to `0` across all scales. Arabic typography does not support positive character tracking due to cursive letter ligatures.
- **Hierarchical Restraint:** Heavy weights (`700`) are reserved solely for primary section titles to prevent visual aggression. Body levels favor clear `400` weights on dark slate (`#0F172A`) to preserve clarity for users with visual fatigue or dyslexia.

## Layout & Spacing

The layout employs a responsive, fluid 12-column grid on desktop/tablet and a 4-column grid on mobile devices.

- **RTL-First Structure:** Layout flows naturally right-to-left. Sidebar navigation anchors to the right viewport boundary; page headers and content flows cascade from right to left.
- **Generous Tap Radii & Spacing:** Minimum distance between independent touchable controls is maintained at `space-sm` (12px) to prevent accidental mis-taps by users with motor tremors or unsteady grip.
- **Adaptive Breakpoints:**
  - *Mobile (< 640px):* Single-column flow with persistent bottom-anchored companion action bars, 20px edge margins, and vertically stacked control groupings.
  - *Tablet (641px - 1024px):* 8-column layout accommodating side-by-side video feeds alongside exercise prompt overlays.
  - *Desktop (> 1025px):* 12-column grid capped at a maximum width of 1440px to ensure line lengths for text do not exceed 75 characters per line, optimizing sustained reading comprehension.

## Elevation & Depth

Visual hierarchy is created through a synthesis of **tonal surface separation** and **soft ambient micro-shadows**. This avoids harsh borders while keeping layered elements immediately distinguishable for users with depth-perception challenges.

- **Canvas (Level 0):** Background surface rendered in `#F8FAFC`. Completely matte and reflection-free.
- **Resting Containers (Level 1):** Main content cards and panels sit on pure `#FFFFFF` with a dual ambient shadow: `0px 2px 8px -2px rgba(15, 23, 42, 0.04), 0px 8px 24px -4px rgba(15, 23, 42, 0.06)`. This diffuse, blue-tinted slate shadow lifts content smoothly without creating sharp optical edges.
- **Floating Controls & Modals (Level 2):** Dropdown sheets, active video call status pills, and alert sheets sit with elevated presence: `0px 12px 32px -4px rgba(3, 105, 161, 0.08), 0px 4px 12px -2px rgba(15, 23, 42, 0.05)`.
- **Focus Rings & Highlighting:** No element relies on drop-shadows alone for focus. Every interactive element adopts a crisp 3px double-offset outline in `#0284C7` with a 2px pure white separation gap upon keyboard navigation or screen-reader focus.

## Shapes

The design system incorporates rounded, organic geometries to communicate safety, warmth, and accessibility.

- **Scale Configuration:** Set to `2` (Rounded), generating baseline borders of `0.5rem` (8px), intermediate containers at `1rem` (16px), and prominent therapy cards and primary containers at `1.5rem` (24px, equivalent to `rounded-2xl`).
- **Interactive Pill Geometry:** Small badge indicators, state tags, audio controls, and emergency contact triggers utilize full pill contours (`rounded-full`) to offer soft touch surfaces with no abrupt edges.
- **Corner Consistency:** All inset nested children maintain proportional concentric curvature (e.g., an image nested within a 24px card uses a 16px corner radius) to maintain optical rhythm.

## Components

### Buttons & Interactive Controls
- **Touch Target:** Minimum height and width of 52px on mobile and 48px on desktop to accommodate assistive pointers and finger taps.
- **Primary Buttons:** Solid `#0369A1` with crisp white bold typography, 24px horizontal padding, and subtle active scale feedback (`transform: scale(0.98)`).
- **Secondary Buttons:** Soft `#F0FDFA` fill with `#0D9488` border (1.5px) and label text, giving a gentle, accessible secondary action.
- **Caregiver / Emergency Quick-Action:** Saturated high-contrast badge button with immediate visual clarity, featuring an accompanying icon on the right side of the Arabic label.

### Form Inputs & Selectors
- **Text Inputs:** Generous 56px height, pure `#FFFFFF` background, framed with `#CBD5E1` (1.5px border). On focus, borders shift to `#0284C7` with an accessible 3px focus halo. Labels sit permanently above the input in `body-md` bold; floating labels are avoided to reduce cognitive load.
- **Checkboxes & Radios:** Scaled to an oversized 24x24px footprint with thick, clear indicator checkmarks and custom high-contrast fill colors, ensuring intuitive validation for users with fine-motor limitations.

### Telehealth Cards & Therapy Progress Cards
- **Structure:** Encased in `rounded-2xl` (1.5rem) with solid white background, 24px internal padding, and subtle 1px border in `#E2E8F0`.
- **Session Indicators:** Status chips positioned consistently in the top-left corner (opposite the right-aligned Arabic title), displaying session state (e.g., "مكتمل", "قيد الانتظار", "جلسة مباشرة") with high-contrast pastel backgrounds.

### Chips & Filters
- Compact interactive filter pills (`rounded-full`) with a minimum height of 40px. Resting state utilizes `#F1F5F9` with `#334155` text; selected state transitions to deep `#0369A1` with pure white text and an explicit checkmark glyph.

### Assistive Audio & Reading Prompts
- Dedicated text-to-speech and visual magnification control dock placed at the top-left of major reading panels, enabling instant sensory adaptations for patients, individuals with disabilities, and their supporting family members.