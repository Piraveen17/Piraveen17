<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0B1220,45:0F766E,100:38BDF8&height=210&section=header&text=SASIKARAN%20PIRAVEEN&fontSize=38&fontColor=F8FAFC&fontAlignY=36&desc=SOFTWARE%20ENGINEERING%20INTERN%20%E2%80%A2%20AI%20SYSTEMS%20%E2%80%A2%20FULL-STACK&descSize=13&descAlignY=58&animation=twinkling" width="100%" alt="Animated profile header" />

  <img src="https://readme-typing-svg.demolab.com?font=JetBrains+Mono&size=19&duration=3200&pause=800&color=38BDF8&center=true&vCenter=true&width=760&height=48&lines=Building+software+that+solves+real+problems;Engineering+AI-powered+backend+workflows;Exploring+LLM+agents+and+deep+learning;Full-stack+development+from+UI+to+database" alt="Animated typing introduction" />

  <p>
    <a href="https://www.linkedin.com/in/sasikaran-piraveen/">
      <img src="https://img.shields.io/badge/LinkedIn-Connect-0A66C2?style=for-the-badge&logo=linkedin&logoColor=white" alt="LinkedIn" />
    </a>
    <a href="https://piraveen-portfolio.vercel.app">
      <img src="https://img.shields.io/badge/Portfolio-Visit-111827?style=for-the-badge&logo=vercel&logoColor=white" alt="Portfolio" />
    </a>
    <a href="mailto:piraveen1727@gmail.com">
      <img src="https://img.shields.io/badge/Email-Contact-EA4335?style=for-the-badge&logo=gmail&logoColor=white" alt="Email" />
    </a>
    <img src="https://komarev.com/ghpvc/?username=Piraveen17&style=for-the-badge&color=0F766E&label=PROFILE+VIEWS" alt="Profile views" />
  </p>
</div>

<br />

## `whoami` — About Me

<p align="justify">
I'm a <strong>Computer Science undergraduate at the University of Jaffna</strong> and a <strong>Software Engineering Intern at David Pieris Holdings</strong>. I work across backend engineering, full-stack development, and AI-driven automation, with a growing focus on reliable LLM-agent systems and applied deep learning.
</p>

<p align="justify">
I enjoy understanding a problem end to end: from the user interface and API design to database behavior, testing, and the safeguards that make a system dependable.
</p>

- **Currently:** Software Engineering Intern at David Pieris Holdings, working across backend development, R&D, QA, and prompt engineering on a company-wide AI ecosystem for ERP process automation.
- **Research focus:** Deepfake detection by combining RGB visual semantics with Error Level Analysis (ELA) forensic features.
- **Engineering interests:** Backend APIs, LLM agents, workflow orchestration, database systems, and production-minded application design.
- **Based in:** Jaffna, Sri Lanka.

<br />

## 🧠 AI in Practice — Controlled Actions & Governed Text-to-SQL

<p align="justify">
I design AI workflows around a strict philosophy: <strong>let the model interpret and propose; keep execution, validation, and data transformations under deterministic code.</strong> The two projects below are my main evidence of that approach — a research prototype in deepfake detection runs alongside them (see <a href="#-featured-projects">Featured Projects</a>).
</p>

<table width="100%">
  <tr>
    <td width="50%" align="left" valign="top">
      <h3 align="center">📲 WhatsApp Order Flow<br/><sub>Conversational Commerce</sub></h3>
      <p>The assistant clarifies ambiguous item varieties before finalizing an order. Totals are computed by deterministic business logic against database prices — the model proposes the order, the backend confirms the price and issues the order ID.</p>
      <p align="center">
        <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI" />
        <img src="https://img.shields.io/badge/OpenRouter-111827?style=flat-square&logoColor=white" alt="OpenRouter" />
        <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL" />
        <img src="https://img.shields.io/badge/Deterministic_Pricing-2DD4BF?style=flat-square&logoColor=white" alt="Deterministic Pricing" />
      </p>
      <p align="center">
        <a href="https://piraveen17.github.io/Piraveen17/?scenario=kottu">
          <img src="https://img.shields.io/badge/▶_Try_the_Walkthrough-F59E0B?style=for-the-badge&logoColor=white" alt="Try the WhatsApp Order walkthrough" />
        </a>
      </p>
    </td>
    <td width="50%" align="left" valign="top">
      <h3 align="center">🚗 Car Rental Admin RAG<br/><sub>Enterprise Text-to-SQL</sub></h3>
      <p>A natural-language BI assistant for admin users. Queries are routed to either a fixed metric tool or an AST-validated, read-only SQL path (via <code>pgsql-ast-parser</code>), and a second pass checks any numeric claim in the response against the raw database record before it's shown.</p>
      <p align="center">
        <img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white" alt="Next.js" />
        <img src="https://img.shields.io/badge/pgsql--ast--parser-111827?style=flat-square&logoColor=white" alt="pgsql-ast-parser" />
        <img src="https://img.shields.io/badge/Supabase_RPC-3FCF8E?style=flat-square&logo=supabase&logoColor=white" alt="Supabase RPC" />
      </p>
      <p align="center">
        <a href="https://piraveen17.github.io/Piraveen17/?scenario=admin_rag">
          <img src="https://img.shields.io/badge/▶_Try_the_Walkthrough-F59E0B?style=for-the-badge&logoColor=white" alt="Try the Car Rental AI assistant walkthrough" />
        </a>
      </p>
    </td>
  </tr>
</table>

<br />

## 🚀 Featured Projects

<table width="100%">
  <tr>
    <td width="33%" align="center" valign="top">
      <h3 align="center">📲 WhatsApp Order Management</h3>
      <p>A production system enabling customers to perform full CRUD operations on orders through WhatsApp conversations, powered by specialist LLM agents on a layered architecture.</p>
      <p><strong>Design focus:</strong> a safety-first design where agents propose structured tool-call actions while deterministic code executes every mutation behind explicit confirmation; prices and totals are always rendered from verified DB reads, never generated by the LLM.</p>
      <p align="center">
        <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
        <img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI" />
        <img src="https://img.shields.io/badge/OpenRouter-111827?style=flat-square&logoColor=white" alt="OpenRouter" />
        <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL" />
        <img src="https://img.shields.io/badge/WhatsApp_Business_API-25D366?style=flat-square&logo=whatsapp&logoColor=white" alt="WhatsApp Business API" />
      </p>
    </td>
    <td width="33%" align="center" valign="top">
      <h3 align="center">🕵️ Deepfake Detection</h3>
      <p>Early-stage research investigating the fusion of RGB semantic features and ELA forensic features through adaptive attention weighting.</p>
      <p><strong>Status:</strong> architecture and fusion method defined; experiments and results in progress.</p>
      <p align="center">
        <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
        <img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" alt="PyTorch" />
        <img src="https://img.shields.io/badge/Google_Colab-F9AB00?style=flat-square&logo=googlecolab&logoColor=white" alt="Google Colab" />
      </p>
    </td>
    <td width="33%" align="center" valign="top">
      <h3 align="center">🚗 Car Rental & AI Analytics</h3>
      <p>A full-stack rental platform with an AST-governed Text-to-SQL analytics assistant, booking date-overlap validation, automated invoicing, and role-based access control.</p>
      <p><strong>Design focus:</strong> read-only Text-to-SQL planning, AST-level query security via <code>pgsql-ast-parser</code>, and a second-pass check that cross-verifies numeric answers against the raw records.</p>
      <p align="center">
        <img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white" alt="Next.js" />
        <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
        <img src="https://img.shields.io/badge/Supabase_Auth-3FCF8E?style=flat-square&logo=supabase&logoColor=white" alt="Supabase Auth" />
        <img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL" />
        <img src="https://img.shields.io/badge/shadcn%2Fui-111827?style=flat-square&logo=shadcnui&logoColor=white" alt="shadcn/ui" />
      </p>
      <p align="center">
        <a href="https://car-rental-l5zj4kcqu-piraveen-s-projects.vercel.app/">
          <img src="https://img.shields.io/badge/🔗_Live_Demo-16A34A?style=for-the-badge&logoColor=white" alt="Car Rental live demo" />
        </a>
      </p>
    </td>
  </tr>
  <tr>
    <td width="33%" align="center" valign="top">
      <h3 align="center">🛡️ CheatShield</h3>
      <p>A university group project for exam-environment control.</p>
      <p><strong>My contribution:</strong> implemented allowlist-based web access control with polling-based policy synchronization, symmetric-key client registration (TTL), and secure admin-to-client policy enforcement; validated end-to-end workflows and API behavior using Postman.</p>
      <p align="center">
        <img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white" alt="Next.js" />
        <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
        <img src="https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white" alt="MongoDB" />
        <img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
        <img src="https://img.shields.io/badge/Postman-FF6C37?style=flat-square&logo=postman&logoColor=white" alt="Postman" />
      </p>
      <p align="center">
        <a href="https://cheatshield-dcs.vercel.app/">
          <img src="https://img.shields.io/badge/🔗_Live_Demo-16A34A?style=for-the-badge&logoColor=white" alt="CheatShield live demo" />
        </a>
      </p>
    </td>
    <td width="33%" align="center" valign="top">
      <h3 align="center">💼 Olirsuite</h3>
      <p>A company-management group project.</p>
      <p><strong>My contribution:</strong> built responsive frontend modules, integrated backend APIs, and contributed to income/expense transaction workflows and testing.</p>
      <p align="center">
        <img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white" alt="Next.js" />
        <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
        <img src="https://img.shields.io/badge/shadcn%2Fui-111827?style=flat-square&logo=shadcnui&logoColor=white" alt="shadcn/ui" />
        <img src="https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white" alt="MongoDB" />
      </p>
      <p align="center">
        <a href="https://olir-suite-one.vercel.app/">
          <img src="https://img.shields.io/badge/🔗_Live_Demo-16A34A?style=for-the-badge&logoColor=white" alt="Olirsuite live demo" />
        </a>
      </p>
    </td>
    <td width="33%" align="center" valign="top">
      <h3 align="center">🍽️ JeyaFoods</h3>
      <p>A group food-ordering project.</p>
      <p><strong>My contribution:</strong> built responsive menu pages and reusable UI components, implementing global search and filtering to improve item discovery and navigation consistency.</p>
      <p align="center">
        <img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white" alt="Next.js" />
        <img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
        <img src="https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white" alt="MongoDB" />
      </p>
    </td>
  </tr>
  <tr>
    <td width="100%" colspan="3" align="center" valign="top">
      <h3 align="center">📅 Resource Hub Management System</h3>
      <p>A university group project for scheduling and booking shared resources.</p>
      <p><strong>My contribution:</strong> implemented a resource scheduling calendar UI (availability + booked slots) and booking workflows with input validation.</p>
      <p align="center">
        <img src="https://img.shields.io/badge/HTML-E34F26?style=flat-square&logo=html5&logoColor=white" alt="HTML" />
        <img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white" alt="Tailwind CSS" />
        <img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" alt="JavaScript" />
        <img src="https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white" alt="PHP" />
      </p>
    </td>
  </tr>
</table>

<br />

## 🧰 Tech Stack

<div align="center">

**Languages**

<img src="https://img.shields.io/badge/Python-3776AB?style=flat-square&logo=python&logoColor=white" alt="Python" />
<img src="https://img.shields.io/badge/TypeScript-3178C6?style=flat-square&logo=typescript&logoColor=white" alt="TypeScript" />
<img src="https://img.shields.io/badge/JavaScript-F7DF1E?style=flat-square&logo=javascript&logoColor=black" alt="JavaScript" />
<img src="https://img.shields.io/badge/Java-ED8B00?style=flat-square&logo=openjdk&logoColor=white" alt="Java" />
<img src="https://img.shields.io/badge/C%2B%2B-00599C?style=flat-square&logo=cplusplus&logoColor=white" alt="C++" />
<img src="https://img.shields.io/badge/PHP-777BB4?style=flat-square&logo=php&logoColor=white" alt="PHP" />

<br /><br />

**Frontend**

<img src="https://img.shields.io/badge/Next.js-000000?style=flat-square&logo=nextdotjs&logoColor=white" alt="Next.js" />
<img src="https://img.shields.io/badge/React-20232A?style=flat-square&logo=react&logoColor=61DAFB" alt="React" />
<img src="https://img.shields.io/badge/Tailwind_CSS-06B6D4?style=flat-square&logo=tailwindcss&logoColor=white" alt="Tailwind CSS" />
<img src="https://img.shields.io/badge/shadcn%2Fui-111827?style=flat-square&logo=shadcnui&logoColor=white" alt="shadcn/ui" />
<img src="https://img.shields.io/badge/HTML5-E34F26?style=flat-square&logo=html5&logoColor=white" alt="HTML5" />
<img src="https://img.shields.io/badge/CSS3-1572B6?style=flat-square&logo=css3&logoColor=white" alt="CSS3" />

<br /><br />

**Backend, AI & Data**

<img src="https://img.shields.io/badge/FastAPI-009688?style=flat-square&logo=fastapi&logoColor=white" alt="FastAPI" />
<img src="https://img.shields.io/badge/LangGraph-1C3C3C?style=flat-square&logoColor=white" alt="LangGraph" />
<img src="https://img.shields.io/badge/PyTorch-EE4C2C?style=flat-square&logo=pytorch&logoColor=white" alt="PyTorch" />
<img src="https://img.shields.io/badge/NestJS-E0234E?style=flat-square&logo=nestjs&logoColor=white" alt="NestJS" />
<img src="https://img.shields.io/badge/PostgreSQL-4169E1?style=flat-square&logo=postgresql&logoColor=white" alt="PostgreSQL" />
<img src="https://img.shields.io/badge/MongoDB-47A248?style=flat-square&logo=mongodb&logoColor=white" alt="MongoDB" />
<img src="https://img.shields.io/badge/MySQL-4479A1?style=flat-square&logo=mysql&logoColor=white" alt="MySQL" />
<img src="https://img.shields.io/badge/Oracle-F80000?style=flat-square&logo=oracle&logoColor=white" alt="Oracle" />
<img src="https://img.shields.io/badge/SQLite-003B57?style=flat-square&logo=sqlite&logoColor=white" alt="SQLite" />

<br /><br />

**Tools & Platforms**

<img src="https://img.shields.io/badge/Git-F05032?style=flat-square&logo=git&logoColor=white" alt="Git" />
<img src="https://img.shields.io/badge/GitHub-181717?style=flat-square&logo=github&logoColor=white" alt="GitHub" />
<img src="https://img.shields.io/badge/Docker-2496ED?style=flat-square&logo=docker&logoColor=white" alt="Docker" />
<img src="https://img.shields.io/badge/Redis-DC382D?style=flat-square&logo=redis&logoColor=white" alt="Redis" />
<img src="https://img.shields.io/badge/Microsoft_Entra_ID-5E5E5E?style=flat-square&logo=microsoft&logoColor=white" alt="Microsoft Entra ID" />
<img src="https://img.shields.io/badge/Postman-FF6C37?style=flat-square&logo=postman&logoColor=white" alt="Postman" />
<img src="https://img.shields.io/badge/Bitbucket-0052CC?style=flat-square&logo=bitbucket&logoColor=white" alt="Bitbucket" />
<img src="https://img.shields.io/badge/Jira-0052CC?style=flat-square&logo=jira&logoColor=white" alt="Jira" />

</div>

<br />

## 🤝 Let's Connect

<div align="center">

<p align="justify">
I'm interested in thoughtful software engineering, AI-powered products, and collaborating on projects that solve meaningful problems.
</p>

<a href="https://www.linkedin.com/in/sasikaran-piraveen/">LinkedIn</a> ·
<a href="https://piraveen-portfolio.vercel.app">Portfolio</a> ·
<a href="mailto:piraveen1727@gmail.com">Email me</a>

</div>

<div align="center">
  <img src="https://capsule-render.vercel.app/api?type=waving&color=0:0B1220,45:0F766E,100:38BDF8&height=110&section=footer" width="100%" alt="Decorative animated footer" />
</div>
