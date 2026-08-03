
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

目前不要急著 Commit

你現在最正確的順序是：

修改 app/page.tsx
        ↓
儲存
        ↓
npm run build
        ↓
Build PASS
        ↓
Commit
        ↓
Push
        ↓
Vercel 自動部署
        ↓
Production URL
        ↓
瀏覽器實測

目前狀態：NOT VERIFIED

