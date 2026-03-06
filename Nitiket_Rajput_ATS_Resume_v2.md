# NITIKET RAJPUT
**Full Stack Developer | ASP.NET Core · C# · SQL Server · EF Core · TypeScript**

📧 95842528+rajputnitiket@users.noreply.github.com | 🔗 github.com/rajputnitiket | 📍 India

---

## PROFESSIONAL SUMMARY

Results-driven Full Stack Developer specialising in enterprise-grade Content Management Systems (CMS) for government and large-scale organisations. Hands-on expertise building production ASP.NET Core (net10.0) applications with claim-based authorisation, EF Core + SQL Server, Razor Pages, RESTful APIs, and rich content workflows. Proven ability to architect complex multi-module systems, design performant database schemas, and deliver clean, maintainable C# code under real-world constraints.

---

## TECHNICAL SKILLS

| Category | Technologies |
|---|---|
| **Languages** | C#, TypeScript, JavaScript, SQL (T-SQL), HTML5, CSS3 |
| **Frameworks** | ASP.NET Core (net10.0), Razor Pages, MVC, Entity Framework Core 10 |
| **Frontend** | Bootstrap, Vanilla JS, responsive UI, social-media embed integration |
| **Database** | SQL Server, SQLite, stored procedures, schema design, indexing, query optimisation |
| **Auth & Security** | ASP.NET Core Identity, Claims-based RBAC, custom `IAuthorizationHandler`, dynamic policy provider |
| **Cloud / DevOps** | Git, GitHub, health-check endpoints, response compression (Brotli/Gzip) |
| **Libraries / Packages** | DocumentFormat.OpenXml 3.2, SixLabors.ImageSharp 3.1, IMemoryCache, BenchmarkDotNet |
| **Patterns** | Repository pattern, Service-layer pattern, Strategy pattern (media extractors), Dependency Injection |
| **Other** | REST APIs, DOCX import/export, SEO metadata generation, AI-powered content summarisation |

---

## PROFESSIONAL EXPERIENCE

### Full Stack Developer — PIB CMS (PIBNIC/PIBCMS_N)
**Press Information Bureau, Government of India** | Nov 2025 – Mar 2026 | github.com/PIBNIC/PIBCMS_N

Architected and built the complete backend and frontend for the Press Information Bureau's next-generation Content Management System — a multi-region, multi-language enterprise platform serving government press and media operations.

**Key Contributions:**

- **ASP.NET Core application on net10.0** — designed `Program.cs` bootstrap with scoped/singleton DI, response compression (Brotli + Gzip), EF Core retry-on-failure, health-check endpoints, and custom SaveChanges interceptors for permission-cache invalidation
- **Claims-based Role & Module Access Control** — implemented custom `IUserClaimsPrincipalFactory`, `IAuthorizationHandler` (`PermissionHandler`), and `DynamicAuthorizationPolicyProvider`; modelled granular permissions (`module:{id}:{action}`) for 19+ CMS modules across editors, reviewers, publishers, and admins
- **Content Workflow Engine** — built full draft → review → approval → publish lifecycle for Press Releases, Press Notes, Features, Backgrounders, FAQs, Tenders, and Menus via stored procedures (`sp_Menu_CreateOrUpdateDraft`, `sp_Tender`, etc.)
- **Service Layer (20+ services)** — authored `PressNoteService`, `MenuService`, `TenderService`, `SeoMetadataService`, `UserService`, `ModuleAccessService`, `PermissionCacheService`, `PaginationService`, and `ContentAnalysis` subsystem
- **Content Analysis Subsystem** — designed Strategy-pattern media extraction pipeline (`ImageExtractor`, `YouTubeExtractor`, `TwitterExtractor`, `InstagramExtractor`, `FacebookExtractor`, `PdfExtractor`, `DocumentExtractor`); `MetaTagGenerator` with frequency analysis, proper-noun extraction, and multilingual stop-word support; `TextAnalyzer` with sentence splitting and keyword extraction
- **SEO Metadata Service** — auto-generates Open Graph tags, canonical URLs, og:image, and locale-aware meta descriptions across 13 Indian languages (English, Hindi, Urdu, Tamil, Telugu, Malayalam, Kannada, Bengali, Marathi, Gujarati, Punjabi, Odia, Assamese)
- **DOCX Import/Export** — integrated `DocumentFormat.OpenXml` for importing Word documents and converting to HTML with environment-aware image URL prefixing (`IWebHostEnvironment` + `IConfiguration`)
- **Database Design** — authored a large-scale relational schema (ApplicationDbContext with 100+ entities visible in 1.4 MB `.dgml` diagram); optimised EF Core queries to avoid OPENJSON on legacy SQL Server; introduced explicit OR/IN patterns as alternatives to `Contains` over list parameters
- **Image Processing** — integrated `SixLabors.ImageSharp` for server-side image manipulation and thumbnail generation
- **Performance & Reliability** — implemented `IMemoryCache`-backed `PermissionCacheService` with version-key invalidation; SQL command timeout and transient-failure retry; `BenchmarkUserRoleModuleLoading` for profiling permission-load hot paths
- **Multi-language & Multi-region** — managed region-scoped content access control; AllowedRegionIds filtering passed to stored procedures; SuperAdmin bypass logic for cross-region operations
- **Unique Identifier Migration** — refactored press-release routing to use `PermPrid` as the stable permanent identifier across temp/perm tables, enabling reliable bulk operations and deep-link stability

**Technologies:** C# · ASP.NET Core net10.0 · Razor Pages · EF Core 10 · SQL Server · T-SQL · TypeScript · JavaScript · Bootstrap · DocumentFormat.OpenXml · SixLabors.ImageSharp · GitHub

---

### Frontend Developer — PIB Web Portal (PIBNIC/PIB_WEB_USER)
**Press Information Bureau, Government of India** | 2024 – 2025

- Built TypeScript (59.7%) + CSS (37.8%) public-facing web portal consuming PIB CMS APIs
- Integrated T-SQL (1.9%) data queries and designed responsive page layouts

---

### CMS Developer — NIS CMS (rajputnitiket/NIS_cms)
**NIS Project** | 2024

- Developed TypeScript-first (89.4%) CMS with custom CSS theming (10.1%)
- Delivered full content management workflow from scratch

---

### Frontend Developer — NIS Clone & Fintaxnation
**Personal / Contract Projects** | 2023 – 2024

- **NIS Clone** — CSS (51.9%) + JavaScript (46.3%) pixel-perfect responsive front-end replication
- **Fintaxnation** — TypeScript (91.3%) + CSS fintech application with custom component library

---

## PROJECTS

### PIB CMS — Press Information Bureau CMS *(Production System)*
**Repo:** github.com/PIBNIC/PIBCMS_N | **Stack:** C# 49% · JS 24% · ASP.NET 13% · HTML 11% · CSS 2% · T-SQL 1%

Enterprise CMS for India's primary government press agency. Highlights:
- 39+ commits architecting full system from greenfield to production
- 20+ service classes covering content lifecycle, SEO, media, users, permissions, and caching
- 19+ CMS modules with granular claim-based access (`module:{id}:{view|edit|draft|review|publish|delete}`)
- `ApplicationDbContext.dgml` — 1.4 MB entity relationship diagram representing full database schema
- Multilingual support for 13 Indian languages with locale-aware SEO metadata

### PIB Site (PIBNIC/pib_siteN)
**Stack:** C# 73% · TypeScript 14% · CSS 9% · T-SQL 2%
Production PIB website backend and API layer.

### PIB Accreditation (PIBNIC/Accreditaion)
**Stack:** C# 99.5%
Press accreditation management system for journalist credential workflows.

---

## EDUCATION

**Bachelor of Technology / Bachelor of Engineering**
*Computer Science & Engineering / Information Technology*

---

## KEY COMPETENCIES

| Competency | Details |
|---|---|
| Enterprise CMS Architecture | Multi-module, multi-region, multi-language government CMS on ASP.NET Core net10.0 |
| Backend Engineering | Clean service-layer design, stored-procedure integration, async/await throughout |
| Claims & Authorization | Custom policy providers, dynamic module-permission model, region-scoped access |
| Database Engineering | Schema design, stored procedures, EF Core query optimisation, SQL Server compatibility |
| Content Intelligence | Media extraction pipeline (7 extractors), SEO generation, DOCX conversion, AI summaries |
| Performance Engineering | In-memory caching with invalidation, response compression, transient-failure retry |
| Frontend Development | Razor Pages, Bootstrap, TypeScript, social-media embeds (YouTube, Twitter, Instagram, Facebook) |
| Version Control | Git, GitHub, collaborative multi-repo development (PIBNIC org) |

---

## GITHUB ACTIVITY

- **github.com/PIBNIC/PIBCMS_N** — Enterprise PIB CMS (C# / ASP.NET Core, 39+ commits)
- **github.com/PIBNIC/pib_siteN** — PIB production website (C# / TypeScript)
- **github.com/PIBNIC/Accreditaion** — PIB Accreditation system (C#)
- **github.com/PIBNIC/PIB_WEB_USER** — PIB public user portal (TypeScript / CSS)
- **github.com/rajputnitiket/NIS_cms** — NIS CMS (TypeScript)
- **github.com/rajputnitiket/Fintaxnation** — Fintech application (TypeScript)

---

*References available upon request*