# Vendor Ramp Tracker

Available in English and Spanish (EN/ES toggle). A 90-day proficiency console for outsourced vendor teams. Anyone can answer a few guided questions to choose the metrics that matter for their vendor, set goals and a ramp, log results, and see whether the team is on pace, where the vendor's leaders should focus, or whether it is proficient at day 90.

**Live site:** https://karentinoco13-alt.github.io/vendor-ramp-tracker/

## Features

- **Guided setup:** vendor and start date, type of work, priorities, recommended metrics (or your own), then goals, weights and ramp speed.
- **30/60/90 assessment:** each phase's target is a share of the final goal (e.g. 70% / 85% / 100%). Results are marked on track (≥100% of target), fine-tune (90–99%, coaching led by the vendor's own leaders) or needs support (<90%, vendor-led coaching plus the support the client provides under the agreement).
- **Day-90 verdict:** proficient when the weighted score for days 61–90 is at least 100% and no metric is below 90%.
- **Partnership plan:** metrics grouped by area, with what to ask the vendor's leaders to address, the support the client provides under the agreement (tools, access, guidelines, forecasts), and strengths to share with the vendor.
- **Metric review:** scorecard with trends, ramp chart and 30/60/90 checkpoint grid.
- **Live demo:** replay a sample vendor's first 98 days.
- **Tableau export:** two tidy CSV files (results and ramp targets) plus the calculated fields to build the workbook.

## Working with vendors the right way

The client manages the agreement and the team's results; the vendor manages its people. Directing a vendor's workers as if they were your own staff can make your company look like their employer (co-employment or joint employment), with legal, tax and benefits risks. The app is built around that line:

- Metrics are team-level only. The app asks you not to enter agent names, individual results or performance reviews.
- The partnership plan lists what to **ask the vendor's leaders** to address, never instructions for individual vendor workers, plus the support the client provides under the agreement.
- **Do:** manage to the contract and team outcomes; share feedback and data with the vendor's management; provide tools, access, guidelines, forecasts and clear requirements.
- **Don't:** assign, schedule, supervise, coach, evaluate, discipline, hire or fire individual vendor workers, give them day-to-day direction, or treat them like employees (titles, benefits, internal events) unless your contract and legal team allow it.

Rules differ by country (for example, the US joint-employer standard, or Mexico's 2021 outsourcing reform and REPSE registry). This is general guidance, not legal advice: check with your legal and procurement teams. The same guidance appears in the app, in English and Spanish, under How it scores, Privacy & security and Terms.

## Privacy and security

The app has a **Privacy & security** tab with these notes in English and Spanish.

On the public site (GitHub Pages) everything you enter stays in your own web browser. The site has no database and no accounts, so nobody else, including the author, can see your programs or results.

- **Saving:** programs and results are saved when you click Create program, Save changes or Save results. They are stored in your browser (localStorage) on that computer only. Another device or browser will not see them, and clearing your browser data deletes them.
- **No AI:** the app does not send your data to Claude or any other AI service. All scoring runs in your browser.
- **Export:** CSV files download to your own device, or are copied to your clipboard. They are not stored anywhere else.
- **Sharing the link:** gives people the app, not your data. Each person starts with the sample vendor and their own programs.
- **Hosting:** the site is hosted on GitHub Pages and loads fonts from Google Fonts. Like any website, these services receive standard request details such as your IP address, never what you type.
- **Good practice:** log team-level metrics. Avoid entering personal details about individual agents.
- **Access:** no accounts or passwords; the app never asks for login details.
- **Tracking:** no cookies, analytics or advertising trackers.
- **Shared computers:** anyone using the same browser profile can see saved programs. Export your CSVs and clear browser data when you finish.
- **Deleting data:** Delete program removes one program and its results. **Delete all my data** (Privacy & security tab and footer) removes every program, result and setting saved in the browser, including the Terms acceptance, after two warnings: the first offers to export a copy, the final one needs a ticked acknowledgment before *Delete permanently* unlocks. In the team version on claude.ai, it deletes the person's own feedback and browser settings; shared programs belong to the team and are deleted one by one.
- **Exported files:** CSVs are plain text; store and share them according to your company's data policy.

For a shared, live team workspace, the same data model maps onto three Salesforce custom objects (`Ramp_Program__c`, `Ramp_Metric__c`, `Metric_Result__c`) that Tableau can read with its Salesforce connector.

## Terms & conditions

See [TERMS.md](TERMS.md). The same terms are in the app's **Terms** tab, in English and Spanish. Visitors see an acceptance banner until they agree, and must tick "I have read and agree to the Terms & conditions" before creating a program. Deleting data shows two warnings, including an acknowledgement that the app and its developer are not responsible for lost data.

## Feedback

Use the **Feedback** tab in the app, or [open an issue](https://github.com/karentinoco13-alt/vendor-ramp-tracker/issues/new). Feedback is used to plan future versions.

## Run locally

It is a single static file. Open `index.html` in a browser.

## Credits

Vendor Ramp Tracker by Karen Tinoco. Designed and directed by the author; implemented with Claude Code as an AI pair programmer. All sample vendor data is simulated. Northwind BPO is a fictional company; not affiliated with any real vendor.

## License

Required Notice: Copyright (c) 2026 Karen Tinoco (https://www.thehumanelement.live)

Vendor Ramp Tracker by Karen Tinoco · © 2026 Karen Tinoco. Licensed under the [PolyForm Noncommercial License 1.0.0](LICENSE.md): free to use, share and adapt for non-commercial purposes, with credit. Commercial use by permission only.
