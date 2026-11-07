# Agent Prompt — Kiddy Ranch HR Portfolio Case Study

Copy and paste the prompt below into a new Agent chat to recreate or refresh this public case-study repository from private source.

---

## Prompt (copy from here)

```text
# Task: Analyze My GitHub Kiddy Ranch Projects and Create a Professional Public Portfolio Repository for HR

You are an AI software engineering agent with authorized access to my GitHub account.

My GitHub username is:

`amiragomaa2597`

## 1. Source Repositories

Analyze these private repositories thoroughly (landing + student management + transactions):

| Role | Repository |
|------|------------|
| Public marketing / admissions frontend | `amiragomaa2597/kiddy` |
| Public / admissions backend API | `amiragomaa2597/kiddyMainSiteApi` |
| Nursery operations frontend (students + finance UI) | `amiragomaa2597/KiddyRanchFront` |
| Unified student + transactions/invoice API | `amiragomaa2597/kiddyApi` |

These repositories are parts of the same brand ecosystem: **Kiddy Ranch** (nursery / preschool operations and public website).

Use GitHub access or local clones. If access is denied, explain the exact permission issue and do not assume anything about the project.

Do not modify visibility of private source repositories. Do not publish private source code.

## 2. Main Objective

I am preparing my CV for a Full Stack Web Developer position (educational / nursery / school operations context).

The company / recruiter should understand that I have built and maintained real systems covering:

- Public educational / nursery landing pages
- Student (or child) management workflows
- Transactions, payments, and financial operations
- Backend APIs and database design
- Full-stack architecture
- Maintaining and improving existing systems

Identify which of these capabilities are genuinely implemented. Do not claim a feature exists unless you find evidence in the source code.

## 3. Technical Analysis

Inspect all four repositories, including:

- Folder and project structure
- Frontend frameworks and libraries (Angular versions, SSR if present)
- Backend frameworks and libraries (.NET versions, EF Core, Identity, JWT)
- API controllers and endpoints (students, transactions, payments, interviews, auth)
- Services and business logic
- Database models, relationships, and migrations
- Authentication and authorization (roles, permissions, branch scoping)
- Integrations (email, WhatsApp, PDF/Excel) — only if verified
- How frontends communicate with backends (environment URLs, interceptors)
- Architecture and design patterns
- Any unification / migration docs (e.g. invoice API merge into student API)

Distinguish clearly:

- Verified implementation
- Inferred architecture
- Features that need my confirmation

Known product split to validate (do not invent beyond evidence):

- `kiddy` + `kiddyMainSiteApi` ≈ public site + interview/admissions CRM
- `KiddyRanchFront` + `kiddyApi` ≈ enrolled student ops + transactions/finance

## 4. My Professional Portfolio

Create a new PUBLIC GitHub repository named:

`Kiddy-Ranch-Platform`

This repository must be a professional, HR-friendly technical case study.

It must NOT contain the private source code from my original repositories.

Create a detailed and attractive README.md containing:

1. Project Overview
2. Project Purpose
3. My Role and Contributions
4. System Architecture
5. Frontend Technologies
6. Backend Technologies
7. Database Architecture
8. Main Features (landing, students, transactions)
9. API Architecture
10. Authentication and Security (only verified features)
11. Technical Challenges and Solutions (only supported by evidence)
12. Screenshots section
13. Demo / Live Platform links, if available
14. Project Structure
15. Source Code Availability

Add architecture diagrams using Mermaid where useful.

Use professional English suitable for technical recruiters and engineering managers.

## 5. Accurate Professional Representation

My profile:

- Full Stack Web Developer
- Approximately 3 years of professional software development experience
- Strong experience with C#, ASP.NET Core, Angular, SQL Server, and full-stack development
- Experience building real business and educational software systems

Describe my contributions professionally, but do not exaggerate my responsibilities or claim that I independently built every feature unless the repositories support that.

Check git history for multiple contributors and describe the product as team-built when evidence shows it.

## 6. Public Repository Requirements

Include:

- A professional README
- Clear technical documentation
- Mermaid architecture diagrams
- A clean repository structure
- Appropriate topics and descriptions
- No open-source license unless I explicitly approve it

Do not publish:

- Private source code
- API keys or secrets
- Passwords or connection strings
- Personal information
- Private student / parent / child data
- Hardcoded JWTs found in comments
- Unredacted screenshots with PII

Live URL that may be listed if verified in code/config: `https://www.kiddyranch.com`

## 7. CV Integration

At the end, provide:

- The best project title for my CV
- A concise CV project description (3–5 bullet points)
- The technologies I can confidently list
- The strongest verified features
- The public GitHub URL
- A short explanation of why this project is relevant to an educational / nursery technology employer

## 8. Execution Rules

- First inspect and analyze the source repositories.
- Do not modify or rename the original repositories.
- Do not change their visibility.
- Do not delete, overwrite, or expose any source code.
- Create the new public repository only after confirming that the analysis is complete.
- If repository creation is unavailable, provide the complete README and all required files so I can publish them myself.
- Never fabricate project details, screenshots, URLs, features, or results.
- Prefer accurate wording: e.g. if WhatsApp is only a stored phone field, do not claim WhatsApp API integration; if PDF is generated in the browser, say client-side PDF export.

The final result should make this project look like a credible, professionally documented Full Stack Nursery / Educational Operations case study that I can confidently share with HR.
```

---

## Confirmed source mapping (filled after analysis)

| Portfolio focus | Source repos |
|-----------------|--------------|
| Landing page | `kiddy` (Angular SSR marketing) + `kiddyMainSiteApi` |
| Student management | `KiddyRanchFront` + `kiddyApi` (enrolled students); interviews in `kiddy` + `kiddyMainSiteApi` |
| Transactions | `KiddyRanchFront` invoices UI + `kiddyApi` Transactions/Accounts/PaymentItem APIs |
