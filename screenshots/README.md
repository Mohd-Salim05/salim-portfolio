# Project screenshots

Put project screenshots in this folder. `index.html` loads them from here.

Until a file exists, its card shows a "Screenshot coming soon" placeholder instead of a broken image.

## Expected file names

| Project | Files |
|---|---|
| Timesheet Management SuiteApp | `timesheet-grid.png`, `timesheet-dashboard.png`, `timesheet-approvals.png`, `timesheet-admin.png` |
| Customer & Vendor Portal | `portal-login.png`, `portal-customer.png`, `portal-vendor.png` |
| Work Breakdown Structure (WBS) | `wbs-hierarchy.png`, `wbs-kpi.png` |
| NetSuite API Integration | `integration-architecture.png`, `integration-powerbi.png` |
| Inventory-Store SuiteApp | `inventory-count.png`, `inventory-approval.png` |

The first file in each list is the card's cover image.

## Adding, renaming or removing screenshots

Edit the `screenshots: [...]` array for that project in `index.html`. Search for `SCREENSHOTS`.

```js
screenshots: [
  { src: "screenshots/my-file.png", caption: "What this screen shows" }
]
```

## Tips

- Use a 16:9 ratio, about 1600×900. Covers are cropped from the top, so put the important part near the top.
- `.png`, `.jpg` and `.webp` all work. Keep each file under about 500 KB so the page loads quickly.
- GitHub Pages file names are **case-sensitive**: `Timesheet-Grid.PNG` will not match `timesheet-grid.png`.
- Before publishing, blur or redact client names, amounts and any personal data.
