# RavilCrypto Web Design Code — v1.0

Reusable system for editorial strategy guides and educational product pages. The STRC page is the first reference implementation.

## Product principles
- Lead with a clear promise and the important qualification in the same first screen.
- Build a narrative: context → mechanism → practical route → risks → checks → primary sources → next step.
- Each section adds a new answer. Avoid repeated feature cards, filler, fabricated testimonials, and unsupported claims.
- Make financial figures time-stamped. Separate issuer terms, live market quotes, user-authored claims, and editorial interpretation.
- Every action link should go to a verified first-party page or the exact protocol market. Never invent or guess a route, token address, Telegram CTA, performance number, or user's result.
- Product access, eligibility, custody, and jurisdiction checks appear before any transaction instruction.

## Visual language
- Premium, modern, editorial; calm confidence rather than trading-terminal noise.
- Dark evergreen/graphite canvas with warm off-white text. Acid lime is the action/highlight color; pale blue marks neutral information; restrained orange signals risk.
- Use soft light gradients, hairline borders, generous negative space, translucent glass only for small floating labels, and rounded cards (18–30 px). Do not put every content block in a card.
- Create one memorable hero visual that explains the subject. Prefer bespoke CSS/SVG diagrams and data metaphors over generic stock photos or coin piles.
- No fake Apple logo/product UI and no implication of Apple sponsorship.

## Type and layout
- System sans-serif stack by default; no external font dependency for portable HTML.
- Large, tightly tracked headline; 1–2 short lines; body copy at comfortable 16–18 px on desktop and 15–16 px on mobile.
- Content max width 1160 px; desktop uses 12-column-like split compositions and varied section layouts; mobile becomes one column at 820 px.
- Paragraph measure stays readable. Use generous section rhythm (68–92 px) and visible hierarchy.

## Interaction and accessibility
- Mobile-first responsive layout; key actions and source links remain visible and tappable.
- Semantic landmarks, descriptive links, high contrast, visible textual meaning beyond color, keyboard focus support, reduced-motion support.
- Motion must explain hierarchy or provide feedback; no autoplay, parallax dependence, or decorative movement that competes with reading.
- External links use `target="_blank" rel="noreferrer"` where appropriate.

## Financial-content guardrails
- Show the as-of date adjacent to every volatile quote. Prefer wording such as “current observed rate” and “market snapshot”; never call variable rates guaranteed.
- Distinguish APY from realized holding-period return, and an underlying-denominated result from USD return.
- State the maturity, fees, slippage, liquidity, smart-contract, issuer/custody, redemption, and regional eligibility considerations relevant to the actual route.
- Don’t imply a tokenized representation is the underlying share or grants shareholder rights unless official product terms say so.
- Explain that target/par value is not a floor or redemption guarantee.
- Link primary documentation beside the relevant claims, plus a source section at the end. Refresh volatile numbers before publishing or trading.
- Make education/disclosure clear without burying the key risk in a footer.

## STRC page tokens (reference)
```css
:root {
  --bg: #101410;
  --panel: #171d18;
  --ink: #f3f2e9;
  --muted: #a4ada2;
  --line: rgba(236,242,220,.13);
  --acid: #d5ff5f;
  --blue: #9ad9ff;
  --orange: #ff9d66;
  --max: 1160px;
  --radius: 26px;
}
```

## QA checklist before any future site goes live
1. Read every claim against its cited primary source and timestamp it.
2. Validate the entire CTA route and jurisdiction language.
3. Check responsive layouts at 390 px, 768 px, and desktop width.
4. Check headline, body contrast, focus states, link names, and reduced-motion behavior.
5. Confirm there are no placeholders, invented testimonials, broken destinations, stale APYs, or unsupported guarantees.
6. Review the page as a funnel: source/video → clear learning → safe next step → measurable CTA.
