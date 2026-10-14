<img width="100%" src="header.svg" alt="Terminal with Kamal and his cat" />

<p align="center">
  <a href="https://x.com/potential_dev">
    <img src="https://pbs.twimg.com/profile_images/2102061424579088384/2qKeUgjg_400x400.jpg" width="120" alt="Kamal on X" />
  </a>
</p>

<p align="center">
  <a href="https://github.com/KamalPixel">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=22&pause=1200&color=F4A261&center=true&vCenter=true&width=600&lines=Building+ChessNextDoor+%E2%99%9F%EF%B8%8F;Building+AI+learning+games+%40+Leqtio+%F0%9F%8E%AE;Shipping+client+sites+%40+verkstedweb.no+%F0%9F%9A%80;Stripe+%2B+Cloudflare+Workers+%2B+D1+%E2%9A%A1;Computer+Engineering+student+%40+H%C3%98+%F0%9F%8E%93" alt="Typing SVG" />
  </a>
</p>

<p align="center">
  <a href="https://leqtio.dev"><img src="https://img.shields.io/badge/Leqtio-leqtio.dev-2563EB?style=for-the-badge&logo=googlechrome&logoColor=white" /></a>
  <a href="https://verkstedweb.no"><img src="https://img.shields.io/badge/verkstedweb.no-agency-0f172a?style=for-the-badge&logo=cloudflare&logoColor=F38020" /></a>
  <a href="https://www.linkedin.com/in/kamal-mahad-317191308/"><img src="https://img.shields.io/badge/LinkedIn-Kamal_Mahad-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" /></a>
  <a href="https://x.com/potential_dev"><img src="https://img.shields.io/badge/X-@potential__dev-000000?style=for-the-badge&logo=x&logoColor=white" /></a>
  <a href="mailto:kamash02@outlook.com"><img src="https://img.shields.io/badge/Say_hi-Email-0078D4?style=for-the-badge&logo=microsoftoutlook&logoColor=white" /></a>
</p>

```ts
const kamal = {
  location: "Østfold, Norway",
  studying: "Computer Engineering",
  building: ["ChessNextDoor", "Leqtio", "verkstedweb.no"],
  currentlyLearning: ["Software testing", "Discrete math"],
  askMeAbout: ["Payment idempotency", "Cloudflare Workers", "AI in the classroom"],
};
```

## 🚀 Projects

<details>
<summary><b>♟️ ChessNextDoor</b> · a platform for learning chess · 🚧 In development</summary>
<br>

I'm building a platform where you learn chess from scratch. It's my newest project and hasn't launched yet.

</details>

<details>
<summary><b>🎮 Leqtio</b> · AI-generated learning games for teachers · 🏆 County champion</summary>
<br>

A teacher picks a curriculum goal and Leqtio generates a game the class can play.

- REST API in **Django Ninja** with Pydantic validation and OpenAPI docs
- **Claude API** integration that retries on 429 and 504 and filters inappropriate content
- Cascade deletes: removing a game wipes every row of student data tied to it (GDPR)
- We won the Østfold county final for student companies and competed in the national final

</details>

<details>
<summary><b>💳 Bakery webshop backend</b> · Stripe checkout on Cloudflare Workers</summary>
<br>

I moved the backend from PHP/MySQL to **TypeScript on Cloudflare Workers + D1**.

- Idempotency on three layers (client token, DB constraint, Stripe key) stops double charges
- The client sends product ID and quantity. The server sets the price in øre from a catalog built at deploy time
- Stripe webhooks with signature checks and event dedup trigger order emails through Resend
- PBKDF2 through WebCrypto keeps password hashing inside the 10 ms CPU limit

</details>

<details>
<summary><b>🍜 Restaurant booking + SMS</b> · full-stack reservation system</summary>
<br>

- Guests book online and get an SMS confirmation. Staff get an alert
- Guests who opt in get a review request by SMS 4 hours after their visit, never after 21:30
- Holiday mode turns off booking on set dates without a redeploy
- A custom prerender script turns React routes into static HTML with JSON-LD for SEO

</details>

## 🛠️ Stack

**Languages**

<p align="center">
  <img src="https://skillicons.dev/icons?i=ts,python,java,php,cpp" />
</p>

**Frameworks & tools**

<p align="center">
  <img src="https://skillicons.dev/icons?i=react,nextjs,tailwind,django,nodejs,postgres,cloudflare,docker,arduino" />
</p>

## 📊 Activity

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/KamalPixel/KamalPixel/output/github-snake-dark.svg" />
    <img alt="Snake eating my contributions" src="https://raw.githubusercontent.com/KamalPixel/KamalPixel/output/github-snake.svg" />
  </picture>
</p>

<img width="100%" src="https://capsule-render.vercel.app/api?type=rect&color=0:11151c,100:f4a261&height=6" />
