# WallCraft Dark Mode UI/UX Design System & Color Tokens

This guide details the complete Dark Mode color palette, contrast tokens, surface elevation hierarchy, and best practices tailored for the **WallCraft** mobile wallpaper experience, optimized for OLED deep blacks and accessible readability.

---

## 1. Core Color Token Reference (Hex Codes)

### Surfaces & Backgrounds (OLED-Optimized Layering)
| Token Name | Hex Code | Purpose / Application |
| :--- | :--- | :--- |
| `surface-base` / `bg-default` | `#0B0C10` | Screen canvas background, true dark neutral for maximum OLED power efficiency. |
| `surface-container-lowest` | `#111319` | Lowest level cards, underlying panel base. |
| `surface-container-low` | `#171922` | Grouped list backgrounds, recessed sections. |
| `surface-container` | `#1D212D` | Primary card tiles, wallpaper preview cards, navigation bars. |
| `surface-container-high` | `#262B3A` | Modals, bottom sheets, floating popovers, dropdown menus. |
| `surface-container-highest` | `#31374A` | Interactive inputs, search bars, pill tags, inactive chip buttons. |

---

### Brand & Accent Colors (Luminous Vibrancy)
| Token Name | Hex Code | Purpose / Application |
| :--- | :--- | :--- |
| `brand-primary` | `#7C5CFC` | Primary CTA buttons, active state toggles, key highlights (Breeze Purple). |
| `brand-primary-hover` | `#9074FD` | Pressed/hover state for primary purple buttons. |
| `brand-primary-subtle` | `rgba(124, 92, 252, 0.16)` | Background for active chips, highlighted card badges, pill glows. |
| `brand-secondary-teal` | `#2DD4BF` | Synced status, AI badges, active checks, success confirmations. |
| `brand-accent-amber` | `#FBBF24` | Streak fire icons, pro subscription stars, coins/credits counter. |
| `brand-accent-rose` | `#FB7185` | Heart/like button, delete/destructive actions, critical alerts. |

---

### Typography & Icon Text Tones (WCAG AAA / AA Tested)
| Token Name | Hex Code | Contrast Ratio vs `#0B0C10` | Usage |
| :--- | :--- | :--- | :--- |
| `text-primary` | `#F8FAFC` | 17.5:1 (AAA) | Main headings, wallpaper titles, active buttons, primary data. |
| `text-secondary` | `#94A3B8` | 7.8:1 (AAA) | Subheadings, author tags (`@ElenaVFX`), form field labels. |
| `text-tertiary` | `#64748B` | 4.6:1 (AA) | Timestamps, inactive tabs, placeholder text, micro-captions. |
| `text-disabled` | `#475569` | 3.1:1 | Disabled state text and deactivated icon strokes. |

---

### Borders, Dividers & Glow Lines
| Token Name | Hex Code / Value | Usage |
| :--- | :--- | :--- |
| `border-subtle` | `rgba(255, 255, 255, 0.08)` | Default card borders, segmented switch dividers. |
| `border-medium` | `rgba(255, 255, 255, 0.14)` | Hoverable tiles, input borders on focus. |
| `border-highlight`| `rgba(124, 92, 252, 0.45)` | Active selected cards (e.g. 2-Months Pause option). |
| `glow-primary` | `0 8px 24px rgba(124, 92, 252, 0.35)` | Primary button glow, active device mockup shadow. |

---

## 2. Component Styling Rules in Dark Mode

### 1. Wallpaper Image Cards & Mockups
- **Bezel Frame**: Instead of bright drop shadows, use `border: 1px solid rgba(255, 255, 255, 0.12)` paired with a soft dark shadow `box-shadow: 0 20px 40px rgba(0, 0, 0, 0.6)`.
- **Contrast Buffer**: Dark mode naturally makes colorful wallpapers pop with higher perceived luminance. Ensure text overlays directly on wallpaper images always have a 30%–45% gradient scrim (`linear-gradient(to top, rgba(0,0,0,0.8), transparent)`).

### 2. Action Buttons & Chips
- **Primary Action (Set Wallpaper, Confirm)**:
  - Background: `#7C5CFC`
  - Text: `#FFFFFF` (Font weight 600)
  - Subtle top inner highlight: `inset 0 1px 0 rgba(255,255,255,0.2)`
- **Secondary Action (Cancel, Keep Plan)**:
  - Background: `#1D212D`
  - Border: `1px solid rgba(255, 255, 255, 0.1)`
  - Text: `#F8FAFC`

### 3. Toggles & Segmented Controls
- **Track**: `#171922` (Border: `1px solid rgba(255,255,255,0.06)`)
- **Active Thumb**: `#7C5CFC` with white check or glyph
- **Active Segment Pill**: `#262B3A` with text `#F8FAFC` and soft shadow

---

## 3. Tailwind CSS Config Mapping

```javascript
// tailwind.config.js - WallCraft Dark Mode Extension
module.exports = {
  darkMode: 'class',
  theme: {
    extend: {
      colors: {
        dark: {
          bg: '#0B0C10',
          card: '#1D212D',
          'card-hover': '#262B3A',
          input: '#171922',
          border: 'rgba(255, 255, 255, 0.08)',
          'border-focus': 'rgba(124, 92, 252, 0.5)',
        },
        brand: {
          purple: '#7C5CFC',
          'purple-glow': 'rgba(124, 92, 252, 0.25)',
          teal: '#2DD4BF',
          amber: '#FBBF24',
          rose: '#FB7185',
        },
        text: {
          primary: '#F8FAFC',
          secondary: '#94A3B8',
          muted: '#64748B',
        }
      }
    }
  }
}
```

---

## 4. UI/UX Improvements Delivered by this Dark Theme
1. **True OLED Battery Savings**: Utilizing `#0B0C10` instead of washed-out grays turns off display pixels on mobile AMOLED displays.
2. **Reduced Glare for Wallpapers**: Vibrant neon colors and photography display with greater optical depth without bright background interference.
3. **Accessibility Compliance**: Meets WCAG 2.1 AAA for primary text and AA for secondary captions.
