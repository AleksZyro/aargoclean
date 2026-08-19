# AARGO Clean GmbH

Static company website for AARGO Clean GmbH. The site uses plain HTML, CSS and a small amount of JavaScript. It has no build step, package dependencies, backend or contact form.

## Local preview

Open `index.html` directly in a browser or serve the folder with any static web server.

## Vercel

- Framework Preset: `Other`
- Root Directory: `./`
- Build Command: leave empty
- Output Directory: `.`

## Content status

The current hero image is a temporary generated placeholder and should be replaced with an approved original company photo later. Service descriptions are intentionally broad and must be confirmed with the company before the final launch.

The website only links to `info@aargoclean.ch` through `mailto:`. No mail records, MX records, domain transfer or nameserver changes are part of this repository.

The current website does not set cookies and does not include analytics, tracking, external maps, embedded videos or third-party fonts. If any of these are added later, `datenschutz.html` must be reviewed before deployment.

## Publishing references

The reference section in `index.html` is fully styled but hidden. Before removing its `hidden` attribute:

1. Add approved original project photos under `assets/references/` and replace each `.reference-media` placeholder with an `<img>` element containing meaningful alternative text.
2. Confirm the service category, project description and location with AARGO Clean GmbH.
3. Obtain documented permission from the customer before publishing their name, logo, property or identifiable project details.
4. Use only genuine customer wording for testimonials. Record whether the customer's full name, company name or an anonymous label such as `Privatkundschaft, Region Aarau` may be shown.
5. Remove unused reference cards and then remove the section's `hidden` attribute.

Public company details were checked against the commercial-register information available through Moneyhouse and the 2026 ZPK cleaning-industry company list.
