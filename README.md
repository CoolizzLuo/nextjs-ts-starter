This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

## Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `pages/index.tsx`. The page auto-updates as you edit the file.

[API routes](https://nextjs.org/docs/api-routes/introduction) can be accessed on [http://localhost:3000/api/hello](http://localhost:3000/api/hello). This endpoint can be edited in `pages/api/hello.ts`.

The `pages/api` directory is mapped to `/api/*`. Files in this directory are treated as [API routes](https://nextjs.org/docs/api-routes/introduction) instead of React pages.

This project uses [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) to automatically optimize and load Inter, a custom Google Font.

## Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

## Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.

## Git commit example

以下是專案中設定的 commitlint 規則：
- 提交訊息標題最大長度為 72 個字元。
- 提交類型必須是以下之一：`build`, `ci`, `chore`, `docs`, `feat`, `fix`, `perf`, `refactor`, `revert`, `style`, `test`。
- 提交主題必須使用句子大小寫（sentence-case）。

提交訊息範例：
- `build`: 針對構建系統或外部依賴的更改
  - 範例：`build: 升級 webpack 到 v5.0.0`
- `ci`: 針對持續集成配置的更改
  - 範例：`ci: 修復 Jenkinsfile 中的錯誤`
- `chore`: 對非業務邏輯程式碼的更改，例如更新開發工具
  - 範例：`chore: 更新 .gitignore 檔案`
- `docs`: 文件相關的更改
  - 範例：`docs: 新增 API 文件`
- `feat`: 新功能的添加
  - 範例：`feat: 新增使用者登入功能`
- `fix`: 修復程式錯誤
  - 範例：`fix: 修復購物車計算錯誤的問題`
- `perf`: 改善程式的性能
  - 範例：`perf: 降低首頁載入時間`
- `refactor`: 重構程式，但不改變其功能
  - 範例：`refactor: 重構購物車模塊`
- `revert`: 恢復先前的提交
  - 範例：`revert: 回滾至上一個版本`
- `style`: 改善程式碼風格，例如縮排、空格等
  - 範例：`style: 更新程式碼格式`
- `test`: 增加或修改測試程式
  - 範例：`test: 新增購物車功能的測試`
