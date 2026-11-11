# Fitness & Nutrition

This repository contains:
- `index.html`: existing workout-plan page, left unchanged
- `nutrition.html`: public, read-only nutrition dashboard
- `nutrition.json`: source-of-truth food log, coach targets and daily activity log

## Public dashboard
`https://sandypuns.github.io/fitness/nutrition.html`

GitHub Pages publishes from `main` and the repository root.

## Coach plan is the nutrition source of truth
Daily targets: **2,140 kcal, 153 g protein, 207 g carbohydrates, 79 g fat and 26 g fibre**.

Daily whey protocol: **2 scoops**, one with breakfast and one as the evening snack. These are part of the coach's meal plan; the "no supplements" note refers to other external supplements.

Current weight: **70.1 kg** (user-confirmed 11 November 2026).

## Logging workflow
Send meal photos and descriptions in the ChatGPT Fitness and Diet conversation. Food estimates will be added to `nutrition.json` and `nutrition.html` will be refreshed. Cooking oil is estimated as part of the dish; it is not added again as a separate entry unless the user confirms it is additional.

At the end of each day, share:
- The workout actually completed (and duration or other stats, when available)
- Step count
- Sleep duration (and optional sleep notes)

These are recorded in that date's `workouts`, `steps`, `sleepHours`, `sleepNotes` and `activityNotes` fields. The dashboard never assumes a workout from the planned schedule.

## Privacy
This repository is public. Anyone can view and copy its files. The nutrition dashboard intentionally displays the current weight because the user requested it. Avoid adding sensitive medical information or private notes.

## Estimates
Calories and macros are estimates from meal photos and descriptions. Mixed dishes, cooking fats, brands and serving sizes create uncertainty. Meal suggestions remain guidance based on the coach's plan and the food already logged; confirm substantive changes with your coach.
