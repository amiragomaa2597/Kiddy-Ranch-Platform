# Architecture Overview

## Two paired systems

1. **Marketing / admissions:** `kiddy` ↔ `kiddyMainSiteApi`
2. **Operations / finance:** `KiddyRanchFront` ↔ `kiddyApi`

## Ops API layering

```text
ProjectAPI.PresentationLayer  → HTTP controllers
BusinessLogicLayer            → services, DTOs, AutoMapper, email, jobs
DataAccessLayer               → EF StoreContext, repositories, migrations
Shared                        → current-user / cross-cutting helpers
```

## Marketing API layering

```text
KiddyRanchWeb.API  → controllers
KiddyRanchWeb.BL   → managers
KiddyRanchWeb.DAL  → AppDbContext, migrations
```

## Why employers care

Shows ability to ship and maintain **multiple cooperating apps**, unify domains over time (invoice merge), and keep public vs private concerns separated.
