<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f0c29,50:302b63,100:24243e&height=220&section=header&text=Faris%20Yahya%20Ayyash%20Alfatih&fontSize=38&fontColor=ffffff&fontAlignY=38&desc=Full-Stack%20Developer%20%7C%20UI%2FUX%20Designer%20%7C%20Information%20Systems%20at%20Telkom%20University&descAlignY=58&descSize=16&animation=fadeIn" alt="Faris Yahya Ayyash Alfatih" />

<a href="https://github.com/ramirezzServer"><img src="https://komarev.com/ghpvc/?username=ramirezzServer&style=for-the-badge&color=7c3aed&label=PROFILE+VIEWS" alt="Profile views" /></a>
<img src="https://img.shields.io/github/followers/ramirezzServer?style=for-the-badge&color=7c3aed&labelColor=1c1917&label=FOLLOWERS" alt="Followers" />
<img src="https://img.shields.io/github/stars/ramirezzServer?style=for-the-badge&color=f97316&labelColor=1c1917&label=STARS" alt="Stars" />
<a href="https://linkedin.com/in/faris-yahya-ayyash-alfatih-0a502a215"><img src="https://img.shields.io/badge/LINKEDIN-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
<a href="mailto:faris651234@gmail.com"><img src="https://img.shields.io/badge/EMAIL-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>

<br/><br/>

<img src="https://readme-typing-svg.herokuapp.com?font=Fira+Code&size=20&duration=3000&pause=1000&color=A78BFA&center=true&vCenter=true&width=860&lines=Building+SIAGA%3A+early+warning+and+air+quality+for+West+Java;Go+%C2%B7+PostgreSQL+%C2%B7+NATS+JetStream+%C2%B7+Kubernetes;React+%C2%B7+TypeScript+%C2%B7+Laravel+%C2%B7+FastAPI;From+Figma+to+production;Information+Systems+%40+Telkom+University" alt="Typing SVG" />

</div>

---

## About

I'm Faris, an Information Systems student at Telkom University in Bandung. I build web apps end to end: product documents first, then the API, the interface, and the pipeline that ships it. I also design, so most of my interfaces start in Figma before they turn into React.

Lately I have been spending more time on the backend side of things: event-driven services in Go, geospatial and time-series data in PostgreSQL, and running it all on Kubernetes with proper CI, tracing, and secret management.

<table>
  <tr>
    <td><b>Now</b></td>
    <td>Building SIAGA, a disaster early warning and air quality platform for West Java</td>
  </tr>
  <tr>
    <td><b>Maintaining</b></td>
    <td>TradeView Dashboard (web and mobile)</td>
  </tr>
  <tr>
    <td><b>Shipped</b></td>
    <td>Spektra, UMKM-Sense (PKM-KC, team lead)</td>
  </tr>
  <tr>
    <td><b>Also</b></td>
    <td>Teaching assistant (Asisten Praktikum), community development work with Bina Desa</td>
  </tr>
  <tr>
    <td><b>Open to</b></td>
    <td>Internships, freelance, and collaboration</td>
  </tr>
</table>

---

## Featured Projects

<table>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/ramirezzServer/siaga">SIAGA</a></h3>
      <img src="https://img.shields.io/badge/status-in_progress-1f6feb?style=flat-square" alt="In progress" />
      <p>Disaster early warning and air quality monitoring for West Java, with Greater Bandung as the focus area. It pulls BMKG, USGS, Open-Meteo, OpenAQ, and NASA FIRMS data into one event-driven pipeline and matches hazards to places people care about.</p>
      <p>Done so far: ingestion with per-source rate limits, BMKG and USGS earthquake deduplication calibrated on historical catalogs, a raw payload archive that can be replayed, river gauge cells picked from GloFAS reanalysis, OpenTelemetry tracing into Grafana, and signed container images with Kubernetes manifests. Planned next: flood thresholds, the public map, personal alerts, and an offline-first mobile app.</p>
      <p>
        <img src="https://img.shields.io/badge/Go-20232A?style=flat-square&logo=go&logoColor=00ADD8" alt="Go" />
        <img src="https://img.shields.io/badge/PostGIS-20232A?style=flat-square&logo=postgresql&logoColor=4169E1" alt="PostGIS" />
        <img src="https://img.shields.io/badge/TimescaleDB-20232A?style=flat-square&logo=timescale&logoColor=FDB515" alt="TimescaleDB" />
        <img src="https://img.shields.io/badge/NATS_JetStream-20232A?style=flat-square&logo=natsdotio&logoColor=27AAE1" alt="NATS JetStream" />
        <img src="https://img.shields.io/badge/Protobuf-20232A?style=flat-square&logo=google&logoColor=white" alt="Protobuf" />
        <img src="https://img.shields.io/badge/k3s-20232A?style=flat-square&logo=k3s&logoColor=FFC61C" alt="k3s" />
        <img src="https://img.shields.io/badge/OpenTelemetry-20232A?style=flat-square&logo=opentelemetry&logoColor=F5A800" alt="OpenTelemetry" />
      </p>
      <sub>Planned for later phases: Next.js, MapLibre, NestJS, Keycloak, Flutter.</sub>
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/ramirezzServer/tradeview-dashboard">TradeView Dashboard</a></h3>
      <img src="https://img.shields.io/badge/status-maintenance-d29922?style=flat-square" alt="Maintenance" />
      <p>Trading simulation and portfolio dashboard on web and mobile. Watchlist, portfolio, OHLCV charts, company financials, crypto, market news, and web push notifications.</p>
      <p>One Laravel API serves both the React web app and the Expo mobile app, and proxies Finnhub, Alpha Vantage, and CoinGecko so API keys never leave the server. Feature work is done for now; the repo is in maintenance.</p>
      <p>
        <img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" alt="React" />
        <img src="https://img.shields.io/badge/TypeScript-20232A?style=flat-square&logo=typescript&logoColor=3178C6" alt="TypeScript" />
        <img src="https://img.shields.io/badge/Laravel-20232A?style=flat-square&logo=laravel&logoColor=FF2D20" alt="Laravel" />
        <img src="https://img.shields.io/badge/PostgreSQL-20232A?style=flat-square&logo=postgresql&logoColor=4169E1" alt="PostgreSQL" />
        <img src="https://img.shields.io/badge/React_Native-20232A?style=flat-square&logo=react&logoColor=61DAFB" alt="React Native" />
        <img src="https://img.shields.io/badge/Expo-20232A?style=flat-square&logo=expo&logoColor=white" alt="Expo" />
        <img src="https://img.shields.io/badge/TanStack_Query-20232A?style=flat-square&logo=reactquery&logoColor=FF4154" alt="TanStack Query" />
      </p>
    </td>
  </tr>
  <tr>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/ramirezzServer/UMKM-SENSE">UMKM-Sense</a> <sub>PKM-KC</sub></h3>
      <img src="https://img.shields.io/badge/status-completed-2ea043?style=flat-square" alt="Completed" />
      <p>AI sales forecasting for Indonesian small businesses, built for PKM-KC where I led the team. It combines transaction history with local weather and national holidays to forecast sales per product and turn the result into prioritized recommendations.</p>
      <p>A separate FastAPI service picks between Prophet, ARIMA, and weighted moving average for each product. Laravel calls it through a background queue, so a slow forecast never blocks the API.</p>
      <p>
        <img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" alt="React" />
        <img src="https://img.shields.io/badge/Laravel-20232A?style=flat-square&logo=laravel&logoColor=FF2D20" alt="Laravel" />
        <img src="https://img.shields.io/badge/FastAPI-20232A?style=flat-square&logo=fastapi&logoColor=009688" alt="FastAPI" />
        <img src="https://img.shields.io/badge/Prophet-20232A?style=flat-square&logo=meta&logoColor=0467DF" alt="Prophet" />
        <img src="https://img.shields.io/badge/Three.js-20232A?style=flat-square&logo=threedotjs&logoColor=white" alt="Three.js" />
        <img src="https://img.shields.io/badge/Turborepo-20232A?style=flat-square&logo=turborepo&logoColor=EF4444" alt="Turborepo" />
      </p>
    </td>
    <td width="50%" valign="top">
      <h3><a href="https://github.com/ramirezzServer/Spektra">Spektra</a></h3>
      <img src="https://img.shields.io/badge/status-completed-2ea043?style=flat-square" alt="Completed" />
      <p>Media tracker for films, series, games, and books. Personal library with ratings and reviews, public profiles, follows, activity feeds, and custom lists, installable as a PWA.</p>
      <p>React frontend on a versioned Laravel Sanctum API, with a FastAPI worker that syncs content from TMDB, RAWG, and OpenLibrary on a schedule. Redis handles caching, throttling, and queues; the whole stack runs from Docker Compose.</p>
      <p>
        <img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" alt="React" />
        <img src="https://img.shields.io/badge/TypeScript-20232A?style=flat-square&logo=typescript&logoColor=3178C6" alt="TypeScript" />
        <img src="https://img.shields.io/badge/Laravel-20232A?style=flat-square&logo=laravel&logoColor=FF2D20" alt="Laravel" />
        <img src="https://img.shields.io/badge/FastAPI-20232A?style=flat-square&logo=fastapi&logoColor=009688" alt="FastAPI" />
        <img src="https://img.shields.io/badge/PostgreSQL-20232A?style=flat-square&logo=postgresql&logoColor=4169E1" alt="PostgreSQL" />
        <img src="https://img.shields.io/badge/Redis-20232A?style=flat-square&logo=redis&logoColor=DC382D" alt="Redis" />
        <img src="https://img.shields.io/badge/PWA-20232A?style=flat-square&logo=pwa&logoColor=5A0FC8" alt="PWA" />
      </p>
    </td>
  </tr>
</table>

Other work: [OurTucTuc Mobility System](https://github.com/ramirezzServer/ourtuctuc-mobility-system), a Laravel and Blade app for a small transport service.

---

## Tech Stack

<div align="center">

**Languages**

<img src="https://skillicons.dev/icons?i=ts,js,go,php,python,java,cs,html,css,bash&theme=dark" alt="Languages" />

<br/><br/>

**Frontend and Mobile**

<img src="https://skillicons.dev/icons?i=react,nextjs,vite,tailwind,threejs&theme=dark" alt="Frontend" />
<br/>
<img src="https://img.shields.io/badge/React_Native-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React Native" />
<img src="https://img.shields.io/badge/Expo-1B1F23?style=for-the-badge&logo=expo&logoColor=white" alt="Expo" />
<img src="https://img.shields.io/badge/TanStack_Query-20232A?style=for-the-badge&logo=reactquery&logoColor=FF4154" alt="TanStack Query" />
<img src="https://img.shields.io/badge/Zustand-20232A?style=for-the-badge&logoColor=white" alt="Zustand" />

<br/><br/>

**Backend and APIs**

<img src="https://skillicons.dev/icons?i=laravel,nodejs,express,fastapi&theme=dark" alt="Backend" />
<br/>
<img src="https://img.shields.io/badge/NATS_JetStream-20232A?style=for-the-badge&logo=natsdotio&logoColor=27AAE1" alt="NATS JetStream" />
<img src="https://img.shields.io/badge/Protocol_Buffers-20232A?style=for-the-badge&logo=google&logoColor=white" alt="Protocol Buffers" />
<img src="https://img.shields.io/badge/OpenAPI-20232A?style=for-the-badge&logo=openapiinitiative&logoColor=6BA539" alt="OpenAPI" />

<br/><br/>

**Data**

<img src="https://skillicons.dev/icons?i=postgres,mysql,sqlite,redis&theme=dark" alt="Databases" />
<br/>
<img src="https://img.shields.io/badge/PostGIS-20232A?style=for-the-badge&logo=postgresql&logoColor=4169E1" alt="PostGIS" />
<img src="https://img.shields.io/badge/TimescaleDB-20232A?style=for-the-badge&logo=timescale&logoColor=FDB515" alt="TimescaleDB" />
<img src="https://img.shields.io/badge/pandas-20232A?style=for-the-badge&logo=pandas&logoColor=white" alt="pandas" />
<img src="https://img.shields.io/badge/Prophet-20232A?style=for-the-badge&logo=meta&logoColor=0467DF" alt="Prophet" />
<img src="https://img.shields.io/badge/scikit--learn-20232A?style=for-the-badge&logo=scikitlearn&logoColor=F7931E" alt="scikit-learn" />

<br/><br/>

**Infrastructure and Observability**

<img src="https://skillicons.dev/icons?i=docker,kubernetes,githubactions,nginx,linux,grafana,prometheus&theme=dark" alt="Infrastructure" />
<br/>
<img src="https://img.shields.io/badge/k3s-20232A?style=for-the-badge&logo=k3s&logoColor=FFC61C" alt="k3s" />
<img src="https://img.shields.io/badge/OpenTelemetry-20232A?style=for-the-badge&logo=opentelemetry&logoColor=F5A800" alt="OpenTelemetry" />
<img src="https://img.shields.io/badge/Trivy-20232A?style=for-the-badge&logo=trivy&logoColor=1904DA" alt="Trivy" />
<img src="https://img.shields.io/badge/Sigstore_cosign-20232A?style=for-the-badge&logo=sigstore&logoColor=white" alt="cosign" />
<img src="https://img.shields.io/badge/SOPS_+_age-20232A?style=for-the-badge&logoColor=white" alt="SOPS and age" />

<br/><br/>

**Tooling**

<img src="https://skillicons.dev/icons?i=git,github,pnpm,vitest,postman,vscode&theme=dark" alt="Tooling" />
<br/>
<img src="https://img.shields.io/badge/Turborepo-20232A?style=for-the-badge&logo=turborepo&logoColor=EF4444" alt="Turborepo" />

<br/><br/>

**Design**

<img src="https://skillicons.dev/icons?i=figma,ai,ps&theme=dark" alt="Design" />
<br/>
<img src="https://img.shields.io/badge/Canva-00C4CC?style=for-the-badge&logo=canva&logoColor=white" alt="Canva" />
<img src="https://img.shields.io/badge/CorelDRAW-47A141?style=for-the-badge&logo=coreldraw&logoColor=white" alt="CorelDRAW" />

</div>

---

## How I Work

- Write the PRD and architecture doc before the first line of code, and record every non-obvious decision as an ADR.
- Keep contracts explicit: Protobuf for events, OpenAPI for HTTP, generated clients instead of hand-written ones.
- Nothing merges unless CI is green: lint, strict types, tests with coverage gates, image scans, and a secret scanner.
- Prefer boring, free infrastructure that I can rebuild from the repo in one command.
- Design in Figma first, then make sure the design survives contact with real data.

---

## GitHub Stats

<div align="center">

<img height="185em" src="https://github-readme-stats-salesp07.vercel.app/api?username=ramirezzServer&show_icons=true&theme=tokyonight&include_all_commits=true&count_private=true&hide_border=true&bg_color=0d1117&title_color=a78bfa&icon_color=7c3aed&text_color=c9d1d9" alt="GitHub stats" />
<img height="185em" src="https://github-readme-stats-salesp07.vercel.app/api/top-langs/?username=ramirezzServer&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d1117&langs_count=8&title_color=a78bfa&text_color=c9d1d9&hide=jupyter%20notebook" alt="Top languages" />

<img src="https://streak-stats.demolab.com?user=ramirezzServer&theme=tokyonight-duo&hide_border=true&background=0d1117&stroke=7c3aed&ring=a78bfa&fire=F97316&currStreakLabel=a78bfa&sideLabels=a78bfa" alt="GitHub streak" />

<picture>
  <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/ramirezzServer/ramirezzServer/output/github-contribution-grid-snake-dark.svg" />
  <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/ramirezzServer/ramirezzServer/output/github-contribution-grid-snake.svg" />
  <img alt="Contribution snake" src="https://raw.githubusercontent.com/ramirezzServer/ramirezzServer/output/github-contribution-grid-snake-dark.svg" />
</picture>

</div>

---

<div align="center">

<a href="https://linkedin.com/in/faris-yahya-ayyash-alfatih-0a502a215"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
<a href="https://instagram.com/rissziee"><img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white" alt="Instagram" /></a>
<a href="mailto:faris651234@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>

<br/><br/>

<i>"You can make the same mistake twice, because the second time is not a mistake, it's a choice."</i>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f0c29,50:302b63,100:24243e&height=120&section=footer&animation=fadeIn" alt="" />

</div>
