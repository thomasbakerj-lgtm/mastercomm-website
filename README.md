# MasterComm International — Website

A static, professional website for an independent technology advisor. No build
step, no framework — just HTML, CSS, and a little JavaScript. It deploys to
Vercel instantly.

## Files

| File           | Purpose                                  |
|----------------|------------------------------------------|
| `index.html`   | Home page                                |
| `about.html`   | About page                               |
| `services.html`| Services / practice areas                |
| `contact.html` | Contact page with request form           |
| `styles.css`   | All styling (the design system)          |
| `script.js`    | Mobile menu + scroll animations          |

## Customizing — the quick edits

**1. Contact details (do this first).**
Search every `.html` file for these placeholders and replace them:
- `hello@mastercomm.example` → your real email
- `+1 (000) 000-0000` and `+10000000000` → your real phone
- `City, State` / `Country` in `contact.html` → your address

**2. Brand colors.**
Open `styles.css`. At the very top, the `:root` block defines every color.
The gold accent is `--gold`. Change these values to match a logo or brand
palette and the whole site updates.

**3. Copy / wording.**
All text lives directly inside the `.html` files between the tags. Edit freely.

**4. Logo.**
The wordmark is text ("Master**Comm**"). To use an image logo instead, replace
the `.brand` block in each page's header with an `<img src="logo.png">`.

## Turning the contact form into a real form (optional)

Right now the contact form opens the visitor's email client. To collect
submissions automatically, sign up for a free service like Formspree, then
wrap the fields in `contact.html` with a `<form action="https://formspree.io/f/XXXX" method="POST">`
tag. Their docs walk you through it.

## Deploying

Push these files to a GitHub repository, then import the repo into Vercel.
Vercel auto-detects it as a static site — no configuration needed.
