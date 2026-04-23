# Hydrogene Vert Event Landing Page

<p align="center">
  <img src="logo.svg" alt="Hydrogene Vert logo" width="96">
</p>

<p align="center">
  A premium one-page event website concept for a green hydrogen scientific conference.
</p>

> Status: Collaborative front-end build  
> UI language: French  
> Documentation language: English

## Overview

This repository contains a static landing page designed for a green hydrogen event. The project focuses on strong visual direction, responsive layout work, and a custom Three.js scene integrated directly into a single-page experience.

Instead of using a generic event template, the site leans into a more editorial presentation with layered textures, atmospheric color treatment, wave dividers, motion details, and a 3D visual that reinforces the energy theme.

This codebase is part of a collaborative work forked from [Morta-dev-git](https://github.com/Morta-dev-git) to give me more free space and full access during development, before sending the updates back upstream through a pull request that was merged.

## Highlights

- Premium visual direction with a custom identity, organic palette, and typography pairing
- Responsive single-page structure for event information, programme, committees, registration, and contact
- Interactive Three.js wind turbine scene rendered in the intro section
- Timeline-based programme layout for the full event schedule
- Scroll-triggered reveal animations and polished hover states
- Mobile navigation behavior tailored for smaller screens
- Lightweight stack with no framework and no build step

## Tech Stack

- HTML5
- CSS3
- Vanilla JavaScript
- Three.js loaded through an import map
- OrbitControls from the Three.js examples package
- Google Fonts
- Font Awesome

## Project Structure

```text
.
|-- index.html          # Main landing page
|-- style.css           # Layout, visual system, animations, responsive styles
|-- 3D_WindFarm.js      # Active Three.js scene used on the page
|-- 3D_Molecule.js      # Alternate 3D concept kept in the repo
|-- logo.svg            # Source vector logo
 \-- img/                # Local image assets used by the page
```

## Running Locally

No installation or build process is required.

1. Start a simple local server from the project root:

```bash
python3 -m http.server 8000
```

2. Open `http://localhost:8000` in your browser.

Opening `index.html` directly may work, but serving the folder locally is the safer option for module-based scripts and asset loading.

## What This Project Demonstrates

- Brand-forward front-end design without relying on a framework
- Careful CSS composition for an event-focused landing page
- Custom 3D work in plain JavaScript rather than stock decorative media
- A complete one-page event experience with clear visual hierarchy

## Notes

This repository was used as the working fork so development could move more freely with full access.

Some content inside `index.html` still reads like demo or placeholder event data, including parts of the committee list, registration URL, and contact information. If the site is reused for a real event, those values should be replaced before deployment.
