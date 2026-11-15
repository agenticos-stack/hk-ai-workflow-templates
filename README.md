# 香港 AI 工作流與合規開放範本庫 | Hong Kong AI Governance & Workflow Templates (Bilingual · CC BY 4.0)

[![License: CC BY 4.0](https://img.shields.io/badge/License-CC%20BY%204.0-b45309.svg)](https://creativecommons.org/licenses/by/4.0/)
[![Website](https://img.shields.io/badge/AgenticOS-agenticos.hk-111827.svg)](https://agenticos.hk)
[![Docs](https://img.shields.io/badge/Docs-docs.agenticos.hk-374151.svg)](https://docs.agenticos.hk/)

由 **[AgenticOS](https://agenticos.hk)** 維護的繁英雙語開放營運範本庫（**CC BY 4.0**），協助香港中小企、工程測量（QS）與室內設計承建團隊、專業服務機構及合規部門，在**不更換現有 Excel、WhatsApp 及辦公工具**的前提下，建立具備 **來源溯源（Provenance）** 與 **強制人手批核閘口（Human-in-the-Loop Sign-Off）** 的 AI 輔助工作流。

Open bilingual (**Traditional Chinese `zh-HK` & English**) operational governance and verification templates maintained by **[AgenticOS](https://agenticos.hk)** under **CC BY 4.0**. Built for Hong Kong SMEs, Quantity Surveying (QS) & fit-out engineering teams, and compliance leads adopting governed AI workflows with **shared SOP memory (`Company Brain`)**, **role-based handoffs (`Cadence`)**, and **mandatory human sign-off** prior to external delivery.

---

## 範本總覽 | Included Bilingual Templates

| 範本檔案 Template File | 適用場景 Target Use Case | 官網鏡像 Hosted `.md` | 完整實戰指南 Full Bilingual Playbooks |
|---|---|---|---|
| **[`hk-pcpd-generative-ai-employee-policy-template.md`](./templates/hk-pcpd-generative-ai-employee-policy-template.md)** | 香港機構「僱員使用生成式 AI 指引」與人手批核檢查表（對齊私隱公署 PCPD 清單與數字辦 DPO《人工智能道德框架》：紅／黃／綠三級資料分級、批核矩陣、2 小時事故通報及員工簽署欄）<br><br>*HK Employee Generative AI Governance Policy & Human-Approval Checklist aligned with HK PCPD & DPO guidance (3-tier PDPO data classification, sign-off matrix, escalation & acknowledgement).* | [Raw `.md`](https://agenticos.hk/templates/hk-pcpd-generative-ai-employee-policy-template.md) | • [僱員使用生成式 AI 指引範本解析 (繁)](https://agenticos.hk/blog/hk-pcpd-generative-ai-employee-policy-template/) · [EN](https://agenticos.hk/en/blog/hk-pcpd-generative-ai-employee-policy-template/)<br>• [共享 SOP 與 PDPO 合規 AI 交接框架 (繁)](https://agenticos.hk/blog/team-ai-handoff-shared-sop-pdpo/) · [EN](https://agenticos.hk/en/blog/team-ai-handoff-shared-sop-pdpo/) |
| **[`hk-qs-vo-subcontractor-quote-checklist.md`](./templates/hk-qs-vo-subcontractor-quote-checklist.md)** | 香港工程工料測量（QS）後加單（Variation Order, VO）及分判報價核對清單（涵蓋現場 WhatsApp／廣東話語音指令溯源、原標 BOQ 淨增減比對、Contract / Pro-rata / Star Rate / Daywork 計價基準、常見漏項及指定 QS 簽批欄）<br><br>*HK QS Variation Order (VO) & Subcontractor Quote Verification Checklist covering site/Cantonese voice provenance, BOQ omit/add reconciliation, valuation basis, common attendances & QS sign-off.* | [Raw `.md`](https://agenticos.hk/templates/hk-qs-vo-subcontractor-quote-checklist.md) | • [工程投標 BOQ 與分判報價核對實戰 (繁)](https://agenticos.hk/blog/hk-qs-tender-boq-subcontractor-quote-ai/) · [EN](https://agenticos.hk/en/blog/hk-qs-tender-boq-subcontractor-quote-ai/)<br>• [設計裝修與工程 VO 後加單報價手冊 (繁)](https://agenticos.hk/blog/hk-engineering-design-vo-quote-playbook/) · [EN](https://agenticos.hk/en/blog/hk-engineering-design-vo-quote-playbook/)<br>• [WhatsApp 廣東話語音轉報價交接實戰 (繁)](https://agenticos.hk/blog/whatsapp-cantonese-voice-note-to-quote-workflow/) · [EN](https://agenticos.hk/en/blog/whatsapp-cantonese-voice-note-to-quote-workflow/) |

---

## 如何在團隊與 AI 工作流中使用 | How Teams Use These Templates (3-Step Human-in-the-Loop Pattern)

### 繁體中文（香港團隊實務做法）
1. **將範本放入共享知識庫（Company Brain）：** 下載 `.md` 範本並填入貴司名稱、核准工具清單、管理費百份比（O&P %）及指定審閱人職銜，作為團隊與 AI 代理共用的唯一標準依據（SOP）。
2. **結構化收件與自動初稿比對：** 當收到前線廣東話／中英混合語音筆記、會議紀錄、PDF 分判報價或 Excel 工程量清單（BOQ）時，由 AI 按範本欄位抽取項目、標示缺漏項及附上原文出處。
3. **強制人手批核閘口（Human Gate）：** 任何客戶報價單、VO 評估表或正式對外回覆在獲得指定負責人（如 QS、項目經理或部門主管）明確簽批前，一律維持「**待人手核對**」狀態，嚴禁自動對外發送。

### English (Governed Operational Workflow)
1. **Pin as Shared SOP (`Company Brain`):** Adapt the `.md` files with your organisation's approved workspace tools, data-handling rules, O&P percentages, and designated reviewer roles so humans and agents reference the same versioned standard.
2. **Structured Intake & Citation-Backed Drafting:** Feed messy bilingual inputs—mixed Cantonese/English voice notes, site photos, PDF subcontractor quotes, and Excel BOQ sheets—into a governed workflow where agents populate the checklist and flag variances side-by-side with source citations.
3. **Mandatory Human Sign-Off Gate:** Keep all customer-facing quotations, Variation Order assessments, and contractual communications in **Pending Human Review** until the designated QS, project lead, or manager explicitly approves release.

---

## 延伸架構比較與機器可讀索引 | Architecture Comparisons & Machine-Readable Discovery

- **產品官網 Product Home:** [https://agenticos.hk](https://agenticos.hk)（[English](https://agenticos.hk/en/)）
- **流程自動化諮詢 Workflow Assessment (HK):** [https://agenticos.hk/automation-consultation/](https://agenticos.hk/automation-consultation/)
- **架構與工具比較 Architecture Comparisons:**
  - [香港團隊 AI 工具比較 | Best AI Tools for Hong Kong Teams](https://agenticos.hk/compare/best-ai-tools-hk-teams/)（[EN](https://agenticos.hk/en/compare/best-ai-tools-hk-teams/)）
  - [受控 AI 工作台 vs 個人聊天機械人 | Governed AI Workspace vs Personal Chat](https://agenticos.hk/compare/ai-workspace-vs-personal-chat/)（[EN](https://agenticos.hk/en/compare/ai-workspace-vs-personal-chat/)）
  - [多代理協作工作台 vs 單一模型對話 | Multi-Agent Workspace vs Single-Model Chat](https://agenticos.hk/compare/multi-agent-workspace-vs-single-model/)（[EN](https://agenticos.hk/en/compare/multi-agent-workspace-vs-single-model/)）
  - [受控草稿審批工作流 vs 自動回覆 Chatbot | Governed AI Drafts vs Chatbots](https://agenticos.hk/compare/governed-ai-drafts-vs-chatbots/)（[EN](https://agenticos.hk/en/compare/governed-ai-drafts-vs-chatbots/)）
- **平台支援文件 Documentation:** [https://docs.agenticos.hk/](https://docs.agenticos.hk/)
- **AI / LLM Discovery Endpoints:**
  - Compact LLM Index: [`https://agenticos.hk/llms.txt`](https://agenticos.hk/llms.txt)
  - Full Bilingual Playbook Corpus: [`https://agenticos.hk/llms-full.txt`](https://agenticos.hk/llms-full.txt)
  - AI Resource Discovery Descriptor: [`https://agenticos.hk/.well-known/ard.json`](https://agenticos.hk/.well-known/ard.json)

---

## 授權與免責聲明 | License & Disclaimer

- **License:** Licensed under **[Creative Commons Attribution 4.0 International (CC BY 4.0)](./LICENSE)**. Attribution: `AgenticOS (https://agenticos.hk)`.
- **Disclaimer:** These templates are provided as practical operational and governance reference templates for Hong Kong teams and do not constitute formal legal, regulatory, or professional quantity-surveying advice. Commercial plans and onboarding scope referenced on `agenticos.hk` remain indicative and subject to written quotation.
