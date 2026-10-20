# Done Right Solutions LLC — handoff at ~60%

**Live:** https://10elizabethbell.github.io/doneRightSolutions/ · **Repo:** https://github.com/10elizabethbell/doneRightSolutions · **Built:** 2026-10-19 from Muse brief (run 2026-10-20, thin brief)

## What's built
- One page, phone first, calm band style: paper header (check-mark logo, "Done Right / Solutions LLC", tap-to-call (937) 407-9540 top right) → photo hero → services → the job start to finish → free-estimate form with 3 steps → closing band → footer.
- Palette from their logo: slate circle → bands (#303945, deep #1e252e with the faint line texture), brick-red check (#a92403) → the one accent, used as a fill **with white text** (7:1). The calm style's rule is "navy text on a gold fill"; red can't carry dark text, so this is the brand-driven exception. On dark bands the red becomes #ff9a82 so it passes contrast.
- Hero: their own power trowel on fresh concrete (frame from their job video), under a slate overlay; separate phone (portrait) and desktop (wide) crops. White text samples ≥8.5:1 on phone, 7.8:1 on desktop; the coral "done right." ≥3.8:1 (large text).
- H1: "Concrete work, done right." with the letter bounce-in; the `.rise` fade-up; the floating red text circle (shows after the hero, hides at the form).
- Services: Basement floors / Garage slabs / Patios / Something else — the rows jump to the form and pre-pick that job.
- Work: four stills from the same video in order (base packed → barrier and steel → poured → finished slab), 2-up on phones, 4-up on desktop, then a red "Click to see more of our work." Facebook row.
- Form: job chips, name, town (optional), notes (optional) → composes a text to Kasey; asks them to add a photo of the spot before sending. Tested: pre-select, empty-name error, composed message decodes correctly, fallback line appears.
- Favicon / home-screen icon: the logo's check-in-circle redrawn as an SVG (the logo crop overlaps the lettering). og:image 1200×630 with the hero photo.

## Assumptions I made
- **No location anywhere**, per Muse's flag (service area unconfirmed). This breaks the calm style's "place in the H1" rule on purpose. **Strong lead:** the Facebook page's own title reads "Done Right Solutions LLC | Urbana OH" (fetched 2026-10-19). If Kasey confirms, the H1 becomes e.g. "Concrete done right in Urbana." and the close gets "Based in Urbana, OH".
- "Outdoor Services" is their own branding — it's on the logo's banner. Used in the footer; header shows "Done Right / Solutions LLC" to fit a 360px phone.
- Voice is "we" (the post says "we're ready…"), with Kasey named as the contact. Crew size unknown.
- The video is theirs (posted with their sign-off). All four work photos and the hero are one job (an insulated-form floor slab). No people, plates or house numbers in the crops; the house above the walls is cropped out along with the burned-in "NEED CONCRETE WORK?" caption.
- Work-card stage titles ("Base packed", etc.) are kept from the kit's work cards. They're short labels, not captions, but if they read as captions to you they're one line each to delete.

## Placeholders and gaps
- Service area, hours, years in business, email (footer has none — rule says don't invent one), reviews, prices, Instagram.
- Only one job's photos. Patios and garage slabs have no photos.
- Business-name variant to confirm: "Done Right Solutions LLC" vs "…Outdoor Services LLC".

## Questions for the owner
1. Where do you work (towns / how far you travel)? — unlocks the H1 and close.
2. Name on the site: "Done Right Solutions LLC" or "Done Right Solutions Outdoor Services LLC"?
3. Photos of patios, garage slabs, driveways, steps — and any before/after pairs?
4. Anything else you pour or do (driveways, sidewalks, steps, removal, "hardscaping" from your hashtags)? Each becomes a service row.
5. Insured? Years doing concrete? Any customer reviews we can quote?
6. Email for the footer, if you want one.

## Ideas not built (yours to pick)
- **Runner-up world / opt-in signature motion: drag to trowel.** The hero as wet concrete; dragging a finger floats it smooth and glossy in the path, like the power trowel in their video, then it slowly "sets". Other worlds considered: saw-cut control joints that draw themselves across the bands as you scroll; a rebar/wire-mesh grid that settles under the hero; gravel compacting under a plate; broom-finish texture on the close band.
- Photo intake: a real upload needs a backend (or a form service). With a small serverless endpoint, the form could take photos and text Kasey a link — a natural first paid upgrade.
- Before/after slider once they have a pair (cracked old slab → new).
- Location-based H1 (see Assumptions).
- Impeccable findings deliberately not applied (Ellie's calm-style choices): eyebrow pills, the letter bounce-in, the floating text circle, Cal Sans, the faint diagonal stripe texture (detector flags `repeating-stripes-gradient`). The detector's `cramped-padding` on the work cards is a false positive (photo cards with an inset overlay title).

## Not verified
- Real-device touch and the real `sms:` hand-off on iOS and Android (checked in headless Chromium + WebKit; composed message decodes correctly).
- Facebook in-app browser specifically.
- Frame rate of the bounce-in on old phones.
- Whether the Facebook profile URL (`profile.php?id=100069736130812`) opens the business page for logged-out visitors (Muse flagged it as not API-readable).
