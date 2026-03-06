# NITIKET RAJPUT
**Senior .NET Developer | Team Lead | ASP.NET Core · C# · EF Core · SQL Server · TypeScript**

Phone: +91 7060552446 | Email: nitiketrajput1@gmail.com | Location: Noida, India
LinkedIn: linkedin.com/in/nitiket-rajput-2b72b3214 | GitHub: github.com/rajputnitiket

---

## PROFESSIONAL SUMMARY

Senior .NET Developer and Team Lead with 3+ years at the Press Information Bureau (NIC), Government of India, specialising in enterprise CMS modernisation, secure authentication, and full-stack .NET development. Led the end-to-end migration of a legacy ASP.NET 4.0 CMS to .NET 8.0/10.0 MVC using EF Core, Identity Framework, and xUnit testing. Proven ability to architect scalable multi-module systems, design performant SQL Server schemas, implement claims-based RBAC, and mentor development teams. Skilled across the full Microsoft .NET stack with strong foundations in REST API design, application security, CI/CD, and clean architecture patterns.

---

## TECHNICAL SKILLS

**Languages:** C#, T-SQL, TypeScript, JavaScript, C++, Python, HTML5, CSS3

**Frameworks:** ASP.NET Core (.NET 8.0/10.0), MVC, Web API, Razor Pages, Web Forms, WinForms, EF Core, ASP.NET Core Identity

**Frontend:** React, Bootstrap, Vanilla JS, Responsive UI

**Database:** SQL Server, MySQL, SQLite — stored procedures, schema design, indexing, query optimisation, EF Core migrations

**Security & Auth:** Claims-based RBAC, OAuth2, ASP.NET Core Identity, IAuthorizationHandler, DynamicAuthorizationPolicyProvider, IUserClaimsPrincipalFactory

**Architecture:** Clean Architecture, Service-layer, Repository, Strategy, DI, SOLID, Microservices, async/await

**Testing:** xUnit

**Performance:** IMemoryCache, Brotli/Gzip compression, EF Core retry-on-failure, BenchmarkDotNet

**Libraries:** DocumentFormat.OpenXml 3.2, SixLabors.ImageSharp 3.1

**Tools:** Visual Studio, VS Code, Git, GitHub, IIS, Windows Server, SSMS, Postman

**Other:** REST APIs, CI/CD, Application Security, cybersecurity audit compliance, DOCX import/export, SEO metadata generation, 13-language content pipelines, health-check endpoints

---

## PROFESSIONAL EXPERIENCE

### Senior .NET Developer and Team Lead
**Press Information Bureau (NIC), Government of India** | Aug 2022 - Present | New Delhi

Led a development team modernising PIB enterprise CMS - a multi-region, multi-language government press and media platform serving national information operations.

**Leadership and Process**

* Reduced code defect rate by ~40%, as measured by post-sprint bug counts before vs after, by instituting structured code reviews, enforcing SOLID principles, and mentoring 3 junior developers on clean architecture practices.

* Aligned the CMS platform with government cybersecurity guidelines, as measured by passing the NIC security audit with zero critical findings, by collaborating with the security audit team and implementing OAuth2, claims-based access control, and secure cookie authentication.

* Managed deployment reliability across IIS and Windows Server, as measured by zero unplanned downtime incidents post-migration, by standardising deployment pipelines and environment configuration management.

**Migration and Modernisation (ASP.NET 4.0 to .NET 8.0/10.0)**

* Delivered a complete production CMS migration from ASP.NET 4.0 to .NET 8.0 MVC in under 4 months, as measured by 39+ commits and full go-live on NIC government infrastructure, by leading architecture decisions, DI wiring (Brotli/Gzip, EF Core retry, health checks), and authoring 20+ service classes and a 100+ entity relational schema.

* Improved application performance by ~60%, as measured by before/after load testing on key press release endpoints, by redesigning the modular MVC architecture, optimising EF Core queries to eliminate N+1 and OPENJSON patterns, and introducing parameterised stored-procedure calls.

* Achieved 100% unit test coverage of critical business logic, as measured by xUnit test suite pass rate, by writing unit tests for the migration service layer and enforcing test-first practices for all new modules.

**Security and Authorization**

* Architected a zero-privilege-escalation RBAC system covering 19+ CMS modules, as measured by clean security audits in production, by designing a custom DynamicAuthorizationPolicyProvider, PermissionHandler (IAuthorizationHandler), and ApplicationClaimsPrincipalFactory modelling module:{id}:{view|edit|draft|review|publish|delete} claims.

* Implemented secure authentication using ASP.NET Core Identity and OAuth2, as measured by zero authentication vulnerabilities in security reviews, by configuring Identity middleware, custom claims factory, and cookie auth redirect paths.

**Performance Engineering**

* Reduced permission-check latency by ~80%, as measured by BenchmarkDotNet profiling, by implementing an IMemoryCache-backed PermissionCacheService with Guid version-key invalidation replacing per-request database calls.

* Scaled SEO content delivery across 13 Indian languages, as measured by locale-correct Open Graph and meta-description output for every published press release, by building SeoMetadataService with a language-to-locale dictionary (en_IN to as_IN).

**Content and Integration**

* Reduced DOCX-to-CMS import time from hours to seconds, as measured by timed imports of 50+ page government documents, by integrating DocumentFormat.OpenXml 3.2 for server-side Word-to-HTML conversion.

* Achieved 100% media asset coverage across 7 platform types (YouTube, Twitter, Instagram, Facebook, PDF, Image, Document), as measured by extraction accuracy tests, by designing a Strategy-pattern IMediaExtractor pipeline.

**Stack:** C# . ASP.NET Core .NET 8.0/10.0 . EF Core . SQL Server . T-SQL . Identity . OAuth2 . TypeScript . React . Bootstrap . xUnit . IIS . Windows Server . GitHub

---

## KEY PROJECTS

**PIB CMS Migration** | github.com/PIBNIC/PIBCMS_N | Stack: C# 49%, ASP.NET 13%, JS 24%, T-SQL
* Led end-to-end migration ASP.NET 4.0 to .NET 8.0/10.0 MVC
* 19+ modules, 100+ entity schema, 7 content types, 13 language SEO
* 39+ commits, greenfield to production on NIC government infrastructure

**PIB Accreditation Portal** | github.com/PIBNIC/Accreditaion | Stack: C# 99.5%
* Journalist credential management and approval workflow system

**New India Samachar Portal** | github.com/rajputnitiket/NIS_cms | Stack: TypeScript 89%, CSS 10%
* Full CMS with role management and content workflow from scratch

**PIB Public Web Portal** | github.com/PIBNIC/PIB_WEB_USER | Stack: TypeScript 60%, CSS 38%, T-SQL 2%
* Public-facing government portal consuming PIB CMS REST APIs

---

## EDUCATION

**Bachelor of Technology - Computer Science and Engineering**
Dr. A.P.J. Abdul Kalam Technical University (AKTU), Lucknow | 2018 - 2022

---

*References available upon request*