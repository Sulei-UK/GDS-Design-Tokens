# GOV.UK Design Tokens (W3C Format)

[![W3C Standard](https://img.shields.io/badge/Standard-W3C_DTCG-blue.svg)](https://www.w3.org/community/design-tokens/)
[![Design Tool](https://img.shields.io/badge/Designed_for-Penpot-black.svg)](https://penpot.app/)
[![License: OGL](https://img.shields.io/badge/License-OGL_v3.0-lightgrey.svg)](https://www.nationalarchives.gov.uk/doc/open-government-licence/version/3/)

A comprehensive, community-maintained set of design tokens for the **[GOV.UK Design System (GDS)](https://design-system.service.gov.uk/)**. 

These tokens are mapped from the official GOV.UK Frontend Sass variables and formatted to the **W3C Design Tokens Community Group (DTCG) specification**. They are ready to be imported directly into **Penpot**, Style Dictionary, Tokens Studio, or any other tool that supports the modern JSON token standard.

## 📦 What's Included

The `gds-tokens.json` file contains the core foundational layer of the GOV.UK design language:

* **Base Colours:** The complete extended GOV.UK colour palette (Red, Green, Blue, Purple, Tints, etc.).
* **Semantic Colours:** Aliased tokens for applied usage (e.g., `semantic.text.primary`, `semantic.link.hover`, `semantic.focus.background`).
* **Spacing Scale:** The official 9-step GDS spacing scale (0px to 60px).
* **Typography:** Core font families (GDS Transport), static font sizes matching the GDS typographic scale, line-heights, and weights.
* **Borders:** Standardised border widths, including specific requirements for focus states and error summaries.

## 🚀 How to use with Penpot

Because these tokens use the W3C draft specification (`$value` and `$type`), Penpot can parse them natively, including all semantic aliases.

1. Download or clone this repository.
2. Open your workspace in **[Penpot](https://penpot.app/)**.
3. Navigate to the **Design Tokens** panel on the left-hand sidebar.
4. Click the **Tools/Menu icon** (three dots) within the Tokens panel.
5. Select **Import**.
6. Upload the `gds-tokens.json` file.

Penpot will automatically build your token library, linking your semantic tokens directly to your base colour palette. 

## 🛠️ Repository Structure

```text
├── gds-tokens.json       # The core W3C-formatted design tokens
├── README.md             # This documentation file
