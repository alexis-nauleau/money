npx create-next-app@latest ./
npm i -D daisyui@latest
npm install @clerk/nextjs
.env ( a ne pas partager mais ici c'est un exercice)
NEXT_PUBLIC_CLERK_PUBLISHABLE_KEY=pk_test_b25lLW1vbmtmaXNoLTU3LmNsZXJrLmFjY291bnRzLmRldiQ
CLERK_SECRET_KEY=sk_test_sYcwl1wO7ENURu13zGErhquvAi3ehq2jBGil0ZebQy
NEXT_PUBLIC_CLERK_SIGN_IN_URL=/sign-in
NEXT_PUBLIC_CLERK_SIGN_UP_URL=/sign-up
NEXT_PUBLIC_CLERK_SIGN_UP_FORCE_REDIRECT_URL="/"
NEXT_PUBLIC_CLERK_SIGN_IN_FORCE_REDIRECT_URL="/"


npm i prisma --save-dev
npx prisma init --datasource-provider sqlite

Dans package.json aller dans depedencies, ajouter "@prisma/client": "^6.0.0"   la version est celle de  dans devDependencies

creation de modals

npx prisma migrate dev --name add_models
npx prisma generate
npx prisma studio (voir la bdd)
npm install emoji-picker-react --force

 npm i lucide-react
 npm install recharts --force


