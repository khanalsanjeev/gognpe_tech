GONGPE TECHNOLOGIES WEBSITE

READY-TO-PUBLISH STATIC WEBSITE

1. Upload the contents of this folder to the root of your GitHub Pages repository (or your hosting web root).
2. If you have your brand files, create an assets folder and place these files inside it:
   - assets/favicon.ico
   - assets/favicon.png
   The HTML references these exact paths. The ZIP intentionally does not include substitute logo files.
3. Enable GitHub Pages for the repository as usual.

Tailwind CSS is already compiled into assets/css/tailwind.css. The live website does not load the Tailwind CDN and does not need Node.js, npm, or a build step on GitHub Pages. The compiled CSS is served as a normal static file.

OPTIONAL: FOR FUTURE DESIGN/HTML CHANGES

This project uses Tailwind CSS v4.1.10.
- Install Node.js, then run: npm install
- For automatic CSS rebuilding while editing: npm run dev
- Before publishing changes: npm run build

Commit the updated assets/css/tailwind.css along with your HTML changes. Do not upload node_modules.

Google Fonts are still loaded externally from Google Fonts. The site remains functional if those fonts are unavailable, using the declared sans-serif fallbacks.

Deployment URL configured in the page: https://tech.gongpe.com/
Contact email: support@gongpe.com
