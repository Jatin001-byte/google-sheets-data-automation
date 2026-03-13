# 🛠️ Setup Guide

## Step 1 — Open Apps Script

1. Open your Google Sheet
2. Click **Extensions → Apps Script**
3. Delete any existing code in `Code.gs`
4. Paste the contents of `Code.gs` from this repo
5. Press **Ctrl + S** to save

## Step 2 — Set Permissions

When you run the script for the first time:
1. Click **Run → fillMonthPlan**
2. Google will ask for permissions — click **Review Permissions**
3. Choose your Google account
4. Click **Advanced → Go to project (unsafe)** *(this is normal for personal scripts)*
5. Click **Allow**

## Step 3 — Add the Button to Your Sheet

1. In your Google Sheet, go to **Insert → Drawing**
2. Draw a rectangle and add text: `Fill Month Plan`
3. Click **Save and Close**
4. Click the 3-dot menu on the drawing → **Assign Script**
5. Type: `fillMonthPlan`
6. Click **OK**

## Step 4 — Customize the Script

Open `Code.gs` and update the `CONFIG` object at the top if your sheet names are different:

```javascript
const CONFIG = {
  masterSheet:    "Month plan TCL",   // ← change if needed
  dispatchSheet:  "DISPATCH",
  launchSheet:    "LAUNCH",
  // ...
};
```

Then fill in the `TODO` sections inside each `populate` function with your actual cell mappings.

## Step 5 — Test It

1. Add some data to your source sheets
2. Click the **Fill Month Plan** button
3. Check that the master sheet updates correctly

---

## ⚠️ Troubleshooting

| Issue | Fix |
|-------|-----|
| "Sheet not found" error | Check sheet names in `CONFIG` match exactly |
| Button does nothing | Re-assign script name `fillMonthPlan` to the button |
| Permission denied | Re-run from Apps Script editor and re-authorize |
