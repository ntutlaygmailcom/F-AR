# F-AR Proposal Website 補充條款檢查與修改建議

## 一、目前檢查結論

目前網站已經大致補齊李先生與其律師提出的主要項目，完整度約為 **90%–95%**。

已補齊的項目包含：

- 智慧財產權與程式碼所有權
- 帳號與基礎設施所有權
- 維護與保固
- 三小時以上重大修改規則
- SEO 基礎設定
- GA4 / GSC / 事件追蹤
- 付款時程

目前主要問題不是缺少項目，而是部分文字語氣仍偏向「建議事項」，建議改成更正式、可執行的提案條款語氣。

---

## 二、已補齊項目整理

### 1. 智慧財產權與程式碼所有權

網站目前已有新增 **Intellectual Property and Code Ownership** 區塊，並列出客戶擁有的範圍，例如：

- 網站視覺設計
- 網站內容
- 客製化前端程式碼
- 設計檔
- 交付檔案

同時也有說明需排除或清楚界定的項目，例如：

- 開發框架
- 程式庫
- 外掛
- 可重複使用的通用程式碼
- 第三方或開源工具

此項目基本上已回應對方要求。

---

### 2. 基礎設施與帳號所有權

網站目前已有寫明所有外部基礎設施與第三方服務帳號，應以 STOA／客戶公司名義註冊與管理，付款資訊也應使用 STOA／客戶的付款方式。

目前已涵蓋：

- 網域名稱註冊
- 網站主機或伺服器帳號
- DNS 管理
- Google Analytics 4
- Google Search Console
- 其他第三方網站服務帳號

也有寫明：

- STOA／客戶保留 Owner 或 Super Admin 權限
- 開發者只取得必要技術權限，例如 Editor、Developer 或 Administrator 權限

此項目已補齊。

---

### 3. 維護與保固

網站目前已有寫到：

- 設計確認後作為開發依據
- 設計確認後仍可進行小幅調整
- 超過三小時人力視為重大修改
- 整體風格、頁面結構、主要流程、版型重設、新頁面、新功能皆屬重大修改
- 上線後三個月保固
- 免費修正程式錯誤、功能問題、版面錯誤與開發 bug

此項目已補齊。

建議微調：

目前「設計定稿後修改」與「維護保固」放在同一段，邏輯上略混雜。建議將 **Design Approval and Change Requests** 獨立成一個小節，放在 Maintenance and Warranty 之前。

---

### 4. SEO 服務

網站目前已有新增 **SEO Service Scope**，並涵蓋：

- Google index readability
- URL structure
- Schema.org structured data
- Sitemap generation
- Core Web Vitals
- Site speed review
- Google Search Console
- GA4 integration
- Conversion tracking
- Event tracking

也有註明長期 SEO、廣告或進階分析可另行評估。

此項目已補齊。

---

### 5. 付款時程

網站目前已有 **Payment Terms**，並清楚分成：

- 40% Project Kickoff Payment
- 40% Design Confirmation Payment
- 20% Launch and Handover Payment

也有寫明：

- 每期款項需在下一階段開始前完成
- 尾款需在正式上線前完成
- 帳號、檔案與網站資料交接會在尾款完成後執行

此項目已補齊。

---

## 三、建議修改重點

### 建議 1：將建議語氣改成正式承諾語氣

目前若網站中出現類似：

> the contract should clearly define whether...

這類句子會比較像「律師建議」或「提案備註」，不太像正式條款。

建議改為：

```text
Upon full payment, STOA / the client will receive ownership or usage rights to the final website deliverables as defined in the agreement, including website design, content, custom interface design, front-end code, specifications, and delivery files.
```

中文意思：

```text
於完成全額付款後，STOA／客戶將依合約約定取得最終網站交付成果之所有權或使用權，包含網站設計、內容、客製化介面設計、前端程式碼、規格文件與交付檔案。
```

---

### 建議 2：獨立新增「Design Approval and Change Requests」區塊

建議將設計定稿後修改規則獨立出來，不要全部放在 Maintenance and Warranty 裡。

可使用以下英文條款：

```text
### Design Approval and Change Requests

Once the website design has been reviewed and approved by the client, the approved design shall serve as the basis for subsequent website development and implementation.

After design approval, minor adjustments may still be requested, including text edits, image replacements, color refinements, spacing adjustments, and minor layout corrections that do not affect the overall structure or design direction.

If a requested change after design approval is estimated to require more than three hours of additional work, or involves changes to the overall visual direction, page structure, key user flow, new pages, new features, redesigned layouts, or requests outside the agreed project scope, it shall be treated as a major change or additional request.

Major changes or additional requests may require a separate quotation, revised timeline, and written approval by both parties before implementation.
```

中文意思：

```text
網站設計稿經客戶確認後，將作為後續開發與製作依據。設計確認後，仍可進行文字、圖片、顏色、間距或局部版面等小幅調整。

若設計確認後提出之修改需求，預估執行時間超過三小時以上人力，或涉及整體視覺風格、頁面架構、主要流程、新增頁面、新增功能、重新設計版型，或其他超出原定專案範圍之需求，將視為重大修改或新增需求。

重大修改或新增需求需另行評估報價與時程，並於雙方確認後執行。
```

---

### 建議 3：補上 Out of Scope 區塊

SEO 與網站功能容易被無限擴張，因此建議補一段 **Out of Scope**，明確說明哪些不包含在目前報價中。

建議英文條款如下：

```text
### Out of Scope

The following items are not included in the current project scope unless separately quoted and confirmed by both parties:

- Long-term SEO ranking guarantee
- Monthly SEO content strategy or keyword reports
- Paid advertising campaign setup or management
- Backlink building or external SEO marketing
- Major new features beyond the approved project scope
- New page designs after design approval
- Major structural changes requiring more than three hours of additional work
- Third-party service subscription fees, hosting fees, domain fees, or advertising costs
```

中文意思：

```text
以下項目不包含於本次專案範圍內，除非雙方另行報價並確認：

- 長期 SEO 排名保證
- 每月 SEO 內容策略或關鍵字報告
- 付費廣告活動設定或管理
- 外部連結建置或站外 SEO 行銷
- 超出已確認專案範圍的重大新功能
- 設計確認後的新頁面設計
- 超過三小時以上人力的重大結構調整
- 第三方服務訂閱費、主機費、網域費或廣告費
```

---

## 四、建議最終網站區塊順序

建議提案網站中條款相關內容可依照以下順序排列：

1. Project Scope / 專案範圍
2. Deliverables / 交付項目
3. Intellectual Property and Code Ownership / 智慧財產權與程式碼所有權
4. Infrastructure and Account Ownership / 基礎設施與帳號所有權
5. Design Approval and Change Requests / 設計確認後之修改規則
6. Maintenance and Warranty / 維護與保固
7. SEO Service Scope / SEO 服務範圍
8. Out of Scope / 不包含項目
9. Payment Terms / 付款時程

---

## 五、總結

目前網站已經補上大部分對方期待的項目，整體方向是正確的。

建議最後再調整三件事：

1. 將「the contract should clearly define」這類建議語氣改成正式承諾語氣。
2. 將「Design Approval and Change Requests」從保固段落中獨立出來。
3. 補上 **Out of Scope** 區塊，避免 SEO、功能、頁面修改被無限擴張。

完成以上三點後，這份提案會更完整，也更能避免後續在所有權、修改範圍、SEO 與付款交付上的爭議。
