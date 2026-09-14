# Nguyen Nhat Tan

**Full-Stack Software Engineer** | Computer Science @ Ho Chi Minh City University of Technology (HCMUT)  
Ho Chi Minh City, Vietnam • [GitHub](https://github.com/nhatnews) • [Email](mailto:tan.nguyennhat07@hcmut.edu.vn)

---

## About Me

I am a Computer Science student at HCMUT and a Full-Stack Software Engineer specializing in scalable web architectures, real-time distributed systems, and resilient cloud services.

With practical experience architecting and shipping full-stack systems across multi-repository environments, I combine responsive and interactive user interfaces with robust backend domain architectures and automated containerized infrastructure.

---

## Technical Arsenal

### Languages & Frameworks
![TypeScript](https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white)
![C#](https://img.shields.io/badge/C%23-239120?style=flat-square&logo=csharp&logoColor=white)
![React 19](https://img.shields.io/badge/React_19-20232A?style=flat-square&logo=react&logoColor=61DAFB)
![.NET 10](https://img.shields.io/badge/.NET_10-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![ASP.NET Core](https://img.shields.io/badge/ASP.NET_Core-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![Tailwind CSS v4](https://img.shields.io/badge/Tailwind_CSS_v4-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white)
![C++](https://img.shields.io/badge/C++-00599C?style=flat-square&logo=cplusplus&logoColor=white)
![Python](https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white)

### Frontend Architecture & State
![Feature-Sliced Design](https://img.shields.io/badge/Architecture-Feature--Sliced_Design-264653?style=flat-square)
![TanStack Query](https://img.shields.io/badge/TanStack_Query-FF4154?style=flat-square&logo=reactquery&logoColor=white)
![Vitest](https://img.shields.io/badge/Vitest-6E9F18?style=flat-square&logo=vitest&logoColor=white)
![Testing Library](https://img.shields.io/badge/Testing_Library-E33332?style=flat-square&logo=testinglibrary&logoColor=white)
- **Design & Modularity:** Feature-Sliced Design (FSD) architecture ensuring decoupled layers (`app`, `pages`, `widgets`, `features`, `entities`, `shared`).
- **Interactive UI:** Dynamic SVG coordinate engine supporting real-time status projection, zooming, and panning.
- **State Synchronization:** TanStack Query for optimistic caching, stale-while-revalidate policies, and real-time state hydration.
- **Quality Assurance:** Unit and adversarial testing with Vitest and React Testing Library.

### Backend Systems & Architecture
![Clean Architecture](https://img.shields.io/badge/Architecture-Clean_Architecture-2B2D42?style=flat-square)
![MediatR](https://img.shields.io/badge/CQRS-MediatR-black?style=flat-square)
![Entity Framework Core](https://img.shields.io/badge/EF_Core-512BD4?style=flat-square&logo=dotnet&logoColor=white)
![Dapper](https://img.shields.io/badge/ORM-Dapper-00599C?style=flat-square)
![SignalR](https://img.shields.io/badge/Realtime-SignalR-512BD4?style=flat-square&logo=dotnet&logoColor=white)
- **Patterns & Flow:** Clean Architecture and CQRS pattern using MediatR for isolation of business logic from infrastructure.
- **Reliability & Configuration:** Options Pattern with `ValidateOnStart` to ensure fail-fast configuration startup validation.
- **Security & Authorization:** Role-Based Access Control (RBAC) and strict server-side role data masking.

### Cloud, Storage & DevOps
![Azure SQL](https://img.shields.io/badge/Azure_SQL-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)
![Azure Blob](https://img.shields.io/badge/Azure_Blob_Storage-0078D4?style=flat-square&logo=microsoftazure&logoColor=white)
![Docker](https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white)
![Caddy](https://img.shields.io/badge/Caddy-1F88C0?style=flat-square&logo=caddy&logoColor=white)
![Git](https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white)
![Linux](https://img.shields.io/badge/Linux-FCC624?style=flat-square&logo=linux&logoColor=black)
- **Cloud Infrastructure:** Azure SQL Database with migration scripts and schema versioning; segregated Azure Blob Storage containers.
- **Containerization & Ingress:** Docker Compose environments fronted by Caddy reverse proxy with automated TLS.
- **Network Diagnostics:** Root cause troubleshooting across infrastructure layers, isolating false CORS issues from upstream 502 Bad Gateway events.

---

## Featured Project: OVC MOVE

> **Real-time Event Operation & Interactive Station Run Map Platform**  
> *A distributed full-stack system managing station-based run events with live participant tracking, interactive navigation, and high-frequency state synchronization.*

- **Role:** Full-Stack Software Engineer
- **Environment:** Multi-repository architecture (`ovc-move-app` frontend & `ovc-move-service` backend)
- **Key Contributions & Architectural Highlights:**
  - **Scalable Frontend Architecture:** Engineered the client application on React 19 and TailwindCSS v4 with Feature-Sliced Design (FSD), eliminating cross-slice circular dependencies.
  - **Interactive Station Map Engine:** Implemented an SVG coordinate calculation engine supporting zoom, pan, and dynamic station markers reflecting live status.
  - **Low-Latency State Sync:** Integrated SignalR hubs with TanStack Query caching for real-time bi-directional synchronization across client devices.
  - **Server-Side Security & Anti-Cheat:** Enforced server-side role data masking to sanitize challenge content before payload dispatch, preventing unauthorized client-side inspection.
  - **Containerized Infrastructure:** Orchestrated backend and frontend services via Docker Compose and Caddy reverse proxy, automating HTTPS and routing.

---

## Engineering Mindset & Practices

- **Root Cause Analysis (RCA):** Deep diagnostic approach to production failures — resolving DB migration discrepancies (e.g., column mapping mismatches) and diagnosing container startup crashes (`OptionsValidationException`).
- **Defensive Engineering:** Enforcing configuration and schema invariants at startup (`ValidateOnStart`) rather than risking runtime failures.
- **Collaborative Git Discipline:** Adhering to structured feature-branching workflows (`feature/*`), resolving complex multi-branch merge conflicts, and writing clear pull request documentation.

---

## Education & Foundations

**Ho Chi Minh City University of Technology (HCMUT) - VNU-HCM**  
*Bachelor of Science in Computer Science*  
- **Core Curriculum:** Data Structures & Algorithms, Object-Oriented Analysis & Design, Database Systems, Computer Networks, Operating Systems, Discrete Mathematics.

---

## GitHub Stats

<div align="center">
  <img src="https://github-readme-stats-fast.vercel.app/api?username=nhatnews&show_icons=true&theme=tokyonight&hide_border=true" alt="GitHub Stats" />
  <img src="https://github-readme-stats-fast.vercel.app/api/top-langs/?username=nhatnews&layout=compact&theme=tokyonight&hide_border=true" alt="Top Languages" />
</div>

<br/>

<div align="center">
  <img src="https://streak-stats.demolab.com/?user=nhatnews&theme=tokyonight&hide_border=true" alt="GitHub Streak" />
</div>

---

## Contact

- **University Email:** [tan.nguyennhat07@hcmut.edu.vn](mailto:tan.nguyennhat07@hcmut.edu.vn)
- **Personal Email:** [nhattan123of@gmail.com](mailto:nhattan123of@gmail.com)
- **GitHub Profile:** [github.com/nhatnews](https://github.com/nhatnews)
