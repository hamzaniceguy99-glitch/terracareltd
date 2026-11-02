# Terra Care — terra care ltd

Static marketing site (HTML / CSS / JS, no build step) hosted on GitHub Pages
at `terracareltd.shop`.

> Generated from `C:\Users\souha\coaching-sites-factory` (content file `sites/terracareltd.mjs`).
> To change the content, edit that file and run `node build.mjs terracareltd` — editing the
> HTML here directly would be overwritten on the next build.

## Before you promote this site

| Priority | What | Where |
|---|---|---|
| 🔴 Blocking | Legal page: fill every `[BRACKET]` (legal name, address, state, payment provider). Have a lawyer review it if you can. | `legal.html` |
| 🟠 Important | `contact@terracareltd.shop` doesn't exist yet: set up free email forwarding in Namecheap (*Domain List → Manage → Redirect Email*). | Namecheap |
| 🟠 Important | Contact form: replace `VOTRE_ID_FORMSPREE` with your Formspree id (until then it falls back to `mailto:`). | `contact.html` |
| 🟠 Important | Add a real introduction of the coach (name, background, photo). Never invent credentials. | `about.html` |
| 🟡 Later | Prices ($£[AMOUNT] / $£[AMOUNT] / $Declined) and plan contents should match what you actually sell. | `index.html` `#pricing` |
| 🟡 Later | Testimonials: only add real ones, with permission. Fake reviews are illegal (FTC). | — |

## Business description (Stripe, directories…)

```
Terra Care Ltd is an agricultural holding company based in Chapel-en-le-Frith in the High Peak, formed in 2018. We hold and oversee agricultural interests rather than farm them, and the distinction matters: the contracts, the employment, the subsidy entitlements and the operating liability all sit with the farming businesses themselves, not with us. The phrase agricultural holding does two jobs in this country and confusing them is expensive. It describes a holding company like ours, and it also describes tenanted farmland under the Agricultural Holdings Act 1986. Which of the two statutes a tenancy sits under decides almost everything about it. A tenancy under the 1986 Act generally carries lifetime security and statutory succession rights through up to two generations, while a farm business tenancy granted under the 1995 Act carries neither, ending on its term with notice. The same field, the same soil, the same yield, and a materially different value depending on which Act applies to the piece of paper. So the first thing we establish about any land is which one that is. Site: terracareltd.shop
```

## Structure

```
index.html            Home: hero, programs, method, pricing, approach, FAQ
programs.html         The four programs in detail
about.html            How we work, principles
contact.html          Contact form
legal.html            Business info, privacy policy, terms of service
404.html              Error page (absolute paths)
assets/css/style.css  Brand colors at the top, shared styles below
assets/js/main.js     Menu, theme, animations, form
```

## DNS (Namecheap → Advanced DNS)

Delete the parking records, then add:

| Type | Host | Value |
|---|---|---|
| A Record | `@` | `185.199.108.153` |
| A Record | `@` | `185.199.109.153` |
| A Record | `@` | `185.199.110.153` |
| A Record | `@` | `185.199.111.153` |
| CNAME Record | `www` | `hamzaniceguy99-glitch.github.io.` |
