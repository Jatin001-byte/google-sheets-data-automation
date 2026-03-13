# 📊 TCL Month Plan – Google Sheets Automation

> Eliminates manual data entry in TCL watch production planning with a single button click.

---

## 🧩 Problem

Every month, data from **8+ sheets** had to be manually copied into the master Month Plan — hundreds of rows across Dispatch, Launch, WIP, Stock, PO, and more. This was:
- Time-consuming ⏱️
- Error-prone ❌
- Repetitive and frustrating 😤

## ✅ Solution

A **Google Apps Script** automation that consolidates all source sheet data into the Month Plan automatically — triggered by a single button click built directly into the spreadsheet.

---

## 🚀 Features

| Feature | Description |
|--------|-------------|
| 🔘 One-click button | Custom button in the sheet triggers full data fill |
| 📋 Multi-sheet consolidation | Pulls from 8 source sheets automatically |
| 🔄 Auto-populate | Fills Month Plan without any manual copying |
| 🛡️ Error reduction | Eliminates copy-paste mistakes |
| ⚡ Fast execution | Entire fill completes in seconds |

---

## 📁 Sheets Managed

| Sheet | Purpose |
|-------|---------|
| `Month plan TCL` | Master monthly planning dashboard |
| `TCL mail` | Critical component list for suppliers |
| `DISPATCH` | Sales dispatch tracking (since 16th Feb) |
| `LAUNCH` | Production launch/work orders |
| `WIP` | Work-in-progress inventory (Assy, Strapping, FG) |
| `STOCK` | Raw material & IGI stock levels |
| `TCL Order` | Customer order history and tracking |
| `PO` | Purchase order management |
| `busy stock` | Combined live stock view |

---

## 🛠️ Tech Stack

- **Google Sheets** — Data storage and UI
- **Google Apps Script** (JavaScript) — Automation logic
- **Custom UI Button** — Trigger mechanism inside the sheet

---

## 📂 Project Structure

```
tcl-month-plan-automation/
├── Code.gs                  # Main automation script
├── README.md                # Project documentation
├── sample-data/
│   └── Month_Plan_Sample.xlsx   # Anonymized sample file
└── screenshots/
    └── button-demo.png      # Screenshot of button in sheet
```

---

## ⚙️ How to Use

### Setup
1. Open your Google Sheet
2. Go to **Extensions → Apps Script**
3. Paste the contents of `Code.gs`
4. Save the project (Ctrl+S)
5. Reload your spreadsheet

### Run
1. Navigate to the **data input sheet**
2. Enter the new month's data
3. Click the **"Fill Data"** button
4. ✅ Month Plan sheet auto-populates instantly

---

## 📸 Screenshots

> *(Add a screenshot of your Google Sheet with the button visible here)*

---

## 📌 Key Stats

- **300+ watch models** tracked monthly
- **8 sheets** consolidated into 1
- **~77 columns** of planning data per model
- Covers: B/log, Mar, Apr, May requirements, WIP, FG, PO shorts, component stock

---

## 🙋 Author

**Your Name**
- JATIN
- GMAIL-jg6579392@gmail.com

---

## 📄 License

This project is for personal/portfolio use. Data has been anonymized.
