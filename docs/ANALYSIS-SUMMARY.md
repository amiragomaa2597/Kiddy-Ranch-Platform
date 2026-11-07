# Analysis Summary — Evidence Classification

Analysis date: November 2026  
Sources: shallow clones of private repos under local analysis workspace.

## Confirmed repositories

| Repo | Stack | Role |
|------|-------|------|
| `amiragomaa2597/kiddy` | Angular 17 + SSR | Public landing + interview admin |
| `amiragomaa2597/kiddyMainSiteApi` | ASP.NET Core 8 | Marketing/CRM API |
| `amiragomaa2597/KiddyRanchFront` | Angular 20 | Students + transactions UI |
| `amiragomaa2597/kiddyApi` | ASP.NET Core 8 | Unified student + finance API |

## Capability matrix

| Focus | Status | Notes |
|-------|--------|-------|
| Landing page | **Verified** | `kiddy` landing/home + live `kiddyranch.com` |
| Student management (enrolled) | **Verified** | Ops SPA + `api/Student` + registration requests |
| Student admissions interviews | **Verified** | Marketing stack `StudentInterviews` |
| Transactions / payments | **Verified** | Ops invoices UI + `Transactions`/`Accounts`/`PaymentItem` |
| WhatsApp messaging API | **Not verified** | Phone/link fields only |
| Server PDF invoices | **Not verified** | Client-side PDF libs in ops FE |
| Unified invoice+student API | **Verified** | `DEPLOY-UNIFIED.md` + invoice migration |

## Strongest verified signals for HR

1. Real nursery ops domain (students, classes, buses, finance)
2. Public educational marketing site with SSR-capable Angular
3. Full-stack .NET 8 + Angular delivery across two related systems
4. JWT/Identity auth with permissions and branch scoping on ops API
5. Evidence of maintaining/merging systems (invoice unification)
