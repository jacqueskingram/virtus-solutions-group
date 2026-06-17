# Virtus Solutions Group LLC Website

A clean, professional static landing page for **Virtus Solutions Group LLC**, designed for an early-stage government contracting and professional services business.

The site is built to present Virtus as a credible, vendor-ready company while keeping the messaging simple, accurate, and flexible as the business grows.

## Live Site

Planned domain:

```text
govirtus.net
```

## Project Purpose

This website serves as the public landing page for Virtus Solutions Group LLC. It is intended to help visitors quickly understand:

- Who Virtus Solutions Group LLC is
- What services the company provides
- The company’s public-sector and government contracting focus
- How to contact the business

The first version is intentionally simple. As the business becomes fully approved, registered, and active, the site can be expanded with additional details such as a capability statement, NAICS codes, certifications, phone number, and vendor information.

## Current Sections

The landing page includes:

1. **Hero Section**  
   Introduces Virtus Solutions Group LLC with a strong, professional message.

2. **About Virtus**  
   Explains the meaning behind “Virtus” and the values behind the business: strength, excellence, character, and capability.

3. **Services**  
   Highlights broad service areas such as technical support, project coordination, documentation, administrative support, and vendor/subcontractor support.

4. **Government & Public Sector Support**  
   Positions Virtus for federal, state, local, and prime contractor opportunities.

5. **Contact Section**  
   Provides the business email address and a simple contact path.

## File Structure

```text
virtus-website/
├── index.html
├── styles.css
├── script.js
├── README.md
└── assets/
    ├── virtus-logo.png
    ├── logo-full.png
    ├── favicon-32.png
    ├── favicon-180.png
    └── favicon-512.png
```

## Files Explained

| File | Purpose |
|---|---|
| `index.html` | Main website content and page structure |
| `styles.css` | Colors, layout, typography, responsive design, and visual styling |
| `script.js` | Small interactive features, including mobile menu behavior and footer year |
| `assets/virtus-logo.png` | Primary logo image used on the site |
| `assets/logo-full.png` | Full logo version for larger branding use |
| `assets/favicon-32.png` | Browser tab favicon |
| `assets/favicon-180.png` | Apple/mobile icon |
| `assets/favicon-512.png` | Larger app/icon version |

## Brand Direction

The website uses a professional color scheme inspired by the selected Virtus logo:

- Navy blue
- Gold
- Silver/gray
- White

The desired brand tone is:

- Professional
- Trustworthy
- Government-contracting friendly
- Clean and modern
- Strong without being flashy
- Broad enough for future services

## Contact Email

Current business email:

```text
admin@govirtus.net
```

This email is used on the landing page. It can be replaced later with role-based inboxes such as:

```text
info@govirtus.net
contracts@govirtus.net
support@govirtus.net
```

## GitHub Pages Deployment

To publish this site using GitHub Pages:

1. Create a GitHub repository for the website.
2. Upload the contents of this folder to the root of the repository.
3. Make sure these files are at the top level of the repo:
   - `index.html`
   - `styles.css`
   - `script.js`
   - `assets/`
   - `README.md`
4. In GitHub, go to **Settings**.
5. Go to **Pages**.
6. Under **Build and deployment**, select:
   - Source: **Deploy from a branch**
   - Branch: **main**
   - Folder: **/root**
7. Save the settings.
8. GitHub will generate a temporary GitHub Pages URL.
9. Test the website at the temporary URL before connecting the custom domain.

## Custom Domain Setup

Planned custom domain:

```text
govirtus.net
```

After GitHub Pages is working:

1. Go to **Settings > Pages** in the GitHub repository.
2. Enter `govirtus.net` in the **Custom domain** field.
3. Save.
4. Go to the domain provider where `govirtus.net` was purchased.
5. Add the DNS records GitHub recommends.
6. Wait for DNS propagation.
7. Enable **Enforce HTTPS** once GitHub allows it.

## Important Notes Before Going Fully Public

Since Virtus Solutions Group LLC is newly filed and waiting on final processing, avoid adding unconfirmed information to the website.

Do **not** add these until confirmed:

- EIN
- UEI
- CAGE code
- NAICS codes
- Government certifications
- Insurance information
- “Federal contractor” language
- Claims about contracts won
- Claims about years in business under Virtus

Safe language for now:

- “Positioned to support government and public-sector opportunities”
- “Professional and technical support services”
- “North Carolina-based professional services company”
- “Focused on reliable execution, documentation, and support”

## Future Improvements

Potential future additions:

- Capability statement download
- NAICS and PSC codes
- Vendor registration details
- Past performance section
- Certifications section
- Services detail pages
- Contact form backend
- Blog or updates section
- Government contracting opportunity tracker login
- Case studies once work is completed

## Recommended Next Updates

After the LLC is officially approved:

1. Confirm the legal business name exactly as approved.
2. Update the footer and company references if needed.
3. Add the finalized business address or service area.
4. Add a phone number if desired.
5. Begin drafting a capability statement.
6. Add vendor identifiers only after they are issued.

## Maintenance

This is a static website, so most updates can be made by editing:

- `index.html` for wording/content changes
- `styles.css` for design/color/layout changes
- `assets/` for logo and image changes

After making changes, commit and push to GitHub. GitHub Pages should automatically update the live site.

## Business Owner Notes

This website is the first public-facing version of the Virtus brand. The goal is not to look like a large company overnight. The goal is to look organized, professional, reachable, and ready to begin building relationships with agencies, prime contractors, and local business partners.
