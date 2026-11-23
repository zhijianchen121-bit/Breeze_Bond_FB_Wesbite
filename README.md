# Breeze_Bond_FB_Wesbite

## Breeze Bond Cleaning Form

A responsive English bond-cleaning enquiry page styled to match the Breeze Domestics website.

### Publish with GitHub Pages

1. Open **Settings → Pages**.
2. Set **Source** to **Deploy from a branch**.
3. Select **main** and **/(root)**, then **Save**.
4. Wait for the Pages deployment and use the **Visit site** link shown by GitHub.

The page is `index.html`; `.nojekyll` lets GitHub serve it directly. No build or installation is required. The official logo, banner photo and Metropolis regular/bold fonts are embedded in the HTML, so it does not depend on external asset loading.

### Enquiry delivery

The form validates the property and contact details, then prepares an email draft addressed to **admin@breezedomestics.com.au**. Customers must press **Send** in their own email app. They can attach property photos there. A copy-to-clipboard alternative is provided.

This version does not automatically submit, store enquiries, confirm bookings or connect to a database. It never reports a message as delivered. The form prevents native submission when JavaScript is unavailable.

### Contact and branding

- Website: https://breezedomestics.com.au/
- Public enquiries: admin@breezedomestics.com.au
- Phone: 1300 584 385
- Brand colour: `#262262`; secondary grey: `#707070`

The public contact settings are in `BREEZE_CONFIG` near the end of `index.html`.
