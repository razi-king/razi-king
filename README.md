<!-- 👑 Razi Ahmed — Backend Engineer (Go) -->

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:1a0b2e,50:4b1d78,100:8E2DE2&height=230&section=header&text=Razi%20Ahmed&fontSize=62&fontColor=FFD700&fontAlignY=38&desc=Backend%20Engineer%20%E2%80%A2%20Go%20%E2%80%A2%20Travel%20Tech&descAlignY=60&descSize=20&animation=fadeIn" alt="Razi Ahmed — Backend Engineer"/>
</p>

<p align="center">
  <a href="https://github.com/razi-king">
    <img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=600&size=20&duration=3500&pause=900&color=FFD700&center=true&vCenter=true&width=640&lines=%F0%9F%91%91+Ruling+the+backend+with+Go;Flight+%26+transfer+supplier+integrations;Goroutines%2C+PostgreSQL%2C+Redis%2C+MongoDB;Building+systems+that+survive+production" alt="Typing intro"/>
  </a>
</p>

<p align="center">
  <img src="https://img.shields.io/badge/Role-Backend%20Engineer-8E2DE2?style=flat-square"/>
  <img src="https://img.shields.io/badge/Main%20Weapon-Go-00ADD8?style=flat-square&logo=go&logoColor=white"/>
  <img src="https://img.shields.io/badge/Domain-Travel%20Tech-FFD700?style=flat-square&labelColor=1a0b2e"/>
  <img src="https://img.shields.io/badge/Based%20in-Mumbai%2C%20India-4b1d78?style=flat-square"/>
</p>

---

## 👑 About the King

I'm **Razi**, a backend engineer at **Infohybrid**, a travel-technology company, where I write **Go** for a live flight and transfer booking engine.

- 🏰 **Now:** integrating airline and transfer suppliers into production booking flows (search → pricing → hold → ticket)
- ⚔️ **Strongest at:** Go concurrency, PostgreSQL debugging, Redis/MongoDB caching, supplier API design
- 📜 **Before:** 11-month full-stack internship (Java, Spring Boot, RabbitMQ, React)
- 🎓 **B.Sc. IT**, University of Mumbai — CGPA **9.3 / 10**
- 🌱 **Learning:** distributed tracing, gRPC, and writing Go the way the standard library does

---

## 🏰 Conquests in Production

> Work from my day job. The code is private, so here is what it does and how it was built.

| Campaign | What I did | Stack |
|---|---|---|
| ✈️ **TripJack flight integration** | Full booking flow: search, branded fares, price validation, ancillaries, hold-then-confirm, ticketing | Go · PostgreSQL |
| 🛠️ **Critical price-change fix** | Booking was saved before supplier confirmation and never updated on fare change; traced it through app logic, a broken SQL query and an SQL function | Go · SQL |
| 🛡️ **Inherited 3 airline integrations** | Took over FlyArystan, SalamAir and ASL Airlines after the original dev left; fixed mapping, workflow and business-logic defects | Go |
| 🚖 **Transfer booking platform** | Built from scratch on Amadeus Transfer Quick Connect: search, revalidation, add-ons, booking lifecycle, commission rules | Go · PostgreSQL · Logrus |
| ⚡ **Parallel multi-city search** | Split return/multi-city into parallel one-way calls with goroutines and a panic-safe `safeGo()` wrapper | Go concurrency |
| 🚀 **O(n×m) → O(n+m)** | Replaced nested-loop offer matching with hashmap lookups; benchmarked with `testing.B` | Go |

---

## ⚔️ Royal Projects

<table>
  <tr>
    <td width="50%" valign="top">
      <h3>💰 <a href="https://github.com/razi-king/Expense-Tracker">Expense Tracker</a></h3>
      Personal finance tracker with stateless JWT auth (Spring Security), category-based expense logging and a REST API used by an Astro + React frontend.
      <br/><br/>
      <img src="https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white"/>
      <img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white"/>
      <img src="https://img.shields.io/badge/JWT-000000?style=flat-square&logo=jsonwebtokens"/>
      <img src="https://img.shields.io/badge/Astro-BC52EE?style=flat-square&logo=astro&logoColor=white"/>
    </td>
    <td width="50%" valign="top">
      <h3>💬 <a href="https://github.com/razi-king/SpringProjects/tree/main/ChatAppBackend">Real-time Chat</a></h3>
      Room-based chat over WebSocket (STOMP) with a Spring Boot + MongoDB backend, custom error codes, a global exception handler, OpenAPI docs and a React frontend.
      <br/><br/>
      <img src="https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white"/>
      <img src="https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white"/>
      <img src="https://img.shields.io/badge/WebSocket-010101?style=flat-square&logo=socketdotio"/>
      <img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB"/>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3>🏪 Smart Vendor App <sub><i>(in progress)</i></sub></h3>
      Multi-tenant SaaS for retailers with many outlets: Admin / Vendor / User RBAC and tenant data isolation. Inventory, orders and analytics on the way.
      <br/><br/>
      <img src="https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white"/>
      <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white"/>
      <img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB"/>
    </td>
    <td width="50%" valign="top">
      <h3>📨 <a href="https://github.com/razi-king/SpringProjects/tree/main/MailSender">Mail Sender</a></h3>
      Email service in Spring Boot. The event-driven version I built at work adds RabbitMQ retries, dead-letter queues and a parking-lot queue for messages that keep failing.
      <br/><br/>
      <img src="https://img.shields.io/badge/Spring%20Boot-6DB33F?style=flat-square&logo=springboot&logoColor=white"/>
      <img src="https://img.shields.io/badge/RabbitMQ-FF6600?style=flat-square&logo=rabbitmq&logoColor=white"/>
    </td>
  </tr>
</table>

---

## 🛡️ The Arsenal

<p align="center"><b>Backend</b><br/>
  <img src="https://skillicons.dev/icons?i=go,java,spring,python,rabbitmq&theme=dark" />
</p>
<p align="center"><b>Data</b><br/>
  <img src="https://skillicons.dev/icons?i=postgres,mysql,mongodb,redis,azure&theme=dark" />
</p>
<p align="center"><b>Frontend & Tools</b><br/>
  <img src="https://skillicons.dev/icons?i=ts,react,nextjs,astro,tailwind,docker,git,postman,linux&theme=dark" />
</p>

---

## 📈 The Royal Ledger

<p align="center">
  <img height="165" src="https://github-readme-stats.vercel.app/api?username=razi-king&show_icons=true&hide_border=true&bg_color=0D1117&title_color=FFD700&icon_color=8E2DE2&text_color=E6E6E6&include_all_commits=true&count_private=true" alt="GitHub stats"/>
  <img height="165" src="https://streak-stats.demolab.com/?user=razi-king&hide_border=true&background=0D1117&ring=FFD700&fire=8E2DE2&currStreakLabel=FFD700&sideLabels=E6E6E6&dates=999999&currStreakNum=E6E6E6&sideNums=E6E6E6" alt="Streak stats"/>
</p>

<p align="center">
  <img height="150" src="https://github-readme-stats.vercel.app/api/top-langs/?username=razi-king&layout=compact&hide_border=true&bg_color=0D1117&title_color=FFD700&text_color=E6E6E6&langs_count=8" alt="Top languages"/>
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
</p>

<p align="center"><i>👑 Open to backend roles in Go — supplier integrations, booking systems, high-concurrency APIs.</i></p>

<p align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:8E2DE2,50:4b1d78,100:1a0b2e&height=110&section=footer"/>
</p>
