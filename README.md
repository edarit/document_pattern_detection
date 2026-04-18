## 🔎 Document Pattern Detection Lite (stlite Demo)

A browser-based demo for **pattern detection (exact + regex)** built with stlite.

👉 No installation required.
👉 Runs entirely in the browser.
👉 Designed as a **Lite version (80%)** of a full PDF pattern detection tool.

---

## 🚀 Live Demo Concept

This demo is powered by stlite (Streamlit in the browser) and focuses on:

* Exact keyword detection
* Regex pattern scanning
* Quick results preview
* CSV export

👉 It is intentionally limited to text input (not full PDF processing).

📌 Full PDF highlighting and export require the Python Streamlit version.

---

## 🧠 What This Tool Does

Paste any document text and define detection rules:

### ✅ Exact Match

```text
25WPF12345
Lim Ah Kau
B40
```

### ✅ Regex Rules

```text
WPF Code::\b\d{2}WPF\d{5}\b
B40 Tag::\bB40\b
NRIC::\b\d{6}-\d{2}-\d{4}\b
```

Click **Scan → Get results instantly**

---

## 📊 Output

* Total hits count
* Matched values
* Labels (Exact / Regex)
* Downloadable CSV

---

## 🧩 How It Works

This Lite demo mimics the core logic from the full Python engine:

* Combine text into searchable stream
* Apply regex / exact matching
* Return structured hits

The full version performs:

* Page-level detection
* Coordinate mapping
* PDF highlight annotations

👉 See core engine reference:


---

## ⚠️ Limitations (Intentional)

This is a **Lite version**, not a full product.

| Feature              | Lite (This Demo) | Full Version |
| -------------------- | ---------------- | ------------ |
| Text scanning        | ✅                | ✅            |
| Regex rules          | ✅                | ✅            |
| PDF upload           | ❌                | ✅            |
| Highlight PDF        | ❌                | ✅            |
| Save highlighted PDF | ❌                | ✅            |
| Risk scoring         | ❌                | ✅            |
| Executive report     | ❌                | ✅            |

---

## 🔒 Why These Limits Exist

This demo is designed as:

> 🟢 **Lite = “Almost enough”**
> 🔴 **Pro = “Decision-ready output”**

The full system includes:

* Risk scoring engine
* Category weighting
* Duplicate detection
* High-risk page identification

👉 Example Pro engine:


👉 Full Pro app with scoring + report:


---

## 💰 Upgrade to Pro (Concept)

The Pro version provides:

### 🔴 What You Unlock

* 📄 Upload PDF directly
* 🎯 Automatic highlighting inside PDF
* ⚖️ Risk scoring (Low / Medium / High / Critical)
* 📊 Executive summary
* 📌 Priority pages detection
* 📥 Export:

  * Highlighted PDF
  * TXT report
  * Markdown report
  * PDF report

---
