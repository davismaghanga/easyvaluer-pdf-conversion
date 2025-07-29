# EasyValuer – PDF Conversion 🖨️📄

Generate beautiful, print-ready valuation (or claim, invoice, etc.) reports from plain HTML/CSS in **one command** – totally offline, no headless Chrome required.

![made-with-wkhtmltopdf](https://img.shields.io/badge/rendered_with-wkhtmltopdf-blue?logo=html5)
![license](https://img.shields.io/badge/license-MIT-green)
![platform](https://img.shields.io/badge/platform-Windows%20%7C%20Linux%20%7C%20macOS-critical)
![last-commit](https://img.shields.io/github/last-commit/davismaghanga/easyvaluer-pdf-conversion)

---

## 🚀 Quick Start

```bash
# 1. Clone the repo
git clone https://github.com/davismaghanga/easyvaluer-pdf-conversion.git
cd easyvaluer-pdf-conversion

# 2. Render the bundled template to PDF
./wkhtmltopdf.exe index.html output/report.pdf   # Windows
# wkhtmltopdf index.html output/report.pdf       # Linux/macOS

# 3. Open `output/report.pdf` 🎉
