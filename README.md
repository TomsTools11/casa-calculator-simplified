# CASA Peptide Calculator (Simplified)

A streamlined, browser-based peptide reconstitution calculator that helps users determine the correct dosing for reconstituted peptides. Built as a single-page application with no dependencies — just pure HTML, CSS, and JavaScript.

## Features

- **Extensive Peptide Database** — Pre-loaded with 50+ commonly used peptides including BPC-157, Semaglutide, Tirzepatide, GHK-Cu, and many more
- **Smart Autocomplete Search** — Quickly find peptides by typing partial names with real-time dropdown suggestions
- **Automatic Calculations** — Instantly computes the volume to inject (in units and mL) based on peptide vial size, bacteriostatic water volume, and desired dose
- **Syringe Visual Guide** — Displays a visual syringe representation showing exactly where to draw to for accurate dosing
- **Dose Presets** — Each peptide comes with recommended dosing ranges that auto-populate for convenience
- **Mobile-Responsive Design** — Clean, modern dark-themed UI that works on desktop and mobile devices
- **Multiple Calculator Versions** — Includes both a simplified and original version of the calculator

## Project Structure

```
├── index.html                    # Main calculator (full-featured version)
├── simple-casa-calculator.html   # Simplified calculator version
├── original-casa-calculator.html # Original calculator version
└── vercel.json                   # Vercel deployment configuration
```

## Getting Started

### Option 1: Open Locally
Simply open `index.html` in any modern web browser — no server or build step required.

### Option 2: Deploy to Vercel
The project includes a `vercel.json` configuration for easy deployment:
1. Fork or clone this repository
2. Connect it to [Vercel](https://vercel.com)
3. Deploy — the config routes all traffic to `index.html` by default

## How to Use

1. **Select a Peptide** — Type a peptide name into the search box or browse the dropdown list
2. **Enter Vial Size** — Input the peptide vial size in milligrams (auto-filled from the database)
3. **Enter BAC Water Volume** — Specify how much bacteriostatic water you used to reconstitute (in mL)
4. **Set Desired Dose** — Enter your target dose in micrograms (mcg) or select a preset
5. **View Results** — The calculator displays the exact volume to draw in both insulin units and mL, along with a visual syringe guide

## Technologies

- **HTML5** — Semantic markup and structure
- **CSS3** — Modern styling with CSS variables, flexbox, and responsive design
- **Vanilla JavaScript** — All logic handled client-side with no frameworks or dependencies

## License

This project is open source. See the repository for license details.
