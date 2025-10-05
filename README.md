secrets-bangladesh-app/
│
├── app/
│   ├── layout.tsx
│   ├── page.tsx
│   └── loom/
│       └── page.tsx           ← new universal loom page
│
├── components/
│   ├── Loom.tsx               (old version, optional backup)
│   └── FreeformLoom.tsx       ← new free-roam luminous loom
│
├── pages/
│   └── loom.tsx               ← same as above (only if using pages router)
│
├── public/
│   ├── cinematics/
│   │   ├── merged-cinematic-scroll.html
│   │   ├── 1secrets-archive-blacktomato.html
│   │   └── flip-shuffle-updated.html
│   ├── favicon.ico
│   ├── app-icon.png
│   └── manifest.json
│
├── styles/
│   ├── globals.css
│   └── globals-extra.css      ← optional polish (dark BG + smoothing)
│
├── package.json
├── tsconfig.json
├── next.config.js
├── tailwind.config.js
├── postcss.config.js
└── README-PATCH.md            ← install instructions (for reference)
