# Build a Portfolio
I have built a responsive website that will display images. links and description.
This is my portfolio project.

## How to Run the App

1. Install dependencies:
   ```bash
   npm install
   ```

2. Start the application:
   ```bash
   npm start
   ```
   
   This will serve the app from the `dist` folder and automatically open it in your browser at http://localhost:8080

## Development

To compile SCSS files to CSS:
```bash
npm run sass
```

This will watch for changes in the `scss` folder and automatically compile them to `dist/css/`

## Deployment

### Automatic Deployment (Recommended)

The app is automatically deployed to GitHub Pages whenever changes are pushed to the `main` branch via GitHub Actions workflow.

The site will be available at: `https://[username].github.io/modern_portfolio/`

You can also manually trigger the deployment from the Actions tab in the GitHub repository.

### Manual Deployment

Alternatively, you can manually deploy using:
```bash
npm run deploy
```

# Files Included

* index.html
* main.css in css folder
* Gruntfile.js
* img folder
* dist folder (contains the built application)
* package.json
