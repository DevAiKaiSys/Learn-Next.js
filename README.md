## Next.js App Router Course - Starter

[Next.js Learn Course](https://nextjs.org/learn)

```
npx create-next-app@latest nextjs-dashboard --use-npm --example "https://github.com/vercel/next-learn/tree/main/dashboard/starter-example"
```

# Cloud Database Vercel

```
npm i -g vercel
vercel link
```

```
npm i @vercel/postgres
```

```
npm run seed
```

run the code after a specific time once the user has stopped

```
npm i use-debounce
```

# Using the ESLint accessibility plugin in Next.js

By default, Next.js includes the [eslint-plugin-jsx-a11y](https://github.com/jsx-eslint/eslint-plugin-jsx-a11y)

```
npm run lint
```

# Authentication

[NextAuth.js](https://authjs.dev/reference/nextjs)

```
npm install next-auth@beta
```

generate a secret key

```
openssl rand -base64 32
```
or [go to](https://generate-secret.vercel.app/32)