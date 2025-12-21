# Screenshots Directory

This directory contains UI screenshots of the prototype dashboard.

## How to Generate Screenshots

### Option 1: Automated (Recommended)

1. Install Playwright:
   ```bash
   cd prototype
   npm install -D @playwright/test playwright
   npx playwright install chromium
   ```

2. Start the dev server:
   ```bash
   cd prototype
   npm run dev
   ```

3. Run the screenshot script:
   ```bash
   node scripts/generate-screenshots.js
   ```

### Option 2: Manual

1. Start the prototype:
   ```bash
   cd prototype
   npm run dev
   ```

2. Open `http://localhost:3000` in your browser

3. Navigate through views and take screenshots:
   - **Dashboard Overview** (default page)
   - **Spending** (click "Spending" in sidebar)
   - **Analytics** (click "Analytics" in sidebar)
   - **Optimizations** (click "Optimizations" in sidebar)
   - **Trends** (click "Trends" in sidebar)

4. Save screenshots here with descriptive names:
   - `dashboard-overview.png`
   - `spending-view.png`
   - `analytics-view.png`
   - `optimizations-view.png`
   - `trends-view.png`

## Screenshot Specifications

- **Format**: PNG
- **Resolution**: 1920x1080 or higher
- **Device Scale**: 2x for high-DPI displays
- **Full Page**: Yes (capture entire page, not just viewport)

## Usage in Documentation

Screenshots are referenced in the main README.md file. Update the README if you add new screenshots or change naming conventions.

