# QualitySPC v1.0

**QualitySPC** is a free, professional-grade Statistical Process Control (SPC) desktop application designed for Quality Engineers, Manufacturing Professionals, and Students. It provides robust, industry-standard statistical analysis in a secure, offline environment.

This release features a complete suite of tools for Process Control, Capability Analysis, and Measurement System Analysis, adhering to ASTM and AIAG standards.

### 💡 Project Philosophy

This project was built using **AI assistance** (Large Language Models) to accelerate the development of complex statistical formulas and framework structure.

It is designed as an open-source, community-driven resource. We encourage developers to **fork** the repository, **verify the mathematical logic**, and **contribute improvements** to make this the most accurate free SPC tool available.

---

## ✨ Key Features

### 📈 X-Bar & R Charts
* **Automated Analysis:** Instantly calculates Control Limits (UCL/LCL) using standard ASTM constants ($A_2, D_3, D_4$).
* **Flexible Input:** Supports single-column data (with auto-subgrouping) or pre-grouped row data.
* **Visuals:** Clear, interactive charts for Process Mean and Variation.

### 🔔 Process Capability Analysis ($C_{pk}$ / $P_{pk}$)
* **Comprehensive Reporting:** Generates full "Six Pack" style reports including Histograms with Normal Curves.
* **Advanced Metrics:** Calculates $C_p, C_{pk}, P_p, P_{pk}, C_{pm}$, and Sigma Level.
* **Performance Data:** Includes detailed PPM (Parts Per Million) analysis for Observed vs. Expected performance.
* **Correct Mathematics:** Distinguishes between *Within* variation (using $\bar{R}/d_2$) and *Overall* variation (standard deviation) for accurate short-term vs. long-term analysis.

### 📏 Gage R&R Study (Crossed)
* **AIAG Standard:** Uses the industry-standard "Average and Range" method.
* **Diagnostic Charts:** Generates a full grid of 6 diagnostic charts (Components of Variation, Interaction, By Operator, By Part, etc.) to identify root causes of measurement error.
* **Key Metrics:** Calculates % Study Variation, % Tolerance, and Number of Distinct Categories (NDC).

### 📝 Professional Reporting
* **PDF Export:** One-click generation of professional PDF reports for all analysis tools.
* **Customizable Headers:** Add your Company Name, Representative Name, and Logo to reports for official documentation.
* **Excel Integration:** Seamlessly import large datasets from `.xlsx` or `.csv` files.

---

## 📦 How to Install & Run

1.  **Download** the `QualitySPC_v1.0_Windows.zip` file from the Releases section.
2.  **Extract** the zip file to a folder on your computer.
3.  Open the folder and double-click **`QualitySPC.exe`** to launch the application.

*Note: This is a portable application. No complex installation wizard is required.*

### ⚠️ Security Notice
Because this software is free and independently developed, Windows Defender or SmartScreen may flag it as an "Unknown Publisher."
* **To Run:** Click **"More Info"** -> **"Run Anyway"**.
* **Safety:** This application works entirely offline. It does not collect data or connect to the internet.

---

## ⚖️ License & Disclaimer

**Free for use, but "Use at Your Own Risk".**

This software was developed as a personal project to assist students and professionals with statistical analysis. While every effort has been made to ensure mathematical accuracy (adhering to AIAG/ASTM standards), this software has **not** undergone the third-party validation or certification often required for Enterprise Quality Management Systems (EQMS).

### ⚠️ Commercial & Industrial Use Warning
**This software is primarily intended for educational and personal verification purposes.**

Any company, corporation, or organization that chooses to use **QualitySPC** for commercial production, quality control, or critical business decisions does so **entirely at their own risk**.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR IMPLIED. **THE AUTHORS EXPRESSLY DISCLAIM ANY LIABILITY** FOR DEFECTIVE PRODUCTS, FINANCIAL LOSSES, RECALLS, OR DAMAGES RESULTING FROM THE USE OF THIS SOFTWARE. BY DOWNLOADING THIS APPLICATION, YOU AGREE THAT YOU ARE SOLELY RESPONSIBLE FOR VERIFYING ALL RESULTS BEFORE APPLYING THEM TO LIVE MANUFACTURING PROCESSES.

