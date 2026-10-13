# NutriCalix

A web application for food recognition and nutrition tracking. It estimates calories and macronutrients (protein, carbs, fat, fiber) from meal photos and helps track daily food intake.

This is an ongoing project currently in development (final submission planned after December).

## Features

- **Food Scanner**: Upload or drop a photo of a meal to analyze its nutritional content.
- **Nutritional Breakdown**: Estimates calories and macronutrients along with simple dietary tips.
- **Daily Dashboard**: Log scanned meals to track total daily calories and macros with progress bars.

## Project Structure

```
nutricalix/
├── frontend/
│   ├── index.html
│   ├── scan.html
│   ├── css/
│   │   └── style.css
│   └── js/
│       └── app.js
└── README.md
```

## Running Locally

No installation or dependencies required.

**Option 1: Python simple server**
```bash
python -m http.server 3000 --directory frontend
```
Then open `http://localhost:3000` in your browser.

**Option 2: Direct file open**
Open `frontend/index.html` directly in any browser.

## Tech Stack

- HTML5
- CSS3
- JavaScript (ES6)

## Future Work

- Backend integration for real-time model inference
- Export daily food intake reports
- Multi-dish plate support
