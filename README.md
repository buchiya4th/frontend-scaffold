## 設定関連
- Next.js の初期セットアップを以下で実行
  - What is your project named? frontend-scaffold
  - Would you like to use TypeScript? Yes
  - Would you like to use ESLint? Yes
  - Would you like to use Tailwind CSS? No
  - Would you like to use `src/` directory? No
  - Would you like to use App Router? (recommended) Yes
  - Would you like to customize the default import alias (@/*)? No
- Node.js 関連の実行環境
  - volta で管理
  - Node.js: 20.10.0
  - yarn: 4.0.2
    - `.yarnrc.yml` で node_modules ディレクトリが生成されるように修正
- .gitignore の更新
  - デフォルトでは /.next, /node_modules 等を除外していないので更新

## Next.js の npx create-next-app@latest の README.md
This is a [Next.js](https://nextjs.org/) project bootstrapped with [`create-next-app`](https://github.com/vercel/next.js/tree/canary/packages/create-next-app).

### Getting Started

First, run the development server:

```bash
npm run dev
# or
yarn dev
# or
pnpm dev
# or
bun dev
```

Open [http://localhost:3000](http://localhost:3000) with your browser to see the result.

You can start editing the page by modifying `app/page.tsx`. The page auto-updates as you edit the file.

This project uses [`next/font`](https://nextjs.org/docs/basic-features/font-optimization) to automatically optimize and load Inter, a custom Google Font.

### Learn More

To learn more about Next.js, take a look at the following resources:

- [Next.js Documentation](https://nextjs.org/docs) - learn about Next.js features and API.
- [Learn Next.js](https://nextjs.org/learn) - an interactive Next.js tutorial.

You can check out [the Next.js GitHub repository](https://github.com/vercel/next.js/) - your feedback and contributions are welcome!

### Deploy on Vercel

The easiest way to deploy your Next.js app is to use the [Vercel Platform](https://vercel.com/new?utm_medium=default-template&filter=next.js&utm_source=create-next-app&utm_campaign=create-next-app-readme) from the creators of Next.js.

Check out our [Next.js deployment documentation](https://nextjs.org/docs/deployment) for more details.
