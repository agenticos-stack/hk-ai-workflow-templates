# 香港機構「僱員使用生成式 AI 指引」與人手批核檢查範本（繁英雙語）
# Hong Kong Employee Generative AI Governance Policy & Human-Approval Checklist (Bilingual)

> **授權條款 License:** Creative Commons Attribution 4.0 (CC BY 4.0) — 歡迎香港企業、工程公司及機構自由複製、修改及內部採用，轉載或引用請註明來源。  
> **實戰全文與適用解析 Full Guide:** [https://agenticos.hk/blog/hk-pcpd-generative-ai-employee-policy-template/](https://agenticos.hk/blog/hk-pcpd-generative-ai-employee-policy-template/)  
> **參考框架 Alignment:** 香港個人資料私隱專員公署（PCPD）《僱員使用生成式 AI 的指引清單》、香港數字政策辦公室（DPO）《人工智能道德框架》及《香港生成式人工智能技術及應用指引》。

---

## 第一部分：繁體中文版（供香港企業內部政策採用）

### 1. 目的與適用範圍
本指引適用於 **[公司名稱]** 全體全職、兼職、合約員工、實習生及外判人員，規範日常職務（包括客戶報價、合約及文件草擬、會議紀要整理、內部研究與知識管理）中使用生成式人工智能（Generative AI）及受控 AI 工作台的資料安全與審批責任。

### 2. 三級資料分級與允許操作（PDPO 資料最小化原則）

| 級別 | 定義與常見香港商業例子 | 未受控公開個人帳號（如私人免費版 Chatbot） | 機構核准之受控 AI 工作台（如 AgenticOS） |
|---|---|---|---|
| **紅燈（高度機密 / 受條例嚴管）** | 客戶身份證／護照副本、銀行帳號／信用卡資料、醫療紀錄、未公開投標底價表、員工薪酬與私隱投訴檔案 | **嚴格禁止輸入或上載** | 除非獲資訊保安主管及管理層書面批准並實施脫敏／隔離，否則禁止直接輸入原始證件號及完整帳號 |
| **黃燈（內部商業／一般聯絡資料）** | 公司標準價目表、工程報價草稿、非敏感客戶電郵／WhatsApp 範圍查詢、專案進度會議紀錄 | **禁止輸入**（防止資料用作外部公開模型訓練或散落個人裝置） | **容許於機構核准權限範圍內處理**；對外發出前須經指定審閱人核對來源及金額條款 |
| **綠燈（公開／脫敏結構化內容）** | 公開法例條文、匿名化標準營運程序（SOP）、空白表單架構、公開產品規格 | 可作一般參考草擬，但不得視為已核實事實 | **容許自由使用**，產出仍需按業務流程保留引用來源 |

### 3. 核准工作環境 vs 未受控工具
- 員工**不得**使用個人手機或未經登記的第三方 AI 帳戶上載公司商業文件、客戶報價單、WhatsApp 對話截圖或會議錄音。
- 機構鼓勵員工使用統一管理的受控工作台，確保 **公司知識庫（SOP）版本一致**、**操作紀錄可追溯**，並由公司集中維護存取權限及離職回收安排。

### 4. 強制人手批核閘口（Human-in-the-Loop Sign-off Matrix）
所有由 AI 輔助產出的對外文件與關鍵商業紀錄，均須處於「**待人手核對**」狀態，直至指定審閱人確認方能對外發送：

| AI 輔助產出類型 | 原則上依據之來源 | 強制指定審閱人 | 未批核前可否對外發送／執行？ |
|---|---|---|---|
| 客戶報價單／VO 後加單／收費調整建議 | 現行價目 SOP ＋ 原合約／BOQ | 項目負責人／工料測量師（QS）或銷售經理 | **絕對禁止** |
| 對外合約條款修改／投標文件承諾 | 法律顧問或授權標準範本 | 董事／部門主管 | **絕對禁止** |
| 對外客戶回覆／正式電郵／投訴回應 | 客戶原始查詢 ＋ 內部跟進紀錄 | 客戶經理或客服主管 | **絕對禁止** |
| 內部會議摘要／草稿筆記 | 會議紀錄或錄音轉寫 | 與會同事核對要點即可 | 只限內部流轉 |

### 5. 引用溯源、準確性核實與紀錄保存
- **不得盲信 AI 生成內容：** 凡涉及港幣金額、面積數量、交付日期、條文編號及工程規格，必須並列核對原始資料（Original Source）後簽批。
- **保留交接紀錄：** 須清楚記錄誰發起任務、依據哪份 SOP 版本草擬，以及由哪一位審閱人於何時確認。

### 6. 資料外洩或誤發通報程序
- 若員工懷疑誤把「紅燈／黃燈」個人資料貼上未授權工具，或將未批核草稿錯發予外部人士，須於 **2 小時內** 通報部門主管及資料保障主任（DPO / Privacy Officer），保留截圖、時間戳記及涉及客戶名單以評估合規通報義務。

### 7. 員工確認簽署欄
- **員工姓名：** ______________________  **部門／職位：** ______________________
- **簽署：** __________________________  **日期（DD/MM/YYYY）：** ______________

---

## Part 2: English Version (For Internal Organisational Adoption in Hong Kong)

### 1. Purpose & Scope
This policy governs the responsible use of Generative AI and governed multi-agent workspaces by all employees, contractors, and interns of **[Company Name]** across client communications, quotations, Variation Orders (VO), meeting documentation, and internal knowledge workflows.

### 2. Three-Tier Data Classification (PDPO Data Minimisation)

| Tier | Examples | Unmanaged Personal / Public AI Accounts | Organisation-Approved Governed Workspace |
|---|---|---|---|
| **Red (Restricted / Sensitive PII)** | HKID/passport copies, bank/card numbers, health records, confidential tender reserve prices, HR payroll & disciplinary files | **Strictly prohibited** | Prohibited in raw form unless expressly authorised in writing with redaction/isolation controls |
| **Amber (Internal Commercial Data)** | Rate cards, client scope requests, subcontractor quotes, project meeting transcripts, SOPs | **Prohibited** (prevents leakage or model training reuse) | **Permitted under role-based access**, subject to mandatory human approval before external release |
| **Green (Public / Anonymised Data)** | Public legislation, anonymised SOP structures, public product specs | Permitted for non-confidential drafting only | **Permitted**; retain citations for factual accuracy |

### 3. Approved Workspace vs Shadow AI
- Staff must **not** upload client files, Excel rate sheets, WhatsApp voice notes, or meeting recordings into unmanaged personal AI tools.
- Governed team workflows require centralised permission control, maintained SOP references, and auditable handoffs.

### 4. Mandatory Human-in-the-Loop Sign-Off Matrix
AI drafts must remain in **Pending Human Review** until explicitly approved by the designated reviewer:
- **Client Quotations / VO Revisions / Pricing Changes:** Mandatory check against baseline SOP/BOQ & sign-off by Project Lead / QS / Manager before sending.
- **Contract / Tender Commitments:** Mandatory approval by Director / Department Head.
- **External Client Replies / Formal Notices:** Mandatory review by Account Lead / Supervisor.

### 5. Source Provenance & Incident Escalation
- Every numeric figure, quantity, delivery date, or policy statement must be verified against cited source records before approval.
- Report any accidental Red/Amber data disclosure or unapproved external send to your Department Head and Data Protection Officer within **2 hours**.

### 6. Employee Acknowledgement
- **Employee Name:** ___________________  **Role / Department:** ___________________
- **Signature:** ________________________  **Date (DD/MM/YYYY):** __________________

---

> **Implementation Resource:** See how Hong Kong SMEs connect WhatsApp, Excel & Word/PDF stacks to governed human sign-off workflows at [https://agenticos.hk/](https://agenticos.hk/) or book a 60-minute assessment at [https://agenticos.hk/automation-consultation/](https://agenticos.hk/automation-consultation/).
