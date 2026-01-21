# JC - Code Validator

A simple web application for reviewing 6-digit codes with specific constraints.

## Features

- Displays 6-digit codes starting with "66"
- Ensures at least 5 unique digits in each code
- Yes/No decision buttons
- Undo functionality after pressing Yes
- Tracks statistics (total reviewed, yes count)
- Clean, modern UI

## Quick Deploy to GitHub Pages

1. Push your code to GitHub:
   ```bash
   git add .
   git commit -m "Add code validator app"
   git push origin main
   ```

2. Enable GitHub Pages:
   - Go to your repository on GitHub
   - Click on **Settings**
   - Scroll down to **Pages** (in the left sidebar)
   - Under **Source**, select **main** branch
   - Click **Save**
   - Your site will be live at: `https://[your-username].github.io/jc/`

## Local Testing

Simply open `index.html` in your browser to test locally.

## How It Works

- **No Button**: Moves to the next code and increments the reviewed count
- **Yes Button**: Marks the code as "Yes", increments both counts, and shows an undo option
- **Undo Button**: Reverts the Yes decision and allows you to continue reviewing the same code
