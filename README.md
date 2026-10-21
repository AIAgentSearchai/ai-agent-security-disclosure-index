# AI Agent Security Disclosure Index, October 2026: Totals by Category

Publisher: AIAgentSearch.ai (Agentic Solutions LLC)
Author: AIAgentSearch.ai Editorial Team
Data collected: October 20, 2026
Published: October 21, 2026
Edition: October 2026 (first edition; the index is re-read monthly on the same companies)
Page: https://aiagentsearch.ai/ai-agent-security-disclosure-index.html
License: Creative Commons Attribution 4.0 International (CC BY 4.0), https://creativecommons.org/licenses/by/4.0/

## What this file set contains

| File | What it is |
|---|---|
| `Data_Study_02_Public_Totals_by_Category_2026-10-20.csv` | One row per category (20 rows) plus an "All" row: counts of companies read and of each measure below |
| `LICENSE` | The CC BY 4.0 licence notice for this repository |
| `README.md` | This codebook |

The chart is on the study page linked above.

## Method

**Question.** What security evidence and agent controls do the AI agent startups we track state on their own public pages, before a buyer has signed a non-disclosure agreement or spoken to sales?

**Sample.** 106 early-stage AI agent companies: the fixed panel of the AIAgentSearch.ai AI Agent Pricing Transparency Index, which is every company in the AIAgentSearch.ai candidate pool (our working list of AI agent companies sourced for coverage, compiled August to September 2026) except those our editors had already rejected as outside our 20 categories or not agent products. The pool was sourced mainly from startup accelerator rosters, funding coverage and category round-ups, so it leans toward early-stage companies. It is not a random sample of the AI agent market. Results describe the startups we track, not AI agent companies as a whole.

**Collection.** On October 20, 2026 we read, for each company, its homepage or pricing page and the trust center, security and documentation pages those pages linked to. Pages were read with an AI-assisted page reader instructed to report only what each page states. Every value was recorded with the URL it came from. Nothing was estimated or filled in.

**Readable companies.** 88 of the 106, across 19 of our 20 categories, the same 88 readable in the pricing index. Of the 18 not counted: 6 had changed product, 1 had been acquired, and 11 could not be read. None of the 18 is counted as "not stated". The Data Analysis and BI category has 0 readable companies this month.

**Pages we could not read.** 15 of the 88 companies linked at least one page we could not read: 10 trust centers that load their content only by script, and 5 pages our reader could not fetch. Items on those pages are counted as not stated. Where a company's own security or pricing page already answered an item, we did not always open its separate trust center as well. Every count is therefore a floor.

## Codebook: `Data_Study_02_Public_Totals_by_Category_2026-10-20.csv`

Every count column counts companies among the `read_n` readable companies in that row. A company is counted once per column. An item is counted when it is stated on a page we read.

| Column | Type | Definition |
|---|---|---|
| `category` | text | AIAgentSearch.ai category, or `All` for the total row |
| `sampled_n` | integer | Companies sampled in the category (all statuses) |
| `read_n` | integer | Companies readable on October 20, 2026 (the denominator for every other column) |
| `soc2_held` | integer | SOC 2 named in text or a labelled badge as held, completed, certified, attested or compliant, any type. "In progress" or "readiness" is not counted. A badge named only in an image file name, or labelled "AICPA SOC" without the number 2, is not counted |
| `soc2_type2_stated` | integer | Of `soc2_held`, the page says Type II (or Type 2) |
| `iso27001_held` | integer | ISO 27001 named as held, certified or compliant. "In progress" is not counted. ISO 42001 is not counted |
| `trust_or_security_page` | integer | The company's site links to a page or subdomain dedicated to security, trust or compliance. A homepage section is not counted |
| `retention_period_stated` | integer | A period is stated for keeping any customer data (including logs, history, recordings or traces), or a zero-retention commitment |
| `training_statement` | integer | Any statement on whether customer data is used to train or improve AI models, in either direction |
| `sso_saml` | integer | Single sign-on or SAML sign-in offered on at least one plan |
| `audit_logs` | integer | Audit logs or an audit trail of user or agent activity offered to the customer. Logs kept only for the company's internal use are not counted |
| `human_approval_documented` | integer | A step where a person approves or reviews before the agent acts is described, by default or as a setting. Escalation of unfamiliar cases, or a feature described only as planned, is not counted |
| `pentest_mentioned` | integer | Penetration testing of the company's own product or systems is mentioned. Penetration testing sold as a product is not counted |
| `hipaa_or_baa_named` | integer | HIPAA compliance or a business associate agreement (BAA) is named |
| `soc2_in_progress` | integer | SOC 2 is named as in progress or readiness (not included in `soc2_held`) |
| `iso27001_in_progress` | integer | ISO 27001 is named as in progress (not included in `iso27001_held`) |
| `training_not_used_stated` | integer | Of `training_statement`, the company says plainly that customer data is not used to train models |
| `soc2_report_on_request` | integer | The page says how a buyer can obtain the SOC 2 report (on request, under NDA or by request through a trust center). No company in the sample offered the report as an open download |

Totals in the `All` row: read 88; SOC 2 held 41 (Type II stated 27); ISO 27001 held 5; trust center or security page 49; retention period stated 21; training statement 21 (of which 14 say customer data is not used); SSO or SAML 30; audit logs 22; human approval documented 23; penetration testing mentioned 10; HIPAA or BAA named 16; SOC 2 in progress 5; ISO 27001 in progress 4; SOC 2 report on request 9.

**Reading small rows.** Eleven categories have fewer than five readable companies. A percentage on two or three companies would mislead; the published page groups them.

## Company-level data

Company-level data is withheld to avoid singling out individual companies. A public row reading "no SOC 2 report named" would name a company, on a single reading date, for a gap many companies share. This file set publishes totals only.

## How to cite

**APA (7th edition)**
AIAgentSearch.ai Editorial Team. (2026, October 21). *Most AI Agent Startups We Track Do Not Name a SOC 2 Report*. AIAgentSearch.ai. https://aiagentsearch.ai/ai-agent-security-disclosure-index.html

**MLA (9th edition)**
AIAgentSearch.ai Editorial Team. "Most AI Agent Startups We Track Do Not Name a SOC 2 Report." *AIAgentSearch.ai*, 21 Oct. 2026, aiagentsearch.ai/ai-agent-security-disclosure-index.html.

**Citing the data files (APA 7, data set)**
AIAgentSearch.ai Editorial Team. (2026). *AI Agent Security Disclosure Index: Totals by category, October 2026* [Data set]. AIAgentSearch.ai. https://aiagentsearch.ai/ai-agent-security-disclosure-index.html

Under CC BY 4.0 you may share and adapt these files for any purpose, including commercially, if you credit "AIAgentSearch.ai, AI Agent Security Disclosure Index, October 2026" with a link to the page above and say whether you made changes.

## Independence

AIAgentSearch.ai takes no advertising, affiliate fees or sponsored content. No company in the study was told it was being studied or asked to review its data. Companies that buy a listing on AIAgentSearch.ai are treated the same as every other company in the data.
