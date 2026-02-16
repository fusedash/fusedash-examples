# Contributing to Fusedash Examples

Thanks for your interest in contributing. This repository hosts public examples, templates, and demo datasets related to Fusedash dashboards, charts, maps, real-time monitoring, AI chat, and storytelling reports.

Website: https://fusedash.ai/

## What you can contribute
- Example ideas for dashboards, charts, maps, and storytelling reports
- Prompt examples for AI Chat workflows
- Small demo datasets (CSV) that are safe to share publicly
- Fixes or improvements to existing documentation

## How to contribute
### Option 1: Suggest an example (no files needed)
1. Open an Issue.
2. Use this format:
   - **Use case:** (team + goal)
   - **KPIs:** (5 to 12 metrics)
   - **Dimensions:** (segments for drilldowns, for example: channel, region, product, cohort)
   - **Time grain:** (daily/weekly/monthly)
   - **Notes:** (anything important to interpret the data)

### Option 2: Add a dataset (CSV)
1. Add your dataset to `/datasets/`.
2. Follow the naming convention:
   - `sample-[topic]-[type].csv`  
   Examples: `sample-ecommerce-kpis.csv`, `sample-finance-variance.csv`
3. Add a short description in `/datasets/README.md`.

## Dataset rules (important)
- Do not include personal data (emails, names, phone numbers, addresses).
- Do not include sensitive or client data.
- Keep files small and easy to understand (usually under 1 to 5 MB).
- Include a clear time field (`date` or `month`) when possible.

## Documentation style
- Keep examples decision-focused (what question the dashboard answers).
- Avoid buzzwords and long paragraphs.
- Add links only when they are relevant to the folder topic.

## Questions
If you are not sure where something belongs, open an Issue and describe what you want to add.

