

export default function Home() {
  return (
    <main className="min-h-screen bg-black text-white">
      {/* Header */}
      <header className="border-b border-white/10">
        <div className="mx-auto flex h-20 w-full max-w-7xl items-center justify-between px-6 lg:px-10">
          <div>
            <div className="text-lg font-semibold tracking-[0.25em]">
              GUBON
            </div>
            <div className="text-[10px] tracking-[0.35em] text-zinc-500">
              LUCID OS
            </div>
          </div>

          <div className="hidden items-center gap-8 text-sm text-zinc-400 sm:flex">
            <a href="#system" className="transition hover:text-white">
              SYSTEM
            </a>
            <a href="#process" className="transition hover:text-white">
              PROCESS
            </a>
            <a href="#access" className="transition hover:text-white">
              ACCESS
            </a>
          </div>

          <a
            href="#access"
            className="rounded-full border border-emerald-400/40 px-5 py-2 text-xs font-medium tracking-wider text-emerald-300 transition hover:border-emerald-300 hover:bg-emerald-400/10"
          >
            ENTER
          </a>
        </div>
      </header>

      {/* Hero */}
      <section className="relative overflow-hidden">
        <div className="absolute inset-0 bg-[radial-gradient(circle_at_50%_35%,rgba(16,185,129,0.12),transparent_35%)]" />

        <div className="relative mx-auto flex min-h-[calc(100vh-80px)] w-full max-w-7xl flex-col items-center justify-center px-6 py-24 text-center lg:px-10">
          <div className="mb-8 inline-flex items-center gap-3 rounded-full border border-white/10 bg-white/[0.03] px-4 py-2 text-[10px] tracking-[0.3em] text-zinc-400">
            <span className="h-1.5 w-1.5 rounded-full bg-emerald-400" />
            DECISION INTELLIGENCE RUNTIME
          </div>

          <h1 className="max-w-5xl text-5xl font-semibold leading-[1.05] tracking-tight sm:text-7xl lg:text-8xl">
            GUBON
            <span className="block text-zinc-500">LUCID OS</span>
          </h1>

          <p className="mt-8 max-w-2xl text-base leading-8 text-zinc-400 sm:text-lg">
            將你正在面對的人生問題、關鍵資料與當下狀態，
            轉化為可理解、可判斷、可行動的決策情報。
          </p>

          <div className="mt-12 flex w-full flex-col gap-4 sm:w-auto sm:flex-row">
            <a
              href="#access"
              className="flex h-14 items-center justify-center rounded-full bg-white px-8 text-sm font-semibold text-black transition hover:bg-zinc-200"
            >
              開始決策分析
            </a>

            <a
              href="#system"
              className="flex h-14 items-center justify-center rounded-full border border-white/15 px-8 text-sm text-white transition hover:bg-white/5"
            >
              查看系統
            </a>
          </div>

          <div className="mt-20 grid w-full max-w-3xl grid-cols-3 divide-x divide-white/10 border-y border-white/10 py-6">
            <div>
              <div className="text-xl font-semibold">01</div>
              <div className="mt-2 text-[10px] tracking-widest text-zinc-500">
                INPUT
              </div>
            </div>

            <div>
              <div className="text-xl font-semibold">02</div>
              <div className="mt-2 text-[10px] tracking-widest text-zinc-500">
                DECISION
              </div>
            </div>

            <div>
              <div className="text-xl font-semibold">03</div>
              <div className="mt-2 text-[10px] tracking-widest text-zinc-500">
                ACTION
              </div>
            </div>
          </div>
        </div>
      </section>

      {/* System */}
      <section id="system" className="border-t border-white/10">
        <div className="mx-auto w-full max-w-7xl px-6 py-24 lg:px-10">
          <div className="max-w-2xl">
            <div className="text-xs tracking-[0.3em] text-emerald-400">
              GUBON DECISION CORE
            </div>

            <h2 className="mt-5 text-4xl font-semibold tracking-tight sm:text-5xl">
              不只是報告。
              <br />
              是一套決策流程。
            </h2>

            <p className="mt-6 leading-8 text-zinc-400">
              GUBON LUCID OS 將使用者輸入、分析引擎、AI
              生成、摘要、解鎖與後續行動串接成完整流程。
            </p>
          </div>

          <div className="mt-16 grid gap-px overflow-hidden rounded-2xl border border-white/10 bg-white/10 md:grid-cols-3">
            <article className="bg-black p-8">
              <div className="text-xs text-zinc-600">01</div>
              <h3 className="mt-10 text-xl font-medium">INPUT</h3>
              <p className="mt-4 text-sm leading-7 text-zinc-500">
                建立個人資料與當下主要問題，形成決策分析的輸入上下文。
              </p>
            </article>

            <article className="bg-black p-8">
              <div className="text-xs text-zinc-600">02</div>
              <h3 className="mt-10 text-xl font-medium">INTELLIGENCE</h3>
              <p className="mt-4 text-sm leading-7 text-zinc-500">
                經過 Decision Engine 與 AI Runtime 處理，產生個人化決策情報。
              </p>
            </article>

            <article className="bg-black p-8">
              <div className="text-xs text-zinc-600">03</div>
              <h3 className="mt-10 text-xl font-medium">ACTION</h3>
              <p className="mt-4 text-sm leading-7 text-zinc-500">
                從分析結果進入下一步行動、解鎖內容與後續決策流程。
              </p>
            </article>
          </div>
        </div>
      </section>

      {/* Process */}
      <section id="process" className="border-t border-white/10">
        <div className="mx-auto w-full max-w-7xl px-6 py-24 lg:px-10">
          <div className="flex flex-col justify-between gap-8 md:flex-row md:items-end">
            <div>
              <div className="text-xs tracking-[0.3em] text-emerald-400">
                DECISION FLOW
              </div>

              <h2 className="mt-5 text-4xl font-semibold sm:text-5xl">
                從問題開始。
              </h2>
            </div>

            <p className="max-w-md text-sm leading-7 text-zinc-500">
              每一次分析都從真實輸入開始，經過處理後產生對應的決策結果。
            </p>
          </div>

          <div className="mt-16 space-y-0 border-t border-white/10">
            {[
              ["01", "Identity", "建立個人決策上下文"],
              ["02", "Question", "鎖定目前最主要的問題"],
              ["03", "Analysis", "執行 Decision Intelligence"],
              ["04", "Preview", "取得分析摘要與初步結果"],
              ["05", "Unlock", "進入完整核心內容"],
              ["06", "Action", "取得下一步行動方向"],
            ].map(([number, title, description]) => (
              <div
                key={number}
                className="grid gap-4 border-b border-white/10 py-7 md:grid-cols-[80px_220px_1fr] md:items-center"
              >
                <span className="text-xs text-zinc-600">{number}</span>
                <span className="text-lg font-medium">{title}</span>
                <span className="text-sm text-zinc-500">{description}</span>
              </div>
            ))}
          </div>
        </div>
      </section>

      {/* Access */}
      <section id="access" className="border-t border-white/10">
        <div className="mx-auto w-full max-w-7xl px-6 py-28 lg:px-10">
          <div className="relative overflow-hidden rounded-3xl border border-emerald-400/20 bg-emerald-400/[0.03] p-8 sm:p-12 lg:p-16">
            <div className="absolute right-0 top-0 h-64 w-64 rounded-full bg-emerald-400/10 blur-3xl" />

            <div className="relative max-w-3xl">
              <div className="text-xs tracking-[0.3em] text-emerald-400">
                ACCESS GATEWAY
              </div>

              <h2 className="mt-6 text-4xl font-semibold tracking-tight sm:text-6xl">
                你的下一個決策，
                <br />
                從這裡開始。
              </h2>

              <p className="mt-6 max-w-xl leading-8 text-zinc-400">
                輸入你的資料與目前正在面對的問題，開始建立專屬決策分析。
              </p>

              <a
                href="/analysis"
                className="mt-10 inline-flex h-14 items-center justify-center rounded-full bg-white px-8 text-sm font-semibold text-black transition hover:bg-zinc-200"
              >
                開始分析
              </a>
            </div>
          </div>
        </div>
      </section>

      {/* Footer */}
      <footer className="border-t border-white/10">
        <div className="mx-auto flex w-full max-w-7xl flex-col gap-4 px-6 py-8 text-xs text-zinc-600 sm:flex-row sm:items-center sm:justify-between lg:px-10">
          <div className="tracking-[0.2em]">GUBON LUCID OS</div>
          <div>DECISION INTELLIGENCE PLATFORM</div>
        </div>
      </footer>
    </main>
  );
}

檔案位置

如果你目前是標準 Next.js App Router：

app/
├── layout.tsx
└── page.tsx    ← 替換成上面內容

如果你的專案是 src 結構：

src/
└── app/
    ├── layout.tsx
    └── page.tsx    ← 替換

狀態：NOT VERIFIED

