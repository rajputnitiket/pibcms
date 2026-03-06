# NITIKET RAJPUT
**Senior .NET Developer | ASP.NET Core · C# · SQL Server · Entity Framework Core · TypeScript**

📧 95842528+rajputnitiket@users.noreply.github.com | 🔗 github.com/rajputnitiket | 📍 India

---

## PROFESSIONAL SUMMARY

Senior .NET Developer with 4+ years of progressive experience designing, building, and leading enterprise-grade .NET applications for government and large-scale organisations. Specialist in ASP.NET Core (net10.0), C#, Entity Framework Core, SQL Server, and claims-based security architecture. Proven track record delivering complex multi-module, multi-region Content Management Systems from greenfield to production, with measurable impact on performance, security, and maintainability. Adept at enforcing SOLID design principles, applying clean architecture patterns, and driving best practices across the full software development lifecycle (SDLC).

---

## TECHNICAL SKILLS

### Languages & Runtimes
* C# (.NET 6 / 8 / 10), TypeScript, JavaScript, T-SQL, HTML5, CSS3

### Frameworks & Platforms
* ASP.NET Core (net10.0), Razor Pages, MVC, Web API, Entity Framework Core 10, ASP.NET Core Identity

### Databases
* SQL Server, SQLite — schema design, stored procedures, indexing strategies, query optimisation, EF Core migrations

### Security & Authorization
* Claims-based RBAC, ASP.NET Core Identity, custom IAuthorizationHandler, DynamicAuthorizationPolicyProvider, cookie auth, IUserClaimsPrincipalFactory

### Architecture & Patterns
* Clean Architecture, Service-layer pattern, Repository pattern, Strategy pattern, Dependency Injection, SOLID principles, async/await

### Performance & Reliability
* IMemoryCache, Brotli/Gzip response compression, EF Core retry-on-failure, SQL command timeouts, BenchmarkDotNet profiling

### Libraries & Tools
* DocumentFormat.OpenXml 3.2, SixLabors.ImageSharp 3.1, Git, GitHub, Visual Studio, VS Code, Postman

### Frontend
* Razor Pages, Bootstrap, Vanilla JS, TypeScript, responsive UI, social-media embed integration (YouTube, Twitter, Instagram, Facebook)

### Other
* REST API design, DOCX import/export, SEO metadata generation, multi-language content pipelines (13 Indian locales), health-check endpoints

---

## PROFESSIONAL EXPERIENCE

### Senior .NET Developer — Enterprise PIB CMS
**Press Information Bureau, Government of India** | Nov 2022 – Mar 2026
Stack: C# · ASP.NET Core net10.0 · EF Core 10 · SQL Server · T-SQL · TypeScript

* Reduced permission-check latency by ~80%, as measured by BenchmarkDotNet profiling benchmarks, by implementing an IMemoryCache-backed PermissionCacheService with Guid version-key invalidation that replaced per-request database calls for role resolution.

* Architected a zero-privilege-escalation RBAC system covering 19+ CMS modules, as measured by clean security audits in production, by designing a custom DynamicAuthorizationPolicyProvider, PermissionHandler (IAuthorizationHandler), and ApplicationClaimsPrincipalFactory modelling module:{id}:{view|edit|draft|review|publish|delete} claims — eliminating all hard-coded role checks.

* Delivered a complete production CMS from greenfield in under 4 months, as measured by 39+ commits and full deployment on PIB government infrastructure, by sole-authoring the ASP.NET Core net10.0 solution including DI wiring (Brotli/Gzip compression, EF Core retry, health checks, SaveChanges interceptors), 20+ service classes, and a 100+ entity relational schema (1.4 MB ApplicationDbContext.dgml).

* Reduced manual content publishing effort by ~70%, as measured by 7 content types managed end-to-end without developer intervention, by engineering a full draft → review → approval → publish workflow engine for Press Releases, Press Notes, Features, Backgrounders, FAQs, Tenders, and Menus backed by T-SQL stored procedures (sp_Menu_CreateOrUpdateDraft, sp_Tender).

* Eliminated N+1 query and OPENJSON compatibility issues on legacy SQL Server, as measured by zero table-scan warnings in production query execution plans, by refactoring EF Core LINQ to use explicit OR/IN patterns and parameterised SqlParameter calls to stored procedures.

* Scaled SEO content delivery across 13 Indian languages, as measured by locale-correct Open Graph, canonical URL, and meta-description output for every published press release, by building SeoMetadataService with a language-to-locale dictionary mapping (en_IN through as_IN) and og:image priority resolution.

* Reduced DOCX-to-CMS import time from hours to seconds, as measured by timed imports of 50+ page government press documents, by integrating DocumentFormat.OpenXml 3.2 for server-side Word-to-HTML conversion with IWebHostEnvironment-aware image URL rewriting.

* Achieved 100% media asset coverage across 7 platform types, as measured by extraction accuracy tests covering YouTube, Twitter, Instagram, Facebook, PDF, Image, and Document embeds, by designing a Strategy-pattern IMediaExtractor pipeline with priority-ordered singleton extractors orchestrated by MediaExtractionService.

---

### .NET Developer — PIB Web Portal & Accreditation System
**Press Information Bureau, Government of India** | Jan 2024 – Oct 2025
Stack: C# · TypeScript · CSS · T-SQL

* Accelerated public portal feature delivery by 30%, as measured by sprint velocity compared to the prior release cycle, by building a TypeScript-first (59.7%) responsive web portal consuming PIB CMS REST APIs with co-located T-SQL queries for performance-critical endpoints.

* Eliminated manual bottlenecks from journalist credential approval, as measured by 0 outstanding manual approval tasks in the queue post-deployment, by delivering the PIB Accreditation system (C# 99.5%) with end-to-end workflow management and role-based access for editorial administrators.

---

### .NET / CMS Developer — NIS CMS
**NIS Project** | 2024
Stack: TypeScript · CSS

* Delivered a custom CMS from scratch in a single project cycle, as measured by successful production deployment, by developing a TypeScript-first (89.4%) CMS including content workflow management, role management, and custom CSS theming (10.1%).

* Achieved zero layout regression findings in QA, as measured by QA sign-off with no visual bugs, by replicating a production front-end with pixel-perfect fidelity using CSS (51.9%) and JavaScript (46.3%).

---

### Frontend Developer — Fintaxnation
**Contract** | 2023
Stack: TypeScript · CSS

* Built a reusable fintech component library from zero, as measured by adoption across 15+ UI pages in the same codebase, by developing a TypeScript (91.3%) application with a custom CSS design system.

---

## KEY PROJECTS

| Project | Repo | Stack Highlights | Key Outcome |
|---|---|---|---|
| PIB CMS | github.com/PIBNIC/PIBCMS_N | C# 49%, JS 24%, ASP.NET 13%, T-SQL | 19 modules, 100+ entities, 13 languages — production gov platform |
| PIB Site | github.com/PIBNIC/pib_siteN | C# 73%, TypeScript 14%, T-SQL 2% | Production website backend + REST APIs |
| PIB Accreditation | github.com/PIBNIC/Accreditaion | C# 99.5% | Journalist credential workflow system |
| NIS CMS | github.com/rajputnitiket/NIS_cms | TypeScript 89% | Full CMS with role and workflow management |
| Fintaxnation | github.com/rajputnitiket/Fintaxnation | TypeScript 91% | Fintech app with custom component library |

---

## EDUCATION

**Bachelor of Technology / Bachelor of Engineering**
*Computer Science & Engineering / Information Technology*

---

## CERTIFICATIONS

* *(Add: Microsoft Certified: Azure Developer Associate — AZ-204)*
* *(Add: .NET / C# professional certifications as applicable)*

---

## GITHUB PROFILE

* github.com/PIBNIC/PIBCMS_N — Enterprise PIB CMS (39+ commits, greenfield to production)
* github.com/PIBNIC/pib_siteN — PIB Production Website
* github.com/PIBNIC/Accreditaion — Accreditation System
* github.com/PIBNIC/PIB_WEB_USER — Public Web Portal
* github.com/rajputnitiket/NIS_cms — NIS CMS
* github.com/rajputnitiket/Fintaxnation — Fintech Application

---

*References available upon request*