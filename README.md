# MasterComm International — Website

A static, professional website for an independent technology advisor. No build
step, no framework — just HTML, CSS, and a little JavaScript. Deploys to Vercel
instantly.

## Pages
| File            | Purpose                                            |
|-----------------|----------------------------------------------------|
| `index.html`    | Home                                               |
| `about.html`    | About                                              |
| `services.html` | Services / practice areas                          |
| `process.html`  | The MasterComm Method — 8-phase engagement framework |
| `contact.html`  | Contact + request form                             |
| `styles.css`    | Design system (fonts, colors, components)          |
| `script.js`     | Mobile menu + scroll animations                    |
| `logo.svg`      | Compass-star logomark (also used as favicon)       |

## Brand at a glance
- **Fonts:** Bricolage Grotesque (headlines) + Libre Franklin (body), loaded from Google Fonts.
- **Colors:** deep royal navy base, bright gold (`--gold`) for power/value, crimson (`--crimson`) for passion. All defined in the `:root` block at the top of `styles.css` — change them there and the whole site updates.
- **Logo:** a faceted compass star. Symbolism — the compass = guidance/trust; the rising gold-to-crimson gradient = aspiration meeting passion; nodes at the cardinal tips = network/referrals; the seal ring = enterprise credibility; the glowing core = the insight at the center of every engagement.

## First edits to make
Search every `.html` file and replace:
- `hello@mastercomm.example` -> your real email
- `+1 (000) 000-0000` and `+10000000000` -> your real phone
- `City, State` / `Country` in `contact.html` -> your address
- The `300+` / stat figures in `index.html` if you want different proof points.

## Turning the contact form into a real form (optional)
The form currently opens the visitor's email client. To capture submissions
automatically, create a free Formspree account and wrap the fields in
`contact.html` with `<form action="https://formspree.io/f/XXXX" method="POST">`.

## Deploy
Push to a GitHub repo, import into Vercel. Vercel auto-detects a static site —
no configuration needed. (Full step-by-step was provided separately.)
