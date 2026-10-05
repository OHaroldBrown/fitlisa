# FitLisa

Static site for FitLisa FitLife (Lisa Brown, personal trainer & nutritionist). Plain HTML + one stylesheet, hosted on GitHub Pages.

## To finish
- **Contact form:** in `contact.html`, replace `YOUR_FORM_ID` with your Formspree form ID.
- **Booking:** in `coaching.html`, point the "Get in touch" button at Calendly/Acuity when ready.
- **Photos:** drop images in `images/` and update the `src` attributes in `gallery.html` and `about.html`.
- **Custom domain:** see "Pointing fitlisa.com" below.

## Pointing fitlisa.com
1. Repo Settings → Pages → Custom domain → `fitlisa.com` (this adds a `CNAME` file).
2. At the domain registrar, set DNS:
   - `A` records for `@`: 185.199.108.153, 185.199.109.153, 185.199.110.153, 185.199.111.153
   - `CNAME` for `www` → `oharoldbrown.github.io`
3. Once the certificate is issued, tick "Enforce HTTPS".
