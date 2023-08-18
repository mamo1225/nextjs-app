■ プロジェクト作成
npx create-next-app nextjs-app --use-npm


C:\Asano\sample-src\nextjsApp>npx create-next-app nextjs-app --use-npm
√ Would you like to use TypeScript? ... Yes
√ Would you like to use ESLint? ... Yes
√ Would you like to use Tailwind CSS? ... Yes
√ Would you like to use `src/` directory? ... Yes
√ Would you like to use App Router? (recommended) ... No
√ Would you like to customize the default import alias? ... No
Creating a new Next.js app in C:\Asano\sample-src\nextjsApp\nextjs-app.

Using npm.

Initializing project with template: default-tw


Installing dependencies:
- react
- react-dom
- next
- typescript
- @types/react
- @types/node
- @types/react-dom
- tailwindcss
- postcss
- autoprefixer
- eslint
- eslint-config-next


added 349 packages, and audited 350 packages in 2m

131 packages are looking for funding
  run `npm fund` for details

found 0 vulnerabilities
Success! Created nextjs-app at C:\Asano\sample-src\nextjsApp\nextjs-app

A new version of `create-next-app` is available!
You can update by running: npm i -g create-next-app




■ 実行
cd nextjs-app
npm run dev



■動作確認
http://localhost:3000



■next.jsのバージョン確認方法
 package.jsonの「next」の値を参照



https://reffect.co.jp/react/next-js-13-app/