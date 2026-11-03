# Process: Identity Card, Order and Rupture

Dania Altman · Homework Assignment 1

> **Before submitting:** the parts marked ✍️ need your own words, sketches or photos.
> The brief asks for rupture "the model could not have known", and only you can supply that.

---

## 1. The concept: the encounter

**The grid is the plan. The cats are what actually happens.**

The page has three layers, and each one comments on the others:

| Layer | Where on the page | Language |
|---|---|---|
| **Templatology** | *Exhibit A*, near the top | The AI's default: centered hero, purple gradient, 16px rounded cards, Inter, marketing copy. Each default gets a red label and the whole thing is crossed out by hand. |
| **Order** | *Fig. 1 Identity card*, *Fig. 3 Position* | A Swiss grid: 12 columns, one grotesque, one red. Every number is written in the margin. |
| **Rupture** | The windows desktop, camera roll, yearbook, contact, BYE-BYE header, and the intrusions on the grid (Tova, Sofi, poppy seeds, blue marker) | Weingart / Carson / 1999-web punk, built from my real photos, cats, kids, baking. |

**How they meet (not side by side):**
- The grid columns stay visible under everything, including the chaotic desktop. The mess never erases the order.
- Drag a window and let go: it **snaps to the nearest column but keeps its tilt**. The order catches the rupture without taming it.
- Tova lies on the ID card, Sofi sits in the margin of the position text, and poppy seeds are scattered over every ordered section.
- Blue marker (rupture) edits the strict text: "~~feel~~ *weight*", "~~perfect~~ *boring*". **Red belongs to the system, blue belongs to me.**
- The template is shown first and refused. The real "hero" is at the very bottom of the page.

**The encounter is playable.** The visitor holds both sides and feels the difference:
- **The cat dial** (Fig. 1, field 04): a slider from 0 to 4 cats. At 0 the ID card is perfectly Swiss, every field on the baseline, and the margin admits "grid integrity: 100%. never observed in the wild." Each cat that lands on the card knocks the fields a little further out of line (a rotation and offset scaled by the number of cats), but the grid lines never move. 4 cats is labelled "a normal day".
- **The passport photo** (Fig. 1): click it to see the five rejected attempts: smiling, eyes closed, 7am, not facing the camera, holding a Kinder egg. The regulated format against the real face.
- **Tidy up** (Fig. 2): the order gets one button. It aligns every window to a column, zero tilt, in neat rows. Then Sofi walks across the desktop and knocks each window back as she passes. Order can be imposed, for about seven seconds.
- **Shake the dough** (the baking window): poppy seeds fly out of the window and land on the rest of the page, including the Swiss sections. The counter stops saying "everywhere" and starts counting.
- Snapping a window to a column makes a small click. Order is something you can hear.

---

## 2. Order: every measurement chosen

| Decision | Value | Why |
|---|---|---|
| Grid | 12 columns, 4 on mobile | 12 divides into halves, thirds and quarters, so the ID card can use 3 columns for the photo, 9 for data, and 3×3 for the fields. |
| Gutter / margin | 24px / 48px (16 / 16 on mobile) | Multiples of the 8px baseline. The margin is exactly 2 gutters. |
| Baseline | 8px | Every line-height and vertical space is a multiple of 8. |
| Typeface | **Archivo**, one family only | A grotesque in the Akzidenz line (Müller-Brockmann's family), not Inter. Inter is the template's default, so using it would be accepting a default. |
| Type scale | 13 / 17 / 26 / 40 / 96 / 176 | Roughly ×1.5 per step: label, body, field value, heading, display, name. |
| Colour | ink `#111`, paper `#fff`, red `#E3000F` | Only these three, but used as **whole colour fields** like Müller-Brockmann posters: the ID card is a red field with white type, the position text is black. A first version had them as a thin red accent on white and it looked sad and pale next to the rupture, so the order had to be as loud as the mess to hold its own. |
| Alignment | Flush left, ragged right | The opposite of the template's centered hero. The eye starts at the top left, by decision. |
| Photos | Natural ratio, never cropped or stretched | My real photos stay true. The weirdness lives in the layout, not in distorting people or cats. |

## 3. Templatology vs. conscious modernism

| | Template (Exhibit A) | Modernist order (Fig. 1, Fig. 3) |
|---|---|---|
| Alignment | Centered because that's the default | Flush left on a 12-column grid |
| Type | Inter (already there) | Archivo, chosen for its lineage |
| Corners | 16px radius everywhere | Square. A rule is a 2px line |
| Colour | Gradient `#667eea → #764ba2` | Ink, paper, one red |
| Copy | "Passionate designer crafting delightful experiences" (fits anyone) | Facts: name, age, household, what I make |
| Ideology | None: the look of order without the belief | Clarity, honesty, a reason for every measurement |

---

## 4. What the AI suggested, and how I responded

The site was built with Claude Code (an AI coding assistant). The git history records every step.

| # | The AI suggested / did | My response | Commit |
|---|---|---|---|
| 1 | An "anti-design" page: reversed order, draggable fake Windows, runaway buttons, a contact form that knocks the page over. **All illustrations were AI-generated** (Magnific). | Kept the structure, but generated pictures can't be "personal material". | `bbd7c3e` |
| 2 | More gimmicks: fake loader, seasick tilt, melting, googly eyes, talking letters, DO NOT PRESS. | Kept them, and asked for the content to be **about me**: my details, cats, baking, the "AI vs reality" window. | `fa464a0` |
| 3 | — | **Replaced every generated picture with my own photos and my four real cats.** | `41217ae` |
| 4 | The AI made the photos "weird" by stretching, inverting and hue-shifting them. | **Refused.** Distortion is a cheap way of looking messy. My photos keep their real proportions and colours, and the rupture moves into the layout. | `8aa6094` |
| 5 | Hostile cursor tricks: photo trail, nav links running away, a fact button that always dodges. | Too hostile to use. Normal cursor, the button dodges once, slower melting. Rupture shouldn't block reading. | `66dbca2` |
| 6 | Photos cropped to fit boxes. | Stopped cropping. Photos are shown whole. | `4015e20` |
| 7 | **My critique of the whole result:** it was 100% rupture. There was no real order and no position against templatology, so it was only a style. | Added Exhibit A (the template, labelled and refused), the Swiss ID card, the visible grid under the desktop, windows snapping to columns, and the position text. | `(order commit)` |
| 8 | After the order went in, I asked for the site to be **more fun**. The AI's first instinct would have been more random chaos (more pop-ups, more noise). | We put the fun into the **encounter** instead: the cat dial on the ID card, the rejected passport photos, the tidy-up button that Sofi undoes, and the dough that scatters seeds onto the grid. Every new toy is a control over how much rupture lands on the order. The first placement of the new cats covered the card's text; they were moved into empty red so the rupture never blocks reading. | this commit |
| 9 | I said it still wasn't funny, and asked for **Magnific pictures of the cats** and **more typography**. | Made six pictures with Magnific, each generated from a real photo of the actual cat so it is Sofi, Moffi, Toffy and Tova and not generic cats: Tova as a passport officer stamping REJECTED (she appears when the ID photo is rejected), Sofi as a 1960s Swiss designer ruling a grid (she sits next to the position text as "head of order", beside the real Sofi, "head of rupture"), Moffi as a lawyer (legal_dept.exe, OBJECTION), Toffy as a 1999 webmaster (webmaster.jpg), the four of them in a boardroom presenting "Q3 fish allocation & zoomies" (the LinkedIn window), and Tova as pastry chef belly up in poppy seeds (the baking window). These are not "AI illustrations instead of personal material": cats in suits is a thing I actually make, and every picture starts from my own photo. Added Fig. 2½, an unauthorised type specimen: the order has one face in six sizes, so each cat took a different display face (Bungee Shade, Monoton, Press Start 2P, Shrikhand). ORDER is set in Archivo and refuses to scramble when clicked; everything else scrambles. A box lets the visitor set their own text, one random face per letter. | this commit |
| 10 | I asked for **Hebrew**, because I love Hebrew. | Hebrew is the most personal rupture available: the model's default site is in English and nothing else. Added שבת שלום as the biggest word in the type specimen, a שבת_שלום.exe window (every Friday: Saint-Honoré instead of challah, the cats object), תעודת זהות and דניה אלטמן on the ID card, Hebrew in the marquee, the bye-bye header, the footer and the contact form. The type box accepts Hebrew and only gives Hebrew letters faces that actually contain Hebrew (Suez One, Karantina, Rubik, Amatic SC), so it never falls back to a system default. Clicked Hebrew words are spoken in Hebrew. | this commit |

✍️ **Add here:** in your own words, the moment you realised the AI's first instinct was either a template or "random weird", and what you felt about it.

---

## 5. Manual work and raw materials

- **Real photos** (`images/`): me (deadpan, asleep, laughing, 7am selfie, dancing at a wedding, the sandwich in Germany, the Kinder egg), my cats Sofi, Moffi, Toffy and Tova, my own baking (Saint-Honoré, cherry pastry, poppy-seed dough), and my AI art of cats in suits.
- **AI pictures of my cats** (`images/cat-*-officer|designer|lawyer|webmaster|chef.jpg`, `cats-boardroom.jpg`): made with Magnific from the real photos above. Prompts and the reasons for each scene are in row 9 of the table.
- **Metadata** was stripped from all photos (no location).
- ✍️ **Sketches:** scan or photograph your paper sketches of the grid and the encounter and put them in `docs/sketches/`. Then link them here, for example `![first grid sketch](sketches/grid-01.jpg)`.
- ✍️ **Handwork:** if you can, replace the Permanent Marker font with a scan of **your own handwriting** (the blue notes). That is the most "non-replicable" upgrade available.
