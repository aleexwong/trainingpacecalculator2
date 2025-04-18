# Training Pace Calculator 2

[![Netlify Status](https://api.netlify.com/api/v1/badges/2b8c6c05-12b2-423a-a2c2-af4e93e8f160/deploy-status)](https://app.netlify.com/sites/trainpace/deploys)[![Codacy Badge](https://app.codacy.com/project/badge/Grade/171bbd8a94744254a9db632e2650b6e4)](https://app.codacy.com/gh/aleexwong/trainingpacecalculator2/dashboard?utm_source=gh&utm_medium=referral&utm_content=&utm_campaign=Badge_grade)

---

This is my 2nd edition of my training pace calculator

- Google Analytics Metrics after 30 Days :)
  <img width="637" alt="trainPaceStats" src="https://github.com/user-attachments/assets/6f881b3f-b53e-4128-8b6b-baa93a466add" />

- URL hosted here: https://trainpace.netlify.app/

# Directory structure:

```plaintext
aleexwong-trainingpacecalculator2/
├── README.md
└── vite-project/
    ├── README.md
    ├── components.json
    ├── eslint.config.js
    ├── index.html
    ├── package-lock.json
    ├── package.json
    ├── postcss.config.js
    ├── tailwind.config.js
    ├── tsconfig.app.json
    ├── tsconfig.json
    ├── tsconfig.node.json
    ├── vite.config.ts
    ├── .gitignore
    ├── public/
    │   └── site.webmanifest
    └── src/
        ├── App.css
        ├── App.tsx
        ├── CalculatorModal.tsx
        ├── Footer.tsx
        ├── ResultsWithTooltips.tsx
        ├── RunningTips.tsx
        ├── TrainingPaceCalculator.tsx
        ├── index.css
        ├── main.tsx
        ├── vite-env.d.ts
        ├── assets/
        ├── components/
        │   └── ui/
        │       ├── accordion.tsx
        │       ├── button.tsx
        │       ├── card.tsx
        │       ├── dialog.tsx
        │       ├── input.tsx
        │       ├── select.tsx
        │       ├── toast.tsx
        │       ├── toaster.tsx
        │       └── tooltip.tsx
        ├── hooks/
        │   └── use-toast.ts
        ├── icons/
        └── lib/
            ├── GoogleAnalytics.tsx
            └── utils.ts
```

---

## 1st Edition

- https://github.com/aleexwong/marathon-training
- Project 1 is hosted here https://marathontraining.netlify.app/

but this time it is built with TypeScript and the Shadcn ui framework

- https://ui.shadcn.com/

---

Todo list:

- Host on Netlify - Done! 11/25/2024
- Icon for PWA and main site, Done! - 12/29/2024 report here:
  - https://realfavicongenerator.net/favicon-checker/reports/fd896a38-a6de-4ca6-b05c-fd99a10da526
- Testing with PlayWright
- Any new running tips I learn on the way
- Linking to any guides I find useful

ORIGINAL SOURCE: https://www.runnersworld.com/uk/training/a761676/rws-training-pace-calculator/
