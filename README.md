# Massachusetts Tobacco Page — Verdict Section Redesign

Complete page built from the user's uploaded files (index-12.html /
style-14.css — which already include the redesigned "Why Clients
Choose" section) with the verdict section ("The Massachusetts
Tobacco Lawsuit" / $200,000,000 / Walter Kelley) redesigned the same
way. Everything else is untouched.

## Files

- `index.html` — the full page (your index-12, one section swapped
  + one footer link repointed)
- `css/style.css` — your style-14, with the new section rules appended
- `images/` — all nine uploaded images, so the folder is self-contained
  for every local image reference (the CSS parallax backgrounds still
  point at their absolute majusticehelp.com URLs, as in your files)
- `section-verdict.html` + `section-verdict.css` — the section alone,
  if you'd rather paste just the section into your own files

## What changed

Only the verdict section and the appended CSS. Copy is verbatim from
your uploaded files.

1. **Header order fixed** — the kicker ("Massachusetts Tobacco
   Verdict") now sits above the headline, then the headline, then the
   $200M figure.
2. **One heading, one figure** — the $200,000,000 is now a 64px serif
   display number with a green $, not a second `<h2>` stacked under
   the title. The "Recent verdict obtained by..." line and the
   "Prior results do not guarantee a similar outcome." note sit
   directly under it.
3. **One coherent text column** — the intro paragraphs ("Did You Start
   Smoking as a Teenager...") and the Free Case Review / 100%
   Confidential / No Fee Unless We Win checklist now live in the text
   column with the header, instead of sitting in separate containers
   below the grid with a stray `<br>` between them.
4. **Portrait arranged like the section below it** — Walter Kelley's
   photo is now a framed card with a light-green offset outline (the
   same treatment as the hospital photo in "Why Clients Choose"),
   and his name and title sit on a white card overlapping its
   bottom-left corner — instead of a bare photo in a narrow column
   with a plain caption underneath.
5. **Typo fixed** — `<stong>` is now `<strong>` on "Find out if you
   qualify." (it was rendering as unbolded text).

## The duplicate id is fixed

Your file had TWO sections with `id="conditions"` (this one and "Why
Clients Choose"). This section is now `id="verdict"`, and the footer
link "About the Lawsuit" now points to `#verdict` — it still lands on
the same section, so nothing changes for visitors. The "Why Clients
Choose" section keeps `id="conditions"`.

## Notes

- New CSS is scoped to `.verdict-*` classes and uses the page's
  existing variables (--navy #122a48, --gold #009a44, --gold-light
  #8bc34a) and classes (.qualifier-list, .prior-results).
- Mobile (≤900px) stacks the columns, figure at 48px, name card still
  overlapping the photo.
- The file's other pre-existing markup quirks (unclosed span in the
  About heading) were left untouched.
