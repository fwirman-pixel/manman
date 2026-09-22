---
name: Kinetic Pop Arcade
colors:
  surface: '#fbf8ff'
  surface-dim: '#d4d8f7'
  surface-bright: '#fbf8ff'
  surface-container-lowest: '#ffffff'
  surface-container-low: '#f3f2ff'
  surface-container: '#ececff'
  surface-container-high: '#e4e7ff'
  surface-container-highest: '#dde1ff'
  on-surface: '#151a30'
  on-surface-variant: '#5b3f44'
  inverse-surface: '#2a2f47'
  inverse-on-surface: '#f0efff'
  outline: '#8f6f74'
  outline-variant: '#e3bdc3'
  surface-tint: '#bc0051'
  primary: '#b7004e'
  on-primary: '#ffffff'
  primary-container: '#df1e65'
  on-primary-container: '#fffbff'
  inverse-primary: '#ffb1c0'
  secondary: '#705d00'
  on-secondary: '#ffffff'
  secondary-container: '#ffde59'
  on-secondary-container: '#756100'
  tertiary: '#006384'
  on-tertiary: '#ffffff'
  tertiary-container: '#007ea6'
  on-tertiary-container: '#fbfcff'
  error: '#ba1a1a'
  on-error: '#ffffff'
  error-container: '#ffdad6'
  on-error-container: '#93000a'
  primary-fixed: '#ffd9df'
  primary-fixed-dim: '#ffb1c0'
  on-primary-fixed: '#3f0016'
  on-primary-fixed-variant: '#90003c'
  secondary-fixed: '#ffe16e'
  secondary-fixed-dim: '#e4c542'
  on-secondary-fixed: '#221b00'
  on-secondary-fixed-variant: '#544600'
  tertiary-fixed: '#c2e8ff'
  tertiary-fixed-dim: '#75d1ff'
  on-tertiary-fixed: '#001e2b'
  on-tertiary-fixed-variant: '#004d67'
  background: '#fbf8ff'
  on-background: '#151a30'
  surface-variant: '#dde1ff'
typography:
  display-xl:
    fontFamily: Bricolage Grotesque
    fontSize: 64px
    fontWeight: '800'
    lineHeight: 72px
    letterSpacing: -0.03em
  display-xl-mobile:
    fontFamily: Bricolage Grotesque
    fontSize: 40px
    fontWeight: '800'
    lineHeight: 48px
    letterSpacing: -0.02em
  headline-lg:
    fontFamily: Bricolage Grotesque
    fontSize: 44px
    fontWeight: '700'
    lineHeight: 52px
    letterSpacing: -0.02em
  headline-lg-mobile:
    fontFamily: Bricolage Grotesque
    fontSize: 30px
    fontWeight: '700'
    lineHeight: 38px
    letterSpacing: -0.01em
  headline-md:
    fontFamily: Bricolage Grotesque
    fontSize: 28px
    fontWeight: '700'
    lineHeight: 36px
    letterSpacing: -0.01em
  headline-sm:
    fontFamily: Bricolage Grotesque
    fontSize: 20px
    fontWeight: '700'
    lineHeight: 28px
  body-lg:
    fontFamily: Inter
    fontSize: 18px
    fontWeight: '400'
    lineHeight: 28px
  body-md:
    fontFamily: Inter
    fontSize: 15px
    fontWeight: '400'
    lineHeight: 24px
  body-sm:
    fontFamily: Inter
    fontSize: 13px
    fontWeight: '400'
    lineHeight: 20px
  label-lg:
    fontFamily: Inter
    fontSize: 14px
    fontWeight: '700'
    lineHeight: 20px
    letterSpacing: 0.02em
  label-md:
    fontFamily: Inter
    fontSize: 12px
    fontWeight: '700'
    lineHeight: 16px
    letterSpacing: 0.04em
  label-sm:
    fontFamily: Inter
    fontSize: 11px
    fontWeight: '600'
    lineHeight: 14px
    letterSpacing: 0.05em
rounded:
  sm: 0.25rem
  DEFAULT: 0.5rem
  md: 0.75rem
  lg: 1rem
  xl: 1.5rem
  full: 9999px
spacing:
  gutter: 1.5rem
  gutter-sm: 1rem
  margin: 3rem
  margin-sm: 1.25rem
  space-xs: 0.25rem
  space-sm: 0.5rem
  space-md: 1rem
  space-lg: 1.5rem
  space-xl: 2.5rem
---

## Brand & Style
This design system defines the visual language for a Motion Designer & Illustrator portfolio. It merges early 2000s Pop-Vector exuberance with structural Neubrutalism and tactile 16-bit arcade aesthetics. The tone is kinetic, self-assured, unapologetically vivid, and immaculately structured.

The visual narrative relies on high-energy contrast: hyper-saturated tones contained inside stark, structural ink outlines. The UI serves both as an electric exhibition space for dynamic motion work and a reliable client conversion engine. Micro-interactions should feel tactile, snappy, and physical—reminiscent of mechanical push-buttons, screen-printed stickers, and vintage gaming cabinet interfaces.

## Colors
The palette balances vibrant neon pop accents against dense inks and paper whites. Surfaces avoid subtle tinting or diffuse gradients; fills are solid, punchy, and deliberate.

- **Primary Pop Pink (`#FF3B7B`)**: Primary calls to action, featured project labels, and active interactive states.
- **Secondary Arcade Yellow (`#FFDE59`)**: Accent tags, highlight containers, sticker badges, and hover state transformations.
- **Tertiary Sky Blue (`#00C2FF`)**: Client category badges, tool tags, and secondary interactive cues.
- **Lime Green Accent (`#40C057`)**: Availability status indicators, playback triggers, and success alerts.
- **Pure White (`#FFFFFF`)**: Card surfaces, input backgrounds, and crisp typographic baseline areas.
- **Dark Navy (`#0E1329`)**: Main canvas background or secondary high-contrast structural sections.
- **Deep Black (`#000000`)**: Structural ink borders, hard drop-shadows, and primary display typography.

## Typography
Typographic rhythm relies on the tension between dynamic, quirky display headings and disciplined, neutral body text.

- **Headlines (Bricolage Grotesque)**: Selected for its bold, expressive ink-traps and chunky geometric flavor that mimics pop-art prints and modern vector branding. Headlines should be rendered in tight letter spacing with deliberate weight to anchor each section.
- **Body & Labels (Inter)**: High legibility for long-form case studies, metadata tables, project timelines, and navigational links. Neutral structure ensures the content never competes with the motion clips or illustrations.

## Layout & Spacing
The layout follows a 12-column responsive fluid grid on desktop (`>1024px`) shifting to an 8-column layout on tablet (`768px - 1023px`) and a 4-column layout on mobile (`<767px`). 

Sections use stark separation with visible horizontal rules (`2px-3px solid #000000`) or alternating background blocks. Portfolio item tiles adopt asymmetric modular sizing to create a posterized, editorial rhythm rather than a monotonous grid.

## Elevation & Depth
Depth in this design system rejects blurry, gradual lighting drops. Hierarchy is communicated through rigid, hard-edged isometric offset shadows:

- **Baseline Level (Ground)**: Flat UI elements, canvas backgrounds, and inline dividers carry no shadow.
- **Resting Interactive Surfaces**: Cards, buttons, and popover modules utilize a `3px 3px 0px #000000` hard shadow with a `2px solid #000000` or `3px solid #000000` border.
- **Hover State**: Elements push outward or translate upwards, increasing the hard shadow to `5px 5px 0px #000000` while shifting `-2px, -2px`.
- **Active / Pressed State**: Elements translate directly into the shadow origin (`3px 3px`), removing the drop shadow completely (`0px 0px 0px #000000`) to evoke a mechanical micro-switch press.

## Shapes
The structural system uses a hybrid geometry:
- **Panels, Media Players, and Cards**: Configured with a distinct `8px` to `12px` border radius (`roundedness: 2`), ensuring corners feel polished yet distinctly outlined.
- **Badges, Tags, and Pill Counters**: Strict `9999px` full capsule rounding to introduce organic, sticker-like counterpoints to rectangular cards.
- **Borders**: All primary component boundaries must carry an explicit `2px` or `3px` solid `#000000` border.

## Components

### Buttons
- **Primary Action**: Background `#FF3B7B`, text `#FFFFFF`, border `3px solid #000000`, shadow `3px 3px 0px #000000`, radius `8px`. On hover: background `#FFDE59`, text `#000000`, translate `(-2px, -2px)` with shadow `5px 5px 0px #000000`. On active: translate `(3px, 3px)` with `0px` shadow.
- **Secondary Action**: Background `#FFFFFF`, text `#000000`, border `3px solid #000000`, shadow `3px 3px 0px #000000`, radius `8px`.
- **Arcade Icon Trigger**: Square `44px x 44px`, background `#00C2FF` or `#FFDE59`, border `2px solid #000000`, hard shadow `3px 3px 0px #000000`.

### Badges & Category Chips
- Rendered as capsule pills (`border-radius: 9999px`) with `2px solid #000000` ink outlines and no dropshadow at rest.
- Background tokens map directly to specialization areas: `#00C2FF` for Motion Graphics, `#FFDE59` for 2D Illustration, `#40C057` for 3D/VFX, and `#FFFFFF` for client names.

### Project Cards
- Surface: `#FFFFFF`, outer border: `3px solid #000000`, radius: `12px`, shadow: `4px 4px 0px #000000`.
- Thumbnail/Video Container: Framed internally with an inner `2px solid #000000` lower divider. Aspect ratios are fixed to 16:9 or 4:3.
- Metadata Bar: Displays pill tags, project title in Headline-SM, and an interactive hover arrow trigger.

### Form Inputs & Fields
- Surface: `#FFFFFF`, border `2px solid #000000`, radius `8px`, shadow `2px 2px 0px #000000`.
- Focused state: Border changes to `3px solid #000000`, shadow expands to `4px 4px 0px #FF3B7B`. Placeholder text in muted dark navy `#0E1329` at 50% opacity.

### Interactive Reel Player / Media Frame
- Mimics a physical arcade monitor or sticker-laden sketchbook frame: solid `#0E1329` outer rim, `3px solid #000000` outer border, corner decorative crosshairs (`+`), and custom neon timeline scrubbers using `#FF3B7B` and `#FFDE59`.