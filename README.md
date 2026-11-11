# Fitness & Nutrition

Public nutrition and activity dashboard:
https://sandypuns.github.io/fitness/nutrition.html

## Coach-led nutrition target
2,140 kcal · 153 g protein · 207 g carbs · 79 g fat · 26 g fibre.
Two whey scoops daily: one with breakfast and one as the evening snack.
Current weight: 70.1 kg.

## Logging
Send meal photos/descriptions in ChatGPT. Food estimates, cooking oil included within dishes, daily activity, steps and sleep are maintained in `nutrition.json`.

Additional nutrient monitoring includes sodium, free/added sugars, saturated fat, fibre and caffeine. Values not reasonably estimable from photos are stored as unknown rather than zero. The dashboard distinguishes known subtotals from complete daily totals.

## General reference points used
- Sodium: less than 2,000 mg/day for adults (WHO).
- Free sugars: less than 10% of energy, ideally 5% (WHO).
- Saturated fat: less than 10% of daily energy (WHO).
- Fibre: 26 g/day per the coach's plan; WHO advises at least 25 g/day for adults.
- Caffeine: up to 400 mg/day is not generally associated with negative effects for most adults (FDA).

These are broad reference points, not individualized medical limits.

## Privacy
The repository is public. The dashboard displays current weight because the user requested it. Avoid adding medical details or other sensitive data.

## Accuracy
Calories and macros are estimated from meal photos. Sodium, sugars, saturated fat and fibre are especially difficult to infer from mixed dishes without recipes, brands or package labels. Unknown values remain blank rather than being treated as zero.


## Daily photo gallery
Meal and drink photos are stored as compressed thumbnails under `photos/YYYY-MM-DD/` and referenced from the corresponding date in `nutrition.json`. The dashboard gallery changes with the selected date. Thumbnails are indicative, not high-resolution originals.
