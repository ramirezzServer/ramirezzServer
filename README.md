<div align="center">

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f0c29,50:302b63,100:24243e&height=260&section=header&text=Faris%20Yahya%20Ayyash%20Alfatih&fontSize=40&fontColor=ffffff&fontAlignY=36&desc=Full-Stack%20Developer%20%7C%20UI%2FUX%20Designer%20%7C%20Lab%20Assistant%20%40%20EISD%20Laboratory%20%7C%20Telkom%20University&descAlignY=56&descSize=15&animation=twinkling" alt="Faris Yahya Ayyash Alfatih" />

<a href="https://github.com/ramirezzServer"><img src="https://komarev.com/ghpvc/?username=ramirezzServer&style=for-the-badge&color=7c3aed&label=PROFILE+VIEWS" alt="Profile views" /></a>
<img src="https://img.shields.io/github/followers/ramirezzServer?style=for-the-badge&color=7c3aed&labelColor=1c1917&label=FOLLOWERS" alt="Followers" />
<img src="https://img.shields.io/github/stars/ramirezzServer?style=for-the-badge&color=f97316&labelColor=1c1917&label=STARS" alt="Stars" />
<a href="https://linkedin.com/in/faris-yahya-ayyash-alfatih-0a502a215"><img src="https://img.shields.io/badge/LINKEDIN-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
<a href="mailto:faris651234@gmail.com"><img src="https://img.shields.io/badge/EMAIL-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>
<br/>
<img src="https://img.shields.io/badge/BANDUNG%2C_INDONESIA-UTC%2B7-a78bfa?style=for-the-badge&labelColor=1c1917&logo=googlemaps&logoColor=a78bfa" alt="Bandung, Indonesia, UTC+7" />
<img src="https://img.shields.io/badge/STATUS-OPEN_TO_INTERNSHIPS-2ea043?style=for-the-badge&labelColor=1c1917" alt="Open to internships" />

<br/><br/>

<img src="https://readme-typing-svg.demolab.com?font=Fira+Code&weight=500&size=20&duration=3000&pause=1000&color=A78BFA&center=true&vCenter=true&width=880&lines=Asprak+%26+Aslab+%40+EISD+Laboratory%2C+Telkom+University;Building+SIAGA%3A+early+warning+and+air+quality+for+West+Java;Go+%C2%B7+PostgreSQL+%C2%B7+NATS+JetStream+%C2%B7+Kubernetes;React+%C2%B7+TypeScript+%C2%B7+Laravel+%C2%B7+FastAPI;AWS+%C2%B7+Google+Cloud+%C2%B7+Docker+%C2%B7+k3s;From+Figma+to+production;Information+Systems+%40+Telkom+University" alt="Typing SVG" />

</div>

---

## About

```ts
const faris = {
  name:        "Faris Yahya Ayyash Alfatih",
  base:        "Bandung, Indonesia (UTC+7)",
  study:       "Information Systems @ Telkom University",
  roles:       ["Full-Stack Developer", "UI/UX Designer"],
  lab:         ["Lab Assistant @ EISD Laboratory", "Practicum Assistant @ EISD Laboratory"],
  now:         "SIAGA — disaster early warning + air quality for West Java",
  maintaining: ["TradeView Dashboard (web + mobile)"],
  shipped:     ["Spektra", "UMKM-Sense (PKM-KC, team lead)"],
  completed:   ["Bina Desa community development program (R&D division)"],
  openTo:      ["Internships", "Freelance", "Collaboration"],
} as const;
```

I'm Faris, an Information Systems student at Telkom University in Bandung. I build web apps end to end: product documents first, then the API, the interface, and the pipeline that ships it. I also design, so most of my interfaces start in Figma before they turn into React.

Lately I have been spending more time on the backend side of things: event-driven services in Go, geospatial and time-series data in PostgreSQL, and running it all on Kubernetes with proper CI, tracing, and secret management.

On campus I work at **EISD Laboratory** as both a lab assistant and a practicum assistant: helping run practicum sessions, mentoring students, reviewing their work, and supporting the lab day to day. Coursework keeps the rest of my toolbox wide: AWS and Google Cloud for cloud computing, Pentaho and MySQL for data warehousing, Cisco Packet Tracer for networking, Google Colab for data mining and machine learning, and VMware or VirtualBox whenever something needs its own machine.

<table>
  <tr>
    <td><b>Now</b></td>
    <td>Building SIAGA, a disaster early warning and air quality platform for West Java</td>
  </tr>
  <tr>
    <td><b>Lab</b></td>
    <td>Lab Assistant and Practicum Assistant at EISD Laboratory, Telkom University</td>
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
    <td><b>Completed</b></td>
    <td>Community development work with Bina Desa (R&D division), including Smart Posyandu</td>
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

<div align="center">
  <a href="https://github.com/ramirezzServer/siaga"><img src="https://github-readme-stats-salesp07.vercel.app/api/pin/?username=ramirezzServer&repo=siaga&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=a78bfa&icon_color=7c3aed&text_color=c9d1d9" alt="SIAGA repo card" /></a>
  <a href="https://github.com/ramirezzServer/tradeview-dashboard"><img src="https://github-readme-stats-salesp07.vercel.app/api/pin/?username=ramirezzServer&repo=tradeview-dashboard&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=a78bfa&icon_color=7c3aed&text_color=c9d1d9" alt="TradeView repo card" /></a>
  <a href="https://github.com/ramirezzServer/UMKM-SENSE"><img src="https://github-readme-stats-salesp07.vercel.app/api/pin/?username=ramirezzServer&repo=UMKM-SENSE&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=a78bfa&icon_color=7c3aed&text_color=c9d1d9" alt="UMKM-Sense repo card" /></a>
  <a href="https://github.com/ramirezzServer/Spektra"><img src="https://github-readme-stats-salesp07.vercel.app/api/pin/?username=ramirezzServer&repo=Spektra&theme=tokyonight&hide_border=true&bg_color=0d1117&title_color=a78bfa&icon_color=7c3aed&text_color=c9d1d9" alt="Spektra repo card" /></a>
</div>

### Architecture at a glance

<details>
<summary><b>SIAGA</b> — event-driven ingestion pipeline (dashed = planned)</summary>
<br/>

```mermaid
flowchart LR
  subgraph SRC[Public data sources]
    BMKG[BMKG]
    USGS[USGS]
    OM[Open-Meteo]
    OAQ[OpenAQ]
    FIRMS[NASA FIRMS]
  end
  SRC --> ING[Go ingestion workers<br/>per-source rate limits]
  ING --> ARC[(Raw payload archive<br/>replayable)]
  ING --> BUS{{NATS JetStream<br/>Protobuf events}}
  BUS --> DEDUP[Earthquake dedup<br/>BMKG x USGS]
  DEDUP --> DB[(PostgreSQL<br/>PostGIS + TimescaleDB)]
  BUS --> DB
  ING -. traces .-> OTEL[OpenTelemetry to Grafana]
  DB -.-> MAP[Public map<br/>Next.js + MapLibre]:::planned
  DB -.-> ALERT[Personal alerts<br/>NestJS + Keycloak]:::planned
  ALERT -.-> APP[Offline-first app<br/>Flutter]:::planned
  classDef planned stroke-dasharray: 5 5
```

</details>

<details>
<summary><b>TradeView Dashboard</b> — one API, two clients</summary>
<br/>

```mermaid
flowchart LR
  WEB[React web app] --> API[Laravel API]
  MOB[Expo mobile app] --> API
  API --> PG[(PostgreSQL)]
  API -->|keys stay server-side| FH[Finnhub]
  API --> AV[Alpha Vantage]
  API --> CG[CoinGecko]
  API -. web push .-> WEB
```

</details>

<details>
<summary><b>UMKM-Sense</b> — forecasting off the request path</summary>
<br/>

```mermaid
flowchart LR
  UI[React dashboard] --> L[Laravel API]
  L -->|background queue| F[FastAPI forecasting service]
  IN[Transactions + local weather + national holidays] --> F
  F --> M{Model per product}
  M --> P[Prophet]
  M --> A[ARIMA]
  M --> W[Weighted moving average]
  F --> R[Prioritized recommendations]
  R --> UI
```

</details>

<details>
<summary><b>Spektra</b> — API, cache, and scheduled sync worker</summary>
<br/>

```mermaid
flowchart LR
  UI[React PWA] --> API[Versioned Laravel Sanctum API]
  API --> PG[(PostgreSQL)]
  API --> RD[(Redis<br/>cache, throttling, queues)]
  WK[FastAPI sync worker] -->|scheduled| T[TMDB]
  WK --> RA[RAWG]
  WK --> OL[OpenLibrary]
  WK --> PG
```

</details>

### Other work

| Project | What it is | Stack |
| --- | --- | --- |
| OurTucTuc Mobility System | Laravel and Blade app for a small transport service | Laravel, Blade |
| Sirkula | Group project, in progress: community marketplace for second-hand goods and recycling between city and village communities (SDG 12) | Laravel, Laravel Cloud |
| TelEvent | Campus event system built as GraphQL microservices | Node.js, GraphQL, Docker, MySQL on Railway |
| NRG Data Warehouse | Data warehouse for a retail case study (Nusantara Retail Group) | Pentaho Data Integration, MySQL |
| Smart Posyandu | Community health post management system, built during Bina Desa | Laravel, MySQL, React, TypeScript, Docker, Nginx, VPS |
| BimbingKita | Thesis supervision web app, UX design proposal for GEMASTIK XIX | Figma |
| Cloud Computing | Group cloud project on a shared AWS account with IAM users per member | AWS |
| Coursework labs | Naive Bayes sleep disorder classifier, K-Means and logistic regression on UMKM data, load and stress testing, E2E test automation, SQL injection mitigation with ModSecurity | Streamlit, Google Colab, scikit-learn, JMeter, Katalon Studio, VirtualBox, Ubuntu |

---

## Tech Stack

<details open>
<summary><b>Languages</b></summary>
<p align="center">
  <img src="https://skillicons.dev/icons?i=ts,js,go,php,python,java,cs,html,css,bash,graphql&theme=dark" alt="Languages" />
  <br/>
  <img src="https://img.shields.io/badge/SQL-20232A?style=for-the-badge&logo=postgresql&logoColor=white" alt="SQL" />
</p>
</details>

<details open>
<summary><b>Frontend and Mobile</b></summary>
<p align="center">
  <img src="https://skillicons.dev/icons?i=react,nextjs,vite,tailwind,threejs&theme=dark" alt="Frontend" />
  <br/>
  <img src="https://img.shields.io/badge/React_Native-20232A?style=for-the-badge&logo=react&logoColor=61DAFB" alt="React Native" />
  <img src="https://img.shields.io/badge/Expo-1B1F23?style=for-the-badge&logo=expo&logoColor=white" alt="Expo" />
  <img src="https://img.shields.io/badge/TanStack_Query-20232A?style=for-the-badge&logo=reactquery&logoColor=FF4154" alt="TanStack Query" />
  <img src="https://img.shields.io/badge/Zustand-20232A?style=for-the-badge&logoColor=white" alt="Zustand" />
  <img src="https://img.shields.io/badge/shadcn%2Fui-20232A?style=for-the-badge&logo=shadcnui&logoColor=white" alt="shadcn/ui" />
  <img src="https://img.shields.io/badge/Blade-20232A?style=for-the-badge&logo=laravel&logoColor=FF2D20" alt="Blade" />
  <img src="https://img.shields.io/badge/PWA-20232A?style=for-the-badge&logo=pwa&logoColor=5A0FC8" alt="PWA" />
</p>
</details>

<details open>
<summary><b>Backend and APIs</b></summary>
<p align="center">
  <img src="https://skillicons.dev/icons?i=laravel,nodejs,express,fastapi,graphql&theme=dark" alt="Backend" />
  <br/>
  <img src="https://img.shields.io/badge/NATS_JetStream-20232A?style=for-the-badge&logo=natsdotio&logoColor=27AAE1" alt="NATS JetStream" />
  <img src="https://img.shields.io/badge/Protocol_Buffers-20232A?style=for-the-badge&logo=google&logoColor=white" alt="Protocol Buffers" />
  <img src="https://img.shields.io/badge/OpenAPI-20232A?style=for-the-badge&logo=openapiinitiative&logoColor=6BA539" alt="OpenAPI" />
  <img src="https://img.shields.io/badge/Laravel_Sanctum-20232A?style=for-the-badge&logo=laravel&logoColor=FF2D20" alt="Laravel Sanctum" />
  <img src="https://img.shields.io/badge/Microservices-20232A?style=for-the-badge&logo=graphql&logoColor=E10098" alt="Microservices" />
</p>
</details>

<details open>
<summary><b>Data, Analytics and ML</b></summary>
<p align="center">
  <img src="https://skillicons.dev/icons?i=postgres,mysql,sqlite,redis,sklearn&theme=dark" alt="Databases and ML" />
  <br/>
  <img src="https://img.shields.io/badge/PostGIS-20232A?style=for-the-badge&logo=postgresql&logoColor=4169E1" alt="PostGIS" />
  <img src="https://img.shields.io/badge/TimescaleDB-20232A?style=for-the-badge&logo=timescale&logoColor=FDB515" alt="TimescaleDB" />
  <img src="https://img.shields.io/badge/Pentaho_Data_Integration-20232A?style=for-the-badge&logoColor=white" alt="Pentaho Data Integration" />
  <img src="https://img.shields.io/badge/pandas-20232A?style=for-the-badge&logo=pandas&logoColor=white" alt="pandas" />
  <img src="https://img.shields.io/badge/NumPy-20232A?style=for-the-badge&logo=numpy&logoColor=4DABCF" alt="NumPy" />
  <img src="https://img.shields.io/badge/scikit--learn-20232A?style=for-the-badge&logo=scikitlearn&logoColor=F7931E" alt="scikit-learn" />
  <img src="https://img.shields.io/badge/Prophet-20232A?style=for-the-badge&logo=meta&logoColor=0467DF" alt="Prophet" />
  <img src="https://img.shields.io/badge/Google_Colab-20232A?style=for-the-badge&logo=googlecolab&logoColor=F9AB00" alt="Google Colab" />
  <img src="https://img.shields.io/badge/Jupyter-20232A?style=for-the-badge&logo=jupyter&logoColor=F37626" alt="Jupyter" />
  <img src="https://img.shields.io/badge/Streamlit-20232A?style=for-the-badge&logo=streamlit&logoColor=FF4B4B" alt="Streamlit" />
</p>
</details>

<details open>
<summary><b>Cloud and Hosting</b></summary>
<p align="center">
  <img src="https://skillicons.dev/icons?i=aws,gcp&theme=dark" alt="AWS and Google Cloud" />
  <br/>
  <img src="https://img.shields.io/badge/AWS_IAM-232F3E?style=for-the-badge&logoColor=white" alt="AWS IAM" />
  <img src="https://img.shields.io/badge/AWS_EC2-232F3E?style=for-the-badge&logoColor=white" alt="AWS EC2" />
  <img src="https://img.shields.io/badge/AWS_S3-232F3E?style=for-the-badge&logoColor=white" alt="AWS S3" />
  <img src="https://img.shields.io/badge/AWS_VPC-232F3E?style=for-the-badge&logoColor=white" alt="AWS VPC" />
  <img src="https://img.shields.io/badge/Google_Cloud-20232A?style=for-the-badge&logo=googlecloud&logoColor=4285F4" alt="Google Cloud" />
  <img src="https://img.shields.io/badge/Laravel_Cloud-20232A?style=for-the-badge&logo=laravel&logoColor=FF2D20" alt="Laravel Cloud" />
  <img src="https://img.shields.io/badge/Railway-20232A?style=for-the-badge&logo=railway&logoColor=white" alt="Railway" />
  <img src="https://img.shields.io/badge/VPS_(IDCloudHost)-20232A?style=for-the-badge&logoColor=white" alt="VPS on IDCloudHost" />
  <img src="https://img.shields.io/badge/ngrok-20232A?style=for-the-badge&logo=ngrok&logoColor=white" alt="ngrok" />
</p>
</details>

<details open>
<summary><b>Infrastructure, DevOps and Observability</b></summary>
<p align="center">
  <img src="https://skillicons.dev/icons?i=docker,kubernetes,githubactions,nginx,linux,ubuntu,grafana,prometheus&theme=dark" alt="Infrastructure" />
  <br/>
  <img src="https://img.shields.io/badge/k3s-20232A?style=for-the-badge&logo=k3s&logoColor=FFC61C" alt="k3s" />
  <img src="https://img.shields.io/badge/Docker_Compose-20232A?style=for-the-badge&logo=docker&logoColor=2496ED" alt="Docker Compose" />
  <img src="https://img.shields.io/badge/OpenTelemetry-20232A?style=for-the-badge&logo=opentelemetry&logoColor=F5A800" alt="OpenTelemetry" />
  <img src="https://img.shields.io/badge/Trivy-20232A?style=for-the-badge&logo=trivy&logoColor=1904DA" alt="Trivy" />
  <img src="https://img.shields.io/badge/Sigstore_cosign-20232A?style=for-the-badge&logo=sigstore&logoColor=white" alt="cosign" />
  <img src="https://img.shields.io/badge/SOPS_+_age-20232A?style=for-the-badge&logoColor=white" alt="SOPS and age" />
</p>
</details>

<details open>
<summary><b>Virtualization and Networking</b></summary>
<p align="center">
  <img src="https://img.shields.io/badge/VMware-20232A?style=for-the-badge&logo=vmware&logoColor=white" alt="VMware" />
  <img src="https://img.shields.io/badge/VirtualBox-20232A?style=for-the-badge&logo=virtualbox&logoColor=2F61B4" alt="VirtualBox" />
  <img src="https://img.shields.io/badge/WSL2-20232A?style=for-the-badge&logo=ubuntu&logoColor=E95420" alt="WSL2" />
  <img src="https://img.shields.io/badge/Cisco_Packet_Tracer-20232A?style=for-the-badge&logo=cisco&logoColor=1BA0D7" alt="Cisco Packet Tracer" />
</p>
</details>

<details open>
<summary><b>Testing, QA and Security</b></summary>
<p align="center">
  <img src="https://skillicons.dev/icons?i=vitest,postman&theme=dark" alt="Testing" />
  <br/>
  <img src="https://img.shields.io/badge/Apache_JMeter-20232A?style=for-the-badge&logo=apachejmeter&logoColor=D22128" alt="Apache JMeter" />
  <img src="https://img.shields.io/badge/Katalon_Studio-20232A?style=for-the-badge&logoColor=white" alt="Katalon Studio" />
  <img src="https://img.shields.io/badge/ModSecurity-20232A?style=for-the-badge&logoColor=white" alt="ModSecurity" />
</p>
</details>

<details open>
<summary><b>Tooling</b></summary>
<p align="center">
  <img src="https://skillicons.dev/icons?i=git,github,pnpm,vitest,postman,vscode&theme=dark" alt="Tooling" />
  <br/>
  <img src="https://img.shields.io/badge/Turborepo-20232A?style=for-the-badge&logo=turborepo&logoColor=EF4444" alt="Turborepo" />
</p>
</details>

<details open>
<summary><b>Design</b></summary>
<p align="center">
  <img src="https://skillicons.dev/icons?i=figma,ai,ps&theme=dark" alt="Design" />
  <br/>
  <img src="https://img.shields.io/badge/Canva-00C4CC?style=for-the-badge&logo=canva&logoColor=white" alt="Canva" />
  <img src="https://img.shields.io/badge/CorelDRAW-47A141?style=for-the-badge&logo=coreldraw&logoColor=white" alt="CorelDRAW" />
</p>
</details>

<details>
<summary><b>Next up</b> (planned for SIAGA's later phases)</summary>
<p align="center">
  <img src="https://skillicons.dev/icons?i=nestjs,flutter,dart&theme=dark" alt="Next up" />
  <br/>
  <img src="https://img.shields.io/badge/MapLibre-20232A?style=for-the-badge&logo=maplibre&logoColor=white" alt="MapLibre" />
  <img src="https://img.shields.io/badge/Keycloak-20232A?style=for-the-badge&logo=keycloak&logoColor=white" alt="Keycloak" />
</p>
</details>

---

## How I Work

- Write the PRD and architecture doc before the first line of code, and record every non-obvious decision as an ADR.
- Keep contracts explicit: Protobuf for events, OpenAPI for HTTP, generated clients instead of hand-written ones.
- Nothing merges unless CI is green: lint, strict types, tests with coverage gates, image scans, and a secret scanner.
- Prefer boring, free infrastructure that I can rebuild from the repo in one command.
- Design in Figma first, then make sure the design survives contact with real data.

```mermaid
flowchart LR
  A[PRD] --> B[Architecture + ADRs] --> C[Figma] --> D[Contracts<br/>OpenAPI / Protobuf] --> E[Code] --> F[CI gates<br/>lint, types, tests, scans] --> G[Ship]
```

---

## GitHub Stats

<div align="center"> <img height="185em" src="https://github-readme-stats-salesp07.vercel.app/api?username=ramirezzServer&show_icons=true&theme=tokyonight&include_all_commits=true&count_private=true&hide_border=true&bg_color=0d1117&title_color=a78bfa&icon_color=7c3aed&text_color=c9d1d9" alt="GitHub stats" /> <img height="185em" src="https://github-readme-stats-salesp07.vercel.app/api/top-langs/?username=ramirezzServer&layout=compact&theme=tokyonight&hide_border=true&bg_color=0d1117&langs_count=8&title_color=a78bfa&text_color=c9d1d9&hide=jupyter%20notebook" alt="Top languages" /> <img src="https://streak-stats.demolab.com?user=ramirezzServer&theme=tokyonight-duo&hide_border=true&background=0d1117&stroke=7c3aed&ring=a78bfa&fire=F97316&currStreakLabel=a78bfa&sideLabels=a78bfa" alt="GitHub streak" /> <img src="./metrics/isocalendar.svg" alt="Isometric contribution calendar" /> <img src="./metrics/achievements.svg" alt="GitHub achievements" /> <picture> <source media="(prefers-color-scheme: dark)" srcset="https://raw.githubusercontent.com/ramirezzServer/ramirezzServer/output/github-contribution-grid-snake-dark.svg" /> <source media="(prefers-color-scheme: light)" srcset="https://raw.githubusercontent.com/ramirezzServer/ramirezzServer/output/github-contribution-grid-snake.svg" /> <img alt="Contribution snake" src="https://raw.githubusercontent.com/ramirezzServer/ramirezzServer/output/github-contribution-grid-snake-dark.svg" /> </picture> </div>

---

<div align="center">

<a href="https://linkedin.com/in/faris-yahya-ayyash-alfatih-0a502a215"><img src="https://img.shields.io/badge/LinkedIn-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" /></a>
<a href="https://instagram.com/rissziee"><img src="https://img.shields.io/badge/Instagram-E4405F?style=for-the-badge&logo=instagram&logoColor=white" alt="Instagram" /></a>
<a href="mailto:faris651234@gmail.com"><img src="https://img.shields.io/badge/Email-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" /></a>

<br/><br/>

<i>"You can make the same mistake twice, because the second time is not a mistake, it's a choice."</i>

<img src="https://capsule-render.vercel.app/api?type=waving&color=0:0f0c29,50:302b63,100:24243e&height=120&section=footer&animation=fadeIn" alt="" />

</div>
