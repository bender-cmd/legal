# TechInvasion and Safe2gether site

TechInvasion homepage, donation page, and static legal pages for **Safe2gether — Connected. Protected. Together.**

The repository is configured for GitHub Pages with the custom domain
`techinvasion.co.za`.

## Publish

1. Push the `main` branch to a public GitHub repository.
2. Open **Settings → Pages**.
3. Select **Deploy from a branch**, then choose `main` and `/(root)`.
4. Configure the DNS records required by GitHub Pages.
5. Enable **Enforce HTTPS** after GitHub provisions the certificate.

Published paths:

- `/privacy/`
- `/terms/`
- `/data-deletion/`

- `/donation/payment/`

The donation page links to the owner's Paystack hosted checkout:
`https://paystack.shop/pay/slal2u9ww3`.
The mobile app links to `https://techinvasion.co.za/donation/payment/`, so the
checkout destination can be updated here without an app release.
Never include Paystack secret keys in this static site.
