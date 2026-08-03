
GitHub Repository
└── app/
    └── page.tsx    ←  GUBON React 

name: Build
on: push

jobs:
  build:
    ...

 GitHub Actions / Docker BuildKit workflow

① app/page.tsx
 Next.js 

export default function Home() {
  return (
    <main className="min-h-screen bg-black text-white">
      ...
    </main>
  );
}

② app/layout.tsx

 Vercel Analytics,

import { Analytics } from "@vercel/analytics/next";

<Analytics />


Docker BuildKit
GitHub Actions
name: Build
jobs:
runs-on
docker/build-push-action

.github/
└── workflows/
    └── build.yml


GUBON/
├── app/
│   ├── layout.tsx
│   └── page.tsx
│
├── .github/
│   └── workflows/
│       └── build.yml
│
├── package.json
├── next.config.ts
├── tsconfig.json
└── ...


 app/page.tsx
        ↓

        ↓
npm run build
        ↓
Build PASS
        ↓
Commit
        ↓
Push
        ↓
Vercel 
        ↓
Production URL
        ↓


   NOT VERIFIED 

