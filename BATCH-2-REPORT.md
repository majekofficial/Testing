# Phademy article expansion, batch 2 checkpoint

Expanded in batch 2: Discount, Date, Countdown, Time Duration, Calorie and Salary calculators.
Batch 1 articles remain unchanged. The five original long articles remain untouched.
Word counts are visible source article text, excluding HTML tags. The expanded target is 2,000 to 3,000 words per article.

| Article | Words | Status |
|---|---:|---|
| age-calculator | 2080 | expanded batch 1 |
| algebra-solver | 618 | not yet expanded |
| area-calculator | 668 | not yet expanded |
| average-calculator | 2011 | expanded batch 1 |
| basic-calculator | 499 | not yet expanded |
| bmi-calculator | 2053 | expanded batch 1 |
| calorie-calculator | 2151 | expanded batch 2 |
| cgpa-calculator | 2611 | protected long article |
| change-of-subject-calculator | 594 | not yet expanded |
| countdown-calculator | 2001 | expanded batch 2 |
| currency-converter | 2024 | expanded batch 1 |
| date-calculator | 2016 | expanded batch 2 |
| density-pressure-calculator | 537 | not yet expanded |
| discount-calculator | 2034 | expanded batch 2 |
| exponent-calculator | 563 | not yet expanded |
| final-grade-calculator | 636 | not yet expanded |
| force-calculator | 581 | not yet expanded |
| fraction-calculator | 2027 | expanded batch 1 |
| gpa-calculator | 3031 | protected long article |
| grade-calculator | 2869 | protected long article |
| gravitation-calculator | 514 | not yet expanded |
| heat-calculator | 539 | not yet expanded |
| inequality-calculator | 535 | not yet expanded |
| lens-mirror-calculator | 690 | not yet expanded |
| linear-equation-calculator | 505 | not yet expanded |
| logarithm-calculator | 552 | not yet expanded |
| matrix-calculator | 562 | not yet expanded |
| momentum-calculator | 563 | not yet expanded |
| motion-calculator | 666 | not yet expanded |
| ohms-law-calculator | 626 | not yet expanded |
| percentage-calculator | 3053 | protected long article |
| permutation-combination-calculator | 577 | not yet expanded |
| projectile-motion-calculator | 660 | not yet expanded |
| quadratic-equation-calculator | 670 | not yet expanded |
| salary-calculator | 2053 | expanded batch 2 |
| savings-goal-calculator | 599 | not yet expanded |
| scientific-calculator | 551 | not yet expanded |
| sequence-calculator | 562 | not yet expanded |
| simple-machines-calculator | 621 | not yet expanded |
| simultaneous-equations-calculator | 548 | not yet expanded |
| slope-calculator | 588 | not yet expanded |
| speed-distance-time-calculator | 482 | not yet expanded |
| statistics-calculator | 634 | not yet expanded |
| study-time-calculator | 3346 | protected long article |
| surd-calculator | 545 | not yet expanded |
| tax-calculator | 505 | not yet expanded |
| time-duration-calculator | 2022 | expanded batch 2 |
| tip-calculator | 523 | not yet expanded |
| unit-converter | 2042 | expanded batch 1 |
| volume-calculator | 596 | not yet expanded |
| wave-calculator | 478 | not yet expanded |
| word-problem-solver | 695 | not yet expanded |
| work-energy-power-calculator | 589 | not yet expanded |

## Progress

- Original long articles protected: 5
- Expanded in batch 1: 6
- Expanded in batch 2: 6
- Remaining short articles: 36
- Total calculator articles tracked: 53

## Batch 2 validation

- All six batch 2 source articles exceed 2,000 words.
- Generated article sections also exceed 2,000 visible words on all six pages.
- Worked examples and formula explanations checked against `source/app.js` calculation logic.
- One H1 per generated HTML page: PASS.
- Duplicate IDs across generated HTML pages: PASS.
- Duplicate H2 headings in batch 2 articles: PASS.
- Local internal links across generated HTML pages: PASS.
- Sitemap XML parses successfully: PASS.
- Two consecutive builds produce identical HTML and sitemap hashes: PASS.
- `phademy.js`, `phademy.css` and `sw.js` remain byte-for-byte identical to the original source ZIP: PASS.
- Prior batch 1 article source files compared with the batch 1 checkpoint: unchanged.
- Live in-browser calculator interaction test: NOT RUN because no browser executable is installed in this environment.
- 390 px visual/sideways-scroll test: NOT RUN for the same reason.

## Notes

- The calorie article explains the Mifflin–St Jeor estimate, activity multipliers and the calculator’s displayed goal-table guardrails. It explicitly states that outputs are not individual medical advice.
- The date, countdown and time-duration articles distinguish elapsed calendar days, countdown rounding and overnight clock-time handling.
- The salary article documents the calculator’s 12-month, 52-week and 260-working-day assumptions, and explains gross/net and pay-frequency limitations.
- The discount article explains sequential discounts, reverse calculations, fees and practical offer comparison.
- No calculator JavaScript, input IDs, canonical URLs, service worker or ad slots were edited.
