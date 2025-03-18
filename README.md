# SBOM Analysis on Pre-Compiled Rust & Go Binaries

## 🔍 Overview
This repository documents my research on **Software Bill of Materials (SBOMs)** generation and analysis from **pre-compiled Rust and Go binaries**.  
The goal is to understand software supply chain security risks and compare SBOM formats like **CycloneDX and SPDX**.

## 🛠️ Tools Used
- **Syft** – To generate SBOMs
- **CycloneDX / SPDX** – SBOM formats
- **Rust & Go binaries** – Analyzed software components
- **Dependency scanning tools** (BlackDuck, etc.)

## 📂 Project Structure
- `/results/` – Contains **small sample SBOM outputs**
- `/scripts/` – Includes **commands & automation scripts** used in the analysis
- `/reports/` – Documentation of **findings, vulnerabilities, and industry interviews**

## 🚀 How to Reproduce
To generate an SBOM for a pre-compiled Rust or Go binary:
```bash
syft binary:<your_binary> -o cyclonedx-json > output.json
```
This research is part of my work on **[SBOMit](https://github.com/SBOMit)** at NYU SSL.
