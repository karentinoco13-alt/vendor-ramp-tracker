# Vendor Ramp Tracker

Available in English and Spanish (EN/ES toggle). A 90-day proficiency console for outsourced vendor teams. Anyone can answer a few guided questions to choose the metrics that matter for their vendor, set goals and a ramp, log results, and see whether the team is on pace, needs coaching, or is proficient at day 90.

**Live site:** https://karentinoco13-alt.github.io/vendor-ramp-tracker/

## Features

- **Guided setup:** vendor and start date, type of work, priorities, recommended metrics (or your own), then goals, weights and ramp speed.
- **30/60/90 assessment:** each phase's target is a share of the final goal (e.g. 70% / 85% / 100%). Results are marked on track (≥100% of target), fine-tune (90–99%, coaching) or needs support (<90%, coaching plus support from the client side).
- **Day-90 verdict:** proficient when the weighted score for days 61–90 is at least 100% and no metric is below 90%.
- **Partnership plan:** metrics grouped by area, with coaching for the vendor team, the support the client provides (tools, access, guidelines, forecasts), and strengths to recognize.
- **Metric review:** scorecard with trends, ramp chart and 30/60/90 checkpoint grid.
- **Live demo:** replay a sample vendor's first 98 days.
- **Tableau export:** two tidy CSV files (results and ramp targets) plus the calculated fields to build the workbook.

## Data

On GitHub Pages, programs and results are saved in each visitor's own browser (localStorage). Use the Tableau export tab to download CSVs for sharing or reporting. For a live, shared feed, the data model maps onto three Salesforce custom objects (`Ramp_Program__c`, `Ramp_Metric__c`, `Metric_Result__c`) that Tableau can read with its Salesforce connector.

## Run locally

It is a single static file. Open `index.html` in a browser.
