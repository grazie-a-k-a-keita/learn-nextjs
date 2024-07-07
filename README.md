## Learn Next.js

see the [course curriculum](https://nextjs.org/learn) on the Next.js Website.

### Develop

```bash
# project start
npx create-next-app@latest nextjs-dashboard --example "https://github.com/vercel/next-learn/tree/main/dashboard/starter-example" --use-pnpm

# package install
pnpm install

# server start
pnpm dev
```

### Deploy

```bash
openssl rand -base64 32
xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx
```

Vercel の `Environment Variables` に以下の設定を加える

```txt
AUTH_SECRET: xxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxxx
AUTH_URL: https://your-project-name.vercel.app/api/auth
```
