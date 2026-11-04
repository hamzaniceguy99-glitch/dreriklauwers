# Dr. Erik Lauwers — dr. erik lauwers bv

Static marketing site (HTML / CSS / JS, no build step) hosted on GitHub Pages
at `dreriklauwers.shop`.

> Generated from `C:\Users\souha\coaching-sites-factory` (content file `sites/dreriklauwers.mjs`).
> To change the content, edit that file and run `node build.mjs dreriklauwers` — editing the
> HTML here directly would be overwritten on the next build.

## Before you promote this site

| Priority | What | Where |
|---|---|---|
| 🔴 Blocking | Legal page: fill every `[BRACKET]` (legal name, address, state, payment provider). Have a lawyer review it if you can. | `legal.html` |
| 🟠 Important | `contact@dreriklauwers.shop` doesn't exist yet: set up free email forwarding in Namecheap (*Domain List → Manage → Redirect Email*). | Namecheap |
| 🟠 Important | Contact form: replace `VOTRE_ID_FORMSPREE` with your Formspree id (until then it falls back to `mailto:`). | `contact.html` |
| 🟠 Important | Add a real introduction of the coach (name, background, photo). Never invent credentials. | `about.html` |
| 🟡 Later | Prices ($On request / $Room-dependent / $Excluded) and plan contents should match what you actually sell. | `index.html` `#pricing` |
| 🟡 Later | Testimonials: only add real ones, with permission. Fake reviews are illegal (FTC). | — |

## Business description (Stripe, directories…)

```
We are the practice of Dr. Erik Lauwers, registered for medical specialist activities and based in Wijnegem in the province of Antwerp since 2009. This page is information rather than advertising, because the rules governing what a doctor may say publicly exclude comparisons with other practitioners, claims of superiority, patient testimonials and promises about outcomes. Two things are worth stating plainly instead. The first is that a specialist title in Belgium is an official recognition granted after approved training, not a description a practitioner may simply adopt, which is why the recognition appears on the legal page rather than as a loose claim. The second concerns money, and it is the point patients most often discover too late. For a hospital stay, fee supplements are prohibited in a two-bed room and in a common room, and that prohibition applies regardless of the doctor's own agreement status. In a single room, supplements may be charged within the limits the hospital applies. So what you pay is determined not only by which doctor treats you but by which room you accepted, and the financial conditions appear in the admission declaration you sign before admission rather than in the invoice afterwards. Site: dreriklauwers.shop
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
