# 🛡️ Cybersecurity ROI Calculator

This tool helps CISOs, IT leaders, and risk analysts **quantify the financial impact of cybersecurity investments**. Designed to be fully client-side and secure, it allows users to model risk scenarios, adjust for organizational context, and calculate ROI in a structured, data-driven way.

> **Built during Memorial Day weekend** in a Gemini-fueled code sprint — perfect blend of sun, caffeine, and cybersecurity.

---

## 🚀 Features

- 📊 **Annualized Loss Expectancy (ALE)** calculations
- 🏢 Organization-specific risk adjustment:
  - Industry
  - Region
  - Company Size
  - Infrastructure Type & Complexity
- 🔐 Risk scenario builder (ransomware, insider threat, cloud misconfig, etc.)
- 📉 Residual risk calculation with control effectiveness inputs
- 💰 **ROI metrics** for individual scenarios and entire security programs
- 📦 Export to Excel + Save/Load data as JSON
- 🔎 In-browser only (no backend = no data exposure)

---

## 📌 Use Cases

- Communicating cybersecurity value to executive leadership
- Budget justification for security programs
- Scenario modeling for risk quantification (FAIR-aligned)
- Supporting insurance assessments and M&A diligence

---

## 🧪 Methodology

This calculator uses principles inspired by the **FAIR Model** and is informed by public research:
- IBM & Ponemon *Cost of a Data Breach Report (2024)*
- Verizon *Data Breach Investigations Report (2025)*

Key concepts:
- **SLE (Single Loss Expectancy)** × **ARO (Annualized Rate of Occurrence)** = **ALE**
- **Risk Reduction (%)** per scenario reduces ALE
- ROI = `(Risk Reduction - Program Cost) / Program Cost`

---

## 🧭 Getting Started

1. Clone or download this repo
2. Open `adv-risk-calculator.html` in your browser
3. No build steps, no backend — just run and go!

---

## 📂 Files

- `index.html`: Full standalone app

---


## 🙌 Contributing

Bug reports, enhancements, and feedback are welcome. Open an issue or submit a pull request.

---

## 📄 License

MIT License

---

## 💬 Shoutout

Built with 💻, ☕, and Gemini by [Silvano Silva].  
Let's bring clarity to cyber risk — one scenario at a time.

