# SCM 庫存功能優化 — 互動原型

KKday SCM Web 2026 Q1「庫存功能優化」的單檔互動原型。

## 使用方式
直接用瀏覽器打開 `index.html` 即可（離線可跑，相依的 Vue / Ant Design Vue / dayjs 都放在 `vendor/`）。

## 內容
- 5 種庫存模式（東京迪士尼 ind_ind、河口湖 ind_shared、大阪周遊卡 shared_ind、teamLab shared_shared、eSIM unlimited）。
- 月曆選取（單日 / Shift 連續區間 / Cmd·Ctrl 分散多選 / 平日・週末篩選）、右側批次面板、可售狀態、篩選範圍、庫存模式精靈等。
- 依 Figma 設計稿還原，單檔 `index.html`（in-DOM template，無建置流程）。
