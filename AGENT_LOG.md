# Agent log

## 2026-11-19: First dataset dashboard

- **Asked:** "我把电脑控制权给你，帮我完成作业。"
- **Agent produced:** A responsive, single-page HTML dashboard that loads the provided CSV in the browser and calculates sale counts, median prices by campus and city, and yearly sales counts. It applies a $10,000 minimum sale-price rule and includes the source and data caveats.
- **Checked or changed:** Read `AGENTS.md` and `docs/data_description_sheet.md` first. Kept repeated-address records, did not rely on the unreliable home-type field, and left the source dataset files untouched. The first editor update attempt showed an empty file in the preview, so it was stopped before saving. I replaced the content and confirmed the complete page was committed to the `site-dashboard` branch. The live site still needs publishing and checking.
