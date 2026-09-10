# Congressional Trading Risk Intelligence

A legal data analytics project examining **U.S. congressional securities disclosures**, trading patterns, reporting timelines, and potential compliance-screening indicators using Python.

## Project Overview

The project analyzes **17,170 congressional transaction records** and demonstrates how public financial-disclosure data can be transformed into structured ethics and compliance intelligence.

After cleaning and deduplication, **16,616 transactions across 196 lawmakers** were analyzed.

### Key Findings

* **554 duplicate records** identified and removed.
* **Technology** was the most represented trading sector.
* **MSFT** was the most frequently disclosed ticker.
* Median transaction-to-disclosure lag was **28 days**.
* **2,606 records** exceeded the 45-day outer-limit screening threshold and were flagged for **further review**, not classified as violations.

## Project Workflow

**01 — Data Cleaning**
Cleans 17,170 raw records, standardizes transaction data, parses amount ranges, and calculates disclosure timing.

**02 — Trading Patterns Analysis**
Examines lawmaker trading activity, transaction types, sectors, industries, securities, transaction sizes, and time trends.

**03 — Disclosure Compliance Analysis**
Translates congressional disclosure timing requirements into an auditable compliance-screening workflow.

## Tools

Python · pandas · Jupyter Notebook · Matplotlib

## Legal-Tech Focus

This project demonstrates the intersection of **financial regulation, government ethics, compliance analytics, data analysis, and responsible legal-tech design**.

> **Disclaimer:** Screening flags are analytical indicators only. They do not establish insider trading, a STOCK Act violation, unethical conduct, or current risk by any lawmaker.
