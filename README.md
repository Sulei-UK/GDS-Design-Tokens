# GOV.UK Design Tokens (W3C Format)

[![W3C Standard](https://img.shields.io/badge/Standard-W3C_DTCG-blue.svg)](https://www.w3.org/community/design-tokens/)
[![Design Tool](https://img.shields.io/badge/Designed_for-Penpot-black.svg)](https://penpot.app/)
[![License: OGL](https://img.shields.io/badge/License-OGL_v3.0-lightgrey.svg)](https://www.nationalarchives.gov.uk/doc/open-government-licence/version/3/)

A comprehensive, community-maintained set of design tokens for the **[GOV.UK Design System (GDS)](https://design-system.service.gov.uk/)**, complete with multi-brand theming support for government sub-agencies.

These tokens are mapped from the official GOV.UK Frontend Sass variables and formatted to the **W3C Design Tokens Community Group (DTCG) specification**. They are ready to be imported directly into **Penpot**, Style Dictionary, Tokens Studio, or any other tool that supports the modern JSON token standard.

## 📦 What's Included

The `master-tokens.json` file contains the core foundational layer of the GOV.UK design language, plus specific brand overrides:

* **Base & Semantic Colours:** The complete GDS extended palette and applied semantic tokens (e.g., `semantic.link.hover`, `semantic.focus.background`).
* **Spacing Scale:** The official 9-step GDS spacing scale (0px to 60px).
* **Typography:** Core font families (GDS Transport), scales, line-heights, and pre-packaged composite Text Styles (e.g., `heading-xl`).
* **Borders & Shadows:** Standardised border widths and the specific, hard-edged drop shadows used for GDS buttons and high-contrast focus rings.
* **Brand Themes:** Pre-configured theme overrides for **NHS**, **Ministry of Justice (MoJ)**, and **MoneyHelper**, allowing you to instantly swap colour palettes and typography across your designs.

## 🚀 How to use with Penpot

Because these tokens use the W3C draft specification and Penpot's nested `/` naming convention, Penpot will automatically organize them into folders.

### 1. Importing the Tokens
1. Download or clone this repository.
2. Open your workspace in **[Penpot](https://penpot.app/)**.
3. Navigate to the **Design Tokens** panel on the left-hand sidebar.
4. Click the **Tools/Menu icon** (three dots) within the Tokens panel.
5. Select **Import** and upload the `master-tokens.json` file.
6. Penpot will automatically build your `GDS-Tokens` base set and a `sub` folder containing the MoJ, NHS, and MoneyHelper themes.

### 2. Activating a Theme
To swap your designs from the base GOV.UK style to a specific agency brand:
1. In the Design Tokens panel, click **Create one** next to **THEMES**.
2. Name your theme (e.g., "NHS Mode").
3. In the setup list, set `GDS-Tokens` to **Source**.
4. Set your chosen brand (e.g., `sub/nhsTheme`) to **Enabled**.
5. Save the theme. You can now toggle this theme on and off from the dropdown to instantly re-style your components!

## 🛠️ Repository Structure

```text
├── master-tokens.json    # The core W3C-formatted tokens containing GDS base + all themes
├── README.md             # This documentation file
