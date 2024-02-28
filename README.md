# Supabase Auth Example 

How do you integrate supabase auth with Instant? This repo gives you an example to do just that! 

To run everything: 

```
cd server
yarn 
yarn dev
```

```
cd frontend
yarn 
yarn dev
```

Now load the page on http://localhost:5173 and get playin :) 

There's two files to understand: 

1. server/index.ts 
   1. This creates an endpoint that generates instant tokens
2. frontend/src/App.tsx
   1. This handles sync between supabase and Instant!
