# Core Features — Landing, Students, Transactions

## Landing page

| Capability | Evidence |
|------------|----------|
| Brand home / hero | `kiddy` `LandingComponent`, route `/home` |
| Second brand page | `Landing2Component` (`Kiddy House`) |
| Public join / interview form | `JoinUsComponent` → StudentInterviews API |
| CMS sections / branches | Sections & Branches controllers + staff customization UI |
| Live site | https://www.kiddyranch.com |

## Student management

| Capability | Evidence |
|------------|----------|
| Interview pipeline | `StudentInterviews` API + kids interview dashboard |
| Enrolled student CRUD | `api/Student` + student table/forms in ops SPA |
| Bulk import | `POST api/Student/bulk-import` |
| Registration requests | Anonymous create + admin approve/reject flow |
| Classes / courses / buses | Matching controllers and ops pages |

## Transactions

| Capability | Evidence |
|------------|----------|
| Income / expense / transfer | `api/Transactions` + invoices transactions UI |
| Accounts & categories | `api/Accounts`, `api/Categories` |
| Payment items | `api/PaymentItem`, `api/Payment` |
| Reports / remaining / next payments | Ops SPA invoice report routes + statistic endpoints |
| Export | Client jsPDF / xlsx in ops frontend |
