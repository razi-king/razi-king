<!-- 👑 Razi King — Backend Engineer (Go) · Full-Stack -->

<p align="center">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:0d0221,40:3b1466,75:8E2DE2,100:c084fc&height=260&section=header&text=%F0%9F%91%91%20Razi%20King&fontSize=70&fontColor=FFD700&fontAlignY=36&desc=Razi%20Ahmed%20%E2%80%A2%20Backend%20Engineer%20(Go)%20%E2%80%A2%20Full-Stack%20Developer&descSize=19&descAlignY=58&animation=fadeIn" alt="Razi King"/>
</p>

<p align="center">
  <a href="https://github.com/razi-king">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=21&duration=3000&pause=800&color=FFD700&center=true&vCenter=true&width=700&lines=Ruling+the+backend+with+Go+%F0%9F%91%91;Airline+%26+transfer+supplier+integrations+%E2%9C%88%EF%B8%8F;Goroutines+%E2%80%A2+PostgreSQL+%E2%80%A2+Redis+%E2%80%A2+MongoDB;Crafting+frontends+in+React%2C+Astro+%26+Tailwind;Shipping+code+that+survives+production+%F0%9F%9B%A1%EF%B8%8F" alt="Typing intro"/>
  </a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Backend-Go%20%7C%20Java-00ADD8?style=for-the-badge&logo=go&logoColor=white&labelColor=1a0b2e"/>
  <img src="https://img.shields.io/badge/Frontend-React%20%7C%20Astro-61DAFB?style=for-the-badge&logo=react&logoColor=61DAFB&labelColor=1a0b2e"/>
  <img src="https://img.shields.io/badge/Domain-Travel%20Tech-FFD700?style=for-the-badge&logo=googlemaps&logoColor=FFD700&labelColor=1a0b2e"/>
  <br/>
  <img src="https://komarev.com/ghpvc/?username=razi-king&label=Royal%20Visitors&color=8E2DE2&style=flat-square" alt="Profile views"/>
  <img src="https://img.shields.io/github/followers/razi-king?label=Followers&style=flat-square&color=FFD700&labelColor=1a0b2e" alt="Followers"/>
  <img src="https://img.shields.io/badge/Open%20to-Backend%20roles-8E2DE2?style=flat-square&labelColor=1a0b2e"/>
  <a href="https://razi-king.github.io/Portfolio/"><img src="https://img.shields.io/badge/Portfolio-razi--king.github.io-F2C14E?style=flat-square&labelColor=1a0b2e"/></a>
</p>

---

## 👑 The King, Compiled

```go
package main

type Engineer struct {
	Name       string
	Alias      string
	Role       string
	Kingdom    string
	Weapons    []string
	Conquering []string
}

func main() {
	razi := Engineer{
		Name:       "Razi Ahmed",
		Alias:      "Razi King 👑",
		Role:       "Backend Engineer @ Infohybrid (Travel Tech)",
		Kingdom:    "Mumbai, India",
		Weapons:    []string{"Go", "PostgreSQL", "Redis", "MongoDB", "Java", "Spring Boot", "React"},
		Conquering: []string{"Airline integrations", "Booking engines", "High-concurrency APIs"},
	}
	razi.Build("systems that survive production")
}
```

- 🏰 **Now:** writing Go for a live flight and transfer booking engine. I take suppliers from first API call to production.
- ⚔️ **Strongest at:** goroutines and concurrency, PostgreSQL debugging, Redis and MongoDB caching, supplier API design
- 🎨 **Also at home in:** React, Astro, Next.js and Tailwind. I've shipped CRMs, websites and storefronts end to end.
- 🎓 **B.Sc. IT**, University of Mumbai, CGPA **9.3 / 10**

---

## 🏰 Conquests in Production

> From my day job. The code is private, so here is what it does and how it was built.

| ⚔️ Campaign | What I did | Stack |
|---|---|---|
| ✈️ **TripJack integration** | Full flight booking flow: search, branded fares, price validation, ancillaries, hold-then-confirm, ticketing | Go · PostgreSQL |
| 🛫 **Akasa Air integration** | Resolved integration defects and took it through QA sign-off for production release | Go |
| 🛠️ **Critical price-change fix** | Booking was saved before supplier confirmation and never updated on fare change; traced it through app logic, a broken SQL query and an SQL function | Go · SQL |
| 🛡️ **3 inherited airlines** | Took over FlyArystan, SalamAir and ASL Airlines after the original dev left | Go |
| 🚖 **Transfer booking platform** | Built from scratch on Amadeus Transfer Quick Connect, including booking lifecycle and commission rules | Go · PostgreSQL |
| ⚡ **Parallel multi-city search** | Fan-out of one-way supplier calls with goroutines and a panic-safe `safeGo()` wrapper | Go concurrency |
| 🚀 **O(n×m) → O(n+m)** | Hashmap-based offer matching, benchmarked with `testing.B` | Go |
| 📨 **Fault-tolerant email system** | RabbitMQ with retries, dead-letter queues and a parking-lot queue (internship CRM) | Java · RabbitMQ |

---

## ⚙️ Backend Realm

<p align="center">
  <a href="https://github.com/razi-king/Portfolio"><b>🌐 Portfolio Platform</b></a>: a Three.js site with an <b>event-driven Go backend</b>.<br/>
  Contact messages flow <b>Go API → PostgreSQL → RabbitMQ → email worker</b>, with retry queues, a DLQ and a parking lot, and integration tests run in CI.<br/><br/>
  <a href="https://razi-king.github.io/Portfolio/"><img src="https://img.shields.io/badge/Open%20the%20live%20site-F2C14E?style=for-the-badge&labelColor=1a0b2e&logo=threedotjs&logoColor=F2C14E"/></a>
  <img src="https://img.shields.io/badge/Go-00ADD8?style=for-the-badge&logo=go&logoColor=white"/>
  <img src="https://img.shields.io/badge/RabbitMQ-FF6600?style=for-the-badge&logo=rabbitmq&logoColor=white"/>
  <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=for-the-badge&logo=postgresql&logoColor=white"/>
</p>

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>💰 <a href="https://github.com/razi-king/Expense-Tracker">Expense Tracker</a></h3>
      Personal finance dashboard: monthly totals, a category donut and a 6-month trend, plus add, edit and delete. Stateless JWT security with every query scoped to the logged-in user. Integration-tested against Postgres in CI.
      <br/><br/>
      <img src="https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white"/>
      <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white"/>
      <img src="https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens"/>
      <img src="https://img.shields.io/badge/Astro-BC52EE?style=flat-square&logo=astro&logoColor=white"/>
    </td>
    <td width="50%" valign="top">
      <h3>💬 <a href="https://github.com/razi-king/SpringProjects/tree/main/ChatAppBackend">Real-time Chat</a></h3>
      Live chat rooms over STOMP/WebSocket with <b>who's online</b>, <b>typing indicators</b> and paginated history in MongoDB. The <a href="https://razi-king.github.io/SpringProjects/">React client</a> reconnects on its own. A live STOMP test runs in CI.
      <br/><br/>
      <img src="https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white"/>
      <img src="https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white"/>
      <img src="https://img.shields.io/badge/WebSocket-010101?style=flat-square&logo=socketdotio"/>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>🏪 Smart Vendor App <sub><i>(in progress)</i></sub></h3>
      Multi-tenant SaaS for retailers with many outlets: Admin / Vendor / User RBAC and tenant data isolation. Inventory, orders and analytics on the way.
      <br/><br/>
      <img src="https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white"/>
      <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white"/>
    </td>
    <td width="50%" valign="top">
      <h3>📦 <a href="https://github.com/razi-king/SpringProjects">Spring Projects</a></h3>
      My Spring Boot workshop: chat backend, expense tracker, mail sender and a student management system, each one a step up in architecture.
      <br/><br/>
      <img src="https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white"/>
      <img src="https://img.shields.io/badge/Spring-6DB33F?style=flat-square&logo=spring&logoColor=white"/>
    </td>
  </tr>
</table>

---

## 🎨 Frontend Kingdom

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>🛍️ <a href="https://razi-king.github.io/E_Com/">Kumo Fashion Store — live</a></h3>
      A shop you can actually use: search, filters and sorting in the URL, product pages with sizes and stock, a persistent bag, and checkout with validation.
      <br/><br/>
      <img src="https://img.shields.io/badge/React%2019-20232A?style=flat-square&logo=react&logoColor=61DAFB"/>
      <img src="https://img.shields.io/badge/React%20Router%207-CA4245?style=flat-square&logo=reactrouter&logoColor=white"/>
      <img src="https://img.shields.io/badge/Tailwind%204-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white"/>
    </td>
    <td width="50%" valign="top">
      <h3>⚛️ <a href="https://razi-king.github.io/ReactJs-25-Project/">React Components Lab — live</a></h3>
      9 accessible components in one app: tree view, image slider, QR generator, load-more pagination and more, each with keyboard support and loading/error states.
      <br/><br/>
      <img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB"/>
      <img src="https://img.shields.io/badge/Hooks-8E2DE2?style=flat-square"/>
      <img src="https://img.shields.io/badge/Vite-646CFF?style=flat-square&logo=vite&logoColor=white"/>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>🌐 Institute Website <sub><i>(internship)</i></sub></h3>
      Public website for ITDaksh Education, built with Astro, React and Tailwind. Its lead forms feed straight into the CRM backend I built.
      <br/><br/>
      <img src="https://img.shields.io/badge/Astro-BC52EE?style=flat-square&logo=astro&logoColor=white"/>
      <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white"/>
      <img src="https://img.shields.io/badge/Tailwind-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white"/>
    </td>
    <td width="50%" valign="top">
      <h3>💰 <a href="https://razi-king.github.io/expense-tracker/">Expense Tracker UI</a></h3>
      Astro + React dashboard with Recharts: monthly summary cards, category donut, 6-month trend, and an accessible add/edit dialog.
      <br/><br/>
      <img src="https://img.shields.io/badge/GitHub%20Pages-222222?style=flat-square&logo=githubpages&logoColor=white"/>
      <img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB"/>
    </td>
  </tr>
</table>

---

## 🛡️ The Royal Arsenal

<p align="center"><b>⚙️ Backend</b><br/><br/>
  <img src="https://skillicons.dev/icons?i=go,java,spring,python,rabbitmq&theme=dark&perline=10" />
</p>
<p align="center"><b>🗄️ Data</b><br/><br/>
  <img src="https://skillicons.dev/icons?i=postgres,mysql,mongodb,redis,azure&theme=dark&perline=10" />
</p>
<p align="center"><b>🎨 Frontend</b><br/><br/>
  <img src="https://skillicons.dev/icons?i=ts,js,react,nextjs,astro,tailwind,html,css&theme=dark&perline=10" />
</p>
<p align="center"><b>🧰 Tools</b><br/><br/>
  <img src="https://skillicons.dev/icons?i=docker,git,github,postman,linux,vscode&theme=dark&perline=10" />
</p>

---

## 📈 The Royal Ledger

<p align="center">
  <img height="170" src="https://github-readme-stats.vercel.app/api?username=razi-king&show_icons=true&hide_border=true&bg_color=0D1117&title_color=FFD700&icon_color=8E2DE2&text_color=E6E6E6&ring_color=FFD700&include_all_commits=true&count_private=true&rank_icon=github" alt="GitHub stats"/>
  <img height="170" src="https://streak-stats.demolab.com/?user=razi-king&hide_border=true&background=0D1117&ring=FFD700&fire=8E2DE2&currStreakLabel=FFD700&sideLabels=E6E6E6&dates=999999&currStreakNum=E6E6E6&sideNums=E6E6E6" alt="Streak stats"/>
</p>
<p align="center">
  <img height="150" src="https://github-readme-stats.vercel.app/api/top-langs/?username=razi-king&layout=compact&hide_border=true&bg_color=0D1117&title_color=FFD700&text_color=E6E6E6&langs_count=8" alt="Top languages"/>
</p>
<p align="center">
  <img width="95%" src="https://github-readme-activity-graph.vercel.app/graph?username=razi-king&bg_color=0D1117&color=FFD700&line=8E2DE2&point=FFD700&area=true&area_color=8E2DE2&hide_border=true&custom_title=The%20King's%20Campaign%20Log" alt="Activity graph"/>
</p>

<p align="center">
  <picture>
    <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/razi-king/razi-king/output/github-contribution-grid-snake-dark.svg"/>
    <img alt="Contribution snake" src="https://raw.githubusercontent.com/razi-king/razi-king/output/github-contribution-grid-snake.svg"/>
  </picture>
</p>

---

## 📜 Summon the King

<p align="center">
  <a href="mailto:raziinsane@gmail.com"><img src="https://img.shields.io/badge/Email-FFD700?style=for-the-badge&logo=gmail&logoColor=1a0b2e"/></a>
  <a href="https://www.linkedin.com/in/razi-ahmed-8s/"><img src="https://img.shields.io/badge/LinkedIn-8E2DE2?style=for-the-badge&logo=linkedin&logoColor=white"/></a>
  <a href="https://github.com/razi-king?tab=repositories"><img src="https://img.shields.io/badge/All%20Repos-1a0b2e?style=for-the-badge&logo=github&logoColor=FFD700"/></a>
</p>

<p align="center"><i>"Every bug fixed is a battle won. Every deploy, a kingdom expanded."</i> 👑</p>

<p align="center">
  <img width="100%" src="https://capsule-render.vercel.app/api?type=waving&color=0:c084fc,25:8E2DE2,60:3b1466,100:0d0221&height=120&section=footer"/>
</p>
