# GitHub Activity Report for HR Review

## 1. 報告目的

本報告彙整帳號 **SwLok0** 在 **SwLok0/atlas** 的 GitHub 原生活動，並另列可由 GitHub 原生資料驗證的 Copilot／系統活動。報告僅納入可追溯至 GitHub URL 的資料。

## 2. 期間與識別資訊

- **期間**：2025-05-01 至 2026-09-29（報告產出日）
- **Repository**：SwLok0/atlas
- **GitHub 帳號**：SwLok0
- **資料來源**：GitHub repository commits、pull requests、pull-request reviews；查詢時間以 GitHub API 回傳資料為準。

## 3. 摘要統計

| 類別 | 數量 | 計算方式 |
|---|---:|---|
| 本人 commits | 62 | commit author login 為 SwLok0 |
| Copilot agent commits | 5 | commit author login 為 Copilot |
| Dependabot system commits | 1 | commit author login 為 dependabot[bot] |
| PR records | 8 | 期間內可驗證且與本人／agent merge 或建立關聯的 PR |
| Copilot reviews | 5 | GitHub 原生 review URL |
| Issues | 0 件可確認由 SwLok0 建立 | GitHub issue search；未找到符合條件的結果 |
| Comments | 0 件可確認由 SwLok0 發表 | 已查詢期間內相關 PR discussion comments；未找到本人留言 |

## 4. 月度統計

| 月份 | 本人 commits | Agent/system commits | PR records | Reviews |
|---|---:|---:|---:|---:|
| 2026-03 | 0 | 0 | 3 | 3 |
| 2026-05 | 4 | 0 | 0 | 0 |
| 2026-06 | 33 | 5 | 3 | 2 |
| 2026-07 | 24 | 0 | 1 | 0 |
| 2026-08 | 1 | 1 | 1 | 0 |

## 5. 活動明細

完整結構化明細請見 [`github-activity-details.csv`](./github-activity-details.csv)。CSV 欄位為：日期、活動類型、repository、標題／簡述、狀態、相關 URL、備註。

### 代表性 PR 與 reviews

- 2026-03-12 — **#1 Import/bond weighted forecast** — [https://github.com/SwLok0/atlas/pull/1](https://github.com/SwLok0/atlas/pull/1) — PR 建立者 SwLok0；合併 2026-03-12
- 2026-03-27 — **#17 Refactor GFF notebook into modular, independently-runnable experiment scripts** — [https://github.com/SwLok0/atlas/pull/17](https://github.com/SwLok0/atlas/pull/17) — PR 建立者為 Copilot；納入可驗證 agent 活動
- 2026-03-27 — **#18 Copilot/refactor ipynb for model repo** — [https://github.com/SwLok0/atlas/pull/18](https://github.com/SwLok0/atlas/pull/18) — PR 建立者 SwLok0；合併 2026-03-27
- 2026-06-06 — **#27 Agent B — L1 leave-one-out cross-domain validation** — [https://github.com/SwLok0/atlas/pull/27](https://github.com/SwLok0/atlas/pull/27) — PR 建立者為 Copilot；納入可驗證 agent 活動
- 2026-06-06 — **#28 Cross-asset Granger causality analysis** — [https://github.com/SwLok0/atlas/pull/28](https://github.com/SwLok0/atlas/pull/28) — PR 建立者為 Copilot；納入可驗證 agent 活動
- 2026-06-25 — **#29 Add missing requirements.txt for generate-readme workflow** — [https://github.com/SwLok0/atlas/pull/29](https://github.com/SwLok0/atlas/pull/29) — PR 建立者為 Copilot；納入可驗證 agent 活動
- 2026-07-12 — **#30 Add AMR deployment Phase 0 audit and checkpoint gate** — [https://github.com/SwLok0/atlas/pull/30](https://github.com/SwLok0/atlas/pull/30) — PR 建立者為 Copilot；納入可驗證 agent 活動
- 2026-08-14 — **#31 Dependabot torch update** — [https://github.com/SwLok0/atlas/pull/31](https://github.com/SwLok0/atlas/pull/31) — 透過本人 merge commit 驗證；PR 本身由 Dependabot 建立
- 2026-03-12 — **Copilot review of PR #1** — [https://github.com/SwLok0/atlas/pull/1#pullrequestreview-3936829421](https://github.com/SwLok0/atlas/pull/1#pullrequestreview-3936829421) — GitHub 原生 Copilot reviewer
- 2026-03-27 — **Copilot review of PR #17** — [https://github.com/SwLok0/atlas/pull/17#pullrequestreview-4023178302](https://github.com/SwLok0/atlas/pull/17#pullrequestreview-4023178302) — GitHub 原生 Copilot reviewer
- 2026-03-27 — **Copilot review of PR #18** — [https://github.com/SwLok0/atlas/pull/18#pullrequestreview-4023417049](https://github.com/SwLok0/atlas/pull/18#pullrequestreview-4023417049) — GitHub 原生 Copilot reviewer
- 2026-06-06 — **Copilot review of PR #27** — [https://github.com/SwLok0/atlas/pull/27#pullrequestreview-4441928092](https://github.com/SwLok0/atlas/pull/27#pullrequestreview-4441928092) — GitHub 原生 Copilot reviewer
- 2026-06-25 — **Copilot review of PR #29** — [https://github.com/SwLok0/atlas/pull/29#pullrequestreview-4568205398](https://github.com/SwLok0/atlas/pull/29#pullrequestreview-4568205398) — GitHub 原生 Copilot reviewer

## 6. 限制與說明

- GitHub 原生資料可驗證提交者、PR、review 與 URL，但不能單獨證明某項 Copilot／Dependabot 活動是否由本人在 GitHub 外部主動觸發；因此 agent/system 項目標示為「可驗證活動」，不宣稱因果關係。
- GitHub API 的 commit author identity 可能與提交 email/name 不一致；本報告以 GitHub 回傳的 login 為主要身份判定依據。
- 未納入無法確認與 SwLok0 或上述可驗證 agent/system 活動相關的其他提交者活動。
- 截止日為 2026-09-29；資料中最後可見活動日期早於截止日，不代表截止日後沒有活動。
- Issues 與 comments 僅報告目前可由查詢結果確認的紀錄；未將他人活動推定為本人活動。

## 7. 可稽核來源

- Repository commits: https://github.com/SwLok0/atlas/commits/main?since=2025-05-01
- Pull requests: https://github.com/SwLok0/atlas/pulls?q=is%3Apr+created%3A%3E%3D2025-05-01
- Issues: https://github.com/SwLok0/atlas/issues?q=is%3Aissue+created%3A%3E%3D2025-05-01
