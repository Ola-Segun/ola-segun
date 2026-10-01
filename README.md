<picture>
  <source media="(prefers-color-scheme: dark)" srcset="assets/header-dark.svg">
  <img alt="Segun Olaniyan. Frontend engineer: live data, real money, TypeScript. Ibadan, Nigeria, open to remote roles." src="assets/header-light.svg" width="100%">
</picture>

<p align="center">
  <a href="https://olasegun.netlify.app"><img alt="Portfolio" src="https://img.shields.io/badge/Portfolio-0969da?style=for-the-badge&logo=netlify&logoColor=white"></a>
  <a href="https://linkedin.com/in/segun-olaniyan-4286a0260"><img alt="LinkedIn" src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge"></a>
  <a href="mailto:olaniyanpaul012@gmail.com"><img alt="Email" src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white"></a>
  <img alt="Open to remote roles" src="https://img.shields.io/badge/Open_to_remote_roles-1a7f37?style=for-the-badge">
</p>

I'm a frontend engineer in Ibadan, Nigeria. Most of what I build is TypeScript UI with live data or real money behind it: React 19 and Next.js 16 day to day, Angular 21 in production, and Vue when the job needs it. I'm looking for **remote full-stack and frontend roles**.

## ⚡ Now

- 🩺 **Core contributor at AfriDam AI**, an AI dermatology platform. Since May 2026 I've led frontend across three production apps: a consumer skin-scan app and a specialist portal in Next.js 16, and a clinical annotation studio in Angular 21. In the first four months I merged **57 PRs (141 commits)** and did the final review before `main`.
- 🎓 **B.Sc. Computer Science** at the National Open University of Nigeria (in progress).

That work lives in private repos, so here are four things it involved:

| Problem | What I did |
| :-- | :-- |
| 💳 **Payment retries** | A second click on "Proceed to Payment" hit a unique constraint on the order, so the user could not pay at all. I cached the authorization URL per order so that retrying is idempotent. |
| 🔀 **A merge that would have undone 9 shipped fixes** | The branch was cut from a stale base and would have quietly reverted work from 4 merged PRs. I rebased it and kept its 3 real fixes. |
| 🔎 **Search results arriving out of order** | I added debounced server-side search, plus a guard so a slow response can't overwrite newer results. |
| 🔒 **Admin pages anyone could open by URL** | I built the app's first route-level `RoleGuard`. |

## 📦 Public work

<!--
Add when Fleet Live is published (repo + live URL), as the FIRST row of the table:

| [**Fleet Live**](https://github.com/Ola-Segun/fleet-live) | <img src="https://skillicons.dev/icons?i=nextjs,ts" height="28"> <sub>+ WebGL2 · MapLibre · Playwright</sub><br>A dispatcher's live map of 5,000 simulated trucks on Lagos roads, fed by GPS data that arrives late, out of order, twice or not at all. It renders trucks with raw WebGL2 on MapLibre, and replayed trucks land within 1.4 m (p95) of where the live map drew them. It also has alerts scored against simulator ground truth, 224 tests and CI. |
-->

| Project | What it shows |
| :-- | :-- |
| [**Signal Desk**](https://github.com/Ola-Segun/signal-desk) | <img src="https://skillicons.dev/icons?i=nextjs,ts,postgres,graphql,vitest" height="28"> <sub>+ Drizzle · viem (read-only)</sub><br>A market-research pipeline that only simulates trades. It includes a small prompt-evaluation experiment: the model echoed a score fed into its prompt, so I removed the score and a contract test keeps it out. It also has a GraphQL API that shares its service layer with REST, and a WebSocket stream that reconnects with backoff and jitter. |
| [**Portfolio**](https://olasegun.netlify.app) | <img src="https://skillicons.dev/icons?i=vite,js,netlify" height="28"> <sub>+ WebGL2 · GLSL · GSAP</sub><br>Hand-written WebGL2 shaders in place of three.js (that layer went from ~185 kB to ~6 kB gzipped), GSAP ScrollTrigger, and a design-token system tuned separately for light and dark. |
| [**V-Topup**](https://github.com/Ola-Segun/V-Topup-app-Full-implementation) | <img src="https://skillicons.dev/icons?i=nextjs,supabase,postgres" height="28"><br>A mobile-first, installable bill-payment PWA for Nigerian users. A wallet is funded through several payment gateways, and transactions are tracked live. |
| [**Inventory & POS**](https://github.com/Ola-Segun/Inventory_POS_system) | <img src="https://skillicons.dev/icons?i=nextjs,laravel,mysql" height="28"><br>Role-based access with HttpOnly-cookie auth, plus product, order and reporting workflows. Client work. |
| [**School platform**](https://github.com/Ola-Segun/Sch-p) | <img src="https://skillicons.dev/icons?i=vue,pinia,laravel,mysql" height="28"><br>A multi-role system for admins, lecturers and students, with different authorisation rules for each role. |
| [**Accessible Learning Path**](https://github.com/Ola-Segun/accessible-learning-path) | <img src="https://skillicons.dev/icons?i=react,ts,tailwind" height="28"> <sub>+ TanStack Start</sub><br>Interactive lessons built to work with a keyboard and a screen reader. |

## 🛠️ Toolbox

<table>
  <tr>
    <td><b>Daily</b></td>
    <td>
      <img src="https://skillicons.dev/icons?i=ts,react,nextjs,tailwind,vitest" height="40" alt="TypeScript, React, Next.js, Tailwind CSS, Vitest"><br>
      <img alt="Zustand" src="https://img.shields.io/badge/Zustand-443E38?style=flat-square">
      <img alt="TanStack Query" src="https://img.shields.io/badge/TanStack_Query-FF4154?style=flat-square&logo=reactquery&logoColor=white">
      <img alt="Playwright" src="https://img.shields.io/badge/Playwright-2EAD33?style=flat-square">
    </td>
  </tr>
  <tr>
    <td><b>In production</b></td>
    <td>
      <img src="https://skillicons.dev/icons?i=angular,vue,pinia,laravel,mysql,supabase,postgres" height="40" alt="Angular, Vue, Pinia, Laravel, MySQL, Supabase, PostgreSQL"><br>
      <img alt="Socket.IO" src="https://img.shields.io/badge/Socket.IO-010101?style=flat-square&logo=socketdotio&logoColor=white">
      <img alt="GSAP" src="https://img.shields.io/badge/GSAP-0AE448?style=flat-square&logo=greensock&logoColor=black">
    </td>
  </tr>
  <tr>
    <td><b>In public projects</b></td>
    <td>
      <img src="https://skillicons.dev/icons?i=graphql,alpinejs" height="40" alt="GraphQL, Alpine.js"><br>
      <img alt="Drizzle" src="https://img.shields.io/badge/Drizzle-C5F74F?style=flat-square&logo=drizzle&logoColor=black">
      <img alt="WebGL2" src="https://img.shields.io/badge/WebGL2-990000?style=flat-square&logo=webgl&logoColor=white">
      <img alt="Anthropic SDK" src="https://img.shields.io/badge/Anthropic_SDK-191919?style=flat-square&logo=anthropic&logoColor=white">
    </td>
  </tr>
  <tr>
    <td><b>Ship with</b></td>
    <td>
      <img src="https://skillicons.dev/icons?i=git,githubactions,vite,nodejs,netlify,vercel,cloudflare" height="40" alt="Git, GitHub Actions, Vite, Node.js, Netlify, Vercel, Cloudflare">
    </td>
  </tr>
</table>
