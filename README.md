# Medicinal Lifestyle — free GitHub Pages development demo

This is a separate static prototype, preserving the original storefront/admin design and product photographs. No server, npm, Render account, payment or database credentials are needed.

## Upload and publish
1. Upload the **docs folder** from this ZIP to your GitHub repository. You can keep your existing server source alongside it. Ensure `docs/index.html` exists, not `docs/docs/index.html`.
2. For GitHub Free, use a public repository containing no secrets.
3. Repository Settings → Pages → Source: Deploy from a branch → Branch: main → Folder: /docs → Save.
4. Wait for the Pages deployment under Actions to succeed. Use the URL displayed under Settings → Pages.
5. For repository `medicinal-lifestyle-store`, the usual URL is https://subsubanjreduardo.github.io/medicinal-lifestyle-store/ . For a repository named `subsubanjreduardo.github.io`, it is https://subsubanjreduardo.github.io/ .
6. Open `admin.html` from the Demo admin link to edit the demo. Sign in as the sample customer to demonstrate checkout. Initial stock is fictional: 15 per variant.

GitHub documentation: https://docs.github.com/en/pages/getting-started-with-github-pages/configuring-a-publishing-source-for-your-github-pages-site

## Scope
Products, inventory history, content, settings, orders and reviews use browser localStorage. Price changes, stock deductions, cancellation restoration, scheduling and featured sections can be demonstrated. Images can use HTTPS URLs or small browser-only uploads. Reset demo clears demo data.

This has no real authentication or restricted admin access. Each browser has its own data; admin changes are NOT published to other visitors. No payments, emails, MongoDB, Cloudinary or production orders are connected. Use fictional delivery information. Browser storage can be cleared or fill up. This package is for development demonstrations, not real selling.

The Node server edition remains separate for further backend development. Do not upload secrets, .env files, node_modules or local databases.
