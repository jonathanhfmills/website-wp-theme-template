<!-- Generated: 2026-05-09 | Updated: 2026-05-09 -->

# website-wp-theme-template

## 要旨
WordPress主題範本資源庫。包含主題清單及組件結構之定義。代理人得據此建構主題變體，或擴展核心功能。此庫存無獨立部署；隸屬更大之網站建設事業。

## 要覽
| 檔案 | 說明 |
|------|------|
| `composer.json` | 套件宣告：型別 `wordpress-theme`，名稱 `jonathanhfmills/website-wp-theme-template`，版本 0.1.0 |
| `style.css` | WordPress主題頁首：主題名稱、版本宣示 |

## 為人工智能代理

### 工作規範
- 本庫存為主題樣板，非生產主題。勿直接修改版本號；應由編排器管理指標。
- 主題功能實作應置於適當子目錄（如 `template-parts/`、`inc/`），後續代理可據此擴展。
- 所有提交遵循 `tag: Description` 格式（無作用域、無頁腳）。有效標籤：`feat`、`fix`、`bug`、`chore`、`docs`、`style`、`refactor`、`perf`、`test`、`infra`。
- composer.json 中之依賴應明確列舉；勿引入未紀錄之隱性依賴。

### 常見模式
- 主題變體由分支或孤立提交標記；樣板本身維持最小狀態。
- 新功能區塊應隨文檔提交，記錄其用途與掛鉤點。
- 版本遞增遵循語義化版本規範（MAJOR.MINOR.PATCH）。

## 依賴

### 外部
- WordPress 核心：主題由 WordPress.org 環境載入並驅動。
- Composer：package 管理與自動加載（若有依賴包）。

<!-- MANUAL: Any manually added notes below this line are preserved on regeneration -->
