<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0f172a,100:2563eb&height=200&section=header&text=Kamal&fontSize=70&fontColor=ffffff&animation=fadeIn&desc=Software%20Engineer%20in%20the%20making&descAlignY=72&descSize=18" />

<p align="center">
  <a href="https://github.com/KamalPixel">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=22&pause=1200&color=2563EB&center=true&vCenter=true&width=600&lines=Building+AI+learning+games+%40+Leqtio+%F0%9F%8E%AE;Shipping+client+sites+%40+verkstedweb.no+%F0%9F%9A%80;Stripe+%2B+Cloudflare+Workers+%2B+D1+%E2%9A%A1;Computer+Engineering+student+%40+H%C3%98+%F0%9F%8E%93" alt="Typing SVG" />
  </a>
</p>

<p align="center">
  <a href="https://leqtio.dev"><img src="https://img.shields.io/badge/Leqtio-leqtio.dev-2563EB?style=for-the-badge&logo=googlechrome&logoColor=white" /></a>
  <a href="https://verkstedweb.no"><img src="https://img.shields.io/badge/verkstedweb.no-agency-0f172a?style=for-the-badge&logo=cloudflare&logoColor=F38020" /></a>
  <a href="mailto:kamash02@outlook.com"><img src="https://img.shields.io/badge/Say_hi-Email-0078D4?style=for-the-badge&logo=microsoftoutlook&logoColor=white" /></a>
</p>

```ts
const kamal = {
  location: "Østfold, Norway 🇳🇴",
  studying: "Computer Engineering @ HiØ",
  building: ["Leqtio", "verkstedweb.no"],
  currentlyLearning: ["Software testing", "Discrete math"],
  askMeAbout: ["Payments without double charges", "Edge computing", "AI in education"],
};
```

## 🚀 Projects

<details>
<summary><b>🎮 Leqtio</b> – AI-generated learning games for teachers · 🏆 County champion</summary>
<br>

Teachers pick a curriculum goal, Leqtio generates a playable game for the class.

- REST API with **Django Ninja**, Pydantic validation and auto-generated OpenAPI docs
- Resilient **Claude API** integration: handles 429/504 and filters inappropriate content
- GDPR by design: cascade deletes wipe all student data when a game is removed
- Won the Østfold county final for student companies, went on to the national final

</details>

<details>
<summary><b>💳 Bakery webshop backend</b> – Stripe checkout on Cloudflare Workers</summary>
<br>

Migrated from PHP/MySQL to **TypeScript on Cloudflare Workers + D1**.

- Three-layer idempotency so no customer is ever charged twice
- Price tampering impossible: client sends only product ID + quantity, amounts in øre server-side
- Signed Stripe webhooks with event dedup, transactional email via Resend
- PBKDF2 via WebCrypto to fit the 10 ms CPU budget

</details>

<details>
<summary><b>🍜 Restaurant booking + SMS</b> – full-stack reservation system</summary>
<br>

- Booking page with SMS confirmations to guests and alerts to staff
- Consent-based review follow-up SMS, with a "no texts after 21:30" rule
- Date-driven holiday mode that disables booking without a redeploy
- Custom prerender script for React routes + JSON-LD for SEO

</details>

## 🛠️ Stack

<p align="center">
  <img src="https://skillicons.dev/icons?i=ts,js,python,php,react,nextjs,tailwind,django,nodejs,postgres,mysql,sqlite,cloudflare,docker,git,figma&perline=8" />
</p>

## 📊 Activity

<p align="center">
  <img src="https://github-readme-activity-graph.vercel.app/graph?username=KamalPixel&bg_color=0f172a&color=93c5fd&line=2563eb&point=ffffff&area=true&hide_border=true" width="100%" />
</p>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/KamalPixel/KamalPixel/output/github-snake-dark.svg" />
    <img alt="Snake eating my contributions" src="https://raw.githubusercontent.com/KamalPixel/KamalPixel/output/github-snake.svg" />
  </picture>
</p>

<img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:2563eb,100:0f172a&height=120&section=footer" />
