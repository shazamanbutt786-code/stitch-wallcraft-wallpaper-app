# 🎨 WallCraft Wallpaper App — Stitch UI Design System & Mockups

[![WallCraft Design System](https://img.shields.io/badge/Design_System-WallCraft_OLED-7C5CFC?style=for-the-badge)](./wallcraft_dark_mode_ui_ux_color_system.md)
[![Screens](https://img.shields.io/badge/Screens-48_Interactive_Mockups-2DD4BF?style=for-the-badge)](#-screen-catalog)
[![Theme](https://img.shields.io/badge/Theme-OLED_Dark_%26_Breeze_Light-FBBF24?style=for-the-badge)](#-uiux-color-system--tokens)

> High-fidelity UI/UX design specifications, screen mockups, and interactive HTML previews exported from **Stitch** for the **WallCraft** Android & iOS 4K wallpaper application.

---

## 📱 Project Overview

WallCraft is a modern, high-performance mobile wallpaper application designed with:
- **True OLED Dark Mode**: Surface tokens engineered for battery savings and visual depth (`#0B0C10` baseline).
- **Parallax 3D & Live Wallpaper Engine**: Mockups for depth previews, interactive lock screen widgets, and wallpaper setters.
- **AI Wallpaper Studio**: Generative prompt interfaces, neural latent space progress screens, and prompt suggestion chips.
- **Gamified Retention**: 7-day daily check-in streaks, coins/credits rewards, and creator subscriber tiers.

---

## 📂 Repository Structure

Each screen directory includes:
- `code.html`: Interactive, fully styled HTML preview with Tailwind CSS / inline styling.
- `screen.png`: High-resolution device mockup screenshot rendered at phone aspect ratio.

```
stitch-wallcraft-wallpaper-app/
├── wallcraft_dark_mode_ui_ux_color_system.md   # Design tokens & color system
├── discover/                                   # Home discovery feed & trending hero
├── wallpaper_preview/                          # Fullscreen wallpaper preview
├── customize_lock_screen/                      # Clock, widget & depth lock screen
├── crop_position_wallpaper/                    # Aspect ratio crop & alignment tool
├── set_wallpaper/                              # Home, Lock, or Both screen setter
├── set_home_screen_wallpaper/                  # Home screen launcher preview
├── wallpaper_applied_successfully/             # Success confirmation dialog
├── ai_generator/                               # Prompt studio & visual style presets
├── ai_wallpaper_generation_in_progress/        # Diffusion progress & latent loader
├── daily_check_in/                             # 7-Day streak reward calendar
├── categories/                                 # Curated category grid & collections
├── search_results/                             # Search queries & color palette filters
├── saved_items/                                # User favorites & offline collection
├── profile/                                    # Creator profile & verified badges
├── edit_profile/                               # Bio, avatar & social link settings
├── subscription_plans/                         # VIP tier pass & credit packages
├── wallcraft_crystal_logo/                     # Brand vector emblem & crystal mark
├── wallcraft_app_icon_*/                       # Emerald, Ruby, Sapphire, Amber icons
└── ... (48 comprehensive design modules)
```

---

## 🎨 UI/UX Color System & Tokens

For complete specs on surface layering, WCAG AAA contrast ratios, and button glows, refer to [`wallcraft_dark_mode_ui_ux_color_system.md`](./wallcraft_dark_mode_ui_ux_color_system.md).

### Core Palette
- **Canvas Base**: `#0B0C10` (True OLED Dark)
- **Primary Brand**: `#7C5CFC` (Breeze Luminous Purple)
- **Secondary Teal**: `#2DD4BF` (AI / Active Confirmation)
- **Accent Amber**: `#FBBF24` (Daily Streak & VIP Pass)
- **Accent Rose**: `#FB7185` (Favorites & Critical Actions)

---

## 🚀 How to View Locally

Simply open any screen's `code.html` file in any modern web browser or serve via a lightweight HTTP server:

```bash
# Using Python
python3 -m http.server 8080

# Using Node.js
npx serve .
```

Navigate to `http://localhost:8080/discover/code.html` to explore the screens.

---

## 📄 License

Design assets and mockups created with Stitch for WallCraft. Released under the MIT License.
