# Fitness & Nutrition

This repository contains:
- `index.html`: existing training plan
- `nutrition.html`: public, read-only nutrition dashboard
- `nutrition.json`: source-of-truth food log and provisional targets

## Publish
In GitHub, open **Settings → Pages**, set **Deploy from a branch**, choose **main** and **/(root)**. The dashboard will be available at:

`https://sandypuns.github.io/fitness/nutrition.html`

If GitHub Pages is already enabled, the page will appear after the commit deploys.

## Logging workflow
Send meal photos and descriptions in the ChatGPT Fitness and Diet conversation. Nutrition estimates will be added to `nutrition.json`, and `nutrition.html` will be refreshed. No website-side food entry or login is required.

## Privacy
The repository is public. Anyone can view and copy its files. The nutrition dashboard and `nutrition.json` do not include current weight or body measurements. The pre-existing `index.html` workout plan contains older references to 69 kg and 25% body fat; these were left untouched to preserve the existing page.

## Estimates
Calories and macros are estimates from meal photos and descriptions. Mixed dishes, cooking fats, brands and serving sizes create uncertainty. Targets are provisional and should be reviewed with a dietician.
