# Creator Portfolio Demo

A responsive, one-page portfolio website made as a demo for a creator portfolio studio. It uses plain HTML, CSS, and JavaScript, so there is no build step and no package installation.

> **Important:** This is a fictional demo creator profile. The name, follower count, engagement, reach, work examples, and contact email are placeholders. Do not present these details as a real creator or real campaign results.

## Preview locally on Windows

1. Download and extract `creator-portfolio-demo.zip`.
2. Open the extracted `creator-portfolio-demo` folder.
3. Double-click `index.html` to open it in your browser.
4. For a local web server, use one of the options below.

### Option A — Python local server

Open PowerShell in the extracted folder and run:

```powershell
# Start a local web server from this folder.
python -m http.server 8000
```

Then open `http://localhost:8000` in your browser. Stop the server with `Ctrl+C`.

If `python` is not recognized, try `py -m http.server 8000` or install Python from python.org.

### Option B — VS Code Live Server

1. Open the folder in VS Code.
2. Install the **Live Server** extension.
3. Right-click `index.html`.
4. Select **Open with Live Server**.

## Upload to GitHub

1. Create a new empty GitHub repository, e.g. `creator-portfolio-demo`.
2. Extract this ZIP on your computer.
3. Upload the files inside the extracted folder (not the ZIP itself) to the repository root:
   - `index.html`
   - `styles.css`
   - `script.js`
   - `README.md`
4. Commit the files.

## Publish the demo for free with GitHub Pages

1. Open your repository on GitHub.
2. Go to **Settings → Pages**.
3. Under **Build and deployment**, choose **Deploy from a branch**.
4. Choose the `main` branch and `/ (root)` folder, then save.
5. Wait for the Pages deployment to finish. GitHub will show the public website URL on the Pages settings screen.

If you prefer, you can deploy the same static files to Netlify or Cloudflare Pages.

## Customize this demo

Edit `index.html`:
- Replace `Aanya Mehta` with your demo persona or real client's name (with permission).
- Replace `hello@example.com` with the creator's approved business email.
- Replace social profile links with their actual profile URLs.
- Replace the bio and content categories.
- Replace placeholder statistics with verified figures supplied by the creator.
- Replace illustrative images with creator-approved photos or properly licensed assets.

Edit `styles.css`:
- Change the color variables at the top to customize the brand colors.
- Adjust spacing, fonts, and layout as needed.

## Before delivering a client website

- Get written approval for the content and photos.
- Confirm the email address and links work.
- Verify all stats and collaboration claims.
- Explain hosting, domain renewal, revision count, delivery time, and any ongoing maintenance fees.
- Do not ask clients for social media or email passwords.
- Test on mobile and desktop.
