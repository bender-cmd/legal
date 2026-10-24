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

The donation page shows a coming-soon message until a live checkout is ready.
The supplied Paystack page `https://paystack.shop/pay/slal2u9ww3` displays a
Test Mode warning and must not be used to collect public contributions.
Once a live payment page is supplied, link it from `/donation/payment/` and
activate the mobile app donation button using that stable website URL.
Never include Paystack secret keys in this static site.
