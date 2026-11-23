# Selina Medical Center — React + Tailwind CSS

A responsive, frontend-only medical centre website built with React, Vite and Tailwind CSS. The uploaded Selina Medical Center logo is included at `src/assets/selina-logo.jpeg`.

## Run locally

1. Install Node.js (LTS).
2. Open a terminal in this project folder.
3. Install dependencies:
   ```bash
   npm install
   ```
4. Start the development server:
   ```bash
   npm run dev
   ```
5. Open the local URL printed by Vite (normally `http://localhost:5173`).

Create a production build with `npm run build`.

## Website sections

- Home / hero
- About Selina Medical Center
- General Dentistry
- General Practice
- Dermatology
- Laser & Aesthetic Treatments
- Why choose us
- Multilingual care
- Appointment enquiry form
- Contact / footer

## Before publishing — important customisation

This is a frontend prototype. The appointment form currently validates the fields and displays a demo confirmation; it does **not** send or store appointments. Connect it to the clinic's booking platform, email service or backend before going live.

Please replace or confirm the following clinic details before publishing:

- Official phone / WhatsApp number and email address (not supplied in the uploaded overview).
- Exact street address and map pin. The overview refers to Mohamed Bin Zayed City on page 1 and Mussafah on page 3, so confirm the correct public-facing location.
- Opening days and hours.
- Doctor names, photographs, qualifications and professional licence details (not supplied).
- Social media profile URLs.

The services, facility descriptions and language list are based on the supplied Facility Overview. General promotional copy and layout are design additions. Stock photographs are loaded from Unsplash and require an internet connection; replace them with approved clinic photography when available.

## Stack

- React
- Vite
- Tailwind CSS 3
- Lucide React icons
