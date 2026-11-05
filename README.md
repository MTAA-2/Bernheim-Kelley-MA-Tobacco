# Massachusetts Tobacco Lawsuit Landing Page — GitHub Pages (static) version

A static (HTML + CSS only, no PHP) version of the **Massachusetts Tobacco Lawsuit** landing page for **Bernheim Kelley**, rebuilt from the correct reference files you uploaded (`index-2.php` — the tobacco page's PHP source with the full content from the firm's intake documents — plus `style-11.css` and its README), in the same file structure as the previous GitHub builds. Per your clarification, the **content and goals come entirely from the tobacco files**; the only things cross-referenced from the BioZorb page are the **Bernheim Kelley branding logo and law firm information**, since it is the same firm.

## Content (all from the tobacco files / intake documents)

- Hero: the page config's headline — "Did You Start Smoking as a Teen — and Get Diagnosed with Cancer or COPD?" — and its subhead (Massachusetts smokers and their families can still hold the tobacco companies accountable; free, confidential case reviews for smokers diagnosed in the last four years).
- Why Clients Choose Bernheim Kelley: the $200 million Massachusetts verdict (Walter Kelley and Colleen Ryf; $25M medical/pain-and-suffering, $5M × five children, $150M punitive) with the intake guide's honest framing (most cases settle for more modest amounts), the "Built to Take On Big Tobacco" point, and the free, no-obligation review.
- About the Lawsuit: industry knowledge and concealment from 1957, free sample packs to minors, "light"/"ultralight" deception, and the Master Settlement Agreement not barring individual suits.
- Do You Qualify: the five intake qualifiers as cards — lives in Massachusetts; began smoking 1957 or later, ideally before 18; diagnosed within the last 4 years with lung cancer, throat cancer, mouth cancer, COPD, emphysema, or bladder cancer; or a loved one who died from one of those within 4 years; free sample packs / "light" cigarettes as a case-strengthener.
- Deadlines band: statute of limitations — three years from diagnosis (four in certain circumstances); a loved one's death generally within the last four years.
- Questions Answered: all six FAQs from the intake guide (still able to sue in MA, MSA, comparative negligence under-50% rule, light cigarettes, what must be proved, getting started/deadline).

## Bernheim Kelley branding (cross-referenced from the BioZorb page only)

From personaljusticeclaim.com, the firm's BioZorb page — this also fills the four placeholders the tobacco documents never contained:

- **Logo:** the firm's real logo file, `personaljusticeclaim.com/images/bernheim-kelley-battista-injury-lawyers-logo-home.webp`, in the visible header (`.logo-size`, 115px/80px) and footer (150px).
- **Phone:** 617-468-5342 — header ("Need Immediate Assistance?"), and footer ("Call us for immediate help."). (Note: the phone count in the header/footer follows the BioZorb page.)
- **Address:** Bernheim Kelley Injury Lawyers, 1212 East Broward Blvd, 3rd Floor, Fort Lauderdale, FL 33301.
- **Disclaimer:** the BioZorb page's verbatim text — "THIS IS ATTORNEY ADVERTISING sponsored by Bernheim Kelley Injury Lawyers. This website is an attorney advertisement. Prior results do not guarantee a similar outcome. No representation is made that the quality of legal services to be performed is greater than the quality of legal services performed by other lawyers." — plus its call/text consent paragraph. © 2026 Bernheim Kelley Injury Lawyers.
- **Design:** the Bernheim Kelley palette and serif headlines from the BioZorb static build (dark navy `#122a48`, near-black hero, firm green `#009a44` accents, green CTA `#44974e`, light gray band), so the two firm pages match. Nothing else was taken from BioZorb — no BioZorb subject content, video, or form appears on this page.

## Form, pixel, and placeholders

- **Form embed:** the tobacco files never had a real form URL (it was a marked placeholder), so the form card carries your current framework MTAA embed, `forms.mtaa.ai/f/nf_14bb49f057af4602b5676b8892df3c32` — swap that one line in `index.html` when a tobacco-specific form exists. The card is the usual overflow container: it hangs past the hero over the section below and scrolls internally (`overflow: auto`) if the embed runs tall.
- **Pixel:** your current framework Meta Pixel (`1238664640565416` + ViewContent line) and the MTAA CIPA block.
- **Pictures/parallax:** the About section's side image is a placeholder (`images/REPLACE-TOBACCO-IMAGE.jpg`), and both parallax background lines are placeholders in `css/style.css` (`YOUR-IMAGE-URL-HERE` in the hero block, `YOUR-IMAGE-URL-HERE-2` in the qualify block; overlay tinted to the near-black hero tone).

## Files

```
github-massachusetts-tobacco-landing-page/
├── index.html
├── css/style.css
└── README.md
```

Publish the same way as the other GitHub pages: upload to a repo keeping the structure, Settings → Pages → deploy from branch (root). Note: the static BioZorb build from the previous (mistaken) brief is still in `github-bernheim-kelley-biozorb-landing-page/` if you want it; this tobacco page is the corrected retry of that task.
